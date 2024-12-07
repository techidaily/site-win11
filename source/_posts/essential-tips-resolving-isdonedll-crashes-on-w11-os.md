---
title: "Essential Tips: Resolving ISDone.dll Crashes on W11 OS"
date: 2024-12-04T23:42:49.701Z
updated: 2024-12-06T18:46:04.141Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Essential Tips: Resolving ISDone.dll Crashes on W11 OS"
excerpt: "This Article Describes Essential Tips: Resolving ISDone.dll Crashes on W11 OS"
keywords: Windows W11 DLL Fix,ISDoneCrash Solutions,DLL Error W11 Guide,W11 OS Stability Tips,Isdone.dll Troubleshooting,Win11 Crash Resolution,DLL Issues on Windows 11
thumbnail: https://thmb.techidaily.com/b84b835099bbd2f060100cf1ff53df1a6537fd5a4b5a03be31336b43fbf43c35.jpg
---

## Essential Tips: Resolving ISDone.dll Crashes on W11 OS

 Some players have reported an ISDone.dll installation error for Windows games. That issue can arise when players try to install certain games with setup wizards. The message in the ISDone.dll error window says, “It is not found any file specified for ISAarcExtract.”

 Users can’t install games on Windows 10 or 11 when the ISDone.dll error appears. Is the same error stopping you from installing a PC game? If it is, this is how you can fix the ISDone.dll installation issue in Windows 11 and 10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Game’s Installer With Admin Rights

 First, run the game’s setup file with elevated rights to ensure admin restrictions can’t cause the issue. As you’ll only need to install the game once, it’s not necessary to set the installer to[always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) . Open the folder that includes the game’s setup.exe. Right-click the game’s installer (setup) file and select its**Run as administrator** context menu option.

![The Run as administrator context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-as-administrator-context-menu-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the Game’s Installer in Compatibility Mode

 Some players have confirmed they’ve fixed the ISDone.dll error by setting the setup wizards for their games to run in compatibility mode. That potential resolution is more likely to work for older games released before Windows 10's own. You can set a setup file to run in compatibility mode like this:

1. First, press Explorer’s**Win + E** key combination to open the File Manager.
2. Navigate to the directory that includes the game setup wizard for which you need to fix the ISDone.dll error.
3. Right-click the setup.exe file for the game and select**Properties** .
4. Select**Compatibility** along the top of the properties window.
5. Next, select the**Run this program in compatibility** mode box.
6. Select the**Windows 7** platform option on the drop-down menu. If your game predates that platform, you can also try selecting Vista or XP.  
![The Run this program in compatibility mode for option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-this-program-in-compatibility-mode-setting.jpg)
7. Click**Apply** to save the compatibility settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Select**OK** to close the setup properties window.

## 3\. Set the Game’s Setup Wizard at High Priority

 Increasing the priority for a game’s setup wizard will raise the system resources allocated to its process. Our article about[setting a priority level for a program](https://www.makeuseof.com/windows-11-set-program-priority/) includes step-by-step instructions for how to apply this potential fix. Open the game’s setup wizard and set its priority level to High in Task Manager as outlined within that guide.

![The Set priority option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-set-priority-option.jpg)

## 4\. Run System File and Image Scans

 System file corruption is another potential cause for the ISDone.dll error in Windows 11/10\. So, we recommend users run a System File Checker scan to address that possible cause. Check out our[guide about running the SFC tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) for further details about how to apply this solution.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-sfc-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In addition, you can also run a Deployment Image Servicing Management scan on top. That scan can resolve issues with the system image. You can run that utility in the Command Prompt by executing this command:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 5\. Increase Virtual Memory Allocation

 As the ISDone.dll error sometimes arises due to insufficient system memory, increasing virtual memory allocation can be a viable solution. Virtual memory is extra memory reallocated from hard drive storage when your PC’s RAM utilization is at maximum. Expanding the paging file will increase the virtual memory.

 You can apply this solution by following the steps in our[how to increase virtual memory](https://www.makeuseof.com/how-increase-virtual-memory-windows-11/) guide. Enter custom megabyte values in the**Initial** and**Maximum size** boxes on the Virtual Memory window. It’s recommended to enter an initial value 1.5 times higher than your PC’s total RAM amount in megabytes. Input a maximum value three times higher than the total RAM on your PC.

![The Virtual Memory window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/custom-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For example, a PC with four GB RAM would have 4096 megabytes of memory. Then you would need to multiply 1.5 by 4096 to input a value of 6144 in the**Initial** box. Three times 4096 amounts to 12288, which would be the value to enter the**Maximum size** box.

## 6\. Install Any Missing Visual C++ Redistributables

 The ISDone.dll error could be occurring because some required Visual C++ Redistributable runtimes are missing on your PC. The solution in such a scenario is to install the required C++ runtime libraries that are missing. You can install missing Visual C++ runtimes in the following steps:

1. Open Microsoft’s download page for[Visual C++ Redistributable packs](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) in your browser.
2. Then click the X64 link for the Visual Studio 2015-2022 package.  
![The X64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-download-link-for-visual-c.jpg)
3. Double-click the**VC\_redist.x64.exe** file to open an installer window.
4. Select the checkbox for agreeing to the license terms.  
![The Microsoft Visual C++ 2015-2022 runtime installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-visual-c-installer-window.jpg)
5. Click the Visual C++**Install** option.

 If the ISDone.dll installation issue arises for an old game, you might need to install missing Visual C++ runtimes that predate 2015\. In this case, you’ll need to repeat the above steps for older Visual C++ packs. Try downloading the 64-bit Visual Studio 2013 and 2012 packs from the same Microsoft page to install older missing runtime libraries.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Re-Register the Referenced ISDone DLL File

 The ISDone.dll error references an ISDone DLL file, which might not be correctly registered. Reregistering that file could resolve the issue for some users. This is how to register the ISDone DLL file:

1. Press**Win + S** to open Windows Search
2. Type in**Command Prompt** to find that app.
3. Click**Run as administrator** for the Command Prompt app within the search results.
4. Input this command for reregistering ISDone.dll and hit**Enter** :  
`regsvr32 isdone.dll`  
![The regsvr32 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-regsvr-command.jpg)

## 8\. Temporarily Switch Off Your PC’s Antivirus Shield

 It’s not entirely unusual for antivirus apps to cause installation issues like the ISDone.dll error. You can ensure your antivirus tool isn’t interfering with the installation process by temporarily disabling its shield before attempting to install the game. Our[guide to disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) explains how to turn off the antivirus shield for the default Windows Security app.

![The Real-time protection option in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-option.jpg)

 Users who’ve installed alternative security software packages on PCs will need to disable the third-party antivirus shields. To do that, click a system tray icon for an antivirus app to bring up its context menu. Then, select an option for turning off (or disabling) the antivirus shield.

 However, don’t leave your antivirus software disabled. Instead, turn it off and then try to install whatever game the ISDone.dll error occurs for. Then make sure you re-enable the antivirus shield afterward.

## 9\. Clean Boot the Windows PC

 To minimize potential conflicting processes, try clean booting your PC. Setting a clean boot involves disabling all third-party startup apps and services. That will reduce the number of background services and apps that start with Windows, which could eliminate a process causing the ISDone.dll error.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-services-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Our guide to[configuring a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to disable third-party startup apps and services with Task Manager and MSConfig. When you’ve set the clean boot and restarted Windows, try installing the game the ISDone.dll error occurs for. Then you can restore the original boot configuration afterward.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Enjoy Your Windows Games Again

 Players have widely confirmed those resolutions fix the ISDone.dll error. So, applying the potential ISDone.dll error resolutions above will probably resolve that game installation issue in most cases. Yet, they might not work for everyone, and you can contact support services for affected game titles if further potential fixes are needed.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-digital-audience-accolades-for-content-makers/"><u>[New] In 2024, Digital Audience Accolades for Content Makers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-full-spectrum-review-google-podcasts-app-explained/"><u>[Updated] Full Spectrum Review Google Podcasts App Explained</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-4k-perfection-selecting-youtubes-best-video-tools/"><u>2024 Approved 4K Perfection Selecting YouTube's Best Video Tools</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-from-apple-iphone-7-plusipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock from Apple iPhone 7 Plus/iPad/iPod</u></a></li>
<li><a href="https://win11.techidaily.com/command-your-computer-manage-updates-and-downtime-in-windows-11/"><u>Command Your Computer: Manage Updates and Downtime in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-stuck-loading-screen-in-league-of-legends/"><u>Fixing Stuck Loading Screen in League of Legends</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-immersive-windows-display-snapshots/"><u>In 2024, Immersive Windows Display Snapshots</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-the-face-forward-top-makeup-creatives/"><u>In 2024, The Face Forward Top Makeup Creatives</u></a></li>
<li><a href="https://win11.techidaily.com/master-guide-fixing-win11win10-bluetooth-pin-related-disconnects/"><u>Master Guide: Fixing Win11/Win10 Bluetooth PIN-Related Disconnects</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-files-win8-apps-that-modify-dates/"><u>Master Your Files: Win8 Apps That Modify Dates</u></a></li>
<li><a href="https://solve-hot.techidaily.com/reinitialisation-des-versions-precedentes-manquantes-guide-complet/"><u>Réinitialisation Des Versions Précédentes Manquantes - Guide Complet</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-password-problems-5-effective-fixes-for-windows-keys-errors/"><u>Swiftly Solve Password Problems: 5 Effective Fixes for Windows Keys Errors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/syncmaster-xtra-leading-solution-for-effortless-cross-platform-file-sharing-between-ios-devices-and-computers/"><u>SyncMaster Xtra: Leading Solution for Effortless Cross Platform File Sharing Between iOS Devices & Computers</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-classics-using-madvr-in-windows-os/"><u>Upgrade Your Classics Using MadVR in Windows OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721457367500-why-isnt-your-iphone-charging-wirelessly-discover-7-fixes-that-work/"><u>Why Isn’t Your iPhone Charging Wirelessly? Discover 7 Fixes That Work</u></a></li>
</ul></div>

