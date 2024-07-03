---
title: "Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse"
date: 2024-06-25T11:25:23.654Z
updated: 2024-06-26T11:25:23.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse"
excerpt: "This Article Describes Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse"
keywords: RecycleBinSelfClean,NeatWindowsRecycling,SelfCleansingBin,EfficientWasteManagement,CleanupSystemsAutomate,WasteBinMaintenance,AutomaticRecycleTidy
thumbnail: https://thmb.techidaily.com/98a12915cb3d2cb54c3468dae6fd64cafa98af7144806238fd48ac7236bdda16.jpg
---

## Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse

 We all know how easy it is to delete files and send them to the Recycle Bin. But wouldn't it be great if Windows automatically emptied the bin for us? Fortunately, you can configure your system to do just that.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

## 1\. How to Automate the Recycle Bin Using the System Settings

 It's easy to configure Windows to empty the recycle bin automatically. All you need to do is open System settings, fiddle with a few things, and you're done.

 However, this feature applies only to the current user account. Other users on the same computer won't have their Recycle Bin emptied automatically until they adjust this setting. In other words, if you're using a shared computer, it won't affect anyone else.

 Here's how to do it:

1. [Open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left panel, select the **System** tab.
3. Scroll down and click on **Storage** on the right-hand side. Here, you will find various computer data storage and management options.  
![Stoage in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stoage-in-system-settings.jpg)
4. Now, you will see a toggle switch under **Storage Sense**. If it's turned off, click to switch it on. This feature enables Windows to delete no longer needed files automatically.  
![Turn on Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/turn-on-storage-sense.jpg)
5. Once Storage Sense is active, click the tiny arrow next to it to expand the options.
6. On the next screen, you'll find an option that says, **Delete files in my recycle bin if they have been there for over**. Click the drop-down menu beside this and select the duration, after which Windows should empty the recycle bin automatically.
7. Select **1 day** if you want Windows to delete these items daily. Or choose another option that suits your needs better.  
![Configure Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/configure-storage-sense.jpg)
8. You can also configure the system to delete downloaded files that haven't been used for several days. To do so, click the **Delete files in my Downloaded folder if they haven't been opened for more than** drop-down menu and select the desired option.

 Once you're done, close the Settings window. Windows will automatically empty your Recycle Bin from now on.

## 2\. How to Automate the Recycle Bin Using the Task Scheduler

 If you want more control over the process, you can use Windows Task Scheduler to empty your Recycle Bin. Here's how:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **taskschd.msc** and hit **Enter** or click **OK**. Doing this [opens the Task Scheduler program](https://www.makeuseof.com/windows-11-open-task-scheduler/).
3. On the left-hand side of the window, select **Task Scheduler Library**.
4. Now, click **Create Basic Task** from the right-hand panel. It will open another window where you can configure your task settings.  
![Create Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-basic-task.jpg)
5. Enter a name for your task (e.g., Empty Recycle Bin) and a brief description if you want. Then, click the **Next** button.

1. The following window will ask you to select the frequency when Windows should empty your Recycle Bin. You can choose Daily, Weekly, Monthly, or One time only. Once you've chosen your preferred frequency, click **Next**.  
![Create a Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-a-basic-task.jpg)
2. After that, set the start date and time for your task. Also, select **Recur every** to specify the total duration of each cleaning session. Then, click **Next**.  
![Start Date and Time in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-date-and-time-in-task-wizard.jpg)
3. You must specify what action Windows should perform when this task runs. Click on the **Start a program** option and click **Next** again.  
![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  
/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.
6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

## Automate the Recycling Process on Windows

 To keep your computer running smoothly, you must empty your Recycle Bin regularly. However, the process can be tedious and time-consuming. Fortunately, Windows provides some easy ways to automate this task, either through Windows Settings or Task Scheduler.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-previewable-file-trouble-on-outlook-365-pc/"><u>Overcoming Non-Previewable File Trouble on Outlook 365 PC</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-clarity-manage-all-open-windows-win1110/"><u>From Chaos to Clarity: Manage All Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-contribution-to-linux-user-growth/"><u>WSL Contribution to Linux User Growth</u></a></li>
<li><a href="https://win11.techidaily.com/locating-group-policies-a-users-guide-for-win-users/"><u>Locating Group Policies: A User's Guide for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-attaching-notes-to-windows-apps/"><u>The Art of Attaching Notes to Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/directly-to-dialer-windows-11-tutorial/"><u>Directly to Dialer: Windows 11 Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-startup-options-your-ultimate-guidebook/"><u>Decoding Windows Startup Options: Your Ultimate Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-playback-in-reverse-the-ultimate-youtube-playlist-technique/"><u>2024 Approved  Playback in Reverse  The Ultimate YouTube Playlist Technique</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-captivate-audiences-perfecting-snapchats-boomerang-feature/"><u>[New] 2024 Approved  Captivate Audiences  Perfecting Snapchat's Boomerang Feature</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-samsung-galaxy-s24-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Samsung Galaxy S24 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/how-to-convert-your-social-media-presence-into-a-sustainable-business-model-for-2024/"><u>How to Convert Your Social Media Presence Into a Sustainable Business Model for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/content-cash-cow-how-much-does-the-meme-king-make-for-2024/"><u>Content Cash Cow  How Much Does the Meme King Make for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/efficiency-in-social-media-sharing-tweets-with-snapchat/"><u>Efficiency in Social Media  Sharing Tweets with Snapchat</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-comprehensive-list-of-top-screen-recording-tools/"><u>[Updated] The Comprehensive List of Top Screen Recording Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/voice-memo-grab-and-examine/"><u>Voice Memo Grab & Examine</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-professional-filmmaking-essentials-ideal-lenses-to-consider/"><u>[Updated] Professional Filmmaking Essentials  Ideal Lenses to Consider</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-where-to-buy-a-monetized-youtube-channel-a-complete-guide/"><u>2024 Approved  Where to Buy a Monetized YouTube Channel  A Complete Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>