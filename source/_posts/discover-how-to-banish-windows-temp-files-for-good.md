---
title: Discover How to Banish Windows Temp Files for Good
date: 2024-09-27T22:40:53.360Z
updated: 2024-09-28T18:04:21.817Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discover How to Banish Windows Temp Files for Good
excerpt: This Article Describes Discover How to Banish Windows Temp Files for Good
keywords: Remove Temp Files in Windows,Delete Windows Temporary Folder,Clear Windows Cache Safely,Eradicate Windows Tmp Files,Optimize Windows Temp Storage,Eliminate Windows Temp Space,Purge Windows System Cache
thumbnail: https://thmb.techidaily.com/8728071c55cb4a9d737d3c276cbce71523d45848bd43ebfc7e5000f0a5d34387.jpg
---

## Discover How to Banish Windows Temp Files for Good

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-fps-fanatics-compendium-selecting-superior-extensions/"><u>[New] FPS Fanatics' Compendium Selecting Superior Extensions</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-avoiding-youtubes-controversial-scrutiny/"><u>[New] In 2024, Avoiding YouTube's Controversial Scrutiny</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-dive-deep-with-these-6-extraordinary-metaverse-models-for-2024/"><u>[Updated] Dive Deep with These 6 Extraordinary Metaverse Models for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-hear-got-music-top-sites-to-download-ringtones-for-2024/"><u>[Updated] Hear GoT Music - Top Sites to Download Ringtones for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instatilecraft-create-impressive-androidplusios-vids/"><u>[Updated] In 2024, InstaTilecraft Create Impressive Android+iOS Vids</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-prime-collection-of-effortless-phone-apps/"><u>[Updated] Prime Collection of Effortless Phone Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-x90s-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo X90S by Name | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-display-with-best-time-clock-screen-savers/"><u>Enhance PC Display with Best Time Clock Screen Savers</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-nubia-red-magic-8s-pro-frp-by-drfone-android/"><u>How Can We Bypass Nubia Red Magic 8S Pro FRP?</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-masterpiece-in-motion-capture-sonys-x1000-action-gear/"><u>In 2024, Masterpiece in Motion Capture Sony's X1000 Action Gear</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remediation-for-elusive-obs-studio-issue-on-win-11-pcs/"><u>Swift Remediation for Elusive OBS Studio Issue on Win 11 PCs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-timepiece-technology-discover-how-chatgpt-enhances-smartwatch-capabilities/"><u>Transforming Timepiece Technology: Discover How ChatGPT Enhances Smartwatch Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://win11.techidaily.com/unyielding-security-seven-ways-to-shield-your-system/"><u>Unyielding Security: Seven Ways to Shield Your System</u></a></li>
<li><a href="https://win11.techidaily.com/windows-define-custom-idle-timeframe/"><u>Windows: Define Custom Idle Timeframe</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    