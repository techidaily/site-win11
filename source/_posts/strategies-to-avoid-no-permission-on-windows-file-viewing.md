---
title: Strategies to Avoid 'No Permission' On Windows File Viewing
date: 2024-08-15T23:38:25.196Z
updated: 2024-08-16T23:38:25.196Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Avoid 'No Permission' On Windows File Viewing
excerpt: This Article Describes Strategies to Avoid 'No Permission' On Windows File Viewing
keywords: Avoiding NoPermViewError,WindowsFileAccessDeny,SafeFileshareTechniques,PermissionsControlWindows,AccessDeniedWindowsStrategy,FilePermissionAvoidance,SecureFilesystemWindows
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
---

## Strategies to Avoid 'No Permission' On Windows File Viewing

 Did you encounter an error message when opening photos on an external hard drive? The message says "It looks like you don't have permission to view this file. Check the permissions and try again." The error implies that Windows Photos or File Explorer is not authorized to access this file.

 In this article, we explain how to fix this error, so you can view your photos again.

## Why Can't You View the File?

 You may encounter this error if your external hard drive is connected to a device without the right permissions settings. Other possible causes include user account control settings which restrict access to external drives, or a corrupted Windows Photos app.

 Now you know what causes this error, let's explore the solution.

## 1\. Grant Full Control Permissions

 It looks like the main issue causing this error is that Windows doesn’t have sufficient permissions to access the file. To fix this, you must grant full control permissions to the account or user accessing the file. Here are the steps to follow:

1. Right-click on the folder and choose **Properties**.
2. In the Properties window, go to the **Security** tab.
3. Select the user account or group from the list and click **Edit**.
4. Under the **Permissions** section, check the box next to **Full Control**.  
![Grant Full Control Permissions to an user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/grant-full-control-permissions-to-an-user-account.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
5. Click **Apply** and **OK** to save the changes.

 After making these changes, try viewing the photos again and checking if the error has been resolved.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Take Ownership of the Folder

 If granting full control permissions does not work, take ownership of the folder to get more control. Taking ownership means you can manage, access, and delete files within it. Here's how to do it:

1. Right-click on the folder and select **Properties** from the context menu.
2. Switch to the **Security** tab, then click **Advanced** at the bottom.
3. In the Advanced Security Settings window, make sure you're on the **Permissions** tab.
4. Click on **Change** next to **Owner** in the top section.  
![Advanced Security Settings for Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-security-settings-for-folders.jpg)
5. In the dialog box, type **Everyone** and click **Check Names**.  
![Enter the object name to select user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enter-the-object-name-to-select-user.jpg)

1. If it seems correct, click **OK**.
2. Check the box next to **Replace owner on subcontainers and objects**.  
![Take Ownership of the Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/take-ownership-of-the-folder.jpg)
3. Now click Apply. A pop-up appears and asks you to confirm the ownership change.
4. Click **Yes** and wait for the process to finish.
5. Once done, click **OK** and close the window.

 After that, restart your computer and try accessing the folder.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Reset the Photos App

 Another way to fix this error is to reset the Photos app. Resetting the app will delete all settings and cached data and restore it to its default state. Here’s how to reset the Photos app:

1. Press **Win + I** to open the Settings menu.
2. From the left pane, click **Apps** \> **Installed apps**.
3. Scroll down to find the **Microsoft Photos** app. You can also use the search bar to find it.  
![Microsoft Photos App in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-photos-app-in-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the three dots and select **Advanced options**.
5. Under the **Reset** section, click the **Reset** button.  
![Reset Microsoft Photos App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-microsoft-photos-app.jpg)
6. If a pop-up appears, click **Reset** again to confirm your action.

 After that, try to open photos on your external hard drive.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 4\. Disable UAC Temporarily

 You may often find that you don’t have enough permissions to perform specific tasks. In such cases, [disabling UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) may do the trick. So, disable it temporarily and see if it works.

## 5\. Run the Program Compatibility Troubleshooter

 If you're still encountering the error, try [running the Program Compatibility Troubleshooter](http://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/). This tool scans for compatibility issues with installed programs and solves them automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Open Files Without a Problem Again on Windows

 If you have the proper permissions, you should not encounter the "you don’t have permission to view this file” message. However, if you run into this issue, read this guide to resolve it quickly. Make sure you grant all permissions and take ownership of the folder.

 In this article, we explain how to fix this error, so you can view your photos again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-break-new-ground-in-social-sagas-free-extended-versions-await/"><u>[New] In 2024, Break New Ground in Social Sagas – Free, Extended Versions Await</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-snapchats-zoom-for-crisp-visuals/"><u>[New] Navigating Snapchat's Zoom for Crisp Visuals</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-punpixel-patterner/"><u>[New] PunPixel Patterner</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-how-to-play-your-iphone-videos-backward/"><u>[Updated] 2024 Approved  How to Play Your iPhone Videos Backward</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-zoom-chat-how-to-chat-in-zoom-meeting/"><u>[Updated] 2024 Approved  Zoom Chat  How to Chat in Zoom Meeting?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-luminous-techniques-for-web-based-cinema/"><u>[Updated] Luminous Techniques for Web-Based Cinema</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-nokia-c12-pro-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Nokia C12 Pro</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-reviewing-window-recording-the-sprout-experience/"><u>2024 Approved  Reviewing Window Recording - The Sprout Experience</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-tips-for-safeguarding-your-youtube-presence/"><u>2024 Approved  Tips for Safeguarding Your YouTube Presence</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pc-non-compliance-intel-hd-graphics-setback/"><u>Addressing PC Non-Compliance: Intel HD Graphics Setback</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-print-saturation-with-windows-11/"><u>Avoiding Print Saturation with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-navigation-of-files-with-gallery-on-pc/"><u>Efficient Navigation of Files with Gallery on PC</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-productivity-top-30-mouse-control-wizards/"><u>Elevate Productivity: Top 30 Mouse Control Wizards</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-roblox-gaming-with-higher-frames-per-second/"><u>Elevating Roblox Gaming with Higher Frames per Second</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-boosting-productivity-in-project-management-tools/"><u>Expert Tips for Boosting Productivity in Project Management Tools</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-in-linux-sphere/"><u>Exploiting Windows Software in Linux Sphere</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-blank-windows-11-logins/"><u>Guide to Fixing Blank Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-impact-on-performance-the-unseen-effect-of-disguised-software/"><u>Hidden Impact on Performance: The Unseen Effect of Disguised Software</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-your-laptop-or-desktop-a-portable-network-hub-on-windows-11/"><u>How to Make Your Laptop or Desktop a Portable Network Hub on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-repairs-how-to-tackle-post-windows-update-glitches/"><u>Immediate Repairs: How to Tackle Post-Windows Update Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality.</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-apple-maps-on-windows/"><u>Navigating the World: Apple Maps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-distant-devices-a-guide-for-windows-users/"><u>Reconciling Distant Devices: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/relish-in-unmatched-windows-software-sweepstakes/"><u>Relish In Unmatched Windows Software Sweepstakes</u></a></li>
<li><a href="https://win11.techidaily.com/revive-muted-slack-on-windows-easy-steps-to-resuscitate-alerts/"><u>Revive Muted Slack on Windows: Easy Steps to Resuscitate Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/stop-auto-changing-visuals-on-win11-pcs/"><u>Stop Auto-Changing Visuals on Win11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-reviving-your-windows-system/"><u>The Blueprint for Reviving Your Windows System</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/tips-to-quicken-instagram-media-playback-for-2024/"><u>Tips to Quicken Instagram Media Playback for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unable-to-access-your-windows-start-icon/"><u>Troubleshooting: Unable to Access Your Windows Start Icon</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-tech-titans-android-and-microsoft-pc/"><u>Uniting Two Tech Titans: Android and Microsoft PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-xiaomi-mix-fold-3-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Xiaomi Mix Fold 3 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11.techidaily.com/verifying-your-version-three-ways-for-windows-11/"><u>Verifying Your Version: Three Ways for Windows 11</u></a></li>
</ul></div>
