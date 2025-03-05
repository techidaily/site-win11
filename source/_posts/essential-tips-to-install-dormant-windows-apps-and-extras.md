---
title: Essential Tips to Install Dormant Windows Apps & Extras
date: 2025-02-28T20:01:45.542Z
updated: 2025-03-04T22:26:15.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips to Install Dormant Windows Apps & Extras
excerpt: This Article Describes Essential Tips to Install Dormant Windows Apps & Extras
keywords: Dormant Window Use,App Install Guide,Extra Window Features,App Enhancement Steps,Quick Window Setup,Efficient Windows Extras,Simplify Window Extras
thumbnail: https://thmb.techidaily.com/a7150b4ff2ea7550c12f390526178357d28d5879ccd1eca0b9ed1b9c559e12d9.jpg
---

## Essential Tips to Install Dormant Windows Apps & Extras

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the[DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the[ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best[ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  

![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try[installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.

4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.

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
<li><a href="https://fox-links.techidaily.com/new-in-2024-crafting-the-best-video-aspect-ratio-experience/"><u>[New] In 2024, Crafting the Best Video Aspect Ratio Experience</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-the-digital-moguls-guide-to-vimeo-earnings-mastery/"><u>[New] In 2024, The Digital Mogul's Guide to Vimeo Earnings Mastery</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-mastering-sound-communication-on-whatsapp-for-2024/"><u>[New] Mastering Sound Communication on WhatsApp for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-simplifying-the-process-recording-on-xbox-one/"><u>[Updated] 2024 Approved Simplifying the Process Recording on Xbox One</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-perfecting-virtual-sessions-best-free-and-paid-zoom-transcribing-tools/"><u>[Updated] Perfecting Virtual Sessions Best Free & Paid Zoom Transcribing Tools</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/boosting-bots-top-9-reasons-for-choosing-chatgpt-plus/"><u>Boosting Bots: Top 9 Reasons for Choosing ChatGPT Plus</u></a></li>
<li><a href="https://fox-pages.techidaily.com/comment-reproduire-facilement-le-disque-de-debut-pour-windows-serveur-version-2003-2008-ou-2012-sans-refaire-linstallation/"><u>Comment Reproduire Facilement Le Disque De Début Pour Windows Serveur Version 2003, 2008 Ou 2012 Sans Refaire L'Installation</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-operation-failure-error-in-win-1011/"><u>Eradicating Operation Failure Error in Win 10/11</u></a></li>
<li><a href="https://article-tips.techidaily.com/highlighting-key-developments-in-windows-movie-maker-releases/"><u>Highlighting Key Developments in Windows Movie Maker Releases</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-out-of-arrow-chaos-in-windows-pcs/"><u>Navigate Out of Arrow Chaos in Windows PCs</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-macos-11-big-sur-system-details/"><u>Navigating MacOS 11 Big Sur - System Details</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lsassexe-issue-a-step-by-step-guide/"><u>Overcoming 'lsass.exe' Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-app-camera-access-disputes-error-a00f4243/"><u>Overcoming Windows App Camera Access Disputes (Error A00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-windows-11-to-classic-folder-visibility/"><u>Resetting Windows 11 to Classic Folder Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-virtual-setup-installing-win11-on-workstation-17/"><u>Streamlining Virtual Setup: Installing Win11 on Workstation 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-10-best-error-lookup-tools-for-windows/"><u>The 10 Best Error Lookup Tools for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-enigmatic-personal-space-in-win-how-to-engage-with-private-character-viewer/"><u>The Enigmatic Personal Space in Win: How to Engage with Private Character Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-windows-automatic-images-on-screen-lock/"><u>Turning On/Off Windows' Automatic Images on Screen Lock</u></a></li>
<li><a href="https://win11.techidaily.com/updating-your-spotlight-theme-a-users-guide-in-windows/"><u>Updating Your Spotlight Theme: A User's Guide in Windows</u></a></li>
</ul></div>

