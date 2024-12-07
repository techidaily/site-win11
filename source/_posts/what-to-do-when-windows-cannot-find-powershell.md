---
title: What to Do When Windows Cannot Find PowerShell
date: 2024-11-30T09:14:42.744Z
updated: 2024-12-07T03:30:47.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What to Do When Windows Cannot Find PowerShell
excerpt: This Article Describes What to Do When Windows Cannot Find PowerShell
keywords: PowerShell No Energy,Fixing PowerShell Power Loss,Addressing Null PowerShell Energy,Resolve PowerShell Power Failure,Tips for Lost PS Power Access,Restarting Without PowerShell,Remedying Disconnected Windows PS
thumbnail: https://thmb.techidaily.com/7e475b588f2cf5836119cf29eeb77a68a0d6cc175af9626b84f7c3d068d74a0f.jpg
---

## What to Do When Windows Cannot Find PowerShell

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your computer after this (see[how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-indoor-games-galore-top-9-screen-less-titles-for-android-gamers/"><u>[New] 2024 Approved Indoor Games Galore Top 9 Screen-Less Titles for Android Gamers</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-essential-date-counting-tools-for-android-and-ios-users-for-2024/"><u>[New] Essential Date-Counting Tools for Android and iOS Users for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-live-stream-perfection-an-experts-take-on-webcams/"><u>[New] In 2024, Live Stream Perfection An Expert's Take on WebCams</u></a></li>
<li><a href="https://win11.techidaily.com/dynamic-workspace-transformation-go-fancywm/"><u>Dynamic Workspace Transformation: Go FancyWM</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-hyper-v-for-flawless-linux-vm-development-on-windows/"><u>Harnessing Hyper-V for Flawless Linux VM Development on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-screen-flashing-on-windows-11-pcs/"><u>How to Stop Screen Flashing on Windows 11 PCs</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-encompassing-insight-a-look-inside-the-google-podcasts-app/"><u>In 2024, Encompassing Insight A Look Inside the Google Podcasts App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-retro-revelry-exploring-the-ultimate-selection-of-gb-console-emulation-for-pcs/"><u>In 2024, Retro Revelry Exploring The Ultimate Selection of GB Console Emulation for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-hidden-windows-startup-details/"><u>Revealing Hidden Windows Startup Details</u></a></li>
</ul></div>

