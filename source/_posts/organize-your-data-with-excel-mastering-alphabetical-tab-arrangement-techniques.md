---
title: "Organize Your Data with Excel: Mastering Alphabetical Tab Arrangement Techniques"
date: 2024-08-28T00:49:33.094Z
updated: 2024-08-29T00:49:33.094Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fd60f16bf20dda981eb260766dc085349ba6360b3659bdf5766d705fbc85be65.jpg
---

## Organize Your Data with Excel: Mastering Alphabetical Tab Arrangement Techniques

If you have a large number of worksheets in your Excel workbook, it may be hard to find a specific worksheet. Sorting your worksheet tabs alphabetically would make it easier to find what your looking for.

Related: [How to Change the Color of the Worksheet Tabs in Excel](https://hardware-help.techidaily.com/get-the-latest-hp-scanjet-software-for-windows-operating-systems-quick-guide-and-downloads/) 

 In addition to organizing your worksheet tabs by [applying colors to them](https://eaxpv-info.techidaily.com/updated-harness-your-view-count-cross-platform-studio-methods-for-2024/), you can also sort them alphabetically or alphanumerically, as long as you've [applied custom names to your worksheets](https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-xiaomi-14-ultra-phone-unlock-it-now-by-drfone-android/). Unfortunately, sorting worksheet tabs alphabetically is not built in to Excel, but you can add a macro to your workbook that will allow you to sort your tabs in ascending or descending order. We’ll show you how to add a macro available on Microsoft’s support site to your Excel workbook that will sort your worksheet tabs.

![01_unsorted_tabs](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/01_unsorted_tabs.png) 

 To begin, press Alt+F11 to open the Microsoft Visual Basic for Applications (VBA) editor. Then, go to Insert > Module.

![02_selecting_insert_module](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/02_selecting_insert_module.png) 

 Copy and paste the following macro [from Microsoft](https://support.microsoft.com/en-us/kb/812386) into the module window that displays.

Sub Sort_Active_Book()

    
                    Dim i As Integer

    
                    Dim j As Integer

    
                    Dim iAnswer As VbMsgBoxResult

    
                    '

    
                    ' Prompt the user as which direction they wish to

    
                    ' sort the worksheets.

    
                    '

    
                     iAnswer = MsgBox("Sort Sheets in Ascending Order?" & Chr(10) _

    
                     & "Clicking No will sort in Descending Order", _

    
                     vbYesNoCancel + vbQuestion + vbDefaultButton1, "Sort Worksheets")

    
                     For i = 1 To Sheets.Count

    
                     For j = 1 To Sheets.Count - 1

    
                    '

    
                    ' If the answer is Yes, then sort in ascending order.

    
                    '

    
                     If iAnswer = vbYes Then

    
                     If UCase$(Sheets(j).Name) > UCase$(Sheets(j + 1).Name) Then

    
                     Sheets(j).Move After:=Sheets(j + 1)

    
                     End If

    
                    '

    
                    ' If the answer is No, then sort in descending order.

    
                    '

    
                     ElseIf iAnswer = vbNo Then

    
                     If UCase$(Sheets(j).Name) < UCase$(Sheets(j + 1).Name) Then

    
                     Sheets(j).Move After:=Sheets(j + 1)

    
                     End If

    
                     End If

    
                     Next j

    
                     Next i

    
                    End Sub

 The VBA editor automatically names each module with a number on the end, such as Module1, Module2, etc. You can simply accept the default name of the module. However, if you plan to add other macros to your workbook, it’s a good idea to rename each module so you know what they are. We’ll rename our module to show you how.

![04_module1_in_modules_list](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/04_module1_in_modules_list.png) 

 To rename the module, select the text in the Name box for the module under Properties in the left pane.

![05_changing_module_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/05_changing_module_name.png) 

 Type a name for the module in the Name box and press Enter. Note that the module name cannot contain spaces.

![06_typing_new_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/06_typing_new_name.png) 

 The name of the module changes in the Modules list under Project in the left pane.

![07_name_changed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/07_name_changed.png) 

 Close the VBA editor by going to File > Close and Return to Microsoft Excel.

![08_file_close_and_return_to_excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/08_file_close_and_return_to_excel.png) 

 Now, we’re going to run the macro to sort our tabs. Press Alt+F8 to access the list of macros on the Macro dialog box. Select the macro in the list (in our case there is only one macro), and click “Run”.

![09_running_macro](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/09_running_macro.png) 

 The following dialog box displays, allowing you to choose whether you want to sort your worksheets in ascending or descending order. We want to sort them in ascending order, so we click “Yes”.

![10_sort_worksheets_dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/10_sort_worksheets_dialog.png) 

 The worksheet tabs are now arranged in alphabetical order.

![11_sorted_tabs](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/11_sorted_tabs.png) 

 The macro you added is part of your workbook now, but when you save it, you’ll probably see the following dialog box. That’s because you saved your workbook as an .xlsx file, which is a normal Excel workbook format that does not include macros. To include macros in your workbook, and be able to run them, you must save your workbook as a macro-enabled workbook, or an .xlsm file. To do this, click “No” on this dialog box.

![12_warning_about_saving_macro_enabled_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/12_warning_about_saving_macro_enabled_file.png) 

 The Save As dialog box displays. Navigate to where you want to save the macro-enabled workbook, if you’re not already in that folder. Select “Excel Macro-Enabled Workbook (\*.xlsm)” from the “Save as type” drop-down list.

![13_selecting_excel_macro_enabled_workbook](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/13_selecting_excel_macro_enabled_workbook.png) 

 Click “Save”.

![14_clicking_save](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/14_clicking_save.png) 

 If you don’t save the workbook as a macro-enabled workbook (.xlsm file), the macro you added will be deleted. You might want to delete the .xlsx version of your workbook so you don’t forget to use the .xlsm version of your workbook if you want to add more worksheet tabs and sort them again using the macro. You can always save the workbook as an .xlsx file again if you don’t want to use macros anymore.

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
<li><a href="https://extra-information.techidaily.com/new-bridging-gaps-building-relationships-with-your-audience/"><u>[New] Bridging Gaps  Building Relationships with Your Audience</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-sprint-through-photo-composition-googles-easy-way/"><u>[Updated] 2024 Approved  Sprint Through Photo Composition - Google's Easy Way</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unleash-potential-superior-strategies-for-personalized-facebook-profiles/"><u>[Updated] In 2024, Unleash Potential  Superior Strategies for Personalized Facebook Profiles</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-guide-to-writing-captivating-docu-scripts/"><u>2024 Approved  Step-By-Step Guide to Writing Captivating Docu-Scripts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/determining-peak-listener-engagement-days/"><u>Determining Peak Listener Engagement Days</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-demystified-guiding-you-through-win11-upgrades/"><u>DevHome Demystified: Guiding You Through Win11 Upgrades</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-youtube-traffic-best-hash-tactics-explained/"><u>Elevate Your YouTube Traffic  Best Hash Tactics Explained</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-ms-resouce-text-error-on-windows-11/"><u>Eliminating Ms-Resouce Text Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-unsupported-windows-hello-scanner-mismatch/"><u>Eliminating the Unsupported Windows Hello Scanner Mismatch</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-isdonedll-problem-steps/"><u>Eliminating Windows 11'S ISDone.dll Problem Steps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/empower-your-music-library-cds-in-wmp/"><u>Empower Your Music Library  CDs in WMP</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-advice-overcoming-known-issues-with-your-graphics-driver/"><u>Expert Advice: Overcoming 'Known Issues with Your Graphics Driver'</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-fixing-failed-windows-mmc-creations/"><u>Expert Guide to Fixing Failed Windows MMC Creations</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-startup-functionality-for-a-smooth-windows-11-launch/"><u>Fine-Tuning Startup Functionality for a Smooth Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-iphoneipad-photo-import-error-a-compreayers-approach-on-w11/"><u>Fixing iPhone/iPad Photo Import Error: A Compreayer’s Approach on W11</u></a></li>
<li><a href="https://win11.techidaily.com/halt-unprompted-gaming-suggestions-on-windows-11/"><u>Halt Unprompted Gaming Suggestions on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/improve-visual-identification-displaying-this-pc-icon/"><u>Improve Visual Identification: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-access-your-favorites-anytime-the-leading-6-free-video-downloaders/"><u>In 2024, Access Your Favorites Anytime  The Leading 6 Free Video Downloaders</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-online-companion-fb-stories-saver/"><u>In 2024, Online Companion  Fb Stories Saver</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-the-newest-compatible-epson-v39-drivers-for-smooth-operations-on-win-7810-systems/"><u>Install the Newest Compatible Epson V39 Drivers for Smooth Operations on Win 7/8/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-new-window-11-the-best-modifications-for-an-optimized-experience/"><u>Master Your New Window 11: The Best Modifications for an Optimized Experience</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-with-sticky-notes-in-w11w10/"><u>Maximize Productivity with Sticky Notes in W11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-back-to-your-copilot-in-ws11-spacecraft/"><u>Navigate Back to Your Copilot in WS11 Spacecraft</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-new-era-of-interactive-technology-between-pc-and-galaxy/"><u>Navigating a New Era of Interactive Technology Between PC & Galaxy</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/navigating-hashtag-use-for-maximum-marketing-reach/"><u>Navigating Hashtag Use for Maximum Marketing Reach</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-clipboard-utility-in-windows-11-pcs/"><u>Optimizing Clipboard Utility in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-desk-view-including-this-pc-on-the-screen/"><u>Personalize Desk View: Including 'This PC' On the Screen</u></a></li>
<li><a href="https://win11.techidaily.com/securing-write-rights-to-steam-directories-with-windows-11/"><u>Securing Write Rights to Steam Directories with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-a-unresponsive-discord-overlay-in-windows/"><u>Solving the Puzzle of a Unresponsive Discord Overlay in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sound-system-upgrade-with-atmos-on-win-1011/"><u>Streamlined Sound System Upgrade with Atmos on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sign-in-with-windows-hello-biometrics/"><u>Streamlining Sign-In with Windows Hello Biometrics</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-11-whiz-11-common-problems-solutions-revealed/"><u>The Windows 11 Whiz: 11 Common Problems, Solutions Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/top-factors-for-choosing-windows-10-over-the-latest-operating-system-win11/"><u>Top Factors for Choosing Windows 10 over the Latest Operating System - Win11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-guide-how-to-update-your-hp-laserjet-p3015-printer-software-for-windows-users/"><u>Ultimate Guide: How to Update Your HP LaserJet P3015 Printer Software for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-selecthighlight-capabilities-in-windows-pdf-viewer/"><u>Unblock Select/Highlight Capabilities in Windows' PDF Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-vanishing-printmanagement-in-windows/"><u>Unraveling the Mystery of Vanishing 'Printmanagement' In Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->