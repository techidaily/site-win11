---
title: "Navigating Hard Drive Capacities: Leveraging Windows' DiskUsage Command Skills"
date: 2024-10-08T22:29:51.471Z
updated: 2024-10-15T20:01:00.834Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Hard Drive Capacities: Leveraging Windows' DiskUsage Command Skills"
excerpt: "This Article Describes Navigating Hard Drive Capacities: Leveraging Windows' DiskUsage Command Skills"
keywords: DiskSpace Optimization,Storage Usage Insight,HardDrive Capacity Management,Disk Space Analysis,Data Utilization Windows,Storage Monitoring Command,Filesystem Efficiency Windows
thumbnail: https://thmb.techidaily.com/4af354c0c4f31e85da7815990d834961f2e7342ecb73532a36e97929bcf9934e.jpg
---

## Navigating Hard Drive Capacities: Leveraging Windows' DiskUsage Command Skills

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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-instagram-reel-creating-stunning-slow-motion-content/"><u>[New] 2024 Approved Mastering Instagram Reel Creating Stunning Slow-Motion Content</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-advanced-techniques-in-post-uploaded-youtube-content-enhancement-for-2024/"><u>[Updated] Advanced Techniques in Post-Uploaded YouTube Content Enhancement for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-compliance-in-recording-video-streams-on-youtube/"><u>2024 Approved Compliance in Recording Video Streams on YouTube</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-oppo-a79-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Oppo A79 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-meizu-21-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Meizu 21 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-hot-40-pro-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Infinix Hot 40 Pro PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-assessing-your-needs-selecting-the-optimal-4k-camera-lens/"><u>In 2024, Assessing Your Needs Selecting the Optimal 4K Camera Lens</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-windows-11-status-bar-with-a-weather-icon/"><u>Personalize Windows 11 Status Bar with a Weather Icon</u></a></li>
<li><a href="https://win11.techidaily.com/reactivation-guide-for-apps-from-the-microsoft-store/"><u>Reactivation Guide for Apps From the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-rescue-volume-control-on-disconnected-bluetooth-devices/"><u>Reconnect and Rescue Volume Control on Disconnected Bluetooth Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-bugs-resetting-windows-11-software-issues/"><u>Reviving Bugs: Resetting Windows 11 Software Issues</u></a></li>
<li><a href="https://win11.techidaily.com/solving-code-0x0001-on-geforce-experience-windows-11-edition/"><u>Solving Code 0X0001 on GeForce Experience, Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-nvidia-connection-woes-a-step-by-step-guide-for-win-11-users/"><u>Tackling Nvidia Connection Woes: A Step-by-Step Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-microsoft-edge-shortcut-keeps-appearing-on-your-desktop/"><u>What to Do if Microsoft Edge Shortcut Keeps Appearing on Your Desktop</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    