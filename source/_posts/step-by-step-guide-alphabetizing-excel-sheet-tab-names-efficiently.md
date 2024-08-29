---
title: "Step-by-Step Guide: Alphabetizing Excel Sheet Tab Names Efficiently"
date: 2024-08-28T00:49:45.098Z
updated: 2024-08-29T00:49:45.098Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f999915018347bdff47350b20a165acd94706d7edbf7c9a39198b21a53e266f6.jpg
---

## Step-by-Step Guide: Alphabetizing Excel Sheet Tab Names Efficiently

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-how-to-make-a-youtube-trailer-by-filmora/"><u>[New] 2024 Approved  How to Make a YouTube Trailer by Filmora</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mastering-zoom-for-podcast-recordings-a-step-by-step-guide-for-2024/"><u>[New] Mastering Zoom for Podcast Recordings  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-sprinting-to-victory-key-moments-from-2-omics-games/"><u>[New] Sprinting to Victory  Key Moments From 2 Omics Games</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-srt-to-sub-shift-expert-strategies-and-actions/"><u>[New] SRT to SUB Shift  Expert Strategies & Actions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-effortless-recording-of-netflix-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Effortless Recording of Netflix  A Step-by-Step Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-end-of-struggle-operational-obs-camera/"><u>[Updated] End of Struggle  Operational OBS Camera</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleashing-the-full-power-of-apple-podcasts-downloads/"><u>2024 Approved  Unleashing the Full Power of Apple Podcasts Downloads</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-itel-p55-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Itel P55</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-assessment-of-the-lamicall-t-flexi-tablet-support-where-form-meets-function/"><u>Comprehensive Assessment of the Lamicall T-Flexi Tablet Support - Where Form Meets Function</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-the-most-effective-photo-and-document-converters-of-2eighty-four/"><u>Discover the Most Effective Photo & Document Converters of 2Eighty-Four</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-undetected-windows-malware-risks/"><u>Discovering Undetected Windows Malware Risks</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-itools-virtual-location-not-work-on-apple-iphone-6-plusipad-drfone-by-drfone-virtual-ios/"><u>Does iTools virtual location not work On Apple iPhone 6 Plus/iPad? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-no-qt-platform-support-from-app-launch-errors/"><u>Eliminating 'No Qt Platform Support' From App Launch Errors</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-office-glitch-error-30015-26/"><u>Fixing Microsoft Office Glitch: Error 30015-26</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-a54-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy A54 5G Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-do-not-have-access-error-during-uninstall-on-windows-11/"><u>How to Overcome Do Not Have Access Error During Uninstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-wirelessly-connect-a-ps3-dualshock-controller-to-windows/"><u>How to Wirelessly Connect a PS3 DualShock Controller to Windows</u></a></li>
<li><a href="https://techidaily.com/is-your-oppo-reno-8t-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Oppo Reno 8T 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/lost-voice-troubleshoot-microphone-errors-in-google-meet-windows/"><u>Lost Voice? Troubleshoot Microphone Errors in Google Meet (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-techniques-for-clearing-ms-defender-log-on-pc/"><u>Master the Techniques for Clearing MS Defender Log on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-no-permission-error-on-windows-explorer/"><u>Mastering the 'No Permission' Error on Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-connectivity-with-5ghz-networks/"><u>Mastering Windows 11: Connectivity with 5GHz Networks</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-disk-space-with-windows-11s-ntfs-options/"><u>Maximizing Disk Space with Windows 11'S NTFS Options</u></a></li>
<li><a href="https://win11.techidaily.com/mend-resolving-keyboard-issues-on-windows-11/"><u>Mend: Resolving Keyboard Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-minecrafts-lan-network-issues/"><u>Navigating and Resolving Minecraft's LAN Network Issues</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-troubleshooting-in-windows-1011s-screen-issues/"><u>Navigating Troubleshooting in Windows 10/11'S Screen Issues</u></a></li>
<li><a href="https://win11.techidaily.com/non-responsive-f-keys-heres-how-to-fix-in-windows-10/"><u>Non-Responsive F-Keys? Here's How to Fix in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-multiscreen-woes-in-windows/"><u>Overcoming Multiscreen Woes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-admin-policies-that-hinder-setup/"><u>Overcoming Windows Admin Policies That Hinder Setup</u></a></li>
<li><a href="https://win11.techidaily.com/quick-aid-to-recover-googles-nonresponsive-windows-share-app/"><u>Quick Aid to Recover Google's Nonresponsive Windows Share App</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-adding-dolby-atmos-in-win-11-pro/"><u>Quick Steps for Adding Dolby Atmos in Win 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-for-disconnected-spotify-streaming/"><u>Quick-Fix Guide for Disconnected Spotify Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-nvidia-cp-access-issues-on-ws1110-systems/"><u>Resolving Nvidia CP Access Issues on WS11/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice!</u></a></li>
<li><a href="https://win11.techidaily.com/slash-cpu-usage-spikes-utilizing-windows-rm-wisdom/"><u>Slash CPU Usage Spikes: Utilizing Window's RM Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-autonomous-opens-in-microsoft-marketplace/"><u>Stopping Autonomous Opens in Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-the-size-limit-hurdle-in-discord-win11/"><u>Strategies to Overcome the Size Limit Hurdle in Discord (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-facebook-messenger-on-your-pc-now/"><u>Streamline Facebook Messenger On Your PC Now</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-data-with-tips-max-156/"><u>Streamline Your Windows Data with Tips (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/succeed-without-upgrading-to-windows-11-heres-how/"><u>Succeed without Upgrading to Windows 11, Here's How</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-os-anomalies-a-comprehensive-guide-to-finding-and-fixing-windows-errors-through-command-prompt/"><u>Tackling OS Anomalies: A Comprehensive Guide to Finding & Fixing Windows Errors Through Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-0x800736cc-windows-update-hurdle/"><u>Tackling the 0X800736CC Windows Update Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-app-screens-on-windows-11-properly/"><u>Tailoring App Screens on Windows 11 Properly</u></a></li>
<li><a href="https://win11.techidaily.com/the-undisclosed-menu-maestros-guide-to-win11-concealment/"><u>The Undisclosed Menu Maestro's Guide to Win11 Concealment</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-ranked-e-learning-presentation-palette-for-2024/"><u>Top-Ranked E-Learning Presentation Palette for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-mechanics-of-windows-11s-auto-hdr/"><u>Understanding the Mechanics of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-potential-of-windows-11s-package-control-using-wingetui/"><u>Unleash the Potential of Windows 11'S Package Control Using WingetUI</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-filefolder-secrets-6-property-steps-in-windows/"><u>Unlocking File/Folder Secrets: 6 Property Steps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11-login-secrets-fixing-blank-pages/"><u>Unveiling Windows 11 Login Secrets: Fixing Blank Pages</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-context-menus-move-and-copy-integration-guide/"><u>Upgrading Windows 11 Context Menus: Move and Copy Integration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/uphold-your-online-experience-windows-connection-audit/"><u>Uphold Your Online Experience: Windows Connection Audit</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-windows-blue-screen-data-for-precise-repairs/"><u>Utilizing Windows Blue Screen Data for Precise Repairs</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-typing-lag-seven-effective-fixes-for-win-os/"><u>Win over Typing Lag: Seven Effective Fixes for WIN OS</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->