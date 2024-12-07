---
title: "The Winning Strategy: Configuring Active Hours for a Smooth Windows Experience"
date: 2024-12-03T09:26:56.414Z
updated: 2024-12-07T05:58:37.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Winning Strategy: Configuring Active Hours for a Smooth Windows Experience"
excerpt: "This Article Describes The Winning Strategy: Configuring Active Hours for a Smooth Windows Experience"
keywords: Windows Productivity Boost,Optimize Windows Usage,Active Hours Configuration Guide,Smooth Windows Performance,Enhancing OS Efficiency,Schedule PC Operations,Maximizing Windows Experience
thumbnail: https://thmb.techidaily.com/ced9cab3bb4f4b670e0a461fa0277071d0fe6cc512c46ece52a065d147ecc37a.jpg
---

## The Winning Strategy: Configuring Active Hours for a Smooth Windows Experience

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-guide-to-progressive-audio-diminishment-via-lumafusion-for-2024/"><u>[New] Guide to Progressive Audio Diminishment via Lumafusion for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-master-the-art-of-fb-video-ads-with-a-complimentary-kit-for-2024/"><u>[New] Master the Art of FB Video Ads with a Complimentary Kit for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-top-tier-tips-for-superior-home-theater-dvd-production-on-mac/"><u>[Updated] 2024 Approved Top-Tier Tips for Superior Home Theater DVD Production on Mac</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-vivo-y27s-device-sim-by-drfone-android/"><u>Easily Unlock Your Vivo Y27s Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/easy-fixes-for-unwanted-new-tabs-in-chrome-browser/"><u>Easy Fixes for Unwanted New Tabs in Chrome Browser</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-new-horizons-with-my-goal-zero-bamboo-laptop-the-best-travel-buddy-ever/"><u>Exploring New Horizons with My Goal Zero Bamboo Laptop - The Best Travel Buddy Ever!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/hide-and-discover-instagram-stories-leaders-for-2024/"><u>Hide & Discover Instagram Stories Leaders for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-honor-magic-v2-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my Honor Magic V2</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-infinix-smart-7-hd-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Infinix Smart 7 HD</u></a></li>
<li><a href="https://win11.techidaily.com/missing-out-regain-access-to-windows-11s-hidden-upgrades-and-tools/"><u>Missing Out? Regain Access to Windows 11'S Hidden Upgrades and Tools</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reclaim-faulty-wi-fi-settings-on-a-windows-machine/"><u>Steps to Reclaim Faulty Wi-Fi Settings on a Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-turbulent-troubles-stop-lag-on-star-wars-battlefront-2-pc/"><u>Tackle Turbulent Troubles: Stop Lag on Star Wars Battlefront 2 PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-permission-based-save-errors-in-windows-os/"><u>Tackling Permission-Based Save Errors in Windows OS</u></a></li>
<li><a href="https://article-posts.techidaily.com/unveiling-the-secrets-share-images-professionally-on-youtube/"><u>Unveiling the Secrets Share Images Professionally on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-file-explorer-keeps-opening-by-itself-on-windows/"><u>What to Do if File Explorer Keeps Opening by Itself on Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    