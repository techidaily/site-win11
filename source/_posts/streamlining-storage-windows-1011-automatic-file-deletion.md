---
title: "Streamlining Storage: Windows 10/11 Automatic File Deletion"
date: 2024-08-16T00:32:54.420Z
updated: 2024-08-17T00:32:54.420Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Storage: Windows 10/11 Automatic File Deletion"
excerpt: "This Article Describes Streamlining Storage: Windows 10/11 Automatic File Deletion"
keywords: Auto Delete Files Win,Windows 10 Storage Save,Windows 11 Efficient Saves,File Management Win10,Auto File Cleaning Win11,Deletion Policy Windows,Optimize Win Storage
thumbnail: https://thmb.techidaily.com/a2a04cdf466fbea2e01b9f9b4e0e053a2190bbd1cddde4903063c61616ed0d4f.jpg
---

## Streamlining Storage: Windows 10/11 Automatic File Deletion

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-enhance-live-stream-performance-with-these-5-pro-tips/"><u>[New] Enhance Live Stream Performance with These 5 Pro Tips</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-navigating-video-sharing-from-imovie-to-the-vimeo-network/"><u>[New] In 2024, Navigating Video Sharing  From iMovie to the Vimeo Network</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-step-by-step-approach-to-mastering-free-youtube-video-transcription/"><u>[Updated] 2024 Approved  A Step-by-Step Approach to Mastering Free YouTube Video Transcription</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-google-meet-conversation-blueprint-for-success-for-2024/"><u>[Updated] The Google Meet Conversation Blueprint for Success for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unlocking-the-power-of-targeted-keywords-on-youtube-for-2024/"><u>[Updated] Unlocking the Power of Targeted Keywords on YouTube for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-step-by-step-tips-for-captivating-igtv-backgrounds/"><u>2024 Approved  Step-By-Step Tips for Captivating IGTV Backgrounds</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-art-of-sprucing-up-instagram-stories-with-branded-graphics/"><u>2024 Approved  The Art of Sprucing Up Instagram Stories with Branded Graphics</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-ultimate-guide-unpacking-the-secrets-of-du-recorder/"><u>2024 Approved  Ultimate Guide  Unpacking the Secrets of Du Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-if-the-c-drive-keeps-filling-up-for-no-reason-on-windows/"><u>6 Fixes if the C: Drive Keeps Filling Up for No Reason on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://win11.techidaily.com/8-latest-innovations-in-windows-11-post-update-release/"><u>8 Latest Innovations in Windows 11, Post-Update Release</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-at-dxvks-impact-on-windows-gaming/"><u>A Closer Look at DXVK's Impact on Windows Gaming</u></a></li>
<li><a href="https://fake-location.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-activate-windows-calculator/"><u>A Step-by-Step Walkthrough: Activate Window's Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/a-visionary-approach-to-taskbar-design-essential-improvements-for-microsofts-new-release/"><u>A Visionary Approach to Taskbar Design: Essential Improvements for Microsoft's New Release</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-top-7-fixes-for-browser-blockades-on-win-os/"><u>Access Denied? Top 7 Fixes for Browser Blockades on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-perfect-hover-over-experience-win11-mouse-guide/"><u>Achieve a Perfect Hover Over Experience: Win11 Mouse Guide</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-terminal-for-quake-interface/"><u>Activating Windows Terminal for Quake Interface</u></a></li>
<li><a href="https://win11.techidaily.com/address-keyboard-malfunction-fixing-unresponsive-function-keys-on-windows-11/"><u>Address: Keyboard Malfunction - Fixing Unresponsive Function Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-call-failed-problems-in-windows-devices/"><u>Addressing 'Call Failed' Problems in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-profile-alerts-on-windows-1011/"><u>Addressing Invalid Profile Alerts on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-self-shutting-windows-11-units/"><u>Addressing Self-Shutting Windows 11 Units</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-how-windows-11-manages-your-files-a-look-at-its-recovery-system/"><u>Analyzing How Windows 11 Manages Your Files: A Look at Its Recovery System</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-10-and-11s-vital-parts-missing-alert/"><u>Avoiding Windows 10 & 11'S Vital Parts Missing Alert</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-obscured-windows-11-query-engine/"><u>Awakening Obscured Windows 11 Query Engine</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-fixing-windows-scheduler-failures/"><u>Beat the Bug: Fixing Windows Scheduler Failures</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-battle-guide-to-winning-in-diablo/"><u>Beginner's Battle Guide to Winning in Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-10-safe-free-software-download-sites/"><u>Best Practices: 10 Safe Free Software Download Sites</u></a></li>
<li><a href="https://win11.techidaily.com/black-and-white-brilliance-a-guide-for-the-shadows/"><u>Black & White Brilliance: A Guide for the Shadows</u></a></li>
<li><a href="https://win11.techidaily.com/bolster-window-app-interactions-via-efficient-internet-accessing-methods/"><u>Bolster Window App Interactions via Efficient Internet Accessing Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-user-engagement-with-context-menu-update-options/"><u>Bolstering User Engagement with Context Menu Update Options</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-mastering-the-search-function-of-windows-11/"><u>Boost Productivity: Mastering the Search Function of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-android-performance-with-optimized-resources-on-wsl/"><u>Boosting Android Performance with Optimized Resources on WSL</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-functionality-restore-search-box-to-win11-taskbar/"><u>Boosting Functionality: Restore Search Box to Win11 TaskBar</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-administration-local-groups-and-users/"><u>Boosting Windows Administration: Local Groups and Users</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-update-autopilot-hurdles/"><u>Breaking Down Windows Update Autopilot Hurdles</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-the-insignia-usb-vga-converter-step-by-step-guide/"><u>Download & Install the Insignia USB-VGA Converter – Step-by-Step Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-picks-gpus-optimized-for-4k-gaming/"><u>Elite Picks  GPUs Optimized for 4K Gaming</u></a></li>
<li><a href="https://fox-info.techidaily.com/how-to-capture-clear-and-smooth-aquatic-moments-for-2024/"><u>How to Capture Clear and Smooth Aquatic Moments for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-smart-7-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Smart 7 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-dead-iphone-se-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover data from dead iPhone SE | Stellar</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-xiaomi-13-ultra-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Xiaomi 13 Ultra?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-13t-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi 13T to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-innovative-methods-blurring-the-line-between-work-and-distractions/"><u>In 2024, Innovative Methods  Blurring the Line Between Work and Distractions</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-mastering-device-independent-techniques-for-capturing-youtube-live-streams/"><u>In 2024, Mastering Device-Independent Techniques for Capturing YouTube Live Streams</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-8-social-and-adventure-games-for-oculus-users/"><u>In 2024, Top 8 Social & Adventure Games for Oculus Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-lip-sync-experience-5-must-try-apps-for-2024/"><u>New The Ultimate Lip Sync Experience 5 Must-Try Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719290483430-quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC</u></a></li>
<li><a href="https://win11.techidaily.com/1719347165719-restore-order-in-your-keyboard-chaos-with-these-9-fixes-for-broken-windows-shortcuts-and-combinations/"><u>Restore Order in Your Keyboard Chaos with These 9 Fixes for Broken Windows Shortcuts and Combinations.</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/solve-your-lg-monitor-difficulties-a-step-by-step-approach-for-windows-10-7-and-81-users/"><u>Solve Your LG Monitor Difficulties: A Step-by-Step Approach for Windows 10, 7, and 8.1 Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/streamlining-file-management-the-top-six-tips-for-your-windows-11-mov-files/"><u>Streamlining File Management - The Top Six Tips for Your Windows 11 MOV Files</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-vivo-x90s-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/the-photographers-roadmap-to-stunning-hdr-portraits/"><u>The Photographer's Roadmap to Stunning HDR Portraits</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-non-functioning-hp-laptop-camera-on-windows-11/"><u>Troubleshooting a Non-Functioning HP Laptop Camera on Windows 11</u></a></li>
</ul></div>
