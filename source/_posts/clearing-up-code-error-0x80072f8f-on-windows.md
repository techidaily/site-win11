---
title: Clearing Up Code Error 0X80072f8f on Windows
date: 2025-02-11T20:32:24.630Z
updated: 2025-02-15T22:02:42.554Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up Code Error 0X80072f8f on Windows
excerpt: This Article Describes Clearing Up Code Error 0X80072f8f on Windows
keywords: Windows Error Fix,Code Debugging Guide,X80072F8F Issue,WinError Troubleshooting,Software Compatibility,OS Update Tips,Programming Error Resolution
thumbnail: https://thmb.techidaily.com/d2f76001c4f2646491c0fc840a81d8218602e492050e0d16896d960da5c49a16.png
---

## Clearing Up Code Error 0X80072f8f on Windows

 The Windows Media Creation Tool prepares installation media for upgrading your PC or creating a USB drive to perform a clean Windows installation. It is the perfect tool to make sure you are using the latest Windows version and is quite easy to use.

 However, there are times when users can run into errors while using the Media Creation Tool. One such error is the error code 0x80072f8f – 0x20000, which appears when users attempt to launch the MediaCreationTool.exe file.

 Below, you will find several effective troubleshooting methods that will help you fix this issue in no time.

## 1\. Run the Media Creation Tool as an Administrator

 Certain programs and processes on Windows operating system need administrative privileges to perform their jobs properly. If they are not allowed these extra permissions, you are likely to run into error codes such as this one.

 So, the first thing that you need to do if you encounter the error code 0x80072f8f - 0x20000 upon attempting to use the Media Creation Tool is to launch the file as an administrator. If insufficient permissions are causing the problem, this should fix it without you having to go through any of the complex troubleshooting methods.

Follow these steps to run the file as administrator:

1. Right-click on the targeted file and select**Run as administrator** from the context menu.  
![Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/run-as-administrator-1.jpg)
2. Click**Yes** in the confirmation prompt and check if the file runs without any issues now.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Yes button in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/user-account-control-yes.jpg)

 If the error persists, it indicates that there is another cause behind it. In that case, proceed with the next method.

## 2\. Use a Different USB Port

 Often, faulty ports cause issues during the creation of the installation media. There are[several ways to test if the USB port is faulty](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) . You can begin by switching to another port and checking if the USB works fine there.

 You can also try using the same USB on another device and see if it works fine there.

## 3\. Modify the Windows Registry

 Making some changes in the Windows Registry to allow Media Creation Tool to run smoothly is another potential fix that you can try.

 Windows Registry is an administrative-level, powerful utility that stores information about the programs and processes of your operating system. The information here is stored as keys and values. You can modify the relevant keys/values to customize the processes of your system, which is exactly what we are going to do in this method.

 However, before you proceed with this method, we highly recommend[creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will help you restore the current state of your system in case anything goes wrong during the process.

When you have created a backup, follow these steps.

1. Press**Win** +**R** to open a Run dialog.
2. Type**regedit** in Run and click**Enter** .  
![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/regedit.jpg)
3. Once you are inside the Registry Editor, navigate to the location mentioned below:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\Auto Update`
4. Right-click in an empty area in the right pane and select**New** \>**DWORD (32-bit) Value** from the context menu.  
![New DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/auto-update-new-dword.jpg)
5. Name this value as**AllowOSUpgrade** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![AllowOSUpgrade value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade.jpg)
6. Double-click on**AllowOSUpgrade** and type**1** under Value data.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade-value-data.jpg)
7. Hit**OK** and close the Registry Editor.

 You can now restart your PC and upon reboot, check if the Media Creation Tool works fine.

## 4\. Delete the Content of the Software Distribution Folder

 Another solution that worked for users was deleting the contents of the Software Distribution folder. This folder contains temporary files that might be interfering with the process of the Media Creation Tool.

 If this scenario is applicable, deleting the contents of the Software Distribution folder by following the steps below should do the trick for you.

1. Launch File Explorer and navigate to the location below:  
`C:\Windows\SoftwareDistribution\Download`  
![Software Distribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/software-distribution-download.jpg)
2. Select all the contents of the Download folder and right-click on them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Click on the**bin icon** in the context menu to delete them.  
![Delete icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/delete-download.jpg)
4. Once you delete the files, type**cmd** in the search area of the taskbar and select**Run as administrator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Type the following command in the Command Prompt window and hit**Enter** .  
`wuauclt.exe /updatenow`  
![wuauclt.exe command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/wuauclt-exe-updatenow.jpg)
6. Then, restart your PC and try launching Media Creation Tool again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Enable Relevant Services

 Programs and processes on the Windows operating system require relevant services to be functioning to work. If any of the relevant services are disabled or corrupt, the program will fail to function.

 For instance, the Windows Update process requires the Windows Update service to run. If the settings of this service are not configured properly, you will fail to install the latest updates.

 Similarly, Media Creation Tool is related to the following services, and they should be working fine for you to use it:

* Windows Update
* Background Intelligent Transfer Service
* Server
* Workstation
* TCP/IP NetBIOS Helper
* IKE and AuthIP IPsec Keying Modules

 In this method, we will make sure that these services are configured accurately, and we will be using the Windows Update service to demonstrate the steps.

1. Open a Run dialog by pressing**Win** +**R keys** .
2. Type**services.msc** in the dialog and hit**Enter** . This should launch Windows Services.
3. In the following window, right-click on the**Windows Update** service and choose**Properties** from the context menu.
4. ![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, change the Startup type to**Automatic** .  
![Startup type as automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/startup-type-automatic.jpg)
6. If the service is stopped, click on the**Start button** and select**Apply** \>**OK** to save the changes.  
![Start button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/start-service-status.jpg)
7. Repeat the same steps for the rest of the above-mentioned services.

 Once done, check if you can run the Media Creation Tool without any issues now.

## 8\. Perform a Clean Boot

 The issue can also arise due to a driver or software conflict within the system. To check if this is the case, you can perform a clean boot to launch the system with a minimal set of drivers and startup programs. If the issue does not appear in this mode, then it implies that a background process or driver is indeed causing the problem. You can then take necessary steps to remove it from the system.

Here is how you can perform a clean boot in Windows:

1. Press the Win + R keys together to open Run.
2. Type msconfig in the text field of Run and click Enter.
3. In the System Configuration window, head over to the**Services** tab and checkmark the box for**Hide all Microsoft services** .  
![Hide all Microsoft services option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-hide-all-msservices.jpg)
4. Click on the**Disable all button** .
5. Now, navigate to the**Startup** tab and click on**Open Task Manager** .  
![Open the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/startup-open-task-manager.jpg)
6. In the Startup tab, right-click on all the items and choose**Disable** .  
![Click on the Disable button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-program.jpg)
7. Once done, close the Task Manager and go back to the System Configuration window.
8. Click**Apply** \>**OK** to save the changes.
9. Finally, restart your computer.

 If the error code 0x80072f8f - 0x20000 is not present after a clean boot, it suggests that the issue was caused by a software or driver conflict. If this situation is applicable, you can either manually remove the recently installed software that you think might be leading to the issue, or[perform a system restore](https://www.makeuseof.com/tag/windows-system-restore-works/) to return to an older functioning state of the system.

## 7\. Disable Your Antivirus

 If you are using a third-party antivirus in Windows, there is a chance that it is blocking the process of Media Creation Tool because of a false alarm. To check if this is the case, you can disable or uninstall your antivirus and then run the Media Creation Tool.

 If the antivirus program is the culprit, then we recommend switching to another similar service for better performance.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Media Creation Tool Error, Now Resolved

 Media Creation Tool is undoubtedly one of the most useful and easy-to-use tools offered by Microsoft for Windows. The troubleshooting methods listed above will hopefully allow you to use it without any issues. If the error appears again, you can reach out to the official Microsoft support team and report the problem to them. Hopefully, they will be able to identify the exact cause of the issue and suggest you a fix accordingly.

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
<li><a href="https://fox-boxes.techidaily.com/updated-video-size-and-seconds-deciphering-20mb-duration-for-2024/"><u>[Updated] Video Size & Seconds Deciphering 20MB Duration for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtube-earnings-unveiled-average-adsense-payments-per-thousand-views/"><u>[Updated] Youtube Earnings Unveiled Average AdSense Payments Per Thousand Views</u></a></li>
<li><a href="https://win11.techidaily.com/crippled-corecrypt-still-stand-not-suddenly-shift/"><u>Crippled CoreCrypt: Still Stand, Not Suddenly Shift</u></a></li>
<li><a href="https://fox-within.techidaily.com/custom-actions-component-enhance-your-app-with-tailored-functionality/"><u>Custom Actions Component: Enhance Your App with Tailored Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/defeating-the-license-end-date-imminent-error/"><u>Defeating the License End Date Imminent Error</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-system-info-exploration/"><u>Efficient Strategies for System Info Exploration</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-up-space-how-to-convert-your-dvds-to-digital-video-files/"><u>Free Up Space How to Convert Your DVDs to Digital Video Files</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-windows-upgrade-hurdle-error-xc004f050/"><u>How to Correct Windows Upgrade Hurdle: Error XC004F050</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-zte-nubia-z60-ultra-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve ZTE Nubia Z60 Ultra Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s24plus-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S24+ Bootloader Easily</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-solved-move-from-infinix-hot-30-5g-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Solved Move from Infinix Hot 30 5G to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/projecting-perfection-integrating-amazons-fire-tv-with-a-projector/"><u>Projecting Perfection: Integrating Amazon's Fire TV with a Projector</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-your-windows-11s-fresh-start-procedure/"><u>Reinstating Your Windows 11'S Fresh Start Procedure</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-rainbow-six-siege-lag-for-better-gaming-experience/"><u>Troubleshooting Rainbow Six Siege Lag for Better Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-most-versatile-drawing-apps-for-windows-11/"><u>Unveiling the Most Versatile Drawing Apps for Windows 11</u></a></li>
</ul></div>

