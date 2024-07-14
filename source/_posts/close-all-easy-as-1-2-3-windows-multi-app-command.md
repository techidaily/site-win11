---
title: "Close All, Easy as 1-2-3: Windows Multi-App Command"
date: 2024-07-13T10:27:36.491Z
updated: 2024-07-14T10:27:36.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Close All, Easy as 1-2-3: Windows Multi-App Command"
excerpt: "This Article Describes Close All, Easy as 1-2-3: Windows Multi-App Command"
keywords: Close Apps Quickly,One-Click Shutdown,Simplify Window Closure,Easy Windows Management,Fast Multitasking Control,Multi-App Command Center,Seamless System Halt
thumbnail: https://thmb.techidaily.com/f75585e4daf78953dd0ce1cfd0b26209fab1e9c588003fe7de564148a8e3e23c.jpg
---

## Close All, Easy as 1-2-3: Windows Multi-App Command

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
<li><a href="https://win11.techidaily.com/seamless-android-windows-webcam-transition-techniques/"><u>Seamless Android-Windows Webcam Transition Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-windows-audioscape-via-driver-update-steps/"><u>Revamping Windows Audioscape via Driver Update Steps</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-missing-window-panes-with-win11-6-tips/"><u>Reclaiming Missing Window Panes with Win11 (6 Tips)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-zooming-in-on-clarity-an-essential-guide-to-professional-quality-audio-recordings/"><u>[New] Zooming In On Clarity  An Essential Guide to Professional-Quality Audio Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-dxgierror-post-device-disconnect/"><u>Avoidance of DXGI_Error Post Device Disconnect</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-god-of-war-ragnarok-release-date/"><u>[Updated] In 2024, God of War Ragnarok Release Date</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-computers-efficient-filesharing-through-python-on-windows/"><u>Bridging Computers: Efficient Filesharing Through Python on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Samsung Galaxy S23 Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-greyed-out-pin-deletion-in-windows-11-interface/"><u>Resetting Greyed-Out Pin Deletion in Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/14-unveiling-windows-11-post-update-feature-list/"><u>14 Unveiling Windows 11: Post-Update Feature List</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-data-metering-settings-for-wi-fi-in-windows-11/"><u>Configuring Data Metering Settings for Wi-Fi in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-vds-failures-head-on/"><u>Tackling Windows VDS Failures Head-On</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-make-vintage-film-effect-1980s-for-2024/"><u>Updated How to Make Vintage Film Effect 1980S for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-prime-audiosubtitle-malfunctions-on-windows-11-systems/"><u>Resolve Prime Audio/Subtitle Malfunctions on Windows 11 Systems</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-video-editing-essentials-for-mac-os-x-yosemite-tips-and-tricks/"><u>New 2024 Approved Video Editing Essentials for Mac OS X Yosemite Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-idle-screen-time-on-windows/"><u>Configuring Idle Screen Time on Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-fostering-resilience-in-the-face-of-cyber-haters/"><u>[Updated] In 2024, Fostering Resilience in the Face of Cyber Haters</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-lava-yuva-3-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-cheap-traps-the-realities-of-inferior-windows-activation-codes/"><u>Avoid Cheap Traps: The Realities of Inferior Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-reviving-copy-paste-feature-across-browsers/"><u>Quick Guide: Reviving Copy-Paste Feature Across Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-unsupported-devices-warning/"><u>Quick Guide: Fixing Unsupported Devices Warning</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-no-connection-found-error-in-win/"><u>Steps to Solve No Connection Found Error in WIN</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-path-alteration-guide-for-windows-11-users/"><u>OneDrive Path Alteration Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-gaming-power-drain-from-wm/"><u>Cutting Down Gaming Power Drain From WM</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-navigating-instagram-blocking-basics/"><u>[Updated] In 2024, Navigating Instagram Blocking Basics</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-pathway-to-pristine-recordings-removing-unwanted-noises-for-crystal-clear-sound/"><u>The Pathway to Pristine Recordings Removing Unwanted Noises for Crystal-Clear Sound</u></a></li>
<li><a href="https://win11.techidaily.com/clear-communication-how-to-test-microphone-on-windows-pre-call/"><u>Clear Communication: How to Test Microphone on Windows Pre-Call</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rejuvenating-stuck-windows-based-itunes/"><u>Strategies for Rejuvenating Stuck Windows-Based iTunes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-a-comprehensive-look-at-editing-and-uploading-virtual-reality-videos-to-youtube/"><u>[Updated] In 2024, A Comprehensive Look at Editing and Uploading Virtual Reality Videos to YouTube</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-stunning-highlights-top-video-editing-tools-for-desktop-and-mobile-for-2024/"><u>Create Stunning Highlights Top Video Editing Tools for Desktop and Mobile for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-zoom-obstacles-stop-code-1132-issues/"><u>Avoid Windows Zoom Obstacles: Stop Code 1132 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-devices-in-sleep-mode-of-win11-pc/"><u>Resurrecting Devices in Sleep Mode of Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-pc-mysteries-a-step-by-step-guide-to-error-code-management-in-command-prompt/"><u>Unraveling PC Mysteries: A Step-by-Step Guide to Error Code Management in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-alter-mouse-trail-and-size-on-win11/"><u>Step-by-Step: Alter Mouse Trail & Size on Win11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-making-money-on-youtube-a-beginners-revenue-roadmap/"><u>In 2024, Making Money on YouTube  A Beginner's Revenue Roadmap</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-windows-update-failure-code-xc004f050/"><u>Reverse Windows Update Failure Code XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-compatibility-of-brightness-controls-via-fn-key-win-11/"><u>Restoring Compatibility of Brightness Controls via Fn Key Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-display-technology-an-in-depth-exploration-of-windows-11s-hdr/"><u>Reimagining Display Technology: An In-Depth Exploration of Windows 11'S HDR</u></a></li>
<li><a href="https://win11.techidaily.com/compre-written-for-pc-performance-metrics/"><u>Compre Written for PC Performance Metrics</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-social-media-screen-recorder-app-mobile-windows-mac/"><u>2024 Approved  Social Media Screen Recorder App (Mobile, Windows, Mac)</u></a></li>
<li><a href="https://win11.techidaily.com/1719354508470-fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools.</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-n-a-comparative-study-for-it-pros/"><u>Unveiling Windows N: A Comparative Study for IT Pros</u></a></li>
<li><a href="https://win11.techidaily.com/roblox-error-403-resolving-access-denied-in-win/"><u>Roblox Error 403: Resolving Access Denied in Win</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-design-best-practices-for-engaging-youtube-thumbnails-for-2024/"><u>[New] Design Best Practices for Engaging YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/triumph-over-failed-detection-driver-of-amd-in-wndows-os/"><u>Triumph over Failed Detection Driver of AMD in Wndows OS</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-zen-in-your-screen-time-exploring-the-most-calming-digital-spaces/"><u>New 2024 Approved Zen in Your Screen Time Exploring the Most Calming Digital Spaces</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-1110s-d3d11-gpu-woes-to-fixable-errors/"><u>Simplifying Windows 11/10'S D3D11 GPU Woes to Fixable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-to-connect-to-a-network/"><u>Navigating Windows to Connect to a Network</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-sound-in-obs-studio-resolving-no-audio-on-win-11/"><u>Amplify Sound in OBS Studio - Resolving No Audio on Win 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-legacy-boot-configurations/"><u>Reinstating Legacy Boot Configurations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-fighting-on-the-go-nintendos-best-switch-fighters/"><u>[Updated] Fighting on the Go  Nintendo's Best Switch Fighters</u></a></li>
<li><a href="https://win11.techidaily.com/three-simplified-steps-for-customizing-win11-ui/"><u>Three Simplified Steps for Customizing Win11 UI</u></a></li>
<li><a href="https://video-capture.techidaily.com/stepwise-process-for-high-quality-screen-captures-from-dell/"><u>Stepwise Process for High-Quality Screen Captures From Dell</u></a></li>
<li><a href="https://win11.techidaily.com/clashing-cybersecurity-the-case-against-multiple-antiviruses-on-windows/"><u>Clashing Cybersecurity: The Case Against Multiple Antiviruses on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-services-console-a-list-of-7-restoration-techniques/"><u>Reviving a Dormant Services Console: A List of 7 Restoration Techniques</u></a></li>
</ul></div>
