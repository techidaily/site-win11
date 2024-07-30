---
title: "Clarifying Windows Tools: What Makes WinTools's CHKDSK Unique?"
date: 2024-07-29T15:53:33.397Z
updated: 2024-07-30T15:53:33.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Clarifying Windows Tools: What Makes WinTools's CHKDSK Unique?"
excerpt: "This Article Describes Clarifying Windows Tools: What Makes WinTools's CHKDSK Unique?"
keywords: WinDiskCheckerUniqueFeatures,CHKDSKWinToolsExclusivity,CHKDSKWindowsDifferentiator,CHKDSKWinToolsOverview,UniqueCHKDSKFeatureSet,WindowsToolsCHKDSKCompare,WinToolCHKDSKSpecificity
thumbnail: https://thmb.techidaily.com/dcd52c68a0261301dc49a434565ff933798115ab3a2be4caf338af3c874b626b.jpg
---

## Clarifying Windows Tools: What Makes WinTools's CHKDSK Unique?

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-enhancing-your-iphone-experience-voice-memo-techniques/"><u>[New] Enhancing Your iPhone Experience  Voice Memo Techniques</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-your-step-by-step-equipment-plan-for-youtube-beginnings/"><u>[New] In 2024, Your Step-by-Step Equipment Plan for YouTube Beginnings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-roadmap-to-youtube-fame-accruing-more-subscribers/"><u>[New] The Roadmap to YouTube Fame  Accruing More Subscribers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-premium-console-emulation-choosing-the-top-5-for-windows/"><u>[Updated] 2024 Approved  Premium Console Emulation  Choosing the Top 5 for Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-boost-your-fb-ads-strategy-get-free-video-making-kit-for-2024/"><u>[Updated] Boost Your FB Ads Strategy  Get Free Video-Making Kit for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-digital-discussion-documentary-vault/"><u>[Updated] Digital Discussion Documentary Vault</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-high-end-sound-pumping-tools-pcs-and-smartphones/"><u>[Updated] In 2024, High-End Sound Pumping Tools  PCs & Smartphones</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-understanding-the-impact-of-nikon-d500s-4k-output/"><u>[Updated] Understanding the Impact of Nikon D500's 4K Output</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-20-timeless-anime-themes-making-a-mark-on-tiktok/"><u>2024 Approved  20 Timeless Anime Themes Making a Mark on TikTok</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-techniques-for-sharing-srt-data-on-vimeo-and-linkedin/"><u>2024 Approved  Advanced Techniques for Sharing SRT Data on Vimeo and LinkedIn</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-boost-your-photo-skills-with-these-top-pixlr-tricks/"><u>2024 Approved  Boost Your Photo Skills with These Top Pixlr Tricks</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-instant-reddit-history-retrieval-for-deleted-threads/"><u>2024 Approved  Instant Reddit History Retrieval for Deleted Threads</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/3-top-notch-smartphones-excelling-at-video-capture-for-2024/"><u>3 Top-Notch Smartphones Excelling at Video Capture for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-devices-performance-naturally-with-wintoys/"><u>Accelerate Your Device's Performance Naturally with WinToys</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-older-directx-applications-through-dxvk-transformation/"><u>Bolstering Older DirectX Applications Through DXVK Transformation</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-breakdown-hero4-black-functionality-for-2024/"><u>Complete Breakdown  Hero4 Black Functionality for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://win11.techidaily.com/cpu-age-determination-for-pc-users-8-effective-methods/"><u>CPU Age Determination for PC Users: 8 Effective Methods</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-cross-language-interactions-with-keyboard-shortcuts-on-windows-11/"><u>Enhance Cross-Language Interactions with Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-in-windows-11-after-disruptions/"><u>Enhancing Wi-Fi Connectivity in Windows 11 After Disruptions</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-infinix-smart-8-hd-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/groundbreaking-gear-for-next-level-virtual-reality-for-2024/"><u>Groundbreaking Gear for Next-Level Virtual Reality for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/handling-the-mysterious-windows-subsystem-for-linux-error-4294967295/"><u>Handling the Mysterious Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/how-to-auto-translate-youtube-videos-into-different-languages-for-2024/"><u>How To Auto Translate YouTube Videos Into Different Languages for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-1111/"><u>How to Install Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-lighten-load-time-for-epic-games-on-windows/"><u>How to Lighten Load Time for Epic Games on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-up-advanced-security-features-ms-defender-aguard-for-windows-11-edge/"><u>How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-for-frozen-keys-in-snipping-tool/"><u>Immediate Solution for Frozen Keys in Snipping Tool</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-elite-firefox-screencap-add-ons/"><u>In 2024, Elite Firefox Screencap Add-Ons</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-windows-11-registry-file-layout/"><u>Mastering the Windows 11 Registry File Layout</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-savings-with-windows-11-pro-secure-top-deals/"><u>Maximize Savings with Windows 11 Pro: Secure Top Deals</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-mcuicnt-file-access-problem-on-pcs/"><u>Mitigating McUICnt File Access Problem on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-the-maze-of-unspecified-obs-error-in-windows/"><u>Navigate Through the Maze of Unspecified OBS Error in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/navigating-screencastifys-screen-capture-feature/"><u>Navigating Screencastify's Screen Capture Feature</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-intelligence-of-microsofts-marketplace/"><u>Navigating the Intelligence of Microsoft's Marketplace</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-free-movie-making-magic-top-16-picks-for-2024/"><u>New Free Movie Making Magic Top 16 Picks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hyper-v-error-0x8009030e/"><u>Overcoming Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-functional-shortcuts-cure-errors-in-win-11/"><u>Rectify: Functional Shortcuts - Cure Errors in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-system-call-failure-in-win1011-systems/"><u>Remedying System Call Failure in Win10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-normalcy-after-windows-video-failures/"><u>Restoring Normalcy After Windows Video Failures</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mfc71udll-absence-in-windows-os/"><u>Solving Mfc71u.dll Absence in Windows OS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-to-premium-audio-with-audacity-for-2024/"><u>Step-by-Step to Premium Audio with Audacity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-change-your-windows-11-username/"><u>Steps to Change Your Windows 11 Username</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sticky-notebook-convergence-on-win11/"><u>Streamlining Sticky Notebook Convergence on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-screenshot-feature-to-suit-your-preferences/"><u>Tailor Windows Screenshot Feature to Suit Your Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/tech-savvy-collectors-dream-essential-612lifetime-windows-11-deal-awaits/"><u>Tech-Savvy Collectors' Dream: Essential $6.12/Lifetime Windows 11 Deal Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-keep-word-reading-mode-active-when-handling-email-attachments/"><u>Tips to Keep Word Reading Mode Active When Handling Email Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-user-experience-in-windows-11/"><u>Transforming User Experience in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-inability-to-remove-apps/"><u>Troubleshooting Windows' Inability to Remove Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unhighlight-your-windows-11-desktop-with-ease/"><u>Unhighlight Your Windows 11 Desktop with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-solutions-for-error-0x800704b3-in-windows-11-and-11/"><u>Unlocking Solutions for Error 0X800704B3 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-rapid-notification-curbing-guide/"><u>Windows 11: Rapid Notification Curbing Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winter-wonderland-offering-apps-from-microsofts-store/"><u>Winter Wonderland: Offering Apps From Microsoft's Store</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>