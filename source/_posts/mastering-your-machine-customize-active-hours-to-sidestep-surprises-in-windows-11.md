---
title: "Mastering Your Machine: Customize Active Hours to Sidestep Surprises in Windows 11"
date: 2024-10-11T19:48:15.878Z
updated: 2024-10-15T16:23:08.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Your Machine: Customize Active Hours to Sidestep Surprises in Windows 11"
excerpt: "This Article Describes Mastering Your Machine: Customize Active Hours to Sidestep Surprises in Windows 11"
keywords: Windows 11 ActiveHours,Customize Windows Timers,Avoiding Power Bans,Safe Mode Wakeup,Efficient PC Control,Energy-Saving Windows,Schedule System Startup
thumbnail: https://thmb.techidaily.com/7e377b50c4e513bd18b3a4caf17d4fa401f54e28db3371c8a6654c909a09f9e7.png
---

## Mastering Your Machine: Customize Active Hours to Sidestep Surprises in Windows 11

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
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484951/16446" target="_top" id="1484951">
  <img src="//a.impactradius-go.com/display-ad/16446-1484951" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484951/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135418/19272" target="_top" id="2135418">
  <img src="//a.impactradius-go.com/display-ad/19272-2135418" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135418/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-elevate-your-gameplay-videos-the-ultimate-collection-of-freefire-tags/"><u>[New] 2024 Approved Elevate Your Gameplay Videos The Ultimate Collection of FreeFire Tags</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-guide-to-top-8-linux-screenshot-solutions-for-2024/"><u>[New] Guide to Top 8 Linux Screenshot Solutions for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-time-savers-screen-recording-on-instagrams-story/"><u>[New] Time Savers Screen Recording on Instagram's Story</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-craft-unique-logos-using-complimentary-stock-graphics/"><u>[Updated] Craft Unique Logos Using Complimentary Stock Graphics</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hourly-video-footage-gb-needed-per-day/"><u>[Updated] Hourly Video Footage GB Needed Per Day</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-high-definition-webcams-top-5-combined-visual-and-audio/"><u>2024 Approved High-Definition Webcams Top 5 - Combined Visual & Audio</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-step-by-step-guide-for-earning-from-every-youtube-short/"><u>2024 Approved Step-by-Step Guide for Earning From Every YouTube Short</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-0x80070570-a-roadmap-to-restore-damaged-files-in-windows-11/"><u>Eliminating Error 0X80070570: A Roadmap to Restore Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-mp3-conversion-transforming-digital-music-into-physical-form-using-windows-and-imgburn/"><u>Mastering MP3 Conversion: Transforming Digital Music Into Physical Form Using Windows & ImgBurn</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-activating-ms-defender-in-win-11-edge-browser/"><u>Quick Tips for Activating MS Defender in Win 11 Edge Browser</u></a></li>
<li><a href="https://win11.techidaily.com/skillful-techniques-for-placing-toolbar-icons-on-desktop/"><u>Skillful Techniques for Placing Toolbar Icons on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-systems-task-handling-on-windows/"><u>Supercharge Your System's Task Handling on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-wobble-of-windows-mouse-pointer/"><u>Taming the Wobble of Windows Mouse Pointer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-to-selecting-the-right-smartwatch-a-pre-purchase-checklist/"><u>The Ultimate Guide to Selecting the Right Smartwatch: A Pre-Purchase Checklist</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tips-for-mac-style-window-enhancement-on-windows/"><u>Top 5 Tips for Mac-Style Window Enhancement on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-free-tools-for-flawless-srt-conversion/"><u>Top Free Tools for Flawless SRT Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/verify-eligibility-of-your-computer-for-win11-release/"><u>Verify Eligibility of Your Computer for Win11 Release</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    