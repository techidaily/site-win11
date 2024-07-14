---
title: Strategic Steps for Purging Microsoft Defender Traces From Win 11
date: 2024-07-13T09:56:46.693Z
updated: 2024-07-14T09:56:46.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategic Steps for Purging Microsoft Defender Traces From Win 11
excerpt: This Article Describes Strategic Steps for Purging Microsoft Defender Traces From Win 11
keywords: Cleanse MDT (Microsoft Defender) Traces,Win 11 Trace Cleanup,Defender Removal for Windows 11,Purging Microsoft Security Traces,Removing Defender Logs Win 11,Disable Microsoft Defender on W11,MDT Exclusion Strategies (Windows 11)
thumbnail: https://thmb.techidaily.com/ad4388017aad038e4020bb83bed704ce1407b9c4acd2fda68cb5e54d580ca0be.jpg
---

## Strategic Steps for Purging Microsoft Defender Traces From Win 11

 Windows Defender is Microsoft's antivirus built into your Windows PC to protect you from viruses, malware threats, and attacks. It maintains a record of its scans and actions in its Protection History folder.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

## What Is the Microsoft Defender Protection History? Why Should You Clear It?

 One of the best antivirus for your PC, [Windows Defender keeps getting better with some powerful upgrades](https://www.makeuseof.com/microsoft-defender-riskai-upgrade/). The detections made by Windows Defender appear on the Protection History page—which means you can view actions that Microsoft Defender Antivirus has taken on your behalf. These would be scans done to identify and block malware and other threats. And also the recommendations (highlighted in red or yellow) for actions you should take.

 You also have access to all this information in a clear and easily understandable form, including Potentially Unwanted Apps that have been removed, or key services that have been turned off. The Protection History will also show the detections that appear while performing a Windows Defender Offline scan.

![Protection History Page in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ProtectionHistory1.jpg)

 Though Windows Defender keeps the history of its detections for 30 days, you can clear it before that time if you need to—for example, when a lot of scan logs have accumulated. Clearing the Protection History would help you make space on your PC and keep Defender running smoothly. Remember, you must be signed in as an administrator to clear the protection history so [do check if you have administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/).

 Now let's see four easy ways to clear Protection History in Windows 10 and 11\.

## 1\. How to Clear the Microsoft Defender's Protection History Folder

 You can manually clear the Protection History by deleting the contents of the Service folder in the Windows Defender folder using File Explorer. Here's how:

1. Press **Windows + R** keys to bring up the Run box.
2. Copy and paste the path below and click on **OK** or hit **enter:** **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History**  
![Defender History Folder Path Typed in Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/open-defender-history-folder-via-run.jpg)
3. You can also paste the **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History** path in the File Explorer navigation bar and then hit **enter**.  
![Defender History Folder Path in File Explorer Navigation Bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/defender-history-folder-path-in-file-explorer.jpg)  
 Alternatively, you can navigate to the **Defender Protection History** folder using the above path in File Explorer. If you don't see the **ProgramData** folder when you open the Local Drive, select **View** and then tick the box next to **Hidden items**.  
![Click Hidden Items under View to See ProgramData Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Click-Hidden-Items-under-View-to-See-ProgramData-Folder.jpg)
4. Open the **Service** folder and select all the files inside it. **Right-click** and select **Delete** to clear all the files. Then exit File Explorer.  
![Select Files in History Folder and Delete Them](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Select-Files-in-History-Folder-and-Delete-Them.jpg)
5. Next, search for **Windows Security** and open it.
6. Under **Virus & threat protection** click on **Manage settings**.  
![Virus and Threat Protection Settings in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Virus-and-Threat-Protection-in-Windows-Security.jpg)
7. Finally, toggle the button to **Off** and then to **On** again, for **Real-Time protection** and **Cloud-delivered protection**.

## 2\. How to Clear the Microsoft Defender Protection History Using the Event Viewer

 You can also manually clear the Defender Protection History via the [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/)—a useful app to analyze the event logs on your device. Here's how:

1. First, do a Windows search for **Event Viewer** and click on the app result under **Best match** to open **Event Viewer.**
2. Under the **Event Viewer (Local)** on the left pane, expand the **Applications and Services Logs**.
3. Under **Applications and Services Logs**, click on the down arrow next to the **Microsoft** folder.
4. Click on **Windows** in the left pane to open the list of Windows files on the middle pane.
5. Scroll down through the list of files on the middle pane to find **Windows Defender**.  
![Windows Defender selected in Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-in-Event-Viewer.jpg)
6. Double-click on **Windows Defender**.
7. Then right-click on **Operational** and select **Open** to view all the past logs.  
![Open Operational Option to View Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Operational-Option-to-View-Defender-Logs.jpg)
8. Now you can right-click on **Operational** in the left pane and choose **Clear Log**. Or click on **Clear Log** on the right pane under **Actions**.  
![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  
![Options to Clear Logs or Save and Clear Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Clear-and-Save-and-Clear-Options-for-Defender-Logs.jpg)

## 3\. How to Clear the Microsoft Defender Protection History via PowerShell

 What if you want the Protection History to clear automatically after a specific number of days? You can also use a PowerShell command to do that. Let's see how to do this:

1. Type **PowerShell** in the search bar. Right-click on **Windows PowerShell** under **Best match** and select **Run as administrator**. Or choose **Run as administrator** on the right search pane.
2. Click **Yes** on the UAC prompt that appears.
3. The **Administrator: PowerShell** window will open up. Type or copy and paste the following command and then hit **enter**:

`Set-MpPreference -ScanPurgeItemsAfterDelay 7`

![Command to Clear Protection History in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-Command-to-Clear-Protection-History.jpg)

 The number **7** at the end of the command is the number of days after which the protection history logs will be cleared. Just change that number to specify when you want the protection history to be cleared. And it will be cleared automatically.

## 4\. How to Clear the Microsoft Defender Protection History Using the Group Policy Editor

 If you have a PC with Windows 10 Pro, Windows 11 Pro, or a higher version, you can also use the Group Policy Editor to clear the Defender Protection History automatically. Though there are solutions to [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) too. But let's see how to clear Protection History via Group Policy Editor in Windows Pro and higher versions:

1. Press **Win + R** keys to open the Run box. Type **gpedit.msc** to open the **Local Group Policy Editor**. Or just type **gpedit** in the search bar and click on **Edit Group Policy** under **Best match** to open it.
2. In the **Local Group Policy Editor**, on the left pane under **Computer Configuration**, expand **Administrative Templates** by clicking on the down arrow next to it.
3. Inside the **Administrative Templates** folder, click on **Windows Components** and the list of its components would come up on the middle pane of the **Group Policy Editor**.
4. Then scroll down to find **Windows Defender Antivirus** and double-click on it.  
![Navigate to Windows Defender Antivirus in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-Antivirus-in-Group-Policy-Editor.jpg)
5. In the list of **Windows Defender** items, **double-click** on the **Scan** folder.
6. In the right pane, **double-click** on **Turn on removal of items from scan history folder**. Or click **Edit policy setting** in the middle pane. This policy setting defines the number of days items should be kept in the scan history folder before being permanently removed.  
![Turn on Removal of Items Policy in Defender Scan Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Edit-Removal-of-Items-Policy-in-Defender-Scan-Folder.jpg)
7. Next, select **Edit policy setting** to open the policy window. It would be showing **Not Configured** by default. To set the number of days, toggle on the button next to **Enabled**. The default number of days, which is **30**, would then be set. If you set the number of days to zero, items will be kept forever and will not be automatically removed. So just change the days to whenever you want the items to be removed. Finally, click **Apply** and then **OK**.  
![Specify Number of Days to Remove Scan Items in Defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Set-Number-of-Days-to-Remove-Scan-Items.jpg)

 Now, you won't need to manually clear Protection History every time—the items in the scan history folder would be deleted automatically after the days you've specified.

## Clear the Microsoft Defender Protection History Whenever You Want

 If you ever want to clear Defender Protection History, you know how easy it is to do it through any of the four ways discussed above. If you would want to refer to the Protection History logs later, you can use the Save and Clear option while clearing Protection History using Event Viewer.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/steps-for-restoring-network-link-in-windows/"><u>Steps for Restoring Network Link in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-system-information-tool-on-windows/"><u>10 Ways to Open the System Information Tool on Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-the-ultimate-guide-to-fb-messenger-call-archiving/"><u>2024 Approved  The Ultimate Guide to FB Messenger Call Archiving</u></a></li>
<li><a href="https://win11.techidaily.com/win11-wi-fi-data-metric-control-guide/"><u>Win11 Wi-Fi Data Metric Control Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhance-your-mobile-experience-with-inshots-music-features/"><u>Enhance Your Mobile Experience with InShot's Music Features</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-android-studio-efficiency-on-windows-dev-environment/"><u>Maximize Android Studio Efficiency on Windows Dev Environment</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-s24-ultra-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy S24 Ultra Phone FRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/prose-perfection-on-a-windows-desktop-the-top-5-picks/"><u>Prose Perfection on a Windows Desktop - The Top 5 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/1719302097899-opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now!</u></a></li>
<li><a href="https://win11.techidaily.com/unshackling-your-powershell-scripts-top-4-strategies-for-execution-lift/"><u>Unshackling Your PowerShell Scripts: Top 4 Strategies for Execution Lift</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ptimizing-youtube-view-duration-three-steps-52-chars/"><u>[New] Optimizing YouTube View Duration - Three Steps (52 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-from-the-windows-11-compatibility-shackles/"><u>Unlocking Your PC From the Windows 11 Compatibility Shackles</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-rewind-game-pc-redemption/"><u>AtlasOS Rewind: Game PC Redemption</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveiling-the-simple-nature-of-storytelling/"><u>Unveiling the Simple Nature of Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win1011-nvidia-opengl-error-3/"><u>Overcoming Win10/11 NVIDIA OpenGL Error 3</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-blend-excelling-at-classic-games-in-hd-clarity-through-scummvm-on-windows/"><u>The Perfect Blend: Excelling at Classic Games in HD Clarity Through ScummVM on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-routine-file-explorer-revival-tips-for-win-11/"><u>Rebooting Routine: File Explorer Revival Tips for Win 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/maximizing-engagement-with-youtube-on-facebook-platforms-for-2024/"><u>Maximizing Engagement with YouTube on Facebook Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-quick-fixes-top-6-fb-lite-video-tools-for-2024/"><u>[New] Quick Fixes  TOP 6 FB Lite Video Tools for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-12-html5-videophones-for-optimal-viewing/"><u>[New] Top 12 HTML5 Videophones for Optimal Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/transformative-tips-for-a-productive-win-11-bar/"><u>Transformative Tips for a Productive Win 11 Bar</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-demystifying-youtube-seo-terminology-and-tactics-for-2024/"><u>[New] Demystifying YouTube SEO Terminology and Tactics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-windows-11-installation-with-these-easy-to-implement-tweaks/"><u>Optimize Your Windows 11 Installation with These Easy-to-Implement Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hypervisor-bsos-quick-solutions-on-winxose/"><u>Mastering Hypervisor BSOS: Quick Solutions on WINXOSE</u></a></li>
<li><a href="https://win11.techidaily.com/restore-optional-features-on-windows-os-with-ease/"><u>Restore Optional Features on Windows OS with Ease</u></a></li>
<li><a href="https://some-techniques.techidaily.com/indoor-brightness-boosted-by-external-radiance-for-2024/"><u>Indoor Brightness Boosted by External Radiance for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-disk-usage-errors-in-modern-windows-os/"><u>Circumventing Disk Usage Errors in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1110-onedrive-errors/"><u>Troubleshooting Windows 11/10 OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-windows-with-5-mac-inspired-ideas/"><u>Simplify Your Windows with 5 Mac-Inspired Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-and-mitigating-windows-pause-problems/"><u>Uncovering and Mitigating Windows Pause Problems</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-unsolicited-search-window-opens-in-windows-11/"><u>Stopping Unsolicited Search Window Opens in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-comprehensive-look-at-slug-line-practices/"><u>2024 Approved  A Comprehensive Look at Slug Line Practices</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-stalled-resource-monitors-procedure-in-windows-11/"><u>Streamlining Stalled Resource Monitors: Procedure in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Honor Magic 5? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-diy-sports-highlights-a-comprehensive-guide/"><u>[New] In 2024, DIY Sports Highlights  A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-cleaner-windows-11-desktop-layout/"><u>Designing a Cleaner Windows 11 Desktop Layout</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-changefake-your-tecno-spark-20-proplus-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Tecno Spark 20 Pro+ Location on Viber | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-champion-top-titles-best-free-video-caption-grabs/"><u>2024 Approved  Champion Top Titles  Best Free Video Caption Grabs</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winfreedomgpt-guide-launching-unrestricted-chatbots/"><u>WinFreedomGPT Guide: Launching Unrestricted ChatBots</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-lost-files-restore-with-smart-windows-11-fixes/"><u>Dxgi.dll Lost Files? Restore with Smart Windows 11 Fixes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-online-video-editors-with-music-libraries-free-and-paid-choices/"><u>New 2024 Approved Online Video Editors with Music Libraries Free and Paid Choices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-realme-11x-5g-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Realme 11X 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-with-a-side-of-kali-linux/"><u>Securing Windows with a Side of Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/wu-and-orchestrator-the-pillars-of-update-routine/"><u>WU & Orchestrator: The Pillars of Update Routine</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-understanding-your-twitter-archives-potential-for-2024/"><u>[New] Understanding Your Twitter Archive's Potential for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-approach-for-backup-of-snippets/"><u>Methodical Approach for Backup of Snippets</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-no-audio-output-on-win-10-devices/"><u>Tackling Error: No Audio Output on Win 10 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-sandbox-a-win-11-guide/"><u>Configure Your Sandbox: A Win 11 Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/instagram-breaks-tradition-whatsapp-delivers-2fa-codes/"><u>Instagram Breaks Tradition: WhatsApp Delivers 2FA Codes</u></a></li>
<li><a href="https://win11.techidaily.com/set-up-a-stunning-slideshow-easily-create-in-win11-heres-how/"><u>Set Up a Stunning Slideshow: Easily Create in Win11 Here’s How</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-top-rated-video-editing-apps-with-automatic-reframing-for-2024/"><u>New Top-Rated Video Editing Apps with Automatic Reframing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-halting-windows-boot-straight-into-cmos-setup/"><u>Techniques for Halting Windows Boot Straight Into CMOS Setup</u></a></li>
</ul></div>
