---
title: "Changing File Dates in Windows: A Practical Overview"
date: 2025-01-27T22:34:13.153Z
updated: 2025-02-03T22:23:08.892Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Changing File Dates in Windows: A Practical Overview"
excerpt: "This Article Describes Changing File Dates in Windows: A Practical Overview"
keywords: Change Windows Files Date,Date Alteration Windows,Windows File Update,Windows Files Modify,File Dates Adjustment,Windows Date Changing,OS File Timestamping
thumbnail: https://thmb.techidaily.com/4a0e802a162a5a423f94ca329819be0d261aa988bda1b4b5ab8aef4726e226b5.jpg
---

## Changing File Dates in Windows: A Practical Overview

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Likewise, you can change the date modified and the date accessed by typing the following two commands:

`$(Get-Item File-Name).lastaccesstime=$(Get-Date "mm/dd/yyyy")  
$(Get-Item File-Name).lastwritetime=$(Get-Date "mm/dd/yyyy")`

![Changing the last modified date in Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/last-modified-date-has-been-changed.jpg)

 Before changing the attributes, here is how a file's created, modified, and accessed dates looked:

![Showing dates of a file we are about to change in the properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dates-of-a-file-we-are-about-to-change.jpg)

 After changing them with PowerShell, here are the updated dates:

![Date created and date modified of a file successfully changed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/date-created-and-date-modified-of-a-file-successfully-changed.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows makes real-time changes to attributes. Therefore, don't modify or access the file after making changes since it will change the modified and accessed dates again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.
5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-how-to-reverse-video-playback-on-android-phones/"><u>[New] 2024 Approved How to Reverse Video Playback on Android Phones</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-dominate-instagram-with-superior-reel-content/"><u>[New] In 2024, Dominate Instagram with Superior Reel Content</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-step-by-step-guide-to-create-engaging-thumbnails-for-your-videos-on-youtube/"><u>[Updated] 2024 Approved Step-by-Step Guide to Create Engaging Thumbnails for Your Videos on YouTube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-convenient-methods-for-storing-webinars-windows-and-mac-solutions-for-2024/"><u>[Updated] Convenient Methods for Storing Webinars Windows & Mac Solutions for 2024</u></a></li>
<li><a href="https://fox-zero.techidaily.com/aomei-fonebackup-ios-whatsapp/"><u>AOMEI FoneBackup如何在 iOS设备中轻松传输 WhatsApp信息</u></a></li>
<li><a href="https://games-able.techidaily.com/direct-controlled-races-wheels-edge-over-touchscreen-triumphs/"><u>Direct Controlled Races: Wheel's Edge Over Touchscreen Triumphs?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/finding-legal-ways-to-watch-netflix-without-paying-a-comprehensive-guide/"><u>Finding Legal Ways to Watch Netflix Without Paying: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-essential-guides-to-the-top-10-student-focused-history-vlogs/"><u>In 2024, Essential Guides to the Top 10 Student-Focused History Vlogs</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-motorola-moto-g23-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Motorola Moto G23 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/preserve-your-dvd-collection-effortlessly-with-wonderfox-dvd-ripper-and-converter-technology/"><u>Preserve Your DVD Collection Effortlessly with WonderFox DVD Ripper & Converter Technology</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-mastering-the-art-of-adding-image-watermarks-to-videos/"><u>Quick Guide: Mastering the Art of Adding Image Watermarks to Videos</u></a></li>
<li><a href="https://win11.techidaily.com/record-screenshots-and-audio-a-guide-to-capturing-video-on-your-lenovo-device/"><u>Record Screenshots and Audio: A Guide to Capturing Video on Your Lenovo Device</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-smooth-operation-in-kodi-on-windows-via-full-system-reset/"><u>Restoring Smooth Operation in Kodi on Windows via Full System Reset</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-video-merging-without-re-encoding-a-step-by-step-guide/"><u>Seamless Video Merging Without Re-Encoding: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-convert-your-multimedia-into-htc-formats-using-the-advanced-htc-video-converter-tool/"><u>Seamlessly Convert Your Multimedia Into HTC Formats Using the Advanced HTC Video Converter Tool</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-hassle-free-acquisition-of-vh1-video-content/"><u>Simple Steps to Hassle-Free Acquisition of VH1 Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-flv-videos-into-high-quality-mp4-formats-quickly/"><u>Step-by-Step Guide: Converting FLV Videos Into High-Quality MP4 Formats Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-mpg-videos-to-mp4-playback-on-microsoft-windows-systems/"><u>Step-by-Step Guide: Converting MPG Videos to MP4 Playback on Microsoft Windows Systems</u></a></li>
</ul></div>

