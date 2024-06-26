---
title: "The Chronometer's Comeback: Recovering Windows Time Service"
date: 2024-06-25T10:24:19.225Z
updated: 2024-06-26T10:24:19.225Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Chronometer's Comeback: Recovering Windows Time Service"
excerpt: "This Article Describes The Chronometer's Comeback: Recovering Windows Time Service"
keywords: Comeback Windows Time,Time Service Restore,Windows Time Repair,ChronoSync in Windows,Reviving TimeService,Timeline Recovery,Windows Time Fixation
thumbnail: https://thmb.techidaily.com/f5fbbf41453d9824bf6879798120e6de2082db27f668f4cb2a72d45c0fe37f64.jpg
---

## The Chronometer's Comeback: Recovering Windows Time Service

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/tailored-approach-installing-and-using-outlook-preview-for-windows-11-users/"><u>Tailored Approach: Installing and Using Outlook Preview for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-error-0x80073cf3-on-marketplace/"><u>Deciphering and Fixing Error 0X80073CF3 on Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-amplification-effects/"><u>Diminish Windows Volume Amplification Effects</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-flight-comrade-copilot-in-ws11/"><u>Restore Your Flight Comrade (Copilot) in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsoft-outlook-errors-on-desktops/"><u>Tackling Microsoft Outlook Errors on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/grasping-group-policies-in-windows-environments/"><u>Grasping Group Policies in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-uac-alerts-a-windows-screenshot-guide/"><u>Capturing UAC Alerts: A Windows ScreenShot Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Tecno Phantom V Flip? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-a59-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on A59 5G</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-audacity-advantage-effective-methods-for-quieting-audio-distractions-for-2024/"><u>The Audacity Advantage Effective Methods for Quieting Audio Distractions for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-maximizing-your-reach-live-360-videos-on-facebook/"><u>[Updated] Maximizing Your Reach  Live 360 Videos on Facebook</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-motion-blur-magic-unlocking-the-power-of-final-cut-pro-for-2024/"><u>Updated Motion Blur Magic Unlocking the Power of Final Cut Pro for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-expert-recommendations-top-5-video-recording-software/"><u>[Updated] In 2024, Expert Recommendations  Top 5 Video Recording Software</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How to Detect and Stop mSpy from Spying on Your Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/top-8-best-video-quality-enhancers-free-and-paid/"><u>Top 8 BEST Video Quality Enhancers Free & Paid</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>