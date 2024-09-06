---
title: "Streamlining File Management: Windows 11'S Automatic Deletion Feature Explained"
date: 2024-09-05T08:37:51.257Z
updated: 2024-09-06T08:37:51.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining File Management: Windows 11'S Automatic Deletion Feature Explained"
excerpt: "This Article Describes Streamlining File Management: Windows 11'S Automatic Deletion Feature Explained"
keywords: Win11 Auto Delete Files,File Management Simplified,W11 Automated Cleanup,Windows Streamline Storage,Deletion Feature in W11,Efficient File Organization,W11 Files Automatic Purge
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Streamlining File Management: Windows 11'S Automatic Deletion Feature Explained

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
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
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-flexibility-in-viewing-with-youtube-tv-options/"><u>[New] 2024 Approved  Flexibility in Viewing with YouTube TV Options</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-analyzing-lack-of-interaction-is-it-a-block/"><u>[Updated] 2024 Approved  Analyzing Lack of Interaction  Is It a Block?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-cost-free-win-10-screencast-solutions-top-5-picks-for-2024/"><u>[Updated] Cost-Free Win 10 Screencast Solutions  Top 5 Picks for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-get-crystal-clear-iphone-photos-with-our-free-red-eye-toolkit/"><u>[Updated] Get Crystal Clear iPhone Photos with Our Free Red-Eye Toolkit</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-home-sweet-habitat-6-basic-mc-dwellings-demystified-for-2024/"><u>[Updated] Home Sweet Habitat  6 Basic MC Dwellings Demystified for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-seamless-facial-smoothing-motion-blur-techniques-in-picsart/"><u>[Updated] Seamless Facial Smoothing  Motion Blur Techniques in Picsart</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-stepwise-reduction-tactics-for-audio-levels-in-fl-studio/"><u>2024 Approved  Stepwise Reduction Tactics for Audio Levels in FL Studio</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-optical-character-recognition-ocr-understanding-image-based-text-capture-with-copernic-software/"><u>A Deep Dive Into Optical Character Recognition (OCR): Understanding Image-Based Text Capture with Copernic Software</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/advanced-graphics-tweaking-for-optimal-display-performance/"><u>Advanced Graphics Tweaking for Optimal Display Performance</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-pc-conflicts-with-pct-guide/"><u>Conquer PC Conflicts with PCT Guide</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-disabling-the-mystery-of-0x8007045d-on-windows-11/"><u>Decoding and Disabling the Mystery of 0X8007045d on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-leverage-copernic-for-efficient-cloud-storage-searches/"><u>Discover How to Leverage Copernic for Efficient Cloud Storage Searches</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-performance-by-controlling-cpu-hogs/"><u>Enhancing Performance by Controlling CPU Hogs</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-stability-of-deskanywhere-on-win11-systems/"><u>Enhancing Stability of DeskAnywhere on Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-integrating-msixbundle-and-msix-extensions-into-windows/"><u>Essential Guide: Integrating Msixbundle & MSIX Extensions Into Windows</u></a></li>
<li><a href="https://win11.techidaily.com/family-fortification-the-top-5-corrections-for-safe-haven/"><u>Family Fortification: The Top 5 Corrections for Safe Haven</u></a></li>
<li><a href="https://win11.techidaily.com/find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search</u></a></li>
<li><a href="https://win11.techidaily.com/1723809008305-find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search!</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-steams-unauthorized-files-problem-in-win11/"><u>Fixing Steam's Unauthorized Files Problem in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/getting-around-a-non-opening-windows-command-prompt/"><u>Getting Around a Non-Opening Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/handling-printer-id-clashes-in-windows/"><u>Handling Printer ID Clashes in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Samsung Galaxy Z Flip 5? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correctly-handle-read-only-folders-on-windows/"><u>How to Correctly Handle Read-Only Folders on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-broken-registry-items-in-windows-11/"><u>How to Fix Broken Registry Items in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-se-2020-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID on Your Apple iPhone SE (2020)?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-the-wsl-error-4294967295-on-windows/"><u>How to Resolve the WSL Error 4294967295 on Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-update-your-pcs-bluetooth-hardware-with-broadcom-drivers-windows-1087/"><u>How to Update Your PC's Bluetooth Hardware with Broadcom Drivers (Windows 10/8/7)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-github-desktop-in-windows-11-and-11/"><u>How to Use GitHub Desktop in Windows 11 and 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-transform-insta-videos-into-mp4-format-expert-methods-revealed/"><u>In 2024, Transform Insta Videos Into MP4 Format  Expert Methods Revealed</u></a></li>
<li><a href="https://solve-lab.techidaily.com/leveraging-the-power-of-nvenc-encoding-within-handbrake-a-comprehensive-guide/"><u>Leveraging the Power of NVENC Encoding Within Handbrake: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/linux-flourish-windows-subsystem-effect/"><u>Linux Flourish: Windows Subsystem Effect?</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-pc-resource-demand-fixing-wmi-usage-issues/"><u>Lowering PC Resource Demand: Fixing WMI Usage Issues</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-maze-of-full-screen-issues-fix-sonic-adventure-crashes-win-on-windows-11/"><u>Master the Maze of Full-Screen Issues: Fix Sonic Adventure Crashes, Win! On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1723809006534-mastering-social-media-growth-with-seamless-menu-expand-functions-on-fb-li-yt-top-level-navigation-essentials/"><u>Mastering Social Media Growth with Seamless Menu Expand Functions on FB, LI, YT - Top-Level Navigation Essentials!</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-fixing-windows-1011-filesystem-issues/"><u>Navigating and Fixing Windows 10/11 Filesystem Issues</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/optimal-mac-animation-storer/"><u>Optimal Mac Animation Storer</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-downloads-a-guide-to-the-microsoft-store/"><u>Optimize Your Downloads: A Guide to the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-round-corners-on-windows-11/"><u>Rectify Round Corners on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-failed-to-install-error-in-discord-win11/"><u>Remedying the Failed to Install Error in Discord (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/renaming-microsoft-account-admin-for-enhanced-security/"><u>Renaming Microsoft Account Admin for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-stream-disconnection-in-remote-pc-mode/"><u>Resolving Stream Disconnection in Remote PC Mode</u></a></li>
<li><a href="https://win11.techidaily.com/shake-off-frozen-clicks-top-6-tips-for-windows-users/"><u>Shake Off Frozen Clicks: Top 6 Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-output-5-essential-windows-productivity-hacks/"><u>Skyrocketing Output: 5 Essential Windows Productivity Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-the-steps-to-epic-gaming-success/"><u>Speeding Up the Steps to Epic Gaming Success</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-win11-cc-troubleshooting-made-easy/"><u>Step-by-Step Guide: Win11 CC Troubleshooting Made Easy</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-tutorial-for-watching-video-formats-mov-in-windows-11-environment/"><u>Step-by-Step Tutorial for Watching Video Formats (MOV) in Windows 11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-quick-systemsettings-fix-on-windows-11/"><u>Strategies for Quick SystemSettings Fix on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-document-discovery-using-copernics-expert-text-search-features-for-professionals/"><u>Streamline Document Discovery Using Copernic's Expert Text Search Features for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/the-stranded-site-stories-seven-windows-workarounds-for-access-issues/"><u>The Stranded Site Stories: Seven Windows Workarounds for Access Issues</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-to-virtualbox-70-on-windows-11-your-ultimate-walkthrough/"><u>Transitioning to VirtualBox 7.0 on Windows 11 – Your Ultimate Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-adjusting-creation-and-modification-dates-in-windows/"><u>Understanding and Adjusting Creation & Modification Dates in Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-status-quo-of-fifth-generation-connectivity-through-a-verizon-perspective/"><u>Understanding the Status Quo of Fifth-Generation Connectivity Through a Verizon Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-potential-chromium-setup-for-windows-11/"><u>Unleash Full Potential: Chromium Setup for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-potential-mastering-the-run-command-enhancement/"><u>Unlock Windows 11 Potential: Mastering the Run Command Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/win-fixes-overcoming-firefox-page-load-issues-in-windows/"><u>Win Fixes: Overcoming Firefox Page Load Issues in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>