---
title: Troubleshooting High CPU Costs From WMI Worker
date: 2024-11-24T18:40:29.228Z
updated: 2024-11-27T16:19:05.773Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting High CPU Costs From WMI Worker
excerpt: This Article Describes Troubleshooting High CPU Costs From WMI Worker
keywords: Low CPU Use,Optimize WMI,Reduce Worker Cost,Manage WMI Power,Minimize WMI Expense,Efficient System Monitoring,Control WMI Resource
thumbnail: https://thmb.techidaily.com/4abc1e0d974f64940dfb669b21c754808ce4ab1e9a63c263741b581b4fbcec72.jpg
---

## Troubleshooting High CPU Costs From WMI Worker

 If your computer is heating up and the CPU fan is running loudly, it could mean there is an issue with the Windows Modules Installer Worker process. This process is part of the operating system and handles Windows updates. In some cases, it leads to slow speeds and even system crashes due to high CPU usage.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Give It Some Time

 If your computer's "Windows Modules Installer Worker" process is using a lot of CPU power, it means that Windows is busy installing updates or doing system maintenance in the background. These tasks may take a few minutes to complete, and the CPU usage should go back to normal afterward.

 So if you're not in a hurry, give it some time and let it finishes before trying anything else.

## 2\. Restart Your Computer

 If there is no ongoing update process or system maintenance, and CPU usage is still abnormally high, restart your computer. This will kill all running programs, including "Windows Modules Installer Worker" and any other process that might be causing the issue.

 To restart your computer, open the **Start** menu or hit the **Windows** key. Select the **Power** icon and click **Restart** from the menu. Once your computer restarts, see if CPU usage is back to normal.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The troubleshooter will now run and attempt to fix any Windows Update issues. After the troubleshooter finishes its scan and fixes any problems, see if it solves your problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Try Some Generic Windows Fixes

 Aside from the solutions above, there are some generic fixes you can try to reduce high CPU usage. This includes [disabling unnecessary startup programs](https://www.makeuseof.com/windows-11-disable-startup-programs/) and [repairing corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/). If you have downloaded any third-party programs, uninstall them and check if that helps.

 In addition, check if you have installed any updates recently. Corrupted or incompatible updates can cause high CPU usage issues. If the problem persists after performing these steps, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/).

## Optimizing High CPU Usage on Windows

 If Windows Modules Installer Worker is using too much CPU power, you now have solutions to try. Although this process usually utilizes computer resources while installing updates and shouldn't create issues, if you observe that it is using excessive CPU power for an extended period, you can try deactivating services, deleting files from the SoftwareDistribution folder, and implementing common fixes.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-decision-making-in-the-workplace-a-neurological-approach-to-efficacy-and-ethics/"><u>[New] 2024 Approved Decision-Making in the Workplace A Neurological Approach to Efficacy and Ethics</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-from-page-to-screen-jujutsu-kaisen-on-tiktok-for-2024/"><u>[New] From Page to Screen Jujutsu Kaisen on TikTok for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-audience-allure-powerful-hashtags-that-transform-youtube-shorts/"><u>[Updated] 2024 Approved Audience Allure Powerful Hashtags That Transform YouTube Shorts</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfecting-your-makeup-mastery/"><u>[Updated] Perfecting Your Makeup Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-copilot-key-in-windows-11-enhance-your-experience/"><u>Decoding Copilot Key in Windows 11 - Enhance Your Experience</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/dvdmacdvdrip/"><u>DVDレンタルサービスからMacへ素晴らしいDVDをダウンロードする簡単方法とおすすめRipソフトの使い方</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-video-wins-essential-ideas-for-vloggers/"><u>In 2024, Quick Video Wins Essential Ideas for Vloggers</u></a></li>
<li><a href="https://win11.techidaily.com/kickstart-windows-11-help-and-support-mechanism/"><u>Kickstart Windows 11 Help & Support Mechanism</u></a></li>
<li><a href="https://extra-hints.techidaily.com/launch-sequence-the-right-moment-for-podcasts/"><u>Launch Sequence The Right Moment for Podcasts</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-server-with-iis-manager/"><u>Master Your Windows Server with IIS Manager</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-common-steam-freeze-during-gaming/"><u>Overcoming Windows 11: Common Steam Freeze During Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/overriding-windows-update-requests/"><u>Overriding Windows Update Requests</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-ethernet-connection-problems-on-windows-10-quickly-and-effectively/"><u>Resolve Ethernet Connection Problems on Windows 10 Quickly and Effectively</u></a></li>
<li><a href="https://win-dash.techidaily.com/simple-solutions-for-troubleshooting-i2c-interface-problems-with-hid-drivers/"><u>Simple Solutions for Troubleshooting I2C Interface Problems with HID Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-geforce-nows-error-code-0xc0f1103f-in-windows/"><u>Steps to Fix GeForce Now's Error Code 0Xc0f1103f in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-no-write-windows-saving-hurdles/"><u>Strategies for Overcoming No Write Windows Saving Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/swift-and-smooth-keyboard-shortcuts-for-3d-artists/"><u>Swift and Smooth: Keyboard Shortcuts for 3D Artists</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-your-digital-steps-in-windows-11/"><u>Tracing Your Digital Steps in Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-iphone-14-pro-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>Unlocking iPhone 14 Pro Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    