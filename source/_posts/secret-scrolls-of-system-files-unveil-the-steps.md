---
title: "Secret Scrolls of System Files: Unveil the Steps"
date: 2024-09-09T19:25:50.329Z
updated: 2024-09-16T19:34:12.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secret Scrolls of System Files: Unveil the Steps"
excerpt: "This Article Describes Secret Scrolls of System Files: Unveil the Steps"
keywords: Secrets of Sysfiles,System File Insight,Uncovering Filesystem,Explore SysFiles Steps,Reveal Systemfile Paths,Deciphering Sysfiles,Sysfile Discovery Guide
thumbnail: https://thmb.techidaily.com/4a8a85a143c0d3d9775ca5a0e81916a22ae62d07a1551bf0ada3f1e75697ff38.jpg
---

## Secret Scrolls of System Files: Unveil the Steps

 Windows offers the feature to view the properties of any file or folder present on the disk. For many, it may appear as a non-useful utility because you can see a lot of data in File Explorer by changing the icons view. But you can do much more than just view metadata information in the Properties Window.

 Apart from checking out the file type, location, size, and creation data, you can apply access restrictions and even encrypt the folder contents. Moreover, you can enable or disable file sharing, add security measures and customize icons. So, without further ado, let us dive deep into the multiple methods to open file or folder properties in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Open File or Folder Properties in Windows

 Here are some easy ways to view the file or folder properties on a Windows PC. These methods will work for Windows 11 and older versions of Windows OS too.

### 1\. Using the Keyboard Shortcut

 You can view the file properties using the pre-defined shortcut keys on Windows. Here’s how to do it:

1. Press**Win + E** to launch File Explorer on your system.
2. Click on a file or folder to select it.
3. Then press**Alt + Enter** keys at once to open the file properties window.  
![View File Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties.jpg)

### 2\. Using the Mouse and Keyboard Shortcut

 This method eliminates the usage of the enter key to open the file properties windows. Repeat the following steps to open the properties window:

1. Open the File Explorer app and navigate to the folder location.
2. Now, hold the**Alt** key and**double-click** on the file to display its properties.

### 3\. Using the Context Menu

 If you don’t want to use the keyboard at all, then you can open the file properties using the context menu.

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) and type**explorer.exe** . Press the enter key to open the File Explorer.
2. Navigate to the desired file or folder location.
3. Now,**right-click** on the file and select the**Properties** option from the context menu.  
![View File Properties using Right Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties-using-right-context-menu.jpg)
4. The file properties window will launch on your system.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Keep in mind that the right-click context menu will look a bit different from the older versions of Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Using the File Explorer

 You can also view the file properties using the File Explorer app and not press a keyboard key even once. The option to view properties is hidden in the menu bar. Here’s how to open file properties using File Explorer:

1. Press**Win + E** to[open the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the file location and**click** on it to highlight it.
3. Now, navigate to the top menu and click on the**three dots (...)** button.
4. A drop-down menu will open. Select the**Properties** option from the menu.  
![View File Properties using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties-using-file-explorer.jpg)
5. The Properties window will launch on your system. Press**Alt + F4** to close it after you no longer need it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 5\. Using the CMD Tool

 The above-mentioned shortcuts launch the Properties window which shows the GUI version of File Properties. But, you can also view the properties of a folder or file using the command prompt on Windows. Repeat the following steps to view file properties using the command prompt utility:

1. Press**Win + R** to launch the Run command box. Type**cmd** in the text box and press**Ctrl + Shift + Enter** key at once.
2. UAC will pop up. Click on the**Yes** button to open the command prompt with administrator permissions.
3. Now, enter the following command and press the enter key: **wmic datafile where "name='File Path'" list full**
4. Replace the “**File Path** ” with the actual location of your file. We have a text file saved on the desktop. So, the command to display its properties will be: **wmic datafile where "name='C:\\\\Users\\\\Test\\\\Desktop\\\\rr.txt'" list full**  
![View File Properties using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties-using-cmd.jpg)
5. Scroll down to check the file properties such as size, creation date, and more attributes.

### 6\. Using PowerShell

 PowerShell has a different command to display folder or file properties. Like the CMD command, it also displays the file properties inside the shell in text format.

1. Press**Win + S** and type PowerShell. Click on the first search result to launch PowerShell on your system.
2. Now, type the following command:**Get-Item -Path File Path | fl \***
3. Replace “**File Path** ” with the actual storage location like you did in the fifth method.  
![View File Properties using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties-using-powershell.jpg)
4. Press the**Enter** key to execute the command.

## Quickly View File or Folder Properties on Windows

 These were the multiple methods to view file or folder properties in Windows. The first four options launch the GUI version of file properties, which is easier to navigate for users. However, you can also view file properties in CMD or PowerShell.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-enhancing-video-content-through-effective-use-of-cardsannotations-for-2024/"><u>[New] Enhancing Video Content Through Effective Use of Cards/Annotations for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-how-to-change-screenshot-file-formats-on-a-mac/"><u>[New] In 2024, How to Change Screenshot File Formats on a Mac</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-speedy-tiktok-video-performance-a-step-by-step-plan/"><u>[New] In 2024, Speedy TikTok Video Performance A Step-by-Step Plan</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-how-to-guide-elevating-gameplay-recordings-via-obs-for-2024/"><u>[Updated] How-To Guide Elevating Gameplay Recordings via OBS for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/boost-your-youtube-presence-expert-tips-for-effective-channel-growth-and-promotion-techniques/"><u>Boost Your YouTube Presence: Expert Tips for Effective Channel Growth and Promotion Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-unnecessary-workload-in-windows-system/"><u>Cutting Down Unnecessary Workload in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/direct-steps-to-activatedisable-wifi-cost-metering-in-win11/"><u>Direct Steps to Activate/Disable Wifi Cost Metering in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-all-chromium-notifications-in-windows-pc/"><u>Disabling All Chromium Notifications in Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/effective-tactics-for-printer-troubles-on-windows-11/"><u>Effective Tactics for Printer Troubles on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-a-vanishing-sd-card-in-windows-filesystem/"><u>How to Locate a Vanishing SD Card in Windows Filesystem</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-guide-to-extracting-srt-from-a-zip-archive/"><u>In 2024, Guide to Extracting SRT From a ZIP Archive</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-vivo-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Vivo Phone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-pathway-to-popularity-on-instagram-from-zero-to-a-thousand-in-30-days/"><u>In 2024, The Pathway to Popularity on Instagram From Zero to a Thousand in 30 Days</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-workspace-viewing-switch-wmdesk-way/"><u>Optimize Workspace Viewing: Switch WmDesk Way</u></a></li>
<li><a href="https://win11.techidaily.com/proficient-techniques-for-managing-win-registry-from-cmd/"><u>Proficient Techniques for Managing Win Registry From CMD</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-realme-gt-5-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Realme GT 5</u></a></li>
</ul></div>

