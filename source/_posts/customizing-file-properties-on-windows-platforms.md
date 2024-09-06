---
title: Customizing File Properties on Windows Platforms
date: 2024-09-05T08:36:04.440Z
updated: 2024-09-06T08:36:04.440Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing File Properties on Windows Platforms
excerpt: This Article Describes Customizing File Properties on Windows Platforms
keywords: WinFilePropertyAdjustment,CustomWinFilesSettings,WindowsFilePropertiesChange,EditWindowsFileMeta,FileAttributesCustomize,WindowsMetadataEditing,FilesConfigOnWindowsOS
thumbnail: https://thmb.techidaily.com/0091dc61c65475448e6b20380c1ba19b6aec743f43714543b259bc14c7475306.jpg
---

## Customizing File Properties on Windows Platforms

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
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Likewise, you can change the date modified and the date accessed by typing the following two commands:

`$(Get-Item File-Name).lastaccesstime=$(Get-Date "mm/dd/yyyy")  
$(Get-Item File-Name).lastwritetime=$(Get-Date "mm/dd/yyyy")`

![Changing the last modified date in Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/last-modified-date-has-been-changed.jpg)

 Before changing the attributes, here is how a file's created, modified, and accessed dates looked:

![Showing dates of a file we are about to change in the properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dates-of-a-file-we-are-about-to-change.jpg)

 After changing them with PowerShell, here are the updated dates:

![Date created and date modified of a file successfully changed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/date-created-and-date-modified-of-a-file-successfully-changed.jpg)

 Windows makes real-time changes to attributes. Therefore, don't modify or access the file after making changes since it will change the modified and accessed dates again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-expert-recommendations-top-5-windows-screen-cutting-apps/"><u>[New] 2024 Approved  Expert Recommendations  Top 5 Windows Screen Cutting Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-unlock-audio-content-in-vimeo-using-mp3-technology/"><u>[New] 2024 Approved  Unlock Audio Content in Vimeo Using MP3 Technology</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-5-best-live-stream-video-conference-recorders/"><u>[Updated] In 2024, 5 Best Live Stream Video Conference Recorders</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-nokia-xr21-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-license-free-meditation-songs-your-ultimate-selection/"><u>2024 Approved  License-Free Meditation Songs – Your Ultimate Selection</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-user-biometrics-in-windows-11-for-domains/"><u>Configuring User Biometrics in Windows 11 for Domains</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-fresh-start-with-the-win11-control-panel/"><u>Crafting a Fresh Start with the Win11 Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-workings-of-runtime-brokers-in-computing/"><u>Delving Into the Workings of Runtime Brokers in Computing</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-use-of-ram-in-cross-device-service-platforms-windows-tips/"><u>Efficient Use of RAM in Cross-Device Service Platforms: Windows Tips</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-disabled-warning-unverified-adobe-in-windows/"><u>Eliminate Disabled Warning: Unverified Adobe in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-cortana-in-windows-with-vivetool/"><u>Empowering Cortana in Windows with ViveTool</u></a></li>
<li><a href="https://win11.techidaily.com/executing-a-pristine-windows-11-reboot/"><u>Executing a Pristine Windows 11 Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-navigating-folder-tabs-with-windows-11/"><u>Expert Advice on Navigating Folder Tabs with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-order-windows-arrow-restoration-guide/"><u>From Chaos to Order: Windows Arrow Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/get-inside-windows-credentials-manager-with-win11s-11-strategies/"><u>Get Inside Windows Credentials Manager with Win11's 11 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unveiling-and-managing-windows-10-actions/"><u>Guide to Unveiling & Managing Windows 10 Actions</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/here-are-different-ways-to-find-pokemon-go-trainer-codes-to-add-to-your-account-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>Here are Different Ways to Find Pokemon Go Trainer Codes to Add to Your Account On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-and-change-keyboard-layouts-in-windows-11/"><u>How to Add and Change Keyboard Layouts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-invalid-profiles-in-win11-devices/"><u>How to Address 'Invalid Profiles' In Win11 Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/identify-screenshot-storage-in-windows/"><u>Identify Screenshot Storage in Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-tecno-spark-10-4g-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-boost-your-earnings-on-youtube-shorts-a-guide/"><u>In 2024, Boost Your Earnings on YouTube Shorts  A Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-streamlining-tv-downloads-a-step-by-step-recording-approach/"><u>In 2024, Streamlining TV Downloads  A Step-by-Step Recording Approach</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-effective-policy-review-the-gpresult-methodology/"><u>Initiating Effective Policy Review: The GPResult Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-windows-10-activity-log-with-ease/"><u>Navigate Windows 10 Activity Log with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-auto-color-management-in-win11/"><u>Navigating Through Auto Color Management in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-security-restrictions-with-rufus-expertise/"><u>Navigating Windows 11'S Security Restrictions with Rufus Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/new-laptops-that-will-take-your-breath-away-ifa-2023/"><u>New Laptops That Will Take Your Breath Away - IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-network-errors-in-win11/"><u>Overcoming Steam Network Errors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-notification-management-skills-on-win-11/"><u>Perfect Your Notification Management Skills on Win 11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ps5-pro-release-on-horizon-however-many-gamers-are-happy-with-their-current-ps4-systems/"><u>PS5 Pro Release on Horizon; However, Many Gamers Are Happy with Their Current PS4 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-keyboard-errors-windows-11s-function-keys/"><u>Rectify: Keyboard Errors - Windows 11'S Function Keys</u></a></li>
<li><a href="https://win11.techidaily.com/resilience-reinstated-the-5-key-repairs-for-family-safe/"><u>Resilience Reinstated: The 5 Key Repairs for Family Safe</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-perfect-performance-to-microsoft-outlook/"><u>Restoring Perfect Performance to Microsoft Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/securely-updating-windows-without-internet/"><u>Securely Updating Windows Without Internet</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-radeon-driver-transitions-on-new-windows-11-laptops/"><u>Smooth Radeon Driver Transitions on New Windows 11 Laptops</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-guide-generating-dummy-data-sets-with-microsoft-excel/"><u>Step-by-Step Guide: Generating Dummy Data Sets with Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-input-flows-disable-mouse-acceleration-on-win-devices/"><u>Streamline Your Input Flows: Disable Mouse Acceleration on Win Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-invisible-gadget-issue-in-windows-os/"><u>Tackling Invisible Gadget Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-discretion-in-windows-11-functionality/"><u>The Art of Discretion in Windows 11 Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/the-basics-how-to-use-microsofts-phone-link-app/"><u>The Basics: How to Use Microsoft's ‘Phone Link’ App</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-ultimate-background-guide-for-online-video-calls/"><u>The Ultimate Background Guide for Online Video Calls</u></a></li>
<li><a href="https://win11.techidaily.com/top-bargain-alert-lifetime-win10-starting-at-612/"><u>Top Bargain Alert: Lifetime Win10, Starting at $6.12</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-common-22h2-windows-errors/"><u>Troubleshooting Common 22H2 Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-automating-the-openness-of-emails-in-words-reading-area/"><u>Tutorial: Automating the Openness of Emails in Word's Reading Area</u></a></li>
<li><a href="https://win11.techidaily.com/unclutter-your-taskbar-separate-groups/"><u>Unclutter Your Taskbar: Separate Groups</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-creative-potential-with-microsofts-innovative-paint-updates/"><u>Unlock Your Creative Potential with Microsoft's Innovative Paint Updates</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-def5-effective-methods-to-solve-onedrive-error-on-windows-11/"><u>Unlocking DEF5: Effective Methods to Solve OneDrive Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-computer-with-microsoft-works-for-windows/"><u>Unlocking Your Computer with Microsoft Works for WIndows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>