---
title: Access Advanced Control Panel to Change Screen After Dark Mode
date: 2024-06-25T11:39:52.120Z
updated: 2024-06-26T11:39:52.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Access Advanced Control Panel to Change Screen After Dark Mode
excerpt: This Article Describes Access Advanced Control Panel to Change Screen After Dark Mode
keywords: Dark Mode Screen Control,Advanced Control Panel Access,Dark Theme Display Change,Modify After Dark Settings,Access Control Panel Adjustments,Control Dark Mode Screens,Panel for Dark Themes Alteration
thumbnail: https://thmb.techidaily.com/124b72dbf62c2315133422a27b4166aca8de938c7b4431d8ccd93ecf0eac5efe.png
---

## Access Advanced Control Panel to Change Screen After Dark Mode

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://win11.techidaily.com/actions-to-take-against-lunar-client-start-up-failure-notice/"><u>Actions to Take Against Lunar Client Start-Up Failure Notice</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-file-viewer-rights-in-windows-1011/"><u>How to Regain File Viewer Rights in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/10-solutions-for-stuck-pin-locks-on-windows/"><u>10 Solutions for Stuck PIN Locks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-tactics-for-repeated-usernamepassword-alerts/"><u>Bypass Tactics for Repeated Username/Password Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-idle-screen-time-on-windows/"><u>Configuring Idle Screen Time on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-boost-engagement-through-anime-style-subscribe-buttons-filmora-tutorial-for-2024/"><u>[New] Boost Engagement Through Anime-Style Subscribe Buttons (Filmora Tutorial) for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-social-media-synergy-cross-promoting-your-youtube-content/"><u>2024 Approved  Social Media Synergy  Cross-Promoting Your YouTube Content</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-the-power-of-your-lost-iphone-x/"><u>[Updated] Unleash the Power of Your Lost iPhone X</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-comparing-leading-names-in-4k-yt-video-to-mp3-tools/"><u>In 2024, Comparing Leading Names in 4K YT Video to MP3 Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-elevating-audience-excitement-with-top-ideas-for-2024/"><u>[New] Elevating Audience Excitement with Top Ideas for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-top-action-cam-battle-max-360-vs-hero-11-review/"><u>2024 Approved  Top Action Cam Battle  Max 360 vs Hero 11 Review</u></a></li>
</ul></div>
