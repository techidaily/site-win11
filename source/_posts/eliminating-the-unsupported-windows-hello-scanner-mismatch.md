---
title: Eliminating the Unsupported Windows Hello Scanner Mismatch
date: 2024-08-23T06:10:29.882Z
updated: 2024-08-24T06:10:29.882Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating the Unsupported Windows Hello Scanner Mismatch
excerpt: This Article Describes Eliminating the Unsupported Windows Hello Scanner Mismatch
keywords: Windows Hello Error Fixing,Scan Match Issue Resolution,Windows Hello Compatibility,Removing Login Failures,Overcoming Hello Scanner Issues,Correcting Hello Mismatch,Enhancing Windows Hello Security
thumbnail: https://thmb.techidaily.com/6cb4391f5b78a0bded981255e816f25b4a4f4175f4c2d7396281a9558ff75db1.jpg
---

## Eliminating the Unsupported Windows Hello Scanner Mismatch

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on[how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to[uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

## 6\. Disable Fast Startup

 According to some users on a[Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on[enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on[fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-elite-list-of-mac-tech-for-live-recording-for-2024/"><u>[New] Elite List of Mac Tech for Live Recording for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-essential-techniques-for-musical-tiktok-creation-for-2024/"><u>[New] Essential Techniques for Musical TikTok Creation for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-journey-through-games-top-5-samsung-gear-vr-experiences/"><u>[New] Journey Through Games - Top 5 Samsung Gear VR Experiences</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-next-generation-of-video-communities-post-youtube/"><u>[New] The Next Generation of Video Communities Post-YouTube</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-iciness-to-comfort-five-warm-backdrops-ideas-for-2024/"><u>[Updated] From Iciness to Comfort  Five Warm Backdrops Ideas for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-sonic-steps-to-better-snapchat-videos/"><u>[Updated] In 2024, Sonic Steps to Better Snapchat Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-instagram-intonation-blending-audio-with-imagery/"><u>[Updated] Instagram Intonation  Blending Audio with Imagery</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-joke-jugglers-androids-in-the-dead-zone/"><u>[Updated] Joke Jugglers  Androids in the Dead Zone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-navigating-the-challenges-of-remote-podcasting-for-2024/"><u>[Updated] Navigating the Challenges of Remote Podcasting for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-proven-strategies-for-powerful-customer-success-stories-on-screen-for-2024/"><u>[Updated] Proven Strategies for Powerful Customer Success Stories on Screen for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-enhancing-communication-top-4-techniques-for-fb-call-records/"><u>2024 Approved  Enhancing Communication  Top 4 Techniques for FB Call Records</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pro-chromebook-zoom-usage-techniques/"><u>2024 Approved  Pro Chromebook Zoom Usage Techniques</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-revolutionary-q500-the-ultimate-4k-bird/"><u>2024 Approved  Revolutionary Q500  The Ultimate 4K Bird</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-solving-windows-steams-e84-glitches/"><u>Comprehensive Guide to Solving Windows Steam's E84 Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-nvidia-experience-error-setting-retrieval-woes-in-windows-1011/"><u>Correcting NVIDIA Experience Error - Setting Retrieval Woes in Windows 10/11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ng-revenue-with-well-crafted-youtube-channel-trailers-for-2024/"><u>Driving Revenue with Well-Crafted YouTube Channel Trailers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/erase-ms-defender-logs-a-guide-to-cleansing-on-windows-oses/"><u>Erase MS Defender Logs: A Guide to Cleansing on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-app-blocks-system-function-problem-on-your-pc/"><u>Fixing the App Blocks System Function Problem on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-and-fixing-secure-boot-grayout-issue-in-bios/"><u>Guide to Reactivating and Fixing Secure Boot Grayout Issue in BIOS</u></a></li>
<li><a href="https://driver-error.techidaily.com/hands-on-remedy-for-disrupted-mtp-functionality/"><u>Hands-On Remedy for Disrupted MTP Functionality</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-sony-by-drfone-android/"><u>How to Bypass FRP on Sony?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-size-constraints-essential-tips-for-resizable-gifs-on-discowin11/"><u>How to Bypass Size Constraints: Essential Tips for Resizable GIFs on DiscoWin11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-malwarebytes-unable-to-connect-to-service-error-in-windows-11-and-11/"><u>How to Fix Malwarebytes’ “Unable to Connect to Service” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-from-standard-home-page-in-windows-11/"><u>How to Switch From Standard Home Page in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-triple-tactic-tracker-how-to-scrutinize-your-subscriber-earnings-on-googles-platform-youtube/"><u>In 2024, Triple Tactic Tracker  How to Scrutinize Your Subscriber Earnings on Google's Platform, YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-window-11-lock-pattern-designing-techniques/"><u>Innovative Window 11 Lock Pattern Designing Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-keystrokes-an-effective-guide-to-mending-windows-shortcut-malfunctions/"><u>Master Your Keystrokes: An Effective Guide to Mending Windows Shortcut Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fixes-handling-error-code-0x80072f17/"><u>Microsoft Store Fixes: Handling Error Code 0X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-process-of-turning-esd-files-into-windows-isos/"><u>Navigating the Process of Turning ESD Files Into Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-games-download-failures/"><u>Overcoming Xbox Games Download Failures</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-win11s-data-harvest-routines/"><u>Peering Into Win11’s Data Harvest Routines</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-lockscreen-enabledisable-image-display/"><u>Personalizing Windows Lockscreen: Enable/Disable Image Display</u></a></li>
<li><a href="https://win11.techidaily.com/re-gain-control-over-your-windows-hello-fingerprint-setup/"><u>Re-Gain Control Over Your Windows Hello Fingerprint Setup</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-insufficient-vm-ram-issue/"><u>Resolving Windows: Insufficient VM RAM Issue</u></a></li>
<li><a href="https://win11.techidaily.com/rotate-window-viewing-angle-windows-style/"><u>Rotate Window Viewing Angle Windows-Style</u></a></li>
<li><a href="https://games-able.techidaily.com/solving-component-missing-in-win-1011/"><u>Solving Component Missing in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/starting-driver-verifier-on-windows-11/"><u>Starting Driver Verifier on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-using-onedrive-offline-in-windows/"><u>Step-by-Step Guide to Using OneDrive Offline in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://fox-that.techidaily.com/struggle-no-more-10-essential-fixes-when-iphones-fail-to-download-new-applications/"><u>Struggle No More: 10 Essential Fixes When iPhones Fail To Download New Applications</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-gpu-load-and-strain-in-windows-our-top-6-tool-list/"><u>Tackling GPU Load & Strain in Windows: Our Top 6 Tool List</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-separating-concentrated-pc-icons/"><u>Techniques for Separating Concentrated PC Icons</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-leading-hubs-for-online-interaction-exploring-facebook-twitter-instagram-and-youtube/"><u>The Leading Hubs for Online Interaction: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-for-broken-windows-google-nearby-share/"><u>Troubleshooting Guide for Broken Windows Google Nearby Share</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-win-10-and-11-phishing-alerts/"><u>Turning On/Off Win 10 & 11 Phishing Alerts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/unlock-movie-magic-with-cg-centrals-look-up-tables-luts/"><u>Unlock Movie Magic with CG Central's Look-Up Tables (Luts)</u></a></li>
<li><a href="https://win11.techidaily.com/vanishing-act-the-art-of-eliminating-taskbar-linguistics/"><u>Vanishing Act: The Art of Eliminating Taskbar Linguistics</u></a></li>
<li><a href="https://extra-information.techidaily.com/view-count-visionaries-strategies-for-huge-traffic/"><u>View Count Visionaries  Strategies for Huge Traffic</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-crafting-a-distinctive-user-interface/"><u>Windows 11: Crafting a Distinctive User Interface</u></a></li>
<li><a href="https://win11.techidaily.com/windows-voice-conversion-made-easy-using-whisper/"><u>Windows Voice Conversion Made Easy Using Whisper</u></a></li>
</ul></div>
