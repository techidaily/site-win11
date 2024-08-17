---
title: Unlock Home View in Windows 11 Settings
date: 2024-08-16T00:38:06.316Z
updated: 2024-08-17T00:38:06.316Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Home View in Windows 11 Settings
excerpt: This Article Describes Unlock Home View in Windows 11 Settings
keywords: Unlock Window View,Windows 11 Screen Access,Enable Home Screens,Windows Settings Viewing,Windows 11 Home Screen,Enter Home View Mode,Toggle Home Display
thumbnail: https://thmb.techidaily.com/fb9dc69321147c58e76f643c816e11fbbc732b6fd56c746767b53b83551e6f78.jpg
---

## Unlock Home View in Windows 11 Settings

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-elevate-your-social-standing-with-1000-followersmth/"><u>[New] 2024 Approved  Elevate Your Social Standing with 1,000 Followers/Mth</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-full-length-video-view-remove-youtube-preview/"><u>[New] 2024 Approved  Full-Length Video View  Remove YouTube Preview</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-21-pioneering-metaverse-ventures-for-insightful-discussion/"><u>[New] 21 Pioneering Metaverse Ventures for Insightful Discussion</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-convenient-procedures-for-recording-screen-chats/"><u>[New] In 2024, Convenient Procedures for Recording Screen Chats</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-jumpstarting-instagram-celebrity-status-for-2024/"><u>[New] Jumpstarting Instagram Celebrity Status for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-pathway-to-pinnacle-chromatic-precision/"><u>[New] The Pathway to Pinnacle Chromatic Precision</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-crossing-platforms-upload-video-to-twittertumblr/"><u>[Updated] 2024 Approved  Crossing Platforms  Upload Video to Twitter/Tumblr</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-advancing-google-meet-sessions-implementing-effects-and-masks/"><u>[Updated] Advancing Google Meet Sessions  Implementing Effects & Masks</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-ensuring-perfect-fb-live-recordings-a-guide-to-4-ways/"><u>[Updated] Ensuring Perfect FB Live Recordings  A Guide to 4 Ways</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-access-royalty-free-beats-for-your-vlog-and-more/"><u>[Updated] In 2024, Access Royalty-Free Beats for Your Vlog & More</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-pro-screencast-strategies-secrets-for-video-creators-for-2024/"><u>[Updated] Pro Screencast Strategies  Secrets for Video Creators for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-secrets-of-selecting-the-best-nba-live-feed/"><u>[Updated] Secrets of Selecting the Best NBA Live Feed</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-ultimate-shortcut-to-instagram-video-connectivity-for-2024/"><u>[Updated] The Ultimate Shortcut to Instagram Video Connectivity for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tune-into-unparalleled-music-video-watching-best-android-vids-for-you/"><u>[Updated] Tune Into Unparalleled Music Video Watching  Best Android Vids for You</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-comprehensive-fb-messenger-recordings-explained/"><u>2024 Approved  Comprehensive FB Messenger Recordings Explained</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-effortless-viewing-tackling-instagram-video-issues/"><u>2024 Approved  Effortless Viewing  Tackling Instagram Video Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-supercharge-your-design-with-these-canva-insider-tips/"><u>2024 Approved  Supercharge Your Design with These Canva Insider Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-tier-laptops-and-pcs-for-ultimate-comfort/"><u>2024 Approved  Top-Tier Laptops & PCs for Ultimate Comfort</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-future-skies-top-weather-apps-for-pc/"><u>A Window Into Future Skies: Top Weather Apps for PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-cheap-traps-the-realities-of-inferior-windows-activation-codes/"><u>Avoid Cheap Traps: The Realities of Inferior Windows Activation Codes</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-realme-narzo-n55-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Realme Narzo N55 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/chocolatey-vs-windows-package-manager-which-is-the-better-tool-to-download-software-on-windows/"><u>Chocolatey Vs. Windows Package Manager: Which Is the Better Tool to Download Software on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-secure-boot-the-ultimate-rufus-guidebook/"><u>Conquering Secure Boot: The Ultimate Rufus Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-fatal-javascript-issue-on-windows-11s-discord-app/"><u>Easing the Fatal Javascript Issue on Windows 11'S Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-vm-management-hosting-linux-on-a-windows-system-with-hyper-v/"><u>Efficient VM Management: Hosting Linux on a Windows System with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-not-enough-privileges-error-during-installation-on-windows/"><u>Eliminating Not Enough Privileges Error During Installation on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/esd-files-demystified-creating-iso-versions-for-windows-systems/"><u>ESD Files Demystified: Creating ISO Versions for Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/ethernet-efficiency-top-tips-to-test-your-networks-pace-on-windows/"><u>Ethernet Efficiency: Top Tips to Test Your Network's Pace on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-vivo-y55s-5g-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-a23-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy A23 5G Pattern Lock Screen</u></a></li>
<li><a href="https://win-dash.techidaily.com/freshly-updated-magiccard-rio-pro-driving-simulator-now-available-supports-windows-operating-systems-including-11-8-the-title-magicard-rio-pro-driver-latest277/"><u>Freshly Updated Magiccard Rio Pro Driving Simulator Now Available – Supports Windows Operating Systems Including 11, 8. The Title Magicard Rio Pro Driver | Latest Download | For Windows 11, 8.1 and 7 Could Be Rephrased As:</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-asus-rog-phone-8-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-win11s-network-settings/"><u>Guiding Through Win11's Network Settings</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/immediate-improvement-photo-colors-in-photoshop-for-2024/"><u>Immediate Improvement  Photo Colors in Photoshop for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-complete-insight-the-full-picture-of-bublcam-360/"><u>In 2024, Complete Insight  The Full Picture of Bublcam 360</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-next-gen-fb-converter-transform-vids-to-premium-mp4/"><u>In 2024, Next-Gen FB Converter  Transform Vids to Premium MP4</u></a></li>
<li><a href="https://youtube-help.techidaily.com/inquiry-youtubes-payment-scheme-for-creators-for-2024/"><u>Inquiry  YouTube's Payment Scheme for Creators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microphone-settings-in-w11-systems/"><u>Mastering Microphone Settings in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-switch-for-regedit-on-win11/"><u>Mastering the Switch for RegEdit on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-error-0x8007251d-windows-activation-demystified/"><u>Mastery over Error 0X8007251D: Windows Activation Demystified</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-driver-not-running-error-in-windows-11/"><u>Solutions for Driver Not Running Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-not-writable-file-problems-in-windows-11/"><u>Solutions for Not Writable File Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://extra-hints.techidaily.com/taking-views-viral-the-ultimate-guide-for-youtube-success/"><u>Taking Views Viral  The Ultimate Guide for YouTube Success</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-erroneous-temporary-folders-in-windows-11/"><u>Troubleshooting Erroneous Temporary Folders in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-store-access-on-windows-11/"><u>Troubleshooting Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-mail-issues-with-html-enhanced-emails/"><u>Troubleshooting Windows 11 Mail Issues with HTML-Enhanced Emails</u></a></li>
<li><a href="https://win11.techidaily.com/twinkling-tokens-gifting-windows-games-via-mstore/"><u>Twinkling Tokens: Gifting Windows Games via MSTORE</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-pop-8-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Pop 8.</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/vimeo-cash-flow-maximizing-income-through-content-marketing-for-2024/"><u>Vimeo Cash Flow  Maximizing Income Through Content Marketing for 2024</u></a></li>
</ul></div>
