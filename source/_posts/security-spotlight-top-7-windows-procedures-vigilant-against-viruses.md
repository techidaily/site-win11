---
title: "Security Spotlight: Top 7 Windows Procedures Vigilant Against Viruses"
date: 2024-09-05T08:42:02.697Z
updated: 2024-09-06T08:42:02.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Spotlight: Top 7 Windows Procedures Vigilant Against Viruses"
excerpt: "This Article Describes Security Spotlight: Top 7 Windows Procedures Vigilant Against Viruses"
keywords: Win Security Measures,Anti-Virus Tips for PCs,Protecting Windows Systems,Virus Prevention Strategies,Windows Defense Procedures,Top Windows Antivirus Methods,Secure Windows Practices
thumbnail: https://thmb.techidaily.com/90cf06f9730c5591652ae4f421f62950743940a3b49411aac162c7581850732b.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Security Spotlight: Top 7 Windows Procedures Vigilant Against Viruses

 Processes are an unavoidable part of Windows, and it is not unusual to see dozens or hundreds of them in Task Manager. Each process is a program or part of a program that is running. Unfortunately, malware creators know this and are known to hide malicious software behind the names of legitimate processes.

 Here are some of the most commonly hijacked or duplicated processes, along with where they should be located and how to spot a malicious version.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Svchost.exe

 The Service Host, or svchost.exe, is a shared-service process. It allows various other Windows services to share processes. This helps to reduce resource usage, making the system more efficient. You will almost certainly see more than one instance of Svchost.exe in Task Manager, but this is normal. If one or more of these files are compromised by malware, you may notice a distinct reduction in performance.

![the svchost process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/svchost-process.jpg)

 The legitimate Svchost files should be found in**C:\\Windows\\System32** . If you suspect it has been hijacked, check**C:\\Windows\\Temp** . If you see svchost.exe here, it could be a malicious file. Scan the file with your antivirus software, and quarantine it if necessary.

## 2\. Explorer.exe

 Explorer.exe is responsible for the graphical shell. Without it, you would have no Taskbar, Start Menu, File Manager, or even the Desktop. Therefore, it is an essential part of Windows and cannot be disabled.

 Several viruses can use the Explorer.exe filename to hide behind, including trojan.w32.ZAPCHAST. The legitimate file will be in**C:\\Windows** . If you find it in**System32** , you should definitely check it with your antivirus software.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Winlogon.exe

 The Winlogon.exe process is an essential part of the Windows OS. It handles things like loading the user profile during login and locking the computer when the screensaver runs. Unfortunately, because it handles security elements, Windows Logon and the winlogon.exe process are common targets for threats.

 Several Trojan viruses, including Vundo, can be hidden within or disguised as winlogon.exe. The usual location of the Winlogon.exe file is**C:\\Windows\\System32** . If you find it in**C:\\Windows\\WinSecurity** , it could be malicious. One good indication that the process has been hijacked is unusually high memory use.

 Viruses and malware don't just hide behind Windows processes. Here are some[other ways malware can go undetected and hide on your computer](https://www.makeuseof.com/can-malware-go-undetected-how-viruses-hide-from-you/) .

## 4\. Csrss.exe

 The Client/Server Run-Time Subsystem, or Csrss.exe, is an essential Windows process. Although it is not as widely used in modern Windows versions, it is still required by the system and cannot be disabled.

![The csrss process file in folder location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/csrss-process.jpg)

 The Nimda.E virus has been known to mimic the Csrss.exe process, although that is not the only potential threat. The legitimate file should be located in the**System32** or**SysWOW64** folders. Right-click on the Csrss.exe process in Task Manager and choose**Open File Location** . If it is located anywhere else, it is likely to be a malicious file.

## 5\. Lsass.exe

 lsass.exe is an essential process responsible for the security policy on Windows. It verifies the login name and password, among other security procedures. It is unlikely that the process will be hijacked. If it isn't running correctly, you will usually be automatically logged out of your computer. But viruses are known to use the filename to hide.

 Look for the Lsass.exe file in**C:\\Windows\\System32** . This is the only place you should find it. If you see it in another location, such as**C:\\Windows\\system** or**C:\\Program Files** , act with suspicion and scan the file with your antivirus.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Services.exe

 The Services.exe process is responsible for starting and stopping various essential Windows services. Like the other Windows processes in this list, viruses and malware target it because it allows them to hide in plain sight.

 If the file is hijacked, you may notice problems during the startup and shutdown of your PC. Look for the real Services.exe file in the**System32** folder. If it is located anywhere else, such as in**C:\\Windows\\ConnectionStatus** , the file could be a virus.

 The processes mentioned here are essential to the smooth running of Windows. But not all are, and many non-essential[processes can even be closed to help with performance](https://www.makeuseof.com/windows-processes-end-safely-performance/) .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Spoolsv.exe

 The Windows Print Spooler Service, or Spoolsv.exe, is an important part of the printing interface. It runs in the background, waiting to manage things like the print queue when required. The process is not dependent on having a printer connected, so you shouldn't be surprised to see it in Task Manager.

![The spooler process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/spooler-process.jpg)

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
 Perhaps because Spoolsv.exe is easily overlooked, a virus can take the name to make itself seem legitimate. The true spools file can be found in**C:\\Windows\\System32** . The fake file will often appear in**C:\\Windows** , or in a user profile folder.

## How Do You Check if a Process Is Legitimate?

 The Task Manager is your friend when looking for suspicious activity. Infected processes will often behave erratically, consuming more CPU power and memory than is usual. But that isn't always the case, so here are some other ways to check a process is legitimate.

 Most of the essential processes listed here should only appear in the System32 folder. You can easily check the location of a suspicious file in the Task Manager. Right-click on the process and select**Open File Location** . Check the path of the folder that opens to ensure the file is in the correct place.

 Another way to tell if a file is legitimate is to check the size. Most of the .exe files of these essential processes will be under 200kb. Right-click on the process name in Task Manager, select**Properties** and look at the size. If it seems unusually large, take a closer look to determine if it is safe.

 You can also[check the certificate of the EXE file](https://www.makeuseof.com/windows-tell-if-exe-file-is-safe/) . An authentic file will have a security certificate issued by Microsoft. If you see anything else, it is likely to be malicious.

 The final thing to do is scan suspect files with an up-to-date antivirus scanner. Quarantine and remove any files that are flagged as infected. Fortunately, modern versions of Windows come with Microsoft Defender built-in, so learn[how to scan a single file or folder with Microsoft Defender](https://www.makeuseof.com/microsoft-defender-scan-file-folder/) to check any suspicious files you find.

## The Windows Processes That Might Be Hiding a Virus

 Part of keeping your Windows PC safe from malware and viruses is knowing where they hide. Sometimes a malicious file will behave oddly, using too much CPU and memory. But not always. So spotting a suspicious file in other ways is a useful skill.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-discovering-the-secret-to-engaging-content-with-aspect-ratios-in-youtube/"><u>[New] 2024 Approved  Discovering the Secret to Engaging Content with ASPECT RATIOS in YOUTUBE</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-essential-software-for-high-quality-video-capture-on-windows-pcs/"><u>2024 Approved  Essential Software for High-Quality Video Capture on Windows PCs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-mastering-video-cropping-and-export-for-instagram-posts/"><u>2024 Approved  Mastering Video Cropping & Export for Instagram Posts</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-honor-100-pro-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comparative-study-how-microsoft-and-default-windows-user-accounts-diverge/"><u>Comparative Study: How Microsoft and Default Windows User Accounts Diverge</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-webcam-written-as-how-to-fix-your-webcam-showing-a-black-screen-on-windows/"><u>Correcting Windows Webcam' Written as How to FIX Your WebCam Showing a BLACK SCREEN on WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-explorer-photo-functionality/"><u>Enhancing Windows Explorer Photo Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/exciting-laptop-releases-at-ifa-2023/"><u>Exciting Laptop Releases at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/first-timers-guide-to-navigating-windows-tools/"><u>First Timer's Guide to Navigating Windows Tools</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-oneplus-by-fonelab-android-recover-music/"><u>How to recover old music from your OnePlus</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-users-from-changing-the-screensaver-on-windows/"><u>How to Stop Users From Changing the Screensaver on Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-decoding-sonys-screenshot-system-an-in-depth-look-at-ps4-recording/"><u>In 2024, Decoding Sony's Screenshot System  An In-Depth Look at PS4 Recording</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-a24-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy A24 Phone without Any Data Loss</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-nokia-c210-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-printer-support-into-application-guard/"><u>Integrating Printer Support Into Application Guard</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-advanced-visuals-within-edges-security/"><u>Mastering Advanced Visuals Within Edge's Security</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-warhammers-precision-gameplay-end-stuttering-on-windows/"><u>Mastering Warhammer's Precision Gameplay - End Stuttering on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-with-high-dynamic-range-on-windows-11-systems/"><u>Pushing Boundaries with High Dynamic Range on Windows 11 Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/razer-kraken-microphone-malfunction-troubleshooting-and-fixes/"><u>Razer Kraken Microphone Malfunction: Troubleshooting and Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/re-enabling-disabled-recycle-bin-on-win11/"><u>Re-Enabling Disabled Recycle Bin on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-not-found-entry-point-errors/"><u>Rectifying Windows 'Not Found' Entry Point Errors</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-your-system-replacing-outdated-windows-cards/"><u>Rejuvenating Your System: Replacing Outdated Windows Cards</u></a></li>
<li><a href="https://win11.techidaily.com/removing-restrictions-for-microsoft-store-in-windows-11/"><u>Removing Restrictions for Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-copypaste-errors-on-windows-11-pcs/"><u>Resolving Copy/Paste Errors on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-errors-in-windows/"><u>Resolving Disk Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/snooze-button-secrets-for-window-computers/"><u>Snooze Button Secrets for Window Computers</u></a></li>
<li><a href="https://win11.techidaily.com/solving-microsoft-11s-input-lag-8-effective-steps/"><u>Solving Microsoft 11'S Input Lag: 8 Effective Steps</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722862321446-solving-the-photoshop-scratch-disk-full-dilemma-a-comprehensive-guide/"><u>Solving the Photoshop Scratch Disk Full Dilemma: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-windows-update-eliminating-error-0x800736cc/"><u>Swift Solutions for Windows Update: Eliminating Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/synapse-troubleshoot-restore-functionality-on-windows-devices/"><u>Synapse Troubleshoot: Restore Functionality on Windows Devices</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-xbox-one-elite-series-2-gamepad-assessment-a-must-have-for-gamers/"><u>Top Xbox One Elite Series 2 Gamepad Assessment - A Must-Have for Gamers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlock-the-mystery-fixing-unable-to-dial-or-answer-incoming-calls-in-android-phones/"><u>Unlock the Mystery: Fixing Unable to Dial or Answer Incoming Calls in Android Phones</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-setup-effortless-installation-of-legacy-applications/"><u>Windows 11 Setup: Effortless Installation of Legacy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/windows-arp-cache-explained-and-guide-to-clear-it-out/"><u>Windows ARP Cache Explained & Guide to Clear It Out</u></a></li>
<li><a href="https://win11.techidaily.com/winrush-securing-past-command-actions/"><u>WinRush: Securing Past Command Actions</u></a></li>
</ul></div>
