---
title: Personalizing Your Win11 Screen Scaling Preference
date: 2024-06-25T11:38:02.627Z
updated: 2024-06-26T11:38:02.627Z
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
<li><a href="https://win11.techidaily.com/addressing-windows-file-error-xc10100bf/"><u>Addressing Windows File Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-mystery-of-the-blank-steam-window/"><u>Dealing With the Mystery of the Blank Steam Window</u></a></li>
<li><a href="https://win11.techidaily.com/1719319756779-revive-your-frozen-shift-key-on-pc/"><u>Revive Your Frozen Shift Key on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-mouse-customization-for-better-trail-control/"><u>A Simple Guide to Mouse Customization for Better Trail Control</u></a></li>
<li><a href="https://win11.techidaily.com/targeted-user-group-policies-implementing-changes-step-by-step/"><u>Targeted User Group Policies: Implementing Changes Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-mastering-vlc-how-to-play-videos-in-slow-motion-with-ease/"><u>Updated Mastering VLC How to Play Videos in Slow Motion with Ease</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-best-gaming-intro-creators-for-windows-and-mac-free-and-paid-options-for-2024/"><u>Updated Best Gaming Intro Creators for Windows and Mac Free and Paid Options for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-experts-list-12-offline-screen-capturing-choices/"><u>In 2024, Expert's List  12 Offline Screen Capturing Choices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/tadah-best-magic-tricks-of-youtube-video-editors-ever/"><u>TADAH! Best Magic Tricks of YouTube Video Editors EVER</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-time-saving-ways-to-log-vimeo-media-for-2024/"><u>[Updated] Time-Saving Ways to Log Vimeo Media for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/masterpieces-without-barriers-publicly-available-artwork/"><u>Masterpieces Without Barriers  Publicly Available Artwork</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-access-your-secret-snaps-archive-for-2024/"><u>[New] How to Access Your Secret Snaps Archive for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-step-by-step-guide-to-personalizing-mobile-notifications-for-2024/"><u>The Step-by-Step Guide to Personalizing Mobile Notifications for 2024</u></a></li>
</ul></div>
