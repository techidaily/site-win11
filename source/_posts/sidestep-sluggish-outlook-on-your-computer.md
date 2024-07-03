---
title: Sidestep Sluggish Outlook on Your Computer
date: 2024-06-25T11:42:23.955Z
updated: 2024-06-26T11:42:23.955Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sidestep Sluggish Outlook on Your Computer
excerpt: This Article Describes Sidestep Sluggish Outlook on Your Computer
keywords: Boost PC Speed,Accelerate Compute,Optimize System,Enhance Performance,Elevate Speedup,Amplify Pace,Improve Response
thumbnail: https://thmb.techidaily.com/1e8ed7d03244990645b268803c3dbd7e538910f876a7a096244cc5d3946c5238.jpg
---

## Sidestep Sluggish Outlook on Your Computer

 With Microsoft Outlook, you can easily manage your emails, calendar, contacts, and tasks from one app. If you rely on Microsoft Outlook for work or personal communication, it can be frustrating when the app runs slowly on your Windows computer.

 Before you give up and switch to an alternative, try out the following tips to boost Outlook’s performance on Windows.

## 1\. Modify Outlook's Send and Receive Settings

 By default, Outlook is set to send/receive emails every 30 minutes. Setting a longer interval for automatic send/receive in Outlook can help improve the app's performance as it would need to consume system resources less frequently.

1. In the Outlook app, click the **File** menu in the top left corner.
2. Select **Options** from the left sidebar.
3. Navigate to the **Advanced** tab.
4. Under the **Send and receive** section, click the **Send/Receive** button.
5. Tick the **Schedule an automatic send/receive every** checkbox and enter the desired refresh interval in the box next to it.  
![Outlook Send and Receive Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/outlook-send-and-receive-settings.jpg)

## 2\. Avoid Syncing RSS Feeds

 Outlook periodically checks the RSS feeds you have subscribed to in order to download new content. If you are syncing too many RSS feeds into Outlook, it may adversely impact its performance on Windows. If you don't want that, use these steps to disable RSS feed sync in Outlook.

1. In the Outlook app, click the **File** menu in the top left corner.
2. Select **Options** from the left sidebar.
3. Switch to the **Advanced** tab.
4. Under the **RSS Feeds** section, clear both check boxes.
5. Click **OK**.  
![Disable RSS Feed in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rss-feed-in-outlook.jpg)

## 3\. Compact Outlook's PST files

 On Windows, Outlook creates PST (or Personal Storage Table) files to store your emails, attachments, calendar data, and other information. If these PST files become too large, they can negatively impact Outlook's performance on Windows, causing it to run slowly. You can try reducing the size of Outlook data files to see if that improves the situation.

1. Press **Win + R** to open the Run dialog box.
2. Type **control** in the box and press **Enter** to open Control Panel.
3. Use the **View by** drop-down menu in the top right corner to select **Large icons**.
4. Click on **Mail (Microsoft Outlook)**.
5. Click the **Data Files** button.
6. Select your Outlook data file and click the **Settings** option.
7. Click the **Compact Now** button.  
![Reduce the Size of Outlook Data File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reduce-the-size-of-outlook-data-file.jpg)

## 4\. Check the Outlook Indexing Status

 By default, Windows Search indexes all the data contained within Outlook OST and PST files. If Windows is in the process of indexing Outlook files, the app may experience lag during that time. To check the indexing status of Outlook data files, follow these steps:

1. In the Outlook app, navigate to **File > Options**.
2. Switch to the **Search** tab and click on **Indexing Options**.
3. Check the indexing status in the Indexing Options window.  
![Outlook Indexing Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/outlook-indexing-status.jpg)

 It’s important to note that Windows only indexes Outlook data when the Outlook app is open. So, if Windows is indexing Outlook files, leave the app open until the process is complete. Following this, Outlook should run smoothly on Windows.

## 5\. Disable Unwanted Add-Ins

 Although third-party add-ins help [improve your Outlook workflow](https://www.makeuseof.com/tag/6-best-practices-outlook-boost-workflow/) in many ways, they can also cause the app to operate slowly, especially if you are using too many of them. To avoid this, it’s best to disable or remove any non-essential add-ins from Outlook. Here are the steps for the same.

1. In the Outlook app, click the **File** menu at the top.
2. Select **Options** from the left pane.
3. In the Outlook Options window, switch to the **Add-ins** tab.
4. Click the **Go** button next to **COM Add-ins**.
5. Clear all the checkboxes to disable your add-ins. Alternatively, you can use the **Remove** button to uninstall add-ins.
6. Click **OK** to save changes.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

## 6\. Disable Redirection of the AppData Directory

 Another reason why Outlook may run slowly is if the AppData folder is being redirected to a network location. To avoid issues caused by a slow network, you can disable the redirection of the AppData directory. Since this process involves editing registry files, make sure you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Use one of the many ways to [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Windows > CurrentVersion > Explorer > User Shell Folders**.
3. Locate the **AppData** entry in the right pane and double-click it.
4. Enter **%USERPROFILE%\\AppData\\Roaming** in the Value data field and click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-dword-in-registry.jpg)

## 7\. Run the Inbox Repair Tool

 The Outlook app may become unresponsive on Windows if some of its files are corrupted. Luckily, you can repair Outlook files easily with the built-in Inbox Repair Tool. Here's how to run it.

1. Right-click the Outlook shortcut and select **Properties**.
2. Under the **Shortcut** tab, click on **Open File Location**.
3. Double-click on **SCANPST.EXE** to run it.
4. In the Microsoft Outlook Inbox Repair Tool window, click the **Browse** button and then navigate to the following directory:  
`C:\Users\*username*\AppData\Local\Microsoft\Outlook`  
 Replace **\*username\*** in the above path with your own username.
5. Select your profile and then click **Start**.  
![Outlook Inbox Repair Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/outlook-inbox-repair-tool.jpg)

 Wait for the repair operation to complete, and then restart the Outlook app.

## 8\. Create a New Outlook Profile

 A damaged or corrupt Outlook profile can also cause such performance issues. If that’s the case, your best option is to create and switch to a new Outlook profile. Here’s how to do it.

1. Open the **Control Panel** using the search menu.
2. Click on **Mail (Microsoft Outlook)**.
3. Under **Profiles**, select **Show Profiles**.
4. Click the **Add** button.
5. Enter a name for your new profile, and click **OK**.
6. Enter your account details and hit **Next**.
7. Select your new profile under **When starting Microsoft Outlook** and hit **Apply**.  
![Create New Outlook Profile-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-new-outlook-profile-1.jpg)

## 9\. Run the Outlook Advanced Diagnostics Tool

 The Microsoft Support and Recovery Assistant (SaRA) is a useful tool that can help you address Outlook performance problems on Windows. It can scan the Outlook app to detect potential issues and suggest fixes accordingly. Here’s how to run it.

1. Download and install the [Outlook Advanced Diagnostics tool](https://aka.ms/SaRA-OutlookAdvDiagnostics).
2. Select **Advanced diagnostics** and click **Next**.
3. Select **Outlook** and hit **Next**.  
![Run Microsoft Support and Recovery Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-microsoft-support-and-recovery-assistant.jpg)

 From there, follow the on-screen prompts to scan the Outlook app for any issues. Click the **Issues found** tab after the scan is complete, and then take the suggested actions to troubleshoot Outlook’s performance issues.

![Microsoft Support and Recovery Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-support-and-recovery-assistant.jpg)

## 10\. Run the Office Repair Tool

 If you are here, it’s safe to assume that none of the above tips have helped. In that case, you can run the Office repair tool to [fix issues with the Outlook app on Windows](https://www.makeuseof.com/microsoft-outlook-crashing-windows/).

1. Press **Win + R** to open the Run dialog box.
2. Type **appwiz.cpl** in the box and press **Enter**.
3. In the Programs and Features window, right-click the **Microsoft Office** suite and select **Change**.
4. Select your preferred repair option and then click **Repair**.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

## Don’t Let Outlook Slow You Down

 Few things are as frustrating as working with an app that constantly lags or runs slowly. Hopefully, one or more of the fixes covered above have helped improve Outlook’s performance on Windows, and you are at peace.

 Before you give up and switch to an alternative, try out the following tips to boost Outlook’s performance on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/in-depth-look-at-windows-11-admin-interface/"><u>In-Depth Look at Windows 11 Admin Interface</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-and-prevent-windows-drive-vanishing/"><u>Pinpoint and Prevent Windows Drive Vanishing</u></a></li>
<li><a href="https://win11.techidaily.com/edge-persistent-operation-on-win11/"><u>Edge: Persistent Operation on Win11?</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-blend-excelling-at-classic-games-in-hd-clarity-through-scummvm-on-windows/"><u>The Perfect Blend: Excelling at Classic Games in HD Clarity Through ScummVM on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719363401331-win10-troubleshooting-make-functions-work-again/"><u>WIN10 Troubleshooting: Make Functions Work Again!</u></a></li>
<li><a href="https://win11.techidaily.com/creating-digital-wonders-on-win11-with-paint-cocreator-the-ultimate-guide-for-ai-image-creation/"><u>Creating Digital Wonders on Win11 With Paint Cocreator: The Ultimate Guide for AI Image Creation</u></a></li>
<li><a href="https://win11.techidaily.com/boost-budget-efficiency-windows-11-pro-discounts/"><u>Boost Budget Efficiency: Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/digital-diaries-7-excelent-notetakers-for-pcs-and-slate/"><u>Digital Diaries: 7 Excelent Notetakers for PCs & Slate</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-embedding-google-play-into-windows-11/"><u>Guide to Embedding Google Play Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-cpu-woes-strategies-from-windows-rm-window/"><u>Unraveling CPU Woes: Strategies From Windows' RM Window</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-ultimate-guide-to-android-video-calls-for-2024/"><u>The Ultimate Guide to Android Video Calls for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/strategies-to-skyrocket-your-popularity-on-tiktok/"><u>Strategies to Skyrocket Your Popularity on TikTok</u></a></li>
<li><a href="https://youtube-data.techidaily.com/tial-tactics-for-youtube-short-troubleshooting/"><u>Essential Tactics for YouTube Short Troubleshooting</u></a></li>
<li><a href="https://some-skills.techidaily.com/superb-alter-ego-voice-tools-for-aspiring-vtubers-for-2024/"><u>Superb Alter-Ego Voice Tools  For Aspiring VTubers for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-how-to-make-an-animated-explainer-video/"><u>2024 Approved How to Make an Animated Explainer Video</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/understanding-vtuber-culture-and-career-trajectory/"><u>Understanding VTuber Culture & Career Trajectory</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-ultimate-arsenal-of-audio-manipulation-software-for-professional-use-for-2024/"><u>The Ultimate Arsenal of Audio Manipulation Software for Professional Use for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-top-farm-games-for-social-play-with-peers/"><u>[Updated] 2024 Approved  Top Farm Games for Social Play with Peers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-10-best-zoom-alternatives-for-2024/"><u>[New] 10 Best Zoom Alternatives for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-channel-your-earnings-effective-youtube-money-methods-for-2024/"><u>[New] Channel Your Earnings  Effective YouTube Money Methods for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>