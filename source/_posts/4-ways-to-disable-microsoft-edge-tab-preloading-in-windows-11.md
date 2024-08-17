---
title: 4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11
date: 2024-08-16T00:19:47.768Z
updated: 2024-08-17T00:19:47.768Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11
excerpt: This Article Describes 4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11
keywords: Disable Edge Tab Loading,Stop Edge Preload,Turn Off Edge Tabs,No Preloading in Edge,End Tab Load by Edge,Block Windows 11 Tab Start,Stop Edge Tab Activation
thumbnail: https://thmb.techidaily.com/2453bc5c0249af0de921ee166f14d8e128b375913b07ba9cca730be764e6c410.jpg
---

## 4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-groundbreaking-6-modern-mc-residentials/"><u>[New] Groundbreaking 6 Modern MC Residentials</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-best-5-web-video-recorders/"><u>[New] In 2024, Best 5 Web Video Recorders</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-in-depth-analysis-ultimate-storage-choices/"><u>[New] In-Depth Analysis  Ultimate Storage Choices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-panasonics-hx-a1-wearable-cam-examined-a-detailed-review/"><u>[New] Panasonic’s HX-A1 Wearable Cam Examined - A Detailed Review</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-selecting-your-favorite-free-game-capture-software/"><u>[Updated] 2024 Approved  Selecting Your Favorite Free Game Capture Software</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-becoming-a-wealthy-beauty-channel-host/"><u>2024 Approved  Becoming a Wealthy Beauty Channel Host</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-samsung-galaxy-m34-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Samsung Galaxy M34 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-api-unveiled-a-step-by-step-guide/"><u>ChatGPT API Unveiled: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-webcam-error-code-a00f4289-on-windows-11/"><u>Deciphering and Rectifying Webcam Error Code A00F4289 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-program-format-pe/"><u>Demystifying Windows Program Format (PE)</u></a></li>
<li><a href="https://extra-information.techidaily.com/digital-choices-for-content-creators-sound-or-sight-focus/"><u>Digital Choices for Content Creators  Sound or Sight Focus</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-accessing-cloud-drives-from-windows-drive-letters/"><u>Effortlessly Accessing Cloud Drives: From Windows Drive Letters</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elevate-your-editing-with-blend-mode-innovations-for-2024/"><u>Elevate Your Editing with Blend Mode Innovations for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/facing-the-falls-top-action-cameras-2023-for-2024/"><u>Facing the Falls  Top Action Cameras 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-hidden-icons-in-windows-11/"><u>Guiding Through Hidden Icons in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-nokia-c110-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Nokia C110 using Video Repair Utility on Windows? </u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-nokia-c12-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Nokia C12 Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-motorola-razr-40-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Motorola Razr 40 to PC? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Tecno Camon 20 Premier 5G? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-securing-a-seamless-srt-upload-experience-on-social-networks/"><u>In 2024, Securing a Seamless SRT Upload Experience on Social Networks</u></a></li>
<li><a href="https://win11.techidaily.com/is-voice-access-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is Voice Access Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-80211n-adapter-software-updates-for-smooth-wi-fi-connectivity-in-windows-systems/"><u>Latest 802.11N Adapter Software Updates for Smooth Wi-Fi Connectivity in Windows Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/modular-game-console-akkos-revolutionary-mod007b-board/"><u>Modular Game Console: Akko's Revolutionary MOD007B Board</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-silent-tab-disabling-in-windows-11/"><u>Navigating to Silent Tab Disabling in Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-windows-10-photos-not-your-cup-of-tea-try-these-8-alternatives-instead/"><u>New 2024 Approved Windows 10 Photos Not Your Cup of Tea? Try These 8 Alternatives Instead</u></a></li>
<li><a href="https://extra-information.techidaily.com/photographers-ultimate-cloud-companion-infinite-free-and-paid-sky-sanctuaries/"><u>Photographer’s Ultimate Cloud Companion  Infinite, Free & Paid Sky Sanctuaries</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-xiaomi-13-ultra-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Xiaomi 13 Ultra? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/regain-lost-dxgidll-with-effective-win11-tactics/"><u>Regain Lost Dxgi.dll with Effective Win11 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/regulating-pcs-to-prevent-windows-11-overheats/"><u>Regulating PCs to Prevent Windows 11 Overheats</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-admin-oversight-of-chromium-and-microsoft-edge-browsing-experience/"><u>Revamping Admin-Oversight of Chromium & Microsoft Edge Browsing Experience</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-the-w11-desktop-step-by-step-guide/"><u>Revamping the W11 Desktop: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/review-of-surface-laptop-go-3s-new-cpu-unchanged-shortcomings/"><u>Review of Surface Laptop Go 3'S New CPU - Unchanged Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-mouse-click-rate-with-just-a-few-tweaks/"><u>Skyrocket Mouse Click Rate with Just a Few Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-out-irregularities-a-guide-to-correction-of-windows-charmap-issues/"><u>Smoothing Out Irregularities: A Guide to Correction of Windows CharMap Issues</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-xbox-game-pass-x8007e9-error-in-windows/"><u>Solutions for Xbox Game Pass X8007E9 Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-users-from-adjusting-windows-time-and-date/"><u>Stopping Users From Adjusting Windows Time and Date</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-new-row-insertion-issues-in-excel-windows/"><u>Strategies for Fixing New Row Insertion Issues in Excel Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-disconnected-remote-resources-in-windows/"><u>Strategies to Address Disconnected Remote Resources in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streaming-windows-network-shares-from-smartphones/"><u>Streaming Windows Network Shares From Smartphones</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-complete-guide-to-new-ai-features-presented-by-apple-at-wwdc-2024/"><u>The Complete Guide to New AI Features Presented by Apple at WWDC 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-creating-a-unique-terminal-theme/"><u>The Guide to Creating a Unique Terminal Theme</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-freezing-and-black-steam-in-winos/"><u>Troubleshooting Freezing & Black Steam in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-quick-fixes-for-five-common-defender-disruptions/"><u>Troubleshooting Guide: Quick Fixes For Five Common Defender Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-approach-to-sound-channel-division/"><u>Understanding Windows’ Approach to Sound Channel Division</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-potential-a-complete-walkthrough-of-wpm-on-windows-os/"><u>Unlock Full Potential: A Complete Walkthrough of WPM on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-np-settings-a-simple-fix-guide/"><u>Windows NP Settings: A Simple Fix Guide</u></a></li>
</ul></div>
