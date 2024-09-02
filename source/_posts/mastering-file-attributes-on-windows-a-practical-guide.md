---
title: "Mastering File Attributes on Windows: A Practical Guide"
date: 2024-09-01T04:36:41.267Z
updated: 2024-09-02T04:36:41.267Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering File Attributes on Windows: A Practical Guide"
excerpt: "This Article Describes Mastering File Attributes on Windows: A Practical Guide"
keywords: WinFileAttrsTutorial,MasterWinAttributes,WindowsFileGuide,MasterFileSettings,AttributesControlWindows,FileAttrsPracticalUse,OptimizeWinAttrs
thumbnail: https://thmb.techidaily.com/2bb5e1bc170b8c3f4a6ce1aff27e49a67b4dbeb274ccf0d0ed18fa3d929b62b2.jpg
---

## Mastering File Attributes on Windows: A Practical Guide

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

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-standout-on-social-media-top-30-memorable-tiktok-usernames-for-views/"><u>[New] 2024 Approved  Standout on Social Media  Top 30 Memorable TikTok Usernames for Views</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-taming-twitch-audio-for-top-notch-streaming-saves/"><u>[New] 2024 Approved  Taming Twitch Audio for Top-Notch Streaming Saves</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-comparing-multimedia-software-vlcs-stand-against-mx/"><u>[New] In 2024, Comparing Multimedia Software  VLC's Stand Against MX</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-essential-knowledge-how-io-screen-recorder-works/"><u>[Updated] 2024 Approved  Essential Knowledge  How Io Screen Recorder Works</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-guffaw-guide-the-leading-text-generator-companions/"><u>[Updated] Guffaw Guide  The Leading Text Generator Companions</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-master-the-art-of-video-cuts-essential-tools-for-mac-users/"><u>[Updated] In 2024, Master the Art of Video Cuts  Essential Tools for Mac Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-streamlining-your-youtube-tracks-a-sound-guide/"><u>[Updated] Streamlining Your YouTube Tracks  A Sound Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-top-10-trending-videos-on-twitter/"><u>[Updated] Top 10 Trending Videos on Twitter</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-empty-cell-copies-master-the-shortcuts-for-efficient-data-transfer-in-ms-excel/"><u>Avoiding Empty Cell Copies: Master the Shortcuts for Efficient Data Transfer in MS Excel</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-infinix-smart-8-pro-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Infinix Smart 8 Pro? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-tutorial-on-verifying-if-an-email-was-opened-via-gmail/"><u>Comprehensive Tutorial on Verifying If an Email Was Opened via Gmail</u></a></li>
<li><a href="https://win11.techidaily.com/crucial-excel-tricks-you-need-to-know-for-effective-data-input/"><u>Crucial Excel Tricks You Need to Know for Effective Data Input</u></a></li>
<li><a href="https://win11.techidaily.com/easily-arrange-spreadsheet-cells-based-on-shade-with-excels-color-feature/"><u>Easily Arrange Spreadsheet Cells Based on Shade with Excel's Color Feature</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-snap-windows-security-messages/"><u>Efficient Methods to Snap Windows' Security Messages</u></a></li>
<li><a href="https://blog-min.techidaily.com/einfach-und-schnell-konvertieren-sie-ihr-acsm-gewahrtes-ebook-ins-universelle-epub-dateiformat/"><u>Einfach Und Schnell: Konvertieren Sie Ihr ACSM-Gewährtes eBook Ins Universelle EPUB-Dateiformat</u></a></li>
<li><a href="https://win11.techidaily.com/end-the-paper-to-excel-transfer-hassle-with-our-simple-phone-trick/"><u>End the Paper-to-Excel Transfer Hassle with Our Simple Phone Trick</u></a></li>
<li><a href="https://win11.techidaily.com/excel-essentials-a-step-by-step-guide-to-manipulating-dates-by-addingsubtracting-them/"><u>Excel Essentials: A Step-by-Step Guide to Manipulating Dates by Adding/Subtracting Them</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tips-and-tricks-effectively-displaying-data-with-icon-sets-for-clarity-and-impact/"><u>Excel Tips & Tricks: Effectively Displaying Data with Icon Sets for Clarity and Impact</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tips-leveraging-the-power-of-scenario-analysis-with-microsoft-excels-tools/"><u>Excel Tips: Leveraging the Power of Scenario Analysis with Microsoft Excel’s Tools</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tricks-writing-your-own-function-to-count-business-days/"><u>Excel Tricks: Writing Your Own Function to Count Business Days</u></a></li>
<li><a href="https://win11.techidaily.com/excel-the-perfect-alternative-for-non-wearable-tech-enthusiasts-to-monitor-their-wellness/"><u>Excel: The Perfect Alternative for Non-Wearable Tech Enthusiasts to Monitor Their Wellness</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-and-tricks-leveraging-the-power-of-text-splitting-in-excel/"><u>Expert Tips and Tricks: Leveraging the Power of Text Splitting in Excel</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-cleaning-up-smart-tags-in-your-excel-spreadsheets/"><u>Expert Tips for Cleaning Up Smart Tags in Your Excel Spreadsheets</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-vivo-y02t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/genuine-deal-alert-claim-your-50-savings-on-microsoft/"><u>Genuine Deal Alert: Claim Your 50%% Savings on Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-highlighting-incorrect-values-using-circular-boundaries-in-excel-spreadsheets/"><u>Guide to Highlighting Incorrect Values Using Circular Boundaries in Excel Spreadsheets</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-roblox-needs-to-quit-error-on-windows/"><u>How to Fix the “Roblox Needs to Quit” Error on Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-resolve-game-crash-issues-a-step-by-step-fix-for-genshin-impact-on-desktop-systems/"><u>How to Resolve Game-Crash Issues: A Step-by-Step Fix for Genshin Impact on Desktop Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-special-features-virtual-location-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Honor 90 Lite? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-grasping-the-metaverse-a-look-at-6-in-depth-illustrations/"><u>In 2024, Grasping the Metaverse  A Look at 6 In-Depth Illustrations</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-mastering-deleted-yt-content-two-simplified-approaches/"><u>In 2024, Mastering Deleted YT Content  Two Simplified Approaches</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/latest-tech-news-anticipating-new-releases-from-google-and-samsung-telecoms/"><u>Latest Tech News: Anticipating New Releases From Google and Samsung Telecoms</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-financial-formatting-a-step-by-step-guide-to-applying-accounting-number-styles-in-excel/"><u>Mastering Financial Formatting: A Step-by-Step Guide to Applying Accounting Number Styles in Excel</u></a></li>
<li><a href="https://win11.techidaily.com/organize-your-data-with-excel-mastering-alphabetical-tab-arrangement-techniques/"><u>Organize Your Data with Excel: Mastering Alphabetical Tab Arrangement Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-transferring-data-between-sheets-using-microsoft-excel/"><u>Simple Steps: Transferring Data Between Sheets Using Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-data-visualization-with-excel-2010-your-step-by-step-sparkline-tutorial/"><u>Simplify Data Visualization with Excel 2010: Your Step-by-Step Sparkline Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-alphabetizing-excel-sheet-tab-names-efficiently/"><u>Step-by-Step Guide: Alphabetizing Excel Sheet Tab Names Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-automatically-populating-date-columns-in-excel/"><u>Step-by-Step Guide: Automatically Populating Date Columns in Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-incorporating-a-trendline-into-your-microsoft-excel-data-analysis/"><u>Step-by-Step Guide: Incorporating a Trendline Into Your Microsoft Excel Data Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-tallying-selections-with-excels-formulas/"><u>Step-by-Step Guide: Tallying Selections with Excel's Formulas</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-tutorial-on-controlling-information-input-in-microsoft-excel-through-data-validation-rules/"><u>Step-by-Step Tutorial on Controlling Information Input in Microsoft Excel Through Data Validation Rules</u></a></li>
<li><a href="https://facebook.techidaily.com/the-key-to-reaching-wider-audiences-on-fb-groups/"><u>The Key to Reaching Wider Audiences on FB Groups</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-users-handbook-for-coupling-amazons-fire-stick-with-a-high-quality-projector/"><u>The User's Handbook for Coupling Amazon's Fire Stick with a High-Quality Projector</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/transform-your-channels-income-the-monetization-magic-with-500plus-fans-for-2024/"><u>Transform Your Channel's Income  The Monetization Magic with 500+ Fans for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unifying-data-points-merging-text-from-various-excel-cells-into-a-single-cell/"><u>Unifying Data Points: Merging Text From Various Excel Cells Into a Single Cell</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>