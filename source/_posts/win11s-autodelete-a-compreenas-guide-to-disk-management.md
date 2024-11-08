---
title: "Win11's Autodelete: A Compreenas Guide to Disk Management"
date: 2024-11-03T16:38:32.236Z
updated: 2024-11-07T19:09:49.178Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11's Autodelete: A Compreenas Guide to Disk Management"
excerpt: "This Article Describes Win11's Autodelete: A Compreenas Guide to Disk Management"
keywords: Win11 Disk Deletion,Delete Files Win11,File AutoDeletion Win11,Windows 11 Autodelete,Manage Disks in Win11,Win11 Data Loss Prevention,AutoDeleted Files Guide
thumbnail: https://thmb.techidaily.com/2e5cadcabaa5bc146e9286cd6ccf5e30c43742afdff538e1080a5add013b39bf.jpg
---

## Win11's Autodelete: A Compreenas Guide to Disk Management

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-innovative-approaches-to-android-video-capture-for-2024/"><u>[New] Innovative Approaches to Android Video Capture for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-comprehensive-guide-to-nvidia-screener-use/"><u>[Updated] In 2024, Comprehensive Guide to NVIDIA Screener Use</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/5-most-effective-methods-to-unlock-iphone-x-in-lost-mode-by-drfone-ios/"><u>5 Most Effective Methods to Unlock iPhone X in Lost Mode</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/androids-prime-video-calls-top-10-cost-free-options-for-2024/"><u>Android's Prime Video Calls Top 10 Cost-Free Options for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/compreenhensive-guide-for-youtube-short-video-creators-for-2024/"><u>Compreenhensive Guide for YouTube Short Video Creators for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connect-your-microsoft-wireless-adapter-with-ease-overcoming-challenges-on-windows-10-platforms/"><u>Connect Your Microsoft Wireless Adapter with Ease: Overcoming Challenges on Windows 10 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/dazzling-display-holiday-themed-window-wonders/"><u>Dazzling Display: Holiday Themed Window Wonders</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-fix-non-syncing-itunes-album-covers-on-your-iphone-and-ipod-complete-guide/"><u>How to Fix Non-Syncing iTunes Album Covers on Your iPhone and iPod: Complete Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-your-path-to-perfect-videos-with-any-of-these-7-free-tools/"><u>In 2024, Your Path to Perfect Videos with Any of These 7 Free Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-connections-with-spotify/"><u>Mastering Windows 11 Connections with Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/nine-essential-tips-for-new-windows-11-users-avoid-these-errors/"><u>Nine Essential Tips for New Windows 11 Users - Avoid These Errors</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solution-matching-internet-on-mobile-and-desktop/"><u>Speedy Solution: Matching Internet on Mobile & Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/subtle-system-tweaks-windows-toolbars-unseen/"><u>Subtle System Tweaks: Windows Toolbars Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-signature-compliant-update-files-on-windows/"><u>Tackling Non-Signature Compliant Update Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-to-resolve-skies-sse-woes/"><u>The Quest to Resolve Skies' SSE Woes</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-strategies-to-exit-s-mode/"><u>Unlocking Your PC: Strategies to Exit S Mode</u></a></li>
<li><a href="https://win-tips.techidaily.com/1728505200837-windows1011/"><u>Windows10/11で欠落したユーザーディレクトリを回復する効果的な手順</u></a></li>
</ul></div>

