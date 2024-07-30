---
title: Combat Strategies for Operational Error #740 in Windows Devices
date: 2024-07-29T15:53:14.082Z
updated: 2024-07-30T15:53:14.082Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combat Strategies for Operational Error #740 in Windows Devices
excerpt: This Article Describes Combat Strategies for Operational Error #740 in Windows Devices
keywords: Win Error Fixes,DevTech Strategy,Error Resolution Win,Strategic Error Handling,Operational Device Fix,Windows Error Tactics,Debugging Win Solutions
thumbnail: https://thmb.techidaily.com/e85743b34dfe1708fd7baeaabbf4be530a9d0acc972c34955c94cad23467f1e0.jpg
---

## Combat Strategies for Operational Error #740 in Windows Devices

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
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
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-how-to-record-roblox-gameplay-on-mac/"><u>[New] 2024 Approved  How to Record Roblox Gameplay on Mac</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-crafting-compelling-visual-narratives-with-illustrators-motion-blur/"><u>[New] Crafting Compelling Visual Narratives with Illustrator's Motion Blur</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-gameplay-memories-preserved-unveiling-6-minecraft-tips/"><u>[Updated] 2024 Approved  Gameplay Memories Preserved  Unveiling 6 Minecraft Tips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-transform-your-reels-6-advanced-applications-for-instagram-for-2024/"><u>[Updated] Transform Your Reels  6 Advanced Applications for Instagram for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transformative-visuals-the-pixiz-process-for-photo-video-fusion/"><u>[Updated] Transformative Visuals  The Pixiz Process for Photo-Video Fusion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-enhance-entertainment-experience-navigating-netflixs-picture-in-picture-functionality/"><u>2024 Approved  Enhance Entertainment Experience  Navigating Netflix's Picture-in-Picture Functionality</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-unconventional-text-presentation-methods/"><u>2024 Approved  Unconventional Text Presentation Methods</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correction-of-errors-in-organization-managed-windows-11-settings/"><u>Correction of Errors in Organization-Managed Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-managing-setup-host-cpu-use/"><u>Efficiently Managing Setup Host CPU Use</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-winning-streak-with-fps-techniques/"><u>Elevating Your Winning Streak with FPS Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-signs-on-screen-when-booting-windows/"><u>Fixing No Signs on Screen When Booting Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-non-starting-issues-with-obs-on-pc/"><u>How to Address Non-Starting Issues with OBS on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-code-0x80d03801-in-microsoft-store-on-windows-pc/"><u>How to Fix Error Code 0X80d03801 in Microsoft Store on Windows PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-samsung-galaxy-z-fold-5-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Samsung Galaxy Z Fold 5 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-audio-visual-blend-in-online-photography/"><u>In 2024, Audio-Visual Blend in Online Photography</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-iphone-7-plus-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock iPhone 7 Plus After Forgetting the Passcode?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-oppo-a78-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Oppo A78 Face Lock?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-redmi-13c-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Xiaomi Redmi 13C 5G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-a-new-pdf-reader-standard-on-os/"><u>Instituting a New PDF Reader Standard on OS</u></a></li>
<li><a href="https://win11.techidaily.com/master-keyboard-flair-with-typingaid-techniques/"><u>Master Keyboard Flair with TypingAid Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-transfer-in-google-chrome-now-easier-on-windows/"><u>Mastering File Transfer in Google Chrome, Now Easier on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-invisible-images-with-encrypted-zips-win/"><u>Mastering the Art of Invisible Images with Encrypted Zips (WIN)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-altering-windows-registry-using-cli/"><u>Navigating and Altering Windows Registry Using CLI</u></a></li>
<li><a href="https://win11.techidaily.com/prime-virtually-powered-platforms-for-windows-11-users/"><u>Prime Virtually-Powered Platforms for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-remote-display-issue-darkened-screen/"><u>Resolving Windows Remote Display Issue: Darkened Screen</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-access-post-error-code-22-fixing-a-locked-down-pc-in-windows-11/"><u>Restoring Access Post-Error Code 22: Fixing a Locked Down PC in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rethinking-upgrades-windows-11s-improvement-focus/"><u>Rethinking Upgrades: Windows 11’S Improvement Focus</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-clutter-windows-generative-erasure/"><u>Say Goodbye to Clutter: Windows' Generative Erasure</u></a></li>
<li><a href="https://win11.techidaily.com/sound-superchargers-4-applications-boosting-windows-audio-capacity/"><u>Sound Superchargers: 4 Applications Boosting Windows' Audio Capacity</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-day-wins-best-time-management-solutions/"><u>Streamline Your Day: Win's Best Time Management Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/stutter-no-more-essential-9-tips-to-ensure-fluid-video-on-pcs/"><u>Stutter No More: Essential 9 Tips to Ensure Fluid Video on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcoming-stuck-windows-update-fixer/"><u>Swiftly Overcoming Stuck Windows Update Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-windows-11-in-software-installation-harmony/"><u>The Role of Windows 11 in Software Installation Harmony</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-for-effective-app-packages-control-using-winget-on-win11/"><u>Top Tips for Effective App Packages Control Using Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secure-windows-server-settings/"><u>Unlocking Secure Windows Server Settings</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-dxgidll-quick-fixes-for-the-missing-file/"><u>Win11 & Dxgi.dll: Quick Fixes for the Missing File</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>