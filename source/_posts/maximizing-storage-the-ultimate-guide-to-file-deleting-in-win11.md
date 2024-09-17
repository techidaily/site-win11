---
title: "Maximizing Storage: The Ultimate Guide to File Deleting in Win11"
date: 2024-09-11T04:30:40.514Z
updated: 2024-09-17T08:34:06.463Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Storage: The Ultimate Guide to File Deleting in Win11"
excerpt: "This Article Describes Maximizing Storage: The Ultimate Guide to File Deleting in Win11"
keywords: Win11 File Cleanup,Optimal Data Management,Efficient Space Saving,Delete Files Win11 Guide,Storage Maximize Win11,Win11 Deletion Tips,Manage Win11 Disk Space
thumbnail: https://thmb.techidaily.com/8404aae8332517e90ea13209ccbcb49d56b9cbe41228f9bbeee698b42d6caf34.jpg
---

## Maximizing Storage: The Ultimate Guide to File Deleting in Win11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121334/18498" target="_top" id="2121334">
  <img src="//a.impactradius-go.com/display-ad/18498-2121334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121334/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/effective-strategies-for-reducing-audio-file-size-via-email-a-guide-for-windows-and-web-users/"><u>Effective Strategies for Reducing Audio File Size via Email: A Guide for Windows and Web Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/erfolgreiche-methoden-grossere-avi-filme-zu-0-euro-in-mp4-umwandeln/"><u>Erfolgreiche Methoden: Größere AVI-Filme Zu 0 Euro in MP4 Umwandeln</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-oppo-reno-8t-5g-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Oppo Reno 8T 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://win11.techidaily.com/playing-your-dvd-files-in-mp4-format-3-easy-methods/"><u>Playing Your DVD Files in MP4 Format: 3 Easy Methods</u></a></li>
<li><a href="https://win11.techidaily.com/preserve-your-dvd-collection-effortlessly-with-wonderfox-dvd-ripper-and-converter-technology/"><u>Preserve Your DVD Collection Effortlessly with WonderFox DVD Ripper & Converter Technology</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-mastering-the-art-of-adding-image-watermarks-to-videos/"><u>Quick Guide: Mastering the Art of Adding Image Watermarks to Videos</u></a></li>
<li><a href="https://win11.techidaily.com/record-screenshots-and-audio-a-guide-to-capturing-video-on-your-lenovo-device/"><u>Record Screenshots and Audio: A Guide to Capturing Video on Your Lenovo Device</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/recording-realities-evaluating-the-power-and-precision-of-apeaksoftware-for-2024/"><u>Recording Realities – Evaluating the Power and Precision of Apeaksoftware for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-smooth-operation-in-kodi-on-windows-via-full-system-reset/"><u>Restoring Smooth Operation in Kodi on Windows via Full System Reset</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-video-merging-without-re-encoding-a-step-by-step-guide/"><u>Seamless Video Merging Without Re-Encoding: A Step-by-Step Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silencing-the-silent-printouts-in-your-device/"><u>Silencing the Silent Printouts in Your Device</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-game-changer-going-from-console-to-pc/"><u>The Ultimate Game-Changer: Going From Console to PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/tinkering-with-technology-a-new-sound-for-your-phone/"><u>Tinkering with Technology A New Sound for Your Phone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-secure-and-safe-interactions-a-list-of-trustworthy-chat-services-for-strangers/"><u>Updated In 2024, Secure and Safe Interactions A List of Trustworthy Chat Services for Strangers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    