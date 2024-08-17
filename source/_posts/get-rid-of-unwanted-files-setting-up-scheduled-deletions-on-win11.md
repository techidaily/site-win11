---
title: "Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11"
date: 2024-08-16T00:39:38.050Z
updated: 2024-08-17T00:39:38.050Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11"
excerpt: "This Article Describes Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11"
keywords: Win11 File Cleanup,Daily Delete Schedule,Remove Junk Files Win,Automated File Deletion,Windows 11 Cleanup Tool,Unwanted Files Removal,Weekly File Purge (Win11)
thumbnail: https://thmb.techidaily.com/ef756af67baaa63e6513047560b51e7a06317e95c3578e612a362286e500591b.jpg
---

## Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-discover-the-best-premiere-pro-templates-free-2023/"><u>[New] 2024 Approved  Discover the Best Premiere Pro Templates (FREE) 2023</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-a-critical-review-of-top-no-cost-video-communication-apps-iosandroid-for-2024/"><u>[New] A Critical Review of Top No-Cost Video Communication Apps (iOS/Android) for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-streamline-your-gameplay-win10-screen-record-tech/"><u>[New] In 2024, Streamline Your Gameplay  Win10 Screen Record Tech</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-speed-up-sound-on-smartphones-with-these/"><u>[New] Speed Up Sound on Smartphones with These</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-essential-manual-to-measure-youtube-success-metrics/"><u>[New] The Essential Manual to Measure YouTube Success Metrics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unlocking-srt-potential-mac-edition-tutorial/"><u>[Updated] 2024 Approved  Unlocking SRT Potential  Mac Edition Tutorial</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-prime-video-hits-on-twitter-the-most-popular-watches-of-23-for-2024/"><u>[Updated] Prime Video Hits on Twitter  The Most Popular Watches of '23 for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/altered-captions-a-video-guide/"><u>Altered Captions  A Video Guide</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-honor-magic-6-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Honor Magic 6 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/curing-a-non-operational-windows-control-panel/"><u>Curing a Non-Operational Windows Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-overlooked-windows-extras-a-step-by-step-manual/"><u>Enabling Overlooked Windows Extras: A Step-by-Step Manual</u></a></li>
<li><a href="https://win11.techidaily.com/expert-windows-11-weather-app-reviews/"><u>Expert Windows 11 Weather App Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/explore-5-innovative-windows-folder-strategies/"><u>Explore 5 Innovative Windows Folder Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-modules-installer-workers-high-cpu-usage/"><u>How to Fix the Windows Modules Installer Worker's High CPU Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-a-keyboard-that-wont-respond-on-your-windows-machine-solutions-inside/"><u>How to Resolve a Keyboard That Won't Respond on Your Windows Machine - Solutions Inside</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-to-other-iphone-11-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 to other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-thumbnails-for-maximum-clicks-for-2024/"><u>Ideal Thumbnails for Maximum Clicks for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-nokia-g22-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Nokia G22 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-oculus-game-collection-top-8-popular-picks/"><u>In 2024, Oculus Game Collection  Top 8 Popular Picks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-step-by-step-ppt-and-vo-integration-tutorial/"><u>In 2024, Step-by-Step PPT & VO Integration Tutorial</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/infusing-life-into-ppt-with-professional-voiceovers-for-2024/"><u>Infusing Life Into PPT with Professional Voiceovers for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovation-in-iphone-filmmaking-virtual-worlds-for-2024/"><u>Innovation in iPhone Filmmaking  Virtual Worlds for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/investing-successfully-with-a-makeup-channel-for-2024/"><u>Investing Successfully with a Makeup Channel for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-archiving-concealing-data-within-images-windows-11/"><u>Invisible Archiving: Concealing Data Within Images (Windows 11)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-there-trouble-in-steering-control-of-chatgpt-for-openai/"><u>Is There Trouble in Steering Control of ChatGPT for OpenAI?</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-system-safe-spotting-hidden-threats-in-windows/"><u>Keep Your System Safe: Spotting Hidden Threats in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-powertoys-reset-on-new-machine/"><u>Navigating PowerToys: Reset on New Machine</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-missing-file-updates-error-on-windows-error-code-0x80070003/"><u>Navigating Through Missing File Updates Error on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-excessive-use-of-windows-module-installer/"><u>Overcoming Excessive Use of Windows Module Installer</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-driver-loading-issues-in-the-latest-os/"><u>Overcoming Failed Driver Loading Issues in the Latest OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/premier-fb-viewing-sites-ranked-1-10-for-2024/"><u>Premier FB Viewing Sites Ranked #1-10 for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/prime-software-solutions-for-video-games/"><u>Prime Software Solutions for Video Games</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-onedrive-error-adding-folder-not-possible-immediately/"><u>Resolving OneDrive Error - Adding Folder Not Possible Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/setting-specific-windows-lockdown-period/"><u>Setting Specific Windows Lockdown Period</u></a></li>
<li><a href="https://win11.techidaily.com/solving-common-closed-captions-issues-in-win11/"><u>Solving Common Closed Captions Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-window-task-completion-via-key-combinations/"><u>Speedy Window Task Completion via Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-windows-error-0xc1900101/"><u>Strategies for Correcting Windows Error 0xC1900101</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-immediate-failure-how-to-successfully-add-a-folder-in-onedrive-on-pc/"><u>Tackling Immediate Failure: How to Successfully Add a Folder in OneDrive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-operation-failed-error-code-0x0000011b/"><u>Tackling Operation Failed Error: Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/unite-with-your-absent-astra-pilot-on-windows-11/"><u>Unite With Your Absent Astra Pilot On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-status-check-top-three-techniques/"><u>Windows 11 Status Check: Top Three Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-a-journey-with-the-taskbar-through-time/"><u>Windows UI: A Journey with the Taskbar Through Time</u></a></li>
</ul></div>
