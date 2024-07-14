---
title: Revolutionize File Management with Windows' Automatic Deletion
date: 2024-07-13T10:34:23.600Z
updated: 2024-07-14T10:34:23.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revolutionize File Management with Windows' Automatic Deletion
excerpt: This Article Describes Revolutionize File Management with Windows' Automatic Deletion
keywords: Auto Delete Files,Windows File Management,Revolutionize File Handling,Streamlined File Erasure,Efficient File System,Quick File Cleanup,Secure Windows Deletion
thumbnail: https://thmb.techidaily.com/a770835b076eb6b9f15ef9eaa24a0d7865dfb16a5caaa3e52196c91037b09546.jpg
---

## Revolutionize File Management with Windows' Automatic Deletion

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/bridging-computers-efficient-filesharing-through-python-on-windows/"><u>Bridging Computers: Efficient Filesharing Through Python on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-explore-tab-glitches-in-modern-os/"><u>Disabling Explore Tab Glitches in Modern OS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-guide-to-getting-1000-subscribers-for-your-youtube-channel/"><u>2024 Approved  Guide to Getting 1000 Subscribers for Your YouTube Channel</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-precise-video-queue-a-step-by-step-guide-to-creating-an-effective-playlist-on-youtube/"><u>2024 Approved  Precise Video Queue  A Step-by-Step Guide to Creating an Effective Playlist on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/1719354508470-fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools.</u></a></li>
<li><a href="https://win11.techidaily.com/clear-communication-how-to-test-microphone-on-windows-pre-call/"><u>Clear Communication: How to Test Microphone on Windows Pre-Call</u></a></li>
<li><a href="https://win11.techidaily.com/three-simplified-steps-for-customizing-win11-ui/"><u>Three Simplified Steps for Customizing Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-cheap-traps-the-realities-of-inferior-windows-activation-codes/"><u>Avoid Cheap Traps: The Realities of Inferior Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-data-metering-settings-for-wi-fi-in-windows-11/"><u>Configuring Data Metering Settings for Wi-Fi in Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-navigating-the-world-of-vr-playback-technology/"><u>[Updated] 2024 Approved  Navigating the World of VR Playback Technology</u></a></li>
<li><a href="https://win11.techidaily.com/14-unveiling-windows-11-post-update-feature-list/"><u>14 Unveiling Windows 11: Post-Update Feature List</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-vds-failures-head-on/"><u>Tackling Windows VDS Failures Head-On</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-n-a-comparative-study-for-it-pros/"><u>Unveiling Windows N: A Comparative Study for IT Pros</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-yourself-for-youtube-video-production-finalcut-pro-techniques/"><u>Ready Yourself for YouTube Video Production - FinalCut Pro Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-no-connection-found-error-in-win/"><u>Steps to Solve No Connection Found Error in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-photo-management-winning-windows-applications/"><u>Efficient Photo Management: Winning Windows Applications</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-launching-into-content-creation-account-setup-on-youtube/"><u>[Updated] In 2024, Launching Into Content Creation  Account Setup on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-gaming-power-drain-from-wm/"><u>Cutting Down Gaming Power Drain From WM</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-idle-screen-time-on-windows/"><u>Configuring Idle Screen Time on Windows</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-xiaomi-14-pro-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Xiaomi 14 Pro.</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-for-fast-utorrent-downloads-on-windows/"><u>Expert Techniques for Fast uTorrent Downloads on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-alter-mouse-trail-and-size-on-win11/"><u>Step-by-Step: Alter Mouse Trail & Size on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/esd-files-demystified-creating-iso-versions-for-windows-systems/"><u>ESD Files Demystified: Creating ISO Versions for Windows Systems</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/astering-video-production-essential-lessons-for-beginners/"><u>[New] Mastering Video Production  Essential Lessons for Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-techniques-pin-free-windows-projecting/"><u>Cutting Edge Techniques: PIN-Free Windows Projecting</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-mastery-over-buffering-in-vimeo-streams-revised-tips/"><u>[New] Mastery Over Buffering in Vimeo Streams (Revised Tips)</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-add-cinematic-flair-to-your-videos-free-slow-motion-editing-with-filmora/"><u>In 2024, Add Cinematic Flair to Your Videos Free Slow Motion Editing with Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-zoom-obstacles-stop-code-1132-issues/"><u>Avoid Windows Zoom Obstacles: Stop Code 1132 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-dxgierror-post-device-disconnect/"><u>Avoidance of DXGI_Error Post Device Disconnect</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-zte-nubia-flip-5g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked ZTE Nubia Flip 5G Phone?</u></a></li>
<li><a href="https://win11.techidaily.com/essential-knowledge-setting-windows-filter-keys/"><u>Essential Knowledge: Setting Windows Filter Keys</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-turn-your-videos-into-a-revenue-stream-with-these-tips/"><u>[New] In 2024, Turn Your Videos Into a Revenue Stream with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/clashing-cybersecurity-the-case-against-multiple-antiviruses-on-windows/"><u>Clashing Cybersecurity: The Case Against Multiple Antiviruses on Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-top-video-rotator-tools-for-online-use-for-2024/"><u>Updated Top Video Rotator Tools for Online Use for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-easy-way-to-mix-and-match-youtube-playlist-order/"><u>[New] 2024 Approved  The Easy Way to Mix and Match YouTube Playlist Order</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-sound-in-obs-studio-resolving-no-audio-on-win-11/"><u>Amplify Sound in OBS Studio - Resolving No Audio on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-pc-mysteries-a-step-by-step-guide-to-error-code-management-in-command-prompt/"><u>Unraveling PC Mysteries: A Step-by-Step Guide to Error Code Management in Command Prompt</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-honor-x50-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Honor X50 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rejuvenating-stuck-windows-based-itunes/"><u>Strategies for Rejuvenating Stuck Windows-Based iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/compre-written-for-pc-performance-metrics/"><u>Compre Written for PC Performance Metrics</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-oneplus-nord-n30-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our OnePlus Nord N30 5G Phone Screen?</u></a></li>
</ul></div>
