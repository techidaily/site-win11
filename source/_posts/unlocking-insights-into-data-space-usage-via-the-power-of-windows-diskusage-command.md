---
title: Unlocking Insights Into Data Space Usage via the Power of Windows DiskUsage Command
date: 2024-10-21T04:46:07.424Z
updated: 2024-10-27T03:49:46.944Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Insights Into Data Space Usage via the Power of Windows DiskUsage Command
excerpt: This Article Describes Unlocking Insights Into Data Space Usage via the Power of Windows DiskUsage Command
keywords: Data Usage Windows Disk,Unlocking Disk Insights,DiskSpace Analysis Tool,Optimize Data Storage,Windows Disk Usage Cmd,Space Data Management,Discover Disk Utility
thumbnail: https://thmb.techidaily.com/71f97dd9274703edf2e1d5e61f1afdbaca75ab6c6c70ddf26d28f8e813f8a89f.jpg
---

## Unlocking Insights Into Data Space Usage via the Power of Windows DiskUsage Command

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-top-10-tips-for-mastering-magix-video-pro-x/"><u>[New] 2024 Approved Top 10 Tips for Mastering Magix Video Pro X</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-unleashing-media-prime-video-players-on-windows-mobile/"><u>[Updated] 2024 Approved Unleashing Media Prime Video Players on Windows Mobile</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-richest-streamers-ever-caught/"><u>2024 Approved Richest Streamers Ever Caught</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-ultimate-6-tools-for-audiovisual-interpretation/"><u>2024 Approved Ultimate 6 Tools for Audio/Visual Interpretation</u></a></li>
<li><a href="https://extra-resources.techidaily.com/converting-photographic-moments-into-cinematic-vignettes/"><u>Converting Photographic Moments Into Cinematic Vignettes</u></a></li>
<li><a href="https://win11.techidaily.com/effective-tactics-to-ensure-v22h2-update-on-windows-11-proceeds/"><u>Effective Tactics to Ensure V22H2 Update on Windows 11 Proceeds</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-activate-and-use-chatgpts-additional-functionality-through-plugins/"><u>How to Activate and Use ChatGPT's Additional Functionality Through Plugins</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-navigation-learn-to-use-gestures-in-ms-edge-for-windows-11/"><u>Master the Art of Navigation: Learn to Use Gestures in MS Edge for Windows 11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/optimal-chatgpt-command-strategies-unveiled/"><u>Optimal ChatGPT Command Strategies Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-default-save-issues-in-modern-windows/"><u>Preventing Default Save Issues in Modern Windows</u></a></li>
<li><a href="https://win-webster.techidaily.com/preventing-unwanted-windows-10-auto-upgrades-discover-6-proven-strategies-inside/"><u>Preventing Unwanted Windows 10 Auto-Upgrades: Discover 6 Proven Strategies Inside!</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-transition-turning-windows-cr2-photos-into-jpgs/"><u>Seamless Transition: Turning Windows CR2 Photos Into JPGs</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-file-maintenance-the-autodelete-system-for-windows-users/"><u>Simplifying File Maintenance: The AutoDelete System for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-backup-cortanas-digital-footprint-windows/"><u>Strategies to Backup Cortana's Digital Footprint (Windows)</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-new-animated-features-now-available-on-dvd-discover-the-latest-releases/"><u>Top New Animated Features Now Available on DVD - Discover the Latest Releases</u></a></li>
<li><a href="https://win11.techidaily.com/top-six-reasons-for-switching-to-win11-from-macos/"><u>Top Six Reasons for Switching to Win11 From macOS</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-guide-to-enhancing-frame-rates-and-reducing-lag-in-watch-dogs-legion/"><u>Ultimate Guide to Enhancing Frame Rates & Reducing Lag in Watch Dogs: Legion</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-full-potential-of-your-browser-with-gestures-in-microsoft-edge-windows-11/"><u>Unlock the Full Potential of Your Browser with Gestures in Microsoft Edge, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/winexe-transformation-techniques-with-bat-scripts/"><u>WinEXE Transformation Techniques with .bat Scripts</u></a></li>
</ul></div>

