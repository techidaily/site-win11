---
title: Streamlining Storage Strategies with a Focus on Windows' DiskUsage
date: 2024-06-25T10:05:58.577Z
updated: 2024-06-26T10:05:58.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining Storage Strategies with a Focus on Windows' DiskUsage
excerpt: This Article Describes Streamlining Storage Strategies with a Focus on Windows' DiskUsage
keywords: Storage Optimization,Disk Usage Insight,Disk Management Tips,Data Organizing Strategy,File System Efficiency,Storage Reduction Methods,Optimized Disk Space
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Streamlining Storage Strategies with a Focus on Windows' DiskUsage

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/streamlining-microsoft-store-use-in-windows-11/"><u>Streamlining Microsoft Store Use in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-user-biometric-use-by-domains/"><u>Enabling/Disabling User Biometric Use by Domains</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-chatgpt-is-at-capacity-right-now-error-on-windows/"><u>How to Fix the ChatGPT Is at Capacity Right Now Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-cheap-traps-the-realities-of-inferior-windows-activation-codes/"><u>Avoid Cheap Traps: The Realities of Inferior Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-app-hiccup-geforce-x0001/"><u>Overcoming Windows 11 App Hiccup: GeForce X0001</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-interface-with-fn-key-modifications/"><u>Enhancing User Interface with FN Key Modifications</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-beginners-guide-to-choosing-lenses-and-cameras-for-youtube-vloggers/"><u>[New] Beginner's Guide to Choosing Lenses and Cameras for YouTube Vloggers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-xiaomi-14-ultra-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Xiaomi 14 Ultra to Another | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-ultimate-crops-and-cultivation-compilation/"><u>2024 Approved  The Ultimate Crops & Cultivation Compilation</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-vivo-y78t-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Vivo Y78t Phone that is Locked?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-samsung-galaxy-a24mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Samsung Galaxy A24Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-navigating-to-upcoming-somber-soundscape-collections/"><u>2024 Approved Navigating to Upcoming Somber Soundscape Collections</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-elevate-views-with-science-backed-timing-tactics/"><u>[New] Elevate Views with Science-Backed Timing Tactics</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>