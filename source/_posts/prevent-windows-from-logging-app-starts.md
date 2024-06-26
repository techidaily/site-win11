---
title: Prevent Windows From Logging App Starts
date: 2024-06-25T11:29:35.793Z
updated: 2024-06-26T11:29:35.793Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Prevent Windows From Logging App Starts
excerpt: This Article Describes Prevent Windows From Logging App Starts
keywords: Stop App Start Logs Windows,Disable Windows App Logging,Prevent System Logs App,Halt Window's App Logs,Block Windows Log Starts,Turn Off Windows Start Recording,Eliminate Windows App Login Tracking
thumbnail: https://thmb.techidaily.com/f51042103ff6c3f87c92a84096e29bdaf9eccd433a92cd047a35aea4a9510783.jpg
---

## Prevent Windows From Logging App Starts

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reward-system-reboot-for-your-favorite-titles/"><u>Reward System Reboot for Your Favorite Titles</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-screen-display-defeating-windows-overscan/"><u>Optimize Full-Screen Display: Defeating Windows Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-dilemma-is-removing-pagefilesys-advisable/"><u>Deletion Dilemma: Is Removing Pagefile.sys Advisable?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-process-unterminate-obstacles-in-windows/"><u>Overcoming 'Process Unterminate' Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-bridging-imessage-between-devices/"><u>From iPhone to Desktop: Bridging iMessage Between Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/short-segment-screenplay-snippet/"><u>Short Segment Screenplay Snippet</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-best-live-stream-tools-for-gamers/"><u>In 2024, Unveiling Best Live-Stream Tools for Gamers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fundamentals-of-managing-volume-increase-in-projects/"><u>[New] Fundamentals of Managing Volume Increase in Projects</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-becoming-a-viral-star-on-tiktok-steps-to-increase-views-and-likes/"><u>[Updated] 2024 Approved  Becoming a Viral Star on TikTok  Steps to Increase Views and Likes</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-15-must-read-books-that-rule-the-social-media-reading-sphere/"><u>[Updated] 2024 Approved  15 Must-Read Books that Rule the Social Media Reading Sphere</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-upgrading-minecraft-stability-via-ram-adjustment/"><u>[Updated] In 2024, Upgrading Minecraft Stability via RAM Adjustment</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-adobe-premiere-rush-not-meeting-your-needs-explore-these-top-4-alternatives/"><u>In 2024, Adobe Premiere Rush Not Meeting Your Needs? Explore These Top 4 Alternatives</u></a></li>
<li><a href="https://extra-resources.techidaily.com/journey-into-joke-making-mastering-the-art-of-gif-memes/"><u>Journey Into Joke-Making  Mastering the Art of GIF Memes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>