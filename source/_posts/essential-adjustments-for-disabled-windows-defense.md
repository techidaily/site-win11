---
title: Essential Adjustments for Disabled Window's Defense
date: 2024-08-23T06:06:45.906Z
updated: 2024-08-24T06:06:45.906Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Adjustments for Disabled Window's Defense
excerpt: This Article Describes Essential Adjustments for Disabled Window's Defense
keywords: Disabled Window Safety,Accessible Window Locks,Inclusive Window Barriers,Easy Window Guards,Assistive Window Protection,Adapted Window Security,Universal Window Guarding
thumbnail: https://thmb.techidaily.com/fe3425cd8bd2ff0c1232de1bab83bce21e82181cb81ffb7e2c2a0692c27f7927.png
---

## Essential Adjustments for Disabled Window's Defense

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

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-beat-matching-visuals-and-audio-on-facebook-platform/"><u>[New] 2024 Approved  Beat-Matching Visuals & Audio on Facebook Platform</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-cam-problem-solved-operation-normal/"><u>[New] 2024 Approved  Cam Problem Solved  Operation Normal</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-socialsnatcher-grab-and-save-twitter-vids-in-a-flash/"><u>[New] In 2024, SocialSnatcher  Grab and Save Twitter Vids in a Flash</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-break-free-from-linearity-mastering-jump-cut-transitions/"><u>[Updated] Break Free From Linearity  Mastering Jump Cut Transitions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-setting-benchmarks-a-look-at-successful-igtv-videos/"><u>[Updated] In 2024, Setting Benchmarks  A Look at Successful IGTV Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-step-by-step-guide-to-optimal-screen-casting-via-meet/"><u>[Updated] Step-by-Step Guide to Optimal Screen Casting via Meet</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-trending-14-moving-text-design-illustrations/"><u>[Updated] Trending 14 Moving Text Design Illustrations</u></a></li>
<li><a href="https://iphone-location.techidaily.com/a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-11-proipad-drfone-by-drfone-virtual-ios/"><u>A Full Review for iTools Virtual Location and Top 5 Alternatives For Apple iPhone 11 Pro/iPad | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-solving-windows-steams-e84-glitches/"><u>Comprehensive Guide to Solving Windows Steam's E84 Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-nvidia-experience-error-setting-retrieval-woes-in-windows-1011/"><u>Correcting NVIDIA Experience Error - Setting Retrieval Woes in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/erase-ms-defender-logs-a-guide-to-cleansing-on-windows-oses/"><u>Erase MS Defender Logs: A Guide to Cleansing on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-app-blocks-system-function-problem-on-your-pc/"><u>Fixing the App Blocks System Function Problem on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-and-fixing-secure-boot-grayout-issue-in-bios/"><u>Guide to Reactivating and Fixing Secure Boot Grayout Issue in BIOS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-does-claude-pro-stack-up-against-chatgpt-plus-in-natural-language-processing/"><u>How Does Claude Pro Stack Up Against ChatGPT Plus in Natural Language Processing?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-size-constraints-essential-tips-for-resizable-gifs-on-discowin11/"><u>How to Bypass Size Constraints: Essential Tips for Resizable GIFs on DiscoWin11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-to-mp4-for-samsung-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD MTS to MP4 for Samsung ?</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-remove-your-apple-id-permanently-from-iphone-12-pro-max-by-drfone-ios/"><u>How To Delete iCloud Account Remove Your Apple ID Permanently From iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-malwarebytes-unable-to-connect-to-service-error-in-windows-11-and-11/"><u>How to Fix Malwarebytes’ “Unable to Connect to Service” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-from-standard-home-page-in-windows-11/"><u>How to Switch From Standard Home Page in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-on-your-iphone-8-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID On your iPhone 8 without Security Questions?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-essentials-of-using-igtv-effectively-and-efficiently/"><u>In 2024, Essentials of Using IGTV Effectively and Efficiently</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-honor-magic-vs-2-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Honor Magic Vs 2 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-samsung-galaxy-a14-4g-easily-by-drfone-android/"><u>In 2024, How To Unlock a Samsung Galaxy A14 4G Easily?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-window-11-lock-pattern-designing-techniques/"><u>Innovative Window 11 Lock Pattern Designing Techniques</u></a></li>
<li><a href="https://review-topics.techidaily.com/lava-blaze-2-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Lava Blaze 2 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-control-rgb-lighting-in-windows-11/"><u>Learn to Control RGB Lighting in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-keystrokes-an-effective-guide-to-mending-windows-shortcut-malfunctions/"><u>Master Your Keystrokes: An Effective Guide to Mending Windows Shortcut Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fixes-handling-error-code-0x80072f17/"><u>Microsoft Store Fixes: Handling Error Code 0X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-process-of-turning-esd-files-into-windows-isos/"><u>Navigating the Process of Turning ESD Files Into Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-games-download-failures/"><u>Overcoming Xbox Games Download Failures</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-win11s-data-harvest-routines/"><u>Peering Into Win11’s Data Harvest Routines</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-lockscreen-enabledisable-image-display/"><u>Personalizing Windows Lockscreen: Enable/Disable Image Display</u></a></li>
<li><a href="https://win11.techidaily.com/re-gain-control-over-your-windows-hello-fingerprint-setup/"><u>Re-Gain Control Over Your Windows Hello Fingerprint Setup</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-insufficient-vm-ram-issue/"><u>Resolving Windows: Insufficient VM RAM Issue</u></a></li>
<li><a href="https://win11.techidaily.com/rotate-window-viewing-angle-windows-style/"><u>Rotate Window Viewing Angle Windows-Style</u></a></li>
<li><a href="https://win11.techidaily.com/starting-driver-verifier-on-windows-11/"><u>Starting Driver Verifier on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-using-onedrive-offline-in-windows/"><u>Step-by-Step Guide to Using OneDrive Offline in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-gpu-load-and-strain-in-windows-our-top-6-tool-list/"><u>Tackling GPU Load & Strain in Windows: Our Top 6 Tool List</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-separating-concentrated-pc-icons/"><u>Techniques for Separating Concentrated PC Icons</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-for-broken-windows-google-nearby-share/"><u>Troubleshooting Guide for Broken Windows Google Nearby Share</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-win-10-and-11-phishing-alerts/"><u>Turning On/Off Win 10 & 11 Phishing Alerts</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-techniques-for-creating-full-sphere-photos-for-2024/"><u>Ultimate Techniques for Creating Full-Sphere Photos for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-features-of-imo-instant-messaging-a-detailed-assessment/"><u>Unveiling the Features of Imo Instant Messaging - A Detailed Assessment</u></a></li>
<li><a href="https://win11.techidaily.com/vanishing-act-the-art-of-eliminating-taskbar-linguistics/"><u>Vanishing Act: The Art of Eliminating Taskbar Linguistics</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-crafting-a-distinctive-user-interface/"><u>Windows 11: Crafting a Distinctive User Interface</u></a></li>
<li><a href="https://win11.techidaily.com/windows-voice-conversion-made-easy-using-whisper/"><u>Windows Voice Conversion Made Easy Using Whisper</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>