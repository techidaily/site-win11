---
title: "Windows 11: The Art of Scheduling Updates and Downtime"
date: 2024-10-11T22:08:36.461Z
updated: 2024-10-15T16:50:50.777Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: The Art of Scheduling Updates and Downtime"
excerpt: "This Article Describes Windows 11: The Art of Scheduling Updates and Downtime"
keywords: Windows Update Efficiency,Scheduled PC Maintenance,Optimized System Updates,Minimal Disruption Windows,Timely OS Updates Strategy,Controlled Downtime Windows,Seamless Update Management
thumbnail: https://thmb.techidaily.com/783d5a68cd1201f00d72d69bc7ad0995ab16e6e244585454342ca9de98074a9b.jpg
---

## Windows 11: The Art of Scheduling Updates and Downtime

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884017/19272" target="_top" id="1884017">
  <img src="//a.impactradius-go.com/display-ad/19272-1884017" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884017/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-best-gopro-helmet-mounts-and-how-to-use-them/"><u>[New] 2024 Approved Best GoPro Helmet Mounts and How to Use Them</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-budget-friendly-tactics-to-increase-your-youtube-video-impact-for-2024/"><u>[New] Budget-Friendly Tactics to Increase Your YouTube Video Impact for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/awaiting-lift-off-spacex-may-become-rescue-mission-for-stranded-boeing-starliner-crew/"><u>Awaiting Lift-Off: SpaceX May Become Rescue Mission for Stranded Boeing Starliner Crew</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-clarity-visual-notes-made-easy-with-obsidian/"><u>Dive Into Clarity: Visual Notes Made Easy with Obsidian</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-utorrent-download-freeze-phenomenon-on-pcs/"><u>Eliminating uTorrent Download Freeze Phenomenon on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-guide-windows-11s-hidden-themes-unlocked-with-registry/"><u>Exclusive Guide: Windows 11'S Hidden Themes Unlocked with Registry</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/future-fusion-unlocking-mac-with-smartwatches/"><u>Future Fusion Unlocking Mac With Smartwatches</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-samsung-galaxy-s24-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Samsung Galaxy S24 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-honor-x50i-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Honor X50i Device</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-static-silence-fixing-pc-sounds/"><u>Overcoming Static Silence: Fixing PC Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-net-visibility-on-disconnected-pcs-windows/"><u>Restoring Net Visibility on Disconnected PCs Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/swifter-play-eliminate-amd-tarkov-glitches-now/"><u>Swifter Play: Eliminate AMD Tarkov Glitches Now</u></a></li>
<li><a href="https://win11.techidaily.com/switching-off-games-in-windows-11-suggestions/"><u>Switching Off Games in Windows 11 Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-re-ignite-windows-11-explorer/"><u>Troubleshooting Tips: Re-Ignite Windows 11 Explorer</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Tecno Spark 10C | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    