---
title: Overcoming Excessive Use of Windows Module Installer
date: 2024-08-16T00:00:40.662Z
updated: 2024-08-17T00:00:40.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Excessive Use of Windows Module Installer
excerpt: This Article Describes Overcoming Excessive Use of Windows Module Installer
keywords: WMI Abuse Reduction,Stop WMI Overuse,Limit WMI Usage,Curbing WMI Dependence,WMI Control Strategies,Curtail Windows Module Installer,Minimize WMI Installations
thumbnail: https://thmb.techidaily.com/0553b37a2d0bfe56c6f7794ae22609d4c46a2b30d090cb5ced8396683e115022.jpg
---

## Overcoming Excessive Use of Windows Module Installer

 If your computer is heating up and the CPU fan is running loudly, it could mean there is an issue with the Windows Modules Installer Worker process. This process is part of the operating system and handles Windows updates. In some cases, it leads to slow speeds and even system crashes due to high CPU usage.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

## 1\. Give It Some Time

 If your computer's "Windows Modules Installer Worker" process is using a lot of CPU power, it means that Windows is busy installing updates or doing system maintenance in the background. These tasks may take a few minutes to complete, and the CPU usage should go back to normal afterward.

 So if you're not in a hurry, give it some time and let it finishes before trying anything else.

## 2\. Restart Your Computer

 If there is no ongoing update process or system maintenance, and CPU usage is still abnormally high, restart your computer. This will kill all running programs, including "Windows Modules Installer Worker" and any other process that might be causing the issue.

 To restart your computer, open the **Start** menu or hit the **Windows** key. Select the **Power** icon and click **Restart** from the menu. Once your computer restarts, see if CPU usage is back to normal.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->

 The troubleshooter will now run and attempt to fix any Windows Update issues. After the troubleshooter finishes its scan and fixes any problems, see if it solves your problem.

## 4\. Restart the Windows Update Service

 Another solution is to restart Windows Update. This will reset the Windows Update settings and possibly fix any issues causing the high CPU usage. Here's how to do it:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **services.msc** in the dialog box and hit Enter. This will open the Services console.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Restart** from the menu.  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-update-service.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the service has been restarted, check if the "Windows Modules Installer Worker" process is still using a lot of CPU power.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Set Windows Update to Manual Mode

 The Windows Modules Installer Worker process sometimes remains active even when there are no updates to install. This usually happens when the Windows Update service is set to Automatic.

 To fix this issue, you can change the Windows Update service to manual mode. This will prevent Windows from running the process all the time and reduce CPU usage.

 To change Windows Update into manual mode, do the following:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Scroll down and right-click on **Windows Update**.
3. From the context menu, select the **Properties** option. You can also double-click on the service to open its Properties window
4. On the **General** tab, set the **Startup type** to **Manual** and click **OK**.  
![Set Windows Update to Manual](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/set-windows-update-to-manual.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
7. Click **Apply** \> **OK** to save your changes.

 After performing the above steps, close the Services window and restart your computer. Check if the "Windows Modules Installer Worker" process is still using CPU resources. Don't forget to enable Windows Update once you're done troubleshooting.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
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



