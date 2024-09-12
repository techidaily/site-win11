---
title: Exploring the Role of Windows ~BT Directories in OS
date: 2024-09-11T09:45:18.254Z
updated: 2024-09-12T09:45:18.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring the Role of Windows ~BT Directories in OS
excerpt: This Article Describes Exploring the Role of Windows ~BT Directories in OS
keywords: Windows BT Folder Guide,Operating System Windows,BT Directory Functions,OS Window Integration,Windows BT File Paths,BT Directories in OS,Windows OS Configuration
thumbnail: https://thmb.techidaily.com/14ec62870ba2076f7e8c9687f751c49a66df2b130718dc75492a59a5c4cfcb22.jpg
---

## Exploring the Role of Windows ~BT Directories in OS

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-peeling-back-layers-what-hides-beneath-each-snapchat-emoji/"><u>[New] 2024 Approved Peeling Back Layers What Hides Beneath Each Snapchat Emoji?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-resolution-spaces-for-online-viewers/"><u>[New] High-Resolution Spaces for Online Viewers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-deciphering-social-media-copyright-laws-including-fb/"><u>[New] In 2024, Deciphering Social Media Copyright Laws, Including FB</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-the-starscape-a-guide-to-influencers-for-your-needs/"><u>[New] Navigating the Starscape A Guide to Influencers for Your Needs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-streamlining-the-process-dells-way-to-screen-recording/"><u>[Updated] 2024 Approved Streamlining the Process Dell's Way to Screen Recording</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-asmr-gurus-recommend-best-microphones-reviewed-for-2024/"><u>[Updated] ASMR Gurus Recommend Best Microphones Reviewed for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-audible-illusion-how-does-this-voice-change-application-work-alternatives-awaits/"><u>[Updated] Audible Illusion How Does This Voice Change Application Work? Alternatives Awaits</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-expertly-evaluating-webcam-technology-for-professionals-for-2024/"><u>[Updated] Expertly Evaluating WebCam Technology for Professionals for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-launching-professional-instagram-starting-an-enterprise-account/"><u>[Updated] In 2024, Launching Professional Instagram Starting an Enterprise Account</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-innovative-advanced-gaming-monitoring-tools-for-a-better-experience/"><u>[Updated] Innovative, Advanced Gaming Monitoring Tools for a Better Experience</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-digital-freedom-list-best-10-mp3-makers/"><u>2024 Approved Digital Freedom List Best 10 MP3 Makers</u></a></li>
<li><a href="https://fox-that.techidaily.com/boosting-safari-speed-top-4-fixes-for-a-faster-iphone-experience/"><u>Boosting Safari Speed: Top 4 Fixes for a Faster iPhone Experience</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-using-windows-canary-service/"><u>Comprehensive Guide for Using Windows' Canary Service</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-cannot-create-window-errors-on-windows/"><u>Decoding the 'Cannot Create' Window Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-network-drive-configuration-for-enhanced-workflow/"><u>Efficient Network Drive Configuration for Enhanced Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-workspace-individual-monitors-in-windows-11/"><u>Elevating Your Workspace: Individual Monitors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-precision-and-speed-of-windows-11-laptop-screens/"><u>Enhance Precision and Speed of Windows 11 Laptop Screens</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-frayed-script-extensions-in-skyrim-games/"><u>Fixing Frayed Script Extensions in Skyrim Games</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-driver-verifier-manager-in-windows-11/"><u>How to Open the Driver Verifier Manager in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-err0r-x7e1-on-win10-pcs/"><u>How to Reset Err0r: X7E1 on Win10 PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-a-disable-iphone-6-plus-using-macos-finder-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock a disable iPhone 6 Plus using macOS finder</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-vivo-s17e-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Vivo S17e PC | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/isolating-and-remedying-solo-sideheadphone-glitches-in-win/"><u>Isolating and Remedying Solo Sideheadphone Glitches in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/key-complementary-aid-for-elevating-your-windows-11-use/"><u>Key Complementary Aid for Elevating Your Windows 11 Use</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-tcpip-with-python-servers-on-windows-networks/"><u>Leveraging TCP/IP with Python Servers on Windows Networks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-search-configurations-reset/"><u>Mastering Windows 11 Search Configurations Reset</u></a></li>
<li><a href="https://win11.techidaily.com/modify-display-scaling-in-windows-11/"><u>Modify Display Scaling in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-subsystem-for-linux-solving-error-4294967295/"><u>Navigating Through Windows Subsystem for Linux: Solving Error 4294967295</u></a></li>
<li><a href="https://win11.techidaily.com/onedrives-invalid-reparse-point-a-guide-to-mend-it-on-windows/"><u>OneDrive’s Invalid Reparse Point: A Guide to Mend It on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-with-googles-nearby-sharing-on-pc/"><u>Overcoming Errors with Google's Nearby Sharing on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-block-after-failure/"><u>Overcoming Windows Login Block After Failure</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-unsupported-boot-state-in-windows/"><u>Quick-Fix for Unsupported Boot State in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/refinement-of-console-controls-in-depth-windows-techniques/"><u>Refinement of Console Controls: In-Depth Windows Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/regain-command-function-keys-restoration-in-win10/"><u>Regain Command: Function Keys' Restoration in Win10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-loss-of-critical-dll-reinstating-mfc71u-on-pcs/"><u>Resolving Loss of Critical DLL: Reinstating Mfc71u on PCs</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-poe-game-crashes-a-step-by-step-guide/"><u>Resolving POE Game Crashes: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-the-impact-of-glitches-winvolume-fix-guide/"><u>Reverse the Impact of Glitches: WinVolume Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-merge-your-android-with-a-windows-system/"><u>Seamlessly Merge Your Android with a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-installation-failure-on-discord-win/"><u>Strategies to Overcome Installation Failure on Discord (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsoft-store-errors-the-quick-fix-for-0x80072efd/"><u>Tackling Microsoft Store Errors: The Quick Fix for 0X80072EFD</u></a></li>
<li><a href="https://some-approaches.techidaily.com/techniques-to-purge-background-from-photos-using-photopea-for-2024/"><u>Techniques to Purge Background From Photos Using Photopea for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-resolving-not-handled-error-on-windows-1011/"><u>Tips for Resolving Not Handled Error on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-11-reading-comics-like-never-before/"><u>Transforming Windows 11: Reading Comics Like Never Before</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-the-0x8007045d-blue-screen/"><u>Understanding and Remedying the 0X8007045D Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-steps-for-windows-copilot-enablement/"><u>ViveTool Steps for Windows Copilot Enablement</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-down-follow-these-9-simple-steps-to-fix-it/"><u>Win 11’S Bluetooth Down? Follow These 9 Simple Steps to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-webcam-troubleshooting-avoid-code-0xa00f4289/"><u>Win10/11 Webcam Troubleshooting - Avoid Code 0xA00F4289</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-google-play-setup-protocols/"><u>Windows 11 Google Play Setup Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/windows-component-tools-accessing-and-operating-guide/"><u>Windows Component Tools: Accessing & Operating Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-innovations-effortless-navigation-of-qr-codes/"><u>Windows Innovations: Effortless Navigation of QR Codes</u></a></li>
<li><a href="https://win11.techidaily.com/windows-reset-triggers-top-10-tips/"><u>Windows Reset Triggers: Top 10 Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    