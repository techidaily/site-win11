---
title: "How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge"
date: 2024-07-13T10:23:44.041Z
updated: 2024-07-14T10:23:44.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge"
excerpt: "This Article Describes How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge"
keywords: Secure Windows 11,Advanced MS Defender,Aguard Security Features,Windows Edge Protection,Win11 Security Setup,Advanced Firewall Config,Threat Detection in MS Defender
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
---

## How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge

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
<li><a href="https://win11.techidaily.com/addressing-chrome-downloads-disruptions-in-the-windows-os/"><u>Addressing Chrome Downloads Disruptions in the Windows OS</u></a></li>
<li><a href="https://youtube-web.techidaily.com/astering-the-art-of-crafting-engaging-youtube-screen-closures-for-2024/"><u>[New] Mastering the Art of Crafting Engaging YouTube Screen Closures for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-tray-graphics-windows-resource-indicators-displayed/"><u>Amplify Tray Graphics: Windows Resource Indicators Displayed</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-domain-services-print-problems-in-win11/"><u>Addressing Domain Services Print Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/adapt-window-placement-for-windows-os/"><u>Adapt Window Placement for Windows OS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-sky-high-engagement-50plus-outstanding-tiktok-username-ideas-for-2024/"><u>[Updated] Sky-High Engagement  50+ Outstanding TikTok Username Ideas for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msvcr110dll-disappearance/"><u>Addressing msvcr110.dll Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/augment-context-menu-with-higher-powers/"><u>Augment Context Menu with Higher Powers</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-share-glitches-with-nvidia/"><u>Addressing Windows 11 Share Glitches with NVIDIA</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-asus-rog-phone-7-ultimate-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Asus ROG Phone 7 Ultimate to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-system32-folder-on-windows-11/"><u>Accessing System32 Folder on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adding-visual-disk-space-analyzer-to-windows-explorer-menu/"><u>Adding Visual Disk Space Analyzer to Windows Explorer Menu</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fusion-of-youtube-beats-and-imovie-editing-magic/"><u>[New] 2024 Approved  Fusion of YouTube Beats and iMovie Editing Magic</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-keyword-mastery-the-10-best-online-resources-to-increase-views/"><u>[New] 2024 Approved  Keyword Mastery  The 10 Best Online Resources to Increase Views</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-success-reinstalling-microsofts-pc-manager-in-winxp/"><u>Achieve Success: Reinstalling Microsoft's PC Manager in WinXP</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-passcode-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-edge-how-to-get-rid-of-it-in-w11/"><u>Avoiding Edge: How to Get Rid of It in W11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-windows-11-task-managers-search-functionality/"><u>Activate Windows 11 Task Manager's Search Functionality</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/fcpx-tutorial-image-cropping-made-easy-for-2024/"><u>FCPX Tutorial Image Cropping Made Easy for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ustream-evaluation-find-alternates/"><u>[New] Ustream Evaluation, Find Alternates</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-system-restore-problem-code-0x80780119/"><u>Addressing System Restore Problem: Code 0X80780119</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-stunning-photographic-mosaics/"><u>Mastering Stunning Photographic Mosaics</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-organizing-files-in-win-os-max-156/"><u>Advanced Tips for Organizing Files in Win OS (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-brightness-control-software-for-windows-multiscreen-enthusiasts/"><u>Advanced Brightness Control Software for Windows Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-character-visualization-tool/"><u>Accessing the Character Visualization Tool</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-unexpected-device-access-in-winos/"><u>Addressing Audacity's Unexpected Device Access in WinOS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-techniques-to-purify-your-recordings-in-audacity/"><u>[New] 2024 Approved  Techniques to Purify Your Recordings in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-profile-alerts-on-windows-1011/"><u>Addressing Invalid Profile Alerts on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-virtualization-setting-up-win11-with-vmware-17-player/"><u>Accelerating Virtualization: Setting Up Win11 with VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-epic-games-account-unlock-on-windows/"><u>Addressing Epic Games Account Unlock on Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-understanding-seconds-for-a-20mb-movie/"><u>2024 Approved  Understanding Seconds for a 20MB Movie</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-lava-yuva-2-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Lava Yuva 2 PC | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-elite-6-urban-home-structures-in-minecraft/"><u>[Updated] In 2024, Elite 6 Urban Home Structures in Minecraft</u></a></li>
</ul></div>
