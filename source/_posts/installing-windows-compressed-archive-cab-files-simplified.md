---
title: Installing Windows Compressed Archive (CAB) Files Simplified
date: 2024-09-18T03:55:28.746Z
updated: 2024-09-21T22:43:21.857Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1934292/19272" target="_top" id="1934292">
  <img src="//a.impactradius-go.com/display-ad/19272-1934292" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934292/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-converting-ordinary-images-into-artistic-hdr-works/"><u>[Updated] 2024 Approved Converting Ordinary Images Into Artistic HDR Works</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-exploring-lgs-ultra-clear-4k-screen-capabilities-for-2024/"><u>[Updated] Exploring LG's Ultra-Clear 4K Screen Capabilities for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-minecraft-survival-shelter-mastery/"><u>[Updated] Minecraft Survival Shelter Mastery</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-samsung-galaxy-m34-5g-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from Samsung Galaxy M34 5G</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-iphone-12-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iPhone 12 Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-track-imei-number-of-samsung-galaxy-m54-5g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Samsung Galaxy M54 5G Through Google Earth?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-packaging-as-a-marketing-tool/"><u>In 2024, Packaging as a Marketing Tool</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-nubia-red-magic-8s-pro-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-and-using-brstm-audio-format/"><u>Step-by-Step Guide: Converting and Using BRSTM Audio Format</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-gxf-files-into-mp4-format-and-more/"><u>Step-by-Step Guide: Converting GXF Files Into MP4 Format & More</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-streaming-mp4-videos-seamlessly-on-your-apple-tv/"><u>Step-by-Step Guide: Streaming MP4 Videos Seamlessly on Your Apple TV</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-guide-cost-free-movie-trimming-across-platforms-windows-mac-online/"><u>Streamlined Guide: Cost-Free Movie Trimming Across Platforms (Windows, Mac, Online)</u></a></li>
<li><a href="https://win11.techidaily.com/successful-conversion-transforming-m4a-files-into-mp4-for-easy-video-uploads/"><u>Successful Conversion: Transforming M4A Files Into MP4 for Easy Video Uploads!</u></a></li>
<li><a href="https://win11.techidaily.com/three-simple-methods-capturing-your-creative-moments-with-youtube-shorts-from-your-computer/"><u>Three Simple Methods: Capturing Your Creative Moments with YouTube Shorts From Your Computer</u></a></li>
</ul></div>

