---
title: Simultaneous Shutdown Techniques for Windowed Applications
date: 2024-07-13T09:53:42.899Z
updated: 2024-07-14T09:53:42.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simultaneous Shutdown Techniques for Windowed Applications
excerpt: This Article Describes Simultaneous Shutdown Techniques for Windowed Applications
keywords: Windows Shutdown Methods,App-Window Shutdown Strategies,Simultaneous Close Apps,Coordinated Application Closure,Windowed Program Termination,Seamless Shutdown Procedures,Multiplexed Software Halt
thumbnail: https://thmb.techidaily.com/75afd5a2790c3528915ac28a66faf57312a6eb60abbc500be807cdf0c4c1fe06.jpg
---

## Simultaneous Shutdown Techniques for Windowed Applications

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://win11.techidaily.com/festive-fireworks-christmas-window-gifts-via-mstore/"><u>Festive Fireworks: Christmas Window Gifts via MSTORE</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-user-experience-tailoring-windows-via-alomware-applications/"><u>Elevate User Experience: Tailoring Windows via AlomWare Applications</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-basics-to-high-quality-srgb-vs-rgb/"><u>From Basics to High-Quality  Srgb vs Rgb</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-10-audio-playback-accelerators-for-phones/"><u>2024 Approved  Top 10 Audio Playback Accelerators for Phones</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-ultimate-guide-to-vimeo-record-features-for-2024/"><u>[New] The Ultimate Guide to Vimeo Record Features for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-how-to-climb-higher-on-tiktoks-rankings-a-guide-for-more-interactions-for-2024/"><u>[Updated] How to Climb Higher on TikTok's Rankings  A Guide for More Interactions for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-learn-the-best-green-screen-video-editors-for-mac-users-including-green-screen-final-cut-pro-for-2024/"><u>New Learn the Best Green Screen Video Editors for Mac Users, Including Green Screen Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-valid-temp-directory-in-windows-11-os/"><u>Ensuring a Valid Temp Directory in Windows 11 OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-pitfall-of-superficial-engagement-on-insta/"><u>[New] In 2024, The Pitfall of Superficial Engagement on Insta</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-senior-accessibility-on-legacy-computers/"><u>Enhancing Senior Accessibility on Legacy Computers</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-troubleshooting-sound-quality-strategies-for-easing-audio-deformation/"><u>New 2024 Approved Troubleshooting Sound Quality Strategies for Easing Audio Deformation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-compre-written-in-html-a-journey-through-web-content-creation-for-2024/"><u>[New] The Compre Written in HTML  A Journey Through Web Content Creation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-taskbar-datetime-visibility/"><u>Adjusting Windows 11 Taskbar Date/Time Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/the-face-swap-revolution-top-apps-for-iphone-and-android-for-2024/"><u>The Face Swap Revolution Top Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-reverting-customized-windows-configurations/"><u>Effective Methods: Reverting Customized Windows Configurations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/10-viral-tweets-dominating-social-media-for-2024/"><u>10 Viral Tweets Dominating Social Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-add-folder-not-possible-issue-with-windows-onedrive/"><u>Combatting 'Add Folder Not Possible' Issue with Windows OneDrive</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-hardware-hurdles-with-intel-drivers/"><u>Overcoming Hardware Hurdles with Intel Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-personalized-taskbar-in-w11-windows/"><u>Crafting a Personalized Taskbar in W11 Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-harmonizing-social-media-twitter-plus-tumblr-videos/"><u>[Updated] In 2024, Harmonizing Social Media  Twitter + Tumblr Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-crafted-for-quality-converting-ipv-files-from-instagram-to-mp4/"><u>[New] 2024 Approved  Crafted for Quality  Converting IPV Files From Instagram to MP4</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-vivo-y100t-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Vivo Y100t Phones</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-realme-narzo-60-pro-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve  deleted photos on Realme Narzo 60 Pro 5G</u></a></li>
<li><a href="https://extra-hints.techidaily.com/detailed-walkthrough-to-load-wm6/"><u>Detailed Walkthrough to Load WM6</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-sudden-invisibility-issues-in-pc-gaming/"><u>Eradicating Sudden Invisibility Issues in PC Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-vivo-v29e-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Vivo V29e Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-lsa-error-on-windows-systems/"><u>Fixing LSA Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/embark-on-a-parallels-driven-path-for-windows-11-installation/"><u>Embark on a Parallels-Driven Path for Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-elevating-vr-gametime-through-advanced-recording-practices/"><u>2024 Approved  Elevating VR Gametime Through Advanced Recording Practices</u></a></li>
<li><a href="https://win11.techidaily.com/selecting-the-best-downloader-choco-vs-windows-package-tool/"><u>Selecting the Best Downloader: Choco Vs. Windows Package Tool</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-information-gathering-using-everythingapp/"><u>Efficient PC Information Gathering Using EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-how-to-access-your-secret-snaps-archive/"><u>2024 Approved  How to Access Your Secret Snaps Archive</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-straightforward-screen-capture-app-win10-edition/"><u>[Updated] In 2024, Straightforward Screen Capture App, Win10 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-obstructions-a-guide-to-windows-11s-search-problems/"><u>Clearing Obstructions: A Guide to Windows 11'S Search Problems</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-sony-xperia-10-v-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-exploring-the-perks-and-pitfalls-of-mcn-alliances-for-2024/"><u>[Updated] Exploring the Perks and Pitfalls of MCN Alliances for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-intricate-yet-straightforward-guide-exploring-popular-youtube-reactions/"><u>[Updated] The Intricate Yet Straightforward Guide  Exploring Popular YouTube Reactions</u></a></li>
</ul></div>
