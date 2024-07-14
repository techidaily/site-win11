---
title: Personalizing Your Win11 Screen Scaling Preference
date: 2024-07-13T10:40:40.365Z
updated: 2024-07-14T10:40:40.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalizing Your Win11 Screen Scaling Preference
excerpt: This Article Describes Personalizing Your Win11 Screen Scaling Preference
keywords: Win11 Customize View,Set Win11 Scale Size,Win11 Display Preferences,Windows Personalization Settings,Adjust Win11 Screen Size,Windows Scaling Options,Tailor Win11 Resolution
thumbnail: https://thmb.techidaily.com/c2522eefb8fbc96fa570f56849cfdf92d72e221bd3a27b7e0b7d3fec1332bd02.png
---

## Personalizing Your Win11 Screen Scaling Preference

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
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-determining-the-ideal-image-aspect-ratio-a-step-by-step-guide-for-2024/"><u>New Determining the Ideal Image Aspect Ratio A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-7-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone 7 iOS System? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-resolving-upgrade-error-in-windows-os/"><u>A Step-By-Step Guide to Resolving Upgrade Error in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/1719366255245-functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now!</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-iphone-imaging-insights-for-professionals/"><u>2024 Approved  IPhone Imaging Insights for Professionals</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-fun-and-easy-masking-tricks-in-filmora/"><u>New 2024 Approved Fun & Easy Masking Tricks in Filmora</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-netflix-subtitle-translation-methods-comprehensive-guide/"><u>new Netflix Subtitle Translation Methods Comprehensive Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-clearing-the-path-free-facebook-videos-from-interruptions/"><u>[Updated] In 2024, Clearing the Path  Free Facebook Videos From Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-black-desktop-background-display-issue-on-windows/"><u>8 Ways to Fix the Black Desktop Background Display Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-viral-potential-hashtags-for-gamers-vlogs/"><u>[Updated] Unlocking Viral Potential  Hashtags for Gamers' Vlogs</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-honor-90-gt-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-face-unlock-tech-iphone-xs-face-id-versus-samsung/"><u>[New] Face Unlock Tech  IPhone X's Face ID Versus Samsung'</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-guide-to-add-transition-effects-in-premiere-pro/"><u>Updated Guide to Add Transition Effects in Premiere Pro</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-methods-for-turning-vimeo-content-into-mp3-for-2024/"><u>[Updated] Methods for Turning Vimeo Content Into MP3 for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/crafting-serenity-a-spiritual-journey-through-6-intellectually-designed-minecraft-modern-houses-for-2024/"><u>Crafting Serenity  A Spiritual Journey Through 6 Intellectually Designed Minecraft Modern Houses for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-iphone-xs-max-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or iPhone XS Max without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/diving-into-user-preferences-a-tiktok-vs-snapchat-breakdown-for-2024/"><u>Diving Into User Preferences  A TikTok Vs Snapchat Breakdown for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-chasing-channel-currency-the-updated-youtube-partner-guide/"><u>[Updated] Chasing Channel Currency  The Updated Youtube Partner Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-untangling-insta-vids-selfies-validity-questioned/"><u>In 2024, Untangling Insta Vids  Selfies' Validity Questioned</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
</ul></div>
