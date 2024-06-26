---
title: Master the Art of Effortless Data Purging in Windows 10/11
date: 2024-06-25T10:03:19.106Z
updated: 2024-06-26T10:03:19.106Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/installing-kali-linux-effortlessly-on-a-windows-pc/"><u>Installing Kali Linux Effortlessly on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/superior-pc-weather-apps-selection/"><u>Superior PC Weather Apps Selection</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://win11.techidaily.com/win11-terminal-reset-procedure-essentials/"><u>Win11 Terminal Reset Procedure Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-offline-mode-in-microsoft-onedrive/"><u>Setting Up Offline Mode in Microsoft OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-move-your-qbittorrent-installation-to-a-different-windows-pc/"><u>How to Move Your qBittorrent Installation to a Different Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-restoring-windows-11-search-efficiency/"><u>Essential Tips: Restoring Windows 11 Search Efficiency</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-top-anime-impersonators-a-voice-transformation-guide/"><u>Updated 2024 Approved Top Anime Impersonators A Voice Transformation Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-get-your-game-face-on-best-websites-to-download-games-for-2024/"><u>New Get Your Game Face On Best Websites to Download Games for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-blur-background-of-your-youtube-video-2-easy-ways-for-2024/"><u>How to Blur Background of Your YouTube Video - 2 Easy Ways for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-minecraft-pixel-art-is-a-trending-subject-and-they-simply-consist-of-in-game-pixel-artworks-besides-the-minecraft-houses-farms-or-cities-lets-explore-th/"><u>New Minecraft Pixel Art Is a Trending Subject, and They Simply Consist of In-Game Pixel Artworks, Besides the Minecraft Houses, Farms, or Cities. Lets Explore the Fantastic World of Minecraft Pixel Art</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/escape-from-ennui-with-humor-top-20-funny-faces-in-social-media-jail/"><u>Escape From Ennui with Humor  Top 20 Funny Faces in Social Media Jail</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/enhancing-photographic-expression-through-snapchat-edits-for-2024/"><u>Enhancing Photographic Expression Through Snapchat Edits for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-accelerate-creativity-pro-level-lunapic-techniques-unveiled/"><u>In 2024, Accelerate Creativity  Pro-Level LunaPic Techniques Unveiled</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-in-picture-softening-techniques/"><u>2024 Approved  Mastering In-Picture Softening Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-meta-descriptions-top-template-strategies/"><u>[New] 2024 Approved  Elevate Meta Descriptions  Top Template Strategies</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-the-art-of-gameye-immersive-video-recording/"><u>2024 Approved  The Art of GamEye  Immersive Video Recording</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>