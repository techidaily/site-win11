---
title: Fine-Tune Your PC's Performance with Active Hours & Update Management
date: 2024-10-09T17:43:12.707Z
updated: 2024-10-15T20:35:15.443Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tune Your PC's Performance with Active Hours & Update Management
excerpt: This Article Describes Fine-Tune Your PC's Performance with Active Hours & Update Management
keywords: Boost PC Speed,Update PC Regularly,Manage PC Updates,Optimize PC Performance,Set Active PC Hours,Enhance PC Efficiency,Control PC Settings
thumbnail: https://thmb.techidaily.com/73182ed54b3d34ca981abeae24ed800ccc098d1b157cf1a2528e89d05cbc2979.jpg
---

## Fine-Tune Your PC's Performance with Active Hours & Update Management

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
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-clear-up-fb-message-misrepresentation/"><u>[New] Clear Up FB Message Misrepresentation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-rpg-legacy-meets-innovation-written-by-time/"><u>[New] In 2024, RPG Legacy Meets Innovation' Written by Time</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/chedule-smarter-the-art-of-youtube-content-timing-for-2024/"><u>[New] Schedule Smarter The Art of YouTube Content Timing for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-surge-in-online-income-the-revelation-of-500plus-subscribers-power/"><u>[New] Surge in Online Income The Revelation of 500+ Subscribers' Power</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-ultimate-handbook-for-saving-insta-content/"><u>[New] The Ultimate Handbook for Saving Insta Content</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>All You Need To Know About Mega Greninja For Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-performance-erase-sluggish-windows-11-frustration/"><u>Elevate Performance: Erase Sluggish Windows 11 Frustration</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-page-rendering-problems-in-windows-store/"><u>Eradicating Page Rendering Problems in Windows Store</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-resolve-improper-token-usage-problems/"><u>Guidance to Resolve Improper Token Usage Problems</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-windows-power-consumption-statistics/"><u>Identifying Windows Power Consumption Statistics</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-prime-commercial-sky-storage-choices/"><u>In 2024, Prime Commercial Sky-Storage Choices</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-languages-swiftly-on-windows-with-key-combinations/"><u>Navigate Through Languages Swiftly on Windows With Key Combinations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nvidia-sharing-feature-unresponsive-troubleshooting-guide/"><u>NVIDIA Sharing Feature Unresponsive - Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-counter-for-locked-out-accounts-post-failed-logins-on-w10w11/"><u>Resetting Counter for Locked Out Accounts Post-Failed Logins on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-cameras-capability-to-record/"><u>Restoring Windows Camera's Capability to Record</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-group-policy-reports-via-gpresult/"><u>Streamlining Group Policy Reports via GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-turn-your-pc-into-a-transcoding-network-with-tdarr/"><u>Unleash Potential: Turn Your PC Into a Transcoding Network with Tdarr</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-13t-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have 13T fingerprint</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-novice-to-master-the-best-animation-makers-for-every-level/"><u>Updated From Novice to Master The Best Animation Makers for Every Level</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    