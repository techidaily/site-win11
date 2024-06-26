---
title: "Mastering Update Schedules: Setting Active Periods Windows 11"
date: 2024-06-25T09:50:40.182Z
updated: 2024-06-26T09:50:40.182Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Update Schedules: Setting Active Periods Windows 11"
excerpt: "This Article Describes Mastering Update Schedules: Setting Active Periods Windows 11"
keywords: Win11 Update Planning,Active Period Customization,Windows Schedule Optimization,Manage Windows Updates,Scheduled Maintenance Windows,Active Time for Updates,Windows 11 Regime Adjustment
thumbnail: https://thmb.techidaily.com/d62120d0f92dda8643d1fb18ba050a4238aed422d93382b937c3fa171ed251d1.jpg
---

## Mastering Update Schedules: Setting Active Periods Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

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
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

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
<li><a href="https://win11.techidaily.com/merging-windows-credentials-with-microsoft-identity-hub/"><u>Merging Windows Credentials with Microsoft Identity Hub</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-microsoft-edge-speeding-tips-for-windows-1011/"><u>Boosting Microsoft Edge: Speeding Tips for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-malwarebytess-failed-execution-calls-on-windows-1011/"><u>Tackling Malwarebytes's Failed Execution Calls on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-critical-failures-in-windows-with-error-code-c0000022/"><u>Tackling Critical Failures in Windows with Error Code C0000022</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-how-to-execute-a-clean-boot-on-windows-11/"><u>The Ultimate Technique: How to Execute a Clean Boot on Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-6s-plus-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>Unlocking Apple iPhone 6s Plus Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-preserve-and-showcase-nine-exceptional-tools-for-animated-gifs-on-pc/"><u>In 2024, Preserve & Showcase  Nine Exceptional Tools for Animated GIFs on PC</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-xiaomi-14-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/rising-stars-in-streaming-global-youtubes-subs-pantheon-for-2024/"><u>Rising Stars in Streaming  Global YouTube's Subs Pantheon for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/accelerate-artistry-in-windows-11-photoshop/"><u>Accelerate Artistry in Windows 11 Photoshop</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-accelerate-your-videos-a-quicktime-player-guide-for-2024/"><u>Updated Accelerate Your Videos A QuickTime Player Guide for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-champion-streaming-and-capture-tools-for-2024/"><u>[New] Champion Streaming & Capture Tools for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-tweet-tracks-top-ranked-amazon-originals-on-twittersphere/"><u>In 2024, Tweet Tracks  Top-Ranked Amazon Originals on Twittersphere</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlock-the-secrets-of-smooth-and-seamless-keying-in-videography/"><u>In 2024, Unlock the Secrets of Smooth and Seamless Keying in Videography</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>