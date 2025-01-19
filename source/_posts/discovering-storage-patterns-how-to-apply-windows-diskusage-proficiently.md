---
title: "Discovering Storage Patterns: How to Apply Windows' DiskUsage Proficiently"
date: 2025-01-14T02:06:09.203Z
updated: 2025-01-19T01:21:01.433Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Discovering Storage Patterns: How to Apply Windows' DiskUsage Proficiently"
excerpt: "This Article Describes Discovering Storage Patterns: How to Apply Windows' DiskUsage Proficiently"
keywords: Disk Usage Insight,Windows Disk Management,Storage Analysis Tools,Optimal Data Storing,Managing Hardware Space,Data Pattern Discovery,Efficient Disk Utilization
thumbnail: https://thmb.techidaily.com/d208efb0315dc3e80b4d5a8f4b751d30ee62ca28dd2151c249d15e615be6f528.jpg
---

## Discovering Storage Patterns: How to Apply Windows' DiskUsage Proficiently

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-a-step-by-step-approach-to-popularizing-instagram-posts/"><u>[New] 2024 Approved A Step-by-Step Approach to Popularizing Instagram Posts</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-tailoring-your-techniques-for-itunes-videos/"><u>[Updated] 2024 Approved Tailoring Your Techniques for iTunes Videos</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-the-fastest-way-to-scan-windows-files/"><u>[Updated] In 2024, The Fastest Way to Scan Windows Files</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-editors-toolkit-elevating-your-youtube-videos-via-windows-pc/"><u>[Updated] The Editor's Toolkit Elevating Your YouTube Videos via Windows PC</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-leading-gif-software-ranked-apples-favorites/"><u>2024 Approved Leading GIF Software Ranked Apple's Favorites</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-color-dynamics-rgb-on-windows-11/"><u>Configuring Color Dynamics: RGB on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/declutter-minds-notes-organized-with-obsidian-canvas-techniques/"><u>Declutter Minds: Notes Organized with Obsidian Canvas Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-dismantle-persistent-0x800f0831-issues/"><u>Expert Guide to Dismantle Persistent 0X800F0831 Issues</u></a></li>
<li><a href="https://driver-download.techidaily.com/getting-started-with-logitech-g43-essential-driver-software-for-optimal-performance/"><u>Getting Started with Logitech G43# - Essential Driver Software for Optimal Performance</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-xiaomi-redmi-note-13-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Xiaomi Redmi Note 13 5G</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-error-code-0x8007045d-in-windows-11/"><u>Overcoming the Error Code 0X8007045d in Windows 11</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1726026902836-pc/"><u>PCにて自らの声を録音するステップバイステップマニュアル</u></a></li>
<li><a href="https://win11.techidaily.com/secure-data-access-on-windows-pc-without-online-network/"><u>Secure Data Access on Windows PC without Online Network</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-ultimate-insiders-guide-to-instagram-stories-magic-for-2024/"><u>The Ultimate Insider's Guide to Instagram Stories Magic for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-systems-lost-dragging-feature-in-win11/"><u>Unlock Your System's Lost Dragging Feature in Win11</u></a></li>
</ul></div>

