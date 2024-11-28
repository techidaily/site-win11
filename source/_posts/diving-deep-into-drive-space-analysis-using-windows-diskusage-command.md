---
title: Diving Deep Into Drive Space Analysis Using Windows DiskUsage Command
date: 2024-11-22T16:02:12.416Z
updated: 2024-11-27T20:37:00.845Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diving Deep Into Drive Space Analysis Using Windows DiskUsage Command
excerpt: This Article Describes Diving Deep Into Drive Space Analysis Using Windows DiskUsage Command
keywords: Disk Usage Query,Drive Space Analyzer,Windows DiskSpace Check,DiskUsage Insight,Storage Utility Window,DiskStats Command,DriveSpace Monitoring
thumbnail: https://thmb.techidaily.com/fd52a4ddb4c67fef5b4a68a7a51c8e47e5f13f4d158884cb761f8f838fb72e26.jpeg
---

## Diving Deep Into Drive Space Analysis Using Windows DiskUsage Command

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-amplify-your-videos-impact-with-strategically-placed-time-markers/"><u>[New] 2024 Approved Amplify Your Video's Impact with Strategically Placed Time Markers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-apex-storage-wizards-best-of-android-cloud/"><u>[Updated] Apex Storage Wizards Best of Android Cloud</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-steps-to-optimize-win11-network-preferences/"><u>Detailed Steps to Optimize Win11 Network Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-issues-with-windows-11-search-bar/"><u>Eliminate Issues with Windows 11 Search Bar</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-samsung-galaxy-s23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-windows-11-not-running-errors-on-personal-computers-effective-strategies/"><u>Fixing Windows 11 Not Running Errors on Personal Computers - Effective Strategies</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-v29e-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo V29e without Losing Data | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-15-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 15 Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-realme-gt-5-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Realme GT 5?</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-aggregatorhostexe-functionalities-and-security/"><u>Insight Into Windows' AggregatorHost.exe: Functionalities and Security</u></a></li>
<li><a href="https://win11.techidaily.com/nearby-share-guide-for-dual-os-connectivity/"><u>Nearby Share Guide for Dual OS Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-zero-a00f-camera-application-issue/"><u>Overcoming Windows 11'S Zero-A00F Camera Application Issue</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-windows-fbm-errors-seamless-chats-ahead/"><u>Resolve Windows FBM Errors, Seamless Chats Ahead</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-avoiding-password-entry-for-rdp-connections/"><u>Stealth Mode: Avoiding Password Entry for RDP Connections</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-vivo-t2-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-honor-100-pro-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Honor 100 Pro Phones</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-after-successful-login-failed/"><u>Unlocking Windows After Successful Login Failed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    