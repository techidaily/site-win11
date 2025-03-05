---
title: Automatic Empty Recycle Bin in Windows Step by Step
date: 2025-02-25T16:59:18.373Z
updated: 2025-03-05T03:54:03.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Automatic Empty Recycle Bin in Windows Step by Step
excerpt: This Article Describes Automatic Empty Recycle Bin in Windows Step by Step
keywords: Automate Bin Clearing,Quick Recycle Deletion,Windows Bin Emptiness,Refill Bin Easily,Delete Trash Simplicity,Windows Recycle Auto-Clear,Instant Trash Removal Guide
thumbnail: https://thmb.techidaily.com/4bdb303f42b83bdabbc89bbaed552a530d980933768bd910a7c15106cfbf73fe.png
---

## Automatic Empty Recycle Bin in Windows Step by Step

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-premium-picks-the-ultimate-gopro-upgrades/"><u>[New] Premium Picks The Ultimate Gopro Upgrades</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-engaging-local-audiences-with-social-media-videos/"><u>[Updated] Engaging Local Audiences with Social Media Videos</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-juggling-jargons-an-experts-guide-to-multiple-youtube-views/"><u>[Updated] Juggling Jargons An Expert's Guide to Multiple YouTube Views</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-of-the-best-trivia-channels/"><u>2024 Approved Best of the Best Trivia Channels</u></a></li>
<li><a href="https://discord-videos.techidaily.com/elevate-your-streams-step-by-step-discord-tips-for-2024/"><u>Elevate Your Streams Step-by-Step Discord Tips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fix-a-frozen-opera-installer-in-windows-environment/"><u>Fix a Frozen Opera Installer in Windows Environment</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Infinix Smart 8 HD? | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-effective-timestamp-integration-in-image-files/"><u>In 2024, Effective Timestamp Integration in Image Files</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-windows-pin-update-techniques/"><u>Mastery over Windows PIN Update Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/obs-studio-troubleshooting-muted-sound-recording-in-windows-11/"><u>OBS Studio: Troubleshooting Muted Sound Recording in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-wi-fi-connections-metric-functionality/"><u>Optimizing Your Wi-Fi Connection's Metric Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-3d-painting-crucial-shortcuts/"><u>Speed Up 3D Painting: Crucial Shortcuts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-multi-drop-pinning-in-google-maps/"><u>Step-by-Step Tutorial: Multi-Drop Pinning in Google Maps</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-secrets-of-disarming-windows-11-alert-messages/"><u>Unlock Secrets of Disarming Windows 11 Alert Messages</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-non-initialized-disks-on-windows/"><u>Unraveling the Mystery of Non-Initialized Disks on Windows</u></a></li>
</ul></div>

