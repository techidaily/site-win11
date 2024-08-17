---
title: "Resolving Windows: Insufficient VM RAM Issue"
date: 2024-08-16T00:47:27.586Z
updated: 2024-08-17T00:47:27.586Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows: Insufficient VM RAM Issue"
excerpt: "This Article Describes Resolving Windows: Insufficient VM RAM Issue"
keywords: Fix Windows RAM Errors,Solve WinRAM Shortage,Remedy Windows Memory Crash,Address VM RAM Failure,Tackle Insufficient WinRAM,Correct Windows Virtual Ram Issue,Overcome Low VM RAM Problems
thumbnail: https://thmb.techidaily.com/32c4cc7803fd0fa7e8699abcd5e09dfd5773975b7e23e537fd44d6a1e4e623e1.png
---

## Resolving Windows: Insufficient VM RAM Issue

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out[how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.
5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
4. Then click the**Check for Updates** button.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the[VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-leverage-hashtags-in-igtv-for-fan-base-explosion/"><u>[New] 2024 Approved  Leverage Hashtags in IGTV for Fan Base Explosion</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-best-kid-approved-drones-for-beginning-pilots/"><u>[New] Best Kid-Approved Drones for Beginning Pilots</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-best-practices-for-engaging-with-facebook-live-content-for-2024/"><u>[New] Best Practices for Engaging with Facebook Live Content for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-revealing-the-best-screen-grabbers-for-web-use-for-2024/"><u>[New] Revealing the Best Screen Grabbers for Web Use for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-cutting-edge-guide-master-adobe-captivates-screen-capture-feature/"><u>[Updated] 2024 Approved  Cutting-Edge Guide  Master Adobe Captivate's Screen Capture Feature</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-funimate-masterclass-quick-video-access/"><u>[Updated] Funimate Masterclass  Quick Video Access</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-google-pixel-8-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Google Pixel 8 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-combat-shake-in-visual-media/"><u>2024 Approved  How to Combat Shake in Visual Media</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-slicephoto-inspection/"><u>2024 Approved  SlicePhoto Inspection</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-podcasters-roadmap-to-seo-excellence/"><u>2024 Approved  The Podcaster’s Roadmap to SEO Excellence</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-tips-for-unlocking-youtube-video-comments/"><u>2024 Approved  Tips for Unlocking YouTube Video Comments</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-six-wins-of-win11-over-macos/"><u>A Closer Look: Six Wins of Win11 Over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-smooth-windows-11-transitions-in-place-methods/"><u>Achieving Smooth Windows 11 Transitions: In-Place Methods</u></a></li>
<li><a href="https://win11.techidaily.com/breach-the-barrier-opening-credential-store/"><u>Breach the Barrier: Opening Credential Store</u></a></li>
<li><a href="https://win11.techidaily.com/chronicle-reclaim-unearthing-windows-11s-archive/"><u>Chronicle Reclaim: Unearthing Windows 11'S Archive</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-failed-execution-of-defrag-utility/"><u>Correcting Failed Execution of Defrag Utility</u></a></li>
<li><a href="https://win-blog.techidaily.com/diagnosing-and-repairing-crashes-on-startup-for-the-game-fix-it-friends-fall-guys/"><u>Diagnosing and Repairing Crashes on Startup for the Game 'Fix-It Friends (Fall Guys)'</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-device-health-check-up-the-ultimate-guide-for-windows-11s-uptime/"><u>Dive Into Device Health Check-Up: The Ultimate Guide for Windows 11'S Uptime</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-operators-invisible-input-on-windows/"><u>Elusive Operators: Invisible Input on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-30015-26-in-microsoft-365-for-windows-users/"><u>Fixing Error Code 30015-26 in Microsoft 365 for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/from-start-to-status-bar-windows-taskbar-chronology/"><u>From Start to Status Bar: Windows Taskbar Chronology</u></a></li>
<li><a href="https://extra-information.techidaily.com/handheld-film-smoother-companion-2022/"><u>Handheld Film Smoother Companion 2022</u></a></li>
<li><a href="https://win11.techidaily.com/how-are-c-and-d-drive-identities-unique/"><u>How Are C: And D: Drive Identities Unique?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-on-iphone-15-plus-by-drfone-ios/"><u>How to Bypass iCloud Lock on iPhone 15 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-defender-antivirus-blockage/"><u>How to Bypass Windows Defender Antivirus Blockage</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effectively-restart-your-windows-graphics-driver/"><u>How to Effectively Restart Your Windows Graphics Driver</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-scaling-issues-for-high-dpi-screens/"><u>How to Fix Windows Scaling Issues for High DPI Screens</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-recover-from-the-service-did-not-respond-windows-error-1053/"><u>How to Recover From The Service Did Not Respond Windows Error 1053</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-y27-5g-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo Y27 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-printer-severance-guide-for-windows-computers/"><u>Immediate Printer Severance Guide for Windows Computers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/lenovo-screen-revelation-see-clearly-again/"><u>Lenovo Screen Revelation - See Clearly Again</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-for-windows-11-widgets-a-comprehensive-list-of-enhancements/"><u>New Horizons for Windows 11 Widgets: A Comprehensive List of Enhancements</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-mac-video-creation-made-easy-best-tools-and-apps/"><u>New In 2024, Mac Video Creation Made Easy Best Tools and Apps</u></a></li>
<li><a href="https://win11.techidaily.com/old-school-keys-new-horizon-initiate-windows-11-with-windows-7-key/"><u>Old-School Keys, New Horizon: Initiate Windows 11 with Windows 7 Key</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/optimal-hash-tags-for-youtube-success-story-for-2024/"><u>Optimal Hash Tags for YouTube Success Story for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-windows-hello-fingerprint-recognition-issues/"><u>Quick Fixes to Windows Hello Fingerprint Recognition Issues</u></a></li>
<li><a href="https://win11.techidaily.com/rekindle-your-computers-potential-with-windows-11-via-to-go-and-rufus-path/"><u>Rekindle Your Computer's Potential with Windows 11, Via To Go & Rufus Path</u></a></li>
<li><a href="https://win11.techidaily.com/reliability-monitor-vs-performance-monitor-comparing-two-underutilized-windows-tools/"><u>Reliability Monitor Vs. Performance Monitor: Comparing Two Underutilized Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-interruptexceptionnothandled-in-w11-bsods/"><u>Resolving INTERRUPT_EXCEPTION_NOT_HANDLED in W11 BSODs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-speakers-not-detected-issue/"><u>Resolving Windows: Speakers Not Detected Issue</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-lost-connection-fixes-for-wifi-failures-in-win11/"><u>Reviving Your Lost Connection: Fixes for Wifi Failures in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719378810676-shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-address-microsoft-store-monochrome-issue/"><u>Steps to Address Microsoft Store Monochrome Issue</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-windows-updates/"><u>Steps to Reactivate Deactivated Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-mitigate-winerror-0x80780119/"><u>Strategies to Mitigate WinError 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-microsoft-store-use-in-windows-11/"><u>Streamlining Microsoft Store Use in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/studio-2-unleashed-microsofts-near-perfect-creator-tool/"><u>Studio 2 Unleashed: Microsoft's Near-Perfect Creator Tool</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-disassembling-dism-for-image-recovery/"><u>The Art of Disassembling Dism for Image Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/the-fundamentals-of-using-windows-odbc-connectivity/"><u>The Fundamentals of Using Windows' ODBC Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/title-shaping-desktop-interface-with-icon-distance-manipulation/"><u>Title: Shaping Desktop Interface with Icon Distance Manipulation</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-tier-technology-breakdown-the-guide-to-high-performance-systems/"><u>Top-Tier Technology Breakdown - The Guide to High-Performance Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-installation-sites-for-pc-apps-on-windows/"><u>Tracing Installation Sites for PC Apps on Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-distinctions-home-theaters-versus-stereo-audio-receivers/"><u>Understanding the Distinctions: Home Theaters versus Stereo Audio Receivers</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-eternal-delete-with-a-customized-windows-trash-bin-setup-11/"><u>Unleash Eternal Delete with a Customized Windows Trash Bin Setup (11)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-windows-hdr-capabilities-for-cutting-edge-video-workflows-for-2024/"><u>Unlocking Windows' HDR Capabilities for Cutting-Edge Video Workflows for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-video-editing-hack-how-to-reverse-clips-in-final-cut-pro-for-2024/"><u>Updated Video Editing Hack How to Reverse Clips in Final Cut Pro for 2024</u></a></li>
</ul></div>
