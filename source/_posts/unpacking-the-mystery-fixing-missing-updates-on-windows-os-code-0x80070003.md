---
title: "Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)"
date: 2024-09-05T08:26:30.708Z
updated: 2024-09-06T08:26:30.708Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)"
excerpt: "This Article Describes Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)"
keywords: Windows Update Error Code 0X80070003,Resolving Windows Missing Updates,Fix 0X80070003 in Windows OS,Unpacking Windows OS Updates Issue,Troubleshoot Update Failure (Windows),Code 0X80070003,Stop Windows Missing OS Updates Error
thumbnail: https://thmb.techidaily.com/8dec14c118d7ee81f46eabd3dcf3a5188bbf56bf80fdef23b5e5cacf3addecc5.jpg
---

## Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115935/19272" target="_top" id="2115935">
  <img src="//a.impactradius-go.com/display-ad/19272-2115935" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115935/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-supercharge-your-status-top-8-apps-for-boosting-facebook-popularity/"><u>[New] In 2024, Supercharge Your Status  Top 8 Apps for Boosting Facebook Popularity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-no-cost-mac-os-screen-tracker-for-2024/"><u>[New] No-Cost Mac OS Screen Tracker for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-snippet-storyboarding-procedure/"><u>[New] Snippet Storyboarding Procedure</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-2023s-ultimate-toolwiz-photo-suite-analysis/"><u>[Updated] 2023'S Ultimate Toolwiz Photo Suite Analysis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-strategic-use-of-twitters-wayback-machine-features/"><u>[Updated] In 2024, Strategic Use of Twitter's Wayback Machine Features</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-streamlining-the-process-of-saving-ps3-gaming-moments/"><u>[Updated] In 2024, Streamlining the Process of Saving PS3 Gaming Moments</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-the-ultimate-newbies-roadmap-building-a-channel-making-cash/"><u>[Updated] In 2024, The Ultimate Newbie's Roadmap  Building a Channel, Making Cash</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-zooms-playbook-for-precision-and-polished-youtube-conferences/"><u>[Updated] In 2024, Zoom's Playbook for Precision and Polished YouTube Conferences</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-skyline-your-videos-reach-writing-captivating-youtube-descs-using-templates/"><u>[Updated] Skyline Your Video's Reach  Writing Captivating Youtube Descs Using Templates</u></a></li>
<li><a href="https://win11.techidaily.com/1-mastering-formula-protection-a-step-by-step-guide-to-secure-your-data-in-ms-excel/"><u>1. Mastering Formula Protection: A Step-by-Step Guide to Secure Your Data in MS Excel</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphones-secret-to-quick-cost-free-red-eye-removal-revealed/"><u>2024 Approved  IPhone's Secret to Quick, Cost-Free Red-Eye Removal Revealed</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-revamped-recording-reimagined-screens-the-sprout-way/"><u>2024 Approved  Revamped Recording, Reimagined Screens - The Sprout Way</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-poco-x5-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Poco X5 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-standard-file-formats-a-step-by-step-guide-using-libreoffice/"><u>Adjusting Standard File Formats: A Step-by-Step Guide Using LibreOffice</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-microsoft-office-appearance-with-a-simple-step-by-step-guide-on-changing-themes-and-colors/"><u>Customizing Microsoft Office Appearance with a Simple Step-by-Step Guide on Changing Themes and Colors</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-displaying-the-current-date-in-microsoft-excel/"><u>Easy Guide: Displaying the Current Date in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-build-your-own-amortization-spreadsheet-with-excel/"><u>Easy Steps to Build Your Own Amortization Spreadsheet with Excel</u></a></li>
<li><a href="https://win11.techidaily.com/easy-tutorial-aligning-text-evenly-in-multi-cell-sections-of-an-excel-sheet/"><u>Easy Tutorial: Aligning Text Evenly in Multi-Cell Sections of an Excel Sheet</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-for-identifying-and-calculating-vacant-cell-values-in-ms-excel/"><u>Effective Strategies for Identifying and Calculating Vacant Cell Values in MS Excel</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-data-processing-in-microsoft-excel-with-the-introduction-of-regular-expression-capabilities/"><u>Enhanced Data Processing in Microsoft Excel with the Introduction of Regular Expression Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/excel-techniques-for-parsing-forenames-and-family-names-efficiently/"><u>Excel Techniques for Parsing Forenames & Family Names Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/get-ready-microsoft-office-2024-announced-as-a-single-purchase-option/"><u>Get Ready: Microsoft Office 2024 Announced as a Single Purchase Option</u></a></li>
<li><a href="https://youtube-help.techidaily.com/graphical-forecast-the-dominant-23-social-themes-for-2024/"><u>Graphical Forecast  The Dominant '23 Social Themes for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-oppo-reno-11-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Oppo Reno 11 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-systematically-generate-a-detailed-inventory-of-windows-login-details-and-personalized-setups/"><u>How To Systematically Generate A Detailed Inventory of Windows Login Details & Personalized Setups</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-honor-x50-gt-easily-by-drfone-android/"><u>How To Unlock a Honor X50 GT Easily?</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-resolving-looping-errors-a-guide-to-detecting-circular-references-in-excel/"><u>Identifying and Resolving Looping Errors: A Guide to Detecting Circular References in Excel</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-closing-credits-collection-free-to-subscription-choices/"><u>In 2024, Closing Credits Collection  Free to Subscription Choices</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/long-overdue-but-finally-here-the-latest-upgrade-for-microsoft-excels-cloud-version-unveiled/"><u>Long Overdue, but Finally Here: The Latest Upgrade for Microsoft Excel's Cloud Version Unveiled!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-management-in-excel-a-guide-to-advanced-sorting-and-filter-options/"><u>Mastering Data Management in Excel: A Guide to Advanced Sorting and Filter Options</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-date-calculations-adding-and-subtracting-days-with-excel/"><u>Mastering Date Calculations: Adding and Subtracting Days with Excel</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-excel-201/"><u>Mastering Excel 201</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-excel-chart-visualization-by-pinpointing-absolute-value-ranges-instantly/"><u>Mastering Excel Chart Visualization by Pinpointing Absolute Value Ranges Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-excel-data-visualization-with-easy-trendline-insertion-techniques/"><u>Mastering Excel Data Visualization with Easy Trendline Insertion Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-excel-a-step-by-step-guide-on-adding-and-calculating-percentages/"><u>Mastering Excel: A Step-by-Step Guide on Adding and Calculating Percentages</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-finance-with-microsoft-excel-determining-loan-amounts-and-repayment-schedules/"><u>Mastering Finance with Microsoft Excel: Determining Loan Amounts and Repayment Schedules</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-time-calculation-turning-minutes-and-seconds-into-decimals-with-excel-tutorials/"><u>Mastering Time Calculation: Turning Minutes and Seconds Into Decimals with Excel Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-waterfall-charts-a-step-by-step-guide-on-tailoring-visuals-in-ms-excel/"><u>Mastering Waterfall Charts: A Step-by-Step Guide on Tailoring Visuals in MS Excel</u></a></li>
<li><a href="https://driver-download.techidaily.com/overcoming-ralink-rt3290-driver-challenges-in-windows-11-8-and-7-expert-solutions/"><u>Overcoming Ralink RT3290 Driver Challenges in Windows 11, 8 & 7: Expert Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/protect-excel-worksheets-from-changes-master-the-art-of-cell-lockdown-techniques/"><u>Protect Excel Worksheets From Changes - Master the Art of Cell Lockdown Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-duplicate-and-share-spreadsheet-tables-in-excel-with-ease/"><u>Quick Guide: Duplicate and Share Spreadsheet Tables in Excel with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-adding-images-and-objects-into-your-microsoft-office-documents/"><u>Step-by-Step Guide: Adding Images and Objects Into Your Microsoft Office Documents</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-concealing-data-sections-within-microsoft-excel/"><u>Step-by-Step Guide: Concealing Data Sections Within Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-creating-a-workday-function-in-ms-excel/"><u>Step-by-Step Guide: Creating a Workday Function in MS Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-creating-visual-charts-with-microsoft-excel/"><u>Step-by-Step Guide: Creating Visual Charts with Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-designing-dynamic-table-headers-in-excel-spreadsheets/"><u>Step-by-Step Guide: Designing Dynamic Table Headers in Excel Spreadsheets</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-effective-naming-strategies-for-your-microsoft-excel-tables/"><u>Step-by-Step Guide: Effective Naming Strategies for Your Microsoft Excel Tables</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-tips-for-successfully-downloading-and-playing-fortnite-on-android-phones/"><u>Ultimate Tips for Successfully Downloading and Playing Fortnite on Android Phones</u></a></li>
</ul></div>
