---
title: Getting Out the Windows Store in Win11
date: 2024-11-16T03:12:59.903Z
updated: 2024-11-18T05:28:02.304Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Getting Out the Windows Store in Win11
excerpt: This Article Describes Getting Out the Windows Store in Win11
keywords: Win11 Windows Store Access,Stepping Into Windows Store,Entering Windows Store,Windows Store on Win11,Accessing Win11 Store,Navigate to Windows Store,Installation in Windows Store (Win11)
thumbnail: https://thmb.techidaily.com/0fc1e99290cf59c3605c4bd53329b181e70c2492cf43dd61e625fadd84b42143.jpg
---

## Getting Out the Windows Store in Win11

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://youtube-docs.techidaily.com/ed-crafting-perfect-youtube-music-playlists-via-web-and-mobile-platforms-for-2024/"><u>[Updated] Crafting Perfect YouTube Music Playlists via Web & Mobile Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-brand-yourself-differently-strategies-for-finding-uncommon-names/"><u>[Updated] In 2024, Brand Yourself Differently Strategies for Finding Uncommon Names</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-restoring-classic-photo-viewing-on-the-modern-windows-11/"><u>[Updated] Restoring Classic Photo Viewing on the Modern Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-shortcuts-fast-paste-of-set-text/"><u>Advanced Shortcuts: Fast Paste of Set Text</u></a></li>
<li><a href="https://tech-revival.techidaily.com/cambiar-formatos-de-imagen-animadas-gif-a-video-3gp-online-de-forma-gratuita-con-herramientas-como-movavi/"><u>Cambiar Formatos De Imagen Animadas (GIF) a Video 3GP Online De Forma Gratuita Con Herramientas Como Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-list-of-15-cool-complimentary-windows-11-designs/"><u>Discover the Ultimate List of 15 Cool, Complimentary Windows 11 Designs!</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-windows-temp-file-deletion-guide/"><u>Effortless Windows Temp File Deletion Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y27-5g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y27 5G</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-iphone-12-pro-complete-guide-by-drfone-ios/"><u>In 2024, How To Remove Passcode From iPhone 12 Pro? Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-error-troubleshooting-e84-edition/"><u>Mastering Steam Error Troubleshooting: E84 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-icon-placement/"><u>Regaining Control Over Icon Placement</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-pin-verification-errors-on-w11w10-systems/"><u>Solutions for Fixing PIN Verification Errors on W11/W10 Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-skype-audio-issues-repairing-your-windows-10-microphone-setup/"><u>Solving Skype Audio Issues: Repairing Your Windows 10 Microphone Setup</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-cortana-commands-in-windows-11/"><u>Troubleshooting Non-Functional Cortana Commands in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-computing-experience-best-windows-devices-2024/"><u>Ultimate Computing Experience - Best Windows Devices 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/undead-lore-weaver/"><u>Undead Lore Weaver</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-mysteries-a-guide-to-finding-and-fixing-error-messages-using-commands/"><u>Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-app-migration-from-older-windows-versions/"><u>Unveiling the Art of App Migration From Older Windows Versions</u></a></li>
</ul></div>

