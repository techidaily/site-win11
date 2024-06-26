---
title: Prevent Windows From Logging App Starts
date: 2024-06-25T10:05:04.437Z
updated: 2024-06-26T10:05:04.437Z
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
<li><a href="https://win11.techidaily.com/the-overlooked-duo-of-windows-monitoring-metrics/"><u>The Overlooked Duo of Windows Monitoring Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-visual-delight-windows-wallpapers-guidebook/"><u>Fine-Tuning Visual Delight: Windows Wallpapers Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-free-media-tools-for-windows-pcs/"><u>Explore the Finest Free Media Tools for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-new-strategies-behind-extended-updates-in-windows-11-h2/"><u>Exploring the New Strategies Behind Extended Updates in Windows 11 H2</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-savvy-in-the-world-of-windows-11/"><u>Sticky Note Savvy in the World of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-macos-via-external-windows-utilities/"><u>Supercharging macOS via External Windows Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-why-windows-fails-to-execute-exe-files/"><u>Decoding Why Windows Fails to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/flush-your-steam-dns-data-a-windows-user-guide/"><u>Flush Your Steam DNS Data - A Windows User Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err-87-for-incompatible-library-loading/"><u>Fixing Err 87 for Incompatible Library Loading</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-ultimate-guide-to-speedy-skipping-in-the-world-of-tiktok-for-2024/"><u>[New] The Ultimate Guide to Speedy Skipping in the World of TikTok for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-bare-bones-budget-friendly-best-5-windows-10-recording-apps/"><u>[Updated] Bare-Bones, Budget-Friendly  Best 5 Windows 10 Recording Apps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-beyond-the-lens-innovative-ideas-for-youtube-video-creation/"><u>[Updated] In 2024, Beyond the Lens  Innovative Ideas for YouTube Video Creation</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-vimeos-video-mosaics-inserting-chapters-for-clarity/"><u>[New] 2024 Approved  Vimeo's Video Mosaics  Inserting Chapters for Clarity</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastering-camera-roll-export-to-snapchat-a-step-by-step-guide-for-2024/"><u>Mastering Camera Roll Export to Snapchat  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-easy-access-guide-skype-audio-to-mp3-free/"><u>[Updated] Easy-Access Guide  Skype Audio to Mp3, Free</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-auditory-playscripts-collection/"><u>2024 Approved  Ultimate Auditory Playscripts Collection</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-streamline-your-instagram-top-8-planning-apps-for-iosandroid-devices-for-2024/"><u>[Updated] Streamline Your Instagram  Top 8 Planning Apps for iOS/Android Devices for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Honor X7b? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-gamers-guide-to-free-game-recording-tools-for-2024/"><u>[New] Gamers' Guide to Free Game Recording Tools for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>