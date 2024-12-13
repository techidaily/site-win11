---
title: "Win11 Storage Cleanup: Removing Microsoft App"
date: 2024-12-06T19:00:58.494Z
updated: 2024-12-12T19:00:22.604Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Storage Cleanup: Removing Microsoft App"
excerpt: "This Article Describes Win11 Storage Cleanup: Removing Microsoft App"
keywords: Win11 Space Clear,Win11 Disk Clean,Remove Win11 Apps,Free Win11 Memory,Optimize Win11 Storage,Delete Windows Apps,Streamline Win11 Files
thumbnail: https://thmb.techidaily.com/1b6976dc536a482a8440b6155a5c6ffdb602672c280e778006363b18d82c63d3.jpg
---

## Win11 Storage Cleanup: Removing Microsoft App

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-from-conversation-to-text-mastering-googles-document-feature/"><u>[New] In 2024, From Conversation to Text Mastering Google's Document Feature</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-bluetooth-speaker-usability-volume-control-restored/"><u>Enhancing Windows Bluetooth Speaker Usability: Volume Control Restored</u></a></li>
<li><a href="https://win11.techidaily.com/getting-your-windows-media-player-running/"><u>Getting Your Windows Media Player Running</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-prevent-your-computers-speaker-drivers-from-causing-high-cpu-consumption-on-windows/"><u>How to Prevent Your Computer's Speaker Drivers From Causing High CPU Consumption on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ifas-hottest-laptops-unveiled/"><u>IFA's Hottest Laptops Unveiled!</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-integrate-srt-into-windowsmacos-operations/"><u>In 2024, Integrate SRT Into Windows/macOS Operations</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-solutions-to-spy-on-apple-iphone-15-plus-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>In 2024, Solutions to Spy on Apple iPhone 15 Plus with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What are Location Permissions Life360 On HTC U23 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-life-into-windows-11-display-with-dynamic-walls-technique/"><u>Infuse Life Into Windows 11 Display With Dynamic Walls Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-system-enough-to-welcome-windows-11/"><u>Is Your System Enough to Welcome Windows 11?</u></a></li>
<li><a href="https://win11.techidaily.com/old-hardware-new-horizons-reviving-pcs-with-windows-11-to-go-and-rufus/"><u>Old Hardware, New Horizons - Reviving PCs with Windows 11 To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/override-non-met-requirements-alert-in-win-11/"><u>Override Non-Met Requirements Alert in Win 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-y27-4g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo Y27 4G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-microsoft-store-error-on-xbox-app/"><u>Steps to Tackle Microsoft Store Error on Xbox App</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-lag-problems-steps-to-enhance-your-street-fighter-eb-experience/"><u>Troubleshooting Lag Problems - Steps to Enhance Your Street Fighter Eb Experience</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/understanding-key-phrases-a-beginners-journey-through-latin-american-vernaculars/"><u>Understanding Key Phrases: A Beginner's Journey Through Latin American Vernaculars</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-and-remedying-windows-1011-update-errors-0xc1900101/"><u>Unpacking & Remedying Windows 10/11 Update Errors (0xC1900101)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-process-of-switching-windows-terminals-attentive-state/"><u>Unveiling the Process of Switching Windows Terminal's Attentive State</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-ricoh-printer-drivers-available-for-free-download-and-windows-installation/"><u>Updated Ricoh Printer Drivers Available for Free Download and Windows Installation</u></a></li>
</ul></div>

