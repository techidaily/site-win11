---
title: Expert Tips on Accessing Windows 11 Homescreen
date: 2024-08-16T00:39:30.735Z
updated: 2024-08-17T00:39:30.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips on Accessing Windows 11 Homescreen
excerpt: This Article Describes Expert Tips on Accessing Windows 11 Homescreen
keywords: Win11 Homescreen Tricks,Access Windows 11 Ease,Navigate Home Screen Quickly,Expert Window 11 Tips,Optimize Windows 11 Viewing,Master Windows 11 Interface,Speed Up Windows 11 Homescreen
thumbnail: https://thmb.techidaily.com/13322664753ec1bcb9b951122efdf005d8bc61a3a13c44fac0ae0c8584b8720e.jpg
---

## Expert Tips on Accessing Windows 11 Homescreen

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-electronic-conference-logging/"><u>[New] 2024 Approved  Electronic Conference Logging</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-how-to-download-gif-images-from-twitter/"><u>[New] 2024 Approved  How to Download GIF Images From Twitter</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-transform-your-videos-expert-choices-for-thumbnails/"><u>[New] 2024 Approved  Transform Your Videos  Expert Choices for Thumbnails</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/oundless-creativity-celebrating-our-top-10-female-youtubers/"><u>[New] Boundless Creativity  Celebrating Our Top 10 Female YouTubers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-techniques-for-epochal-transition-scenes/"><u>[New] Techniques for Epochal Transition Scenes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715859938087-new-top-ios-psp-games-and-emulators-revealed/"><u>[New] Top iOS PSP Games & Emulators Revealed!</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-elevate-video-quality-mastering-fb-1080p-streams/"><u>[Updated] 2024 Approved  Elevate Video Quality  Mastering FB 1080P Streams</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cinematography-secrets-unveiled-by-youtube-pros-for-2024/"><u>[Updated] Cinematography Secrets Unveiled by YouTube Pros for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-curating-striking-instagram-profile-photos-for-2024/"><u>[Updated] Curating Striking Instagram Profile Photos for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-crafting-memorable-visual-narratives-with-instagram-captions/"><u>[Updated] In 2024, Crafting Memorable Visual Narratives with Instagram Captions</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-eyelaughs-funny-image-generator/"><u>[Updated] In 2024, EyeLaughs  Funny Image Generator</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-highlighting-the-best-practices-in-screen-recording-facetime-calls/"><u>[Updated] In 2024, Highlighting the Best Practices in Screen Recording FaceTime Calls</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pros-best-top-8-tripods-excelling-at-4k-video-capture/"><u>[Updated] Pro's Best  Top 8 Tripods Excelling at 4K Video Capture</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-seamless-integration-transferring-snapchat-images-directly-for-2024/"><u>[Updated] Seamless Integration  Transferring Snapchat Images Directly for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-a-beginners-guide-to-starting-a-professional-account-on-ig/"><u>2024 Approved  A Beginner's Guide to Starting a Professional Account on IG</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-breaking-tiktok-trends-twitters-1-list-unveiled/"><u>2024 Approved  Breaking TikTok Trends  Twitter's #1 List Unveiled</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-creating-composition-magic-leading-lines-on-iphone/"><u>2024 Approved  Creating Composition Magic  Leading Lines on iPhone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-pace-your-panorama-learning-time-lapses-on-samsung-phones/"><u>2024 Approved  Pace Your Panorama  Learning Time-Lapses on Samsung Phones</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-clips-captured-a-no-cost-screencasting-tutorial/"><u>2024 Approved  YouTube Clips, Captured  A No-Cost Screencasting Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/7-ultimate-remedies-for-a-disconnected-usb-wi-fi-adapter-in-windows/"><u>7 Ultimate Remedies for a Disconnected USB Wi-Fi Adapter in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-primer-on-locating-and-navigating-components-management-console/"><u>A Primer on Locating & Navigating Components Management Console</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-microsofts-innovative-ai-integration-for-windows-11-taskbar/"><u>Accelerating Workflow: Microsoft's Innovative AI Integration for Windows 11 Taskbar</u></a></li>
<li><a href="https://extra-hints.techidaily.com/affordable-asmr-microphones-with-peak-performance-quality-crest/"><u>Affordable ASMR Microphones with Peak Performance, Quality Crest</u></a></li>
<li><a href="https://win11.techidaily.com/betrayed-by-touch-the-latest-vulnerabilities-in-windows-fingerprint-tech/"><u>Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-no-notification-policy-for-ws11-cameras/"><u>Bypassing No-Notification Policy for WS11 Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-local-data-exchange-protocols-google-and-windows-showdown/"><u>Comparing Local Data Exchange Protocols: Google & Windows Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-the-windows-11-taskbars-search-icon/"><u>Concealing the Windows 11 Taskbar's Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/curating-a-personal-touch-for-windows-mouse-pointer/"><u>Curating a Personal Touch for Windows Mouse Pointer</u></a></li>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-booting-mechanics-and-settings/"><u>Delving Deep Into Windows' Booting Mechanics and Settings</u></a></li>
<li><a href="https://win11.techidaily.com/easing-shared-printer-usage-conflict/"><u>Easing Shared Printer Usage Conflict</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-safety-blocks-set-by-high-ranking-admins/"><u>Easing Windows Safety Blocks Set By High-Ranking Admins</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-drawing-on-windows-desktop/"><u>Elevate Your Workspace: Drawing on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-smooth-operational-flow-for-wsl-after-win-11s-installation/"><u>Ensuring a Smooth Operational Flow for WSL After Win 11'S Installation</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-unchanged-environment-powertoys-settings-replication/"><u>Ensuring Unchanged Environment: PowerToys Settings Replication</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-android-and-ios-timers-your-guide-to-flawless-big-day-management/"><u>Essential Android & iOS Timers  Your Guide to Flawless Big Day Management</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-to-windows-11s-auto-hdr-techniques/"><u>Essential Guide to Windows 11'S Auto HDR Techniques</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/expert-advice-seamless-srt-file-sharing-across-all-social-networks-for-2024/"><u>Expert Advice  Seamless SRT File Sharing Across All Social Networks for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/explore-these-7-premier-prompt-based-ai-marketplaces/"><u>Explore These 7 Premier Prompt-Based AI Marketplaces</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-incorrectly-assigned-speaker-error-windows-style/"><u>Fixing Incorrectly Assigned Speaker Error, Windows Style</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-power-spike-issues-during-multiplayer-adventures/"><u>Fixing Power Spike Issues During Multiplayer Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/from-windows-to-kali-an-installation-journey/"><u>From Windows to Kali: An Installation Journey</u></a></li>
<li><a href="https://win11.techidaily.com/guide-recovering-invisible-bluetooth-in-device-manager/"><u>Guide: Recovering Invisible Bluetooth in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reinstate-missing-mfc71udll-in-windows/"><u>How to Reinstate Missing Mfc71u.dll in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-vm-picks-to-enhance-your-windows-11-experience/"><u>Ideal VM Picks to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-visual-magic-for-your-videos-online/"><u>In 2024, Free Visual Magic for Your Videos Online</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-apple-id-from-iphone-xr-without-password-by-drfone-ios/"><u>In 2024, How to Remove Apple ID from iPhone XR without Password?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-introducing-effortless-age-correction-in-profiles/"><u>In 2024, Introducing Effortless Age Correction in Profiles</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/in-2024-master-amazon-live-features-pro-tips-and-future-trends/"><u>In 2024, Master Amazon Live Features, Pro Tips and Future Trends</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-master-the-pinning-process-for-a-personal-touch-in-snapchat/"><u>In 2024, Master the Pinning Process for a Personal Touch in Snapchat</u></a></li>
<li><a href="https://win-dash.techidaily.com/insignia-graphics-card-to-monitor-cable-driver-download-and-setup-guide/"><u>Insignia Graphics Card to Monitor Cable Driver Download & Setup Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-and-configuring-razer-mice-drivers-on-windows-systems-fast-and-effortless-guide/"><u>Installing and Configuring Razer Mice Drivers on Windows Systems: Fast & Effortless Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/key-principles-for-powerful-video-testimonial-production/"><u>Key Principles for Powerful Video Testimonial Production</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-vivo-x-fold-2-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Vivo X Fold 2 FRP Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/learn-win-11s-network-proxy-configuration/"><u>Learn Win 11'S Network Proxy Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cr2-image-conversion-in-windows-pc/"><u>Mastering the Art of CR2 Image Conversion in Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-mic-silenced-tips-to-unmute-for-google-meet-on-pc/"><u>Microsoft Mic Silenced: Tips to Unmute for Google Meet on PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/motivate-and-master-your-movements-20-top-rated-workout-tracks/"><u>Motivate and Master Your Movements  20 Top-Rated Workout Tracks</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-errors-wows-glitches-in-windows-11/"><u>Navigating Through Errors: WoW's Glitches in Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-best-free-mov-editors-for-windows-and-mac-2023-update-for-2024/"><u>New The Best Free MOV Editors for Windows and Mac 2023 Update for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/opening-your-canvas-microsoft-paint-on-windows-11/"><u>Opening Your Canvas: Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-upgrades-techniques-for-ensuring-optional-components-on-windows-os/"><u>Optimal Upgrades: Techniques for Ensuring Optional Components on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-heat-drainage-in-windows-11-computers/"><u>Reducing Heat Drainage in Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-your-command-prompt-experience-win11/"><u>Resetting Your Command Prompt Experience (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-error-when-starting-speech-recognition/"><u>Resolving Windows Error When Starting Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-volume-settings-after-hiccups-in-windows-10/"><u>Restoring Volume Settings After Hiccups in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-windows-11-re-activate-ms-store-applications/"><u>Revive Your Windows 11: Re-Activate MS Store Applications</u></a></li>
<li><a href="https://win11.techidaily.com/solving-ad-ds-printer-glitches-on-windows-11/"><u>Solving AD DS Printer Glitches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-create-extract-and-manage-files-via-cli/"><u>Step-by-Step Guide to Create, Extract and Manage Files via CLI</u></a></li>
<li><a href="https://win11.techidaily.com/step-wise-approach-to-adding-icons-to-windows-11-taskbar/"><u>Step-Wise Approach to Adding Icons to Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-implementing-animated-wallpapers-on-desktop/"><u>Windows 11 Guide: Implementing Animated Wallpapers on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-shortcuts-for-the-savvy-editor/"><u>Windows Photos Shortcuts for the Savvy Editor</u></a></li>
</ul></div>
