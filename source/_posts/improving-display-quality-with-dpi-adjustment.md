---
title: Improving Display Quality with DPI Adjustment
date: 2024-11-03T23:36:27.223Z
updated: 2024-11-07T20:28:58.342Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Improving Display Quality with DPI Adjustment
excerpt: This Article Describes Improving Display Quality with DPI Adjustment
keywords: Display DPI Boosting,Screen Resolution Optimize,Enhance Pixel Density,High-Quality Displays,DPI Quality Improvement,Clear Visuals Adjustment,Image Clarity DPI Increase
thumbnail: https://thmb.techidaily.com/98a12915cb3d2cb54c3468dae6fd64cafa98af7144806238fd48ac7236bdda16.jpg
---

## Improving Display Quality with DPI Adjustment

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037319/7443" target="_top" id="2037319">
  <img src="//a.impactradius-go.com/display-ad/7443-2037319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should[back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
| Value data | DPI scale                  |  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

| ---------- | -------------------------- |  
| 96         | Smaller 100% (Recommended) |  
| 120        | Medium 125%                |  
| 144        | Larger 150%                |  
| 192        | Extra Large 200%           |  
| 240        | Custom 250%                |  
| 288        | Custom 300%                |  
| 384        | Custom 400%                |  
| 480        | Custom 500%                |
2. When you're done making these changes, click**OK** to save them.
3. Next, double-click**Win8DpiScaling** in the right pane. If you don't see the Win8DpiScaling DWORD key there, you must create it manually in the same way as you created LogPixels.  
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

## Scale the Display DPI on Windows

 If you're in search of ways to give your screen a sharper and crisper look, change the DPI scaling! You can customize different elements displayed on your device like text size, icons, and more so that it's easier for you to read and navigate.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-exclusive-selection-of-fastest-screen-capture-apps-for-2024/"><u>[New] Exclusive Selection of Fastest Screen Capture Apps for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-integrating-tracks-into-video-production-in-premiere-pro-for-2024/"><u>[New] Integrating Tracks Into Video Production in Premiere Pro for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-ultimate-audio-experience-budget-friendly-asmr-mics-reviewed-for-2024/"><u>[Updated] Ultimate Audio Experience Budget-Friendly ASMR Mics Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-inspect-and-purging-windows-10-activities/"><u>Comprehensive Guide to Inspect & Purging Windows 10 Activities</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-redmi-note-12-4g-has-native-hevc-support-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Does Redmi Note 12 4G has native HEVC support?</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-infinix-hot-40-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/hibernation-vs-standby-windows-comparisons/"><u>Hibernation Vs. Standby: Windows Comparisons</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-purify-windows-ram-cache-quickly/"><u>How to Purify Windows' RAM Cache Quickly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-train-your-dragon-movies-in-order/"><u>How to Train Your Dragon Movies in Order</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-a-comprehensive-guide-for-free-video-translator-downloading/"><u>New A Comprehensive Guide for Free Video Translator Downloading</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/1728497459717-ntfs/"><u>NTFS刻面修复指南-如何找回无意删除的分区部分</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-group-policy-settings-on-individual-windows-accounts/"><u>Personalizing Group Policy Settings on Individual Windows Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-audacitys-error-when-opening-sounds-on-win11/"><u>Remedying Audacity's Error When Opening Sounds on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/safe-windows-best-free-software-download-picks/"><u>Safe Windows: Best Free Software Download Picks</u></a></li>
<li><a href="https://win11.techidaily.com/switching-chromes-block-webp-format-for-saved-pics-windows-based/"><u>Switching Chromes: Block WebP Format for Saved Pics, Windows-Based</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-shoppers-list-the-finest-cable-modemrouter-sets/"><u>Ultimate Shopper's List: The Finest Cable Modem/Router Sets</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-digital-files-onedrive-fixes-for-windows/"><u>Unlocking Your Digital Files: OneDrive Fixes for Windows</u></a></li>
</ul></div>

