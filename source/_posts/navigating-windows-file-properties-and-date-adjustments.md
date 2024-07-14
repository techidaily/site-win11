---
title: Navigating Windows File Properties and Date Adjustments
date: 2024-07-13T10:41:47.181Z
updated: 2024-07-14T10:41:47.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows File Properties and Date Adjustments
excerpt: This Article Describes Navigating Windows File Properties and Date Adjustments
keywords: File Prop Settings,Date Format Edit,System Files Info,Windows File Details,Modify File Dates,Explore File Attributes,Adjust File Timestamp
thumbnail: https://thmb.techidaily.com/f6048b78b677a0065b7683b7780e2c91c1ef9e11def92a26e974e1428f77307f.jpg
---

## Navigating Windows File Properties and Date Adjustments

 Windows keeps a record of when a file was created, who authored it, and when it was last modified. This information is known as file attributes and can be used to sort files by date, author name, and other parameters.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

## How to Change the Date Created, Date Accessed, and Date Modified Attributes Using PowerShell

 File Explorer doesn't allow changing critical attributes, such as the date a document was created, accessed, or modified. With [PowerShell, a command-line interface utility built into Windows](http://www.makeuseof.com/what-is-windows-powershell/), you can modify them.

 However, the process to change the attributes with PowerShell is a bit complex. If you don't have any experience using PowerShell, you can use a third-party app, Attribute Changer, to change the attributes, as explained in the next section.

 If running a few commands in PowerShell isn't a big deal (for instance, you already know the [best PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/)), follow the steps outlined below to change the created, modified, or accessed dates.

 First, type **"PowerShell"** in Windows Search, right-click on **PowerShell,** and select **Run as administrator**. This gives the utility administrative access to make the desired changes without any restriction.

![Run windows powershell as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-powershell-as-administrator.jpg)

 Then, navigate to the directory where the file or folder you want to change the attributes of is located. Type **cd..** to move back one folder in the given path, and **cd folder\_name** to move to the next folder.

 For example, our desired folder is located at the following location:

`C:\Users\ehtas\Documents\Files`

 However, in PowerShell, we were in the **"System 32"** subfolder of the main folder **"Windows**.**"** Therefore, to return to the main directory **"C**,**"** we've executed **cd..** twice. Then, we used the **cd folder\_name** command three times to get to the directory where we wanted to be.

![changing the directories in PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-directories.jpg)

 Therefore, use both commands to reach the folder you want to modify attributes for. After landing in your desired directory, type the following command after inserting the file name and your preferred date of creation:

`$(Get-Item File-name).creationtime=$(Get-Date "mm/dd/yyyy")`

 If PowerShell doesn't present any errors and takes you to the same directory again, that confirms that the attributes have been successfully changed.

![successfully changing the creation date of a file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/creation-date-has-been-changed.jpg)

 Likewise, you can change the date modified and the date accessed by typing the following two commands:

`$(Get-Item File-Name).lastaccesstime=$(Get-Date "mm/dd/yyyy")  
$(Get-Item File-Name).lastwritetime=$(Get-Date "mm/dd/yyyy")`

![Changing the last modified date in Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/last-modified-date-has-been-changed.jpg)

 Before changing the attributes, here is how a file's created, modified, and accessed dates looked:

![Showing dates of a file we are about to change in the properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dates-of-a-file-we-are-about-to-change.jpg)

 After changing them with PowerShell, here are the updated dates:

![Date created and date modified of a file successfully changed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/date-created-and-date-modified-of-a-file-successfully-changed.jpg)

 Windows makes real-time changes to attributes. Therefore, don't modify or access the file after making changes since it will change the modified and accessed dates again.

## How to Modify the Date Created, Date Accessed, and Date Modified Using Attribute Changer

 The Attribute Changer app is one of the [third-party attribute changer apps](https://www.makeuseof.com/apps-change-created-modified-date-windows/) that lets users change file attributes, including when a file was created, modified, or accessed. If changing the file attributes using PowerShell is challenging for you, here are the steps to modify them using this third-party app:

1. Go to the [official PETGES website](https://www.petges.lu/).
2. Download the full setup of Attribute Changer; do not download the portable version, as it may not function properly.
3. Once the software has been downloaded, run the setup file and follow the onscreen instructions to install it.
4. Restart your device if the software asks you to; otherwise, there's no need.
5. Navigate to the folder containing the file whose attributes you wish to modify.

1. Right-click the file and select **Change Attribute** from the context menu to open the software. If you're using Windows 11, you may need to click **Show more options** to reveal this option in the context menu.  
![opening the attribute changer app from context menu of a file in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/opening-the-attribute-changer-app-from-context-menu-of-a-file-in-windows.jpg)
2. Once the application opens, check the box beside **Modify date and time stamps** to make the date field editable.
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.
5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-want-to-speed-up-your-video-to-shorten-its-duration-and-make-it-more-entertaining-here-is-how-to-speed-up-videos-in-final-cut-pro-get-a-better/"><u>2024 Approved Want to Speed up Your Video to Shorten Its Duration and Make It More Entertaining? Here Is How to Speed up Videos in Final Cut Pro. Get a Better Alternative to FCP to Speed up Videos</u></a></li>
<li><a href="https://win11.techidaily.com/shrouded-functionality-unveiling-hidden-context-menus-in-win11/"><u>Shrouded Functionality: Unveiling Hidden Context Menus in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-windows-activation-error-0x803f700f-hurdle/"><u>Overcoming the Windows Activation Error 0X803F700f Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-natural-windows-file-sorting-settings/"><u>Restoring Natural Windows File Sorting Settings</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-unleash-creativity-mastering-tiktok-audio/"><u>[Updated] 2024 Approved  Unleash Creativity  Mastering TikTok Audio</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-misleading-game-spots-insights-galore/"><u>Decoding Misleading Game Spots: Insights Galore</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-gaming-mastering-the-art-of-fc-mascot/"><u>Step Up Your Gaming: Mastering the Art of FC Mascot</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-oneplus-12r-by-drfone-android/"><u>In 2024, How to Bypass FRP from OnePlus 12R?</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-elimination-guide-for-wsl-on-windows-11-systems/"><u>Permanent Elimination Guide for WSL on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-onedrive-server-failures-a-quick-guide/"><u>Overcoming Windows OneDrive Server Failures: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/smooth-operations-direct-backup-of-camera-roll-images-to-social-media-apps-for-2024/"><u>Smooth Operations  Direct Backup of Camera Roll Images to Social Media Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-set-longer-duration-for-your-youtube-film/"><u>[New] Set Longer Duration for Your YouTube Film</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/scripting-efficient-files-a-python-server-guide-for-windows-os/"><u>Scripting Efficient Files: A Python Server Guide for Windows OS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-compelling-narratives-with-strategic-youtube-banners/"><u>[New] 2024 Approved  Crafting Compelling Narratives with Strategic YouTube Banners</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-early-edge-tab-launches-on-windows-11/"><u>Prevent Early Edge Tab Launches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-notification-service-for-phone-link-app/"><u>Restoring Windows Notification Service for Phone Link App</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-elevate-conversational-impact-how-to-pin-messages-wisely-in-discord/"><u>[New] In 2024, Elevate Conversational Impact  How to Pin Messages Wisely in Discord</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-icon-placement-strategies/"><u>Perfect Window's Icon Placement Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/proper-methods-to-turn-windows-key-onoff/"><u>Proper Methods to Turn Windows Key On/Off</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-dormant-screen-saver-configurations-in-windows/"><u>Revitalizing Dormant Screen Saver Configurations in Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ve-engagement-with-skillful-use-of-jump-cuts-for-2024/"><u>Improve Engagement with Skillful Use of Jump Cuts for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-blur-out-distractions-free-online-photo-background-editors/"><u>Updated Blur Out Distractions Free Online Photo Background Editors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-free-and-fabulous-the-5-best-online-tone-generators-out-there/"><u>Updated Free and Fabulous The 5 Best Online Tone Generators Out There</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-twist-your-imagery-instagrams-video-rotation-guide-for-2024/"><u>[Updated] Twist Your Imagery  Instagram's Video Rotation Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-your-startup-programs-in-windows-11-for-improved-performance/"><u>How to Optimize Your Startup Programs in Windows 11 for Improved Performance</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-device-interaction-with-windows-and-galaxy/"><u>Revolutionizing Device Interaction with Windows & Galaxy</u></a></li>
</ul></div>
