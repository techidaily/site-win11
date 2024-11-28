---
title: "Purging Windows 11 Store: Simple Steps"
date: 2024-11-24T21:19:31.125Z
updated: 2024-11-28T02:22:20.942Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Purging Windows 11 Store: Simple Steps"
excerpt: "This Article Describes Purging Windows 11 Store: Simple Steps"
keywords: WinStoreCleanup,Windows11Optimize,RemoveWinStore,StreamliningWindows,SimplifyWinXP,XPStoreDeletion,EasyWinStoreClear
thumbnail: https://thmb.techidaily.com/64cbdaa1aef5615ff39347b9db4c0280ec8c3ce520d27154774aa65c3ef13831.jpg
---

## Purging Windows 11 Store: Simple Steps

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://extra-resources.techidaily.com/a-look-at-the-best-narrative-creators-on-youtube-in-23-for-2024/"><u>A Look at the Best Narrative Creators on YouTube in '23 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-black-screens-during-system-bootup/"><u>Fixing Black Screens During System Bootup</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-chrome-not-downloading-files-on-windows/"><u>How to Fix Chrome Not Downloading Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-maximizing-windows-11/"><u>Mastering the Art of Maximizing Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-delay-in-boot-cycle-managing-win11-sequence/"><u>Minimizing Delay in Boot Cycle: Managing Win11 Sequence</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-do-you-want-your-photos-and-videos-to-give-an-old-and-vintage-feel-here-are-some-vintage-luts-premiere-pro-free-and-paid-options-available/"><u>New 2024 Approved Do You Want Your Photos and Videos to Give an Old and Vintage Feel? Here Are some Vintage LUTs Premiere Pro Free and Paid Options Available to Download</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-educational-visuals-on-windows-11/"><u>Optimize Educational Visuals on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-audio-error-0xc00d36b4-in-win11-pcs/"><u>Overcoming Audio Error: 0XC00D36B4 in Win11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-how-to-mask-after-dim-setting-on-windows/"><u>Quick Guide: How To Mask After Dim Setting on Windows</u></a></li>
<li><a href="https://techidaily.com/some-mp4-won-t-play-on-my-samsung-galaxy-s21-fe-5g-2023-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Samsung Galaxy S21 FE 5G (2023)</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-solutions-for-preventing-pc-crashes-during-horizon-forbidden-west-complete-playthrough/"><u>Step-by-Step Solutions for Preventing PC Crashes During 'Horizon Forbidden West' Complete Playthrough</u></a></li>
<li><a href="https://youtube-web.techidaily.com/en-viewers-favorites-in-a-single-day-on-youtube-for-2024/"><u>Top Ten Viewers' Favorites in a Single Day on YouTube for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-your-pcs-power-a-guide-to-activating-the-stealthy-find-bar/"><u>Unlocking Your PC's Power: A Guide to Activating the Stealthy Find Bar</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-dead-internet-whos-listening-when-you-speak-online/"><u>Unveiling the 'Dead Internet': Who's Listening When You Speak Online?</u></a></li>
<li><a href="https://win11.techidaily.com/win-tips-swapping-display-screens/"><u>Win Tips: Swapping Display Screens</u></a></li>
</ul></div>

