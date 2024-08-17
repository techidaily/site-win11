---
title: How to Install the Google Play Store on Windows 11
date: 2024-08-15T23:45:53.168Z
updated: 2024-08-16T23:45:53.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Install the Google Play Store on Windows 11
excerpt: This Article Describes How to Install the Google Play Store on Windows 11
keywords: Windows 11 Google Play Installs,Play Store Setup Windows,Google Play Windows Step-by-Step,Installing Play Store Windows 11,Setting Up Play Store on PC,Direct Google Play for Windows,Guide to Windows Play Store Installation
thumbnail: https://thmb.techidaily.com/8ec7f9d19b5395810145f1bf31b1db142a6ba9be6ed8b5f1e4a621d2eef1f390.jpg
---

## How to Install the Google Play Store on Windows 11

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
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 4: Setup and Install Windows Subsystem for Linux and Linux Distro on Windows 11

 To install Google Play Store on Windows 11, you’ll need to build a locally modified Windows Subsystem for Android. For this, you’ll need to install Windows Subsystem for Linux (WSL) and a Linux distro. This is necessary as you’ll need to run some commands to build Windows Subsystem for Android.

To install WSL and a Linux distro on Windows 11:

1. Launch Microsoft Store.
2. In Microsoft Store, search for**Windows Subsystem for Linux (WSL)** and install the app. Wait for the app to install.  
![windows subsystem for linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-linus-1.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
3. Copy the**GitHub URL** under the**HTTPS** tab.  
![download install magiskonWSA github command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-install-magiskonwsa-github-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## Step 6: Install Google Play Store on Windows 11

1. Next, in the**Into to MagiskOnWSA** dialog, select**OK** .  
![intro to magiskonWSA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/intro-to-magiskonwsa.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Next, select**X64 X86\_64** for**Build Arch** .  
![build arch masigkonwsa local](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/build-arch-masigkonwsa-local.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, for**WSA release** type, select**Retail Stable Channel** .  
![WSA retail type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-retail-type.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
4. Select**No** in the**Do you want to** **Root WSA dialog** .
5. Select**Yes** in the**Do you want to install GApps** dialog.  
![which GApps you want to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/which-gapps-you-want-to-install.jpg)
6. Select**OpenGApps** in the**Which GApps do you want to install** dialog.
7. Next, in the**Do you want to keep Amazon Appstore** dialog, select**Yes** or**No** , depending on your requirement.
8. Select**No** in the**Do you want to compress the output** dialog.
9. MagiskOnWSALocal will start generating custom Windows subsystem for the Android image.

 This process may take some time to complete. So, wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
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
<li><a href="https://some-skills.techidaily.com/new-the-future-is-now-insights-from-jaunt-vr-review/"><u>[New] The Future Is Now  Insights From Jaunt VR Review</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-best-eco-savvy-movie-capture-tools-usage-methods/"><u>[Updated] Best Eco-Savvy Movie Capture Tools  Usage Methods</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-blitz-broadcasting-channel-your-playlist-swiftly/"><u>[Updated] In 2024, Blitz Broadcasting  Channel Your Playlist Swiftly</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-samsung-photo-editor-review-pros-con-features-and-guide/"><u>[Updated] In 2024, Samsung Photo Editor Review - Pros, Con, Features, and Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tactics-to-maximize-engagement-with-every-reddit-post/"><u>[Updated] Tactics to Maximize Engagement with Every Reddit Post</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-fast-track-installing-snapchat-on-your-mac-device/"><u>2024 Approved  Fast Track  Installing Snapchat on Your Mac Device</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-transform-your-ideas-into-actionable-steps-idevice-screenshots-for-video-sharing/"><u>2024 Approved  Transform Your Ideas Into Actionable Steps  IDevice Screenshots for Video Sharing</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721202589069-boost-your-website-traffic-with-the-expertise-of-cookiebot/"><u>Boost Your Website Traffic with the Expertise of Cookiebot</u></a></li>
<li><a href="https://win11.techidaily.com/breach-the-barrier-opening-credential-store/"><u>Breach the Barrier: Opening Credential Store</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-operators-invisible-input-on-windows/"><u>Elusive Operators: Invisible Input on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-30015-26-in-microsoft-365-for-windows-users/"><u>Fixing Error Code 30015-26 in Microsoft 365 for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-are-c-and-d-drive-identities-unique/"><u>How Are C: And D: Drive Identities Unique?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-defender-antivirus-blockage/"><u>How to Bypass Windows Defender Antivirus Blockage</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-tecno-pop-8-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effectively-restart-your-windows-graphics-driver/"><u>How to Effectively Restart Your Windows Graphics Driver</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-scaling-issues-for-high-dpi-screens/"><u>How to Fix Windows Scaling Issues for High DPI Screens</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-on-apple-iphone-12-pro-max-by-drfone-ios/"><u>How To Remove the Two Factor Authentication On Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-manual-how-to-turn-off-igtv/"><u>In 2024, Manual  How to Turn Off IGTV</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-samsung-galaxy-s23-fe-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Samsung Galaxy S23 FE Phone Pattern Lock</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-the-full-screen-potential-of-premiere-pro/"><u>In 2024, Unlocking the Full Screen Potential of Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-for-windows-11-widgets-a-comprehensive-list-of-enhancements/"><u>New Horizons for Windows 11 Widgets: A Comprehensive List of Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-windows-hello-fingerprint-recognition-issues/"><u>Quick Fixes to Windows Hello Fingerprint Recognition Issues</u></a></li>
<li><a href="https://win11.techidaily.com/rekindle-your-computers-potential-with-windows-11-via-to-go-and-rufus-path/"><u>Rekindle Your Computer's Potential with Windows 11, Via To Go & Rufus Path</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-interruptexceptionnothandled-in-w11-bsods/"><u>Resolving INTERRUPT_EXCEPTION_NOT_HANDLED in W11 BSODs</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-lost-connection-fixes-for-wifi-failures-in-win11/"><u>Reviving Your Lost Connection: Fixes for Wifi Failures in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719378810676-shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-windows-updates/"><u>Steps to Reactivate Deactivated Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-microsoft-store-use-in-windows-11/"><u>Streamlining Microsoft Store Use in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-disassembling-dism-for-image-recovery/"><u>The Art of Disassembling Dism for Image Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/the-fundamentals-of-using-windows-odbc-connectivity/"><u>The Fundamentals of Using Windows' ODBC Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/title-shaping-desktop-interface-with-icon-distance-manipulation/"><u>Title: Shaping Desktop Interface with Icon Distance Manipulation</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-selection-elite-power-inverters-coming-powertechtrends/"><u>Ultimate Selection: Elite Power Inverters Coming #PowerTechTrends</u></a></li>
</ul></div>
