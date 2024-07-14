---
title: Addressing Non-Functioning Windows Conditional Filters
date: 2024-07-13T11:24:28.268Z
updated: 2024-07-14T11:24:28.268Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Non-Functioning Windows Conditional Filters
excerpt: This Article Describes Addressing Non-Functioning Windows Conditional Filters
keywords: Window Filter Issues,Fix Unresponsive Windows,Conditional Filters Troubleshoot,Nonfunctional Windows Settings,Resolve Windows Glitches,Improving Windows Performance,Enhance Windows Conditionals
thumbnail: https://thmb.techidaily.com/633e4476d735dff824b3250c253c09c234e7613f83678c9c2635006dd72b341f.jpg
---

## Addressing Non-Functioning Windows Conditional Filters

 By setting up Outlook rules, you can configure the app to handle your inbox efficiently. This allows you to save time and automate actions that would otherwise require manual effort. But what if these Outlook rules stop working on your Windows computer?

 To help out, we have compiled a list of useful solutions that should get Outlook rules to work again.

## 1\. Make Sure Outlook Rules Are Enabled

 To start, you need to ensure that you haven't inadvertently disabled any Outlook rules. To do so, use these steps:

1. Open the **Outlook** app and click the **File** menu in the top left corner.
2. In the **Info** tab, click the **Manage Rules & Alerts** button.
3. Under the **Email Rules** tab, make sure the boxes next to your rules are checked.  
![Enable Outlook Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-outlook-rules.jpg)

## 2\. Rename Outlook Rules

 Using lengthy names for your Outlook rules can cause them to become larger in size, leading to unexpected issues with their functionality. To address this, try assigning shorter names to your Outlook rules and see if that gets things moving again.

 To rename Outlook rules, use these steps:

1. In the Outlook app, click the **File** menu in the top left corner.
2. In the **Info** tab, click the **Manage Rules & Alerts** button.
3. Under the **Email Rules** tab, select the rule you want to rename.
4. Click **Change Rule** and select **Rename Rule**.
5. Type in a shorter name for the rule and hit **OK**.
6. Click **Apply** to save the changes.  
![Rename Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-outlook-rule.jpg)

## 3\. Delete Unwanted Outlook Rules

 Apart from renaming rules, you can also consider deleting rules that you no longer need to prevent conflicts or unexpected behavior. Here’s how.

1. In the Outlook app, navigate to **File > Info > Manage Rules & Alerts**.
2. Hold down the **Ctrl** key and select the rules you no longer need.
3. Click the **Delete** option at the top.
4. Select **Yes** when prompted.  
![Delete a Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-a-outlook-rule.jpg)

## 4\. Reset the Outlook SRS File

 Microsoft Outlook stores essential account configuration in an SRS (Send and Receive Settings) file on your PC. If this file somehow becomes corrupted, Outlook rules won’t work. To fix this, you can force Outlook to recreate the SRS file by renaming the old file. Here's how.

1. Press **Win + R** to open the Run dialog box.
2. Type **%appdata%\\Microsoft\\Outlook** in the Open field and press **Enter**.
3. In the File Explorer window that opens, locate and select **Outlook.srs** file.
4. Press **F2** on your keyboard and [rename the file](https://www.makeuseof.com/windows-11-rename-files/) to **Outlook.srs.old**.  
![Rename Outlook SRS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-outlook-srs-file.jpg)

 Restart Outlook after completing the above steps and check if your rules work as expected.

## 5\. Disable the Stop Processing More Rules Option

 By adjusting the settings in the Outlook app, you can instruct it to halt the processing of additional rules once a specific rule has run. However, this can lead to Outlook ignoring all subsequent rules, giving a false impression that your rules are not functioning correctly. To avoid this, you need to disable the “stop processing more rules” option by following the steps below.

1. In Outlook, head over to **File > Info > Manage Rules & Alerts**.
2. Select your rule from the list.
3. Click the **Change Rule** option and select **Edit Rule Settings** from the list.  
![Edit Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-outlook-rule.jpg)
4. Clear the **stop processing more rules** checkbox.
5. Click **Finish** and then **Apply**.

## 6\. Configure Outlook Rules to Run on All Devices

 Another reason why your Outlook rules may not work is if you have configured them to run on a specific device only. Here’s how you can change that.

1. In Outlook, head over to **File > Info > Manage Rules & Alerts**.
2. Double-click the problematic rule.
3. Under **Select conditions**, uncheck the **on this computer only** box.
4. Hit **Finish** followed by **Apply**.  
![Configure Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/configure-outlook-rule.jpg)

## 7\. Activate Cached Exchange Mode

 When you enable the Cached Exchange Mode, Outlook retains a copy of your mailbox within the Outlook data file. This can help the app implement your rules without any issues.

 To enable Cached Exchange Mode in Outlook:

1. Open Outlook and click the **File** menu.
2. In the Info tab, click **Account Settings**, and select **Account Settings**.
3. Under the **Email** tab, select your account and click **Change**.
4. Click **More Settings** and select **Advanced**.
5. Tick the **Use Cached Exchange Mode** checkbox.
6. Hit **Apply** followed by **OK**.

## 8\. Run the Outlook Inbox Repair Tool

 When you use Microsoft Outlook on your Windows PC, it generates OST and PST files to store your account data locally. If these data files become inaccessible for some reason, your Outlook rules may stop working. Fortunately, Outlook includes an inbox repair tool that can help you [repair Outlook data files with ease](https://www.makeuseof.com/how-to-repair-corrupted-pst-and-ost-files-in-microsoft-outlook-using-recovery-toolbox/). Here’s how to run it.

1. Right-click the Outlook shortcut and select **Properties**.
2. Under the **Shortcut** tab, click the **Open File Location** button.
3. Double-click on **SCANPST.EXE** to run it.
4. In the Microsoft Outlook Inbox Repair Tool window, click the **Browse** button and then navigate to the following directory:  
`C:\Users\*username*\AppData\Local\Microsoft\Outlook`  
 Make sure you replace **\*username\*** in the above path with your own username.
5. Select the profile you want to repair and then click **Start**.  
![Outlook Inbox Repair Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/outlook-inbox-repair-tool.jpg)

 Restart Outlook after this and check if the issue is still there.

## 9\. Update the Outlook App

 Using an outdated version of Outlook can also lead to such issues. If you have [disabled automatic updates for Office apps](https://www.makeuseof.com/windows-stop-automatic-office-updates/), use these steps to update the Outlook app.

1. Open Outlook and select the **File** menu in the top-left corner.
2. Choose the **Office Account** tab from the left column.
3. Click **Update Options > Update Now**.  
![Update Outlook App in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/update-outlook-app-in-windows.jpg)

 Wait for Microsoft Office to check for new updates and install them. Following that, Outlook rules should start working.

## 10\. Reset All the Rules

 Lastly, if none of the above tips help, you can consider deleting all the Outlook rules and then setting them up again. Doing so will help fix any issues caused by improper configuration or corrupt data.

 To delete all the Outlook rules at once, [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Outlook.exe /cleanrules** in the text box and press **Enter**.

![Delete Outlook Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-outlook-rules.jpg)

 Once Outlook deletes all the rules, head to **Manage Rules & Alerts** and set them up again.

## Manage Your Emails Efficiently With Outlook Rules

 Without Outlook rules, organizing your inbox can be quite challenging, especially if you receive a lot of emails throughout the day. Hopefully, one or more of the above tips have proven useful, and Outlook rules are now working as before.

 To help out, we have compiled a list of useful solutions that should get Outlook rules to work again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-transfer-speed-averting-sudden-stops/"><u>Boosting Windows Steam Transfer Speed: Averting Sudden Stops</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-11-pro-data-recovery-an-infographic-to-conquer-iphone-data-loss-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 11 Pro Data Recovery – An Infographic to Conquer iPhone Data Loss | Stellar</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-high-definition-hardware-unveiled-by-gamers-for-2024/"><u>[Updated] High-Definition Hardware Unveiled by Gamers for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-top-ranked-pixel-perfection-appweb-software/"><u>[Updated] In 2024, Top-Ranked Pixel Perfection App/Web Software</u></a></li>
<li><a href="https://win11.techidaily.com/bootable-backup-a-self-reliant-approach/"><u>Bootable Backup: A Self-Reliant Approach</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-13-pro-max-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 13 Pro Max To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-user-interference-with-windows-clocks/"><u>Blocking User Interference with Windows Clocks</u></a></li>
<li><a href="https://win11.techidaily.com/boost-user-experience-add-portable-menus-on-win11plus/"><u>Boost User Experience: Add Portable Menus on Win11+</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-xiaomi-redmi-12-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Xiaomi Redmi 12 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-canon-video-editing-handbook-software-tips-and-trends/"><u>New The Ultimate Canon Video Editing Handbook Software, Tips, and Trends</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-wait-winning-strategies-to-fasten-upstart-in-win11/"><u>Beat The Wait: Winning Strategies to Fasten Upstart in Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/compiling-the-best-12-cost-free-video-apps-for-all-platforms-for-2024/"><u>Compiling the Best 12 Cost-Free Video Apps for All Platforms for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-stream-with-style-hacks-to-keep-your-daily-video-game-engaging/"><u>[New] In 2024, Stream with Style  Hacks to Keep Your Daily Video Game Engaging</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/speak-and-stun-on-snapchat-voice-change-made-simple-for-2024/"><u>Speak and Stun on Snapchat  Voice Change Made Simple for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-ai-assistant-via-vivetool/"><u>Activating Windows AI Assistant via ViveTool</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-ancient-art-of-role-playing-evolutionary-trajectory/"><u>[Updated] 2024 Approved  The Ancient Art of Role-Playing  Evolutionary Trajectory</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-8-window-study-secrets/"><u>Boost Productivity with These 8 Window Study Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-unsolicited-activation-of-windows-marketplace/"><u>Blocking Unsolicited Activation of Windows Marketplace</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-10-premier-free-windows-screencasting-apps/"><u>2024 Approved  10 Premier Free Windows Screencasting Apps</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-quik-or-not-a-review-of-gopros-editor-and-pc-alternatives-for-better-videos/"><u>Updated In 2024, Quik or Not? A Review of GoPros Editor & PC Alternatives for Better Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/in-2024-where-the-best-youtube-symbols-are-hidden/"><u>In 2024, Where the Best YouTube Symbols Are Hidden</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-mastering-online-meetings-best-choices-for-2024/"><u>[New] Mastering Online Meetings  Best Choices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-pitfalls-of-error-xffffff-in-print-tasks/"><u>Avoiding the Pitfalls of Error XFFFFFF in Print Tasks</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-read-this-review-to-learn-everything-you-need-to-know-about-leeming-lut-pro-and-how-to-apply-pro-luts-using-different-video-editors/"><u>2024 Approved Read This Review to Learn Everything You Need to Know About Leeming LUT Pro and How to Apply Pro LUTs Using Different Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-dominance-in-windows-appbrowser-arena/"><u>Blueprint for Dominance in Windows' App/Browser Arena</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-winapp-and-web-browser-mastery/"><u>Blueprint for WinApp and Web Browser Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-glitches-a-guide-to-fixing-error-code-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-real-time-performance-on-windows-11-task-monitor/"><u>Boosting Real-Time Performance on Windows 11 Task Monitor</u></a></li>
<li><a href="https://ai-topics.techidaily.com/a-detailed-guide-to-making-your-pictures-speak/"><u>A Detailed Guide to Making Your Pictures Speak</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-error-xc0f1103f-in-windows-11-nvidias-geforce-now/"><u>Banishing Error Xc0f1103f in Windows 11, NVIDIA's GeForce Now</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-nokia-xr21-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Nokia XR21 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-tecno-pova-5-pro-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Tecno Pova 5 Pro Device SIM</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-5-essential-filming-accessories-for-online-creators/"><u>2024 Approved  Top 5 Essential Filming Accessories for Online Creators</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-excel-pace-on-a-windows-system/"><u>Boosting Your Excel Pace on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/facebooks-visual-storytelling-what-angle-matters-most/"><u>Facebook's Visual Storytelling  What Angle Matters Most?</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-accessing-windowsstore-folder/"><u>Breaking Down Barriers: Accessing WindowsStore Folder</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-complications-with-an-efficient-in-place-windows-11-update/"><u>Avoiding Complications with an Efficient, In-Place Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overuse-steps-for-efficient-wlanextexe/"><u>Avoiding Overuse: Steps for Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-digital-discourse-with-windows-11/"><u>Begin Your Digital Discourse with Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-enhancing-outdoor-vision-with-gopro-and-live-streaming-platforms/"><u>[New] 2024 Approved  Enhancing Outdoor Vision with GoPro and Live Streaming Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-roadblocks-reinstating-access-on-windows-11-system/"><u>Avoiding Roadblocks: Reinstating Access on Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-functions-of-winservicesexe/"><u>Breaking Down the Functions of Winservices.exe</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>