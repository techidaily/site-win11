---
title: Fixing Blocked Notification Errors for Your PC
date: 2024-09-11T09:30:07.370Z
updated: 2024-09-12T09:30:07.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Blocked Notification Errors for Your PC
excerpt: This Article Describes Fixing Blocked Notification Errors for Your PC
keywords: Fix Notification Issue,Unblock Notifications,Clear Notification Error,Resolve Blocked Alerts,Stop Notification Failure,Correct Noise Notice,Remove Notification Barrier
thumbnail: https://thmb.techidaily.com/696965aa1a0f4c21fdfd456761bb63f354f50ffc3b27173b44a827d0fae8995e.jpg
---

## Fixing Blocked Notification Errors for Your PC

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

## 3\. Run the Program as an Administrator

 Some programs require administrator privileges to function properly. If you try to launch them without elevated access, Windows will block their execution and display the error message. In such a case, you can right-click on the app’s shortcut or the executable file and select **Run as administrator**.

 If it runs successfully, you can adjust the app properties to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). Don't forget to save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable the SmartScreen Filter

 SmartScreen is a security feature that protects your computer from unknown and potentially malicious applications. If it’s enabled, SmartScreen may block an application from running. To disable the feature, follow these steps.

1. Open the **Start** menu and search for _Windows Security_.
2. Click on **Windows Security** in the search results.
3. In the Windows Security app, select **App & browser control**.
4. On the right side of the window, click **Reputation-based protection settings**.  
![Disable the SmartScreen Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-smartscreen-filter.jpg)
5. Toggle off **Potentially unwanted app blocking** and **SmartScreen for Microsoft Store apps**.

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will stop the system from blocking apps, but you should be careful with any programs you download. Once you do it, close the Windows Security app and try running the application again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
3. Once you're in the Local Group Policy Editor window, navigate to the following:  
`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
6. Click **OK** to save the changes.

 After making the changes, close the Registry Editor and restart your computer.

## 7\. Reset Windows Update Components

 If the issue persists, you can reset the Windows Update components, which means restarting certain services that manage the update process and enable you to launch the application.

 To reset Windows Update components, do the following:

1. Click on Start and search for **Notepad**.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. Copy and paste the following code into Notepad:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Now click **File** in the top left corner.
5. Then select **Save as** from the options list.
6. In the Save as window, name your script **Reset.bat** and set the Save as type to **All Files**.
7. Select **Desktop** from the left menu and click **Save**.
8. Double-click on the **Reset.bat** file to run it as an administrator.
9. If the UAC window pops up on the screen, click **Yes** to continue.

 Wait for the process to finish and restart your computer. After the reboot, try running the blocked app again. It should now work without issues.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to Your Apps and Files on Windows

 Windows is known for its tight security which prevents malicious applications from launching and infecting your PC. However, sometimes even legitimate programs are blocked by the operating system and leave an error message saying “This app has been blocked for your protection.”

 There are several reasons why this error occurs. It includes outdated security software, the firewall interfering with the program, or the application not trusted by Windows. Read this guide to learn more about this error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-win11s-best-videography-applications-explored/"><u>[New] 2024 Approved  Win11's Best Videography Applications Explored</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-assemble-ppt-narratives-into-video-for-2024/"><u>[New] Assemble PPT Narratives Into Video for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-maximize-impact-with-onestreams-streaming-solutions/"><u>[New] How to Maximize Impact with OneStream's Streaming Solutions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-master-looped-video-techniques-for-instagram-top-4-strategies/"><u>[New] In 2024, Master Looped Video Techniques for Instagram  Top 4 Strategies</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-canon-camera-insights-for-stunning-time-lapse-vids/"><u>[Updated] Canon Camera Insights for Stunning Time-Lapse Vids</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-journey-through-updates-unveiling-lg-bp550-new/"><u>[Updated] In 2024, Journey Through Updates  Unveiling LG BP550 New</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-sail-through-smooth-sharing-with-instagram-troubleshooting-for-2024/"><u>[Updated] Sail Through Smooth Sharing with Instagram Troubleshooting for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unlocking-the-secrets-of-silent-video-suggestions-in-feed-for-2024/"><u>[Updated] Unlocking the Secrets of Silent Video Suggestions in Feed for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/6-proven-ways-to-unlock-infinix-smart-8-plus-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Infinix Smart 8 Plus Phone When You Forget the Password</u></a></li>
<li><a href="https://win11.techidaily.com/commanding-victory-a-quick-guide-to-voice-commands-on-windows-11/"><u>Commanding Victory: A Quick Guide to Voice Commands on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-error-0xc0000001-expert-tips/"><u>Correcting Windows Error 0xC0000001: Expert Tips</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-the-usefulness-of-windows-11-s-mode/"><u>Deciding on the Usefulness of Windows 11 S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-how-to-navigate-the-mspcm-bar-in-win11-systems/"><u>Dive Deep: How to Navigate the MSPCM Bar in Win11 Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-tv-remote-sterilization-techniques-to-prevent-bacteria-spread/"><u>DIY TV Remote Sterilization Techniques to Prevent Bacteria Spread</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-data-management-combine-on-windows-11/"><u>Elevate Your Data Management: Combine on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-autonomous-command-line-emergence-in-os/"><u>Eliminating Autonomous Command Line Emergence in OS</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-efficiency-integrating-to-dot-and-ifttt/"><u>Enhanced Efficiency: Integrating To-Dot & IFTTT</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes.</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-index-settings-on-windows/"><u>Fine-Tuning Index Settings on Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-honor-magic-6-lite-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-download-speed-suddenly-dropping-to-zero-on-steam-for-windows/"><u>How to Fix the Download Speed Suddenly Dropping to Zero on Steam for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-get-help-app-not-working-on-windows-11/"><u>How to Fix the Get Help App Not Working on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-oculus-setup-failures-in-windows-11-and-10/"><u>How to Overcome Oculus Setup Failures in Windows 11 & 10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-oneplus-11r-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on OnePlus 11R online without jailbreak</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Tecno Camon 30 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Xiaomi Redmi K70E? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-to-launch-google-play-on-w11/"><u>Instructions to Launch Google Play on W11</u></a></li>
<li><a href="https://win11.techidaily.com/launching-a-linux-vm-via-hyper-v-in-windows-environment/"><u>Launching a Linux VM via Hyper-V in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-software-understanding/"><u>Legacy Software Understanding</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-preview-errors-in-windows-outlook/"><u>Mastering the Art of Resolving Preview Errors in Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-no-mistakes-top-10-windows-11-errors-to-evade/"><u>Navigating No Mistakes: Top 10 Windows 11 Errors to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/prime-time-deal-black-friday-612-endless-windows-10/"><u>Prime Time Deal: Black Friday - $6.12, Endless Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-download-guide-latest-compatible-drivers-for-hp-deskjet-3755-multifunction-printers-on-windows-pcs/"><u>Quick Download Guide: Latest Compatible Drivers for HP DeskJet 3755 Multifunction Printers on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-failures-in-windows-defrag-process/"><u>Remedying Failures in Windows Defrag Process</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-link-between-sibling-and-online-printer/"><u>Restoring Link Between Sibling and Online Printer</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/srgb-versus-rgb-a-detailed-comparison-for-professionals-for-2024/"><u>Srgb Versus Rgb  A Detailed Comparison for Professionals for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-your-mouse-pointer-on-windows-10/"><u>Stabilizing Your Mouse Pointer on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-adding-bespoke-pattern-loops-for-windows-pin/"><u>Step-by-Step: Adding Bespoke Pattern Loops for Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-memory-couldnt-be-written-in-windows/"><u>Tackling 'Memory Couldn’t Be Written' In Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-collection-6-top-notch-fps-software-for-windows-11/"><u>The Ultimate Collection: 6 Top-Notch FPS Software for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-uninstall-routes-in-windows-11-118-chars/"><u>The Ultimate List of Uninstall Routes in Windows 11 (118 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-eradicating-breakpoint-exception-error-on-pc/"><u>Tips for Eradicating Breakpoint Exception Error on PC</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-network-types-a-comprehensive-windows-guide/"><u>Uniting Two Network Types: A Comprehensive Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-web-interface-controls/"><u>Unveiling Windows 11'S Web Interface Controls</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-icon-alignment-guide-unite-not-bind/"><u>Win 11 Icon Alignment Guide - Unite Not Bind</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-beta-access-the-insider-program-guide/"><u>Windows 11'S Beta Access: The Insider Program Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>