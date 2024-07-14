---
title: Reducing Windows Installer CPU Spikes
date: 2024-07-13T10:04:54.677Z
updated: 2024-07-14T10:04:54.677Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reducing Windows Installer CPU Spikes
excerpt: This Article Describes Reducing Windows Installer CPU Spikes
keywords: Minimize InstallWiz Cpu Peaks,Reduce WinInstaller Power Surge,Optimize Install Wizard CPU Usage,Decrease Windows Installer Load Times,Lower Installer Process Energy Consumption,Control WinInstaller Resource Spikes,Slash Windows Setup Cpu Demand
thumbnail: https://thmb.techidaily.com/2a48b2247fe4fccf62c26b321b73686dd63d342e88315635def6454749492ddb.jpg
---

## Reducing Windows Installer CPU Spikes

 If your computer is heating up and the CPU fan is running loudly, it could mean there is an issue with the Windows Modules Installer Worker process. This process is part of the operating system and handles Windows updates. In some cases, it leads to slow speeds and even system crashes due to high CPU usage.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

## 1\. Give It Some Time

 If your computer's "Windows Modules Installer Worker" process is using a lot of CPU power, it means that Windows is busy installing updates or doing system maintenance in the background. These tasks may take a few minutes to complete, and the CPU usage should go back to normal afterward.

 So if you're not in a hurry, give it some time and let it finishes before trying anything else.

## 2\. Restart Your Computer

 If there is no ongoing update process or system maintenance, and CPU usage is still abnormally high, restart your computer. This will kill all running programs, including "Windows Modules Installer Worker" and any other process that might be causing the issue.

 To restart your computer, open the **Start** menu or hit the **Windows** key. Select the **Power** icon and click **Restart** from the menu. Once your computer restarts, see if CPU usage is back to normal.

## 3\. Run the Windows Update Troubleshooter

 If restarting doesn't work, run the Windows Update troubleshooter. This tool scans for any issues with Windows Update and automatically fixes them, which might solve the "Windows Modules Installer Worker" high CPU usage issue.

 To run the troubleshooter, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **Control Panel** in the dialog box and hit Enter. This will open the Control Panel.
3. Change the Control Panel view to **Large icons** or **Small icons**.
4. Locate and click on the **Troubleshooting** option.  
![Troubleshooting in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooting-in-control-panel.jpg)
5. On the right side, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
6. Click **Run** next to **Windows Update**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 The troubleshooter will now run and attempt to fix any Windows Update issues. After the troubleshooter finishes its scan and fixes any problems, see if it solves your problem.

## 4\. Restart the Windows Update Service

 Another solution is to restart Windows Update. This will reset the Windows Update settings and possibly fix any issues causing the high CPU usage. Here's how to do it:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **services.msc** in the dialog box and hit Enter. This will open the Services console.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Restart** from the menu.  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-update-service.jpg)

 Once the service has been restarted, check if the "Windows Modules Installer Worker" process is still using a lot of CPU power.

## 5\. Set Windows Update to Manual Mode

 The Windows Modules Installer Worker process sometimes remains active even when there are no updates to install. This usually happens when the Windows Update service is set to Automatic.

 To fix this issue, you can change the Windows Update service to manual mode. This will prevent Windows from running the process all the time and reduce CPU usage.

 To change Windows Update into manual mode, do the following:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Scroll down and right-click on **Windows Update**.
3. From the context menu, select the **Properties** option. You can also double-click on the service to open its Properties window
4. On the **General** tab, set the **Startup type** to **Manual** and click **OK**.  
![Set Windows Update to Manual](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/set-windows-update-to-manual.jpg)
5. Next, locate **Windows Modules Installer** in the list of services and repeat the same steps.

 Once done, restart your computer and see if CPU usage has reduced. If not, try the next solution.

## 6\. Disable Windows Update

 If high CPU usage persists, you can disable Windows Update completely. This is not a recommended long-term solution since updates are crucial for security and performance. But if needed, you can disable it for now and check CPU usage.

 To disable Windows Update, do the following.

1. Click on Start and type **Services** in the search box.
2. Select Services from the results list. This will open the Services window.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Stop** from the context menu.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
5. Upon stopping the Windows Update service, double-click on it to open its Properties window.
6. On the **General** tab, click **Startup type** and select **Disabled** from the dropdown.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
7. Click **Apply** \> **OK** to save your changes.

 After performing the above steps, close the Services window and restart your computer. Check if the "Windows Modules Installer Worker" process is still using CPU resources. Don't forget to enable Windows Update once you're done troubleshooting.

## 7\. Clear the SoftwareDistribution Folder

 Another thing you can do is delete the Software Distribution folder. This folder holds temporary files used during Windows updates. However, if there are any corrupt or outdated files in this folder, it might cause high CPU usage.

 In that case, delete the folder and let Windows recreate it. To clear the SoftwareDistribution folder, follow these steps:

1. [Run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In the Command Prompt window, type the following commands and hit Enter after each one:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Upon executing the above commands, open Windows File Explorer and browse to the following location:  
C:\Windows\SoftwareDistribution\
4. In the SoftwareDistribution folder, use **Ctrl + A** to select all contents then delete them.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
5. If a pop-up menu asks for permission, click **Continue**.
6. After deleting the Software Distribution folder, you will need to restart the services you stopped previously. For this, launch the elevated command prompt again and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now close the Command Prompt window and restart your computer. Now check if the Windows Modules Installer Worker process still consumes CPU power.

## 8\. Try Some Generic Windows Fixes

 Aside from the solutions above, there are some generic fixes you can try to reduce high CPU usage. This includes [disabling unnecessary startup programs](https://www.makeuseof.com/windows-11-disable-startup-programs/) and [repairing corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/). If you have downloaded any third-party programs, uninstall them and check if that helps.

 In addition, check if you have installed any updates recently. Corrupted or incompatible updates can cause high CPU usage issues. If the problem persists after performing these steps, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/).

## Optimizing High CPU Usage on Windows

 If Windows Modules Installer Worker is using too much CPU power, you now have solutions to try. Although this process usually utilizes computer resources while installing updates and shouldn't create issues, if you observe that it is using excessive CPU power for an extended period, you can try deactivating services, deleting files from the SoftwareDistribution folder, and implementing common fixes.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/end-of-windows-subsystem-preparing-for-androids-future/"><u>End of Windows Subsystem: Preparing For Android's Future</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-embark-on-your-video-vision-start-your-youtube-channel/"><u>[Updated] Embark on Your Video Vision  Start Your YouTube Channel</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-unleash-your-creativit/"><u>Updated In 2024, Unleash Your Creativit</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsoft-outlook-errors-on-desktops/"><u>Tackling Microsoft Outlook Errors on Desktops</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-checklist-facebook-and-youtube-video-integration/"><u>2024 Approved  The Ultimate Checklist  Facebook & YouTube Video Integration</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-m34-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Samsung Galaxy M34 Phone with Broken Screen</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-find-your-favorite-download-free-slide-show-patterns-today/"><u>In 2024, Find Your Favorite, Download-Free Slide Show Patterns Today</u></a></li>
<li><a href="https://screen-capture.techidaily.com/expert-review-of-bandicams-efficacy-in-multimedia-projects/"><u>Expert Review of Bandicam's Efficacy in Multimedia Projects</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-older-directx-applications-through-dxvk-transformation/"><u>Bolstering Older DirectX Applications Through DXVK Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-win11-powertoys-experience/"><u>Unveiling the Win11 PowerToys Experience</u></a></li>
<li><a href="https://extra-information.techidaily.com/examining-the-economics-pewdiepies-annual-income/"><u>Examining the Economics  PewDiePie's Annual Income</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-effective-techniques-to-resurrect-off-screen-windows-in-windows-11/"><u>6 Effective Techniques to Resurrect Off-Screen Windows in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cpu-age-determination-for-pc-users-8-effective-methods/"><u>CPU Age Determination for PC Users: 8 Effective Methods</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-discovering-the-hottest-templates-for-social-media-vfx/"><u>[Updated] In 2024, Discovering the Hottest Templates for Social Media VFX</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-unleash-your-creativity-canon-video-editing-software-and-tutorials/"><u>Updated 2024 Approved Unleash Your Creativity Canon Video Editing Software and Tutorials</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-in-depth-insights-on-preserving-ps4-gaming-history/"><u>[New] In 2024, In-Depth Insights on Preserving PS4 Gaming History</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-start-experience-no-more-ads-in-w11/"><u>The Ultimate Start Experience: No More Ads in W11</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-impressive-windows-10-sketch-software-lineup/"><u>The Most Impressive Windows 10 Sketch Software Lineup</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-spiritual-command-center-of-windows-11-os/"><u>Unlocking The Spiritual Command Center of Windows 11 OS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-discord-dialogue-perfecting-your-replies/"><u>[New] 2024 Approved  Discord Dialogue  Perfecting Your Replies</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-linux-use-without-wsl/"><u>Uncomplicated Linux Use Without WSL</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-jokegenius-get-the-best-meme-app/"><u>2024 Approved  JokeGenius - Get the Best Meme App</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-savings-black-friday-6e2-win10-forever/"><u>Unmatched Savings: Black Friday - $6E2 (Win10) Forever</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-stalled-win11-license-numbers/"><u>Breathing Life Into Stalled Win11 License Numbers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/gaming-with-style-perfecting-your-steam-footage/"><u>Gaming with Style - Perfecting Your Steam Footage</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-app-install-failure-on-microsofts-marketplace/"><u>Addressing App Install Failure on Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-convert-with-ease-6-top-rated-audio-conversion-software/"><u>2024 Approved Convert with Ease 6 Top-Rated Audio Conversion Software</u></a></li>
<li><a href="https://win11.techidaily.com/synchronize-subtitles-navigating-textual-glitches-with-prime-and-windows-11/"><u>Synchronize Subtitles: Navigating Textual Glitches with Prime & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-windows-update-defeat-error-0x800736cc/"><u>Swiftly Resolving Windows Update: Defeat Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-devices-performance-naturally-with-wintoys/"><u>Accelerate Your Device's Performance Naturally with WinToys</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-widget-personalization-on-windows-11-pcs/"><u>The Beginner's Guide to Widget Personalization on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-utils-for-efficient-gpu-performance-testing/"><u>Top 6 Windows Utils for Efficient GPU Performance Testing</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-honor-play-40c-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Honor Play 40C and Browser | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-premium-downloader-suite-for-vimeo-content/"><u>[Updated] In 2024, Premium Downloader Suite for Vimeo Content</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-9-reasons-to-favor-pc-computing-over-macos/"><u>The Top 9 Reasons to Favor PC Computing Over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-setting-up-permanent-delete-on-your-windows-11-and-11-pcs/"><u>The Ultimate Guide to Setting up Permanent Delete on Your Windows 11 & 11 PCs</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-the-viral-feast-top-15-easy-innovative-tiktok-dishes/"><u>In 2024, The Viral Feast  Top 15 Easy, Innovative TikTok Dishes</u></a></li>
</ul></div>
