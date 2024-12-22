---
title: "Navigating Through Your Drive Space: A Disc Usage Command Breakdown"
date: 2024-12-20T17:49:07.122Z
updated: 2024-12-22T17:08:31.581Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Through Your Drive Space: A Disc Usage Command Breakdown"
excerpt: "This Article Describes Navigating Through Your Drive Space: A Disc Usage Command Breakdown"
keywords: Drive Space Guide,Command Line Use,Disk Utilization,File Explorer Analysis,Storage Optimization,Data Management,Usage Insights
thumbnail: https://thmb.techidaily.com/f567dab373423469fdd9df8f70e7990588879bfed38e1184b365dd128527e555.jpg
---

## Navigating Through Your Drive Space: A Disc Usage Command Breakdown

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/new-prime-android-space-savers-compendium-for-2024/"><u>[New] Prime Android Space-Savers Compendium for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-time-management-the-art-of-planning-zoom-meetings/"><u>[New] Time Management The Art of Planning Zoom Meetings</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-leveraging-keywords-and-metadata-in-podcast-seo-for-2024/"><u>[Updated] Leveraging Keywords and Metadata in Podcast SEO for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-secret-to-reversed-video-magic-in-snapchat-for-2024/"><u>[Updated] The Secret to Reversed Video Magic in Snapchat for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-advanced-tips-for-recording-google-voice-dialogues/"><u>2024 Approved Advanced Tips for Recording Google Voice Dialogues</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exploring-the-fitbit-versa-2s-features-an-in-depth-look-at-its-superior-health-monitoring-abilities-coupled-with-comprehensive-smartwatch-functionality/"><u>Exploring the Fitbit Versa 2'S Features: An In-Depth Look at Its Superior Health Monitoring Abilities Coupled with Comprehensive Smartwatch Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-paint-cocreator-to-create-ai-images-in-windows-11/"><u>How to Use Paint Cocreator to Create AI Images in Windows 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-distinguished-top-5-effortless-action-recorder-recommendations/"><u>In 2024, Distinguished Top 5 Effortless Action Recorder Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fax-cover-page-customization-in-windows-11/"><u>Mastering Fax Cover Page Customization in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-0x80780119-system-image-issue/"><u>Overcoming Windows Error: 0X80780119 System Image Issue</u></a></li>
<li><a href="https://win11.techidaily.com/post-installation-web-steps-and-strategies/"><u>Post-Installation Web: Steps and Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/reestablishing-connection-between-synapse-and-razer-devices/"><u>Reestablishing Connection Between Synapse & Razer Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/satellite-sos-messaging-a-groundbreaking-feature-on-the-newly-launched-google-pixel-9-tech-analysis/"><u>Satellite SOS Messaging: A Groundbreaking Feature on the Newly Launched Google Pixel 9 | Tech Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-vram-a-comprehensible-guide-for-win-users/"><u>Skyrocket VRAM: A Comprehensible Guide for Win Users</u></a></li>
<li><a href="https://techidaily.com/the-best-electronic-signature-way-to-sign-jpg-files-online-by-ldigisigner-sign-a-jpg-sign-a-jpg/"><u>The best electronic signature way to sign JPG files online</u></a></li>
<li><a href="https://win11.techidaily.com/thorough-instructions-to-delete-wsl-entirely/"><u>Thorough Instructions to Delete WSL Entirely</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-calculator-functionality/"><u>Unlocking Window's Calculator Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-causes-of-virtualboxs-efail-error/"><u>Unraveling the Causes of VirtualBox's E_FAIL Error</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-windows-system-with-amd-gpu-software/"><u>Upgrade Windows System with AMD GPU Software</u></a></li>
</ul></div>

