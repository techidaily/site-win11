---
title: Tackling Nonresponsive Diagnostics in Win10/Win11
date: 2024-08-16T00:44:39.380Z
updated: 2024-08-17T00:44:39.380Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Nonresponsive Diagnostics in Win10/Win11
excerpt: This Article Describes Tackling Nonresponsive Diagnostics in Win10/Win11
keywords: WINDOWS 10/11 Diagnostic Failure,Windows 10/11 Nonresponsive Tests,Win10/Win11 System Debugging,Remote Diagnostics in Win10/11,Windows Error Troubleshooting,Win10/Win11 Fault Analysis,Responsive Issues Win10/11
thumbnail: https://thmb.techidaily.com/d7dc5f497c3ff92b83099053ccb7b434fc4fb16a570e502a336cc42130adb602.jpg
---

## Tackling Nonresponsive Diagnostics in Win10/Win11

 Users often utilize the pre-installed Windows 11/10 troubleshooters available in Settings to fix update, sound, internet, microphone, video playback, Bluetooth, and UWP app issues. However, sometimes those troubleshooters display messages in their windows that say, “An error occurred while troubleshooting.” Or the message might say, “An error occurred while loading the troubleshooter.”

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

## 1\. Scan and Repair System Files

 Some users have said the system file and image repair tools helped them fix Windows 11/10 troubleshooting tools not working. System File Checker is the command-line tool for repairing system file corruptions. Deployment Image Servicing and Management is a utility you can run to address issues with the Windows image. Try running both those tools in the Command Prompt, as covered within this [guide for repairing corrupted Windows files](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command4.jpg)

## 2\. Enable or Restart Required Services

 Windows troubleshooters can stop working because required services are disabled or not running. Enabling and starting services like Cryptographic Services, Windows Update, BITS, and Windows Installer is a potential resolution for fixing troubleshooters users confirm to work. Try starting those required services like this:

1. Bring up the service management app with a method in this [guide to opening Services](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click **Cryptographic Services** to bring up a settings window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services.jpg)
3. Click on the **Startup type** drop-down menu and choose the **Automatic** setting if a different option is selected.
4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Rename the Catroot2 and SoftwareDistribution Folders

 If you’re having issues with the Windows Update troubleshooter, try applying this potential solution. Users confirm renaming the catroot2 and SoftwareDistribution folders can fix the Windows Update troubleshooter not working. Those are folders that store data for Windows updates. Rename the catroot2 and SoftwareDistribution folders as follows:

1. Launch the Windows Command Prompt app with administrative rights.
2. Input these four separate commands, pressing **Enter** after each, to stop update services:  
`net stop cryptsvc  

net stop wuauserv  

net stop bits  

net stop msiserver`
3. Next, input this command and hit **Return** to rename the SoftwareDistribution folder:  
`ren c:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren command for the SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-softwaredistribution-folder.jpg)
4. Enter this command for renaming the catroot2 folder and press **Return**:  
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/et-your-digital-dough-worthy-with-these-50-no-cost-youtube-promo-tools-for-2024/"><u>[New] Get Your Digital Dough Worthy With These 50 No-Cost YouTube Promo Tools for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/productname-the-ultimate-autonomous-analytics-solution-for-superior-seo-results/"><u>[Product_Name]: The Ultimate Autonomous Analytics Solution for Superior SEO Results</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-frame-by-frame-the-smartphone-storytellers-path-to-youtubes-thumbnails/"><u>[Updated] 2024 Approved  Frame by Frame  The Smartphone Storyteller's Path to YouTubes Thumbnails</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-gopros-newest-clash-max-360-versus-hero-11-showdown/"><u>[Updated] 2024 Approved  GoPro's Newest Clash  Max 360 Versus Hero 11 Showdown</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-essential-music-video-watching-apps-for-android-for-2024/"><u>[Updated] Essential Music Video Watching Apps for Android for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-masterclass-in-capturing-conversations-for-later-review/"><u>2024 Approved  Masterclass in Capturing Conversations for Later Review</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-restore-missing-desktop-icons-on-windows-11/"><u>8 Ways to Restore Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-experience-filter-key-settings/"><u>Customize Your Windows Experience: Filter Key Settings</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-overcoming-windows-1011s-isdonedll-errors/"><u>Deciphering and Overcoming Windows 10/11'S ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-risks-for-windows-bt-folder-expert-advice/"><u>Deletion Risks for Windows ~BT Folder: Expert Advice</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-role-of-windows-cab-files-in-system-setup/"><u>Dissecting the Role of Windows CAB Files in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/ditching-taskbar-chatting-in-windows-11-how-will-it-influence-your-experience/"><u>Ditching Taskbar Chatting in Windows 11: How Will It Influence Your Experience?</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-flawed-mp4-playback-in-smartphones/"><u>Fixing Flawed MP4 Playback in Smartphones</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-samsung-galaxy-f34-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Samsung Galaxy F34 5G Quickly? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-oppo-f23-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Oppo F23 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-channel-your-inner-narrative-impactful-life-stories-yt/"><u>In 2024, Channel Your Inner Narrative  Impactful Life Stories YT</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-crafting-compelling-video-narratives-using-captivate/"><u>In 2024, Crafting Compelling Video Narratives Using Captivate</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-extended-review-uncomplicated-hdr-approach/"><u>In 2024, Extended Review  Uncomplicated HDR Approach</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-haul-vlogging-101-a-step-by-step-guide/"><u>In 2024, Haul Vlogging 101  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-on-windows-11-desktop-ui/"><u>Increase Visible Pins on Windows 11 Desktop UI</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/microsoft-word-made-affordable-tips-for-finding-and-using-the-software-at-no-expense/"><u>Microsoft Word Made Affordable: Tips for Finding and Using the Software at No Expense</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-color-management-glitches/"><u>Navigating Through Windows' Color Management Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-optimal-windows-11-search-performance/"><u>Navigating to Optimal Window's 11 Search Performance</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-not-working-on-oppo-find-n3-flip-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Oppo Find N3 Flip? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-your-computers-msvcr110dll-void/"><u>Remedying Your Computer’s Msvcr110.dll Void</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-everlasting-file-elimination-on-your-desktop-bin-with-windows-11/"><u>Simplifying Everlasting File Elimination on Your Desktop Bin with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-failed-file-creation-by-camera-app/"><u>Solutions for Fixing Failed File Creation by Camera App</u></a></li>
<li><a href="https://os-tips.techidaily.com/solve-iphone-and-ipad-downloading-messages-issue/"><u>Solve iPhone & iPad Downloading Messages Issue</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-age-of-empires-iv-issues-stuck-during-microsoft-store-installation/"><u>Solving Age of Empires IV Issues - Stuck During Microsoft Store Installation</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-username-switch-on-windows-11/"><u>Streamlining the UserName Switch on Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/tech-companies-held-accountable-the-battle-against-misleading-social-media-ads/"><u>Tech Companies Held Accountable: The Battle Against Misleading Social Media Ads</u></a></li>
<li><a href="https://win11.techidaily.com/the-13-step-blueprint-to-reactivating-your-windows/"><u>The 13-Step Blueprint to Reactivating Your Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-handshake-direct-pc-links-in-windows-11-rdp/"><u>The Invisible Handshake: Direct PC Links in Windows 11 RDP</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-ccleaner-in-win11/"><u>Troubleshooting Non-Functional CCleaner in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-handbook-for-using-googles-ai-for-transcription-in-word-processors-for-2024/"><u>Ultimate Handbook for Using Google's AI for Transcription in Word Processors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-steam-network-access-on-pc-windows/"><u>Unlocking Steam Network Access on PC Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>