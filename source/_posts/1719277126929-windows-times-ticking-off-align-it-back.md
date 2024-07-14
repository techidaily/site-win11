---
title: Windows Time's Ticking Off? Align It Back
date: 2024-07-13T11:08:12.350Z
updated: 2024-07-14T11:08:12.350Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Time's Ticking Off? Align It Back
excerpt: This Article Describes Windows Time's Ticking Off? Align It Back
keywords: Windows Time Adjustment,Clock Sync Issue,System Time Error,Realign Windows Time,Time Discrepancy Fix,Windows Timestamp Correction,Aligning OS Time Correctly
thumbnail: https://thmb.techidaily.com/d03b713b6f6bb665862fd62a3d2bf27a022b75c767766bbee971744ee132695c.jpg
---

## Windows Time's Ticking Off? Align It Back

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
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-effective-ways-how-to-block-facebook-video-ads/"><u>[Updated] In 2024, Effective Ways | How to Block Facebook Video Ads?</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprerante-tale-to-transform-your-windows-11-desk/"><u>A Comprerante Tale to Transform Your Windows 11 Desk</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-leveraging-past-conversations-on-twitter-for-2024/"><u>[New] Leveraging Past Conversations on Twitter for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-11-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-setup-must-have-windows-store-essentials/"><u>Accelerate Setup: Must-Have Windows Store Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-support-tasks-map-windows-troubleshooting-tools/"><u>Accelerate Support Tasks: Map Windows Troubleshooting Tools</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-strategies-to-overcome-unseen-tiktok-limitations/"><u>[New] In 2024, Strategies to Overcome Unseen TikTok Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/a-scholarly-approach-to-embracing-hdr-in-windows-11-workflows/"><u>A Scholarly Approach to Embracing HDR in Windows 11 Workflows</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-the-windows-startup-settings/"><u>A Complete Guide to the Windows Startup Settings</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-skyrocket-visibility-mastering-google-analytics-for-youtubers/"><u>[New] In 2024, Skyrocket Visibility  Mastering Google Analytics for YouTubers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-efficient-keyword-utilization-discover-the-best-7-online-video-tag-extractors-reviewed/"><u>[New] 2024 Approved  Efficient Keyword Utilization  Discover the Best 7 Online Video Tag Extractors Reviewed</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-zte-axon-40-lite-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on ZTE Axon 40 Lite</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-approach-to-managing-settings-in-win11-ui/"><u>A Fresh Approach to Managing Settings in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-upgrading-virtualbox-v70-in-win11/"><u>A Beginner's Guide to Upgrading VirtualBox v7.0 in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-apple-iphone-13-mini-location-on-skout-drfone-by-drfone-virtual-ios/"><u>How to Change Apple iPhone 13 mini Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719370951528-xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips!</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/leading-free-internet-based-tiktok-to-mp3-converter-apps-6-for-2024/"><u>Leading Free, Internet-Based TikTok to MP3 Converter Apps (6) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-top-win-drawing-apps-that-challenge-procreates-edge/"><u>5 Top Win Drawing Apps That Challenge Procreate's Edge</u></a></li>
<li><a href="https://win11.techidaily.com/a-universal-companion-windows-now-app-for-iosmac-and-windows-devices/"><u>A Universal Companion: Windows Now App for iOS/Mac and Windows Devices</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-the-professionals-playbook-streaming-live-videos-on-tiktok-from-computer/"><u>[Updated] In 2024, The Professional’s Playbook  Streaming Live Videos on TikTok From Computer</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-viral-video-roundup-top-tiktok-reaction-shenanigans/"><u>[Updated] In 2024, Viral Video Roundup  Top TikTok Reaction Shenanigans</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-for-restoring-windows-hello-fingerprint-functionality/"><u>7 Key Steps for Restoring Windows Hello Fingerprint Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/6-disappearing-windows-traits-explained/"><u>6 Disappearing Windows Traits Explained</u></a></li>
<li><a href="https://win11.techidaily.com/8-apps-for-changing-the-createdmodified-date-on-a-file-on-windows/"><u>8 Apps for Changing the Created/Modified Date on a File on Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-check-which-intel-processor-generation-you-have-on-windows/"><u>8 Ways to Check Which Intel Processor Generation You Have on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-handy-manual-assessing-and-annulling-window-history-data/"><u>A Handy Manual: Assessing & Annulling Window History Data</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-collageknights-syncing-videos-across-devices-for-2024/"><u>[New] CollageKnights  Syncing Videos Across Devices for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/iphoneipad-podcasting-for-excellent-travel-sessions-for-2024/"><u>IPhone/iPad Podcasting for Excellent Travel Sessions for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-top-tips-navigating-the-latest-facebook-features/"><u>[Updated] In 2024, Top Tips  Navigating the Latest Facebook Features</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-quick-and-easy-increase-or-decrease-story-video-speed/"><u>[New] Quick and Easy  Increase or Decrease Story Video Speed</u></a></li>
<li><a href="https://win11.techidaily.com/7-expert-moves-for-restoring-the-functionality-of-windows-services-control-panel/"><u>7 Expert Moves for Restoring the Functionality of Windows Services Control Panel</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-enrich-your-music-the-ultimate-photo-audio-integration-guide-sonic-visualization-for-2024/"><u>New Enrich Your Music The Ultimate Photo-Audio Integration Guide Sonic Visualization for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/9-pros-of-modernizing-to-windows-revamped-outlook/"><u>9 Pros of Modernizing to Windows' Revamped Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/7-strong-arguments-against-switching-from-win10-to-win11-immediately/"><u>7 Strong Arguments Against Switching From Win10 to Win11 Immediately</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-top-7-color-match-paint-apps/"><u>2024 Approved Top 7 Color Match Paint Apps</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-derek-walsh-phd-dr-jeffrey-l-gardiner-phd-and-david-c-muller-phd-from-their-book-understanding-the-psychology-of-religion-exploring-god-33/"><u>A Compre Written by Derek Walsh, PhD; Dr. Jeffrey L. Gardiner, PhD; and David C. Muller, PhD; From Their Book Understanding the Psychology of Religion: Exploring God Wise</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-twist-your-imagery-instagrams-video-rotation-guide-for-2024/"><u>[Updated] Twist Your Imagery  Instagram's Video Rotation Guide for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-traversing-through-windows-movie-makers-version-landscape/"><u>In 2024, Traversing Through Windows Movie Maker's Version Landscape</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-realme-narzo-60-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Realme Narzo 60 5GMirror Share to PC? | Dr.fone</u></a></li>
</ul></div>
