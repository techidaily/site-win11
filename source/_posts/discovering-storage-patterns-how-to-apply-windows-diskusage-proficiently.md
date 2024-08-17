---
title: "Discovering Storage Patterns: How to Apply Windows' DiskUsage Proficiently"
date: 2024-08-16T00:51:29.107Z
updated: 2024-08-17T00:51:29.107Z
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
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-mastering-thumbnail-creation-a-step-by-step-guide/"><u>[New] Mastering Thumbnail Creation  A Step-by-Step Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unityflip-blend-ios-and-macos-media-artfully/"><u>[Updated] UnityFlip  Blend iOS & macOS Media Artfully</u></a></li>
<li><a href="https://win11.techidaily.com/4-early-stages-of-pc-failure-know-when-to-act/"><u>4 Early Stages of PC Failure, Know When To Act</u></a></li>
<li><a href="https://win11.techidaily.com/6-risks-of-using-cheap-windows-activation-keys/"><u>6 Risks of Using Cheap Windows Activation Keys</u></a></li>
<li><a href="https://win11.techidaily.com/easy-access-mastering-folders-and-files-props/"><u>Easy Access: Mastering Folders and Files Props</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-3-in-nvidia-opengl-win10-and-11/"><u>Eliminating Error Code 3 in NVIDIA OpenGL (Win10 & 11)</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-taskbar-tweaks-in-windows-11/"><u>Expert Guide to Taskbar Tweaks in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/grandiose-photographic-epic-weaver-for-2024/"><u>Grandiose Photographic Epic Weaver for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exclusive-discounts-on-economical-gopro-cameras/"><u>In 2024, Exclusive Discounts on Economical GoPro Cameras</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-13-pro-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 13 Pro with IMEI Code?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/making-your-twitter-media-a-gif-masterpiece-for-2024/"><u>Making Your Twitter Media A GIF Masterpiece for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-printer-friendly-presentations-on-windows/"><u>Mastering the Art of Printer-Friendly Presentations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-elusive-theme-options-through-registry/"><u>Mastering Windows 11'S Elusive Theme Options Through Registry</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-error-5573-essential-tips-for-smooth-gaming-on-playstation-and-pc-with-warzone/"><u>Overcoming Error 5573: Essential Tips for Smooth Gaming on PlayStation and PC with Warzone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-prevent-windows-control-center-crashes/"><u>Quick-Fix Guide to Prevent Windows Control Center Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-vms-from-windows-host-to-linux-guest-with-hyper-v/"><u>Setting Up VMs: From Windows Host to Linux Guest with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-upgrade-failure-in-windows-11-error-0x800f0922/"><u>Steps to Fix Upgrade Failure in Windows 11 - Error 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/sync-windows-display-avoiding-overscan-limitations/"><u>Sync Windows Display: Avoiding Overscan Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-file-management-customizing-explorer-comments/"><u>Tips for Efficient File Management: Customizing Explorer Comments</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-powerrename-for-files/"><u>Transforming Chaos: PowerRename for Files</u></a></li>
<li><a href="https://extra-information.techidaily.com/transforming-videos-with-unprecedented-clarity-using-vce-22/"><u>Transforming Videos with Unprecedented Clarity Using VCE 2.2</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-lock-screen-stop-timer-glitch/"><u>Troubleshooting Windows Lock Screen Stop-Timer Glitch</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-itel-p55-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Itel P55 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-security-of-windows-11s-s-mode/"><u>Unpacking the Security of Windows 11'S 'S Mode'</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-top-online-markets-for-quality-tamil-ringtone-downloads/"><u>Unveiling Top Online Markets for Quality Tamil Ringtone Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/why-the-shift-from-windows-10-to-version-11-fails/"><u>Why the Shift From Windows 10 to Version 11 Fails</u></a></li>
<li><a href="https://win11.techidaily.com/winning-with-linux-the-windows-integration-edge/"><u>Winning with Linux: The Windows Integration Edge</u></a></li>
<li><a href="https://win11.techidaily.com/yearly-best-offer-buy-now-at-612-for-eternal-win10-life/"><u>Yearly Best Offer: Buy Now at $6.12 for Eternal Win10 Life</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>