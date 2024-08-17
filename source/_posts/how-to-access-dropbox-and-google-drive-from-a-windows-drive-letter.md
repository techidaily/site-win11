---
title: How to Access Dropbox and Google Drive From a Windows Drive Letter
date: 2024-08-16T00:45:20.543Z
updated: 2024-08-17T00:45:20.543Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Access Dropbox and Google Drive From a Windows Drive Letter
excerpt: This Article Describes How to Access Dropbox and Google Drive From a Windows Drive Letter
keywords: Access Dropbox on PC,Use Google Drive Windows,Link Dropbox Drives,Connect to GDrive WS,Open Dropbox via Windows,Google Drive File Sharing,Windows Drive Dropbox Share
thumbnail: https://thmb.techidaily.com/9e3724374b3f93992f56d90c3f06be4bddda301db6e3204484fdd608537b1478.png
---

## How to Access Dropbox and Google Drive From a Windows Drive Letter

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

## Common Cloud Storage Issues You May Encounter on Windows

 Dropbox, Google Drive, and similar cloud storage/sync services are easy to access from a web browser or the OS's default file manager. When you demand more than merely accessing your files, though, you may run into issues.

* Dropbox is accessible from a link in the file manager that brings you to its actual local folder, inside which your files are synced. Alternatively, you can visit that folder yourself. Dropbox cannot be "accessible through a letter" by default.
* Google Drive offers the option to map every account to a drive letter. However, try to access the contents of the virtual drive "behind" its "official" drive letter. Instead of your Google Drive files, you'll find a link to its local folder.
* Other alternatives may be even worse, with some only accessible locally through their custom clients.

 So, is it impossible to have your cloud storage account's "root folder" accessible directly from a drive letter?

 Thankfully, you can use a third-party solution for that. They're usually straightforward and can make your cloud storage "behave" like a normal drive on your computer. Still, you might want to avoid such apps for various reasons.

* Most cost money or are ad-supported.
* You'll be giving access to your data to another third party (on top of the cloud storage provider).
* The more apps and services that have access to your files, the higher the chances they'll fall into the wrong hands after a security breach.
* Extra software and services translate to increased complexity and potential for failure: some files may not sync when you expect them, metadata might get lost, etc.

 The major case against them is that there's no reason to use more software than you need.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  
![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
2. Right-click on it and choose **Map network drive**.  
![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  
![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-discovering-the-top-tools-for-engaging-video-beginnings-for-2024/"><u>[New] Discovering the Top Tools for Engaging Video Beginnings for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-elevate-your-profiles-visual-appeal/"><u>[New] Elevate Your Profile's Visual Appeal</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-rapid-fire-windowed-image-reader/"><u>[New] Rapid-Fire Windowed Image Reader</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-flix-fortune-hashtags-for-high-impact-low-length-video-content/"><u>[Updated] 2024 Approved  Flix Fortune  Hashtags for High Impact, Low-Length Video Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exploring-the-best-youtube-extractors-for-android-devices/"><u>[Updated] Exploring the Best YouTube Extractors for Android Devices</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-unlocking-youtube-studios-power-for-professional-edits/"><u>[Updated] In 2024, Unlocking YouTube Studio's Power for Professional Edits</u></a></li>
<li><a href="https://win11.techidaily.com/12-common-windows-11-aesthetic-oddities/"><u>12 Common Windows 11 Aesthetic Oddities</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-accessing-windows-web-services-manager/"><u>A Compreayer's Guide: Accessing Windows Web Services Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-the-negative-side-of-low-end-windows-licenses/"><u>A Deep Dive Into the Negative Side of Low-End Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-restart-utilizing-windows-11s-quick-start-function/"><u>Accelerating System Restart: Utilizing Windows 11'S Quick Start Function</u></a></li>
<li><a href="https://win11.techidaily.com/adding-visual-disk-space-analyzer-to-windows-explorer-menu/"><u>Adding Visual Disk Space Analyzer to Windows Explorer Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-store-glitch-code-0x80073cf3/"><u>Addressing Windows Store Glitch: Code 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-cost-monitor-functionality-of-your-wifi-network/"><u>Adjusting the Cost Monitor Functionality of Your Wifi Network</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-oled-bape-edition-review-stealthy-stylish-and-practical/"><u>ASUS Vivobook S 15 OLED BAPE Edition Review: Stealthy, Stylish, and Practical</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-glitches-a-guide-to-fixing-error-code-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/big-bulky-minipcs-with-brainy-bare-performance/"><u>Big, Bulky Minipcs with Brainy Bare Performance</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computer-skills-keyboard-shortcuts-for-success/"><u>Boost Your Computer Skills: Keyboard Shortcuts for Success</u></a></li>
<li><a href="https://fox-access.techidaily.com/champion-avc-player-for-seamless-viewing-for-2024/"><u>Champion AVC Player for Seamless Viewing for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/fading-frequencies-the-gentle-way-with-garageband/"><u>Fading Frequencies  The Gentle Way with Garageband</u></a></li>
<li><a href="https://fox-helps.techidaily.com/from-dull-to-dynamic-adding-animated-effects-to-instagram-stories-for-2024/"><u>From Dull to Dynamic  Adding Animated Effects to Instagram Stories for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-boot-into-safe-mode-and-efficiently-uninstall-graphics-driver-on-windows-8/"><u>How To Boot Into Safe Mode & Efficiently Uninstall Graphics Driver On Windows 8</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-an-mp4-on-galaxy-f54-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How to play an MP4 on Galaxy F54 5G?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-explore-exceptional-economically-priced-asmr-gear/"><u>In 2024, Explore Exceptional, Economically-Priced ASMR Gear</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-podcast-seo-skyrocketing-your-popularity/"><u>In 2024, Mastering Podcast SEO  Skyrocketing Your Popularity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-treacherous-waters-of-fraudgpt-interaction/"><u>Navigating the Treacherous Waters of FraudGPT Interaction</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://extra-information.techidaily.com/snowdrift-scribes-celebrating-beijings-olympic-spotlight/"><u>Snowdrift Scribes  Celebrating Beijing's Olympic Spotlight</u></a></li>
<li><a href="https://extra-information.techidaily.com/starting-point-for-motion-visual-effects/"><u>Starting Point for Motion Visual Effects</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-essential-guide-to-androids-best-video-editors-for-2024/"><u>The Essential Guide to Android's Best Video Editors for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>