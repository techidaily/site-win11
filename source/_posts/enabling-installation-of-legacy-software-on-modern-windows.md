---
title: Enabling Installation of Legacy Software on Modern Windows
date: 2024-10-20T08:42:18.147Z
updated: 2024-10-26T23:49:08.714Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Installation of Legacy Software on Modern Windows
excerpt: This Article Describes Enabling Installation of Legacy Software on Modern Windows
keywords: Legacy Windows Support,Modern OS Compatibility,Outdated Apps Update,Retro Software Integration,System Legacy Upgrade,Older Software Install,Windows Legacy Patching
thumbnail: https://thmb.techidaily.com/e04a9e5f3764ad02106bedbd9d5d7455103ba03869a73a825a4ebe2566d36218.jpg
---

## Enabling Installation of Legacy Software on Modern Windows

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541">
  <img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-ultimate-guide-to-professional-grade-mobile-screencasting-with-mobizen/"><u>[New] 2024 Approved Ultimate Guide to Professional-Grade Mobile Screencasting with Mobizen</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-cutting-edge-free-and-easy-top-11-youtube-title-inventors-for-2024/"><u>[New] Cutting-Edge, Free, and Easy Top 11 YouTube Title Inventors for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ow-to-post-a-video-from-youtube-on-instagram-for-2024/"><u>[New] How to Post a Video From YouTube on Instagram for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-5-best-tips-for-enhancing-obs-studio-edits/"><u>[Updated] In 2024, 5 Best Tips for Enhancing OBS Studio Edits</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-real-time-chromebook-display-logger/"><u>[Updated] Real-Time Chromebook Display Logger</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-nix-the-sneaky-youtube-quick-playback-feature/"><u>2024 Approved Nix the Sneaky YouTube Quick Playback Feature</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-clutter-a-fast-track-to-a-pristine-win11/"><u>Conquer Clutter: A Fast-Track to a Pristine Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-controlled-access-a-step-by-step-for-windows-10-and-11/"><u>Enabling Controlled Access: A Step-by-Step for Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/explore-these-superior-webp-viewers-for-windows-users/"><u>Explore These Superior WebP Viewers for Windows Users</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-xiaomi-redmi-12-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Xiaomi Redmi 12</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-optimizing-your-video-call-zoom-and-fb-live-integration/"><u>In 2024, Optimizing Your Video Call ZOOM & FB Live Integration</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-pc-performance-for-exciting-valorant-sessions/"><u>Optimize PC Performance for Exciting Valorant Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-windows-11-calculator-unlock/"><u>Quick Tips: Windows 11 Calculator Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-admin-controlled-features-in-windows-11-systems/"><u>Resetting Admin-Controlled Features in Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-retro-replays-linking-legends-with-pcs-photos-folder/"><u>Reviving Retro Replays: Linking Legends with PCs' Photos Folder</u></a></li>
<li><a href="https://win11.techidaily.com/the-pros-guide-to-mastering-20-windows-cmd-commands/"><u>The Pro's Guide to Mastering 20 Windows CMD Commands</u></a></li>
</ul></div>

