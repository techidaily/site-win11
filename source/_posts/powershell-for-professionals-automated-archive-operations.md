---
title: "PowerShell for Professionals: Automated Archive Operations"
date: 2025-01-17T01:13:17.335Z
updated: 2025-01-19T01:23:30.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes PowerShell for Professionals: Automated Archive Operations"
excerpt: "This Article Describes PowerShell for Professionals: Automated Archive Operations"
keywords: PowerShell Pro Guide,Archiving Tasks Script,Automate Document Archives,Efficient PowerShell Use,Secure Data Management,Advanced PowerShell Techniques,PowerShell Archive Control
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## PowerShell for Professionals: Automated Archive Operations

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.

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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-elite-emulators-for-budget-switch-games/"><u>[New] In 2024, Elite Emulators for Budget Switch Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-radiant-reels-elevate-your-visuals-with-3-insta-tactics/"><u>[New] Radiant Reels Elevate Your Visuals with 3 Insta Tactics</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-image-edition-excellence-tutorial-insights/"><u>[Updated] 2024 Approved Image Edition Excellence Tutorial Insights</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-concealed-chronicles-your-ultimate-guide-to-secret-stories/"><u>[Updated] Concealed Chronicles Your Ultimate Guide to Secret Stories</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-version-timeline/"><u>Decoding Windows Version Timeline</u></a></li>
<li><a href="https://win11.techidaily.com/empower-your-workflow-github-desktop-and-windows-integration/"><u>Empower Your Workflow: GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-oppo-f25-pro-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Oppo F25 Pro 5G Devices</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Poco M6 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-mastering-the-science-of-quantum-hdr/"><u>In 2024, Mastering the Science of Quantum HDR</u></a></li>
<li><a href="https://discover-helper.techidaily.com/kostenlose-dvd-regionskonverter-fur-windows-11-8-and-7-freischalten-von-videodateien-aus-beliebigen-gebieten/"><u>Kostenlose DVD Regionskonverter Für Windows 11, 8 & 7 - Freischalten Von Videodateien Aus Beliebigen Gebieten</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-out-of-arrow-chaos-in-windows-pcs/"><u>Navigate Out of Arrow Chaos in Windows PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/obs-essentials-optimizing-your-skype-call-recording-quality-for-2024/"><u>OBS Essentials Optimizing Your Skype Call Recording Quality for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lsassexe-issue-a-step-by-step-guide/"><u>Overcoming 'lsass.exe' Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-app-camera-access-disputes-error-a00f4243/"><u>Overcoming Windows App Camera Access Disputes (Error A00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-virtual-setup-installing-win11-on-workstation-17/"><u>Streamlining Virtual Setup: Installing Win11 on Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-reducing-edges-cpu-usage-on-pc/"><u>Tips for Reducing Edge's CPU Usage on PC</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-windows-automatic-images-on-screen-lock/"><u>Turning On/Off Windows' Automatic Images on Screen Lock</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-features-a-detailed-look-at-the-xp-pen-artist-n-16-pro-illustrators-companion/"><u>Unveiling the Features: A Detailed Look at the XP-Pen Artist N 16 Pro Illustrator's Companion</u></a></li>
<li><a href="https://win11.techidaily.com/updating-your-spotlight-theme-a-users-guide-in-windows/"><u>Updating Your Spotlight Theme: A User's Guide in Windows</u></a></li>
</ul></div>

