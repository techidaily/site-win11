---
title: "Sharpen System Speed: Lowering High Usage of Interest Tasks"
date: 2024-07-13T10:34:27.839Z
updated: 2024-07-14T10:34:27.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sharpen System Speed: Lowering High Usage of Interest Tasks"
excerpt: "This Article Describes Sharpen System Speed: Lowering High Usage of Interest Tasks"
keywords: Speed Sharpen,High Usage Decrease,Interest Rate Low,Task Efficiency Boost,System Performance Improve,Lowering Intensive Tasks,Accelerating Computation Time
thumbnail: https://thmb.techidaily.com/0656fd665c6180b1a80265c93dba7068c3a0cbd851c23bc5b8909b9f9daa190b.jpg
---

## Sharpen System Speed: Lowering High Usage of Interest Tasks

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.


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
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-vivo-y100t-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Vivo Y100t to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-subtitles-management-with-prime-and-windows-11/"><u>Master Subtitles Management with Prime and Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/managing-failed-app-verifications-in-windows-os/"><u>Managing Failed App Verifications in Windows OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-apk-journey-to-gaming-bliss-funimate-pro-guide/"><u>[Updated] APK Journey to Gaming Bliss  Funimate Pro Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-webp-saving-chrome-image-format-change-guide/"><u>Win Over WebP Saving: Chrome Image Format Change Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-0x8004def5-onedrive-hurdle-on-win11/"><u>Eradicating 0X8004DEF5 Onedrive Hurdle on Win11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-a-dash-of-creativity-top-30-innovative-tiktok-pfps-for-2024/"><u>[New] A Dash of Creativity  Top 30 Innovative TikTok PFPs for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-a-comprehensible-walkthrough-finding-your-youtube-remarks/"><u>In 2024, A Comprehensible Walkthrough  Finding Your YouTube Remarks</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-youtube-title-creation-the-perfect-formula/"><u>[New] Mastering YouTube Title Creation  The Perfect Formula</u></a></li>
<li><a href="https://win11.techidaily.com/debugging-made-easy-essential-windows-fixers-guide/"><u>Debugging Made Easy: Essential Windows Fixers Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-depth-guide-to-archiving-online-conversations-with-fb/"><u>[New] In-Depth Guide to Archiving Online Conversations with FB</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-unveiling-the-mysteries-of-video-monetization/"><u>[Updated] 2024 Approved  Unveiling the Mysteries of Video Monetization</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-color-coding-in-the-digital-world-srgb-vs-rgb/"><u>[Updated] Color Coding in the Digital World  Srgb vs Rgb</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-game-bar-errors-due-to-weak-hardware/"><u>Fixing Game Bar Errors Due to Weak Hardware</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-the-complete-guide-to-hulu-recording-across-all-platforms/"><u>[Updated] 2024 Approved  The Complete Guide to Hulu Recording Across All Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/1719222893625-eradicate-failed-capture-on-windows-devices-today/"><u>Eradicate Failed Capture on Windows Devices Today!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-subtle-screen-entry-sequence/"><u>[Updated] Subtle Screen Entry Sequence</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-editing-efforts-10-text-innovations/"><u>2024 Approved  Top Editing Efforts  10 Text Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-directx-protocols-for-your-gaming-system/"><u>Effortless DirectX Protocols for Your Gaming System</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionize-your-augmented-reality-graphics-using-custom-luts/"><u>[New] Revolutionize Your Augmented Reality Graphics Using Custom LUTs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/elevate-your-social-media-impact-secrets-unveiled-in-the-best-facebook-bios/"><u>Elevate Your Social Media Impact  Secrets Unveiled in the Best Facebook Bios</u></a></li>
<li><a href="https://win11.techidaily.com/keep-win10-fresh-actions-for-those-who-skip-11/"><u>Keep Win10 Fresh: Actions for Those Who Skip 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-13-mini-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 13 mini Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/batch-terminate-programs-in-windows-effortlessly/"><u>Batch Terminate Programs in Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-concurrent-wi-fi-and-ethernet-on-windows-pcs/"><u>Mastering Concurrent Wi-Fi and Ethernet on Windows PCs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-spotlight-on-blurbs-captivating-podcast-intros/"><u>2024 Approved  Spotlight on Blurbs  Captivating Podcast Intros</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-use-estimating-windows-app-size/"><u>Efficient Use: Estimating Windows App Size</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-e8024002e-for-updates/"><u>Bypassing Windows Error E:8024002E for Updates</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-screenflix-recorder-insider-report/"><u>[Updated] 2024 Approved  ScreenFlix Recorder Insider Report</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-quick-and-cool-minecraft-abodes-guide/"><u>[New] In 2024, Quick and Cool Minecraft Abodes Guide</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-rectify-hiberflattening-windows/"><u>Easy Steps to Rectify HiberFlattening Windows</u></a></li>
<li><a href="https://win11.techidaily.com/determine-your-pcs-wattage-usage-on-windows-system/"><u>Determine Your PC's Wattage Usage on Windows System</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-step-by-step-process-of-setting-up-your-logitech-webcam-for-video/"><u>[New] 2024 Approved  Step-by-Step Process of Setting Up Your Logitech Webcam for Video</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-best-screen-recorder-for-windows-11-for-2024/"><u>[Updated] Best Screen Recorder for Windows 11 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-chatgpt-is-at-capacity-right-now-error-on-windows/"><u>How to Fix the ChatGPT Is at Capacity Right Now Error on Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-vids-to-dollars-navigating-youtubes-monetization-landscape/"><u>2024 Approved  From Vids to Dollars  Navigating YouTube's Monetization Landscape</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/what-does-jailbreaking-apple-iphone-14-pro-i-do-get-answers-here-drfone-by-drfone-ios/"><u>What Does Jailbreaking Apple iPhone 14 Pro i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pcs-safety-with-these-7-password-generators/"><u>Boost Your PC's Safety with These 7 Password Generators</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-edge-and-keep-your-system-clean-w11/"><u>Eliminate Edge and Keep Your System Clean (W11)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-building-a-unique-presence-when-overshadowed-by-influencers/"><u>In 2024, Building a Unique Presence When Overshadowed by Influencers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-steps-for-setting-up-your-canon-printer-visual-aids/"><u>Quick Steps for Setting up Your Canon Printer (Visual Aids)</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-optimize-cpu-load-from-tiworkerexe/"><u>Approaches to Optimize CPU Load From TiWorker.exe</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-obstacles-when-installing-java/"><u>Addressing Common Obstacles When Installing Java</u></a></li>
<li><a href="https://win11.techidaily.com/determining-optimal-nvidia-driver-gamingstudio-edition/"><u>Determining Optimal Nvidia Driver: Gaming/Studio Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-carryminati-the-youtube-money-trail-of-ajey-nagar/"><u>[New] 2024 Approved  CarryMinati  The YouTube Money Trail of Ajey Nagar</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-remove-apple-iphone-6-sim-lock-by-drfone-ios/"><u>In 2024, How to Remove Apple iPhone 6 SIM Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-update-your-amd-radeon-graphics-drivers-on-windows-11/"><u>How to Update Your AMD Radeon Graphics Drivers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-write-unavailable-issue-in-windows/"><u>Eradicating 'Write Unavailable' Issue in Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-protectively-download-youtube-audio-without-fear-for-2024/"><u>[New] How to Protectively Download YouTube Audio Without Fear for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-or-removing-wi-fi-cost-tracking-in-win11/"><u>Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-essential-list-7-cost-free-video-tags-extractors-on-youtube/"><u>[Updated] In 2024, Essential List  7 Cost-Free Video Tags Extractors on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-top-8-smooth-latency-free-video-reporters/"><u>2024 Approved  Top 8 Smooth, Latency-Free Video Reporters</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-windows-11s-misaligned-html-emails/"><u>Deciphering and Dismantling Windows 11'S Misaligned HTML Emails</u></a></li>
<li><a href="https://extra-hints.techidaily.com/precision-review-of-elite-parrots-ar-model-20/"><u>Precision Review of Elite Parrot's AR Model 2.0</u></a></li>
<li><a href="https://win11.techidaily.com/auto-shutdown-hacks-for-idle-pcs-running-w10w11/"><u>Auto Shutdown Hacks for Idle PCs Running W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-radeon-driver-updates-in-windows-11-step-by-step-guide/"><u>Mastering Radeon Driver Updates in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-best-free-online-face-generators-to-create-fake-faces/"><u>Updated In 2024, Best Free Online Face Generators to Create Fake Faces</u></a></li>
<li><a href="https://win11.techidaily.com/exemplary-protection-in-a-new-era-selecting-four-for-windows-11/"><u>Exemplary Protection in a New Era: Selecting Four for Windows 11</u></a></li>
</ul></div>
