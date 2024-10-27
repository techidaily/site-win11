---
title: Navigating Windows 11 for Home Interface
date: 2024-10-20T04:54:25.176Z
updated: 2024-10-26T20:20:31.543Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows 11 for Home Interface
excerpt: This Article Describes Navigating Windows 11 for Home Interface
keywords: Win11 Home Setup,Win11 UI Guide,Win11 Interior Tips,User Interface Win11,Navigate Win11 Basics,Windows 11 Interface Usage,Home Win11 Navigation
thumbnail: https://thmb.techidaily.com/0e72ae7670739d2aa724a5c1676e3ea5eb7af36bcb7980843f57c620d01dbd2b.jpg
---

## Navigating Windows 11 for Home Interface

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-hack-horizon-navigating-back-to-fb-for-2024/"><u>[New] Hack Horizon Navigating Back to Fb for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-googleplus-photo-frame-settings/"><u>[New] In 2024, Google+ Photo Frame Settings</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-maximizing-b-roll-creative-uses-and-integration/"><u>[Updated] 2024 Approved Maximizing B-Roll Creative Uses and Integration</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-audience-accessibility-switching-from-srt-to-sub/"><u>2024 Approved Audience Accessibility Switching From SRT to SUB</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-go-incognito-your-step-by-step-instagram-live-guide/"><u>2024 Approved Go Incognito Your Step-by-Step Instagram Live Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-740-elevation-woes-on-windows-devices/"><u>Eliminating Error Code 740: Elevation Woes on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-software-essential-tools-for-mac-to-windows-changeover/"><u>Enabling Software: Essential Tools for MAC to WINDOWS Changeover</u></a></li>
<li><a href="https://win11.techidaily.com/improving-thumbnails-on-the-windows-bar/"><u>Improving Thumbnails on the Windows Bar</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-resolve-hdr-video-issue-clearing-blank-display/"><u>In 2024, Resolve HDR Video Issue Clearing Blank Display</u></a></li>
<li><a href="https://video-capture.techidaily.com/mastering-srt-files-essential-techniques-for-opening-and-editing-subtitles/"><u>Mastering .srt Files: Essential Techniques for Opening and Editing Subtitles</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-dism-fixes-code-0x800f082f/"><u>Mastering Windows' DISM Fixes: Code 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-user-profile-errors-windows-10-and-11-tips/"><u>Overcoming User Profile Errors: Windows 10 & 11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-revival-why-not-a-non-windows-pc/"><u>Rethink Revival: Why Not a Non-Windows PC?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-oppo-reno-10-5g-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Oppo Reno 10 5G</u></a></li>
<li><a href="https://win11.techidaily.com/sleek-and-simple-searching-compact-view-in-windows-explorer/"><u>Sleek and Simple Searching: Compact View in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-dxvks-influence-on-windows-gaming-quality/"><u>Understanding DXVK's Influence on Windows Gaming Quality</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-revolutionize-your-videos-best-free-special-effects-apps-for-mobile/"><u>Updated Revolutionize Your Videos Best Free Special Effects Apps for Mobile</u></a></li>
<li><a href="https://discover-help.techidaily.com/western-digital-top-migration-software-solutions-for-ssds/"><u>Western Digital: Top Migration Software Solutions for SSDs</u></a></li>
<li><a href="https://win11.techidaily.com/why-arent-window-11-thumbnail-images-displayed-solutions-available/"><u>Why Aren't Window 11 Thumbnail Images Displayed? Solutions Available!</u></a></li>
</ul></div>

