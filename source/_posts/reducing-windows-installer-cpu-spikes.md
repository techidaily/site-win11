---
title: Reducing Windows Installer CPU Spikes
date: 2024-08-16T00:29:28.812Z
updated: 2024-08-17T00:29:28.812Z
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The troubleshooter will now run and attempt to fix any Windows Update issues. After the troubleshooter finishes its scan and fixes any problems, see if it solves your problem.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 4\. Restart the Windows Update Service

 Another solution is to restart Windows Update. This will reset the Windows Update settings and possibly fix any issues causing the high CPU usage. Here's how to do it:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **services.msc** in the dialog box and hit Enter. This will open the Services console.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Restart** from the menu.  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-update-service.jpg)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
5. If a pop-up menu asks for permission, click **Continue**.
6. After deleting the Software Distribution folder, you will need to restart the services you stopped previously. For this, launch the elevated command prompt again and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now close the Command Prompt window and restart your computer. Now check if the Windows Modules Installer Worker process still consumes CPU power.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Try Some Generic Windows Fixes

 Aside from the solutions above, there are some generic fixes you can try to reduce high CPU usage. This includes [disabling unnecessary startup programs](https://www.makeuseof.com/windows-11-disable-startup-programs/) and [repairing corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/). If you have downloaded any third-party programs, uninstall them and check if that helps.

 In addition, check if you have installed any updates recently. Corrupted or incompatible updates can cause high CPU usage issues. If the problem persists after performing these steps, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/).

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-photo-cinematic-conversions-sonic-enhancements/"><u>[Updated] 2024 Approved  Photo Cinematic Conversions  Sonic Enhancements</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-the-watchers-workshop-advanced-guide-to-live-tv-broadcasting-via-windows-pc/"><u>2024 Approved  The Watcher's Workshop  Advanced Guide to Live TV Broadcasting via Windows PC</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/aerial-visionaries-revealed-detailed-dji-phantom-4-study/"><u>Aerial Visionaries Revealed  Detailed DJI Phantom 4 Study</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-motorola-moto-g84-5g-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Motorola Moto G84 5G Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-back-into-disconnected-adapters-a-six-step-guide-on-winos/"><u>Breathing Life Back Into Disconnected Adapters: A Six-Step Guide on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-apple-and-windows-calendars-a-comprehensive-guide/"><u>Bridging Apple and Windows Calendars: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-the-seven-timeless-windows-features-of-11/"><u>Bridging Generations: The Seven Timeless Windows Features of 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-worlds-windows-meets-kali-linux/"><u>Bridging Worlds: Windows Meets Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-steam-game-icons-quickly/"><u>Bring Back Missing Steam Game Icons Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-frozen-startup-screen-in-win-lol/"><u>Bypassing Frozen Startup Screen in Win: LOL</u></a></li>
<li><a href="https://win11.techidaily.com/changing-lockout-duration-for-unsuccessful-login-events/"><u>Changing Lockout Duration for Unsuccessful Login Events</u></a></li>
<li><a href="https://win11.techidaily.com/changing-the-time-before-next-login-attempt-on-failure/"><u>Changing the Time Before Next Login Attempt on Failure</u></a></li>
<li><a href="https://win11.techidaily.com/cheap-bargains-come-with-hidden-risks-for-windows-users/"><u>Cheap Bargains Come with Hidden Risks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/chromium-and-windows-11-the-ultimate-synchronization-guide/"><u>Chromium & Windows 11: The Ultimate Synchronization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/chromium-setup-for-windows-11-essential-guide/"><u>Chromium Setup for Windows 11: Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-clutter-experience-unadorned-windows-11/"><u>Clear the Clutter: Experience Unadorned Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearer-focus-utilizing-photos-app-background-blur-in-windows-11/"><u>Clearer Focus: Utilizing Photos App Background Blur in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-forbidden-errors-in-windows-os/"><u>Clearing Forbidden Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-confusion-correcting-windows-11-mails-html-messages/"><u>Clearing the Confusion: Correcting Windows 11 Mail's HTML Messages</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-session-verification-failure-on-your-steam-pc/"><u>Clearing Up Session Verification Failure on Your Steam PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-error-31-restoring-seamless-internet-access/"><u>Clearing Up WIN Error 31: Restoring Seamless Internet Access</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-windows-0x80072af9-bug/"><u>Clearing Up Windows 0X80072AF9 Bug</u></a></li>
<li><a href="https://win11.techidaily.com/combat-strategies-for-unresponsive-windows-notepad/"><u>Combat Strategies for Unresponsive Windows Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/combating-insufficient-usb-controller-support/"><u>Combating Insufficient USB Controller Support</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/fifas-favorite-footage-charted-on-youtube/"><u>FIFA's Favorite Footage  Charted on YouTube</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-oppo-a78-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Oppo A78 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-honor-100-pro-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Honor 100 Pro Phone FRP Lock</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-perfect-pitch-perfection-the-top-7-apps-to-change-your-voice-online/"><u>In 2024, Perfect Pitch Perfection  The Top 7 Apps to Change Your Voice Online</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-samsung-galaxy-xcover-7-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Samsung Galaxy XCover 7</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlock-your-presentation-potential-with-these-high-quality-templates/"><u>In 2024, Unlock Your Presentation Potential with These High-Quality Templates</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-vivo-y36-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Vivo Y36? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/is-your-local-rank-tracker-free-by-link-assistant-rank-tracker-local-rankings-local-rankings/"><u>Is your local Rank Tracker free?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolve-no-power-situations-in-roku-televisions-with-ease/"><u>Resolve No Power Situations in Roku Televisions with Ease</u></a></li>
<li><a href="https://android-frp.techidaily.com/samsung-galaxy-a14-4g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Samsung Galaxy A14 4G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/the-core-elements-of-kinetic-visual-storytelling/"><u>The Core Elements of Kinetic Visual Storytelling</u></a></li>
</ul></div>
