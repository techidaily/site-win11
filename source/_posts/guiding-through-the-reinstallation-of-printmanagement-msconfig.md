---
title: Guiding Through the Reinstallation of 'PrintManagement' MSCONFIG
date: 2024-09-09T19:31:04.102Z
updated: 2024-09-17T02:55:44.811Z
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

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Run SFC and DISM Scan

 If Print Management goes missing on Windows due to corruption of system files, the next course of action is to run DISM (Deployment Image Servicing and Management) and SFC (System File Checker). It scans all protected system files and replaces corrupted files with cached copies that are stored in compressed formats.

The steps below will guide you through running DISM and SFC scans:

1. Click the Start menu and search for "Command Prompt."
2. Right-click on the search result and select**Run as administrator** .
3. If UAC appears on the screen, click**Yes** to open the Command Prompt as an administrator.  
![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)
4. Type the following command in the Command Prompt window and hit Enter:  
`sfc /scannow`

It may take some time for the scan to complete, so please be patient.

 After the SFC scan is complete, run Deployment Image Servicing and Management to repair corrupted system images and restore system files. The steps are as follows:

* Run Command Prompt as an administrator. If you need help with this, see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
* Type the following command into the command prompt and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth  
Dism.exe /online /cleanup-image /restorehealth`

 The process may take some time to complete. After you have executed the DISM command, restart your computer to see if the problem has been resolved.

## 5\. Update the Printer Driver

 If you still can't get it to work, it's likely that the printer driver you're using is outdated. In that case, updating your printer driver will solve the problem for you.

To update your printer driver, follow these steps:

1. Right-click Start and select**Device Manager** . Alternatively, you can also use the Run command to open it. For this, press**Win + R** , type "devmgmt.msc," and press**Enter** .
2. In Device Manager, find your printer under the "Print queues" category.
3. Now right-click on your printer driver and choose**Update driver** from the context menu.  
![Update Printer driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Printer-driver.jpg)
4. If you're prompted to choose how you want to search for drivers, select "Search automatically for drivers." Windows will then search for and install the latest drivers for your printer.

 Once the drivers have been updated, try opening Print Management again. The "Printmanagement.msc not found" error should now be fixed. If updating your printer driver doesn't fix the problem, you can also try uninstalling and reinstalling your printer.

## 6\. Check For Windows Update

 An outdated Windows operating system can often result in printmanagement.msc error messages. So, if you continue to have this problem, Windows Update may help.

To run Windows Update, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings.
2. Scroll down and click**Windows Update** in the left pane.
3. Click**Check for updates** on the right to see if there are any updates.
4. If new updates are available, they will begin downloading automatically.
5. Once the update has been completed, restart your computer and check if it resolves your issue.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115934/19272" target="_top" id="2115934">
  <img src="//a.impactradius-go.com/display-ad/19272-2115934" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115934/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/n-2024-boost-visibility-with-customized-channel-names/"><u>[New] In 2024, Boost Visibility with Customized Channel Names</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-mastering-the-art-of-making-and-tweaking-multi-snap-videos/"><u>[Updated] 2024 Approved Mastering the Art of Making & Tweaking Multi-Snap Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-elite-screen-recording-apps-of-2023-expert-picks/"><u>[Updated] Elite Screen Recording Apps of 2023 - Expert Picks</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-one-way-startup-on-secure-windows-for-office-suite/"><u>Combatting the One-Way Startup on Secure Windows for Office Suite</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-activation-problem-0x803f700f/"><u>Eliminating Windows Activation Problem: 0X803F700F</u></a></li>
<li><a href="https://video-capture.techidaily.com/expert-insights-optimal-techniques-for-pc-display-recordings-for-2024/"><u>Expert Insights Optimal Techniques for PC Display Recordings for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-honor-x9b-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Honor X9b? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-vivo-s17-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Vivo S17 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-10-error-e1-exception/"><u>Resolving Windows 10 Error E1 Exception</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-incompatible-media-input-vlc/"><u>Resolving Windows: Incompatible Media Input VLC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-razer-and-windows-interaction-for-seamless-detection/"><u>Streamlining Razer and Windows Interaction for Seamless Detection</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-clear-views-6-fixes-for-windows-resolution-confusion/"><u>Unlock Clear Views: 6 Fixes for Windows Resolution Confusion</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pcs-sound-potential-with-windows-11/"><u>Unlock Your PC's Sound Potential with Windows 11</u></a></li>
</ul></div>

