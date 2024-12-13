---
title: Steps to Take When PowerShell Won't Show Up in Windows
date: 2024-12-06T08:45:12.848Z
updated: 2024-12-12T18:28:43.119Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Take When PowerShell Won't Show Up in Windows
excerpt: This Article Describes Steps to Take When PowerShell Won't Show Up in Windows
keywords: PowerShell Troubleshooting Guide,Enable PowerShell Display,Fixing No Output Issue,Windows PowerShell Initialization,Resolve PS Command Errors,Start PowerShell on Win OS,PowerShell Management Tips
thumbnail: https://thmb.techidaily.com/e0fa0d67e26442f6514904daf3cc23134382c2cc52f88c01d78e6b3f6c28c68c.jpg
---

## Steps to Take When PowerShell Won't Show Up in Windows

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see[how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on[how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the[differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on[how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Sign in with your newly created account, and see if Windows can find PowerShell now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.

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
<li><a href="https://desktop-recording.techidaily.com/new-macbook-cam-tutorial-for-smooth-video-capture-for-2024/"><u>[New] MacBook Cam Tutorial for Smooth Video Capture for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-professionals-path-expert-strategies-for-360-youtube-live-broadcasting/"><u>[New] The Professional's Path Expert Strategies for 360° Youtube Live Broadcasting</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-8-best-facebook-scheduler-to-improve-efficiency-for-2024/"><u>[Updated] 8 Best Facebook Scheduler to Improve Efficiency for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-auditory-allure-finding-perfect-background-sounds/"><u>2024 Approved Auditory Allure Finding Perfect Background Sounds</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-ion-air-pro-3-action-camera-review/"><u>2024 Approved ION Air Pro 3 Action Camera Review</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-shed-price-chains-with-free-video-player-pcmac/"><u>2024 Approved Shed Price Chains with Free VIDEO Player (PC/Mac)</u></a></li>
<li><a href="https://win11.techidaily.com/creating-efficient-pathways-software-shortcut-addition-win11-style/"><u>Creating Efficient Pathways: Software Shortcut Addition Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-the-pin-when-projecting-on-windows-11/"><u>How to Disable the PIN When Projecting on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-poco-x6-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Poco X6 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-device-top-tips-from-the-experts-on-wintools/"><u>Jumpstart Your Device: Top Tips From the Experts on WinTools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-error-xc0f1103f-on-windows-11/"><u>Mastering the Resolution of Error Xc0f1103f on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-quiet-cinema-effective-methods-to-address-netflixs-lack-of-audio/"><u>No More Quiet Cinema: Effective Methods to Address Netflix's Lack of Audio</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-system-track-ram-gpu-cpu-use-in-windows-11/"><u>Optimize Your System: Track RAM, GPU, CPU Use in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-nokia-c110-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Nokia C110 and Browser | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rearranging-visual-output-on-pcs/"><u>Rearranging Visual Output on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-task-execution-with-flow-launcher-innovation/"><u>Revolutionize Task Execution with Flow Launcher Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/shift-to-darker-display-with-windows-calc/"><u>Shift to Darker Display with Windows Calc</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x80070194-repairing-onedrive-in-w11-w10/"><u>Tackling 0X80070194: Repairing OneDrive in W11, W10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-vivo-y78plus-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Vivo Y78+ for Streaming | Dr.fone</u></a></li>
</ul></div>

