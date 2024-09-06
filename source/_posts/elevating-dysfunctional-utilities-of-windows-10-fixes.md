---
title: Elevating Dysfunctional Utilities of Windows 10 Fixes
date: 2024-09-05T08:26:30.079Z
updated: 2024-09-06T08:26:30.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevating Dysfunctional Utilities of Windows 10 Fixes
excerpt: This Article Describes Elevating Dysfunctional Utilities of Windows 10 Fixes
keywords: Windows 10 Fix Guide,Troubleshoot Windows Issues,Solve Tech Problems Win10,Quick Fix for Windows Errors,Improving System Functions,Windows Optimization Tips,Resolve PC Malfunctions
thumbnail: https://thmb.techidaily.com/a4a765e99a54a380752423d8d88b32966a3339aa9293b1bce2b9a95dc690dd25.jpg
---

## Elevating Dysfunctional Utilities of Windows 10 Fixes

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
<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
3. To reset Winsock, execute this command:  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

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
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123481/16836" target="_top" id="2123481">
  <img src="//a.impactradius-go.com/display-ad/16836-2123481" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123481/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:
<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

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
## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-mastering-instagram-video-downloads-pcmac-guide/"><u>[New] 2024 Approved  Mastering Instagram Video Downloads  PC/Mac Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-maximizing-snapchat-earning-potential-step-by-step/"><u>[New] In 2024, Maximizing Snapchat Earning Potential Step by Step</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-instagram-ringtone-making-manual/"><u>[Updated] The Ultimate Instagram Ringtone Making Manual</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleashing-photography-potential-with-lightroom-hdrs/"><u>[Updated] Unleashing Photography Potential with Lightroom HDRs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/boost-career-prospects-with-these-7-reasons-for-afrikaans-mastery/"><u>Boost Career Prospects with These 7 Reasons for Afrikaans Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-the-perplexing-windows-net-error-0x800704b3/"><u>Deciphering and Fixing the Perplexing Windows Net Error 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/decluttering-disk-space-on-windows-using-altwindirstat/"><u>Decluttering Disk Space on Windows Using altWinDirStat</u></a></li>
<li><a href="https://article-helps.techidaily.com/expert-techniques-for-perfect-green-screen-cinematography/"><u>Expert Techniques for Perfect Green-Screen Cinematography</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/expert-recommended-photo-restoration-services-save-your-precious-images/"><u>Expert-Recommended Photo Restoration Services: Save Your Precious Images</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-stacked-elements-at-pcs-action-bar/"><u>Fixing Stacked Elements at PC's Action Bar</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unveiling-and-managing-windows-10-actions/"><u>Guide to Unveiling & Managing Windows 10 Actions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-oppo-k11-5g-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Oppo K11 5G’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-draw-on-the-desktop-on-windows-10-and-11/"><u>How to Draw on the Desktop on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-windows-11s-sticky-notes-on-all-your-devices/"><u>How to Use Windows 11'S Sticky Notes on All Your Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Oppo A2? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-security-restrictions-with-rufus-expertise/"><u>Navigating Windows 11'S Security Restrictions with Rufus Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-dormant-wired-controller-on-windows-pc/"><u>Reactivating a Dormant Wired Controller on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/secure-port-scanning-for-network-windows-safety/"><u>Secure Port Scanning for Network Windows Safety</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-rectify-voice-narration-error-in-ms-word/"><u>Solutions to Rectify Voice Narration Error in MS Word</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-cannot-access-device-pathfile-in-windows-fix-guide/"><u>Solving 'Cannot Access Device Path/File' In Windows - Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-application-was-unable-to-start-in-win1011/"><u>Solving The Application Was Unable to Start in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-fixing-frozen-itunes-on-your-pc/"><u>Step-by-Step Guide: Fixing Frozen iTunes on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-system-win11-lightweight-edition/"><u>Streamline Your System: Win11 Lightweight Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-navigation-the-essential-guide-to-win11-shortcuts/"><u>Streamlining Navigation: The Essential Guide to Win11 Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-detecting-missing-disk-on-windows/"><u>Tactics for Detecting Missing Disk on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-discretion-in-windows-11-functionality/"><u>The Art of Discretion in Windows 11 Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/the-basics-how-to-use-microsofts-phone-link-app/"><u>The Basics: How to Use Microsoft's ‘Phone Link’ App</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-window-glow-on-windows-11-computers/"><u>Transforming Window Glow on Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/unclutter-your-taskbar-separate-groups/"><u>Unclutter Your Taskbar: Separate Groups</u></a></li>
<li><a href="https://win11.techidaily.com/unified-solutions-overcoming-issues-with-windows-defender-threat-engine/"><u>Unified Solutions: Overcoming Issues with Windows Defender Threat Engine</u></a></li>
<li><a href="https://win11.techidaily.com/uninvited-rav-security-on-pc-origins-and-deletion-steps/"><u>Uninvited Rav Security on PC - Origins and Deletion Steps</u></a></li>
<li><a href="https://os-tips.techidaily.com/unveiling-our-insights-ios-18-forecasts-advanced-apple-ai-and-enhanced-siri-at-wwdc24-plus-latest-gadget-releases/"><u>Unveiling Our Insights: IOS 18 Forecasts, Advanced Apple AI & Enhanced Siri at WWDC24 Plus Latest Gadget Releases!</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-artistry-bring-your-desktop-imagery-to-life/"><u>Windows 11 Artistry: Bring Your Desktop Imagery to Life</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>