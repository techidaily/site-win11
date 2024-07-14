---
title: Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11
date: 2024-07-13T10:16:39.693Z
updated: 2024-07-14T10:16:39.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11
excerpt: This Article Describes Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11
keywords: Secure Edge Tech,Microsoft Aguard,Edge Security,Windows Aguard,Protact Technology,Advanced Protection,Windows 11 Guard
thumbnail: https://thmb.techidaily.com/2b5408cdd9aa5a17f9e7b91e863fefaf73cf6e1aca47c82b58449d867a0d4a44.jpg
---

## Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're [having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on [how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.


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
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-tutorial-extracting-audio-from-vimeo-video-for-2024/"><u>[Updated] Tutorial  Extracting Audio From Vimeo Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-laughter-guaranteed-the-best-meme-generator-apps-for-mobile-devices-for-2024/"><u>New Laughter Guaranteed The Best Meme Generator Apps for Mobile Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-strong-authentication-protocols/"><u>In 2024, Strong Authentication Protocols</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-soundtrack-of-successful-snapchat-stories-for-2024/"><u>[Updated] The Soundtrack of Successful Snapchat Stories for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719359813770-cloud-connected-computers-integrating-files-with-dropboxgoogledrive-in-c/"><u>Cloud-Connected Computers: Integrating Files with Dropbox/GoogleDrive in C</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/cut-to-perfection-editing-video-duration-on-youtube/"><u>Cut to Perfection  Editing Video Duration on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-reasons-users-prefer-older-windows-versions/"><u>7 Key Reasons Users Prefer Older Windows Versions</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-xiaomi-redmi-k70-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Xiaomi Redmi K70 FRP</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-jaunt-vr-immersion/"><u>In 2024, The Ultimate Guide to Jaunt VR Immersion</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Tecno Spark 20 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-screen-commanders-face-off/"><u>[Updated] 2024 Approved  Screen Commanders Face-Off</u></a></li>
<li><a href="https://extra-tips.techidaily.com/alliance-of-creativity-brands-and-youtubes-fusion-for-2024/"><u>Alliance of Creativity  Brands and YouTube's Fusion for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/asy-ways-to-add-music-to-imovie-from-youtube-for-2024/"><u>[New] Easy Ways to Add Music to iMovie From YouTube for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-or-malfunctioning-your-hardware-drivers-with-windows-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>How to identify missing or malfunctioning your hardware drivers with Windows Device Manager on Windows 10 & 7</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-resolving-upgrade-error-in-windows-os/"><u>A Step-By-Step Guide to Resolving Upgrade Error in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-essential-steps-for-clear-ipad-recording-for-2024/"><u>[New] Essential Steps for Clear iPad Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719362389609-determining-cpu-version-on-windows-here-are-8-ways/"><u>Determining CPU Version on Windows – Here Are 8 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-achieving-high-quality-videos-with-your-cellphone-webcam/"><u>[New] Achieving High-Quality Videos with Your Cellphone Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-motorola-moto-g13-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Motorola Moto G13 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-how-to-create-free-photo-collage-frame-in-minutes-in-2024/"><u>Updated How to Create Free Photo Collage Frame in Minutes, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-clear-the-tpm-on-windows-11/"><u>4 Ways to Clear the TPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-a-beginners-approach-to-adjusting-pitch-in-audacity/"><u>Updated In 2024, A Beginners Approach to Adjusting Pitch in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-resolve-virtual-machines-on-windows-11-vmware/"><u>7 Key Steps to Resolve Virtual Machines on Windows 11-VMware</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
</ul></div>
