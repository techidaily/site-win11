---
title: Detailed Steps to Fully Remove WSL on Win 11
date: 2024-10-25T09:50:49.137Z
updated: 2024-10-26T23:20:06.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Detailed Steps to Fully Remove WSL on Win 11
excerpt: This Article Describes Detailed Steps to Fully Remove WSL on Win 11
keywords: Remove WSL Windows,Uninstall WSL Win11,Delete WSL Command Line,Eliminate Windows Subsystem,Stop WSL Service,Deactivate WSL Feature,Exit WSL Procedure
thumbnail: https://thmb.techidaily.com/5cce1c00c454a1f4ada87360e66f8d07572afee6c8228611ca9a5690c1d2c490.jpg
---

## Detailed Steps to Fully Remove WSL on Win 11

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068440/7443" target="_top" id="2068440">
  <img src="//a.impactradius-go.com/display-ad/7443-2068440" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068440/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<span id="1982461">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982461.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982461">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982461.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982461%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982461/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/arning-more-utilizing-youtubes-income-tools-on-all-devices-for-2024/"><u>[New] Earning More Utilizing YouTube's Income Tools on All Devices for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-android-and-ios-prime-asmr-software-options-for-2024/"><u>[Updated] Android & iOS Prime ASMR Software Options for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-chuckles-churner-visual-composer/"><u>2024 Approved Chuckles Churner Visual Composer</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-kindred-spirits-nintendos-best-android-emulators/"><u>2024 Approved Kindred Spirits Nintendo's Best Android Emulators</u></a></li>
<li><a href="https://win-dash.techidaily.com/creating-customized-color-scales-by-value-in-microsoft-excel-a-step-by-step-guide/"><u>Creating Customized Color Scales by Value in Microsoft Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-v27-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo V27 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revamp-windows-dashboard-imagery-anytime/"><u>How to Revamp Window's Dashboard Imagery Anytime</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-restricted-folder-access-via-group-policy-on-windows-10/"><u>Implementing Restricted Folder Access via Group Policy on Windows 10</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-story-highlight-a-user-friendly-guide-for-2024/"><u>Instagram Story Highlight A User-Friendly Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-mail-obstacle-error-code-0x80072746-unraveled/"><u>Overcoming Windows Mail Obstacle: Error Code 0X80072746 Unraveled</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-slow-battlenet-downloads-on-windows/"><u>Quick Fix for Slow Battle.net Downloads on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-default-energy-settings-on-modern-windows/"><u>Reactivating Default Energy Settings on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-basic-settings-for-your-windows-explore/"><u>Restoring Basic Settings for Your Windows Explore</u></a></li>
<li><a href="https://win11.techidaily.com/tactical-toolbox-techniques-disguise-power-buttons-in-win11/"><u>Tactical Toolbox Techniques: Disguise Power Buttons in Win11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Realme C33 2023? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-most-effective-video-collage-applications-a-comprehensive-guide-for-smartphone-devices/"><u>The Most Effective Video Collage Applications : A Comprehensive Guide for Smartphone Devices</u></a></li>
<li><a href="https://win11.techidaily.com/transformative-use-of-windows-tools-in-linux/"><u>Transformative Use of Windows Tools in Linux</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    