---
title: Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue
date: 2024-06-25T11:33:18.864Z
updated: 2024-06-26T11:33:18.864Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue
excerpt: This Article Describes Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue
keywords: MsVCR120dll Fix Tips,DLL Deficiency Solutions,Overcoming MSVCR120dll,Msvcrt Trick Guide,DLL Error Handling,CRT120dll Hacks,MsVCR120dll Remedies
thumbnail: https://thmb.techidaily.com/69d60ad1b0674fb9a6dcacd9cfd5c9b2973dbd0d026e48a10d4a2c1cd89022d5.jpg
---

## Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue

 Do you keep getting an error that reads “The program can’t start because MSVCR120.dll is missing from your computer” while opening apps or programs on Windows? This can happen due to a variety of reasons, including a damaged Microsoft Visual C++ Redistributable package, corrupt system files, malware infection, and more.

 Whatever the cause, fixing the msvcr120.dll missing error on Windows isn’t too difficult. Here are the solutions you need to try.

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

## Restore the Missing the Msvcr120.dll File on Windows

 The msvcr120.dll missing error can prevent you from using your favorite apps and programs and waste your time. Fortunately, as with most DLL errors, “The program can’t start because MSVCR120.dll is missing from your computer” can be easily resolved if you apply the above-mentioned fixes.

 If none of the troubleshooting tips help, you can consider resetting Windows to its default state as your last option. The good news is that you can reset Windows without losing any of your personal data or files.

 Whatever the cause, fixing the msvcr120.dll missing error on Windows isn’t too difficult. Here are the solutions you need to try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-issues/"><u>Navigating Through Windows 10/11'S Recycle Bin Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-slow-printer-on-windows/"><u>How to Fix a Slow Printer on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-solid-state-drive-speed-on-windows-via-ssd-fresh/"><u>Elevate Solid State Drive Speed on Windows via SSD Fresh</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-typing-speed-7-latency-fixes-revealed/"><u>Enhance Windows 11 Typing Speed: 7 Latency Fixes Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-and-resolve-windows-error-code-0xc00000f-quickly/"><u>Avoid and Resolve Windows Error Code: 0Xc00000f Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-folder-context-menus-on-windows-11/"><u>Enhancing Folder Context Menus on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-purging-partitions-on-your-win-os/"><u>Mastering the Art of Purging Partitions on Your Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-infinix-note-30-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Infinix Note 30 Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-14-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 14 Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-high-def-odyssey-of-youtubes-twitter-vids/"><u>In 2024, The High-Def Odyssey of YouTube's Twitter Vids</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-essential-conversion-blueprint-for-shorts-to-mp4/"><u>In 2024, The Essential Conversion Blueprint for Shorts to MP4</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-elegant-music-palette-for-online-vlog-production/"><u>Updated Elegant Music Palette for Online Vlog Production</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-mastering-the-art-of-video-clarity-with-version-22-vce/"><u>[New] 2024 Approved  Mastering the Art of Video Clarity with Version 2.2 VCE</u></a></li>
<li><a href="https://youtube-web.techidaily.com/iscal-landmarks-understanding-mr-beasts-financial-growth-for-2024/"><u>[New] Fiscal Landmarks  Understanding Mr. Beast’s Financial Growth for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-precision-camera-mount-for-optimal-field-recordings/"><u>In 2024, Precision Camera Mount for Optimal Field Recordings</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-access-tons-of-free-vocal-textures-for-2024/"><u>[Updated] Access Tons of Free Vocal Textures for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>