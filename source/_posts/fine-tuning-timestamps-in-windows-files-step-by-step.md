---
title: "Fine-Tuning Timestamps in Windows Files: Step by Step"
date: 2024-10-08T03:37:59.278Z
updated: 2024-10-09T11:35:25.835Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fine-Tuning Timestamps in Windows Files: Step by Step"
excerpt: "This Article Describes Fine-Tuning Timestamps in Windows Files: Step by Step"
keywords: Timestamp Editing Windows,Windows File Time Adjustment,Optimize Windows File Dates,Fine-Tune Windows Timestamps,Correct Windows File Times,Windows Date Correction Steps,Sync Windows File Timestamps
thumbnail: https://thmb.techidaily.com/f755ebc6fd74e541b86783b8f288eb9ebe73ceda235653be011e1c74d43e6c3e.jpg
---

## Fine-Tuning Timestamps in Windows Files: Step by Step

 Windows keeps a record of when a file was created, who authored it, and when it was last modified. This information is known as file attributes and can be used to sort files by date, author name, and other parameters.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.
5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-5-emulation-suites-to-experience-sonys-ps1-library-for-2024/"><u>[New] Top 5 Emulation Suites to Experience Sony's PS1 Library for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-top-vr-bikes-to-check-out/"><u>[Updated] 2024 Approved Top VR Bikes to Check Out</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-carryminati-unmasked-the-monetary-milestones-for-2024/"><u>[Updated] CarryMinati Unmasked The Monetary Milestones for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-look-at-vsco-photo-craftsmanship/"><u>2024 Approved In-Depth Look at VSCO Photo Craftsmanship</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-verifying-your-youtube-sign-in-details/"><u>2024 Approved Verifying Your YouTube Sign-In Details</u></a></li>
<li><a href="https://win11.techidaily.com/3-effective-methods-to-enhance-windows-ram-usage/"><u>3 Effective Methods to Enhance Windows' RAM Usage</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-open-the-file-or-folder-properties-in-windows/"><u>6 Ways to Open the File or Folder Properties in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-open-the-sound-settings-in-windows-11/"><u>9 Ways to Open the Sound Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-memory-shortage-in-the-magical-school-of-hogwarts-game/"><u>Addressing Memory Shortage in The Magical School of Hogwarts Game</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-solutions-starting-your-software-on-windows-effortlessly/"><u>Alternative Solutions: Starting Your Software on Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/averting-error-22-disable-situation-in-windows-11-settings/"><u>Averting Error 22 Disable Situation in Windows 11 Settings</u></a></li>
<li><a href="https://games-able.techidaily.com/delay-perks-in-video-game-launches/"><u>Delay Perks in Video Game Launches</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Motorola Edge 40? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-comprehensively-reviewing-youtubes-restrictions-vs-cc-flexibility/"><u>In 2024, Comprehensively Reviewing YouTube's Restrictions Vs. CC Flexibility</u></a></li>
<li><a href="https://win11.techidaily.com/1719361199591-navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/win-over-gamepad-woes-fixing-the-steelseries-gg-engine-compatibility-issues-on-windows-1011/"><u>Win Over Gamepad Woes: Fixing the SteelSeries GG (Engine) Compatibility Issues on Windows 10/11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    