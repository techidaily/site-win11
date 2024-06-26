---
title: Revolutionize File Management with Windows' Automatic Deletion
date: 2024-06-25T10:25:46.469Z
updated: 2024-06-26T10:25:46.469Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revolutionize File Management with Windows' Automatic Deletion
excerpt: This Article Describes Revolutionize File Management with Windows' Automatic Deletion
keywords: Auto Delete Files,Windows File Management,Revolutionize File Handling,Streamlined File Erasure,Efficient File System,Quick File Cleanup,Secure Windows Deletion
thumbnail: https://thmb.techidaily.com/a770835b076eb6b9f15ef9eaa24a0d7865dfb16a5caaa3e52196c91037b09546.jpg
---

## Revolutionize File Management with Windows' Automatic Deletion

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/boost-windows-11-search-11-tricks-for-a-functional-bar/"><u>Boost Windows 11 Search: 11 Tricks for a Functional Bar</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-personalizing-your-desktop-with-widgets/"><u>Mastering Window 11: Personalizing Your Desktop with Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/embark-on-a-parallels-driven-path-for-windows-11-installation/"><u>Embark on a Parallels-Driven Path for Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-grouped-taskbar-symbols-on-windows-11/"><u>Clearing Grouped Taskbar Symbols on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-in-linux-sphere/"><u>Exploiting Windows Software in Linux Sphere</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-beast-boosting-fps-in-cs-go/"><u>Unleash the Beast - Boosting FPS in CS Go</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-top-8-best-video-grabbers-for-windows-10/"><u>[Updated] 2024 Approved  Top 8 Best Video Grabbers for Windows 10</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-realme-c51-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Realme C51 Phones with/without a PC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-streamline-your-youtube-shorts-thumbnail-process/"><u>[Updated] Streamline Your YouTube Shorts Thumbnail Process</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-xiaomi-civi-3-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Xiaomi Civi 3 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-crafting-spectaculous-fb-ad-videos-with-creativity/"><u>[New] 2024 Approved  Crafting Spectaculous Fb Ad Videos with Creativity</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-oneplus-nord-n30-se-frp-by-drfone-android/"><u>How Can We Bypass OnePlus Nord N30 SE FRP?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-vivo-x100-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Vivo X100 Devices</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-a-brief-guide-to-download-install-and-use-ez-grabber/"><u>2024 Approved  A Brief Guide to Download, Install, and Use EZ Grabber</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/mastering-photo-dimensions-how-to-choose-the-right-aspect-ratio/"><u>Mastering Photo Dimensions How to Choose the Right Aspect Ratio</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-animate-photo-online-with-these-awesome-tools-for-2024/"><u>New Animate Photo Online with These Awesome Tools for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>