---
title: "Streamlining Storage: Windows 10/11 Automatic File Deletion"
date: 2024-06-25T09:56:57.188Z
updated: 2024-06-26T09:56:57.188Z
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
<li><a href="https://win11.techidaily.com/maximizing-image-clarity-with-windows-11s-enhanced-photo-app/"><u>Maximizing Image Clarity with Windows 11'S Enhanced Photo App</u></a></li>
<li><a href="https://win11.techidaily.com/system-rescue-in-13-easy-to-follow-tips/"><u>System Rescue in 13 Easy-to-Follow Tips</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-normalcy-after-windows-video-failures/"><u>Restoring Normalcy After Windows Video Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-requires-elevation-puzzle-win-11s-error-740-solution/"><u>Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/unmasking-the-undisclosed-instructions-for-accessing-windows-personal-character-console/"><u>Unmasking the Undisclosed: Instructions for Accessing Windows’ Personal Character Console</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-gaming-potential-android-on-win-11-through-google-services-access/"><u>Unlock Gaming Potential: Android on Win 11 Through Google Services Access</u></a></li>
<li><a href="https://win11.techidaily.com/assigning-custom-codes-to-windows-software/"><u>Assigning Custom Codes to Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-make-a-lasting-impression-6-best-movie-intro-creation-tools/"><u>Updated 2024 Approved Make a Lasting Impression 6 Best Movie Intro Creation Tools</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-unlocking-the-power-of-facebook-slideshows-in-digital-marketing/"><u>In 2024, Unlocking the Power of Facebook Slideshows in Digital Marketing</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-convert-animated-gif-from-video-for-2024/"><u>Updated Convert Animated GIF From Video for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-8-best-educational-animation-software-for-school/"><u>Updated 8 Best Educational Animation Software for School</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-dynamic-sound-mixing-implementing-audio-ducking-techniques-to-subtly-reduce-background-tracks-for-2024/"><u>Updated Dynamic Sound Mixing Implementing Audio Ducking Techniques to Subtly Reduce Background Tracks for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-any-xiaomi-redmi-note-13-proplus-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Xiaomi Redmi Note 13 Pro+ 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-navigating-instagram-marketing-ultimate-guide-to-video-success/"><u>[Updated] In 2024, Navigating Instagram Marketing  Ultimate Guide to Video Success</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-free-video-recorders-for-every-android-user-for-2024/"><u>[New] Free Video Recorders for Every Android User for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/journey-into-the-metaverse-constructing-an-authentic-avatar-for-2024/"><u>Journey Into the Metaverse  Constructing an Authentic Avatar for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>