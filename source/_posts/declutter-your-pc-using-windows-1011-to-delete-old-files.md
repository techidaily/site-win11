---
title: "Declutter Your PC: Using Windows 10/11 to Delete Old Files"
date: 2024-10-14T20:54:05.653Z
updated: 2024-10-15T17:01:00.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Declutter Your PC: Using Windows 10/11 to Delete Old Files"
excerpt: "This Article Describes Declutter Your PC: Using Windows 10/11 to Delete Old Files"
keywords: Declutter PC,Remove Windows Files,Cleanup Windows 10,Clear Windows 11,Deleting Old Data,File Purge Guide,Streamline Disk Space
thumbnail: https://thmb.techidaily.com/7dc1f793da1f2b9c448c995323e3532e944d0308246b622538179ed42958d614.jpg
---

## Declutter Your PC: Using Windows 10/11 to Delete Old Files

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148640/16836" target="_top" id="2148640">
  <img src="//a.impactradius-go.com/display-ad/16836-2148640" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148640/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-timely-team-setups-adjusting-backdrop-beforeafter-calls/"><u>[Updated] 2024 Approved Timely Team Setups Adjusting Backdrop Before/After Calls</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-photo-editing-canvas-backdrop-eradication/"><u>Advanced Photo Editing Canvas Backdrop Eradication</u></a></li>
<li><a href="https://fox-http.techidaily.com/capturing-stardust-the-premier-10-sites-for-hdr-skyscapes/"><u>Capturing Stardust The Premier 10 Sites for HDR Skyscapes</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/consumer-groups-sue-t-mobile-for-misleading-price-protection-promise-a-closer-look-at-the-allegations/"><u>Consumer Groups Sue T-Mobile for Misleading Price Protection Promise: A Closer Look at the Allegations</u></a></li>
<li><a href="https://win11.techidaily.com/creating-unique-keys-for-winapps-and-tools/"><u>Creating Unique Keys for WinApps and Tools</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/enabling-auto-play-feature-for-your-image-flipbooks-with-flipbuilder-easy-integration/"><u>Enabling Auto-Play Feature for Your Image FlipBooks with FlipBuilder - Easy Integration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-error-code-0x0000004e-breakdown/"><u>Fixing Windows Error Code: 0X0000004E Breakdown</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-samsung-galaxy-xcover-7-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Samsung Galaxy XCover 7? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-passcodes-longer-windows-11-and-11-pins/"><u>Mastering Secure Passcodes: Longer Windows 11 and 11 PINs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-pace-boosting-windows-download-efficiency/"><u>Mastering Steam Pace: Boosting Windows Download Efficiency</u></a></li>
<li><a href="https://some-approaches.techidaily.com/melhores-softwares-e-aplicativos-para-modificar-vocalizacao-em-filmes-guia-detalhado-com-nota-classificada/"><u>Melhores Softwares E Aplicativos Para Modificar Vocalização Em Filmes - Guia Detalhado Com Nota Classificada</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-enhancing-listening-experience-steps-for-standardizing-audio-amplitude-in-vlc/"><u>New Enhancing Listening Experience Steps for Standardizing Audio Amplitude in VLC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-invalid-onedrive-tags/"><u>Overcoming the Challenge of Invalid OneDrive Tags</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-windows-still-requires-password-faults/"><u>Quick Fixes for “Windows Still Requires Password” Faults</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-regular-launch-procedure-in-outlook-despite-safe-mode-lockdown/"><u>Reactivating Regular Launch Procedure in Outlook Despite Safe Mode Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-adjacent-and-non-adjacent-windows-partition-merging/"><u>Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging</u></a></li>
<li><a href="https://buynow-info.techidaily.com/syma-x5c-rc-quadcopter-evaluation-exceptional-entry-level-performance-at-a-reasonable-price-point/"><u>SYMA X5C R/C Quadcopter Evaluation - Exceptional Entry-Level Performance at a Reasonable Price Point</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-combining-folders-and-files-in-win-11/"><u>The Essential Guide to Combining Folders & Files in Win 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Samsung Galaxy A24 | Dr.fone</u></a></li>
</ul></div>

