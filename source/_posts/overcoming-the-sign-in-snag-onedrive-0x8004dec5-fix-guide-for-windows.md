---
title: "Overcoming the Sign-In Snag: ONEDRIVE 0X8004DEC5 Fix Guide for Windows"
date: 2024-10-22T01:51:42.447Z
updated: 2024-10-27T05:28:24.986Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming the Sign-In Snag: ONEDRIVE 0X8004DEC5 Fix Guide for Windows"
excerpt: "This Article Describes Overcoming the Sign-In Snag: ONEDRIVE 0X8004DEC5 Fix Guide for Windows"
keywords: ONEDRIVE Login Issue,0X8004DEC5 Error,Overcoming Sign-In Snag,Windows ONEDrive Fix,Troubleshoot ONEDrive,Resolve ONEDrive Errors,ONEDRIVE Login Guide
thumbnail: https://thmb.techidaily.com/20c69587162d153f03eefa64dab5fb5356740a9d42978b0299a0a4d322290d05.jpeg
---

## Overcoming the Sign-In Snag: ONEDRIVE 0X8004DEC5 Fix Guide for Windows

 Microsoft's cloud storage service OneDrive simplifies file management on Windows. However, you might experience issues when signing in to OneDrive, like the 0x8004dec5 error. This article will guide you on how to resolve OneDrive sign-in error 0x8004dec5 specifically on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Your Internet Connection

 If you’re having trouble signing in to OneDrive, first [check your internet connection](http://www.makeuseof.com/windows-check-wifi-network-strength/). Slow or spotty internet causes sign-in problems. So, check your connection speed and make sure it’s strong enough for OneDrive. If necessary, reset your router or modem to restore the connection.

 If your internet connection is working, restart your computer and sign in to OneDrive again. This simple step fixes minor errors in the operating system that may cause the sign-in issue.

## 2\. Run the Network Troubleshooter

 If your internet connection is stable, but you’re still having OneDrive sign-in problems, you can run the Internet Connections Troubleshooter. This diagnosis tool scans for network problems and repairs any issues it finds.

 To run the Internet Connection Troubleshooter, follow these steps:

1. Right-click on Start and select **Run** from the menu list.  
![Open Internet Connections](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/open-internet-connections.jpg)
2. In the dialog box, type the following command and click **OK**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`msdt.exe -id NetworkDiagnosticsWeb`
3. Click **Advanced** and check **Apply repairs automatically**.  
![Run the Internet Connections troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-the-internet-connections-troubleshooter.jpg)
4. Now click **Next** and follow the on-screen instructions to finish the troubleshooting process.

 Once it’s done, sign into OneDrive and see if the error is fixed. If not, try the next solution.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Tweak the Registry Editor

 If the problem persists, remove cached Office account identities from the registry. This requires changing a few settings in the Windows registry which is a database of your operating system, so proceed with caution.

 If you’re not sure what you’re doing, have an experienced technician make the changes for you. To avoid damaging your system, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making these changes.

1. Press **Win + R** on your keyboard to open the Run dialog.
2. Type **regedit** in the search box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to proceed.
4. In the Registry Editor window, navigate to the path as follows:  
`HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity`
5. Right-click on the **Identity** folder and select **Delete** from the menu.  
![Delete Identity Folder From Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-identity-folder-from-registry.jpg)
6. Click **Yes** when asked to confirm your action.
7. Close Registry Editor and restart your computer.

 Now try signing in to OneDrive again. The sign-in error should now be resolved.

## 4\. Remove Cached Credentials Folders

 If you're not comfortable tweaking the registry editor, remove cached Office account identities using Windows Explorer. Here's how to do it.

1. Press **Win + E** to open File Explorer.
2. In the File Explorer window, navigate to the following location:  
`C:\Users\Username\AppData\Local\Microsoft\IdentityCache`
3. Press **Ctrl + A** to select all files and delete them.  
![Clear Identity Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/clear-identity-folder.jpg)
4. Now navigate to this location, and replace **Username** with your own Windows username.:  
`C:\Users\Username\AppData\Local\Microsoft\OneAuth  
`
5. Select all the files here and hit the **Delete** button.

 Once you've removed all cached Office account identities, restart your computer and try signing in to OneDrive again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Unlink and Re-Link Your OneDrive Account

 If you have a valid OneDrive account, but still can’t sign in due to the 0x8004dec5 error code, unlink and relink your account. This will reset the connection and fix the problem.

 To unlink OneDrive, follow these steps.

1. Go to the right side of the taskbar and click on the **OneDrive** icon.
2. Click **Help & Settings** (the gear icon) and select **Settings** from the menu list.
3. In the Settings window, go to the **Account** tab.
4. Under your OneDrive account, click **Unlink this PC**.  
![Unlink OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive.jpg)
5. Click **Unlink account** to confirm your action.  
![Unlink OneDrive Account on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive-account-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148771/18498" target="_top" id="2148771">
  <img src="//a.impactradius-go.com/display-ad/18498-2148771" border="0" alt="https://techidaily.com" width="350" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148771/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After unlinking the account, you now need to relink it. To do that, open the OneDrive Settings window again and click **Add an Account**. Enter your OneDrive credentials and sign in to the account.

 When it’s done, close the Settings window. Now open OneDrive and sign in with your new account credentials. The sign-in error should now be resolved.

## 6\. Reset the OneDrive App

 In some cases, resetting the OneDrive application solves the sign-in errors. This restores the app to its default settings and removes any corrupted system files.

 To reset the OneDrive app, follow these steps.

1. Press **Win + X** on your keyboard and select **Installed apps** from the list.
2. In the list of installed apps, scroll down to **OneDrive**.
3. Click the three dots and select the **Advanced options**.
4. Scroll down to the **Reset** section and click on the **Reset** button.  
![Reset OneDrive app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-onedrive-app.jpg)
5. Click **Reset** again to confirm your action.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After the reset, try signing in to OneDrive and seeing if error 0x8004dec5 is fixed.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Get the Latest Windows Updates

 Microsoft releases new patches that improve Windows performance. If your computer didn't receive the latest updates, it may cause OneDrive sign-in errors. To fix this problem, install the pending Windows updates and try signing in to OneDrive again.

 To download and install the latest Windows updates, use these steps.

1. Press **Win + I** on your keyboard to open the Settings window (see our guide on [how to open the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/)).
2. From the left sidebar, click on the **Windows Update** tab.
3. Now click **Check for updates** and wait while Windows checks for available updates.  
![Check for updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-updates.jpg)
4. If you find new updates, download and install them.

 After performing the above action, restart your computer. Now try signing in to OneDrive and seeing if the error is fixed.

## 8\. Uninstall and Reinstall OneDrive

 If the error persists even after trying the above solutions, it's likely that the OneDrive app is malfunctioning. In that case, reinstall the application. It fixes corrupted files and solves sign-in issues. Here's how to do it.

1. [Open Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/).
2. Set the View by option to **Category**, then click **Programs** \> **Uninstall a program**.
3. Find **OneDrive** in the list of installed programs and click **Uninstall**.  
![Uninstall OneDrive-2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-onedrive-2.jpg)
4. If you get a confirmation prompt, click **Yes**.

 Now follow the instructions to complete the process. After that, [visit Microsoft's official website](https://www.microsoft.com/en-us/microsoft-365/onedrive/download?) to download and install OneDrive.

## Fixing OneDrive's 0x8004dec5 Sign In Error

 Following the steps mentioned above should resolve the 0x8004dec5 OneDrive sign-in error. Corrupt files, outdated Windows versions, or compatibility issues usually cause it. A basic troubleshooting step would be to restart your computer and reset the OneDrive app. If that doesn't fix it, unlink and relink your account, or reinstall OneDrive.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-casino-confidential-communiques/"><u>[New] CASINO CONFIDENTIAL COMMUNIQUES</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-top-10-music-videos-on-facebook-how-to-make-a-facebook-song-video/"><u>[New] In 2024, Top 10 Music Videos on Facebook | How to Make A Facebook Song Video?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-staying-relevant-adapting-to-periscope-trends/"><u>[New] Staying Relevant Adapting to Periscope Trends</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-optimizing-online-content-delivery-to-key-social-media-channels/"><u>[Updated] In 2024, Optimizing Online Content Delivery to Key Social Media Channels</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-boosting-performance-why-it-matters-on-windows/"><u>DXVK: Boosting Performance - Why It Matters on Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/effortless-conversion-the-top-5-methods-for-changing-avi-files-into-mpeg-format/"><u>Effortless Conversion: The Top 5 Methods for Changing AVI Files Into MPEG Format</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-tablet-usability-with-windows-11s-taskbar/"><u>Enhancing Tablet Usability with Windows 11'S Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-gmail-and-outlook-on-pc-simple-steps/"><u>Harmonizing Gmail & Outlook on PC: Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/improve-your-visual-output-boosting-win-11s-vram/"><u>Improve Your Visual Output: Boosting Win 11'S VRAM</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-creating-a-spherical-experience-best-practices-for-panoramic-film-9-essentials/"><u>In 2024, Creating a Spherical Experience Best Practices for Panoramic Film (9 Essentials)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-settings-guide-xbox-app-and-windows-installation/"><u>Optimal Settings Guide: Xbox App & Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-typing-potential-seven-windows-fixes-for-lag-reduction/"><u>Unleashing Typing Potential: Seven Windows Fixes for Lag Reduction</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-edit-like-a-pro-the-5-best-iphone-video-editing-apps-for-2024/"><u>Updated Edit Like a Pro The 5 Best iPhone Video Editing Apps for 2024</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-tecno-spark-20-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Tecno Spark 20 on Windows?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    