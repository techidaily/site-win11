---
title: Guiding Through the Reinstallation of 'PrintManagement' MSCONFIG
date: 2024-10-13T17:29:00.201Z
updated: 2024-10-15T19:12:01.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guiding Through the Reinstallation of 'PrintManagement' MSCONFIG
excerpt: This Article Describes Guiding Through the Reinstallation of 'PrintManagement' MSCONFIG
keywords: PrintMgmt Config Guide,Reinstall Management Tool,MSConfig Troubleshoot,Windows Config Utility,System Software Recovery,Application Setup Assist,Config Settings Repair
thumbnail: https://thmb.techidaily.com/030f43c520c13566e766031892a27e4f35e056dc768bf0f9b9c3aff2261e980f.jpg
---

## Guiding Through the Reinstallation of 'PrintManagement' MSCONFIG

 Print management on Windows is a central way to manage your printers and printing options. You can use print management to control which users have access to printers, as well as set printing preferences such as paper size and quality. However, sometimes you may find the print management console missing from your computer. In most cases, the problem occurs after updating Windows to the latest version.

Here are some potential solutions to help you resolve the issue.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart Your Computer

 If you're getting an error when trying to open Printmanagement.msc, try restarting your computer. This might fix the problem if it's simply a glitch.

## 2\. Add the Print Management Feature Manually

 In case restarting doesn't work, open the Start menu and search for "Printmanagement.msc". If it doesn't show up in the search results, it seems that the Print Management feature isn't installed on your computer. In that case, you will have to manually add it. To do that, follow these steps:

1. Right-click on Start and select**Settings** from the Power User menu.
2. Select**Apps** from the left side of the Settings window.
3. In the right pane, click on**Optional features** .  
![Installing Print Management Via Optional Feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Installing-Print-Management-Via-Optional-Feature.jpg)
4. Next to "Add an optional feature", click**View features** .  
![Add an optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Add-an-optional-feature.jpg)
5. Search for "Print Management" in the next dialog box.
6. Once you find it, click on the**Print Management** checkbox.
7. Click**Next > Install** to add the feature.  
![Install Print Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Print-Management.jpg)

 The process will take a while, so after it has been added, you can check that the problem still exists. If yes, try the next solution on the list.

## 3\. Clear the Printer Spooler Files

 Windows uses a print spooler to manage all the print jobs that are waiting to be sent to your printer. Over time, the spooler can fill up with old or corrupt files, which can cause errors. So, if you're getting an error when trying to open Printmanagement.msc, it might be because your print spooler is full.

 To fix this, you'll need to clean out the print spooler. Here's how to clean it out and get things working again.

1. Click on the**Start** menu and search for "Services."
2. Select the result at the top of the list.
3. In the Services window, scroll down and search for "Print Spooler."
4. Once you find the application, double-click on it to open the**Properties** window.
5. On the "General" tab, check if the "Service status" is**Running** . If yes, click the**Stop** button to stop it.  
![Stop Print Spooler application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Stop-Print-Spooler-application.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. When you are done making changes, click**OK** to save them.
2. Now press**Win + I** on your keyboard to[open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**%WINDIR%\\system32\\spool\\printers** in the dialog box and press Enter.  
![Open Print Spooler files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-Print-Spooler-files.jpg)
4. If this is your first time opening this folder, you may be prompted that you don't have permission to access it. Click**Continue** to grant permanent access to this folder.
5. On the following screen, select and delete all contents of the folder.
6. Now go back to Services and open the Print Spooler Properties window.
7. Click the**Start** button to run the Service status. Also, make sure the "Startup type" dropdown menu is set to**Automatic** .  
![Start Print Spooler application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Start-Print-Spooler-application.jpg)
8. Finally, click**Apply** and then**OK** to save the changes.

 If you have done all the steps above, it should fix the problem. If not, try the next solution.

## 4\. Run SFC and DISM Scan

 If Print Management goes missing on Windows due to corruption of system files, the next course of action is to run DISM (Deployment Image Servicing and Management) and SFC (System File Checker). It scans all protected system files and replaces corrupted files with cached copies that are stored in compressed formats.

The steps below will guide you through running DISM and SFC scans:

1. Click the Start menu and search for "Command Prompt."
2. Right-click on the search result and select**Run as administrator** .
3. If UAC appears on the screen, click**Yes** to open the Command Prompt as an administrator.  
![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)
4. Type the following command in the Command Prompt window and hit Enter:  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`sfc /scannow`

It may take some time for the scan to complete, so please be patient.

 After the SFC scan is complete, run Deployment Image Servicing and Management to repair corrupted system images and restore system files. The steps are as follows:

* Run Command Prompt as an administrator. If you need help with this, see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
* Type the following command into the command prompt and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth  
Dism.exe /online /cleanup-image /restorehealth`

 The process may take some time to complete. After you have executed the DISM command, restart your computer to see if the problem has been resolved.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Update the Printer Driver

 If you still can't get it to work, it's likely that the printer driver you're using is outdated. In that case, updating your printer driver will solve the problem for you.

To update your printer driver, follow these steps:

1. Right-click Start and select**Device Manager** . Alternatively, you can also use the Run command to open it. For this, press**Win + R** , type "devmgmt.msc," and press**Enter** .
2. In Device Manager, find your printer under the "Print queues" category.
3. Now right-click on your printer driver and choose**Update driver** from the context menu.  
![Update Printer driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Printer-driver.jpg)
4. If you're prompted to choose how you want to search for drivers, select "Search automatically for drivers." Windows will then search for and install the latest drivers for your printer.

 Once the drivers have been updated, try opening Print Management again. The "Printmanagement.msc not found" error should now be fixed. If updating your printer driver doesn't fix the problem, you can also try uninstalling and reinstalling your printer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Check For Windows Update

 An outdated Windows operating system can often result in printmanagement.msc error messages. So, if you continue to have this problem, Windows Update may help.

To run Windows Update, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings.
2. Scroll down and click**Windows Update** in the left pane.
3. Click**Check for updates** on the right to see if there are any updates.
4. If new updates are available, they will begin downloading automatically.
5. Once the update has been completed, restart your computer and check if it resolves your issue.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Print Management Should Now Be Available

 Having printer-related issues on your computer is common, but fortunately, the information above will help you resolve them. If none of these solutions work, you can try restoring Windows to an earlier point. This will revert any recent changes that might have caused the printmanagement.msc file to go missing.

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
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-avoiding-pitfalls-tiktok-video-copyright-verification-guide/"><u>[New] In 2024, Avoiding Pitfalls TikTok Video Copyright Verification Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-facebook-lite-video-downloading-made-easy-top-6-tools-of-2023/"><u>[Updated] In 2024, Facebook Lite Video Downloading Made Easy Top 6 Tools of 2023</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-infuse-your-visuals-with-melody-adding-music-in-youtube-editing-for-2024/"><u>[Updated] Infuse Your Visuals With Melody Adding Music in YouTube Editing for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-oneplus-nord-ce-3-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from OnePlus Nord CE 3 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-hibernation-freezes-windows-solutions/"><u>Overcoming Hibernation Freezes: Windows Solutions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/photo-to-pixellated-panels-pro-windows-and-mac-edition-for-2024/"><u>Photo to Pixellated Panels Pro Windows & Mac Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functional-windows-rulesets-in-outlook/"><u>Reinstating Functional Windows Rulesets in Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-file-explorer-quick-fixes-for-windows-1011/"><u>Reviving File Explorer: Quick Fixes for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/shift-file-chronology-efficient-windows-tools-at-hand/"><u>Shift File Chronology: Efficient Windows Tools at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-access-making-shortcuts-on-uwp-windows-apps/"><u>Simplifying Access: Making Shortcuts on UWP Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-bring-your-offline-printer-back-online/"><u>Steps to Bring Your Offline Printer Back Online</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-epic-games-downloads-on-windows-pcs/"><u>Streamlining Epic Games Downloads on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-blue-screen-0x8007007e/"><u>Understanding and Remedying Windows Blue Screen 0X8007007E</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-freeze-time-a-step-by-step-guide-to-pausing-videos/"><u>Updated 2024 Approved Freeze Time A Step-by-Step Guide to Pausing Videos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-unleash-your-creativity-top-video-collage-apps-for-iphone-and-ipad/"><u>Updated 2024 Approved Unleash Your Creativity Top Video Collage Apps for iPhone and iPad</u></a></li>
<li><a href="https://win-amazing.techidaily.com/when-multiple-centrifugal-pumps-operate-in-parallel-they-share-the-same-head-but-distribute-the-total-flow-rate-among-them/"><u>When Multiple Centrifugal Pumps Operate in Parallel, They Share the Same Head but Distribute the Total Flow Rate Among Them.</u></a></li>
<li><a href="https://blog-min.techidaily.com/youtubechrome/"><u>YouTubeや動画サイトでChromeでの再生がうまくいかないときの解決策。</u></a></li>
</ul></div>

