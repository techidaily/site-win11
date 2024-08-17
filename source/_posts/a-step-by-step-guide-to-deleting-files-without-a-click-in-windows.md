---
title: A Step-by-Step Guide to Deleting Files Without a Click in Windows
date: 2024-08-15T23:23:25.074Z
updated: 2024-08-16T23:23:25.074Z
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
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
2. After that, set the start date and time for your task. Also, select **Recur every** to specify the total duration of each cleaning session. Then, click **Next**.  
![Start Date and Time in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-date-and-time-in-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. You must specify what action Windows should perform when this task runs. Click on the **Start a program** option and click **Next** again.  
![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  
/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.
6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-elite-callers-on-windows-top-8-sorted/"><u>[New] In 2024, Elite Callers on Windows  Top 8 Sorted</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-clear-choice-between-projectors-and-televisions-for-4k-quality/"><u>[New] The Clear Choice Between Projectors and Televisions for 4K Quality</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-ultimate-ig-dashboard-unraveling-user-engagement-patterns/"><u>[New] The Ultimate IG Dashboard  Unraveling User Engagement Patterns</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-unlock-social-media-success-a-comprehensive-10-step-plan/"><u>[New] Unlock Social Media Success  A Comprehensive 10-Step Plan</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-a-compreehensive-look-at-itunes-video-capture/"><u>[Updated] A Compreehensive Look at iTunes Video Capture</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-launch-your-channel-8-entry-level-digital-course-series-for-2024/"><u>[Updated] Launch Your Channel  8 Entry-Level Digital Course Series for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/12-common-windows-11-aesthetic-oddities/"><u>12 Common Windows 11 Aesthetic Oddities</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-leap-into-adventure-mastering-the-realm-of-virtual-reality/"><u>2024 Approved  Leap Into Adventure  Mastering the Realm of Virtual Reality</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-strategic-sharing-of-tiktok-content-on-twitter/"><u>2024 Approved  Strategic Sharing of TikTok Content on Twitter</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-lava-blaze-2-pro-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Lava Blaze 2 Pro to Roku | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-11-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719366357478-6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-iscsi-initiator/"><u>A Comprehensive Look at Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-the-flow-of-tasks-with-fast-outlook/"><u>Accelerate the Flow of Tasks with Fast Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-restart-utilizing-windows-11s-quick-start-function/"><u>Accelerating System Restart: Utilizing Windows 11'S Quick Start Function</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-perfect-xbox-audio-with-windows-1011/"><u>Achieving Perfect Xbox Audio with Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/activation-verification-methods-for-windows-11/"><u>Activation Verification Methods for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adding-visual-disk-space-analyzer-to-windows-explorer-menu/"><u>Adding Visual Disk Space Analyzer to Windows Explorer Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-notaxc0f1103f-windows-errors/"><u>Addressing GeForce NotaXC0F1103F Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-store-glitch-code-0x80073cf3/"><u>Addressing Windows Store Glitch: Code 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-your-user-profiles-home-path-on-win11-os/"><u>Adjust Your User Profiles' Home Path on Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-key-differences-between-cloud-and-physical-windows-installations/"><u>Assessing Key Differences Between Cloud and Physical Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-oled-bape-edition-review-stealthy-stylish-and-practical/"><u>ASUS Vivobook S 15 OLED BAPE Edition Review: Stealthy, Stylish, and Practical</u></a></li>
<li><a href="https://win11.techidaily.com/augment-context-menu-with-higher-powers/"><u>Augment Context Menu with Higher Powers</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-defaults-20-ways-to-personalize-windows-11/"><u>Beyond Defaults: 20 Ways to Personalize Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/big-bulky-minipcs-with-brainy-bare-performance/"><u>Big, Bulky Minipcs with Brainy Bare Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-black-backdrops-on-windows/"><u>Breaking Free From Black Backdrops on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-video-files-on-realme-c33-2023-by-fonelab-android-recover-video/"><u>Complete guide for recovering video files on Realme C33 2023</u></a></li>
<li><a href="https://win11.techidaily.com/1719348593153-conquer-non-compatibilities-easy-steps-for-windows-xp-users/"><u>Conquer Non-Compatibilities: Easy Steps for Windows XP Users.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-operation-requirement-issues-on-windows-11-and-11/"><u>Demystifying Operation Requirement Issues on Windows 11 & 11</u></a></li>
<li><a href="https://tools.techidaily.com/wondershare/filmora/download/"><u>Filmora - AI Video Editing Software</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/l-content-makers-conference/"><u>Global Content Makers' Conference</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-realme-v30t-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Realme V30T Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-motorola-moto-g23-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Motorola Moto G23 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expedited-photographic-viewing-in-windows-10/"><u>In 2024, Expedited Photographic Viewing in Windows 10</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-meizu-21-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Meizu 21 to iPod | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-leading-marketplaces-for-bespoke-wrapping-marvels/"><u>In 2024, Leading Marketplaces for Bespoke Wrapping Marvels</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-mastering-twitter-uploading-videos-compliance/"><u>In 2024, Mastering Twitter  Uploading Videos Compliance</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-secrets-to-stunning-fisheye-sphere-photography/"><u>In 2024, Secrets to Stunning Fisheye Sphere Photography</u></a></li>
<li><a href="https://win11.techidaily.com/1719370883063-master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter.</u></a></li>
<li><a href="https://extra-skills.techidaily.com/selecting-the-superior-cloud-vaults-for-your-digital-needs-for-2024/"><u>Selecting the Superior Cloud Vaults for Your Digital Needs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://os-tips.techidaily.com/step-by-step-guide-to-mastering-iphones-dfu-mode-learn-entrance-and-exiting-techniques/"><u>Step-by-Step Guide to Mastering iPhone's DFU Mode - Learn Entrance and Exiting Techniques</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unlocking-the-potential-of-your-devices-tips-and-tricks-by-toms-team/"><u>Unlocking the Potential of Your Devices - Tips & Tricks by Tom's Team</u></a></li>
</ul></div>
