---
title: Installing Windows Compressed Archive (CAB) Files Simplified
date: 2024-09-13T02:07:15.162Z
updated: 2024-09-16T20:08:28.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Installing Windows Compressed Archive (CAB) Files Simplified
excerpt: This Article Describes Installing Windows Compressed Archive (CAB) Files Simplified
keywords: CAB Installation Guide,WinZip CAB Extract,Simplify Cab File,Easy CabFile Setup,Archive File Windows,Cabfile ManageTool,Streamlined CabArchive
thumbnail: https://thmb.techidaily.com/dfca7fb0aa6438e6377385ff2f472549907a4325f08f8d8aadbe962a7502b81d.jpg
---

## Installing Windows Compressed Archive (CAB) Files Simplified

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is a Windows CAB File?

 A CAB file or Cabinet file is a common archive file format used by Microsoft. It contains the compressed version of different files, folders, and even other cabinet files. Microsoft uses these files to distribute Windows, drivers, and UWP app updates. However, you can also use it to store other forms of data, such as images, videos, and documents.

 A CAB file is compressed using the Microsoft Cabinets Compression Format (MCF), which ensures that you can easily decompress it without losing the data stored in it. It can also be signed with digital certificates, allowing to maintain the authenticity and integrity of the file.

 CAB files are recognized by their first four bytes, which are the [ASCII characters](https://www.makeuseof.com/what-is-ascii-text/) MSCF. You can store up to 65,535 folders in a CAB file, with each folder having a storage capacity of 65,535 files.

 Now that you have a brief understanding of CAB files, let's check out how you can install it on Windows 11\.

## How to Install a CAB File on Windows 11

 You can easily install a CAB file on Windows 11 using Command Prompt and Windows PowerShell. In the Command Prompt method, you'll have to use the [DISM command](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/). Whereas, in the PowerShell method, you'll use the Add-WindowsPackage command.

 Here's how to install a CAB file using Command Prompt.

1. Navigate to the CAB file location on your computer.
2. Right-click the CAB file, and choose **Copy as path**.  
![Copy as path option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/copy-as-path-option.jpg)
3. Press **Win** key to open the **Start Menu**, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
4. In the elevated Command Prompt window, type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`dism /Online /Add-Package /PackagePath:"CAB location"`  
![CMD window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cmd-window.jpg)

 Once the installation is complete, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) to see the changes.

 If you want to install a CAB file using Windows PowerShell, follow these instructions:

1. Open the Start Menu, type **Windows PowerShell**, and choose **Run as administrator** from the right pane.
2. Type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`Add-WindowsPackage -Online -PackagePath "CAB location"  
`  
![Powershell window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powershell-window.jpg)

 That's it. PowerShell will install the content of the CAB file on your computer.

## How to Install Driver Updates From a CAB File

 If you have downloaded a driver update, which is a CAB file, you can install it using the following instructions:

1. Double-click the CAB file to view its contents.
2. Press **Ctrl + A** to select all the files, right-click, and choose **Extract**.  
![Extract option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/extract-option.jpg)
3. Choose the location where you want to extract the contents of the CAB file and click **Extract**.
4. Press **Win + X** hotkey to open the Power User menu and choose **Device Manager**.
5. Right-click the device for which you have downloaded the driver update and choose **Update driver**.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/update-driver.jpg)
6. Click **Browse my computer for drivers**.  
![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  
![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/ed-achieve-more-engagement-on-youtube-learn-the-best-thumbnail-size/"><u>[Updated] Achieve More Engagement on YouTube Learn the Best Thumbnail Size</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-snapchat-enhancing-images-and-videos/"><u>[Updated] Mastering Snapchat Enhancing Images & Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-anonymous-advantage-in-instagram-viewing/"><u>[Updated] The Anonymous Advantage in Instagram Viewing</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-more-quiet-pcs-how-to-restore-sound-after-windows-11-update/"><u>No More Quiet PCs: How to Restore Sound After Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-file-protection-with-windows-password-practices/"><u>Optimize Your File Protection with Windows Password Practices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-notice-errors-in-phone-links-windows-functionality/"><u>Overcoming No-Notice Errors in Phone Link's Windows Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-dealing-with-your-license-is-about-to-end-in-win11/"><u>Steps for Dealing with 'Your License Is About to End' In Win11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-connection-issues-how-to-tell-if-blizzards-battlenet-server-is-down/"><u>Troubleshooting Connection Issues: How To Tell If Blizzard's Battle.Net Server Is Down</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    