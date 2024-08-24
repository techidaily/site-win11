---
title: Enable Handwritten Entry on Windows Using Simple Steps
date: 2024-08-23T06:08:19.267Z
updated: 2024-08-24T06:08:19.267Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Handwritten Entry on Windows Using Simple Steps
excerpt: This Article Describes Enable Handwritten Entry on Windows Using Simple Steps
keywords: Handwritten Input Windows,Enable Writing Windows,Handwriting Windows,Windows Write Entry,Simple Windows Entry,Easy Windows Handwrite,Windows Input Method
thumbnail: https://thmb.techidaily.com/d68b2c77d9bc6992a97b4d45a79ba7275bc346cfc58c9a3e57e1e4c2f555ef0b.jpg
---

## Enable Handwritten Entry on Windows Using Simple Steps

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-facebooks-videography-preference-which-orientation/"><u>[New] 2024 Approved  Facebook's Videography Preference  Which Orientation?</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-ultimate-countdown-best-zombie-games-ranked/"><u>[New] 2024 Approved  The Ultimate Countdown  Best Zombie Games Ranked</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-precision-in-video-documentation-windowsosxiphone-methods/"><u>[New] In 2024, Precision in Video Documentation  Windows/OSX/iPhone Methods</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-iconic-acting-peek-vimeo/"><u>[Updated] Iconic Acting Peek - Vimeo</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-generate-individual-meme-crafts-today/"><u>2024 Approved  Generate Individual Meme Crafts Today</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mirrorless-vs-dslr-video-mastery-in-focus/"><u>2024 Approved  Mirrorless vs DSLR  Video Mastery in Focus</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-precision-in-screenshots-a-detailed-guide/"><u>2024 Approved  Precision in Screenshots  A Detailed Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-subscription-surge-entry-into-monetization-realm/"><u>2024 Approved  Subscription Surge  Entry Into Monetization Realm</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/behind-the-scenes-iphone-video-loops-unveiled/"><u>Behind the Scenes  IPhone Video Loops Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-manage-app-packages-with-winget-on-win11/"><u>Comprehensively Manage App Packages with Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-display-not-responding-on-windows-11/"><u>Correcting 'Display Not Responding' On Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/digital-chromatic-conventions-in-media-production/"><u>Digital Chromatic Conventions in Media Production</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-strategies-for-resolving-kernel32dll-problems-on-your-pc/"><u>Effective Strategies for Resolving Kernel32.dll Problems on Your PC</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/effortless-mp4-conversion-from-facebook-hd-content-all-for-free/"><u>Effortless MP4 Conversion From Facebook HD Content – All For Free</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-multi-monitor-use-with-these-windows-11-tips/"><u>Effortless Multi-Monitor Use with These Windows 11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-system-speed-through-virtual-memory-management/"><u>Elevating System Speed Through Virtual Memory Management</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-utilizing-condensed-explorer-settings/"><u>Enhance Visibility: Utilizing Condensed Explorer Settings</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-for-repairing-system-files-in-win11/"><u>Essential Techniques for Repairing System Files in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-hyper-v-error-0x8009030e-in-windows/"><u>How to Fix the Hyper-V Error 0X8009030E in Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-installupdate-hp-laptop-device-drivers-in-windows-step-by-step-guide/"><u>How to Install/Update HP Laptop Device Drivers in Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-error-0x800700e1-in-windows-11-os/"><u>How to Overcome Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-sleep-on-win11/"><u>How to Reactivate Sleep on Win11?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-show-or-hide-folders-in-this-pc-on-windows-11/"><u>How to Show or Hide Folders in This PC on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-on-your-iphone-8-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID On your iPhone 8 without Security Questions?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-x50-gt-phone-without-google-account-by-drfone-android/"><u>How to Unlock Honor X50 GT Phone without Google Account?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/immediate-insta-friendship-status-check/"><u>Immediate Insta Friendship Status Check</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-lava-blaze-2-pro-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Lava Blaze 2 Pro to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-look-at-the-ampace-andes-150cu-portable-power-unit-performance-and-convenience-combined/"><u>In-Depth Look at the Ampacē Andes 150Cu Portable Power Unit: Performance and Convenience Combined</u></a></li>
<li><a href="https://win11.techidaily.com/insight-computing-through-time-with-windows/"><u>Insight: Computing Through Time with Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-open-conversations-windows-freedomgpt/"><u>Mastering Open Conversations: Windows FreedomGPT</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-laptop-battery-with-simple-onoff-tweaks/"><u>Maximize Laptop Battery with Simple On/Off Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-auto-updates-and-change-amd-gpu-drives-in-win10/"><u>Navigate Auto-Updates & Change AMD GPU Drives in Win10</u></a></li>
<li><a href="https://win11.techidaily.com/reinforcing-operational-capabilities-of-windows-problem-solvers/"><u>Reinforcing Operational Capabilities of Windows Problem Solvers</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-the-clear-edge-tips-to-rectify-blurry-win11-displays/"><u>Reveal the Clear Edge: Tips to Rectify Blurry Win11 Displays</u></a></li>
<li><a href="https://extra-hints.techidaily.com/seamless-transitions-the-art-of-editing-with-garagebands-power-tools/"><u>Seamless Transitions  The Art of Editing with GarageBand's Power Tools</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-modify-program-size-on-windows-11/"><u>Simplified Techniques to Modify Program Size on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-clear-vac-failed-windows-error/"><u>Solutions to Clear VAC Failed Windows Error</u></a></li>
<li><a href="https://win11.techidaily.com/solving-x80780119-error-windows-system-restore/"><u>Solving X80780119 Error: Windows System Restore</u></a></li>
<li><a href="https://win11.techidaily.com/start-with-windows-basic-tools-for-new-users/"><u>Start with Windows: Basic Tools for New Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-rectify-windows-error-code-30005-create-failure/"><u>Strategies to Rectify Windows Error Code: 30005 Create Failure</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-operations-with-process-insight-and-elegant-theming-in-windows-11/"><u>Streamline Operations with Process Insight and Elegant Theming in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamline-your-video-projects-using-movie-maker-on-windows-8/"><u>Streamline Your Video Projects  Using Movie Maker on Windows 8</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-group-policies-in-windows-environments/"><u>Streamlining Group Policies in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/stuck-xbox-on-windows-heres-how-to-unlock-it/"><u>Stuck Xbox on Windows? Here's How to Unlock It</u></a></li>
<li><a href="https://win11.techidaily.com/taming-technology-turmoil-essential-techniques-for-windows-application-resets/"><u>Taming Technology Turmoil: Essential Techniques for Windows Application Resets</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-approach-to-unlock-your-start-menu-potential-in-windows-11/"><u>The Ultimate Approach to Unlock Your Start Menu Potential in Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/uality-video-summaries-with-smart-templates-for-2024/"><u>Top-Quality Video Summaries with Smart Templates for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-0x80-grove-2f8f-error-in-windows-11-and-10/"><u>Troubleshooting the 0X80 Grove 2F8f Error in Windows 11 and 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-tips-downloading-and-setting-up-your-dell-mouse-driver-correctly/"><u>Troubleshooting Tips - Downloading and Setting Up Your Dell Mouse Driver Correctly</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unreachable-ms-sql-server-for-malwarebytes-on-win-1011/"><u>Troubleshooting Unreachable MS SQL Server for Malwarebytes on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unifying-computing-windows-adapts-to-iphones-ipads-macs-and-desktops/"><u>Unifying Computing: Windows Adapts to iPhones, iPads, Macs, and Desktops</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/k-the-power-of-beginnings-with-imovies-creative-tools/"><u>Unlock the Power of Beginnings with iMovie's Creative Tools</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-hands-on-with-avs-video-editor-a-2023-review/"><u>Updated In 2024, Hands-On with AVS Video Editor A 2023 Review</u></a></li>
<li><a href="https://win11.techidaily.com/where-windows-keeps-your-image-snaps/"><u>Where Windows Keeps Your Image Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/winrar-file-integrity-6-strategies-for-checksum-precision/"><u>WinRAR File Integrity: 6 Strategies for Checksum Precision</u></a></li>
<li><a href="https://win11.techidaily.com/worldwide-unity-windows-encompasses-iphoneipad-macpc-communities/"><u>Worldwide Unity: Windows Encompasses iPhone/iPad, Mac/PC Communities</u></a></li>
</ul></div>
