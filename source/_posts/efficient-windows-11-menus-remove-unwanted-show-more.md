---
title: "Efficient Windows 11 Menus: Remove Unwanted Show More"
date: 2024-11-03T22:21:40.769Z
updated: 2024-11-07T18:10:23.184Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficient Windows 11 Menus: Remove Unwanted Show More"
excerpt: "This Article Describes Efficient Windows 11 Menus: Remove Unwanted Show More"
keywords: Win11 Menu Optimize,Hide Show More Reduce,Streamline WinMenu,Efficiency WinMenu,Simplify Windows UI,Cut Unneeded Windows Features,Tidy Up Win11 Options
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Efficient Windows 11 Menus: Remove Unwanted Show More

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://extra-information.techidaily.com/new-20-best-anime-opening-songs-of-all-time/"><u>[New] 20 Best Anime Opening Songs of All Time</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-a-comprehensive-guide-accumulating-massive-amounts-of-tiktok-videos/"><u>[New] 2024 Approved A Comprehensive Guide Accumulating Massive Amounts of TikTok Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-essentials-of-blurring-photo-borders/"><u>[Updated] The Essentials of Blurring Photo Borders</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-adobe-reader-from-the-microsoft-store/"><u>Essential Tips for Adobe Reader From the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-lockout-mechanism-after-unsuccessful-sign-ons-in-w10w11/"><u>Fine-Tuning Lockout Mechanism After Unsuccessful Sign-Ons in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-package-installation-failures-across-various-os-versions/"><u>Fixing Package Installation Failures Across Various OS Versions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-razer-synapse-not-detecting-razer-devices-in-windows-11-and-11/"><u>How to Fix Razer Synapse Not Detecting Razer Devices in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resolve-printer-not-detected-error-in-windows-11/"><u>Methods to Resolve Printer Not Detected Error in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-samsung-galaxy-z-fold-5-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Samsung Galaxy Z Fold 5 – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-2024-approved-a-detailed-review-and-alternatives-of-vocaloid6-voice-generator/"><u>New 2024 Approved A Detailed Review & Alternatives of VOCALOID6 Voice Generator</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disk-space-limit-in-windows-os/"><u>Overcoming Disk Space Limit in Windows OS</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-fixing-stutter-and-freezing-problems-in-forza-horizon-5/"><u>Resolved: Fixing Stutter and Freezing Problems in Forza Horizon 5</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-launching-works-on-windows-10plus/"><u>Step-by-Step: Launching Works on WIndows 10+</u></a></li>
<li><a href="https://win-able.techidaily.com/transforming-audio-files-from-wav-to-ogg-format-with-easy-steps-both-offline-and-online-solutions/"><u>Transforming Audio Files From WAV to Ogg Format with Easy Steps - Both Offline & Online Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-detecting-razers-with-synapse-on-windows/"><u>Troubleshooting Non-Detecting Razers with Synapse on Windows</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-blaze-2-pro-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Blaze 2 Pro.</u></a></li>
</ul></div>

