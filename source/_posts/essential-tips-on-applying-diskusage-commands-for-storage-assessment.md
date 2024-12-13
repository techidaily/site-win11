---
title: Essential Tips on Applying DiskUsage Commands for Storage Assessment
date: 2024-12-06T11:03:43.631Z
updated: 2024-12-13T03:12:12.169Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips on Applying DiskUsage Commands for Storage Assessment
excerpt: This Article Describes Essential Tips on Applying DiskUsage Commands for Storage Assessment
keywords: Storage Assessment Guide,Disk Usage Inspection,Command Line Storage Check,DiskSpace Management,Storage Utility Commands,Optimize Disk Space,Performance Disk Insight
thumbnail: https://thmb.techidaily.com/bae70dc1da321109f70e787435e8a7bf8638e992652aa5e9b27c3e355526ca4c.jpg
---

## Essential Tips on Applying DiskUsage Commands for Storage Assessment

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-creative-edge-pushing-boundaries-in-photography/"><u>[New] 2024 Approved The Creative Edge Pushing Boundaries in Photography</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-precise-obs-settings-for-inexpensive-hardware/"><u>[Updated] Precise OBS Settings for Inexpensive Hardware</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-practices-for-apples-podcast-listings-for-2024/"><u>Best Practices for Apple's Podcast Listings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/defending-your-windows-11-with-the-best-four-password-savers/"><u>Defending Your Windows 11 with the Best Four Password Savers</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-perks-of-iphones-enhanced-nfc-connectivity-with-third-party-apps-a-detailed-guide-zdnet/"><u>Discover the Perks of iPhone's Enhanced NFC Connectivity with Third-Party Apps - A Detailed Guide | ZDNET</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-defenders-block-on-third-party-virus-tools/"><u>How to Bypass Defender's Block on Third-Party Virus Tools</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-samsung-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Samsung Devices</u></a></li>
<li><a href="https://buynow-info.techidaily.com/huions-giant-canvas-for-digital-artists-exploring-features-and-performance-of-kamvas-gt-191-drawing-tablet-review/"><u>Huion's Giant Canvas for Digital Artists: Exploring Features & Performance of Kamvas GT-191 Drawing Tablet Review</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210721118-9798218118617-love-handles-muffin-tops/"><u>Love Handles & Muffin Tops | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-camera-app-correction-for-error-a00f425d-in-win11/"><u>Mastering Camera App Correction for Error A00F425D in Win11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/revolutionizing-video-recording-insights-on-camstudios-latest-release/"><u>Revolutionizing Video Recording - Insights on CamStudio's Latest Release</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-chromium-enhancing-youtube-performance/"><u>Tackling Chromium: Enhancing YouTube Performance</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-mastering-win-11-taskbar-controls/"><u>The Ultimate Guide to Mastering Win 11 Taskbar Controls</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-accurate-monitoring-of-tasks-cpu-impact-on-system/"><u>Tips for Accurate Monitoring of Tasks' CPU Impact on System</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ultimate-ranking-the-top-asus-router-picks-you-need/"><u>Ultimate Ranking: The Top Asus Router Picks You Need</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-implementing-login-change-replace-your-windows-11-pin-with-a-password/"><u>Understanding and Implementing Login Change: Replace Your Windows 11 PIN With a Password</u></a></li>
<li><a href="https://win11.techidaily.com/win11-troubleshooting-guide-for-offline-printers/"><u>Win11 Troubleshooting Guide for Offline Printers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    