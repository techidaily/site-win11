---
title: Installation Manual for Google Play on W11
date: 2024-12-03T23:32:30.773Z
updated: 2024-12-07T09:06:07.076Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Installation Manual for Google Play on W11
excerpt: This Article Describes Installation Manual for Google Play on W11
keywords: Google Play Install Guide,Android W11 Setup Guide,Play Store W11 Install,Setting up Google Apps,W11 Google Play Guide,Android OS Play Setup,Installer for Play Services
thumbnail: https://thmb.techidaily.com/72ca63d6325a67d4b7a844299776fc3c0b1aca6440d5ca1111f8174af4b16af4.jpg
---

## Installation Manual for Google Play on W11

 You can natively run Android apps on Windows 11 via Windows Subsystem for Android (WSA); however, it has its limitations. The new OS only natively supports Amazon’s Appstore and not Google Play Store. And while sideloading Android apps is an option, anything that requires Google Play Services will not work.

 However, you can install Google Play Store on Windows 11 to overcome this limitation. Here we show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Install Google Play Store on Windows 11

 As discussed earlier, you can[sideload and run Android apps on Windows 11](https://www.makeuseof.com/windows-11-sideload-android-apps/) . However, finding APKs and installing them via the Command Prompt is cumbersome. You also need to configure Android Debug Bridge (ADB) to install Android apps.

 You can install a fully functional Google Play Store to remedy this problem. Also, this allows you to run Google Play Services-dependent apps.

 However, it is a complicated process and involves downloading several small packages and then moving them around. Fortunately, a developer (Yujinchang08) on GitHub has simplified this process with a custom WSA installer.

 The WSA installer consists of a modified WSA package with Magisk and Open GApps integration. Magisk is a root access utility wherein Open GApps offers up-to-date Google Apps packages.

 For this guide, we will focus on the second method to install Google Play Store on Windows 11\. So, let’s begin.

 Note that this process requires installing third-party modified files and packages and involves potential risks. Before proceeding,[create a restore point in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) or[recovery drive](http://www.makeuseof.com/create-recovery-drive-system-repair-disc-windows-10/) . These recovery options can help you undo the changes or repair the system if something goes wrong.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Step 3: Enable Virtual Machine to Run Android Apps

![enable windows hypervisor platform windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-windows-hypervisor-platform-windows-11.png)

 You need to[enable and configure Virtual Machine Platform and Windows Hypervisor Platform](https://www.makeuseof.com/windows-11-enable-hyper-v/) to run Windows Subsystem for Android on Windows 11\. Skip this step if you have installed WSA previously.

To configure the Virtual Machine:

1. Press**Win + S** to open the**search bar** .
2. Type**Windows Features** and then click on**Turn Windows features on or off** from the search results.
3. In the Windows Features window, select**Virtual Machine Platform** and**Windows Hypervisor Platform.**
4. Click**OK** to save the changes and Windows will install the selected features. Restart your PC to apply the changes.

If successful, you will see an update status message during restart.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Step 4: Setup and Install Windows Subsystem for Linux and Linux Distro on Windows 11

 To install Google Play Store on Windows 11, you’ll need to build a locally modified Windows Subsystem for Android. For this, you’ll need to install Windows Subsystem for Linux (WSL) and a Linux distro. This is necessary as you’ll need to run some commands to build Windows Subsystem for Android.

To install WSL and a Linux distro on Windows 11:

1. Launch Microsoft Store.
2. In Microsoft Store, search for**Windows Subsystem for Linux (WSL)** and install the app. Wait for the app to install.  
![windows subsystem for linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-linus-1.jpg)
3. Next, search for a Linux distro. We’ll use Ubuntu. So, search for**Ubuntu** and install the distro. If you have a Linux distro installed, you can skip to the next step  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Ubuntu distro windows 11 install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/ubuntu-distro-windows-11-install-1.jpg)
4. Once installed, press the**Win** key and type**Ubuntu** . Right-click on**Ubuntu** and select**Run as administrator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In the Ubuntu terminal, you’ll need to create a user with a password for the Linux system. So, create a username and password. Leave the Ubuntu terminal open.

 Now you’ll see a Linux\\Ubuntu folder in File Explorer’s left pane.

## Step 5: Setup Magisk and Windows Subsystem for Android

 The next set of steps involve downloading a Gitbub repository, MagiskOnWSALocal, to integrate Magisk root and Google Apps into WSA.

1. Go to the[MagiskOnWSALocal page](https://github.com/LSPosed/MagiskOnWSALocal) on GitHub.
2. Click the**Code** drop-down in the top right corner.  
![copy github url magiskonwsa](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/copy-github-url-magiskonwsa.jpg)
3. Copy the**GitHub URL** under the**HTTPS** tab.  
![download install magiskonWSA github command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-install-magiskonwsa-github-command-prompt.jpg)
4. Open the Ubuntu terminal and type the following command followed by the GitHub URL:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, go to your installation drive**C:\\** and create a new folder named**WSA** .  
![WSA folder Windows C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-folder-windows-c-drive.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-ios-and-android-a-tutorial-for-saving-twitters-animations/"><u>[New] 2024 Approved IOS and Android A Tutorial for Saving Twitter's Animations</u></a></li>
<li><a href="https://driver-error.techidaily.com/asus-keyboard-brightness-not-working/"><u>ASUS Keyboard Brightness Not Working</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/comprehensive-manual-for-setting-up-brother-integrated-devices-with-windows-8-os-and-above/"><u>Comprehensive Manual for Setting Up Brother Integrated Devices with Windows 8 OS and Above</u></a></li>
<li><a href="https://win11.techidaily.com/digital-dots-for-the-desktop-top-8-non-writing-notebook-alternatives/"><u>Digital Dots for the Desktop: Top 8 Non-Writing Notebook Alternatives</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/dissecting-inshot-an-elite-video-editor-examined-for-2024/"><u>Dissecting InShot An Elite Video Editor Examined for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eradication-guide-incessant-network-credentials-message/"><u>Eradication Guide: Incessant Network Credentials Message</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-greyed-out-remove-pin-option-in-windows-11/"><u>How to Fix the Greyed-Out Remove PIN Option in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-and-rescue-non-responsive-printer-feature-via-win-plus-p-in-windows/"><u>How to Reactivate and Rescue Non-Responsive Printer Feature via Win + P in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-11-pro-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 11 Pro to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-samsung-galaxy-f15-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Samsung Galaxy F15 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/lighten-load-reducing-heavy-cpu-and-memory-consumption-windows/"><u>Lighten Load: Reducing Heavy CPU & Memory Consumption Windows</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/losungen-finden-wenn-bilder-aus-dem-sd-speicher-fehlern-aufweisen/"><u>Lösungen Finden, Wenn Bilder Aus Dem SD-Speicher Fehlern Aufweisen</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-reset-a-trio-of-win11-adjustments/"><u>Personalize, Reset: A Trio of Win11 Adjustments</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/strategies-for-effective-chatgpt-extensions-use/"><u>Strategies for Effective ChatGPT Extensions Use</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-optimizing-network-address-translation-on-windows/"><u>Strategies for Optimizing Network Address Translation on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-stylus-malfunctions-with-these-tips-for-windows-tablets/"><u>Streamline Stylus Malfunctions with These Tips for Windows Tablets</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-lg-bp550-features-and-reviews-for-2024/"><u>Updated LG BP550 - Features & Reviews for 2024</u></a></li>
</ul></div>

