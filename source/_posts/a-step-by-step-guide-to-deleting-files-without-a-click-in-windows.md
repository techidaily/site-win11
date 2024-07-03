---
title: A Step-by-Step Guide to Deleting Files Without a Click in Windows
date: 2024-07-02T13:06:45.874Z
updated: 2024-07-03T13:06:45.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to Deleting Files Without a Click in Windows
excerpt: This Article Describes A Step-by-Step Guide to Deleting Files Without a Click in Windows
keywords: DeleteFilesNoClick,WindowsFileDeletionGuide,EasyWinDeleteTutorial,FilesRemoveWithoutClick,SafeDeleteWindowsFiles,ClicklessFileRemoval,SecureWinDeletionMethod
thumbnail: https://thmb.techidaily.com/5c5beff306decd9e31c3216a57ffb320c5012e1719fd0426ca459ec8dc06e9a5.jpg
---

## A Step-by-Step Guide to Deleting Files Without a Click in Windows

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
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/directx-installation-guide-easy-downloads-and-updates/"><u>DirectX Installation Guide: Easy Downloads & Updates</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-error-0x80073d26/"><u>Unraveling the Mystery of Windows' Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/easy-auto-shutdown-techniques-for-idle-windows-pcs/"><u>Easy Auto-Shutdown Techniques for Idle Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-deleted-characters-a-guide-for-windows-users/"><u>Restoring Deleted Characters: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
<li><a href="https://win11.techidaily.com/1719361199591-navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80246007-in-windows-11s-update-process/"><u>Tackling Error 0X80246007 in Windows 11'S Update Process</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-selecting-the-best-youtube-to-mp4-converter-for-speed/"><u>In 2024, Selecting the Best YouTube to MP4 Converter for Speed</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-techniques-to-transform-your-footage-in-gopro-studio/"><u>2024 Approved  Innovative Techniques to Transform Your Footage in GoPro Studio</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-apple-id-from-iphone-7-without-password-by-drfone-ios/"><u>In 2024, How to Remove Apple ID from iPhone 7 without Password?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-here-are-the-top-five-online-stop-motion-makers-and-a-brief-tutorial-about-how-to-make-a-stop-motion-video-from-photos-and-videos-for-2024/"><u>Updated Here Are the Top Five Online Stop Motion Makers and a Brief Tutorial About How to Make a Stop Motion Video From Photos and Videos for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-transitions-fading-techniques-in-premiere-pro/"><u>Mastering Transitions  Fading Techniques in Premiere Pro</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-advanced-methods-for-effortless-recording-of-your-google-classes/"><u>[New] 2024 Approved  Advanced Methods for Effortless Recording of Your Google Classes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-the-explorers-blueprint-how-to-unearth-hidden-discord-communities/"><u>In 2024, The Explorer's Blueprint  How to Unearth Hidden Discord Communities</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-rated-online-video-reversal-services/"><u>New Top-Rated Online Video Reversal Services</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-asus-proart-pa-329q-in-focus-the-comprehensive-4k-professional-display-analysis/"><u>In 2024, Asus ProArt PA 329Q in Focus – The Comprehensive 4K Professional Display Analysis</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Vivo Y77t | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>