---
title: "Command Your Computer: Manage Updates and Downtime in Windows 11"
date: 2024-10-01T01:03:32.168Z
updated: 2024-10-04T03:49:08.514Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Your Computer: Manage Updates and Downtime in Windows 11"
excerpt: "This Article Describes Command Your Computer: Manage Updates and Downtime in Windows 11"
keywords: Win11 Update Control,PC Maintenance Guide,Minimize System Down Time,Windows 11 Shields Updates,Downtime in Windows 11 Management,Mastering Windows 11 Updates,Optimizing Windows 11 Uptime
thumbnail: https://thmb.techidaily.com/19d1e1f9a7e016bed2849100cf93d86788ddae5b2cf2f12f9be9d04582b68734.jpg
---

## Command Your Computer: Manage Updates and Downtime in Windows 11

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
<a href="https://appsumo.8odi.net/c/5597632/2049364/7443" target="_top" id="2049364">
  <img src="//a.impactradius-go.com/display-ad/7443-2049364" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049364/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-cinematic-narratives-mastering-screenplays/"><u>[New] Cinematic Narratives Mastering Screenplays</u></a></li>
<li><a href="https://solve-info.techidaily.com/boost-efficiency-through-customized-artificial-intelligence-frameworks/"><u>Boost Efficiency Through Customized Artificial Intelligence Frameworks</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/vering-artistic-expression-top-film-tips-on-youtube/"><u>Discovering Artistic Expression Top Film Tips on YouTube</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevating-dev-workflows-with-chatgpt-and-vs-code/"><u>Elevating Dev Workflows with ChatGPT & VS Code</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-n-versions-usage-insights/"><u>Exploring Windows N Versions: Usage Insights</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-zte-axon-40-lite-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your ZTE Axon 40 Lite to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/halt-discord-auto-launch-and-update-checks-on-windows-10/"><u>Halt Discord Auto-Launch & Update Checks on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-windows-11-secure-your-digital-assets/"><u>How Does Windows 11 Secure Your Digital Assets?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-motorola-defy-2-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Motorola Defy 2 Phone that is Locked?</u></a></li>
<li><a href="https://win11.techidaily.com/linux-pure-drop-wsl/"><u>Linux Pure - Drop WSL</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-pagefilesys-usage-and-importance-in-winos/"><u>Navigating Through Pagefile.sys Usage & Importance in WinOS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-video-invitation-design-made-easy-top-apps-for-iphone-and-android-for-2024/"><u>New Video Invitation Design Made Easy Top Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-syncs-restored-overcome-google-drive-pc-challenges/"><u>Seamless Syncs Restored: Overcome Google Drive PC Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-management-in-windows-with-date-mods/"><u>Streamlining Data Management in Windows with Date Mods</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-differences-between-auto-gpt-and-its-cousin-chatgpt/"><u>The Differences Between Auto-GPT and Its Cousin, ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanism-behind-windows-reserve-memory-system/"><u>The Mechanism Behind Windows' Reserve Memory System</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-elevate-your-storytelling-expert-approved-1080p-video-editing-solutions/"><u>Updated In 2024, Elevate Your Storytelling Expert-Approved 1080P Video Editing Solutions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    