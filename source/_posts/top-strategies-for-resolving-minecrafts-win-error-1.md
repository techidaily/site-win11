---
title: "Top Strategies for Resolving Minecraft's Win Error: 1"
date: 2024-08-28T00:53:35.950Z
updated: 2024-08-29T00:53:35.950Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Top Strategies for Resolving Minecraft's Win Error: 1"
excerpt: "This Article Describes Top Strategies for Resolving Minecraft's Win Error: 1"
keywords: Win Error Fix Guide,Debugging Mojang Game,Solve Minecraft Crashes,Win Error 1 Strategies,Resolving Mojang Glitches,Overcoming Minecraft Failures,Uninstall/Reinstall Tips
thumbnail: https://thmb.techidaily.com/f47c079fa1fce90a8221b9c2c003a393b4231e2fbb42dbd4e99eb8971ba63ab6.jpg
---

## Top Strategies for Resolving Minecraft's Win Error: 1

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
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
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. The caveat here is you’ll need to update the Java version number or re-add the Java executable every time you update Java.

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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Restart your computer.
8. To reinstall Minecraft, open**Minecraft Launcher** . It will start the installation process.
9. Follow the on-screen instructions to complete the process and sign in with your Minecraft account.
10. Next, move the**saves** folder back to the following location:  
C:\Users\[Username]\AppData\Roaming\.minecraft
11. Relaunch Minecraft to check if the error is resolved.

## 6\. Perform Generic Windows and Java Fixes

 If Minecraft is still plagued by the "exit code: 1" error, here are some more general fixes you can try.

### Update the Graphics Drivers

 Incompatible or outdated graphics drivers can cause games on Windows computers to malfunction. For a dedicated GPU, you can use AMD Radeon Software or Nvidia GeForce Experience to[install the latest graphics drivers updates on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

 Intel users can download newer updates from the Windows update page. To do this, press Win + I to open Settings. Open Windows Updates and install any update available for your Intel graphics. Alternatively, check Intel’s website for newer display drivers for Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### Reinstall Java

![java runtime environment install windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtine-environment-install-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
 The "exit code: 1" error often hints at invalid Java runtime configuration issues. You can reinstall Java to fix configuration issues fixed in the latest release.

To reinstall Java Runtime Environment:

1. Go to the[Java download page](https://www.java.com/en/download/manual.jsp) .
2. Select the correct version for your Windows computer. You can opt for the Windows Online or Offline version. Also, download the 64-bit version if applicable.
3. Run the installer and follow the on-screen instructions to complete installations.
4. Once installed, restart your computer and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagrams-abandoned-followers-map/"><u>[New] 2024 Approved  Instagram's Abandoned Followers Map</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-angle-advantage-guide-mastering-the-art-of-spinning-photos-for-social-media-triumphs/"><u>[New] 2024 Approved  The Angle Advantage Guide  Mastering the Art of Spinning Photos for Social Media Triumphs</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-pre-upgrade-essentials-a-comprehensive-guide/"><u>[New] In 2024, Pre-Upgrade Essentials  A Comprehensive Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pioneering-flight-paths-with-gopro-karma-technology/"><u>[New] Pioneering Flight Paths with GoPro Karma Technology</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-capturing-both-webcam-and-monitor-live-feed/"><u>[Updated] In 2024, Capturing Both Webcam & Monitor Live Feed</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-10-dynamic-image-backdrops-viewer/"><u>[Updated] Top 10 Dynamic Image Backdrops Viewer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-simple-tips-for-capturing-google-voice-conversations/"><u>2024 Approved  Simple Tips for Capturing Google Voice Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/creating-unique-keys-for-winapps-and-tools/"><u>Creating Unique Keys for WinApps and Tools</u></a></li>
<li><a href="https://facebook.techidaily.com/discovering-the-role-of-facebook-in-building-communities/"><u>Discovering the Role of Facebook in Building Communities</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-with-millions-on-major-platforms-facebook-twitter-instagram-youtube-unveiled/"><u>Engage with Millions on Major Platforms: Facebook, Twitter, Instagram, YouTube Unveiled</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-usb-xhci-compliant-host-controller-error-code-10/"><u>Fix: USB xHCI Compliant Host Controller Error Code 10</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-error-code-0x0000004e-breakdown/"><u>Fixing Windows Error Code: 0X0000004E Breakdown</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/flash-video-insights-guide-for-2024/"><u>Flash Video Insights Guide for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-apple-iphone-6s-location-on-viber-drfone-by-drfone-virtual-ios/"><u>How to Change/Fake Your Apple iPhone 6s Location on Viber | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-tecno-spark-20-proplus-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Tecno Spark 20 Pro+</u></a></li>
<li><a href="https://network-issues.techidaily.com/introducing-enhanced-graphics-driver-for-win10s-nvidia-210/"><u>Introducing Enhanced Graphics Driver for Win10's NVIDIA 210</u></a></li>
<li><a href="https://android-frp.techidaily.com/lava-yuva-2-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Lava Yuva 2 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-projector-screens-without-pin-in-win11/"><u>Mastering Projector Screens Without PIN in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-passcodes-longer-windows-11-and-11-pins/"><u>Mastering Secure Passcodes: Longer Windows 11 and 11 PINs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-pace-boosting-windows-download-efficiency/"><u>Mastering Steam Pace: Boosting Windows Download Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-text-use-with-snipping-tool-windows-edition/"><u>Maximize Text Use with Snipping Tool Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-minecraft-lan-connectivity-woes-on-windows/"><u>Navigating Minecraft LAN Connectivity Woes on Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-through-hugging-face-clarifying-its-essence-and-practical-uses/"><u>Navigating Through Hugging Face - Clarifying Its Essence & Practical Uses</u></a></li>
<li><a href="https://win11.techidaily.com/new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/"><u>New Era of Connectivity: Windows for iPhones, iPads and PCs Just Dropped!</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-default-access-denial-in-winos/"><u>Overcoming Default Access Denial in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-invalid-onedrive-tags/"><u>Overcoming the Challenge of Invalid OneDrive Tags</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-the-hidden-spot-of-your-desktop-picture-in-win11/"><u>Pinpointing the Hidden Spot of Your Desktop Picture in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-windows-still-requires-password-faults/"><u>Quick Fixes for “Windows Still Requires Password” Faults</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-iomap64-blue-screen-error-in-win108/"><u>Quick Guide to Resolve IOMap64 Blue Screen Error in Win10/8</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-regular-launch-procedure-in-outlook-despite-safe-mode-lockdown/"><u>Reactivating Regular Launch Procedure in Outlook Despite Safe Mode Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-windows-11-ignore-admin-restrictions/"><u>Reboot Windows 11, Ignore Admin Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-missing-directory-indicators/"><u>Reversing Missing Directory Indicators</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-adjacent-and-non-adjacent-windows-partition-merging/"><u>Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-secure-sticky-notes-on-modern-oses/"><u>Steps to Secure Sticky Notes on Modern OSes</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-selecting-and-using-b-roll-in-productions-for-2024/"><u>The Art of Selecting and Using B-Roll in Productions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-combining-folders-and-files-in-win-11/"><u>The Essential Guide to Combining Folders & Files in Win 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-8-must-have-educational-apps/"><u>Top 8 Must-Have Educational Apps</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-budget-routers-showdown-spotlight-on-the-tp-link-archer-c9/"><u>Top Budget Routers Showdown - Spotlight on the TP-Link Archer C9</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-of-trio-configuring-widgets-for-windows-11-users/"><u>Triumph of Trio: Configuring Widgets for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharging-your-pcs-download-speed-with-steam/"><u>Turbocharging Your PC's Download Speed with Steam</u></a></li>
<li><a href="https://win11.techidaily.com/unified-world-of-computing-windows-now-available-on-iphoneipadmacpc/"><u>Unified World of Computing: Windows Now Available on iPhone/iPad/Mac/PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlock-your-creativity-with-top-title-methods-for-2024/"><u>Unlock Your Creativity with Top Title Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-driver-verifier-within-win11-control-panel/"><u>Unveiling Driver Verifier Within Win11 Control Panel</u></a></li>
</ul></div>
