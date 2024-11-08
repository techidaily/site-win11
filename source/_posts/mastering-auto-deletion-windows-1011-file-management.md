---
title: "Mastering Auto-Deletion: Windows 10/11 File Management"
date: 2024-11-05T18:56:08.024Z
updated: 2024-11-07T20:05:32.906Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Auto-Deletion: Windows 10/11 File Management"
excerpt: "This Article Describes Mastering Auto-Deletion: Windows 10/11 File Management"
keywords: Win10/11 File Delete,Deleted Files Management,Win10 Auto-Remove,Save Space on PC,Efficient Data Cleanup,Manage Windows Deletion,Optimize Storage Systems
thumbnail: https://thmb.techidaily.com/9482ded5e871af812d18f96a64c4deb315943988e9201916667eb608e7a9ffd3.jpg
---

## Mastering Auto-Deletion: Windows 10/11 File Management

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-photographers-choice-compile-of-essential-apps/"><u>[New] Photographers' Choice Compile of Essential Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-step-by-step-tutorial-for-transforming-profile-photographs-on-social-networks-for-2024/"><u>[New] Step-by-Step Tutorial for Transforming Profile Photographs on Social Networks for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-power-play-enhancing-your-pages-popularity-ranking/"><u>[Updated] 2024 Approved The Power Play Enhancing Your Page's Popularity Ranking</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-the-volume-of-videos-on-a-64128gb-memory-bank/"><u>[Updated] In 2024, The Volume of Videos on a 64/128GB Memory Bank</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-visual-vibes-top-story-filter-rankings/"><u>[Updated] In 2024, Visual Vibes Top Story Filter Rankings</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-from-basic-to-brilliant-top-100plus-biographies-that-captivate-audiences/"><u>2024 Approved From Basic to Brilliant Top 100+ Biographies that Captivate Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/youtuber2024/"><u>次世代Youtuber向けに選ばれる動画編集ソフトウェアとハウツーガイド2024年版</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-leading-free-video-trimming-software-our-top-6-recommendations/"><u>Discover the Leading Free Video Trimming Software: Our Top 6 Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-conversion-from-qt-to-mp4-your-ultimate-guide-to-changing-quicktime-files/"><u>Effortless Conversion From QT to MP4: Your Ultimate Guide to Changing QuickTime Files</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/explore-our-selection-of-top-4-no-cost-virtual-planners-online/"><u>Explore Our Selection of Top 4 No-Cost Virtual Planners Online</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-honor-magic-vs-2-easily-by-drfone-android/"><u>How To Unlock a Honor Magic Vs 2 Easily?</u></a></li>
<li><a href="https://win11.techidaily.com/itunes-iphoneandandroid/"><u>ITunesにダビング！カメラ撮影動画から音楽へ - iPhone&Android利用者向けガイド</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-5-top-sites-to-download-royalty-free-comedy-background-music/"><u>New 5 Top Sites to Download Royalty Free Comedy Background Music</u></a></li>
<li><a href="https://win11.techidaily.com/1726030325875-pc/"><u>PCゲーム記録：シンプルな手法とコツをご紹介</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/perfecting-youtube-videos-with-angle-rotation-mastery-for-2024/"><u>Perfecting YouTube Videos with Angle Rotation Mastery for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/simple-tricks-capturing-and-downloading-your-favorite-instagram-live-sessions/"><u>Simple Tricks: Capturing and Downloading Your Favorite Instagram Live Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/top-lossless-audio-compression-tools-how-to-shrink-audio-file-size-without-losing-quality/"><u>Top Lossless Audio Compression Tools: How to Shrink Audio File Size Without Losing Quality</u></a></li>
<li><a href="https://win11.techidaily.com/transform-cloudy-with-a-chance-of-meatballs-2-into-a-lively-food-frenzy-saga/"><u>Transform Cloudy with a Chance of Meatballs 2 Into a Lively Food Frenzy Saga</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-editing-audio-files-in-windows-operating-systems-windows-11-10-81-and-earlier/"><u>Ultimate Guide: Editing Audio Files in Windows Operating Systems (Windows 11, 10, 8.1, and Earlier)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    