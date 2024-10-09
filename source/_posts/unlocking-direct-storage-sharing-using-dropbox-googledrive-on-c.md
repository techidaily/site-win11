---
title: "Unlocking Direct Storage Sharing: Using Dropbox, GoogleDrive on C:"
date: 2024-10-01T19:31:21.383Z
updated: 2024-10-09T07:32:29.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Direct Storage Sharing: Using Dropbox, GoogleDrive on C:"
excerpt: "This Article Describes Unlocking Direct Storage Sharing: Using Dropbox, GoogleDrive on C:"
keywords: Direct Storage Access,Dropbox Data Sync,Drive C Share,Cloud Storage Unlock,Shared C Drives,Dropbox & GoogleDrive,C
thumbnail: https://thmb.techidaily.com/9fc617880b7f763c252c5a9e983583a15e0501d81b43be135b81d00ad4f84b19.png
---

## Unlocking Direct Storage Sharing: Using Dropbox, GoogleDrive on C

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  

![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
2. Right-click on it and choose **Map network drive**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  

![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-quick-tips-making-high-quality-recordings-on-iphone/"><u>[New] In 2024, Quick Tips Making High-Quality Recordings on iPhone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-top-15-stabilizers-and-platforms-for-dynamic-gopro-use-for-2024/"><u>[New] Top 15 Stabilizers & Platforms for Dynamic GoPro Use for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ideo-quality-comparison-mirrorless-or-dslr-cameras-for-2024/"><u>[New] Video Quality Comparison Mirrorless or DSLR Cameras for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-vidgrabmaster-mobilepc-app-downloads/"><u>2024 Approved VidGrabMaster Mobile/PC App Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-your-preferences-with-nvidia-driver-choices/"><u>Aligning Your Preferences with Nvidia Driver Choices</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-launch-windows-11-on-mac-through-parallels/"><u>Essential Steps to Launch Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/explore-and-manage-windows-11-writable-components/"><u>Explore and Manage Windows 11' Writable Components</u></a></li>
<li><a href="https://fox-info.techidaily.com/full-assessment-experiencing-the-world-in-360-with-samsung/"><u>Full Assessment Experiencing the World in 360° with Samsung</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-honor-90-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-nokia-c02-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Nokia C02</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-iphone-13-pro-max-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 13 Pro Max Without a Home Button</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-nonstop-teams-sign-ins-on-pc/"><u>Overcoming the Hurdle of Nonstop Teams Sign-Ins on PC</u></a></li>
<li><a href="https://win11.techidaily.com/quick-glance-windows-11-expert-guide-to-image-access/"><u>Quick Glance: Windows 11 Expert Guide to Image Access</u></a></li>
<li><a href="https://win11.techidaily.com/reward-system-reboot-for-your-favorite-titles/"><u>Reward System Reboot for Your Favorite Titles</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-windows-embracing-ai-dominance/"><u>Tomorrow's Windows: Embracing AI Dominance</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/transform-your-office-space-with-the-refined-design-of-the-flexispot-theodore-standing-desk-a-complete-review/"><u>Transform Your Office Space with the Refined Design of the Flexispot Theodore Standing Desk – A Complete Review</u></a></li>
</ul></div>

