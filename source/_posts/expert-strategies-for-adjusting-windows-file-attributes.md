---
title: Expert Strategies for Adjusting Windows File Attributes
date: 2024-08-16T00:54:15.431Z
updated: 2024-08-17T00:54:15.431Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Strategies for Adjusting Windows File Attributes
excerpt: This Article Describes Expert Strategies for Adjusting Windows File Attributes
keywords: Window Attribute Tweak,Advanced Files Change,Optimize File Properties,Windows Permissions Edit,Data Security Enhance,File Access Control Adjust,Directory Management Strategies
thumbnail: https://thmb.techidaily.com/4c2f1c5599abfece009f925c2828de86667e5982a128d746578608e8851ede9e.jpg
---

## Expert Strategies for Adjusting Windows File Attributes

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
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Once the application opens, check the box beside **Modify date and time stamps** to make the date field editable.
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Once you've made your changes, click **Apply** to make them permanent.
5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-recording-review-and-examination/"><u>[New] 2024 Approved  Recording Review and Examination</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-top-tech-brands-in-online-recording-solutions/"><u>[New] 2024 Approved  Top Tech Brands in Online Recording Solutions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-elite-group-chat-and-webcams-the-best-selection/"><u>[New] Elite Group Chat & Webcams  The Best Selection</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-top-5-affordable-gaming-mice-and-keyboards-99plus/"><u>[New] Top 5 Affordable Gaming Mice & Keyboards $99+</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-8-linux-screenshot-utilities-compared-for-2024/"><u>[New] Top 8 Linux Screenshot Utilities Compared for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unboxing-unveiled-enhancing-customer-experiences/"><u>[New] Unboxing Unveiled  Enhancing Customer Experiences</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-enhancing-your-online-presence-with-fb-live/"><u>[Updated] 2024 Approved  Enhancing Your Online Presence with FB Live</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-how-to-make-money-on-youtube-shorts-effective-practical-ways/"><u>[Updated] 2024 Approved  How to Make Money on YouTube Shorts? [Effective Practical Ways]</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-top-10-recorders-that-wont-break-your-wallet/"><u>[Updated] 2024 Approved  Top 10 Recorders That Won't Break Your Wallet</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-balancing-acts-the-power-of-alternate-perspectives-in-crafting-engaging-reaction-videos-on-youtube-2-pov-method/"><u>[Updated] In 2024, Balancing Acts  The Power of Alternate Perspectives in Crafting Engaging Reaction Videos on YouTube (2 POV Method)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-mastering-downloads-igtv-media-for-phone-users/"><u>[Updated] Mastering Downloads  IGTV Media for Phone Users</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-ephemeral-echoes-of-facebook/"><u>2024 Approved  Ephemeral Echoes of Facebook</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-obs-tutorial-for-instagram-live-streams-your-ultimate-reference/"><u>2024 Approved  OBS Tutorial for Instagram Live Streams  Your Ultimate Reference</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-under-the-surface-sound-savers-top-6-stealthy-recorders-iosandroid/"><u>2024 Approved  Under-the-Surface Sound Savers  Top 6 Stealthy Recorders (iOS/Android)</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-windows-11s-diagnostic-features/"><u>Breathe New Life Into Windows 11'S Diagnostic Features</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-gap-fixing-laptop-and-phone-connection-discrepancies/"><u>Bridge Gap: Fixing Laptop and Phone Connection Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-connecting-your-computer-again/"><u>Bridge the Gap: Connecting Your Computer Again</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technical-gaps-fixing-faulty-win11-ccleaner/"><u>Bridging Technical Gaps: Fixing Faulty Win11 CCleaner</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-windows-explorer-tab-lapses/"><u>Bridging Windows Explorer Tab Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/bring-the-spirit-of-christmas-alive-with-these-wonderful-windows-themes/"><u>Bring the Spirit of Christmas Alive With These Wonderful Windows Themes</u></a></li>
<li><a href="https://win11.techidaily.com/browser-ram-test-showdown-top-7-lightweight-contenders/"><u>Browser RAM Test Showdown: Top 7 Lightweight Contenders</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-safe-web-environment-with-trustable-sites-in-windows-11/"><u>Building a Safe Web Environment with Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-oculus-setup-errors-with-proven-win11win10-methods/"><u>Bypass Oculus Setup Errors with Proven Win11/Win10 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-quick-access-initiate-file-explorer-via-onedrive-link/"><u>Bypass Quick Access: Initiate File Explorer via OneDrive Link</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-blocked-onedrive-fixes-for-windows-users/"><u>Bypassing Blocked OneDrive: Fixes for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-secure-answers-for-win-11s-default-administrator/"><u>Bypassing Secure Answers for Win 11'S Default Administrator</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-termination-error-a-guide-for-windows-users/"><u>Bypassing Termination Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-audible-hurdle-code-0xc00d36b4/"><u>Bypassing Windows' Audible Hurdle: Code 0Xc00d36b4</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-wsl-smart-choice/"><u>Bypassing WSL - Smart Choice</u></a></li>
<li><a href="https://win11.techidaily.com/cant-use-your-microphone-on-google-meet-for-windows-heres-why/"><u>Can’t Use Your Microphone on Google Meet for Windows? Here's Why</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-constant-pc-startup-in-bios-mode/"><u>Circumventing Constant PC Startup in BIOS Mode</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-error-0x80242016-for-updates/"><u>Circumventing Error 0X80242016 for Updates</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-obstacles-with-amd-195-setup-on-pcs/"><u>Circumventing Obstacles with AMD 195 Setup on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/classic-diablo-playbook-step-by-step-guide/"><u>Classic Diablo Playbook: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/classic-explorer-features-revival-guide/"><u>Classic Explorer Features Revival Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-to-chatting-ease-on-your-pc/"><u>Clear the Path to Chatting Ease on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-successfully-downloading-from-the-ms-store/"><u>Clearing Errors: Successfully Downloading From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-for-startup-display-in-taskbar/"><u>Clearing the Path for Startup Display in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-fixing-office-activation-errors/"><u>Clearing the Path: Fixing Office Activation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-disk-needs-format-warning-on-windows/"><u>Clearing Up 'Disk Needs Format' Warning on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-dark-screen-with-windows-webcam/"><u>Clearing Up Dark Screen with Windows Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/combat-disappearing-steam-app-graphics/"><u>Combat Disappearing Steam App Graphics</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/deciphering-the-tiers-of-royal-match-how-many-layers-does-it-have/"><u>Deciphering the Tiers of 'Royal Match': How Many Layers Does It Have?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dive-into-discreet-communications-with-duckduckgos-advanced-ai-chat-including-chatgpt-and-other-tools/"><u>Dive Into Discreet Communications with DuckDuckGo's Advanced AI Chat - Including ChatGPT and Other Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/evaluating-screencast-software-the-bandicamcamtasia-comparison/"><u>Evaluating Screencast Software  The Bandicam/Camtasia Comparison</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/expert-tips-on-producing-high-quality-facebook-video/"><u>Expert Tips on Producing High-Quality Facebook Video</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-cut-to-connect-advanced-editing-with-kinemaster-for-2024/"><u>From Cut to Connect  Advanced Editing with Kinemaster for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-vivo-x90s-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Vivo X90S to iPad | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-vivo-t2-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/innovative-strategies-for-engaging-your-audience-with-puzzles-on-instagram/"><u>Innovative Strategies for Engaging Your Audience with Puzzles on Instagram</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/maximize-youtube-views-a-comprehensible-guide-to-collaborative-videos/"><u>Maximize YouTube Views  A Comprehensible Guide to Collaborative Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/next-gen-spaceholders-unveiling-the-quintessential-cloud-providers-for-2024/"><u>Next-Gen Spaceholders  Unveiling the Quintessential Cloud Providers for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/rhythm-and-precision-crafting-tiktok-moves-on-a-mac-for-2024/"><u>Rhythm & Precision  Crafting TikTok Moves on a Mac for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-xs-max-without-passcode-easily-by-drfone-ios/"><u>Unlock iPhone XS Max Without Passcode Easily</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-honor-90-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Honor 90 Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>