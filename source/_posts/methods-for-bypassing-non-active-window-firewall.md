---
title: Methods for Bypassing Non-Active Window Firewall
date: 2024-08-16T00:33:29.656Z
updated: 2024-08-17T00:33:29.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods for Bypassing Non-Active Window Firewall
excerpt: This Article Describes Methods for Bypassing Non-Active Window Firewall
keywords: Firewall Workarounds,Bypass Windows Firewall,Active/Inactive FW Tactics,Circumvent Inactive FWs,Stealth FW Avoidance,Secure Firewall Bypass,Safe FW Evasion Methods
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Methods for Bypassing Non-Active Window Firewall

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-no-fuss-guide-for-exploring-loved-and-trending-youtube-comments/"><u>[New] 2024 Approved  The No-Fuss Guide for Exploring Loved and Trending YouTube Comments</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-outstanding-5-streamer-gadgets-online/"><u>[New] Outstanding 5 Streamer Gadgets Online</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-exploring-the-capabilities-of-screenflow-on-mac-devices-for-2024/"><u>[Updated] Exploring the Capabilities of ScreenFlow on Mac Devices for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-insta-followers-footprints-trail-blazing-techniques-for-2024/"><u>[Updated] Insta Followers Footprints  Trail-Blazing Techniques for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-non-vimeo-showstoppers-for-online-content-creators-for-2024/"><u>[Updated] Non-Vimeo Showstoppers for Online Content Creators for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/beyond-vimeo-a-compilation-of-premier-video-editors/"><u>Beyond Vimeo  A Compilation of Premier Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-boot-blockers-top-windows-troubleshooting-steps/"><u>Breaking Through Boot Blockers: Top Windows Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-slow-windows-excel-with-easy-fixes/"><u>Breathe Life Into Slow Windows-Excel with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-hidden-panes-6-strategies-in-win11/"><u>Breathing Life Into Hidden Panes: 6 Strategies in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-the-seven-timeless-windows-features-of-11/"><u>Bridging Generations: The Seven Timeless Windows Features of 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-platforms-apple-maps-for-windows-operating-system/"><u>Bridging Platforms: Apple Maps for Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-for-a-non-opening-command-prompt-window/"><u>Bridging the Gap for a Non-Opening Command Prompt Window</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-integrating-gmail-with-outlook-app-for-windows/"><u>Bridging the Gap: Integrating Gmail with Outlook App for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-worlds-windows-meets-kali-linux/"><u>Bridging Worlds: Windows Meets Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-steam-game-icons-quickly/"><u>Bring Back Missing Steam Game Icons Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forlorn-windows-apps-back-into-use/"><u>Bringing Forlorn Windows Apps Back Into Use</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-windows-up-to-date-key-differences-from-w10-to-w11/"><u>Bringing Windows Up to Date: Key Differences From W10 to W11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-credential-manager-lockup-in-windows/"><u>Bypass Credential Manager Lockup in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-screen-locks-for-uninterrupted-presentations/"><u>Bypass Screen Locks for Uninterrupted Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-webp-conversion-modifying-images-settings-in-chrome-windows/"><u>Bypass WebP Conversion: Modifying Images Settings in Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-while-opening-sound-device-in-audacity-for-windows/"><u>Bypassing Error While Opening Sound Device in Audacity for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-limited-wi-fi-in-windows-11-a-guide-of-8-methods/"><u>Bypassing Limited Wi-Fi in Windows 11: A Guide of 8 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-zero-error-on-windows-11/"><u>Bypassing Microsoft's Zero-Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-printer-busy-on-windows-11-systems/"><u>Bypassing Printer Busy on Windows 11 Systems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-ai-innovations-like-chatgpt-challenge-the-future-of-search-engine-relevance/"><u>Can AI Innovations Like ChatGPT Challenge the Future of Search Engine Relevance?</u></a></li>
<li><a href="https://win11.techidaily.com/cease-self-scrolling-in-your-windowed-world/"><u>Cease Self-Scrolling in Your Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/cheap-windows-key-consequences-a-warning-list/"><u>Cheap Windows Key Consequences: A Warning List</u></a></li>
<li><a href="https://win11.techidaily.com/classic-conundrum-playing-vintage-games-with-dosbox-x/"><u>Classic Conundrum: Playing Vintage Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-steam-game-accomplishments/"><u>Clean Slate for Steam Game Accomplishments</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-air-solving-microphone-problems-in-microsoft-powered-meet/"><u>Clear the Air: Solving Microphone Problems in Microsoft-Powered Meet</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-clutter-experience-unadorned-windows-11/"><u>Clear the Clutter: Experience Unadorned Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-session-verification-failure-on-your-steam-pc/"><u>Clearing Up Session Verification Failure on Your Steam PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-error-31-restoring-seamless-internet-access/"><u>Clearing Up WIN Error 31: Restoring Seamless Internet Access</u></a></li>
<li><a href="https://win11.techidaily.com/combat-non-mic-working-on-windows-headsets/"><u>Combat Non-Mic Working on Windows Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/combat-plan-against-windows-update-setback-code-0x800f080a/"><u>Combat Plan Against Windows Update Setback: Code 0X800f080a</u></a></li>
<li><a href="https://win11.techidaily.com/combating-app-not-uploading-issue-a-guide-to-microsofts-store/"><u>Combating App Not Uploading Issue: A Guide to Microsoft's Store</u></a></li>
<li><a href="https://screen-capture.techidaily.com/dive-deep-into-sims-4-gameplay-with-videography-for-2024/"><u>Dive Deep Into Sims 4 Gameplay with Videography for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Tecno Pop 7 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-breezy-video-capture-testimony/"><u>In 2024, Breezy Video Capture Testimony</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-poco-m6-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Poco M6 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-nokia-c12-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Nokia C12 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-realme-c53-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Realme C53</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207304266-no-more-stuttering-screens-just-gameplay/"><u>No More Stuttering Screens, Just Gameplay!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/skyrocket-your-channel-mastery-of-youtube-data-analysis-for-2024/"><u>Skyrocket Your Channel  Mastery of YouTube Data Analysis for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-future-of-cooling-colorful-ai-thermal-paste-by-cooler-master-powered-by-diamond-nanotechnology-for-ultimate-heat-dissipation/"><u>The Future of Cooling: Colorful AI Thermal Paste by Cooler Master, Powered by Diamond Nanotechnology for Ultimate Heat Dissipation</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-fixing-frontier-game-crashes-on-windows/"><u>Troubleshooting Tips - Fixing Frontier Game Crashes on Windows</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-oneplus-nord-n10-5g-top-reasons-to-consider-this-model/"><u>Unveiling the OnePlus Nord N10 5G - Top Reasons to Consider This Model</u></a></li>
</ul></div>
