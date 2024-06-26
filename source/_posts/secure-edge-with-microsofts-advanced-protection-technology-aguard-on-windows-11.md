---
title: Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11
date: 2024-06-25T10:10:01.146Z
updated: 2024-06-26T10:10:01.146Z
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

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're[having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
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

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn[how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

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

1. Open Windows PowerShell with admin access. If you need help, see our guide on[how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
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
<li><a href="https://win11.techidaily.com/unlocking-windows-ms-office-erase-error-code-0x80041015/"><u>Unlocking Windows MS Office: Erase Error Code 0X80041015</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-solutions-for-error-0x800704b3-in-windows-11-and-11/"><u>Unlocking Solutions for Error 0X800704B3 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/batch-terminate-programs-in-windows-effortlessly/"><u>Batch Terminate Programs in Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-power-plans-to-default-in-windows/"><u>How to Reset Power Plans to Default in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-samsung-galaxy-m34-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Samsung Galaxy M34 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-tecno-camon-20-pro-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Tecno Camon 20 Pro 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-photo-and-video-streaming-from-android-to-iphone/"><u>[Updated] 2024 Approved  Photo & Video Streaming From Android to iPhone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-8-free-video-trimmer-to-trim-videos-without-watermark/"><u>Updated 2024 Approved 8 Free Video Trimmer to Trim Videos without Watermark</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-creative-edge-pushing-boundaries-in-photography/"><u>[New] 2024 Approved  The Creative Edge  Pushing Boundaries in Photography</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fundamentals-of-e-narrative-creation-for-2024/"><u>Fundamentals of E-Narrative Creation for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-locked-out-of-apple-iphone-13-5-ways-to-get-into-a-locked-apple-iphone-13-by-drfone-ios/"><u>In 2024, Locked Out of Apple iPhone 13? 5 Ways to get into a Locked Apple iPhone 13</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exclusive-symphony-broadcasts/"><u>In 2024, Exclusive Symphony Broadcasts</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-how-to-add-effects-in-premiere-pro-for-2024/"><u>New How to Add Effects in Premiere Pro for 2024</u></a></li>
</ul></div>
