---
title: "Exploring System Files: Top 6 Access Methods"
date: 2025-01-23T02:47:35.098Z
updated: 2025-01-24T20:57:16.749Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Exploring System Files: Top 6 Access Methods"
excerpt: "This Article Describes Exploring System Files: Top 6 Access Methods"
keywords: FileSystemBasics,AccessFileMethods,FileStructureInsight,SystemFilesAccess,ExploreOSFiles,OSFileExamineTop,TopFilesAccessTechniques
thumbnail: https://thmb.techidaily.com/0c6d2fd1a73159563e57dda315b30eb330741092cc6760e2a82edb3563c1b5c8.jpg
---

## Exploring System Files: Top 6 Access Methods

 Windows offers the feature to view the properties of any file or folder present on the disk. For many, it may appear as a non-useful utility because you can see a lot of data in File Explorer by changing the icons view. But you can do much more than just view metadata information in the Properties Window.

 Apart from checking out the file type, location, size, and creation data, you can apply access restrictions and even encrypt the folder contents. Moreover, you can enable or disable file sharing, add security measures and customize icons. So, without further ado, let us dive deep into the multiple methods to open file or folder properties in Windows.

## How to Open File or Folder Properties in Windows

 Here are some easy ways to view the file or folder properties on a Windows PC. These methods will work for Windows 11 and older versions of Windows OS too.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Using the Keyboard Shortcut

 You can view the file properties using the pre-defined shortcut keys on Windows. Here’s how to do it:

1. Press**Win + E** to launch File Explorer on your system.
2. Click on a file or folder to select it.
3. Then press**Alt + Enter** keys at once to open the file properties window.  
![View File Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using the Mouse and Keyboard Shortcut

 This method eliminates the usage of the enter key to open the file properties windows. Repeat the following steps to open the properties window:

1. Open the File Explorer app and navigate to the folder location.
2. Now, hold the**Alt** key and**double-click** on the file to display its properties.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using the Context Menu

 If you don’t want to use the keyboard at all, then you can open the file properties using the context menu.

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) and type**explorer.exe** . Press the enter key to open the File Explorer.
2. Navigate to the desired file or folder location.
3. Now,**right-click** on the file and select the**Properties** option from the context menu.  
![View File Properties using Right Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties-using-right-context-menu.jpg)
4. The file properties window will launch on your system.

 Keep in mind that the right-click context menu will look a bit different from the older versions of Windows.

### 4\. Using the File Explorer

 You can also view the file properties using the File Explorer app and not press a keyboard key even once. The option to view properties is hidden in the menu bar. Here’s how to open file properties using File Explorer:

1. Press**Win + E** to[open the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the file location and**click** on it to highlight it.
3. Now, navigate to the top menu and click on the**three dots (...)** button.
4. A drop-down menu will open. Select the**Properties** option from the menu.  
![View File Properties using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/view-file-properties-using-file-explorer.jpg)
5. The Properties window will launch on your system. Press**Alt + F4** to close it after you no longer need it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-expert-selection-of-10-premium-spotify-soundscape-tools/"><u>[New] 2024 Approved Expert Selection of 10 Premium Spotify Soundscape Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crafting-a-youtube-empire-26-successful-techniques/"><u>[Updated] In 2024, Crafting a YouTube Empire 26 Successful Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/9-pros-of-modernizing-to-windows-revamped-outlook/"><u>9 Pros of Modernizing to Windows' Revamped Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-failed-logon-wait-duration-settings/"><u>Adjusting Failed Logon Wait Duration Settings</u></a></li>
<li><a href="https://win11.techidaily.com/adopt-wsl-the-easy-way-to-run-linux-commands/"><u>Adopt WSL: The Easy Way to Run Linux Commands</u></a></li>
<li><a href="https://win11.techidaily.com/altering-account-access-in-windows-11-easily/"><u>Altering Account Access in Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-utility-of-windows-11s-initial-interface/"><u>Boosting the Utility of Windows 11'S Initial Interface</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-xs-max-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone XS Max to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722904106277-master-the-art-of-removing-cache-and-cookies-in-leading-web-browsers-today/"><u>Master the Art of Removing Cache and Cookies in Leading Web Browsers Today!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-avi-file-cutting-made-easy-the-ultimate-tutorial/"><u>New In 2024, AVI File Cutting Made Easy The Ultimate Tutorial</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfecting-subtitles-in-media-ultimate-list-of-on-line-aid-sources-for-2024/"><u>Perfecting Subtitles in Media Ultimate List of On-Line Aid Sources for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/shift-key-issues-discover-effective-fixes-and-solutions/"><u>Shift Key Issues? Discover Effective Fixes and Solutions!</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-sony-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Sony</u></a></li>
<li><a href="https://win11.techidaily.com/1719245846865-windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance</u></a></li>
<li><a href="https://win11.techidaily.com/1719370951528-xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips!</u></a></li>
</ul></div>

