---
title: "Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands"
date: 2024-08-16T00:20:45.269Z
updated: 2024-08-17T00:20:45.269Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands"
excerpt: "This Article Describes Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands"
keywords: WinErrorFixGuide,FixWindowsErrors,CommandLineTroubleshoot,WindowsCommandSolve,DebugWinMessages,ErrorMsgCommands,MessageFindTools
thumbnail: https://thmb.techidaily.com/1eb9ced51df0b5377c33b33676973c39490da0549a761ceba775a1dae7d61065.jpg
---

## Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands

 Encountering random errors and crashes while using the operating system without an explanation can be frustrating. It also makes it harder to find the appropriate solutions, because you have no clue what caused the problem in the first place.

 In this guide, we will show you how you can use the Command Prompt utility to identify potential culprits behind annoying Windows errors. We will also discuss how you fix the issue using CMD as well.

## How to Diagnose Windows Errors in the Command Prompt

 To solve a problem in Windows, such as an update error or a Blue Screen of Death, it's important to identify the potential causes of the issue. Windows comes with several utilities that can help you with this, one of which is Command Prompt.

 Below, we have discussed different ways of using Command Prompt to look up Windows error codes.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Use the NET HELPMSG Command

 The NET HELPMSG command helps convert error codes into strings, which you can use to find relevant solutions for the problem. However, this command can only help you with system error codes, which are specific numerical values. This means you cannot use it for BSOD errors like the INACCESSIBLE\_BOOT\_DEVICE error.

Moreover, the numerical value of the error code must also be precise.

Here is how you can use this command:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type "cmd" in Run and press the**Ctrl + Shift + Enter** keys together to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit**Enter** to execute it. Replace <error code> with the numerical value of the code.  
`NET HELPMSG <error code>`
5. For instance, if the error code you want lookup is 8242, your command will be:  
`NET HELPMSG 8242​​​`  
![Execute the net helpmsg command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/net-helpmsg-error.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

 Once you have the details on the error code, you can either look for solutions online or jump to the solutions listed later in this guide.

### 2\. Use the CertUtil Command

 Another easy way to look up error descriptions using the Command Prompt is by using the CertUtil command. This command is typically used for managing certificates and certificate services, but can also be a helpful tool in finding short explanations for the error codes.

Here is how you can use it:

1. Open Command Prompt using the steps we have described above.
2. In the Command Prompt window, execute the command below. Replace <error code> with the error code you are encountering:  
`CertUtil /error <error code>`
3. So for instance, if you are encountering the update error 0x80070002, your command will be:  
`CertUtil /error 0x80070002​​​​`  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/certutil-command.jpg)

 You should now be presented with a description of the error message. You can use this detail to identify the culprit and eliminate it.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Access the Event Viewer

 When you encounter an error on Windows, a log file for the error is created in the Event Viewer. This log file contains the details of the event, including the time and date it occurred, the error code associated with it, and the source of the event.

 You can [access the Event Viewer using the Command Prompt](https://www.makeuseof.com/windows-open-event-viewer/) to identify the culprit behind the error, and then proceed with the relevant solutions to fix the problem.

## How to Resolve the Problem Using the Command Prompt

 Once you have identified the problem, you can use the Command Prompt utility to fix it as well. Windows comes with a set of troubleshooting utilities that can you can run via this command-line interface to resolve system issues once and for all.

 Here are some common ways you can use the Command Prompt to diagnose and resolve various issues with your Windows operating system.

### 1\. Fix Any Corruption Errors

 There are a number of problems that may result from corruption errors and bugs within the operating system, such as frequent crashes and freezes, boot problems, data loss, and slow performance.

 The easiest way to fix such issues is by [running the built-in SFC and DISM tools](https://www.makeuseof.com/windows-built-in-repair-tools/) via Command Prompt.

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 SFC or the System File Checker works by scanning the protected system files to check their integrity. It will compare the files to a stable version stored in the Windows component store or the installation media. If a problem with the file is identified, the utility will automatically replace the file with its healthier counterpart and generate a report based on it.

 DISM, on the other hand, can be used to repair a wide range of issues, including system files, problematic drivers, and a corrupt Windows image. It is considered to be more advanced and powerful than SFC.

 Once you have completed an SFC scan, you can check the log file for more detailed information as well. Simply execute this command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >"%userprofile%\Desktop\sfcdetails.txt`

 Doing so will create a log file named sfcdetails.txt on your desktop, listing all the issues found during the scan.

### 2\. Uninstall Windows Updates

 There are times when an update you install on the system turns out to be buggy or corrupt, leading to different issues within the system.

 Since Windows provides you with the option to uninstall updates, you can use Command Prompt to achieve this.

 Simply open Command Prompt as an administrator and execute the command listed below to view a list of installed updates:

`wmic qfe list brief /format:table`

 To uninstall one, execute the following command. Replace <HotFixID> with the ID number of the update that you want to uninstall.

`wusa /uninstall /kb:<HotFixID>`

![Uninstall the update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-update-cmd.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### 3\. Fix Boot Issues

 If you are having trouble booting into Windows, or the boot time is just painfully slow, the issue is likely to be related to the boot sector or boot configuration data (BCD).

You can use the bootrec command to repair these via Command Prompt.

Here is how you can do that:

1. [Boot into WinRE](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) and head over to Repair your computer.
2. Navigate to**Troubleshoot** \>**Advanced options** .  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
3. Choose**Command Prompt** from the list of options available.
4. Once you are in the Command Prompt window, execute the following commands:  
`bootrec /fixmbr bootrec /fixboot bootrec /rebuildbcd`
5. If you are prompted with Add installation to boot list?, type Y and hit Enter.
6. Once all the commands are executed, you can exit Command Prompt by typing exit and hitting Enter.
7. Restart your computer, and you should be able to boot into Windows successfully!

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## The Command Prompt to the Rescue

 Having knowledge of certain Windows tools can come in handy when dealing with various computer-related issues. One such utility that can help you find solutions is Command Prompt and knowing how to use it can save you both time and frustration.

 We highly recommend backing up your essential data before making any changes to your operating system, just to be safe. With a little patience and some troubleshooting skills, you can get rid of annoying Windows errors for good.


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
<li><a href="https://youtube-zero.techidaily.com/024-approved-secure-your-videos-with-free-image-savers/"><u>[New] 2024 Approved  Secure Your Videos with FREE Image Savers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-explore-the-ultimate-list-of-comedy-tears-on-instagram-for-2024/"><u>[New] Explore the Ultimate List of Comedy-Tears On Instagram for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-mastering-macbook-webcam-footage/"><u>[New] Mastering MacBook Webcam Footage</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-step-up-your-game-techniques-for-bordered-instagram-videos/"><u>[Updated] 2024 Approved  Step Up Your Game  Techniques for Bordered Instagram Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-cut-trim-and-enhance-leading-apps-for-android-and-pc-editing-for-2024/"><u>[Updated] Cut, Trim & Enhance  Leading Apps for Android and PC Editing for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-effortless-iphone-screen-recording-techniques-unveiled-for-2024/"><u>[Updated] Effortless iPhone Screen Recording Techniques Unveiled for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-enhance-your-story-game-applying-fun-sticker-themes/"><u>[Updated] In 2024, Enhance Your Story Game  Applying Fun Sticker Themes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-elevate-your-video-speed-on-instagram-desktop-guide/"><u>2024 Approved  Elevate Your Video Speed on Instagram  Desktop Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-swift-strategies-to-end-windows-10s-unstable-photo-viewing/"><u>2024 Approved  Swift Strategies to End Windows 10'S Unstable Photo Viewing</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-understanding-video-storage-daylong-total-in-gbs/"><u>2024 Approved  Understanding Video Storage  Daylong Total in GBs</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-remove-the-microsoft-store-app-from-windows-11/"><u>3 Ways to Remove the Microsoft Store App From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-tactics-to-turn-windows-into-a-mac-like-interface/"><u>5 Tactics to Turn Windows Into a Mac-Like Interface</u></a></li>
<li><a href="https://win11.techidaily.com/6-costly-misconceptions-about-affordable-windows-codes/"><u>6 Costly Misconceptions About Affordable Windows Codes</u></a></li>
<li><a href="https://win11.techidaily.com/7-common-concerns-against-moving-to-windows-11/"><u>7 Common Concerns Against Moving to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-10-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-simple-steps-for-unlocking-your-windows-hello-device/"><u>8 Simple Steps for Unlocking Your Windows Hello Device</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-windows-snap-configurations-via-powertoys/"><u>A Comprehensive Guide to Windows Snap Configurations via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-tutorial-on-windows-11-hotspot-setup-procedures/"><u>A Comprehensive Tutorial on Windows 11 Hotspot Setup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-support-tasks-map-windows-troubleshooting-tools/"><u>Accelerate Support Tasks: Map Windows Troubleshooting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/add-ons-for-the-classics-mastering-achievements-via-retroarch-software-guide/"><u>Add-Ons for the Classics: Mastering Achievements via Retroarch Software Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-a00f429f-in-windows-camera-functionality/"><u>Addressing Error A00F429F in Windows' Camera Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alt-code-malfunctions-48-characters/"><u>Addressing Windows ALT Code Malfunctions (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies!</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-pc-a-guide-to-optimizing-windows-11-options/"><u>Adjusting Your PC: A Guide to Optimizing Windows 11 Options</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-multi-archive-handling-in-windows-os/"><u>Advanced Multi-Archive Handling in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-the-non-functional-windows-enter-key/"><u>Ameliorating the Non-Functional Windows Enter Key</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bask-in-the-best-of-microsofts-winstore-treasures/"><u>Bask in the Best of Microsoft’s WinStore Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-blue-screens-in-your-daily-computing-life/"><u>Beating Back Blue Screens in Your Daily Computing Life</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-system-uncrashing-win1011s-corrupt-bin-error/"><u>Beating the System: Uncrashing Win10/11's Corrupt Bin Error</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-tutorial-starting-windows-media-player/"><u>Beginner's Tutorial: Starting Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/blending-worlds-kali-installation-guide-for-windows-users/"><u>Blending Worlds: Kali Installation Guide for Windows Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-samsung-galaxy-a25-5g-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Samsung Galaxy A25 5G Through Google Earth?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-honor-v-purse-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Honor V Purse FRP Without Computer</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-prime-windows-10-photoviewing-suite/"><u>In 2024, Prime Windows 10 Photoviewing Suite</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-step-by-step-guide-for-capturing-fb-streams/"><u>In 2024, Step-by-Step Guide for Capturing FB Streams</u></a></li>
<li><a href="https://win11.techidaily.com/1719335120399-python-package-installation/"><u>Python Package Installation:</u></a></li>
<li><a href="https://win11.techidaily.com/1719336618337-quick-fix-guide-overcome-incompatibility-in-windows-xp/"><u>Quick-Fix Guide: Overcome Incompatibility in Windows XP</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Honor X8b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719352483219-resurrect-computer-sounds-immediate-action-steps/"><u>Resurrect Computer Sounds – Immediate Action Steps!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-rdr2-memory-errors-with-simple-pagefile-enhancement-techniques/"><u>Troubleshoot RDR2 Memory Errors with Simple Pagefile Enhancement Techniques</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-potential-of-apple-books-app-through-a-thorough-review/"><u>Unveiling the Potential of Apple Books App Through a Thorough Review</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Nokia C32? | Dr.fone</u></a></li>
</ul></div>
