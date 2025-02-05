---
title: Clear Outdated Files with Confidence Using Windows 10/11'S Feature
date: 2025-02-02T19:48:08.214Z
updated: 2025-02-03T23:01:12.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clear Outdated Files with Confidence Using Windows 10/11'S Feature
excerpt: This Article Describes Clear Outdated Files with Confidence Using Windows 10/11'S Feature
keywords: Clear Files Windows 10,Update Old Windows Files,Confident File Cleaning,Windows Updater Tool,Deleting Outdated Data,Secure File Removal,Windows 10/11 Cleanup
thumbnail: https://thmb.techidaily.com/4f408d1e600338fdfbc4fe3abf110c58fed31529d9f9f53c6cd72af0ec21a5e5.jpg
---

## Clear Outdated Files with Confidence Using Windows 10/11'S Feature

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-securing-every-moment-tips-for-reliable-capture-of-google-meet-sessions/"><u>[New] In 2024, Securing Every Moment Tips for Reliable Capture of Google Meet Sessions</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-sonic-sculpture-how-to-mold-soundscapes-with-cost-free-effect-tools/"><u>[New] In 2024, Sonic Sculpture How to Mold Soundscapes with Cost-Free Effect Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mp4isotop3/"><u>無料MP4からISOへの高性能な変換ソフトウェア：おすすめランキングTOP3</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/how-to-modify-game-characters-vocal-presence-and-identity-in-free-fire-step-by-step-guide-included-free-for-2024/"><u>How to Modify Game Characters' Vocal Presence and Identity in Free Fire (Step-by-Step Guide Included, FREE) for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-troubleshoot-a-website-facing-a-503-service-error-message/"><u>How to Troubleshoot a Website Facing a 503 Service Error Message</u></a></li>
<li><a href="https://win11.techidaily.com/joyful-easter-celebrations-with-wonderfoxs-special-edition-for-the-holiday/"><u>Joyful Easter Celebrations with WonderFox's Special Edition for the Holiday</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-converting-videocasts-to-high-quality-mp3-files-in-minutes/"><u>Master the Art of Converting Videocasts to High-Quality MP3 Files in Minutes</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-apex-effective-fixes-for-the-infamous-error-code-23-glitch/"><u>Mastering Apex: Effective Fixes for the Infamous Error Code 23 Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-wav-file-creation-in-windows-10-for-clear-sound-capture/"><u>Mastering the Art of WAV File Creation in Windows 10 for Clear Sound Capture</u></a></li>
<li><a href="https://win11.techidaily.com/mp4-f4v/"><u>MP4に変換してください - F4Vファイルからのコンバージョンガイド</u></a></li>
<li><a href="https://win11.techidaily.com/pcgta5/"><u>PC上のGTA5キャプチャ手順: ステップバイステップガイド</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solution-for-no-audio-in-windows-media-player-step-by-step-instructions/"><u>Solution for No Audio in Windows Media Player: Step-by-Step Instructions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-honor-90-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Honor 90 | Dr.fone</u></a></li>
</ul></div>

