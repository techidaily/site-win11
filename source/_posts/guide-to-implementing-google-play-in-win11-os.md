---
title: Guide to Implementing Google Play in Win11 OS
date: 2024-09-05T08:36:29.268Z
updated: 2024-09-06T08:36:29.268Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Implementing Google Play in Win11 OS
excerpt: This Article Describes Guide to Implementing Google Play in Win11 OS
keywords: Win11 Google Play Guide,Integrating Google Store Windows,Win11 App Marketplace Setup,Google Play Implementation on W11,Setting Up Google Play Store in Win11,Installing Win11 Google Play,Accessing Google Play via W11 OS
thumbnail: https://thmb.techidaily.com/9f78d218ca56a8e977ac9c156c6d3df029b653f49542887406f9b6531aa186a8.jpg
---

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Guide to Implementing Google Play in Win11 OS

 You can natively run Android apps on Windows 11 via Windows Subsystem for Android (WSA); however, it has its limitations. The new OS only natively supports Amazon’s Appstore and not Google Play Store. And while sideloading Android apps is an option, anything that requires Google Play Services will not work.

 However, you can install Google Play Store on Windows 11 to overcome this limitation. Here we show you how.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Install Google Play Store on Windows 11

 As discussed earlier, you can[sideload and run Android apps on Windows 11](https://www.makeuseof.com/windows-11-sideload-android-apps/) . However, finding APKs and installing them via the Command Prompt is cumbersome. You also need to configure Android Debug Bridge (ADB) to install Android apps.

 You can install a fully functional Google Play Store to remedy this problem. Also, this allows you to run Google Play Services-dependent apps.

 However, it is a complicated process and involves downloading several small packages and then moving them around. Fortunately, a developer (Yujinchang08) on GitHub has simplified this process with a custom WSA installer.

 The WSA installer consists of a modified WSA package with Magisk and Open GApps integration. Magisk is a root access utility wherein Open GApps offers up-to-date Google Apps packages.

 For this guide, we will focus on the second method to install Google Play Store on Windows 11\. So, let’s begin.

 Note that this process requires installing third-party modified files and packages and involves potential risks. Before proceeding,[create a restore point in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) or[recovery drive](http://www.makeuseof.com/create-recovery-drive-system-repair-disc-windows-10/) . These recovery options can help you undo the changes or repair the system if something goes wrong.

## Step 1: Uninstall Android Subsystem for Android

![uninstall windows subsystem for android](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/uninstall-windows-subsystem-for-android.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128844/7443" target="_top" id="2128844">
  <img src="//a.impactradius-go.com/display-ad/7443-2128844" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128844/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 3: Enable Virtual Machine to Run Android Apps

![enable windows hypervisor platform windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-windows-hypervisor-platform-windows-11.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You need to[enable and configure Virtual Machine Platform and Windows Hypervisor Platform](https://www.makeuseof.com/windows-11-enable-hyper-v/) to run Windows Subsystem for Android on Windows 11\. Skip this step if you have installed WSA previously.

To configure the Virtual Machine:

1. Press**Win + S** to open the**search bar** .
2. Type**Windows Features** and then click on**Turn Windows features on or off** from the search results.
3. In the Windows Features window, select**Virtual Machine Platform** and**Windows Hypervisor Platform.**
4. Click**OK** to save the changes and Windows will install the selected features. Restart your PC to apply the changes.

If successful, you will see an update status message during restart.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 4: Setup and Install Windows Subsystem for Linux and Linux Distro on Windows 11

 To install Google Play Store on Windows 11, you’ll need to build a locally modified Windows Subsystem for Android. For this, you’ll need to install Windows Subsystem for Linux (WSL) and a Linux distro. This is necessary as you’ll need to run some commands to build Windows Subsystem for Android.

To install WSL and a Linux distro on Windows 11:

1. Launch Microsoft Store.
2. In Microsoft Store, search for**Windows Subsystem for Linux (WSL)** and install the app. Wait for the app to install.  
![windows subsystem for linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-linus-1.jpg)
3. Next, search for a Linux distro. We’ll use Ubuntu. So, search for**Ubuntu** and install the distro. If you have a Linux distro installed, you can skip to the next step  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Ubuntu distro windows 11 install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/ubuntu-distro-windows-11-install-1.jpg)
4. Once installed, press the**Win** key and type**Ubuntu** . Right-click on**Ubuntu** and select**Run as administrator** .
5. In the Ubuntu terminal, you’ll need to create a user with a password for the Linux system. So, create a username and password. Leave the Ubuntu terminal open.

 Now you’ll see a Linux\\Ubuntu folder in File Explorer’s left pane.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 5: Setup Magisk and Windows Subsystem for Android

 The next set of steps involve downloading a Gitbub repository, MagiskOnWSALocal, to integrate Magisk root and Google Apps into WSA.

1. Go to the[MagiskOnWSALocal page](https://github.com/LSPosed/MagiskOnWSALocal) on GitHub.
2. Click the**Code** drop-down in the top right corner.  
![copy github url magiskonwsa](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/copy-github-url-magiskonwsa.jpg)
3. Copy the**GitHub URL** under the**HTTPS** tab.  
![download install magiskonWSA github command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-install-magiskonwsa-github-command-prompt.jpg)
4. Open the Ubuntu terminal and type the following command followed by the GitHub URL:  
`git clone https://github.com/LSPosed/MagiskOnWSALocal.git`
5. Press**Enter** to close the GitHub repository to the Linux user account on your computer.  
![run script magiskonwsa local install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-script-magiskonwsa-local-install.jpg)
6. Next, type the following command to move to the scripts folder. This will change the directory to the specified folder.  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
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


