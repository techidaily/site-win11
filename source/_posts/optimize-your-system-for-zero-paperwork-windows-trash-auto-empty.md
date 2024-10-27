---
title: Optimize Your System for Zero Paperwork - Windows Trash Auto-Empty
date: 2024-10-21T23:34:47.268Z
updated: 2024-10-26T16:23:00.299Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimize Your System for Zero Paperwork - Windows Trash Auto-Empty
excerpt: This Article Describes Optimize Your System for Zero Paperwork - Windows Trash Auto-Empty
keywords: No Paperwork PC,Zero Paperwork Windows,Easy Trash Management,Automafe Filing,Quick System Cleanup,Auto-Empty Trash,Streamlined Windows Use
thumbnail: https://thmb.techidaily.com/00d8a989d7a324ab139f90cea816e72b6f2451ab8e331cf2285ff4f2ecbceec0.jpg
---

## Optimize Your System for Zero Paperwork - Windows Trash Auto-Empty

 We all know how easy it is to delete files and send them to the Recycle Bin. But wouldn't it be great if Windows automatically emptied the bin for us? Fortunately, you can configure your system to do just that.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902289/19272" target="_top" id="1902289">
  <img src="//a.impactradius-go.com/display-ad/19272-1902289" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902289/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148640/16836" target="_top" id="2148640">
  <img src="//a.impactradius-go.com/display-ad/16836-2148640" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148640/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

## Automate the Recycling Process on Windows

 To keep your computer running smoothly, you must empty your Recycle Bin regularly. However, the process can be tedious and time-consuming. Fortunately, Windows provides some easy ways to automate this task, either through Windows Settings or Task Scheduler.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-enhance-media-creation-the-ultimate-list-of-top-8-montage-apps/"><u>[New] 2024 Approved Enhance Media Creation The Ultimate List of Top 8 Montage Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-efficient-tactics-for-viewing-subscribers-on-yt-for-2024/"><u>[New] Efficient Tactics for Viewing Subscribers on YT for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-elevate-your-videos-prime-triad-of-transcoding-ways-for-2024/"><u>[New] Elevate Your Videos Prime Triad of Transcoding Ways for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-to-share-screen-on-facebook-live-for-2024/"><u>[New] How to Share Screen on Facebook Live for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-a-guide-to-pinpointing-posted-videos-in-fb-groups/"><u>[Updated] In 2024, A Guide to Pinpointing Posted Videos in FB Groups</u></a></li>
<li><a href="https://extra-resources.techidaily.com/archival-artwork-creative-commons-haven/"><u>Archival Artwork Creative Commons Haven</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-make-purchases-on-iphone-se-2022-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID make purchases on iPhone SE (2022) ?</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-harnessing-windows-11-for-high-impact-visually-striking-videos/"><u>In 2024, Harnessing Windows 11 for High-Impact, Visually Striking Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-asus-rog-phone-7s-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Asus ROG Phone 7s Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-program-window-settings-in-windows-11/"><u>Mastering Program Window Settings in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondly-transforms-education-landscape-connecting-70plus-million-people/"><u>Mondly Transforms Education Landscape, Connecting 70+ Million People</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-open-system-configuration/"><u>Simple Steps to Open System Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-google-play-in-w11/"><u>Step-by-Step Guide to Google Play in W11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-mass-folder-creation-made-simple-for-windows-users/"><u>Step-by-Step Guide: Mass Folder Creation Made Simple for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-android-resources-within-the-windows-subsystem/"><u>Streamlining Android Resources Within the Windows Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-removing-discord-from-pc-boot-sequence/"><u>Tips for Removing Discord From PC Boot Sequence</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-11s-new-look-return-to-icons-only/"><u>Transforming Windows 11'S New Look: Return to Icons Only</u></a></li>
<li><a href="https://win11.techidaily.com/win1011s-hidden-treasures-unlocked-bring-panels-into-view/"><u>Win10/11's Hidden Treasures Unlocked: Bring Panels Into View</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-paves-way-for-pristine-ad-less-start/"><u>Windows 11 Paves Way for Pristine, Ad-Less Start</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    