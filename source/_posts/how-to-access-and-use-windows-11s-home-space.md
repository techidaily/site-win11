---
title: How to Access and Use Windows 11'S Home Space
date: 2024-08-15T23:48:40.071Z
updated: 2024-08-16T23:48:40.071Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Access and Use Windows 11'S Home Space
excerpt: This Article Describes How to Access and Use Windows 11'S Home Space
keywords: Windows 11 Home Spaces,Navigate Windows 11,Using Home Hub,Windows 11 Privacy Sphere,Accessing Space Bar,Win 11 Home Area,Utilize Windows 11 Zone
thumbnail: https://thmb.techidaily.com/4701af21fbd3236ee27b5d0a75fe2af600bece4b4b8021497e0ee7ed3f0b2671.jpg
---

## How to Access and Use Windows 11'S Home Space

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
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
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-constructing-emotional-resonance-trailer-sound-selection-guide/"><u>[New] 2024 Approved  Constructing Emotional Resonance  Trailer Sound Selection Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-non-copyrighted-meditation-sounds/"><u>[New] 2024 Approved  Non-Copyrighted Meditation Sounds</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-mastering-fbx-capturing-games-live/"><u>[New] In 2024, Mastering FBX  Capturing Games Live</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-professional-tips-to-perfect-igtv-thumbnails/"><u>[New] In 2024, Professional Tips to Perfect IGTV Thumbnails</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-gain-insight-into-your-contents-success-via-youtube-rankers/"><u>[Updated] 2024 Approved  Gain Insight Into Your Content's Success via YouTube Rankers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-navigating-through-the-top-5-new-facebook-shifts/"><u>[Updated] 2024 Approved  Navigating Through the Top 5 New Facebook Shifts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-achieving-seamless-360-streaming-on-facebook-for-2024/"><u>[Updated] Achieving Seamless 360 Streaming on Facebook for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-quality-audio-awaits-with-these-premium-asmr-mics/"><u>[Updated] Quality Audio Awaits with These Premium ASMR Mics</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-capturing-photographs-from-movies-in-windows-photos-app-for-savvy-users/"><u>2024 Approved  Capturing Photographs From Movies in Windows Photos App for Savvy Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-top-android-recorder-commercial-free/"><u>2024 Approved  Top Android Recorder - Commercial-Free</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ace-your-application-with-these-6-creative-uses-of-chatgpt-in-job-searches/"><u>Ace Your Application with These 6 Creative Uses of ChatGPT in Job Searches</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-marketplace-failures-error-0x80073cf3/"><u>Deciphering and Resolving Windows Marketplace Failures (Error 0X80073CF3)</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-security-patches/"><u>Demystifying Windows Security Patches</u></a></li>
<li><a href="https://screen-capture.techidaily.com/displayinspector-critique-service/"><u>DisplayInspector Critique Service</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-0x80070194-in-onedrive-errors/"><u>Eliminating Windows' 0X80070194 in OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-change-installing-and-utilizing-themes-from-the-ms-store/"><u>Embracing Change: Installing and Utilizing Themes From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-programming-with-a-newly-installed-jdk-in-windows-11/"><u>Enhance Your Programming with a Newly Installed JDK in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-adobe-photoshop-in-windows-11-and-11/"><u>Fixing Unresponsive Adobe Photoshop in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/fundamental-concepts-in-windows-display-idleness/"><u>Fundamental Concepts in Windows Display Idleness</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-solving-blue-screens-caused-by-not-handled-error/"><u>Guide to Solving Blue Screens Caused by Not Handled Error</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-oneplus-12withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on OnePlus 12with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-or-showing-time-and-date-on-win-11-ui-bar/"><u>Hiding or Showing Time & Date on Win 11 UI Bar</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-honor-v-purse-by-drfone-android/"><u>How to Bypass FRP from Honor V Purse?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-oppo-a1x-5g-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Oppo A1x 5G Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-infinix-smart-8-plus-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Infinix Smart 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-failed-vms-from-vmware-in-windows-11/"><u>How to Resolve Failed VMs From VMware in Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-tecno-spark-10-pro-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Tecno Spark 10 Pro FRP Bypass With Best Methods</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-itel-a70-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Itel A70 Location Settings | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-from-download-to-implementation-installing-obs-on-a-macpc/"><u>In 2024, From Download to Implementation  Installing OBS on a MacPC</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-slick-quick-fades-in-premiere/"><u>In 2024, Slick Quick Fades in Premiere</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-xiaomi-redmi-note-13-pro-5g-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Xiaomi Redmi Note 13 Pro 5G to Gmail | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-file-explorer-with-onedrive-integration/"><u>Initiating File Explorer with OneDrive Integration</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-samsung-galaxy-a34-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Samsung Galaxy A34 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-gaming-with-playnite-and-emulators/"><u>Maximizing Windows Gaming with Playnite and Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/muting-file-explorer-tabs-in-windows-11-guide/"><u>Muting File Explorer Tabs in Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-active-directory-printer-failures/"><u>Navigating and Resolving Active Directory Printer Failures</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-for-rapid-epic-games-access/"><u>Optimizing Windows for Rapid Epic Games Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-microsoft-store-access-blockades/"><u>Overcoming Microsoft Store Access Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/reawakening-computers-top-8-windows-restart-techniques/"><u>Reawakening Computers: Top 8 Windows Restart Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-your-login-experience-opting-for-stronger-protection-over-windows-11s-default-pin/"><u>Reimagining Your Login Experience: Opting for Stronger Protection over Windows 11'S Default PIN</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-windows-11s-system-tray-secrets/"><u>Revealing Windows 11'S System Tray Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-sticky-windows-credential-puzzle/"><u>Reversing Sticky Windows Credential Puzzle</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-keys-in-windows-10-and-11-with-7-hacks/"><u>Speeding Up Keys in Windows 10 & 11 with 7 Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/spruce-up-your-windows-mail-and-schedule-with-pics/"><u>Spruce Up Your Window's Mail & Schedule With Pics</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-storage-efficiently-identifying-large-disk-users/"><u>Streamline Your Storage: Efficiently Identifying Large Disk Users</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-the-steam-deck-experience-with-keyboard-settings-optimization/"><u>Streamlining the Steam Deck Experience with Keyboard Settings Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-windows-11-interface-for-maximum-comfort/"><u>Tailoring Your Windows 11 Interface for Maximum Comfort</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-local-users-and-groups-on-win1110/"><u>The Complete Guide to Local Users and Groups on WIN11/10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-comprehensive-guide-to-understanding-how-large-language-models-work/"><u>The Comprehensive Guide to Understanding How Large Language Models Work</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unseen-drives-in-windows/"><u>Troubleshooting: Unseen Drives in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-oneplus-12r-frp-bypass-by-drfone-android/"><u>Ultimate Guide on OnePlus 12R FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-vac-refusal-on-windows/"><u>Understanding and Rectifying VAC Refusal on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-microsofts-copilot-key-insights-for-windows-11-users/"><u>Unlocking Microsoft's Copilot Key: Insights for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-successful-oculus-installer-on-ws11ws10/"><u>Unlocking Successful Oculus Installer on WS11/WS10</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlocking-the-secrets-of-our-ancient-communication/"><u>Unlocking the Secrets of Our Ancient Communication</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-of-windows-error-0xca00a009/"><u>Unpacking the Mystery of Windows Error 0xCA00A009</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>Which Pokémon can Evolve with a Moon Stone For Apple iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/why-mondly-stands-out-in-language-education-app-field/"><u>Why Mondly Stands Out in Language Education App Field?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-screen-sharing-disabling-pin-during-cast/"><u>Windows 11 Screen Sharing: Disabling PIN During Cast</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-custom-shortcut-for-safe-hardware-disconnect/"><u>Windows 11: Custom Shortcut for Safe Hardware Disconnect</u></a></li>
<li><a href="https://win11.techidaily.com/winstall-workflows-for-smooth-windows-11-app-installation/"><u>Winstall Workflows for Smooth Windows 11 App Installation</u></a></li>
</ul></div>
