---
title: "Windows 11 Setup: Effortless Installation of Legacy Applications"
date: 2024-12-26T22:14:32.663Z
updated: 2024-12-28T00:51:18.089Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Setup: Effortless Installation of Legacy Applications"
excerpt: "This Article Describes Windows 11 Setup: Effortless Installation of Legacy Applications"
keywords: Windows 11 Guide,Legacy Apps in Win11,Easy Win11 Setup,Win11 Installer,Install Win11 Easily,Win11 Upgrade Path,Enable Old Apps W11
thumbnail: https://thmb.techidaily.com/06629510e11e9d29470adf181e231bb23d34ab4b20d9291b76fb465837bc25f3.jpg
---

## Windows 11 Setup: Effortless Installation of Legacy Applications

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/)and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-ultimate-online-seminar-creation-assistant/"><u>[New] Ultimate Online Seminar Creation Assistant</u></a></li>
<li><a href="https://games-able.techidaily.com/apples-mac-gaming-revolution-with-sonoma-os-and-its-new-game-mode-feature/"><u>Apple's Mac Gaming Revolution with Sonoma OS and Its New Game Mode Feature</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-infinix-note-30-vip-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Infinix Note 30 VIP</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-0x800713f-halt-in-windows-11-mail/"><u>Eliminating 0X800713F Halt in Windows 11 Mail</u></a></li>
<li><a href="https://games-able.techidaily.com/investing-smartly-in-virtual-reality-headsets/"><u>Investing Smartly in Virtual Reality Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-malware-control-strategies-to-tackle-unavailable-defender-engine/"><u>Mastering Malware Control: Strategies To Tackle Unavailable Defender Engine</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-your-windows-11-experience-with-forgotten-features/"><u>Maximizing Your Windows 11 Experience with Forgotten Features</u></a></li>
<li><a href="https://win11.techidaily.com/mending-winget-glitches-on-modern-windows/"><u>Mending Winget Glitches on Modern Windows</u></a></li>
<li><a href="https://howto.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-honor-x9a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Honor X9a | Dr.fone</u></a></li>
<li><a href="https://solve-popular.techidaily.com/step-by-step-instructions-removing-disk-partitions-efficiently-on-windows-11-platform/"><u>Step-by-Step Instructions: Removing Disk Partitions Efficiently on Windows 11 Platform</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-obs-recording-glitch-on-windows/"><u>Steps to Overcome OBS Recording Glitch on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11s-help-app-malfunction/"><u>Troubleshooting Windows 11'S Help App Malfunction</u></a></li>
<li><a href="https://buynow-help.techidaily.com/ultimate-guide-to-the-best-laptop-battery-packs-of-2024/"><u>Ultimate Guide to the Best Laptop Battery Packs of 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/ultimate-mobile-solutions-to-sharpen-dji-drone-shoots-for-2024/"><u>Ultimate Mobile Solutions to Sharpen DJi Drone Shoots for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-toms-latest-computer-components-inside-look-with-toms-hardware-the-gadget-guide/"><u>Unveiling Tom's Latest Computer Components: Inside Look with Tom's Hardware | The Gadget Guide</u></a></li>
</ul></div>

