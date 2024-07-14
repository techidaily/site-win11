---
title: "Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11"
date: 2024-07-13T09:54:23.799Z
updated: 2024-07-14T09:54:23.799Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11"
excerpt: "This Article Describes Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11"
keywords: Win11 File Cleanup,Daily Delete Schedule,Remove Junk Files Win,Automated File Deletion,Windows 11 Cleanup Tool,Unwanted Files Removal,Weekly File Purge (Win11)
thumbnail: https://thmb.techidaily.com/ef756af67baaa63e6513047560b51e7a06317e95c3578e612a362286e500591b.jpg
---

## Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-dive-into-the-world-of-lengthened-images-with-iphone/"><u>[New] In 2024, Dive Into the World of Lengthened Images with iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-non-functional-xbox-controller/"><u>Reviving Your Non-Functional Xbox Controller</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-0x80072efd-on-windows-devices/"><u>Remedying Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-enlargement-and-reduction-the-top-six-methods/"><u>Windows 11 Image Enlargement and Reduction – The Top Six Methods</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-six-wins-of-win11-over-macos/"><u>A Closer Look: Six Wins of Win11 Over MacOS</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-unveiling-the-mystery-scriptwriting-for-documentaries-for-2024/"><u>[Updated] Unveiling the Mystery  Scriptwriting for Documentaries for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-program-install-pathways-in-windows/"><u>Unveiling Program Install Pathways in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-powerpoint-outputs-9-steps-for-windows-users/"><u>Achieving Flawless PowerPoint Outputs: 9 Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/tech-guide-uninstalling-the-microsoft-store/"><u>Tech Guide: Uninstalling the Microsoft Store</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-add-border-to-instagram-video/"><u>How to Add Border to Instagram Video?</u></a></li>
<li><a href="https://win11.techidaily.com/pro-guide-how-to-locate-and-setup-shortcuts-near-win11s-power-icon/"><u>Pro Guide: How to Locate & Setup Shortcuts Near Win11's Power Icon</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unresponsive-grammarly-service-windows/"><u>Addressing Unresponsive Grammarly Service Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-flight-comrade-copilot-in-ws11/"><u>Restore Your Flight Comrade (Copilot) in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-vm-workflow-6-expert-tips-for-windows-users/"><u>Supercharge Your VM Workflow: 6 Expert Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/banish-unwanted-zoom-in-your-computer-writings/"><u>Banish Unwanted Zoom in Your Computer' Writings</u></a></li>
<li><a href="https://win11.techidaily.com/rebuilding-with-purpose-windows-11-from-scratch/"><u>Rebuilding with Purpose: Windows 11 From Scratch</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-expert-tips-for-enhancing-youtube-videos-through-seo-mastery/"><u>[New] In 2024, Expert Tips for Enhancing YouTube Videos Through SEO Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-security-keys-mismatch-in-windows-11-networks/"><u>Strategies for Correcting Security Keys Mismatch in Windows 11 Networks</u></a></li>
<li><a href="https://win11.techidaily.com/shaping-the-user-experience-with-wins-console/"><u>Shaping the User Experience with Win’s Console</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-windows-traditional-explore-view/"><u>Unleashing Windows' Traditional Explore View</u></a></li>
<li><a href="https://apple-account.techidaily.com/your-account-has-been-disabled-in-the-app-store-and-itunes-from-apple-iphone-se-by-drfone-ios/"><u>Your Account Has Been Disabled in the App Store and iTunes From Apple iPhone SE?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/color-enhancement-in-final-cut-pro-a-step-by-step-guide/"><u>Color Enhancement in Final Cut Pro A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-group-policy-management-in-windows-108/"><u>Simplifying Group Policy Management in Windows 10/8</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-proaudio-professionals-guide-analyzing-and-reviewing-the-top-8-daws-for-mac/"><u>New 2024 Approved ProAudio Professionals Guide Analyzing and Reviewing the Top 8 DAWs for Mac</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-xiaomi-13t-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Xiaomi 13T Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-smooth-windows-11-transitions-in-place-methods/"><u>Achieving Smooth Windows 11 Transitions: In-Place Methods</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-reliable-windows-photo-organizer-list/"><u>The Most Reliable Windows Photo Organizer List</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-navigating-ig-video-trends-building-your-next-marketing-plan/"><u>[Updated] In 2024, Navigating IG Video Trends  Building Your Next Marketing Plan</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels/"><u>[New] In 2024, Blueprints for Breaking Ground in Edu-Video Production on YouTube Channels</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harnessing-the-power-of-channels-boosting-telegram-presence/"><u>In 2024, Harnessing the Power of Channels  Boosting Telegram Presence</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lost-dll-mfc71u-on-windows/"><u>Troubleshooting Lost DLL: Mfc71u on Windows</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-expert-guide-to-enablingdisabling-multitasking-in-safari/"><u>[New] Expert Guide to Enabling/Disabling Multitasking in Safari</u></a></li>
<li><a href="https://win11.techidaily.com/9-fixes-to-try-when-steam-is-stuck-on-verifying-installation-for-windows/"><u>9 Fixes to Try When Steam Is Stuck on Verifying Installation for Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-transform-your-gopro-footage-free-video-editing-software-and-tutorials/"><u>2024 Approved Transform Your GoPro Footage Free Video Editing Software and Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-tricks-for-mass-folder-creation-at-a-click-in-windows-oses/"><u>The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-achieve-peak-performance-with-these-8-scheduler-apps/"><u>In 2024, Achieve Peak Performance with These 8 Scheduler Apps</u></a></li>
<li><a href="https://win11.techidaily.com/windows-set-your-own-idle-screen-time/"><u>Windows: Set Your Own Idle Screen Time</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-accessing-windows-pre-launch-settings/"><u>Step-by-Step: Accessing Windows' Pre-Launch Settings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-mellow-playtime-10-top-rated-stress-erasers/"><u>2024 Approved  Mellow Playtime  10 Top-Rated Stress Erasers</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-travel-planning-apple-maps-and-windows/"><u>Streamlining Travel Planning: Apple Maps & Windows</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-top-cinematographer-secrets-for-exceptional-visuals/"><u>[Updated] Top Cinematographer Secrets for Exceptional Visuals</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-icloud-lock-on-your-apple-iphone-xr-and-ipad-by-drfone-ios/"><u>In 2024, How to fix iCloud lock on your Apple iPhone XR and iPad</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-lunapic-ultimate-guide-for-professionals/"><u>Mastering LunaPic  Ultimate Guide for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/updating-reset-limit-after-unsuccessful-authentication-in-windows-1011/"><u>Updating Reset Limit After Unsuccessful Authentication in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-vmstart-fixes-to-avoid-errors-in-windows-11/"><u>Unlocking Your VMstart: Fixes to Avoid Errors in Windows 11</u></a></li>
</ul></div>
