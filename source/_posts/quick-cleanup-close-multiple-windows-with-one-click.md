---
title: "Quick Cleanup: Close Multiple Windows with One Click"
date: 2024-07-13T10:17:36.689Z
updated: 2024-07-14T10:17:36.689Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Cleanup: Close Multiple Windows with One Click"
excerpt: "This Article Describes Quick Cleanup: Close Multiple Windows with One Click"
keywords: Quick Closure,Single Window Tap,Multi-Close Tool,One-Click Close,Efficient Window Halt,Faster Cleanup,Unified Window Shutdown
thumbnail: https://thmb.techidaily.com/fe074f06665304f02bb44d59a2cf2f7a7e742cf6a430b43148a19a35d32e38f9.jpg
---

## Quick Cleanup: Close Multiple Windows with One Click

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
<li><a href="https://win11.techidaily.com/addressing-msresourceappname-text-glitch-in-w11/"><u>Addressing 'MsResource/AppName Text' Glitch in W11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-image-jest-inc-punpictures-pro/"><u>[Updated] Image Jest Inc  PunPictures Pro</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-printer-commands-using-windows-11-edge-shield-mode/"><u>Triggering Printer Commands Using Windows 11 Edge Shield Mode</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-proven-methods-for-crafting-big-head-effects-in-tiktok-3-approaches/"><u>2024 Approved  Proven Methods for Crafting Big Head Effects in TikTok (3 Approaches)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-engaging-audiences-through-snapbiz-campaigns/"><u>[New] In 2024, Engaging Audiences Through SnapBiz Campaigns</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-more-disk-room-with-this-roundup-of-cheap-volume-enhancers/"><u>Unlock More Disk Room with This Roundup of Cheap Volume Enhancers</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-insufficient-installation-authorization-errors/"><u>Addressing Insufficient Installation Authorization Errors</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unlocking-the-potential-of-bandicam-your-ultimate-guide/"><u>[Updated] Unlocking the Potential of Bandicam – Your Ultimate Guide</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-non-existent-drive-letters-on-windows-causes-corrections/"><u>Understanding Non-Existent Drive Letters on Windows: Causes, Corrections</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-console-collapse-avoiding-sudden-df-closures/"><u>Counteracting Console Collapse: Avoiding Sudden DF Closures</u></a></li>
<li><a href="https://win11.techidaily.com/cleaning-slates-in-windows-the-3-reset-routes/"><u>Cleaning Slates in Windows: The 3 Reset Routes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-values-on-windows-devices/"><u>Troubleshooting Missing Values on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-with-recalled-logon-code/"><u>Unlocking Windows with Recalled Logon Code</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-impact-do-widgets-streamline-win-11s-usage/"><u>Assessing the Impact: Do Widgets Streamline Win 11'S Usage?</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-cause-behind-error-0x80370102-in-wsl-distribution/"><u>Unraveling the Cause Behind Error 0X80370102 in WSL Distribution</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/winrars-file-consistency-fixing-summation-discrepancies/"><u>WinRAR's File Consistency: Fixing Summation Discrepancies</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-methods-to-project-epoch-shifts/"><u>[New] Methods to Project Epoch Shifts</u></a></li>
<li><a href="https://win11.techidaily.com/1719276552494-unlock-windows-free-up-space-no-more-temp-files/"><u>Unlock Windows Free Up Space, No More Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-xc0000142-in-winoses/"><u>Addressing Error XC0000142 in WinOSes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-filmmaking-for-the-future-adapting-videos-vertically-for-instagram/"><u>[Updated] 2024 Approved  Filmmaking for the Future  Adapting Videos Vertically for Instagram</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unleash-your-creativity-top-rated-4k-video-editing-software-for-2024/"><u>Updated Unleash Your Creativity Top-Rated 4K Video Editing Software for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-spotify-how-to-exclude-recommended-podcasts/"><u>In 2024, Spotify  How to Exclude Recommended Podcasts</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-x100-pro-by-fonelab-android-recover-photos/"><u>How to get back lost photos from X100 Pro.</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-optimal-practices-for-archiving-interactive-online-workshops/"><u>2024 Approved  Optimal Practices for Archiving Interactive Online Workshops</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-a-closed-captioning-guru-windows-10-insights/"><u>Becoming a Closed Captioning Guru: Windows 10 Insights</u></a></li>
<li><a href="https://win11.techidaily.com/windows-networking-essentials-managing-arp-cache/"><u>Windows Networking Essentials: Managing ARP Cache</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-ftdibussys-and-windows-memory-standards/"><u>Unlocking the Secrets of ftdibus.sys & Windows Memory Standards</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
</ul></div>
