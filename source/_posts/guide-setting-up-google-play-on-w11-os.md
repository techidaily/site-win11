---
title: "Guide: Setting Up Google Play on W11 OS"
date: 2024-07-13T10:38:17.612Z
updated: 2024-07-14T10:38:17.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Setting Up Google Play on W11 OS"
excerpt: "This Article Describes Guide: Setting Up Google Play on W11 OS"
keywords: W11 Setup Guide,Google Play Installation,W11 OS Play Store,Play Services Setup,Android W11 Update,Setting Up PlayStore,W11 Play Setup Tips
thumbnail: https://thmb.techidaily.com/33c48593ec0173b68a8667f248e53142d39bc8c3611fadd3a7f85564f8ade76e.jpg
---

## Guide: Setting Up Google Play on W11 OS

 You can natively run Android apps on Windows 11 via Windows Subsystem for Android (WSA); however, it has its limitations. The new OS only natively supports Amazon’s Appstore and not Google Play Store. And while sideloading Android apps is an option, anything that requires Google Play Services will not work.

 However, you can install Google Play Store on Windows 11 to overcome this limitation. Here we show you how.

## How to Install Google Play Store on Windows 11

 As discussed earlier, you can [sideload and run Android apps on Windows 11](https://www.makeuseof.com/windows-11-sideload-android-apps/) . However, finding APKs and installing them via the Command Prompt is cumbersome. You also need to configure Android Debug Bridge (ADB) to install Android apps.

 You can install a fully functional Google Play Store to remedy this problem. Also, this allows you to run Google Play Services-dependent apps.

 However, it is a complicated process and involves downloading several small packages and then moving them around. Fortunately, a developer (Yujinchang08) on GitHub has simplified this process with a custom WSA installer.

 The WSA installer consists of a modified WSA package with Magisk and Open GApps integration. Magisk is a root access utility wherein Open GApps offers up-to-date Google Apps packages.

 For this guide, we will focus on the second method to install Google Play Store on Windows 11\. So, let’s begin.

 Note that this process requires installing third-party modified files and packages and involves potential risks. Before proceeding,[create a restore point in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) or [recovery drive](http://www.makeuseof.com/create-recovery-drive-system-repair-disc-windows-10/) . These recovery options can help you undo the changes or repair the system if something goes wrong.

## Step 1: Uninstall Android Subsystem for Android

![uninstall windows subsystem for android](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/uninstall-windows-subsystem-for-android.png)

 If you have Windows Subsystem for Android installed, you can uninstall it from the Apps & features section.

To uninstall WSA:

1. Press**Win + I** to open the**Settings** panel.
2. Open the**Apps** tab in the left pane.
3. Next, click on**Apps & Features.**
4. Locate and click on**Windows Subsystem for Android** under**App list** .
5. Click the**three dots** and select**Uninstall** . Click**Uninstall** again to confirm the action.

## Step 2: Enable Developer Mode in Windows 11

![enable-developer-mode-windows-11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-developer-mode-windows-11.png)

 Developer Mode allows you to sideload apps and access other developer features, including remote installation apps via SSH services.

To enable Developer Mode:

1. Press**Win + I** to open the**Settings** app.
2. Open the**Privacy and Security** tab in the left pane.
3. In the right pane, click on**For Developers.**
4. Toggle the switch for**Developer Mode** and set it to**On** . Click**Yes** to confirm the action.

## Step 3: Enable Virtual Machine to Run Android Apps

![enable windows hypervisor platform windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-windows-hypervisor-platform-windows-11.png)

 You need to [enable and configure Virtual Machine Platform and Windows Hypervisor Platform](https://www.makeuseof.com/windows-11-enable-hyper-v/) to run Windows Subsystem for Android on Windows 11\. Skip this step if you have installed WSA previously.

To configure the Virtual Machine:

1. Press**Win + S** to open the**search bar** .
2. Type**Windows Features** and then click on**Turn Windows features on or off** from the search results.
3. In the Windows Features window, select**Virtual Machine Platform** and**Windows Hypervisor Platform.**
4. Click**OK** to save the changes and Windows will install the selected features. Restart your PC to apply the changes.

If successful, you will see an update status message during restart.

## Step 4: Setup and Install Windows Subsystem for Linux and Linux Distro on Windows 11

 To install Google Play Store on Windows 11, you’ll need to build a locally modified Windows Subsystem for Android. For this, you’ll need to install Windows Subsystem for Linux (WSL) and a Linux distro. This is necessary as you’ll need to run some commands to build Windows Subsystem for Android.

To install WSL and a Linux distro on Windows 11:

1. Launch Microsoft Store.
2. In Microsoft Store, search for**Windows Subsystem for Linux (WSL)** and install the app. Wait for the app to install.  
![windows subsystem for linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-linus-1.jpg)
3. Next, search for a Linux distro. We’ll use Ubuntu. So, search for**Ubuntu** and install the distro. If you have a Linux distro installed, you can skip to the next step  
![Ubuntu distro windows 11 install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/ubuntu-distro-windows-11-install-1.jpg)
4. Once installed, press the**Win** key and type**Ubuntu** . Right-click on**Ubuntu** and select**Run as administrator** .
5. In the Ubuntu terminal, you’ll need to create a user with a password for the Linux system. So, create a username and password. Leave the Ubuntu terminal open.

 Now you’ll see a Linux\\Ubuntu folder in File Explorer’s left pane.

## Step 5: Setup Magisk and Windows Subsystem for Android

 The next set of steps involve downloading a Gitbub repository, MagiskOnWSALocal, to integrate Magisk root and Google Apps into WSA.

1. Go to the [MagiskOnWSALocal page](https://github.com/LSPosed/MagiskOnWSALocal) on GitHub.
2. Click the**Code** drop-down in the top right corner.  
![copy github url magiskonwsa](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/copy-github-url-magiskonwsa.jpg)
3. Copy the**GitHub URL** under the**HTTPS** tab.  
![download install magiskonWSA github command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-install-magiskonwsa-github-command-prompt.jpg)
4. Open the Ubuntu terminal and type the following command followed by the GitHub URL:  
`git clone https://github.com/LSPosed/MagiskOnWSALocal.git`
5. Press**Enter** to close the GitHub repository to the Linux user account on your computer.  
![run script magiskonwsa local install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-script-magiskonwsa-local-install.jpg)
6. Next, type the following command to move to the scripts folder. This will change the directory to the specified folder.  
`cd MagiskOnWSALocal  
cd scripts`
7. Next, type the following command to run the script and download the necessary files to install all the necessary files for Magisk, Play Store, and Windows Subsystem for Android:  
`./run.sh`
8. Depending on your Internet speed, downloading may take some time. So, wait till the process is complete.
9. As the process completes, you’ll see a command line installer open up.

## Step 6: Install Google Play Store on Windows 11

1. Next, in the**Into to MagiskOnWSA** dialog, select**OK** .  
![intro to magiskonWSA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/intro-to-magiskonwsa.jpg)
2. Next, select**X64 X86\_64** for**Build Arch** .  
![build arch masigkonwsa local](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/build-arch-masigkonwsa-local.jpg)
3. Next, for**WSA release** type, select**Retail Stable Channel** .  
![WSA retail type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-retail-type.jpg)
4. Select**No** in the**Do you want to** **Root WSA dialog** .
5. Select**Yes** in the**Do you want to install GApps** dialog.  
![which GApps you want to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/which-gapps-you-want-to-install.jpg)
6. Select**OpenGApps** in the**Which GApps do you want to install** dialog.
7. Next, in the**Do you want to keep Amazon Appstore** dialog, select**Yes** or**No** , depending on your requirement.
8. Select**No** in the**Do you want to compress the output** dialog.
9. MagiskOnWSALocal will start generating custom Windows subsystem for the Android image.

 This process may take some time to complete. So, wait for the process to complete.

## Step 7: Install Windows Subsystem for Android

 Once done, you’ll need to install WSA on Windows 11\. To install WSA, you’ll need to copy the contents of the MagiskonWSALocal folder, which contains the image file, to your installation drive and then execute a command.

 To install WSA, you need to enable Developer Mode on Windows 11\. Once enabled, follow the below steps to install WSA.

To install WSA on Windows 11:

1. Open**File Explorer** and go to the**Linux\\Ubuntu** tab.
2. Next, depending on where you had installed**MagiskOnWSA** , go to:  
`\home\username\MagiskOnWSALocal\Output  
or  
\root\MagiskOnWSALocal\output`
3. Next, open the **WSA\_2302.40000.9.0\_x64\_Release-Nightly-MindTheGapps-13.0-RemovedAmazon** folder.  
![magiskonwsalocal copy folders files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/magiskonwsalocal-copy-folders-files.jpg)
4. Copy all the files and folders inside the**WSA** folder.
5. Next, go to your installation drive**C:\\** and create a new folder named**WSA** .  
![WSA folder Windows C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-folder-windows-c-drive.jpg)

1. Paste the copied files into the**WSA** folder.
2. Close**File Explorer** .
3. Press the**Win** key and type**cmd** . Right-click on**Command Prompt** and select**Run as administrator** .  
![install Windows subsystem for Android windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-windows-subsystem-for-android-windows-11.jpg)
4. In the Command Prompt window, type the following command to change the directory to the WSA folder:  
`cd C:\WSA`
5. Next, run the following command to execute the following command to install the WSA package:  
`PowerShell.exe -ExecutionPolicy Bypass -File .\Install.ps1`
6. The script will install the modified Windows subsystem for Android with**Play Store** support. Wait for the installation to complete and ignore any errors in the PowerShell console.
7. Once done, you’ll see the**Magisk** and**Play Store** windows. However, you’ll need to enable**Developer mode** on Windows Subsystem for Android to use Play Store.

To enable Developer mode on Windows Subsystem for Android:

![Windows subsystem for android enable developer mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-android-enable-developer-mode.jpg)

1. Press the**Win** key, type**Windows Subsystem for Android** , and open the app from the search results.
2. Next, open the**Developer** tab in the left pane.
3. Toggle the**Developer mode** switch to turn it**On** .
4. Next, open the**Play Store App** and sign in with your Google account. You may need to authenticate and sign in on your Android device.

 After signing in, you can download and install all the Play Store apps just like on an Android phone. Also, you can open the installed apps from the Start menu, Windows search, and apps list.

 Now you can install Android apps on Windows 11 from Google Play Store. That said, some apps may still not work properly due to the region and licensing restrictions.

## Installing the Google Play Store on Windows 11

 Being able to run Android apps natively on Windows 11 removes the hassle of Android emulators. Now with the Play Store support, you can install most if not all the Android apps without sideloading.

 That said, for the apps that are not available in Play Store, you can sideload them on your Windows 11 PC using Command Prompt or the WSA Tool.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/updated-complete-guide-to-slow-down-a-video-on-snapchat-for-2024/"><u>[Updated] Complete Guide to Slow Down a Video on Snapchat for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/choosing-the-right-screen-recorder-outside-of-xbox/"><u>Choosing the Right Screen Recorder, Outside of Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-photos-app-background-blur-feature-on-windows-11/"><u>How to Use the Photos App Background Blur Feature on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/is-it-necessary-to-keep-pagefilesys-reasons-explored/"><u>Is It Necessary to Keep Pagefile.sys? Reasons Explored</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-comic-experience-with-windows-11-techniques/"><u>Maximizing Comic Experience with Windows 11 Techniques</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-video-trimming-made-easy-top-10-pc-and-online-tools/"><u>New 2024 Approved Video Trimming Made Easy Top 10 PC and Online Tools</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-9-methods-for-accessing-windows-11s-audio-control-panel/"><u>Navigate 9 Methods for Accessing Windows 11'S Audio Control Panel</u></a></li>
<li><a href="https://youtube-help.techidaily.com/gamified-learning-educational-youtubers-to-subscribe-for-2024/"><u>Gamified Learning  Educational YouTubers to Subscribe for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-next-big-thing-top-27-alternatives-to-youtube-revealed/"><u>In 2024, The Next Big Thing  Top 27 Alternatives to YouTube Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-bypassing-non-active-window-firewall/"><u>Methods for Bypassing Non-Active Window Firewall</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-apple-iphone-12-mini-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>In 2024, Unlock Your Apple iPhone 12 mini in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-high-space-consumers-on-your-windows-machine/"><u>Identifying High-Space Consumers on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-mass-unzipping-on-your-pc/"><u>Navigating the Maze of Mass Unzipping on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/immersive-education-experience-windows-11-tutorials/"><u>Immersive Education Experience: Windows 11 Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/new-wave-windows-leap-from-the-legacy-of-11/"><u>New Wave Windows: Leap From the Legacy of 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-portable-network-capabilities-via-windows-11-pc/"><u>Activating Portable Network Capabilities via Windows 11 PC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-ultimate-list-of-webinar-software/"><u>[Updated] Ultimate List of Webinar Software</u></a></li>
<li><a href="https://article-files.techidaily.com/top-picks-for-the-best-android-image-correction-tools-5-choices/"><u>Top Picks for the Best Android Image Correction Tools (5 Choices)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-boost-clicks-and-conversions-the-top-15-powerful-tools-for-fb-data-analysis/"><u>[Updated] In 2024, Boost Clicks & Conversions  The Top 15 Powerful Tools for FB Data Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-for-reviving-freeze-ups-on-resource-monitor-win11/"><u>Immediate Actions for Reviving Freeze-Ups on Resource Monitor, Win11</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-no-cost-all-benefits-with-fcp-downloads/"><u>2024 Approved  No Cost, All Benefits with FCP Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/masked-commands-the-win-1011-trickery-guide/"><u>Masked Commands: The Win 10/11 Trickery Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-office-setup-on-windows-10-and-11-systems/"><u>Mastering Office Setup on WIndows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-a-guide-to-mastering-window-11s-taskbar-search-function/"><u>Quick Start: A Guide to Mastering Window 11’S Taskbar Search Function</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-traditional-windows-explorer-look/"><u>Reclaiming Traditional Windows Explorer Look</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-new-to-telegram-heres-your-guide-to-getting-started-with-marketing/"><u>[New] 2024 Approved  New to Telegram? Here's Your Guide to Getting Started with Marketing</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ical-integration-on-windows-11-systems/"><u>Mastering iCal Integration on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/realign-google-chrome-clock-with-windows-time/"><u>Realign Google Chrome Clock with Windows Time</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-pc-with-the-top-10-must-try-powertoy-applications/"><u>Reimagine Your PC with the Top 10 Must-Try PowerToy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-windows-default-settings-on-reboot/"><u>Quick Tips for Windows Default Settings on Reboot</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-audio-wizards-handbook-navigating-complex-editing-tasks-with-sony-vegas-pro-for-2024/"><u>The Audio Wizards Handbook Navigating Complex Editing Tasks with Sony Vegas Pro for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-ultimate-guide-to-choosing-top-audio-reversing-applications-for-your-pc-phone-and-tablet-for-2024/"><u>The Ultimate Guide to Choosing Top Audio Reversing Applications For Your PC, Phone, and Tablet for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-lgs-cutting-edge-monitor-technology-in-detail-for-2024/"><u>Unveiling LG’s Cutting-Edge Monitor Technology in Detail for 2024</u></a></li>
</ul></div>
