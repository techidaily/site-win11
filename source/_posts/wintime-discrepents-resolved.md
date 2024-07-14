---
title: WinTime Discrepents Resolved
date: 2024-07-13T10:29:34.692Z
updated: 2024-07-14T10:29:34.692Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes WinTime Discrepents Resolved
excerpt: This Article Describes WinTime Discrepents Resolved
keywords: Time Discrepancies Solved,WinTime Issue Fixes,Correcting Time Mismatches,Time Sync Restored,Eliminate Time Errors,Time Alignment Success,Resolve Timing Conflicts
thumbnail: https://thmb.techidaily.com/eb645c13ee9dd9fbe7f99fc761b9dd81222823674663074f051eaef5c591591c.jpg
---

## WinTime Discrepents Resolved

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-stores-error-x80131500/"><u>Troubleshooting Microsoft Store's Error X80131500</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-samsung-galaxy-f54-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Samsung Galaxy F54 5G Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-illusion-is-over-separating-authentic-from-counterfeit-windows-store-titles/"><u>The Illusion Is Over: Separating Authentic From Counterfeit Windows Store Titles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-vivo-y55s-5g-2023-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Vivo Y55s 5G (2023)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-sharing-stories-every-day-best-practices-in-personal-videography-for-2024/"><u>[Updated] Sharing Stories Every Day  Best Practices in Personal Videography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-action-camera-bargains-selecting-top-6-for-under-100-costs/"><u>2024 Approved  Action Camera Bargains  Selecting Top 6 for Under $100 Costs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-lava-yuva-2-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Lava Yuva 2 to PC? | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-focusing-on-the-best-ways-to-convert-slow-motion-video-to-normal/"><u>In 2024, Focusing On The Best Ways To Convert Slow-Motion Video to Normal</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mend-admin-level-function-disruptions/"><u>Steps to Mend Admin-Level Function Disruptions</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-of-iphone-12-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-script-setbacks-winerror-solutions-revealed/"><u>Navigating Script Setbacks: WinError Solutions Revealed</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-cutting-edge-hd-screen-recorders-the-finest-titles/"><u>In 2024, Cutting-Edge HD Screen Recorders - The Finest Titles</u></a></li>
<li><a href="https://win11.techidaily.com/reasons-behind-non-existent-drive-letters-and-fix-methods/"><u>Reasons Behind Non-Existent Drive Letters and Fix Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-unfoldable-folders-in-win1110-on-double-clicks/"><u>How to Overcome Unfoldable Folders in Win11/10 on Double-Clicks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-top-10-accelerating-youtube-platforms-for-motivation-and-inspiration-for-2024/"><u>The Top 10 Accelerating YouTube Platforms for Motivation and Inspiration for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-photo-ordering-software-roundup/"><u>Essential Windows Photo Ordering Software Roundup</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-cutting-ties-with-instagram-navigating-a-permanent-exit-strategy/"><u>[New] 2024 Approved  Cutting Ties with Instagram  Navigating a Permanent Exit Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-11s-mail-app-converting-html-in-emails-back-to-plain-text/"><u>Solutions for Windows 11'S Mail App: Converting HTML in Emails Back to Plain Text</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/free-software-showdown-the-leading-10-audio-capture-utilities/"><u>Free Software Showdown  The Leading 10 Audio Capture Utilities</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-quickflips-how-tweets-jumpstart-video-fame/"><u>[Updated] 2024 Approved  QuickFlips  How Tweets Jumpstart Video Fame</u></a></li>
<li><a href="https://win11.techidaily.com/managing-intermittent-default-printer-choice/"><u>Managing Intermittent Default Printer Choice</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/backupbuddy-reviewers-thoughts/"><u>BackupBuddy Reviewers Thoughts</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-with-windows-printmanagement-msc-errors/"><u>Overcoming Obstacles with Windows 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-the-no-nonsense-guide-to-lively-tiktok-live-visits/"><u>[Updated] The No-Nonsense Guide to Lively TikTok Live Visits</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-devices-in-the-dormant-system-state/"><u>Controlling Devices in the Dormant System State</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensive-guide-to-applying-and-customizing-filters-in-video-editing/"><u>[Updated] Comprehensive Guide to Applying and Customizing Filters in Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-win-ratio-valorant-optimization-guide/"><u>Enhancing Win Ratio: Valorant Optimization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-microsoft-m365-flaw-error-30015-26/"><u>Mitigating Microsoft M365 Flaw: Error 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-tracking-and-managing-network-data-using-netstat-in-win11/"><u>Master the Art of Tracking and Managing Network Data Using Netstat in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-control-key-operability-with-ease-on-windows-11/"><u>Restoring Control Key Operability with Ease on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/team-meeting-screens-not-showing-up/"><u>Team Meeting Screens Not Showing Up?</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-analyzing-investment-for-video-promotion/"><u>[New] 2024 Approved  Analyzing Investment for Video Promotion</u></a></li>
<li><a href="https://win11.techidaily.com/guide-on-activating-and-running-sfc-on-pc/"><u>Guide on Activating and Running SFC on PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-nokia-xr21-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Nokia XR21 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unrecognized-hardware-issue-on-windows-1110/"><u>Solving ‘Unrecognized Hardware’ Issue on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/quick-settings-mastery-for-efficient-pc-use-on-win-11/"><u>Quick Settings Mastery for Efficient PC Use on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-video-sequences-fixing-delay-on-windows/"><u>Speeding Up Video Sequences: Fixing Delay on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-with-windows-11-rebuild/"><u>New Horizons with Windows 11 Rebuild</u></a></li>
<li><a href="https://win11.techidaily.com/mending-ms-store-malfunctions-error-code-0x80072f17-solution/"><u>Mending MS Store Malfunctions: Error Code 0X80072f17 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-ending-the-gpsvc-hang-up-loop/"><u>Strategies for Ending the GPSVC Hang-Up Loop</u></a></li>
<li><a href="https://win11.techidaily.com/gpu-strain-tested-the-most-effective-win-utilities-ranked/"><u>GPU Strain Tested: The Most Effective Win Utilities Ranked</u></a></li>
</ul></div>
