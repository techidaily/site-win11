---
title: Combatting Insufficient Privilege Error During Windows Setup
date: 2024-09-05T08:30:38.726Z
updated: 2024-09-06T08:30:38.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting Insufficient Privilege Error During Windows Setup
excerpt: This Article Describes Combatting Insufficient Privilege Error During Windows Setup
keywords: Fixing Privilege Errors,WinSetup Access Issue,Resolve Privileged Error,Overcome Privilege Failure,Dealing with UAC Error,Unblock Setup Windows,Correcting Insufficient Privileges
thumbnail: https://thmb.techidaily.com/454a5d400e77a7a30fc6fb5cf37376c887407a08a4d33d69cb3dc289d466caa6.jpg
---

## Combatting Insufficient Privilege Error During Windows Setup

 Users report Windows software installation errors of various kinds on support forums. Some of those reports have been about an error message that says, “The installer has insufficient privileges to access this directory.” That error message pops up on some users’ Windows 11/10 PCs when they try to install desktop programs with setup files.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Run the Affected Software’s Setup File With Admin Rights

 Running the setup file for an affected program with administrator rights is perhaps the simplest of potential fixes for the “installer has insufficient privileges” error.

 A few users say that’s all they needed to do to fix the “installer has insufficient privileges” error. So, try right-clicking the software’s installer file and selecting **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-as-administrator-option.jpg)

## 2\. Unblock the Setup File

 In addition, check if the installer file is blocked before running it. To do that, right-click the program’s setup file and select **Properties**.

 If you can see an **Unblock** option on the **General** tab, deselect the checkbox and select **Apply**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Take Ownership of the Software’s Installation Directory

 One of the more widely confirmed solutions for fixing the “installer has insufficient privileges” error is to take ownership of the installation directory for the affected software.

 The “installer has sufficient privileges” error message specifies the path of the directory selected to install the software. Take ownership of the second to last folder of that path. The last folder is the one created during the installation that won’t currently exist on your PC.

 Alternatively, you can also apply this potential solution by manually creating the folder specified within the error message that doesn’t currently exist. Keep the error message open and create the last folder in the path. Then take ownership of the last folder in the installation path specified and click **Retry** within the error message.

 You can take ownership of a folder manually or by adding a new context menu option that does the job. This guide about [taking ownership of folders in Windows 11](https://www.makeuseof.com/windows-10-11-own-folder/) includes full instructions for both methods. It’s more straightforward to apply this potential solution by adding a **Take Ownership** option to the context menu with Winaero Tweaker.

![The Take Ownership option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/take-ownership-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Try Installing it in a Different Folder

 You might be able to bypass the “installer has insufficient privileges” error by selecting to install the software in a different directory. Many users install software packages in the Program Files folder. So, try selecting to install a program at a completely different folder path from the one specified in the error message.

## 5\. Start or Restart Windows Installer

 Installation issues can arise because of Windows Installer service issues. Or that service might not even be running. So, check that service and either start or restart it depending on whether it’s running or not. You can start or restart Windows Installer like this:

1. [Open Services](https://www.makeuseof.com/windows-11-open-services-app/), an app you can access by pressing the **Windows** logo + **R** hotkey and inputting a **service.msc** command.
2. Right-click Windows Installer and select **Start** if that service isn’t on and running.  
![windows installer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-installer-option.jpg)
3. If Windows Installer is running, select its **Restart** context menu option.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can double-click the **Windows Installer** service to view its properties window and restart it from there. Click **Start** if the service is already stopped, or, select **Stop > Start** to restart.

## 6\. Disable UAC Before Installing

 User Account Control is one of the security features that can generate installation issues when set to its higher levels. Turn off UAC before attempting to install affected software to see if that resolves the “installer has insufficient privileges” error. Check out this guide about [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) for details about how to turn off UAC.

![The Never notify option in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-notify-option.jpg)

## 7\. Disable All User Account Control Policy Settings

 If you’re a Windows Pro or Enterprise user, you can disable all UAC security settings that might be causing this error by restricting software installation.

 The Group Policy Editor tool in Windows Pro and Enterprise editions enables users to disable more User Account Control settings. You can turn off all UAC policy settings with Group Policy Editor like this:

1. [Open the Group Policy Editor tool](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in its sidebar.
2. Then double-click **Windows Settings** \> **Security Settings** \> **Local Policies** \> **Security Options** to access UAC policy settings.
3. Double-click **User Account Control: Admin Approval Mode** to bring up that policy setting window.  
![The UAP security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-options.jpg)
4. Select **Disabled** to turn off that policy setting.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Apply** \> **OK** to save the policy setting you’ve selected.  
![The Enabled radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-enabled-radio-button.jpg)

 Once done, repeat steps three to five above for all the User Account Control policy settings. Exit Group Policy Editor and restart your PC after disabling all UAC policy settings.

## 8\. Turn Off Third-Party Security Apps

 If you’ve installed a third-party security app, such as antivirus or firewall software, that could be a possible cause for the “installer has insufficient privileges” error on your PC.

 Third-party antivirus tools have settings that can restrict or block the installation of suspicious programs when enabled. That’s more likely to happen when you’re trying to install unsigned software, which antivirus apps sometimes flag.

 You can prevent potential security app blocks when installing programs by temporarily disabling their antivirus shields.

 To find an option for disabling your antivirus app’s shield, right-click its system tray icon; select a setting to turn off your antivirus for a while on the right-click context menu that opens. Then have a go at installing affected software packages again with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115936/19272" target="_top" id="2115936">
  <img src="//a.impactradius-go.com/display-ad/19272-2115936" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115936/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Try Installing Software After Clean Booting

 Clean booting means disabling all third-party apps and services that start with Windows. This troubleshooting method can prevent software conflicts by eliminating unneeded apps and services running in the background. In this case, a clean boot might disable an app or service that’s hindering the software installation process.

 We have a detailed guide on [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) explaining how you can disable the startup items with System Configuration and Task Manager. Select to restart your PC after you’ve set a clean boot configuration. Install the software you need after restarting to see if the clean booting has made any difference.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-services-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 10\. Uninstall Older Software Versions

 The “installer has insufficient privileges” has been reported to occur by users trying to install new versions of software already on their PCs.

 If there’s an older version of the software you can’t install already on your PC, then try uninstalling the preceding version first. This guide on [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) includes various methods for removing programs.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Windows 11/10 Software Installed

 The possible fixes covered here will probably resolve the “installer has insufficient privileges” Windows error in most cases but aren’t necessarily guaranteed.

 Resolution three, taking ownership of the installation directory, is the most widely confirmed solution. So, this error is usually a privilege (permission) issue for installing software, which the potential resolutions above will likely address.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-maximizing-view-count-for-facebook-videos/"><u>[New] 2024 Approved  Maximizing View Count for Facebook Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-download-youtube-tunes-without-risk-for-free-for-2024/"><u>[New] How to Download YouTube Tunes Without Risk for Free for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-macos-big-sur-minimum-requirements/"><u>[New] Understanding MacOS Big Sur  Minimum Requirements</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-squeezing-light-from-iphone-nocturnes/"><u>[Updated] In 2024, Squeezing Light From iPhone Nocturnes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-depth-review-of-splitcam-leading-camera-tech-for-2024/"><u>[Updated] In-Depth Review of SplitCam  Leading Camera Tech for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-tips-for-enabling-grid-on-google-meet-for-2024/"><u>[Updated] Tips for Enabling Grid on Google Meet for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-crafting-excellence-in-instagram-grids-with-these-elite-tools/"><u>2024 Approved  Crafting Excellence in Instagram Grids with These Elite Tools</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-honor-90-gt-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/backup-your-cortana-data-for-future-reference-windows/"><u>Backup Your Cortana Data for Future Reference (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-non-response-issues-in-windows-service-explorer-with-7-methods/"><u>Confronting Non-Response Issues in Windows Service Explorer with 7 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-no-more-files-notifications-on-win-11/"><u>Disabling 'No More Files' Notifications on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/double-the-fun-with-a-swifter-mouse-click-process/"><u>Double the Fun with a Swifter Mouse Click Process</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-pc-experience-win11-narrator-keybindings/"><u>Elevate Your PC Experience: Win11 Narrator Keybindings</u></a></li>
<li><a href="https://win11.techidaily.com/examining-wsls-influence-on-linux-adoption/"><u>Examining WSL's Influence on Linux Adoption</u></a></li>
<li><a href="https://win11.techidaily.com/fix-graphics-glitches-on-windows-11-now/"><u>Fix Graphics Glitches on Windows 11 Now</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-application-couldnt-start-0xc000003e-hexadecimal-error/"><u>Fixing The Application Couldn't Start 0xC000003E Hexadecimal Error</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/getting-the-most-out-of-live-sports-on-youtube-tv/"><u>Getting the Most Out of Live Sports on YouTube TV</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-the-windows-11-login-method-from-pin-to-password/"><u>How to Change the Windows 11 Login Method From PIN to Password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-not-enough-usb-controller-resources-error-on-a-windows-computer/"><u>How to Fix “Not Enough USB Controller Resources” Error on a Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-msstore-crash-with-error-code-0x0-on-windows-1011/"><u>How to Overcome MsStore Crash with Error Code 0X0 on Windows 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-realme-gt-neo-5-se-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Realme GT Neo 5 SE?</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-drawers-for-win-11-a-comprerancial-guide-to-best-apps/"><u>Ideal Drawers for Win 11: A Comprerancial Guide to Best Apps</u></a></li>
<li><a href="https://win11.techidaily.com/illuminated-ideas-a-guide-to-organizing-notes-via-obsidian/"><u>Illuminated Ideas: A Guide to Organizing Notes via Obsidian</u></a></li>
<li><a href="https://win11.techidaily.com/illuminating-holiday-joy-window-decor-inspirations/"><u>Illuminating Holiday Joy - Window Decor Inspirations</u></a></li>
<li><a href="https://win11.techidaily.com/improve-excel-latency-actions-for-windows-enthusiasts/"><u>Improve Excel Latency: Actions for Windows Enthusiasts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-fb-video-capture-toolkit/"><u>In 2024, FB Video Capture Toolkit</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-nokia-c300-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Nokia C300 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-xiaomi-redmi-note-12t-pro-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Xiaomi Redmi Note 12T Pro Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-fundamentals-of-creating-breathtaking-canon-time-lapses/"><u>In 2024, The Fundamentals of Creating Breathtaking Canon Time-Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-macos-with-external-windows-programs/"><u>Mastering macOS with External Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-graphics-driver-updates-for-amd-windows-11/"><u>Navigating the Maze of Graphics Driver Updates for AMD, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-your-drive-space-a-disc-usage-command-breakdown/"><u>Navigating Through Your Drive Space: A Disc Usage Command Breakdown</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-proxies-for-windows-11-users/"><u>Optimizing Proxies for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-all-ppt-save-errors-6-must-try-methods-in-win11/"><u>Quick Cure-All PPT Save Errors: 6 Must-Try Methods in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-common-photo-errors-with-windows-1011-tips/"><u>Resolving Common Photo Errors with Windows 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/screen-splendor-series-designing-distinct-displays-on-win-1011-per-monitor/"><u>Screen Splendor Series: Designing Distinct Displays on WIN 10/11 Per Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-microsoft-teams-experience-navigating-through-windows-error-80080300/"><u>Seamless Microsoft Teams Experience: Navigating Through Windows Error 80080300</u></a></li>
<li><a href="https://win11.techidaily.com/shielding-windows-default-screen-display-from-user-changes/"><u>Shielding Windows Default Screen Display From User Changes</u></a></li>
<li><a href="https://win11.techidaily.com/skip-steps-to-sidestep-login-questions-on-windows-11-local/"><u>Skip Steps to Sidestep Login Questions on Windows 11 Local</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/snapshot-safeguarding-an-easy-tutorial-for-your-phone/"><u>Snapshot Safeguarding  An Easy Tutorial for Your Phone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-approach-to-fix-windows-charmap-woes/"><u>Streamlining Your Approach to Fix Windows CharMap Woes</u></a></li>
<li><a href="https://driver-install.techidaily.com/surefire-logitech-webcam-software/"><u>Surefire Logitech Webcam Software</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-failed-to-install-discord-error-win/"><u>Tackling the Failed to Install Discord Error (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/the-project-pro-essential-ms-project-keys-explained/"><u>The Project Pro: Essential MS Project Keys Explained</u></a></li>
<li><a href="https://win11.techidaily.com/the-roadmap-to-unblemished-wallpaper-clarity-in-w11/"><u>The Roadmap to Unblemished Wallpaper Clarity in W11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-for-windows-multi-monitor-brightness-tuning/"><u>The Ultimate List for Windows Multi-Monitor Brightness Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-achieving-a-trio-of-widget-grids-on-windows-11/"><u>Tutorial: Achieving a Trio of Widget Grids on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-game-files-three-windows-techniques/"><u>Uncovering Game Files: Three Windows Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-web-control-panel/"><u>Unlocking Windows 11'S Web Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-windows-update-mysteries/"><u>Unpacking Window's Update Mysteries</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-best-mobile-apps-to-extract-audio-from-video-files-for-2024/"><u>Updated Best Mobile Apps to Extract Audio From Video Files for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-arm-instalation-simplified-through-iso-file-processing/"><u>Windows 11 ARM Instalation Simplified Through ISO File Processing</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>