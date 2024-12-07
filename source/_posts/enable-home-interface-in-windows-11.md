---
title: Enable Home Interface in Windows 11
date: 2024-12-06T01:37:37.723Z
updated: 2024-12-07T03:24:31.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Home Interface in Windows 11
excerpt: This Article Describes Enable Home Interface in Windows 11
keywords: Windows 11 Interface,Homespace W11,W11 UI Control,Interactive W11 Hub,Home Settings W11,Windows Home Access,W11 Intuitive Space
thumbnail: https://thmb.techidaily.com/de901a9dfeb58de3e9633af24cac79c38827e6567ccf0cdebe9976885fce2e39.png
---

## Enable Home Interface in Windows 11

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-navigating-google-meets-virtual-whiteboards-across-appleandroid-and-laptops/"><u>[New] 2024 Approved Navigating Google Meet's Virtual Whiteboards Across Apple/Android & Laptops</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-step-by-step-saving-tweet-vids-on-androids/"><u>[New] Step-By-Step Saving Tweet Vids on Androids</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-identifying-if-someone-has-removed-you-from-their-snap-circle/"><u>[Updated] 2024 Approved Identifying if Someone Has Removed You From Their Snap Circle</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-eliminated-non-display-of-shorts-videos/"><u>[Updated] In 2024, Eliminated Non-Display of Shorts Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-seamless-sharing-of-oversized-content-from-iphone-to-macos/"><u>[Updated] Seamless Sharing of Oversized Content From iPhone to macOS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/crossing-over-attending-tiktok-live-gigs-easily/"><u>Crossing Over Attending TikTok Live Gigs Easily</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cryptic-code-deciphered-direct-x-error-eradicated-in-league/"><u>Cryptic Code Deciphered: Direct X Error Eradicated in League</u></a></li>
<li><a href="https://blog-min.techidaily.com/free-conversion-of-m4v-files-to-mkv-format-quick-and-easy-with-movavi/"><u>Free Conversion of M4V Files to MKV Format: Quick & Easy with Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-a-non-responsive-windows-service/"><u>How to Reactivate a Non-Responsive Windows Service</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-xs-to-mac-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone XS to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-updates-via-batch-installation-using-winstall/"><u>Streamlining Windows 11 Updates via Batch Installation Using Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-your-taskbar-space-include-google-mail-in-edge-setup/"><u>Tailor Your Taskbar Space: Include Google Mail in Edge Setup</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-verification-failures-for-windows-installs/"><u>Troubleshooting Verification Failures for Windows Installs</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-e84-errors-in-windows-based-steam-clients/"><u>Unraveling E84 Errors in Windows-Based Steam Clients</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    