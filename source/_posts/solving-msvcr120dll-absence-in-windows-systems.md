---
title: Solving MSVCR120.dll Absence in Windows Systems
date: 2024-09-12T09:52:32.716Z
updated: 2024-09-17T01:04:17.844Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving MSVCR120.dll Absence in Windows Systems
excerpt: This Article Describes Solving MSVCR120.dll Absence in Windows Systems
keywords: Fixing `Msvcr120dll` Missing,Remedy MSVCR120 Deficiency,Resolve DLL MSVCR120 Absence,Address Windows MSVCR120 Lack,Cure System MSVCR120 Errors,Tackle Windows `Msvcr120dll` Gap,Rectify `Msvcr120dll` Shortfall
thumbnail: https://thmb.techidaily.com/0fabbd6ca39e068e6ff5a1dc76e09f39c4c023b261fbe4ba782432860cba0bd7.jpg
---

## Solving MSVCR120.dll Absence in Windows Systems

 Do you keep getting an error that reads “The program can’t start because MSVCR120.dll is missing from your computer” while opening apps or programs on Windows? This can happen due to a variety of reasons, including a damaged Microsoft Visual C++ Redistributable package, corrupt system files, malware infection, and more.

 Whatever the cause, fixing the msvcr120.dll missing error on Windows isn’t too difficult. Here are the solutions you need to try.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Repair the Microsoft Visual C++ Redistributable

 The msvcr120.dll file is a component of the Microsoft Visual C++ 2013 Redistributable package. If there are any issues with this package, it may lead to the msvcr120.dll missing error on Windows. You can try repairing the Microsoft Visual C++ 2013 Redistributable package on your PC to see if that fixes the error. Here are the steps for the same.

1. Click the **magnifying icon** on the taskbar or press the **Win + S** keyboard shortcut to access the search menu.
2. Type **control panel** in the search box and select the first result that appears.
3. Use the drop-down menu in the top right corner to change the view type to **Small icons** or **Large icons**.
4. Click on **Programs and Features**.
5. Locate and select the **Microsoft Visual C++ 2013 Redistributable** package on the list.
6. Click the **Change** option at the top.
7. Hit the **Repair** button and wait for the process to complete.  
![Repair the Microsoft Visual C++ Redistributable on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-the-microsoft-visual-c-redistributable-on-windows.jpg)

## 2\. Reinstall Microsoft Visual C++ Redistributable

 If updating the Visual C++ Redistributable package does not help, you can try reinstalling it on your PC. To do so, use these steps:

1. Open up any web browser and visit Microsoft’s website to [download the Visual C++ Redistributable packages](https://www.microsoft.com/en-ph/download/details.aspx?id=40784).
2. Select your preferred language using the drop-down menu and click the **Download** button.
3. Tick the **vcredist\_x64.exe** and **vcredist\_x86.exe** checkboxes and click **Next**.  
![Download the Microsoft Visual C++ Redistributable.png](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/download-the-microsoft-visual-c-redistributable-png.jpg)

 Double-click the downloaded setup file and follow the on-screen prompts to finish the installation process. After that, check if the error occurs again.

 If you are using 64-bit Windows, you can install both vcredist\_x64.exe and vcredist\_x86.exe. However, if you have a 32-bit version of Windows, you should only install vcredist\_x86.exe. You can [tell if the Windows version you are using is 32-bit or 64-bit](https://www.makeuseof.com/tag/4-easy-ways-to-know-if-youre-on-a-64-bit-version-of-windows/) by checking the system information.

## 3\. Copy the Msvcr120.dll From Another Computer

 While troubleshooting the msvcr120.dll missing error, you might stumble upon websites that promise to fix the error through a quick download of the DLL file. However, doing so can be risky, as the file may be infected by malware.

 A safer alternative is to manually copy the msvcr120.dll file from another computer and paste it into the appropriate folder on your computer. You can transfer the msvcr120.dll file from another computer [using nearby sharing on WIndows](https://www.makeuseof.com/how-to-use-nearby-sharing-on-windows-11/) or an external storage device.

 Once you get the msvcr120.dll file, you can paste it into the appropriate folder. If you are using the 64-bit version, you should paste it into **Local Disk (C:) > Windows > System32**. For the 32-bit version, you should paste it into **Local Disk (C:) > Windows > SysWOW64**.

![MSVCR120 in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/msvcr120-in-file-explorer.jpg)

## 4\. Update or Reinstall the Problematic Program

 If you encounter the msvcr120.dll missing error only when launching a specific app or program, it is likely that the program is unable to access the DLL file. You can try updating the problematic program to its most recent version to see if that helps.

 If the error persists even after that, you can consider removing the program completely and installing it again. We have a detailed guide on [different ways to uninstall software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). You can follow any one of the methods outlined there to uninstall the problematic program. Make sure you [eradicate leftovers from the uninstalled program](https://www.makeuseof.com/windows-remove-leftovers-uninstalled-software/) before reinstalling it on your PC.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Re-Register the Msvcr120.dll File

 Re-registering the MSVCR120.dll file on your system refreshes the registration information for the file in the Windows Registry. This can help resolve issues caused by missing or corrupted registry entries that may have led to the error.

 To re-register the msvcr120.dll file on Windows, use these steps:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Type the following command and press **Enter** to unregister the msvcr120.dll file from your system.  
`regsvr32 /u MSVCR120.dll`
4. Paste the following command and press **Enter** to re-register the msvcr120.dll file.  
`regsvr32 MSVCR120.dll`

## 6\. Try Some Generic Fixes to Resolve the Msvcr120.dll Missing Error

 If you are still getting the msvcr120.dll missing error at this point, you can try some of the generic fixes to resolve the error message. Let's go over all of them quickly one by one.

* **Run an SFC Scan:** Problems with your PC's system files can give rise to such errors. [Running the SFC and DISM scans](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) can help you scan your PC for corrupt or damaged system files and repair them.
* **Scan for Malware:** The disappearance of the msvcr120.dll file may be caused by a malware infection. If that seems to be the case, you can [use Microsoft Defender's offline scan to detect and remove any malware](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) from your PC.
* **Update Drivers:** A malfunctioning driver could interfere with your apps and programs and trigger such errors. Hence, it’s a good idea to update the drivers on your PC using a [free driver updater tool](https://www.makeuseof.com/windows-best-free-driver-updaters/).
* **Install Windows Updates:** It’s possible that the error in question is occurring due to a bug within Windows. If that’s the case, [installing pending Windows updates](https://www.makeuseof.com/windows-11-install-updates/) should help fix it.
* **Perform a System Restore:** If the msvcr120.dll missing error has only started appearing recently, you can [use system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state. This will allow you to undo any recent system changes that may have caused the problem.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Restore the Missing the Msvcr120.dll File on Windows

 The msvcr120.dll missing error can prevent you from using your favorite apps and programs and waste your time. Fortunately, as with most DLL errors, “The program can’t start because MSVCR120.dll is missing from your computer” can be easily resolved if you apply the above-mentioned fixes.

 If none of the troubleshooting tips help, you can consider resetting Windows to its default state as your last option. The good news is that you can reset Windows without losing any of your personal data or files.

 Whatever the cause, fixing the msvcr120.dll missing error on Windows isn’t too difficult. Here are the solutions you need to try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-navigating-through-samsungs-digital-picture-editing-app/"><u>[New] In 2024, Navigating Through Samsung's Digital Picture Editing App</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-cutting-edge-video-edits-without-spending-navigate-through-the-8-tools/"><u>[Updated] Cutting-Edge Video Edits Without Spending Navigate Through The 8 Tools</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-the-ideal-set-of-keywords-for-your-youtube-videos/"><u>Crafting the Ideal Set of Keywords for Your Youtube Videos</u></a></li>
<li><a href="https://win11.techidaily.com/direct-to-victory-windows-methods-of-gaming-directories/"><u>Direct to Victory: Windows Methods of Gaming Directories</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-apple-iphone-xr-to-ipod-touch-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Music from Apple iPhone XR to iPod touch | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-conquer-color-chaos-discover-essential-tutorials-and-techniques/"><u>In 2024, Conquer Color Chaos - Discover Essential Tutorials and Techniques</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-nubia-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Nubia FRP Android 10/11/12/13</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-live-production-pros-dilemma-pmix-vs-castpro/"><u>In 2024, Live Production Pros' Dilemma PMix Vs. CastPro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-zte-nubia-flip-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on ZTE Nubia Flip 5G</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-in-setting-up-mstore-apps/"><u>Overcoming Obstacles in Setting Up MSTORE Apps</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-message-0x87e00017-on-microsoft-store/"><u>Resolving Error Message: 0X87E00017 on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-11-icon-size-decline/"><u>Solving Windows 11 Icon Size Decline</u></a></li>
<li><a href="https://win11.techidaily.com/stifling-windows-11-folder-tab-noises/"><u>Stifling Windows 11 Folder Tab Noises</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-error-0x80070141-in-windows-systems/"><u>Strategies to Overcome Error 0X80070141 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-workflow-with-personalized-fn-key-settings/"><u>Streamlining Workflow with Personalized FN Key Settings</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    