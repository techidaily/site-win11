---
title: "Fine-Tuning File Properties: A Window'ayer's Manual"
date: 2024-08-15T23:57:25.728Z
updated: 2024-08-16T23:57:25.728Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fine-Tuning File Properties: A Window'ayer's Manual"
excerpt: "This Article Describes Fine-Tuning File Properties: A Window'ayer's Manual"
keywords: File Property Adjustments,Windows File Settings Guide,Optimize File Attributes,Advanced File Configurations,Enhance File Properties,File Customization Techniques,Mastering File Settings
thumbnail: https://thmb.techidaily.com/950d846f8fcee250021d944b4596b6aafb3f396fb97820df6fae0f8fc53f28aa.jpg
---

## Fine-Tuning File Properties: A Window'ayer's Manual

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

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
2. Once the application opens, check the box beside **Modify date and time stamps** to make the date field editable.
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-building-a-diverse-content-portfolio-on-youtube-shorts/"><u>[New] In 2024, Building a Diverse Content Portfolio on YouTube Shorts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-motion-assessment-2023/"><u>[New] In-Depth Motion Assessment 2023</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-instagrams-algorithm-unlocked-optimizing-your-reels/"><u>[New] Instagram’s Algorithm Unlocked  Optimizing Your Reels</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-swift-image-polishing-the-best-ios-tools-for-removing-obstructions/"><u>[New] Swift Image Polishing  The Best iOS Tools for Removing Obstructions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723013995810-solved-counter-strike-2-cs2-crashing-on-pc-2024-fixes/"><u>[Solved] Counter-Strike 2 (CS2) Crashing on PC – 2024 Fixes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-how-to-make-a-cooking-video-in-steps-an-ultimate-guide-for-2024/"><u>[Updated] How to Make a Cooking Video in Steps - an Ultimate Guide for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-capturing-the-action-top-four-ways-to-record-on-xbox-one/"><u>[Updated] In 2024, Capturing the Action  Top Four Ways to Record on Xbox One</u></a></li>
<li><a href="https://fox-direct.techidaily.com/a-strategic-approach-to-increase-likes-on-your-tiktok-video-content/"><u>A Strategic Approach to Increase 'Likes' On Your TikTok Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-configuring-windows-data-sources-by-odbc/"><u>Accessing and Configuring Windows Data Sources by ODBC</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-an-unadulterated-system-restart-in-windows-11/"><u>Achieving an Unadulterated System Restart in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ancestry-unveiled-7-enduring-features-of-windows-11/"><u>Ancestry Unveiled: 7 Enduring Features of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-errors-with-proper-use-of-winservicesexe/"><u>Avoiding Errors with Proper Use of Winservices.exe</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-grouped-taskbar-symbols-on-windows-11/"><u>Clearing Grouped Taskbar Symbols on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-for-bulk-folder-formation-in-windows-1011/"><u>Efficient Methods for Bulk Folder Formation in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-file-damaged-message-error-0x80070570-in-windows-oses/"><u>Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-the-disparity-between-remote-windows-upgrades-and-purchases/"><u>Evaluating the Disparity Between Remote Windows Upgrades & Purchases</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/exclusive-review-top-6-screen-recorders-for-mac/"><u>Exclusive Review  Top 6 Screen Recorders for Mac</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/fives-best-quick-reliable-time-lapse-tools-for-2024/"><u>Five's Best  Quick, Reliable Time-Lapse Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-repairing-windows-based-pen-tablets/"><u>Guide: Repairing Windows-Based Pen Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-overcoming-geforce-nows-xc0f1103f-problem-in-win11/"><u>Guides to Overcoming GeForce Now’s Xc0f1103f Problem in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-permission-restrictions-and-open-hidden-folders/"><u>How to Disable Permission Restrictions and Open Hidden Folders</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-11-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 11 & 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-cutting-edge-apps-top-10-for-editing-youtube-shorts/"><u>Ideal Cutting Edge Apps  Top 10 for Editing Youtube Shorts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-fix-apple-iphone-12-stuck-on-data-transfer-verified-solution-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Fix Apple iPhone 12 Stuck on Data Transfer Verified Solution! | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instant-setup-acquiring-adobe-reader-via-ms-store/"><u>Instant Setup: Acquiring Adobe Reader via MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/keep-it-neat-how-to-make-windows-recycle-bin-self-cleanse/"><u>Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-amd-gpu-driver-support-for-windows-operating-systems-windows-10117/"><u>Latest AMD GPU Driver Support for Windows Operating Systems (Windows 10/11/7)</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-basics-windows-system-configuration/"><u>Master the Basics: Windows System Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-taskbar-size-tweaks/"><u>Mastering Windows 11 Taskbar Size Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-key-combinations-for-effortless-recalibration/"><u>Mastering Windows: Key Combinations for Effortless Recalibration</u></a></li>
<li><a href="https://win11.techidaily.com/organize-your-workspace-attaching-this-pc-icon-to-desktop/"><u>Organize Your Workspace: Attaching 'This PC' Icon to Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-approach-to-disable-unnecessary-windows-11-services/"><u>Proactive Approach to Disable Unnecessary Windows 11 Services</u></a></li>
<li><a href="https://win11.techidaily.com/procedures-for-resolving-unresponsive-installation-on-windows-os/"><u>Procedures for Resolving Unresponsive Installation on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-crowded-taskbar-image-space-in-windows-11/"><u>Resetting Crowded Taskbar Image Space in Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-frame-drops-and-lag-in-aoe-iv-a-step-by-step-guide/"><u>Resolving Frame Drops and Lag in AoE IV: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-power-user-permissions-issues-in-windows-os/"><u>Resolving Power-User Permissions Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/screen-notes-made-easy-winning-sticky-pad-solutions-for-pc/"><u>Screen Notes Made Easy: Winning Sticky Pad Solutions for PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/show-your-appreciation-budget-friendly-video-closings-for-2024/"><u>Show Your Appreciation  Budget-Friendly Video Closings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/silence-windows-software-update-messages/"><u>Silence Windows Software Update Messages</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mitigate-application-crashes-unhandled-exception-error/"><u>Steps to Mitigate Application Crashes: Unhandled Exception Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-semaphore-timeout-period-ended-in-windows-1011/"><u>Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/stop-flickering-mouse-immediate-troubleshooting-guide/"><u>Stop Flickering Mouse - Immediate Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-blue-screen-errors-with-vmware-on-win11/"><u>Strategies to Address Blue Screen Errors with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/suppress-sound-enhancement-in-windows-os/"><u>Suppress Sound Enhancement in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/swift-steps-to-elevate-account-type/"><u>Swift Steps To Elevate Account Type</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/time-traveling-tactics-top-7-historic-battles-reimagined/"><u>Time-Traveling Tactics  Top 7 Historic Battles Reimagined</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-making-ai-images-with-paint-tool-sai/"><u>Transform Windows 11: Making AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-mitigating-roblox-error-403-for-pc-users/"><u>Understanding & Mitigating Roblox Error 403 for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-textual-form-from-vocal-input-in-windows-via-whisper/"><u>Unlock Textual Form From Vocal Input in Windows via Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-taskbar-while-running-full-screen-edges/"><u>Unveiling Hidden Taskbar While Running Full Screen Edges</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-the-lock-screen-timeout-stops-working-on-windows/"><u>What to Do if the Lock Screen Timeout Stops Working on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/why-excel-fails-to-open-in-windows-notepad/"><u>Why Excel Fails to Open in Windows Notepad?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10plus-users-unlocking-the-secrets-of-your-ram-type/"><u>Windows 10+ Users: Unlocking the Secrets of Your RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/windows-struggles-lack-of-drive-letters-explained-and-cured/"><u>Windows Struggles: Lack of Drive Letters Explained & Cured</u></a></li>
</ul></div>
