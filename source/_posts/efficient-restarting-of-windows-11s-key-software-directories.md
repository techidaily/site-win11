---
title: Efficient Restarting of Windows 11'S Key Software Directories
date: 2024-09-18T18:44:28.178Z
updated: 2024-09-21T23:48:00.381Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Restarting of Windows 11'S Key Software Directories
excerpt: This Article Describes Efficient Restarting of Windows 11'S Key Software Directories
keywords: Win11 Software Startup,Windows 11 Reset Procedures,OS Reboot Management Tools,Efficient OS Restart Guide,Windows Update Resets Quickly,Directories for Windows Updates,Key Windows Firmware Fixes
thumbnail: https://thmb.techidaily.com/380105e59c8959c0073d444abec887193c4b497adc4a29c490c9f0b91ceeacb3.jpg
---

## Efficient Restarting of Windows 11'S Key Software Directories

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  
`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915865/19272" target="_top" id="1915865">
  <img src="//a.impactradius-go.com/display-ad/19272-1915865" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915865/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/updated-conquer-gopro-time-lapse-video-creation-like-a-pro/"><u>[Updated] Conquer GoPro Time Lapse Video Creation Like a Pro</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-discovering-the-best-in-class-9-microphone-recorders-reviewed/"><u>[Updated] Discovering the Best in Class 9 Microphone Recorders Reviewed</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-metaverse-contrasted-with-multimetaverse-a-detailed-breakdown-in-depth-guide-for-2024/"><u>[Updated] Metaverse Contrasted with MultiMetaverse A Detailed Breakdown (In-Depth Guide) for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-unrestricted-data-saver-solutions/"><u>[Updated] Top Unrestricted Data Saver Solutions</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-macs-top-5-mkv-decoder-software/"><u>2024 Approved Mac's Top 5 MKV Decoder Software</u></a></li>
<li><a href="https://win-bytes.techidaily.com/descargas-sin-costo-transformar-archivos-de-audiovideo-flac-a-formatos-mkv-con-el-servicio-online-mas-eficiente/"><u>Descargas Sin Costo: Transformar Archivos De Audio/Video FLAC a Formatos MKV Con El Servicio Online Más Eficiente</u></a></li>
<li><a href="https://win11.techidaily.com/enigmatic-toolbars-windows-11s-invisible-commands/"><u>Enigmatic Toolbars: Windows 11’S Invisible Commands</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-infinix-note-30-vip-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Infinix Note 30 VIP Phones</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-error-code-0xc00ce556-a-guide/"><u>Resolving Windows' Error Code 0xC00CE556: A Guide</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-honor-x50-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Honor X50 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unleashing-performance-how-the-ryzen-9-9950x-eclipses-core-i9-14900k-by-18-while-maintaining-a-slender-power-footprint/"><u>Unleashing Performance: How the Ryzen 9 9950X Eclipses Core I9-14900K by 18% While Maintaining a Slender Power Footprint</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-microphone-settings-on-windows-os/"><u>Unveiling Microphone Settings on Windows OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    