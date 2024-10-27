---
title: "Understanding Storage Needs Better: Strategies with Windows' DiskUsage Commands"
date: 2024-10-20T09:19:18.133Z
updated: 2024-10-26T19:21:47.009Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Understanding Storage Needs Better: Strategies with Windows' DiskUsage Commands"
excerpt: "This Article Describes Understanding Storage Needs Better: Strategies with Windows' DiskUsage Commands"
keywords: Disk Usage Windows,Storage Planning,Data Management,Space Optimization,Command Analysis,File System Insight,Storage Efficiency
thumbnail: https://thmb.techidaily.com/0d31f5646fe3a9a749251ddb64d10288427198f92e87a603dc09ffcf334ba8c5.jpg
---

## Understanding Storage Needs Better: Strategies with Windows' DiskUsage Commands

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
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
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037338/7443" target="_top" id="2037338">
  <img src="//a.impactradius-go.com/display-ad/7443-2037338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037338/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-no-caps-lock-required-android-and-ios-downloader-hacks/"><u>[New] 2024 Approved No Caps Lock Required Android and iOS Downloader Hacks</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-playscreen-media-app-review/"><u>[New] 2024 Approved PlayScreen Media App Review</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-no-fee-optimal-mobile-and-web-picture-upscaler-for-2024/"><u>[New] No-Fee, Optimal Mobile & Web Picture Upscaler for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-understanding-and-applying-luts-to-ae-projects/"><u>[Updated] 2024 Approved Understanding and Applying LUTs to AE Projects</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-step-into-cinematic-quality-using-instagrams-chroma-keying-effect/"><u>[Updated] In 2024, Step Into Cinematic Quality Using Instagram’s Chroma Keying Effect</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-snagging-youtube-vanished-videos-your-2-path-guide-for-2024/"><u>[Updated] Snagging YouTube Vanished Videos Your 2-Path Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gui-add-folders-to-windows-11s-taskbar/"><u>Elevate Your GUI - Add Folders to Windows 11'S Taskbar</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-selecting-peak-performance-lipo-cells-for-drones/"><u>In 2024, Selecting Peak Performance LiPo Cells for Drones</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/laughlineart-memogallery-for-2024/"><u>LaughLineArt MemoGallery for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-type-fixes-for-windows-11s-x80049dd3-error/"><u>Mastering the Art of Type Fixes for Windows 11'S X80049DD3 Error</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-windows-11s-unwanted-apps-quickly/"><u>Navigate Through Windows 11'S Unwanted Apps Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-custom-power-plans-in-windows/"><u>Overhauling Custom Power Plans in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-your-windows-11-printer-problems/"><u>Solve Your Windows 11 Printer Problems</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eradicate-error-80080300-in-windows-team-collaboration/"><u>Steps to Eradicate Error 80080300 in Windows Team Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-practices-for-getting-most-from-windows-11s-launchpad/"><u>The Best Practices for Getting Most From Windows 11'S Launchpad</u></a></li>
<li><a href="https://win11.techidaily.com/the-components-configuration-console-in-windows-explored/"><u>The Components Configuration Console in Windows Explored</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-managing-printers-in-windows-1011/"><u>The Essentials of Managing Printers in Windows 10/11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    