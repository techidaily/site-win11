---
title: Modify Display Scaling in Windows 11
date: 2024-12-02T06:42:57.880Z
updated: 2024-12-07T04:13:12.268Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify Display Scaling in Windows 11
excerpt: This Article Describes Modify Display Scaling in Windows 11
keywords: Win11 Screen Resize,Window Scaling Fix,Adjust Display Settings,Change Win11 Size,Optimize Windows View,Modify Win11 Layout,Tune Display in Windows 11
thumbnail: https://thmb.techidaily.com/4815bdc4b07f62378c934e8844c6ab3ed5ccd8bb0ecbd12c41105ddecee78795.jpg
---

## Modify Display Scaling in Windows 11

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-ethereal-eclipses-the-ultimate-hdr-sky-imagery-hubs/"><u>[Updated] 2024 Approved Ethereal Eclipses - The Ultimate HDR Sky Imagery Hubs</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-avoid-delays-swift-time-lapse-recording-on-iphone-for-2024/"><u>[Updated] Avoid Delays Swift Time-Lapse Recording on iPhone for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fast-track-controlling-netflix-playback-speeds/"><u>2024 Approved Fast Track - Controlling Netflix Playback Speeds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-new-world-effective-solutions-to-the-frustrating-easy-anti-cheat-launch-error/"><u>Conquering New World: Effective Solutions to the Frustrating Easy Anti-Cheat Launch Error</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-unwanted-edge-keyboard-hotkeys/"><u>Disabling Unwanted Edge Keyboard Hotkeys</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-smart-7-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Smart 7 Phone FRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-disk-space-efficiently-with-new-tool-on-windows-menus/"><u>Navigate Disk Space Efficiently with New Tool on Windows Menus</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-6-techniques-for-extracting-file-and-folder-paths-in-windows-11/"><u>Navigating: 6 Techniques for Extracting File & Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/outlook-races-against-time-win-tricks-to-speed-up/"><u>Outlook Races Against Time: WIN Tricks to Speed Up</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-unlocking-a-non-responsive-windows-console/"><u>Quick Tips: Unlocking a Non-Responsive Windows Console</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-microsoft-words-audio-readback-function/"><u>Reinstating Microsoft Word's Audio Readback Function</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/superior-web-based-recording-tools-the-leaders-2023-for-2024/"><u>Superior Web-Based Recording Tools - The Leaders 2023 for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-chronological-counterflow-technique-for-snapchat/"><u>The Chronological Counterflow Technique for Snapchat</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-top-contenders-in-mesh-wi-fi-networks-expert-insights-and-rankings/"><u>Unveiling the Top Contenders in Mesh Wi-Fi Networks - Expert Insights and Rankings</u></a></li>
</ul></div>

