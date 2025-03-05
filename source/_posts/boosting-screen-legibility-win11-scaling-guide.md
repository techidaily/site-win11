---
title: "Boosting Screen Legibility: Win11 Scaling Guide"
date: 2025-03-03T22:30:34.395Z
updated: 2025-03-05T03:57:01.608Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Screen Legibility: Win11 Scaling Guide"
excerpt: "This Article Describes Boosting Screen Legibility: Win11 Scaling Guide"
keywords: Win11 Text Enhance,Screen Readability Boost,Optimal Win11 Display,Windows Scaling Tips,Legible Win11 Screens,Clear Win11 Graphics,Adjust Win11 Resolution
thumbnail: https://thmb.techidaily.com/96d4e4e3696a3d428399dbec4c54090942565cd5b197d0762ff7457e8ce649a0.jpg
---

## Boosting Screen Legibility: Win11 Scaling Guide

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

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

## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should [back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-revel-in-reality-an-extensive-review-of-lgs-high-fidelity-monitor-31mu97-b/"><u>[New] 2024 Approved Revel in Reality - An Extensive Review of LG's High-Fidelity Monitor, 31MU97-B</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-achieve-striking-visuals-your-guide-to-uploading-at-correct-dimensions/"><u>[Updated] Achieve Striking Visuals Your Guide to Uploading at Correct Dimensions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-discover-the-ace-of-virtual-worlds-top-oculus-headsets/"><u>[Updated] Discover the Ace of Virtual Worlds Top Oculus Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/eye-on-windows-authentication-spotting-right-and-wrong-calls/"><u>Eye on Windows Authentication: Spotting Right & Wrong Calls</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-can-we-unlock-our-lava-blaze-curve-5g-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Lava Blaze Curve 5G Phone Screen?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-4-ways-for-apple-iphone-14-pro-to-mac-mirroring-drfone-by-drfone-ios/"><u>In 2024, Top 4 Ways for Apple iPhone 14 Pro to Mac Mirroring | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/pixel-chronicles-mastering-the-art-of-recording-your-minecraft-world-for-2024/"><u>Pixel Chronicles Mastering the Art of Recording Your Minecraft World for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/prompt-engineering-mastery-for-ai-enthusiasts-career-longevity-prospects/"><u>Prompt Engineering Mastery for AI Enthusiasts: Career Longevity Prospects</u></a></li>
<li><a href="https://win11.techidaily.com/realigning-your-gaming-experience-solve-xbox-error-on-win11/"><u>Realigning Your Gaming Experience: Solve Xbox Error on Win11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/rtx-2070-super-graphics-card-driver-download-for-windows-operating-systems/"><u>RTX 2070 Super Graphics Card Driver Download for Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/swift-route-to-rectify-black-screen-and-cursor-on-win11/"><u>Swift Route to Rectify Black Screen and Cursor on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-frozen-wow-installation-delays/"><u>Tackling Frozen WoW Installation Delays</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-hypervisor-in-windows-sandbox-setup/"><u>Troubleshooting Missing Hypervisor in Windows Sandbox Setup</u></a></li>
<li><a href="https://fox-blue.techidaily.com/unveiling-5-leading-photo-experts-who-sync-music-perfectly/"><u>Unveiling 5 Leading Photo Experts Who Sync Music Perfectly</u></a></li>
<li><a href="https://win11.techidaily.com/windows-setup-made-easy-your-steam-deck-guide/"><u>Windows Setup Made Easy: Your Steam Deck Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-boltgun-beating-latency-issues-in-warhammer-40k-on-windows/"><u>Winning at Boltgun: Beating Latency Issues in Warhammer 40K on Windows</u></a></li>
</ul></div>

