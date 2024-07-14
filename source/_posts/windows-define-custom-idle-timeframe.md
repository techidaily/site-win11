---
title: "Windows: Define Custom Idle Timeframe"
date: 2024-07-13T10:46:07.198Z
updated: 2024-07-14T10:46:07.198Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows: Define Custom Idle Timeframe"
excerpt: "This Article Describes Windows: Define Custom Idle Timeframe"
keywords: Windows Idle Timer,Customize Idle Time,Set Idle Window,Personal Idle Period,Adjust System Idle,Tailor Idle Time,Custom Idle Settings
thumbnail: https://thmb.techidaily.com/7210d597b33981cf8e8bc74bc3a1da89a343d982eff67b18284889061aed1be5.jpg
---

## Windows: Define Custom Idle Timeframe

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://extra-approaches.techidaily.com/updated-paving-your-way-to-cost-savvy-cloud-choices/"><u>[Updated] Paving Your Way to Cost-Savvy Cloud Choices</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-through-edges-webview2-controls/"><u>Optimizing System Resources Through Edge's WebView2 Controls</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-y100t-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo Y100t Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/taming-erratic-errors-from-wins-protection-suite/"><u>Taming Erratic Errors From WINS Protection Suite</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-timeless-tunes-selecting-high-quality-ringtones-online/"><u>[Updated] Timeless Tunes  Selecting High-Quality Ringtones Online</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-plus-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Plus To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-the-ultimate-guide-to-snapchat-brand-building/"><u>[New] In 2024, The Ultimate Guide to SnapChat Brand Building</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-problem-zerosevennine/"><u>Overcoming System Problem ZeroSevenNine</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overwatch-2s-missing-graphics-driver-error/"><u>Fixing Overwatch 2'S Missing Graphics Driver Error</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-3-step-financial-forecasting-assessing-revenue-from-googles-platform-youtube/"><u>[New] 2024 Approved  3-Step Financial Forecasting  Assessing Revenue From Google's Platform, YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlock-full-screen-potential-on-youtube-videos/"><u>Unlock Full Screen Potential on YouTube Videos</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-transformation-mp3-files-to-windows-compatible-audio-cds-with-imgburn/"><u>Immediate Transformation: MP3 Files to Windows-Compatible Audio CDs with ImgBurn</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-stalled-windows-batch-processes/"><u>Guide to Reactivating Stalled Windows Batch Processes</u></a></li>
<li><a href="https://win11.techidaily.com/guide-recovering-invisible-bluetooth-in-device-manager/"><u>Guide: Recovering Invisible Bluetooth in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-captures-snip-tool-versus-prtsc/"><u>Mastering Windows Captures: Snip Tool versus PrtSc</u></a></li>
<li><a href="https://win11.techidaily.com/learn-how-to-turn-off-games-for-w11-suggestions/"><u>Learn How To Turn Off Games for W11 Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-efficiency-the-ultimate-guide-to-taskbar-controls/"><u>Unlocking Efficiency: The Ultimate Guide to Taskbar Controls</u></a></li>
<li><a href="https://win11.techidaily.com/preempting-vagrant-start-issues-for-vms-on-win11os/"><u>Preempting Vagrant Start Issues for VMs on Win11OS</u></a></li>
<li><a href="https://win11.techidaily.com/fan-the-fire-essential-tips-for-cooler-gameplay-on-overheated-windows-laptops/"><u>Fan the Fire: Essential Tips for Cooler Gameplay on Overheated Windows Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/taming-setting-turmoil-a-pubg-guide-for-pc-users/"><u>Taming Setting Turmoil: A PUBG Guide for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-end-task-control-panel-in-windows-11-ui/"><u>Mastering the End Task Control Panel in Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11.</u></a></li>
<li><a href="https://win11.techidaily.com/the-6-key-steps-to-discovering-the-identity-of-your-pc-window-edition/"><u>The 6 Key Steps to Discovering the Identity of Your PC, Window Edition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cr2-image-conversion-in-windows-pc/"><u>Mastering the Art of CR2 Image Conversion in Windows PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-path-to-flawless-video-subtitles-via-internet-services/"><u>The Ultimate Path to Flawless Video Subtitles via Internet Services</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-volume-settings-after-hiccups-in-windows-10/"><u>Restoring Volume Settings After Hiccups in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-unresponsive-keyboard-issue-x80049dd3-in-windows-11/"><u>Overcoming the Unresponsive Keyboard Issue - X80049DD3 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-overcoming-forbidden-errors/"><u>Mastering the Art of Overcoming Forbidden Errors</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-sound-recording-on-windows-11/"><u>Streamline Your Sound Recording on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-recovering-without-admin-creds/"><u>Mastering Windows 11: Recovering without Admin Creds</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-mastering-the-art-of-seamless-inshot-edits/"><u>In 2024, Mastering the Art of Seamless Inshot Edits</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-essential-windows-shorthand/"><u>Streamline Your Workflow: Essential Windows Shorthand</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-windows-11-mailcalendar/"><u>Quick Guide: Resetting Windows 11 Mail/Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/faster-utorrent-file-sharing-a-guide-for-windows/"><u>Faster uTorrent File Sharing: A Guide for Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-tecno-camon-30-pro-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Tecno Camon 30 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-realme-12plus-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-go-no-net-with-your-new-os-win11/"><u>How to Go No Net With Your New OS, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-iomap64-system-crashes-and-bsod-quickly-on-pcs/"><u>Resolve IOMap64 System Crashes and BSoD Quickly on PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-prevent-unwanted-recordings-quit-time-tricks/"><u>In 2024, Prevent Unwanted Recordings  Quit Time Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-strategies-for-finding-a-misplaced-pin/"><u>Unlock Windows 11 - Strategies for Finding a Misplaced PIN</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-techniques-for-net-healing-in-windows-max-156/"><u>Top 5 Techniques for .NET Healing in Windows (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/opening-your-canvas-microsoft-paint-on-windows-11/"><u>Opening Your Canvas: Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-steam-sync-errors-in-windows/"><u>Remedying Steam Sync Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-dangers-hacked-fingerprints-on-windows-pcs/"><u>Unlocking Dangers: Hacked Fingerprints on Windows PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/a-guide-to-winning-at-game-capturing-with-win10-for-2024/"><u>A Guide to Winning at Game Capturing with Win10 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insight-navigating-newly-opened-window-folders/"><u>Quick Insight: Navigating Newly Opened Window Folders</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-bridging-the-gap-with-quantum-hdr-knowledge/"><u>In 2024, Bridging the Gap with Quantum HDR Knowledge</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-no-hypervisor-detection-in-sandbox-mode/"><u>How to Address No Hypervisor Detection in Sandbox Mode</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-iphone-12-drfone-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-essentials-of-creating-memorable-fb-slideshows/"><u>2024 Approved  The Essentials of Creating Memorable FB Slideshows</u></a></li>
</ul></div>
