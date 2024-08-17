---
title: "Swift and Simple Fixes: Conquer WinError 740 on WINOS"
date: 2024-08-16T00:53:53.204Z
updated: 2024-08-17T00:53:53.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Swift and Simple Fixes: Conquer WinError 740 on WINOS"
excerpt: "This Article Describes Swift and Simple Fixes: Conquer WinError 740 on WINOS"
keywords: WinError Solutions,Error 740 Remedies,Swift WinError Fix,Simplify WinError X,Conquer SystemErrors,Quick WinError Resolve,Easy WinError Troubleshoot
thumbnail: https://thmb.techidaily.com/2ee7691e7273eb11818d41a9cf81a37cef10bbda58003f87ccdd98d9756a0aeb.jpg
---

## Swift and Simple Fixes: Conquer WinError 740 on WINOS

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-the-fbx-game-recorder-playbook/"><u>[New] 2024 Approved  The FBX Game Recorder Playbook</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-transforming-video-files-to-mp3-a-focused-guide-for-pinterest-users/"><u>[New] 2024 Approved  Transforming Video Files to MP3  A Focused Guide for Pinterest Users</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-twitter-media-upload-instruction-manual/"><u>[New] 2024 Approved  Twitter Media Upload Instruction Manual</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-viewer-friendly-approach-implementing-commentary-and-alerts-on-youtube/"><u>[New] In 2024, A Viewer-Friendly Approach  Implementing Commentary and Alerts on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-recovery-drive-tool/"><u>10 Ways to Open the Windows Recovery Drive Tool</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-android-and-iphones-essential-apps-to-elevate-fb-likes-count-quickly/"><u>2024 Approved  Android & iPhone's Essential Apps to Elevate FB Likes Count Quickly</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-mastering-sound-on-your-apple-device-top-picks/"><u>2024 Approved  Mastering Sound on Your Apple Device (Top Picks)</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-top-10-best-4k-camera-phone/"><u>2024 Approved  Top 10 Best 4K Camera Phone</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-find-the-mac-address-on-windows-11/"><u>4 Ways to Find the MAC Address on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/6-android-apps-perfect-for-a-windows-11-enthusiast/"><u>6 Android Apps Perfect for a Windows 11 Enthusiast</u></a></li>
<li><a href="https://win11.techidaily.com/6-polarizing-windows-features-that-are-gone-for-good/"><u>6 Polarizing Windows Features That Are Gone for Good</u></a></li>
<li><a href="https://win11.techidaily.com/7-fixes-to-try-when-waterfox-is-not-loading-webpages-on-windows/"><u>7 Fixes to Try When Waterfox Is Not Loading Webpages on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-black-desktop-background-display-issue-on-windows/"><u>8 Ways to Fix the Black Desktop Background Display Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-accessing-windows-odbc-tools/"><u>A Beginner's Guide to Accessing Windows' ODBC Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-of-the-most-reliable-window-pomodoros-for-work/"><u>A Compreenas of The Most Reliable Window Pomodoros for Work</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-stopping-blued-in-windows-10/"><u>A Step-by-Step Guide to Stopping Blued in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/a-stepwise-approach-to-win11s-hyper-v-activation/"><u>A Stepwise Approach to Win11's Hyper-V Activation</u></a></li>
<li><a href="https://win11.techidaily.com/a-tutorial-on-windows-media-player-launching/"><u>A Tutorial on Windows Media Player Launching</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-visual-keyboard-assistant/"><u>Accessing Windows 11'S Visual Keyboard Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://driver-install.techidaily.com/activate-mx870-for-canon-on-win-1178-systems/"><u>Activate MX870 for Canon on WIN 11/7/8 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-internal-portaudio-errors-in-audacity-windows-11/"><u>Addressing Internal PortAudio Errors in Audacity (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-vanished-pc-displays-at-launch/"><u>Addressing Vanished PC Displays at Launch</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-brightness-control-software-for-windows-multiscreen-enthusiasts/"><u>Advanced Brightness Control Software for Windows Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win-amazing.techidaily.com/amd-sata-raid-controller-driver-free-download-guide-for-windows-users/"><u>AMD SATA RAID Controller Driver: Free Download Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/automated-uninstall-process-for-printers-in-windows-11/"><u>Automated Uninstall Process for Printers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mishaps-validate-your-webcammic-on-windows-pc/"><u>Avoiding Mishaps: Validate Your Webcam/Mic on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-a-valid-temp-folder-in-windows-11/"><u>Best Practices for a Valid Temp Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/blending-gmail-with-outlook-on-windows-comprehensive-guide/"><u>Blending Gmail with Outlook on Windows: Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-the-new-search-feature-in-windows-11/"><u>Boost Productivity with the New Search Feature in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-system-with-these-5-ease-access-tricks/"><u>Boost Your System with These 5 Ease Access Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-benefits-of-16gb-windows-memory/"><u>Breaking Down the Benefits of 16GB Windows Memory</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-overturning-monochrome-windows-display/"><u>Breaking Free: Overturning Monochrome Windows Display</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-stunning-photography-mastering-hdr-merging-in-lightroom-for-2024/"><u>Crafting Stunning Photography  Mastering HDR Merging in Lightroom for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722977973199-get-the-latest-hp-spectre-x360-drivers-compatible-with-windows-full-set/"><u>Get the Latest HP Spectre X360 Drivers Compatible with Windows - Full Set</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-nokia-c12-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Nokia C12 FRP?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-metaverse-promotion-essentials/"><u>In 2024, Metaverse Promotion Essentials</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mirth-in-monotony-the-top-20-fb-detention-reprieve-humor-for-2024/"><u>Mirth in Monotony  The Top 20 Fb Detention Reprieve Humor for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-poco-m6-pro-5g-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Poco M6 Pro 5G Device</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On OnePlus Ace 2 Pro | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>