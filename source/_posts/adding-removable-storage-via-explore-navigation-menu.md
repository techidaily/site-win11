---
title: Adding Removable Storage via Explore Navigation Menu
date: 2024-07-13T11:18:42.689Z
updated: 2024-07-14T11:18:42.689Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding Removable Storage via Explore Navigation Menu
excerpt: This Article Describes Adding Removable Storage via Explore Navigation Menu
keywords: Storage Expansion,Explore Menu Access,Mobile Device Add-On,Data Portability,External SD Utilization,SIM Card Mounting,USB Drive Integration
thumbnail: https://thmb.techidaily.com/633f0a6d177df3d7fb477a15a0804c21edff9926ab23c2607a0458a0d217d945.jpeg
---

## Adding Removable Storage via Explore Navigation Menu

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/ascending-to-top-level-windows-management/"><u>Ascending to Top-Level Windows Management</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-jvm-not-created-a-windows-solution/"><u>Addressing JVM Not Created: A Windows Solution</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-chromes-timeline-error-on-windows-machines/"><u>Aligning Chrome's Timeline Error on Windows Machines</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-step-by-step-expedition-to-youtubes-unseen-layers/"><u>[New] In 2024, A Step-by-Step Expedition to YouTube's Unseen Layers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/discovering-the-10-leading-low-cost-mobile-video-conferencing/"><u>Discovering the 10 Leading Low-Cost, Mobile Video Conferencing</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-nokia-c12-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Nokia C12? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-easy-nft-creation-a-novices-manual/"><u>[New] Mastering Easy NFT Creation  A Novice's Manual</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-craft-compelling-youtube-titles-faster-than-ever/"><u>[Updated] In 2024, Craft Compelling YouTube Titles Faster Than Ever</u></a></li>
<li><a href="https://win11.techidaily.com/adding-directories-to-your-windows-11-quick-access-menu/"><u>Adding Directories to Your Windows 11 Quick Access Menu</u></a></li>
<li><a href="https://win11.techidaily.com/amd-graphics-update-essentials-for-windows-11-users/"><u>AMD Graphics Update Essentials for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x8007000f-on-task-sequences/"><u>Addressing Windows Error 0X8007000f on Task Sequences</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-hdr-mastery-the-complete-sdr-to-hdr-transformation/"><u>[Updated] HDR Mastery  The Complete SDR-to-HDR Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-navigation-methods-without-ls-command/"><u>Advanced Windows Navigation Methods Without LS Command</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-essential-guide-to-blurring-video-borders-in-teams/"><u>The Essential Guide to Blurring Video Borders in Teams</u></a></li>
<li><a href="https://extra-information.techidaily.com/embrace-enhanced-viewing-picture-in-picture-on-ms-edge/"><u>Embrace Enhanced Viewing  Picture-in-Picture on MS Edge</u></a></li>
<li><a href="https://win11.techidaily.com/alert-essential-windows-processes-to-watch-for-malware/"><u>Alert: Essential Windows Processes to Watch for Malware</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-desktop-presence-embedding-this-pc-icons/"><u>Adjust Desktop Presence: Embedding 'This PC' Icons</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/autonomous-windows-update-an-offline-methodology/"><u>Autonomous Windows Update: An Offline Methodology</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-local-file-transmission-methods-which-fits-best/"><u>Analyzing Local File Transmission Methods: Which Fits Best?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-mastering-background-elimination-on-logitech-cameras/"><u>[New] In 2024, Mastering Background Elimination on Logitech Cameras</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-motorola-moto-g73-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Motorola Moto G73 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-personalize-your-pcs-audio-with-windows-11-mixer/"><u>Activate and Personalize Your PC's Audio with Windows 11 Mixer</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/leveraging-fb-livestream-for-post-produced-content-dissemination-for-2024/"><u>Leveraging FB Livestream for Post-Produced Content Dissemination for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-windows-10-navigating-as-a-first-timer/"><u>Accessible Windows 10: Navigating as a First-Timer</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/realign-corrected-identity-visualization-in-facebook-sessions-for-2024/"><u>Realign Corrected Identity Visualization in Facebook Sessions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-zeroxc000003e-problem-in-pc-application-startup/"><u>Addressing ZeroXc000003e Problem in PC Application Startup</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-samsung-galaxy-s24-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Samsung Galaxy S24 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-timed-lock-screen-issue-windows/"><u>Addressing Faulty Timed Lock Screen Issue Windows</u></a></li>
<li><a href="https://win11.techidaily.com/averting-unwanted-windows-store-automatization/"><u>Averting Unwanted Windows Store Automatization</u></a></li>
<li><a href="https://win11.techidaily.com/art-software-showdown-windows-programs-vs-procreate/"><u>Art Software Showdown: Windows Programs Vs. Procreate</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/stepwise-czech-study-top-efficient-online-tutorials/"><u>Stepwise Czech Study: Top Efficient Online Tutorials</u></a></li>
</ul></div>
