---
title: Troubleshooting Techniques to Stop Crashes in Game
date: 2024-08-28T00:56:59.667Z
updated: 2024-08-29T00:56:59.667Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Techniques to Stop Crashes in Game
excerpt: This Article Describes Troubleshooting Techniques to Stop Crashes in Game
keywords: Fix Game Crashes,Stop Gaming Errors,Prevent Video Games Failures,Solve Game Stops,Ending Game Crashes,Eliminate Gaming Freezes,Avoid Play Glitches
thumbnail: https://thmb.techidaily.com/cd3d45b359655445d3a3fddc84f4f42edd47a1ec876e69fbcc20cbbbf17a86ba.png
---

## Troubleshooting Techniques to Stop Crashes in Game

 When Minecraft fails to launch correctly, it will sometimes crash with the "exit code: 1" error. While the error message indicates issues with Java runtime configuration, there can also be other reasons. An outdated graphics driver, incorrect in-game settings, incompatible mods, buggy game files, and an invalid launcher file path can also trigger the "exit code:1" error on Windows.

 Here we show you a few quick troubleshooting steps to fix the "exit code: 1" and get back to playing Minecraft on your Windows computer.

## 1\. Delete or Disable Outdated Mods

 The "exit code: 1" error can occur due to outdated mods. To resolve the error, check the Minecraft mods folder and delete it. Removing mods can break your worlds. So make sure to create a backup before attempting to remove any mods. Here’s how to do it.

1. Press**Win + R** and type the following in the**Run** dialog:  
`%appdata%\`
2. Click**OK** to open the**AppData\\Roaming** folder in**File Explorer** .  
![appdata run dialog windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/appdata-run-dialog-windows-11.jpg)
3. Next, open the**.minecraft** folder.  
![minecraft mods folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-mods-folder-windows-file-explorer.jpg)
4. Open the**mods** folder inside the**.minecraft** folder.
5. Select and right-click on all the**mods** one by one and select**Delete** .

 Once all the mods are removed, close File Explorer and relaunch Minecraft to see if the error is resolved. On the flip side, you may find some Minecraft levels (worlds) broken upon launch. You may also want to re-download mods to make further modifications.

## 2\. Repair Minecraft Launcher

 You can fix common problems with the Minecraft Launcher using the[built-in repair option on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) . During repair, Windows will look for common issues and try to fix them automatically. It will also delete the app’s data.

To repair Minecraft Launcher:

1. Press**Win + I** to open**Windows** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed Apps** and search**Minecraft Launcher** .  
![minecrafft launcher advanced options windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecrafft-launcher-advanced-options-windows-11.jpg)
4. Next, click the**three-dots menu** beside the app name and select**Advanced Options** .  
![repair minecraft launcher windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/repair-minecraft-launcher-windows-11.jpg)
5. Scroll down to the**Reset** section and click**Repair** . Windows will perform a quick repair and show a checkmark once the repair is complete.
6. Relaunch Minecraft Launcher and check for any improvements.

 Similarly, you can also repair your Minecraft game. Open Minecraft’s**Advanced Options** and perform a repair in the**Settings** app.

## 3\. Modify the Minecraft Launcher File Path

![modify minecraft launcher file path working directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-minecraft-launcher-file-path-working-directory.jpg)

 Issues with the Minecraft Launcher file path can cause the "exit code: 1" on Windows. If your user name has a special character, the Minecraft Launcher file path may not respond to a user account with a special character.

 To fix the issue, you’ll need to modify the Minecraft Launcher file path to allow the launcher to access the launcher without special characters.

To change the Minecraft Launcher file path:

1. Right-click on the**Minecraft Launcher** shortcut and select**Properties** .
2. In the**Properties** dialog, open the Shortcut pat.
3. In the**Target** field, add the following line to change the working directory for Minecraft Launcher. You need to add the below lines after the existing file path:  
`&ndash;workDir %ProgramData%.minecraft`
4. After modifications, the target field will look something like this:  
`"C:\Program Files (x86)\Minecraft Launcher\MinecraftLauncher.exe" &ndash;workDir %ProgramData%.minecraft`
5. Click**Apply** and**OK** to save the changes.
6. Relaunch Minecraft and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change the Java Executable Path

 Your Minecraft installation can run into issues if the launcher fails to detect the correct Java file. While Minecraft Launcher automatically installs the required JRE version, at times, you may need to manually change the executable to run the modified version of the game.

To change the Java executable for Minecraft:

1. Open the**Minecraft Launcher** .
2. Next, select the**Minecraft Java Edition** tab in the left pane.
3. Open the**Installations** tab in the toolbar.
4. Hover your mouse over**Latest Release** and click the**three-dots menu.**
5. Select**Edit** from the menu.  
![minecraft launcher latest release edit windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-launcher-latest-release-edit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Click**More Options** to view additional options.
2. Click**Browse** to add a**Java Executable** .  
![java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-executable-browse-minecraft-launcher-windows.jpg)
3. Navigate to your Java installation. By default, the JRE file path is:  
`C:\Program Files (x86)\Java\jre1.8.0_361\bin`
4. Select the**Java.exe** file and click**Open** .  
![select JRE java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/select-jre-java-executable-browse-minecraft-launcher-windows.jpg)
5. Click**Save** to apply the changes and relaunch Minecraft Launcher.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. The caveat here is you’ll need to update the Java version number or re-add the Java executable every time you update Java.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Reinstall Minecraft Without Deleting Saves

 You can reinstall Minecraft to fix issues with the game. Depending on how you installed the game, you can uninstall Minecraft from the Settings app or delete the .minecraft Appdata folder. If you prefer, you can also choose to keep your Minecraft saves.

To backup Minecraft saves and uninstall the game:

1. Press**Win + R** to open the**Run** dialog.
2. Paste the following in the**Run** field and click**OK** :  
`%appdata%\`
3. Open the**.minecraft** folder.  
![delete minecraft data folder uninstall windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-minecraft-data-folder-uninstall-windows.jpg)
4. Right-click on the saves folder and select**Copy (Ctrl +C)** .
5. Paste the**saves** folder outside the**.minecraft** folder.  
![minecraft saves folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-savess-folder-windows-file-explorer.jpg)
6. Next, return to the**Roaming** folder and delete the**.minecraft** folder to uninstall the game.
7. Restart your computer.
8. To reinstall Minecraft, open**Minecraft Launcher** . It will start the installation process.
9. Follow the on-screen instructions to complete the process and sign in with your Minecraft account.
10. Next, move the**saves** folder back to the following location:  
C:\Users\[Username]\AppData\Roaming\.minecraft
11. Relaunch Minecraft to check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform Generic Windows and Java Fixes

 If Minecraft is still plagued by the "exit code: 1" error, here are some more general fixes you can try.

### Update the Graphics Drivers

 Incompatible or outdated graphics drivers can cause games on Windows computers to malfunction. For a dedicated GPU, you can use AMD Radeon Software or Nvidia GeForce Experience to[install the latest graphics drivers updates on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

 Intel users can download newer updates from the Windows update page. To do this, press Win + I to open Settings. Open Windows Updates and install any update available for your Intel graphics. Alternatively, check Intel’s website for newer display drivers for Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
### Reinstall Java

![java runtime environment install windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtine-environment-install-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The "exit code: 1" error often hints at invalid Java runtime configuration issues. You can reinstall Java to fix configuration issues fixed in the latest release.

To reinstall Java Runtime Environment:

1. Go to the[Java download page](https://www.java.com/en/download/manual.jsp) .
2. Select the correct version for your Windows computer. You can opt for the Windows Online or Offline version. Also, download the 64-bit version if applicable.
3. Run the installer and follow the on-screen instructions to complete installations.
4. Once installed, restart your computer and check for any improvements.

## Fixing the Minecraft Exit Code: 1 Error

 Many things can go wrong and trigger the "exit Code: 1 error" in Minecraft. To resolve the issue, try to disable mods and change the Minecraft Launcher path. If the issue persists, check your graphics driver for the problem.

 If all else fails, perform a reinstall. You can reinstall Minecraft while keeping saves. If you are using the latest Microsoft Store version of the game, you can also uninstall it from the settings app.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-an-easy-way-to-amplify-your-instagram-presence-by-sharing-youtube-links-in-stories/"><u>[New] In 2024, An Easy Way to Amplify Your Instagram Presence by Sharing YouTube Links in Stories</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-complete-picture-toolwizs-app-masterclass/"><u>[New] The Complete Picture  Toolwiz's App Masterclass</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-stand-out-on-social-media-discover-a-hundredplus-creative-frameworks-for-your-snap-stories/"><u>[Updated] 2024 Approved  Stand Out on Social Media  Discover a Hundred+ Creative Frameworks for Your Snap Stories</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-optimize-your-youtube-content-for-maximum-viewership-and-engagement/"><u>[Updated] Optimize Your YouTube Content for Maximum Viewership and Engagement</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-trim-video-in-windows-11-photos-easily/"><u>2024 Approved  How to Trim Video in Windows 11 Photos Easily</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-social-media-synergy-twitters-most-shared-tiktoks/"><u>2024 Approved  The Social Media Synergy  Twitter’s Most Shared TikToks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/7-ways-to-unlock-a-locked-vivo-v29-pro-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Vivo V29 Pro Phone</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-windows-11-tips-easy-rdc-entry/"><u>Convenient Windows 11 Tips: Easy RDC Entry</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/creative-commons-peace-sounds-for-2024/"><u>Creative Commons Peace Sounds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-disms-potential-in-win11-system-restoration/"><u>Decoding Dism's Potential in Win11 System Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-nvidia-experience-on-windows-devices/"><u>Fixing Unresponsive NVIDIA Experience on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unaltered-screenscape-in-windows-11/"><u>Guide to Unaltered Screenscape in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-windows-11s-tracking-features/"><u>How to Disable Windows 11'S Tracking Features</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-discord-installation-has-failed-error-on-windows-11-and-11/"><u>How to Fix the Discord “Installation Has Failed” Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-windows-error-code-1053-for-non-responsive-services/"><u>How to Handle Windows' Error Code 1053 for Non-Responsive Services</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-vivo-x90s-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-the-art-of-affordable-data-storage-cloud/"><u>In 2024, Mastering the Art of Affordable Data Storage (Cloud)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-tailor-made-youtube-music-mixes-a-stepwise-technique-for-webmobile-users/"><u>In 2024, Tailor-Made YouTube Music Mixes  A Stepwise Technique for Web/Mobile Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-samsung-galaxy-s21-fe-5g-2023-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Samsung Galaxy S21 FE 5G (2023) FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-fixes-for-disabled-hard-drives-on-windows-11-systems/"><u>Innovative Fixes for Disabled Hard Drives on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/instant-access-merge-your-onedrive-and-microsoft-account/"><u>Instant Access: Merge Your OneDrive & Microsoft Account</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-eliminate-microsoft-store-error-0x80072efd/"><u>Master Plan to Eliminate Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-full-screen-capture-efficiency-with-these-fixes-in-windows/"><u>Maximize Full-Screen Capture Efficiency with These Fixes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-free-disk-space-in-windows-with-these-7-tips/"><u>Maximizing Free Disk Space in Windows with These 7 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-excessive-heat-on-windows-11-devices/"><u>Mitigating Excessive Heat on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-camera-quirks-with-ease/"><u>Navigating Window's Camera Quirks with Ease</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/oming-shadows-in-indoor-vlogging-environments-for-2024/"><u>Overcoming Shadows in Indoor Vlogging Environments for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-upload-obstacles-with-onedrive-on-win-11/"><u>Overcoming Upload Obstacles with OneDrive on Win 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-oneplus-ace-2-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best OnePlus Ace 2 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unnoticed-windows-11-camera-use/"><u>Preventing Unnoticed Windows 11 Camera Use</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-error-0x80041015-in-ms-word-and-excel/"><u>Quick Fixes for Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-fabricated-device-specification-error-in-win-11/"><u>Rectifying Fabricated Device Specification Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-not-available-errors-on-your-windows-11-pc/"><u>Resolving 'Network Not Available' Errors on Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-uninstalls-that-fail/"><u>Resolving Windows 10/11 Uninstalls That Fail</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-your-corrupted-windows-11-trash/"><u>Restoring Functionality to Your Corrupted WIndows 11 Trash</u></a></li>
<li><a href="https://win11.techidaily.com/retrieve-past-cortana-interactions-in-windows-files/"><u>Retrieve Past Cortana Interactions in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11-after-password-hurdle/"><u>Reviving Windows 11 After Password Hurdle</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-why-your-logitech-g533-microphone-isnt-working-and-how-to-fix-it-fast/"><u>Solved: Why Your Logitech G533 Microphone Isn't Working and How to Fix It Fast</u></a></li>
<li><a href="https://win11.techidaily.com/step-into-the-twilight-zone-paints-dark-mode-magic/"><u>Step Into the Twilight Zone: Paint's Dark Mode Magic</u></a></li>
<li><a href="https://win11.techidaily.com/surgical-solutions-to-windows-11-login-screen-problems/"><u>Surgical Solutions to Windows 11 Login Screen Problems</u></a></li>
<li><a href="https://win11.techidaily.com/top-10-must-have-apps-to-replace-windows-11-essentials/"><u>Top 10 Must-Have Apps to Replace Windows 11 Essentials</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshoot-your-way-through-the-persistent-launch-loop-in-madden-22-expert-tips-inside/"><u>Troubleshoot Your Way Through the Persistent Launch Loop in Madden 22 - Expert Tips Inside</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-mobile-hotspot-connectivity-on-windows-11/"><u>Troubleshooting Failed Mobile Hotspot Connectivity on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-solutions-to-temp-extraction-hurdles-in-win-oses/"><u>Uncovering Solutions to 'Temp Extraction Hurdles in Win OSes'</u></a></li>
</ul></div>
