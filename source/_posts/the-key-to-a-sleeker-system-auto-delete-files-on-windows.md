---
title: "The Key to a Sleeker System: Auto-Delete Files on Windows"
date: 2024-06-25T11:29:45.747Z
updated: 2024-06-26T11:29:45.747Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Key to a Sleeker System: Auto-Delete Files on Windows"
excerpt: "This Article Describes The Key to a Sleeker System: Auto-Delete Files on Windows"
keywords: Delete Windows Files Efficiently,Auto File Removal Windows,Streamline Windows Cleanup,Optimize Storage, Remove Clutter,Simplify Windows Management,Enhance System Organization,Automate Unwanted Windows Files
thumbnail: https://thmb.techidaily.com/56026dcff0736582c2fe4e321c8c74705a564d75fd36c3fc8b04cf6e73d4d3c9.jpg
---

## The Key to a Sleeker System: Auto-Delete Files on Windows

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
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-fixing-dism-error-0x800f082f-in-windows/"><u>Swift Strategies for Fixing DISM Error: 0X800F082F in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-file-viewer-rights-in-windows-1011/"><u>How to Regain File Viewer Rights in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-unlock-the-secrets-of-measuring-ethernet-speeds/"><u>Windows Wonders: Unlock the Secrets of Measuring Ethernet Speeds</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-productivity-configure-multiple-monitors-in-win11/"><u>Achieve Peak Productivity: Configure Multiple Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-editing-the-win11-list-of-premier-video-scripts/"><u>Elevate Editing: The Win11 List of Premier Video Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-direct-voice-communication-for-xbox-on-windows-11/"><u>Reinstating Direct Voice Communication for Xbox on Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-unveiling-the-secrets-of-facebook-lives-dual-display/"><u>[New] 2024 Approved  Unveiling the Secrets of Facebook Live's Dual Display</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-what-is-mov-format-and-how-to-edit-mov-video-creatively/"><u>New What Is MOV Format and How To Edit MOV Video Creatively?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-silent-the-screen-how-to-strip-audio-from-your-movies-in-imovie/"><u>Updated 2024 Approved Silent the Screen How to Strip Audio From Your Movies in iMovie</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-ultimate-selection-top-10-zero-dollar-video-calls/"><u>2024 Approved  The Ultimate Selection  Top 10 Zero-Dollar Video Calls</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-on-your-apple-iphone-15-pro-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock on your Apple iPhone 15 Pro and iPad?</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-constructing-a-premium-video-editing-pc-from-the-ground-up/"><u>[Updated] Constructing a Premium Video Editing PC From the Ground Up</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/tracing-influence-the-quest-for-your-passionate-pioneers/"><u>Tracing Influence  The Quest for Your Passionate Pioneers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-leading-titles-in-editing-webcam-videos-effectively/"><u>[New] In 2024, Leading Titles in Editing Webcam Videos Effectively</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-apowersoft-picks-top-pc-screen-recorder-reviewed/"><u>[New] Apowersoft Picks  Top PC Screen Recorder Reviewed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>