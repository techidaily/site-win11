---
title: How to React When Your Windows Can't Find PowerShell?
date: 2024-09-11T07:26:50.417Z
updated: 2024-09-16T17:29:43.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to React When Your Windows Can't Find PowerShell?
excerpt: This Article Describes How to React When Your Windows Can't Find PowerShell?
keywords: PowerShell No-Power Issue,Troubleshooting PowerShell Loss,Fixing PS Error,Solving No PowerPS Situation,Reactive Steps for PowerFailPS,Addressing Windows + PowerShell Outage,Handling Failure in PowerShell Mode
thumbnail: https://thmb.techidaily.com/230adad01721806c33e8b8bec3c60db44af37ad2338e40c998d0c7dc6ff96d9a.jpg
---

## How to React When Your Windows Can't Find PowerShell?

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

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115945/19272" target="_top" id="2115945">
  <img src="//a.impactradius-go.com/display-ad/19272-2115945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115945/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

<!-- affiliate ads begin -->
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on[how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
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



