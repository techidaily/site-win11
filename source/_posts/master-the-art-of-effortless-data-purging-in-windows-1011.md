---
title: Master the Art of Effortless Data Purging in Windows 10/11
date: 2024-07-13T10:09:04.943Z
updated: 2024-07-14T10:09:04.943Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master the Art of Effortless Data Purging in Windows 10/11
excerpt: This Article Describes Master the Art of Effortless Data Purging in Windows 10/11
keywords: Data Purge Mastery,Effortless Data Delete,Windows Easy Cleanup,Zero-Trouble Deletion,Purging Guide W10/W11,Simplified System Cleaning,No Hassle File Removal
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
---

## Master the Art of Effortless Data Purging in Windows 10/11

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

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

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

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

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
<li><a href="https://win11.techidaily.com/1719281347770-winshift-fixes-guide-needed/"><u>WinShift Fixes Guide Needed!</u></a></li>
<li><a href="https://win11.techidaily.com/1719307585235-the-key-to-no-fuss-vbox-installation-deps-please/"><u>The Key to No-Fuss VBox Installation? Deps, Please!</u></a></li>
<li><a href="https://win11.techidaily.com/1719302930005-bypass-incompatibility-woes-in-windows-xp-7-and-8-easily/"><u>Bypass Incompatibility Woes in Windows XP, 7 & 8 Easily.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-essential-manual-for-srt-conversion-techniques/"><u>The Essential Manual for SRT Conversion Techniques</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-edit-avi-files-on-windows-8-with-ease-2023s-top-editor/"><u>New 2024 Approved Edit AVI Files on Windows 8 with Ease 2023S Top Editor</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevating-your-gameplay-on-youtube-with-these-essential-tags/"><u>2024 Approved  Elevating Your Gameplay on YouTube with These Essential Tags</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-premier-audio-file-transformer-effortless-mp3-creation-in-seconds/"><u>New Premier Audio File Transformer Effortless MP3 Creation in Seconds</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-top-7-free-pc-screen-capture-programs/"><u>[New] 2024 Approved  Top 7 Free PC Screen Capture Programs</u></a></li>
<li><a href="https://win11.techidaily.com/1719319611800-overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing.</u></a></li>
<li><a href="https://win11.techidaily.com/why-and-how-to-choose-effective-encoders-on-your-pc/"><u>Why and How to Choose Effective Encoders on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/1719249883200-revive-keys-in-crisis-arrows-rescued/"><u>Revive Keys in Crisis: Arrows Rescued!</u></a></li>
<li><a href="https://win11.techidaily.com/11-different-ways-to-uninstall-software-in-windows-11/"><u>11 Different Ways to Uninstall Software in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-premier-game-snapshot-software-for-2024/"><u>[New] Premier Game Snapshot Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719313088233-break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly!</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-for-warhammer-40k-players-stop-pc-lag-issues/"><u>Winning Strategies for Warhammer 40K Players - Stop PC Lag Issues</u></a></li>
<li><a href="https://win11.techidaily.com/1719320103482-windows-xbox-not-working-fix-it-fast/"><u>Windows Xbox Not Working? Fix It Fast!</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-network-connections-tool/"><u>10 Ways to Open the Windows Network Connections Tool</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leading-voice-to-text-programs/"><u>2024 Approved  Leading Voice to Text Programs</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-why-steam-cant-synch-files-in-pc-settings/"><u>Unraveling Why Steam Can't Synch Files in PC Settings</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-open-your-iphone-15-pro-max-without-a-home-button-by-drfone-ios/"><u>How To Open Your iPhone 15 Pro Max Without a Home Button</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-online-viewers-count-counter/"><u>[Updated] In 2024, Online Viewers Count Counter</u></a></li>
<li><a href="https://win11.techidaily.com/10-essential-steps-for-accessing-windows-nettools/"><u>10 Essential Steps for Accessing Windows NetTools</u></a></li>
<li><a href="https://win11.techidaily.com/1719254078043-navigating-through-windows-issues-made-simple/"><u>Navigating Through Windows Issues Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/0x8004def5-on-onedrive-unraveling-windows-11-troubles/"><u>0X8004DEF5 on OneDrive - Unraveling Windows 11 Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-implications-of-removing-windows-11s-taskbar-chatting-capability-on-you/"><u>Unpacking the Implications of Removing Windows 11'S Taskbar Chatting Capability on You</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-six-easy-steps-to-enhance-your-videos-with-music-without-expense/"><u>Updated 2024 Approved Six Easy Steps to Enhance Your Videos with Music Without Expense</u></a></li>
<li><a href="https://win11.techidaily.com/10-pro-tips-for-naming-and-organizing-files-in-windows/"><u>10 Pro Tips for Naming and Organizing Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-service-failure-in-windows-11/"><u>Troubleshooting Steam Service Failure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719313398544-maximize-full-screen-capture-efficiency-with-these-fixes-in-windows/"><u>Maximize Full-Screen Capture Efficiency with These Fixes in Windows.</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-spectacular-sites-featuring-rich-3d-and-golden-text/"><u>[New] Spectacular Sites Featuring Rich 3D and Golden Text</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-explorers-gallery-view-capability/"><u>Unlocking File Explorer's Gallery View Capability</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-dynamic-dividends-boosting-social-media-roi-with-fb-ad-animations/"><u>[New] Dynamic Dividends  Boosting Social Media ROI with FB Ad Animations</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-t2x-5g-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted T2x 5G Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://win11.techidaily.com/11-fresh-features-in-windows-11-post-update-milestone/"><u>11 Fresh Features in Windows 11, Post-Update Milestone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/apple-iphone-15-plus-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>Apple iPhone 15 Plus Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://win11.techidaily.com/1719285734353-breathe-life-back-into-your-computers-print-command-wwinplusp/"><u>Breathe Life Back Into Your Computer's Print Command (WWin+P)</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-acoustic-ambiance-in-photo-videos/"><u>2024 Approved  Acoustic Ambiance in Photo Videos</u></a></li>
<li><a href="https://win11.techidaily.com/1719254765561-solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-redirecting-onedrive-storage-location/"><u>Win 11 - Redirecting OneDrive Storage Location</u></a></li>
<li><a href="https://win11.techidaily.com/10-substitutes-for-bitlocker-in-winxp-systems/"><u>10 Substitutes for BitLocker in WinXP Systems</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/best-free-video-cutting-tools-for-divx-files-updated-2023/"><u>Best Free Video Cutting Tools for Divx Files (Updated 2023)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-the-ultimate-guide-to-free-video-looping-software-for-windows-and-mac/"><u>New In 2024, The Ultimate Guide to Free Video Looping Software for Windows and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/1719310047074-overcome-compatibility-issues-with-easy-fixed-steps/"><u>Overcome Compatibility Issues with Easy Fixed Steps.</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-freebies-best-media-centers-for-windows-users/"><u>Top 7 Freebies: Best Media Centers for Windows Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719277126929-windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back</u></a></li>
<li><a href="https://win11.techidaily.com/1719288445449-overcoming-wwin-plus-printer-not-responding-issue-in-windows/"><u>Overcoming WWin + Printer Not Responding Issue in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/1719312305473-premium-savings-with-w11-pro-key-dont-miss-out/"><u>Premium Savings with W11 Pro Key - Don't Miss Out!</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-streamline-your-mpeg2-videos-with-virtualdub-download/"><u>New 2024 Approved Streamline Your MPEG2 Videos with VirtualDub Download</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-recovery-drive-tool/"><u>10 Ways to Open the Windows Recovery Drive Tool</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-top-10-text-to-video-ai-generators-to-create-engaging-and-captivating-videos-for-2024/"><u>New Top 10 Text-to-Video AI Generators to Create Engaging and Captivating Videos for 2024</u></a></li>
</ul></div>
