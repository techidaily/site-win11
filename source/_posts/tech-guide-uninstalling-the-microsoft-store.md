---
title: "Tech Guide: Uninstalling the Microsoft Store"
date: 2024-07-02T13:01:36.279Z
updated: 2024-07-03T13:01:36.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Guide: Uninstalling the Microsoft Store"
excerpt: "This Article Describes Tech Guide: Uninstalling the Microsoft Store"
keywords: Uninstall MSIStore,Remove MS Store,Disable Microsoft Store,Eliminate Windows Store,Removing Store Apps,Stop Store Purchase,Delete Store Apps
thumbnail: https://thmb.techidaily.com/0c50e9701859daef27aa4fad4bc3c104584c3b31a6d296c6daba235eb751bb08.jpg
---

## Tech Guide: Uninstalling the Microsoft Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
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
<li><a href="https://win11.techidaily.com/conjuring-powerful-tools-for-windows-users/"><u>Conjuring Powerful Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-disassembling-dism-for-image-recovery/"><u>The Art of Disassembling Dism for Image Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-google-play-on-w11-os/"><u>Guide: Setting Up Google Play on W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-phone-dialer-mechanics/"><u>Unveiling Windows Phone Dialer Mechanics</u></a></li>
<li><a href="https://win11.techidaily.com/winning-every-game-with-smart-amd-radeon-configurations/"><u>Winning Every Game with Smart AMD Radeon Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-comic-experience-with-windows-11-techniques/"><u>Maximizing Comic Experience with Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/collectors-paradise-unlocked-free-windows-11-for-keys-fan-year-round/"><u>Collector’s Paradise Unlocked: Free Windows 11 For Keys Fan, Year-Round</u></a></li>
<li><a href="https://win11.techidaily.com/check-it-out-quick-fixes-for-your-webcam-and-mic-test/"><u>Check It Out: Quick Fixes for Your Webcam & Mic Test</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-this-article-i-will-show-you-how-to-change-the-shape-of-a-video-in-3-different-ways-with-filmora-for-2024/"><u>Updated In This Article, I Will Show You How to Change the Shape of a Video in 3 Different Ways with Filmora for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/using-montage-in-movies-learn-to-use-montage-with-movies-for-2024/"><u>Using Montage In Movies | Learn to Use Montage With Movies for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-buys-for-your-digital-chime-preferences-in-snapchat/"><u>In 2024, Best Buys for Your Digital Chime Preferences in SnapChat</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-box-tastic-finds-discover-the-best-sites-for-boxes-at-steals/"><u>[Updated] Box-Tastic Finds! Discover the Best Sites for Boxes at Steals</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-tailor-your-vocal-expression-masterful-techniques-for-snapchat-voices/"><u>In 2024, Tailor Your Vocal Expression  Masterful Techniques for Snapchat Voices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-beginners-guide-to-editing-digits-in-tiktoks/"><u>2024 Approved  A Beginner’s Guide to Editing Digits in TikToks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leveraging-zoom-features-for-improved-tiktok-videos/"><u>[New] Leveraging Zoom Features for Improved TikTok Videos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/laying-down-an-elegant-tiktok-credits-panel/"><u>Laying Down an Elegant TikTok Credits Panel</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-the-ultimate-list-of-affordable-and-premium-online-recording-studios-2023-edition/"><u>In 2024, The Ultimate List of Affordable and Premium Online Recording Studios 2023 Edition</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-unbiased-review-of-avs-video-editor-features-pricing-and-more/"><u>Updated In 2024, Unbiased Review of AVS Video Editor Features, Pricing, and More</u></a></li>
</ul></div>
