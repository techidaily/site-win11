---
title: "The Illusion of Choice: Confronting Microphone and Camera Shackles"
date: 2024-08-16T00:50:08.707Z
updated: 2024-08-17T00:50:08.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Illusion of Choice: Confronting Microphone and Camera Shackles"
excerpt: "This Article Describes The Illusion of Choice: Confronting Microphone and Camera Shackles"
keywords: Microscope Limits,Camcorder Confinement,Unseen Restrictions,Photo & Audio Controls,Choice Illusion,Tech Freedom Bound,Digital Shackles
thumbnail: https://thmb.techidaily.com/e3cf30b4720656ba32f87d0a36d739d3e594003c967c2e7d28e98120dd95b14e.jpg
---

## The Illusion of Choice: Confronting Microphone and Camera Shackles

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://twitter-videos.techidaily.com/new-exclusive-content-on-twitter-no-twitting/"><u>[New] Exclusive Content on Twitter - No Twitting</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-drive-participation-with-artisanal-story-inquiries/"><u>[New] In 2024, Drive Participation with Artisanal Story Inquiries</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-harmonize-visuals-and-melodies-in-facebook-media-posts/"><u>[Updated] In 2024, Harmonize Visuals & Melodies in Facebook Media Posts</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-50-clever-tiktok-gags-for-laughter/"><u>2024 Approved  50 Clever TikTok Gags for Laughter</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-winupdate-failure-x8019-error/"><u>Correcting WinUpdate Failure: X8019 Error</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-not-empty-directive-with-error-x80070091-fixes/"><u>Disabling Windows' Not Empty Directive with Error X80070091 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/effective-steps-to-update-login-credentials-on-win-11/"><u>Effective Steps to Update Login Credentials on Win 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/effortless-internal-sound-recording-in-android-for-2024/"><u>Effortless Internal Sound Recording in Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-phone-tethering-experience-in-windows-11-era/"><u>Elevating Phone Tethering Experience in Windows 11 Era</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-fixing-incomplete-network-commands-on-pc/"><u>Enhancing Wi-Fi Connectivity: Fixing Incomplete Network Commands on PC</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-address-unresponsive-spotify-windows/"><u>Essential Steps to Address Unresponsive Spotify Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exclude-non-critical-windows-suggestions-and-tips/"><u>Exclude Non-Critical Windows Suggestions and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-windows-11-a-compreenas-list-of-must-have-modifications/"><u>Fine-Tuning Windows 11: A Compreenas List of Must-Have Modifications</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-raw-footage-to-stunning-visuals-using-luts-in-obs-studio/"><u>From Raw Footage to Stunning Visuals  Using LUTs in OBS Studio</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-eliminate-microsoft-offices-error-code-0x80041015/"><u>Guide to Eliminate Microsoft Office's Error Code 0X80041015</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-motorola-moto-g34-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Motorola Moto G34 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-character-map-in-windows-11/"><u>How to Open the Character Map in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-y78t-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-high-gear-comparison-gopros-best-match-ghost-s-drift/"><u>In 2024, High Gear Comparison  GoPro's Best Match? Ghost-S Drift</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-oppo-find-x7-ultra-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Oppo Find X7 Ultra Phone that is Locked?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Oppo Find X7 Ultra? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-testing-top-120mm-aio-cpu-coolers-from-be-quiet-corsair-cooler-master-and-enermax-compared/"><u>In-Depth Testing: Top 120MM AIO CPU Coolers From Be Quiet, Corsair, Cooler Master, and Enermax Compared</u></a></li>
<li><a href="https://win11.techidaily.com/latency-less-viewing-optimizing-winx-media-with-these-fixes/"><u>Latency-Less Viewing: Optimizing WinX Media with These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mending-erratic-touchpad-movements-in-windows/"><u>Mending Erratic Touchpad Movements in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mending-inactive-mail-signals-for-outlook-users/"><u>Mending Inactive Mail Signals for Outlook Users</u></a></li>
<li><a href="https://win11.techidaily.com/network-prowess-4-tactics-to-measure-ethernet-speed-on-windows/"><u>Network Prowess: 4 Tactics to Measure Ethernet Speed on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-fixing-spotify-errors-on-win11/"><u>Overcoming the Hurdles: Fixing Spotify Errors on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-cant-access-mail-error-in-windows-11-email-service/"><u>Rectifying Can't Access Mail Error in Windows 11 Email Service</u></a></li>
<li><a href="https://driver-install.techidaily.com/resolving-software-compatibility-problems-in-windows/"><u>Resolving Software Compatibility Problems in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-non-working-filesystem-consolidator/"><u>Reversing Non-Working Filesystem Consolidator</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sensors-windows-based-methods-for-examining-network-rate/"><u>Speed Sensors: Windows-Based Methods for Examining Network Rate</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/steps-for-successful-extraction-of-fb-content-for-2024/"><u>Steps for Successful Extraction of FB Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-device-not-found-error-when-connecting-usb-to-virtualbox/"><u>Steps to Rectify 'Device Not Found' Error When Connecting USB to VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-stop-video-resets-on-win1110-devices/"><u>Strategies to Stop Video Resets on Win11/10 Devices</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-nubia-z50s-pro-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Nubia Z50S Pro ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-symbiosis-navigating-github-desktop-and-windows-11/"><u>The Perfect Symbiosis: Navigating GitHub Desktop & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-review-the-ultimate-guide-to-garmin-forerunner-745-for-multisports-enthusiasts/"><u>Top Review: The Ultimate Guide to Garmin Forerunner 745 for Multisports Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-gaming-combat-0x00000001-on-pcs/"><u>Unfreezing Gaming: Combat 0X00000001 on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unpackaging-problems-solved-fixing-windows-package-not-open-errors/"><u>Unpackaging Problems Solved: Fixing Windows Package Not Open Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-drives-c-and-d/"><u>Unraveling the Mystery of Windows Drives (C & D)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-innovation-four-revolutionary-updates-for-paint/"><u>Unveiling Innovation: Four Revolutionary Updates for Paint</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-bt-folders/"><u>Unveiling the Mystery of Windows ~BT Folders</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-the-run-command-wont-save-history-on-windows/"><u>What to Do When the Run Command Won’t Save History on Windows</u></a></li>
</ul></div>
