---
title: How To Address Outdated App Support on Latest Windows Update
date: 2024-11-30T07:29:49.288Z
updated: 2024-12-06T20:59:52.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Address Outdated App Support on Latest Windows Update
excerpt: This Article Describes How To Address Outdated App Support on Latest Windows Update
keywords: WinUpdate Support,AppUpdates Guide,Updating Windows Help,Latest OS Fixes,Old Support Remedies,Software Update Tips,Outdated App Fixes
thumbnail: https://thmb.techidaily.com/e95b10a90432b136a95f53788d2f6a34587f22e1538a737ba31a5504b6070516.jpg
---

## How To Address Outdated App Support on Latest Windows Update

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/new-in-2024-create-an-individualistic-meme-masterpiece/"><u>[New] In 2024, Create an Individualistic Meme Masterpiece</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-embrace-authenticity-your-style-journey-begins-here/"><u>[New] In 2024, Embrace Authenticity Your Style Journey Begins Here</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-essential-android-photography-tools/"><u>[New] In 2024, Essential Android Photography Tools</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-key-sites-for-enhancing-youtube-video-popularity/"><u>[New] Key Sites for Enhancing YouTube Video Popularity</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-mastering-fisheye-photography-for-full-spheres/"><u>[Updated] 2024 Approved Mastering Fisheye Photography for Full Spheres</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-a-closer-look-at-youtubes-payment-system-and-its-potential-for-2024/"><u>[Updated] A Closer Look at YouTube's Payment System and Its Potential for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-capturing-tiktok-videos-saving-on-modern-smartphones/"><u>2024 Approved Capturing TikTok Videos Saving on Modern Smartphones</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-installation-of-legacy-software-on-modern-windows/"><u>Enabling Installation of Legacy Software on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-override-windows-automatic-regional-adjustment/"><u>How to Override Windows' Automatic Regional Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-windows-11s-default-usb-suspend/"><u>How to Sidestep Windows 11'S Default USB Suspend</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-huawei-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Huawei Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/keeping-your-logitech-m510-on-track-with-the-latest-software-updates/"><u>Keeping Your Logitech M510 on Track with the Latest Software Updates</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wins-alerts-in-windows-11/"><u>Mastering Wins Alerts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/peak-your-gpus-performance-the-leading-stress-test-software-ranked/"><u>Peak Your GPU's Performance: The Leading Stress Test Software Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unspecified-obs-studio-error-on-new-windows/"><u>Solving Unspecified OBS Studio Error on New Windows</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-approach-to-heic-to-jpeg-image-change-in-w11/"><u>Systematic Approach to Heic to JPEG Image Change in W11</u></a></li>
<li><a href="https://win11.techidaily.com/three-techniques-for-removing-microsoft-from-win11/"><u>Three Techniques for Removing Microsoft From Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-error-quick-fix-for-0x80072af9/"><u>Unlocking Windows Error: Quick Fix for 0X80072AF9</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95608385-9781449450144-you-are-irreplaceable/"><u>You Are Irreplaceable | Free Book</u></a></li>
</ul></div>

