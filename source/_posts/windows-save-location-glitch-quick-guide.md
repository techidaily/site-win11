---
title: "Windows Save Location Glitch: Quick Guide"
date: 2024-08-16T00:08:33.138Z
updated: 2024-08-17T00:08:33.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Save Location Glitch: Quick Guide"
excerpt: "This Article Describes Windows Save Location Glitch: Quick Guide"
keywords: Windows Save Issue,Fixing Saves Error,Save Locations Bug,Quick Save Guide,Windows Troubleshooting,Resolve Save Glitch,Windows Save Paths
thumbnail: https://thmb.techidaily.com/ff0e2bc796f68a77c989442115175dff38598efbd629d2e9e9c88ebc255585bb.jpg
---

## Windows Save Location Glitch: Quick Guide

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/mplify-your-video-content-with-precision-insights-from-social-blade-and-youtube/"><u>[New] Amplify Your Video Content with Precision Insights From Social Blade & YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-elevate-your-social-score-best-tools-for-post-and-engagement/"><u>[New] Elevate Your Social Score  Best Tools for Post and Engagement</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-enhancing-speed-for-vimeo-playback/"><u>[Updated] Enhancing Speed for Vimeo Playback</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-recovery-drive-tool/"><u>10 Ways to Open the Windows Recovery Drive Tool</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-textual-brilliance-in-media-exploring-the-best-effects/"><u>2024 Approved  Textual Brilliance in Media  Exploring the Best Effects</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-bittorrent-tools-for-windows-users/"><u>5 Superior BitTorrent Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-accessing-windows-odbc-tools/"><u>A Beginner's Guide to Accessing Windows' ODBC Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-removable-storage-via-explore-navigation-menu/"><u>Adding Removable Storage via Explore Navigation Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x8007000f-on-task-sequences/"><u>Addressing Windows Error 0X8007000f on Task Sequences</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-brightness-control-software-for-windows-multiscreen-enthusiasts/"><u>Advanced Brightness Control Software for Windows Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-volume-control-on-windows-bluetooth/"><u>Amplifying Volume Control on Windows-Bluetooth</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-sonic-full-screen-pitfalls-on-windows-11-os/"><u>Avoiding Sonic Full-Screen Pitfalls on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blues-effective-methods-for-hybrid-os-errors-in-winxose/"><u>Beat the Blues: Effective Methods for Hybrid OS Errors in WINXOSE</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/best-anti-tracker-software-for-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>Best Anti Tracker Software For Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://win11.techidaily.com/blending-gmail-with-outlook-on-windows-comprehensive-guide/"><u>Blending Gmail with Outlook on Windows: Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-system-with-these-5-ease-access-tricks/"><u>Boost Your System with These 5 Ease Access Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-task-power-top-5-apps-to-enhance-window-11-workflow/"><u>Boosting Task Power: Top 5 Apps to Enhance Window 11 Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-overturning-monochrome-windows-display/"><u>Breaking Free: Overturning Monochrome Windows Display</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-samsung-galaxy-s23-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-tecno-pop-7-pro-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Tecno Pop 7 Pro Phone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-6-plus-with-7-methods-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 6 Plus With 7 Methods</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-infinix-smart-8-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Infinix Smart 8 Phone Hassle-Free</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mapping-your-marketing-journey-on-youtube-for-2024/"><u>Mapping Your Marketing Journey on YouTube for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/quick-fame-quest-mastering-content-video-and-likes-for-2024/"><u>Quick Fame Quest - Mastering Content, Video, and Likes for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-pc-performance-fixing-valheims-freezing-and-stuttering-issues/"><u>Troubleshooting PC Performance: Fixing Valheim's Freezing & Stuttering Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-how-to-repair-unresponsive-dvd-bd-and-cd-drives/"><u>Troubleshooting Tips: How to Repair Unresponsive DVD, BD & CD Drives</u></a></li>
<li><a href="https://video-capture.techidaily.com/unlocking-the-power-of-voice-transcription-in-whatsapp-recording-for-2024/"><u>Unlocking the Power of Voice Transcription in WhatsApp Recording for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveiling-the-secrets-to-blurring-iphone-photos-a-comprehensive-guide/"><u>Unveiling the Secrets to Blurring iPhone Photos  A Comprehensive Guide</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-meizu-21-pro-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Meizu 21 Pro Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719325788950-windows-users-create-a-self-hosted-free-chatgpt-copy-with-gpt4all/"><u>Windows Users, Create a Self-Hosted Free ChatGPT Copy with GPT4All.</u></a></li>
</ul></div>
