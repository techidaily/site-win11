---
title: "Addressing Text Inconsistency: Ms-Resouce Error, Win11"
date: 2024-08-15T23:52:09.029Z
updated: 2024-08-16T23:52:09.029Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Text Inconsistency: Ms-Resouce Error, Win11"
excerpt: "This Article Describes Addressing Text Inconsistency: Ms-Resouce Error, Win11"
keywords: Win11 Error Guide,Address Inconsistent Text,Resource Management Tips,Win11 Installation Fixes,Consistency in Windows,Ms-Resouce Correction Steps,Resolving Win11 Issues
thumbnail: https://thmb.techidaily.com/6193b23bc0e674c0853b0708bb0c2b43a5237bddcffe969ab0d29845fe4343ae.jpg
---

## Addressing Text Inconsistency: Ms-Resouce Error, Win11

 If you have performed an upgrade recently and noticed a weird "ms-resource:Appname/text" entry in the Start Menu, you are not alone. You may also encounter this error when opening a setting or app.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

## 1\. How to Fix the "ms-resource:Appname/Text" Error in the Start Menu

 You can remove the "ms-resource:Appname/Text" entry from the Start Menu by removing the affected application package using PowerShell. Additionally, you can kill the StartMenuExperienceHost.exe process in Task Manager to restart the service.

 Before attempting to remove the app, package, and restart the services, check if you have any Windows updates pending. If you are running a fresh install, try to install all the pending Windows updates. These updates often include bug fixes and may be the only thing you need to do to fix this issue.

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 To check and install Windows updates:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Windows Update** tab.
3. Click on **Check of updates**. Continue to download and install all pending updates.
4. Restart your computer to apply the updates and check if the issue is resolved.

 If the issue persists, you can use PowerShell to remove the affected app package and then restart the associated services to fix the problem.

 To remove the "ms-resource:Appname/Text" entry from the Start Menu:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows** **PowerShell** and select **Run as administrator**.  
![remove holographicsfirstrun app powershell windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-holographicsfirstrun-app-powershell-windows.jpg)
3. In the PowerShell window, type the following command and press **Enter**:  
`Get-AppxPackage -all *HolographicFirstRun* | Remove-AppPackage -AllUsers`

 Once you've run the command, be sure to restart your computer.

1. After the computer restarts, [open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/).
2. Next, open the **Details** tab in Task Manager. On Windows 11, click the three horizontal lines icon to access the details tab.
3. Now you need to locate both **StartMenuExperienceHost.exe** and **Explorer** **.exe**. On Windows 11, you can use the search feature in **Task Manager** to locate the processes.  
![end start menu experience host task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/end-start-menu-experience-host-task-manager.jpg)
4. Right-click on each process and **End Task**.
5. In Task Manager, click **Run new task**. On Windows 10 and older versions, click **File** and select **Run new task**.  
![run new task open tempstate folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-new-task-open-tempstate-folder-file-explorer.jpg)
6. In the **Create new task** dialog, type the following path and click the **Browse** button.  
`%localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy`
7. In the File Explorer window, delete the **TempState** folder.
8. Go back to Task Manager, and click **Run new task**.
9. Type **explorer.exe** and select the **Create this task with administrative privileges** option.

 Once done, give your PC another restart.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 2\. Re-Register Your Microsoft Store Apps

 You can [re-register Microsoft Store apps using PowerShell](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) to stop the error appearing when using Microsoft apps. Doing so should remove any leftover entries showing up in the Start Menu after the update.

 Wait for the process to complete. This may take a few minutes as the command will try to re-register all the apps, including existing ones. Once the process is complete, restart your computer and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check the Microsoft Store for App Updates

 You may see the "ms-resource:Appname/Text" entry if Windows attempted an unsuccessful app installation. To fix the issue, check if an update exists for the app in the Microsoft Store.

 To determine the app name click on the app entry and check if you can find any information about the app. If not, right-click on the app entry in the **Start Menu** and select **Open File Location**.

![view application folder windows 11 run shell apps folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/view-application-folder-windows-11-run-shell-apps-folder.jpg)

 Alternatively, you can view the application directory to view the installed apps. Press **Win + R** to open Run, type **shell:appsfolder**, and click **OK**. It will open the **Applications** folder. Go through the apps to see if you can locate an app named **ms-resource:Appname/Text** or similar to the entry in the Start Menu.

 Once you have the app name, open the Microsoft Store. Search for the app and check if an update exists. Click **Update** to download and install the update. Once installed, restart your computer and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## What if the "Ms-resource:Appname/Text" Error Appears When Launching an App?

 At times, you may encounter this error when opening a built-in Microsoft Store app. In this instance, you can run the Microsoft Store apps troubleshooter to fix the issue. Here are a few additional troubleshooting steps to fix this error when launching an app.

## 4\. Run the Microsoft Store Apps Troubleshooter

![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-run-button-for-the-app-troubleshooter.jpg)

 You can use the built-in Microsoft Store Apps troubleshooter to fix issues with the store apps. Here’s how to do it.

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.
3. Next, click on **Other troubleshooters**.
4. Click the **Run** button for **Windows Store Apps**. Wait for the troubleshooter to launch and follow the on-screen instructions. It will scan your system against the common Microsoft Store app issues. Apply any recommended fixes and restart your computer to see if the issue is resolved.

 If you don’t see a Windows Store App troubleshooter option, you are likely running a newer version of the OS without this option. In this instance, try to repair the Microsoft Store app.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Repair the Microsoft Store App

![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->

 If the Windows Store Apps troubleshooter is missing or didn’t help, try to repair the Microsoft Store App. You can use the built-in repair option to find and fix common issues with the official app store.

 To repair the Microsoft Store app:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab and click on **Installed Apps.**
3. Locate and click the **three-dots** menu beside the **Microsoft Store** app.
4. Select **Advanced Options**.
5. Scroll down to the **Reset** section.
6. Click the **Repair** button, wait for the process to complete, and show a checkmark. If the repair is successful, restart your computer.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Reset the Microsoft Store App

 In addition to performing a repair, you can also reset the Microsoft Store app to resolve common issues with the store apps. You can perform a reset from the Advanced Options section. Before that, run the wsreset.exe tool to clear the store cache to see if that helps.

 To reset the Microsoft Store App cache:

![wsreset.exe command in the Run tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsreset-exe-command.jpg)

1. Press **Win + R** to open the **Run** dialog.
2. Type **wsreset.exe** and click **OK**.

 Still not resolved? Try to [perform a Microsoft Store reset](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). Doing so will delete all app data, and you may need to sign in to your Microsoft account again.

## 6\. Other Troubleshooting Steps You Can Try

 If the issue persists, here are a few additional troubleshooting steps you can follow:

1. **Create a new user account** – Try to [create a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to see if the error exists in the new account. This is a handy workaround for a newly set up Windows computer.
2. **Perform a repair reinstall of Windows 11** – You can reinstall [Windows 11 without deleting your apps and files](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). This is an upgrade reinstall and should fix any issues triggered due to issues with the system files.
3. **Perform a reset** – If an in-place upgrade doesn’t help, consider [performing a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). You can perform a complete reset while choosing to keep your files, but all your apps will be removed.
4. **Clean install** – [Performing a Windows clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) will erase everything on your computer and reinstall Windows 11 from scratch. Make sure to back up important data before attempting a clean install.

## Fixing the "ms-resource:Appname/Text" Error in Windows 11

 Often this entry in the start menu is a ghost entry from an unsuccessful or leftover installation of a Microsoft app. To remove the entry or restore the app, you can re-register the Microsoft app, remove the affected app package or run the Windows Store Apps Troubleshooter.

 If the issue persists, an in-place upgrade, factory reset, or a clean install may be necessary to resolve the issue. This is a time-consuming process, and you may need to set up your computer from scratch.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-maximizing-your-youtube-potential-with-content-partnerships/"><u>[New] 2024 Approved  Maximizing Your YouTube Potential with Content Partnerships</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-securing-footage-techniques-for-obscuring-sensitive-info/"><u>[New] 2024 Approved  Securing Footage  Techniques for Obscuring Sensitive Info</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-elevate-your-storytelling-on-snapchat-with-top-tips/"><u>[New] Elevate Your Storytelling on Snapchat with Top Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prime-17-solutions-for-removing-picture-outlines/"><u>[New] Prime 17 Solutions for Removing Picture Outlines</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-10-stellar-tools-that-amplify-your-videos-youtube-presence/"><u>[Updated] 2024 Approved  10 Stellar Tools That Amplify Your Video's YouTube Presence</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-imaginative-inspirations-for-virtual-explorers-the-best-metaverse-moments/"><u>[Updated] In 2024, Imaginative Inspirations for Virtual Explorers  The Best Metaverse Moments</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-innovative-tactics-to-amplify-game-vids-via-hashtags/"><u>[Updated] Innovative Tactics to Amplify Game Vids via Hashtags</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-best-practices-for-an-immersive-streaming-experience/"><u>2024 Approved  Best Practices for an Immersive Streaming Experience</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-top-15-free-web-based-image-enhancers-2023/"><u>2024 Approved  Top 15 Free Web-Based Image Enhancers 2023</u></a></li>
<li><a href="https://win11.techidaily.com/9-pros-of-modernizing-to-windows-revamped-outlook/"><u>9 Pros of Modernizing to Windows' Revamped Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-workflow-fine-tuning-mouse-clicks/"><u>Accelerate Your Workflow: Fine-Tuning Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-unexpected-device-access-in-winos/"><u>Addressing Audacity's Unexpected Device Access in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-package-malfunctions-in-windows-updates/"><u>Addressing Package Malfunctions in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-failed-logon-wait-duration-settings/"><u>Adjusting Failed Logon Wait Duration Settings</u></a></li>
<li><a href="https://win11.techidaily.com/adopt-wsl-the-easy-way-to-run-linux-commands/"><u>Adopt WSL: The Easy Way to Run Linux Commands</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-for-windowsapps-acquisition/"><u>Advanced Methods for WindowsApps Acquisition</u></a></li>
<li><a href="https://win11.techidaily.com/altering-account-access-in-windows-11-easily/"><u>Altering Account Access in Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-creativity-best-writing-software-for-windows/"><u>Amplify Creativity: Best Writing Software For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/are-some-of-your-keyboard-keys-not-working-heres-how-to-fix-them-on-windows/"><u>Are Some of Your Keyboard Keys Not Working? Here's How to Fix Them on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-devices-performance-with-quick-android-apk-installation-in-windows-11/"><u>Boost Your Device's Performance with Quick Android APK Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-app-opening-top-techniques-for-windows-11/"><u>Boosted App Opening: Top Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-app-aesthetics-with-win11s-automatic-tuning/"><u>Boosting App Aesthetics with Win11's Automatic Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-directx-titles-with-dxvk-on-windows/"><u>Boosting Classic DirectX Titles with DXVK on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-memory-usage-in-windows-without-complications/"><u>Boosting Memory Usage in Windows Without Complications</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-utility-of-windows-11s-initial-interface/"><u>Boosting the Utility of Windows 11'S Initial Interface</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-and-overcome-insufficient-resources-system-issue-effectively/"><u>How to Address and Overcome 'Insufficient Resources' System Issue Effectively</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-xiaomi-civi-3-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Xiaomi Civi 3 Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-a1-5g-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of A1 5G on Windows??</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-securesave-professionals-assessment/"><u>In 2024, SecureSave Professionals' Assessment</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-safe-and-secure-top-10plus-websites-to-download-games-online/"><u>New In 2024, Safe and Secure Top 10+ Websites to Download Games Online</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/postpresence-mastering-photo-and-video-sizing-on-instagram-for-2024/"><u>PostPresence  Mastering Photo and Video Sizing on Instagram for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/spectral-film-reset-guide-for-2024/"><u>Spectral Film Reset Guide for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-steps-to-correct-blue-screen-of-death-bsod-due-to-ndis-drivers/"><u>Troubleshooting Steps to Correct Blue Screen of Death (BSOD) Due to NDIS Drivers</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-infinix-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have Infinix fingerprint</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-honor-x50-gt-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Honor X50 GT Phone Network-Ready</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-do-when-your-automobile-audio-goes-silent/"><u>What to Do When Your Automobile Audio Goes Silent?</u></a></li>
<li><a href="https://win11.techidaily.com/1719245846865-windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance</u></a></li>
<li><a href="https://win11.techidaily.com/1719370951528-xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips!</u></a></li>
</ul></div>
