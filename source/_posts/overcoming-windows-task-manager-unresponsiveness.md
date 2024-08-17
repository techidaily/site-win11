---
title: Overcoming Windows Task Manager Unresponsiveness
date: 2024-08-15T23:46:56.063Z
updated: 2024-08-16T23:46:56.063Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Task Manager Unresponsiveness
excerpt: This Article Describes Overcoming Windows Task Manager Unresponsiveness
keywords: Fixing TMU,TMU Reliability Boost,Improve TMU Access,Quick TMU Startup,Resolve Task Manager Crash,Enhance Windows TMU Function,Optimize TMU Performance
thumbnail: https://thmb.techidaily.com/ed5e683d03ce80f42203b25af8dacdf35686ccffebc444bf15a8e9ff929bc0bb.jpg
---

## Overcoming Windows Task Manager Unresponsiveness

 Task Manager is one of the most important Windows 11/10 system utilities. So, it’s a big issue when Task Manager is not working. Some users have reported Task Manager not opening (working) for them when they try to access it.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

## 1\. Run System File and Image Repair Commands

 Many users have confirmed running system file and image repair commands can fix the Task Manager not working. So, that’s one of the first things you should try for fixing Task Manager when it’s not opening.

 To apply this potential solution, you’ll need to input separate Command Prompt commands for running the DISM (Deployment Image Servicing and Management) and SFC (System File Checker) tools. The SFC tool repairs system files and DISM services the Windows image.

 Follow the instructions in our article about [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) to run the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command2.jpg)

## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.
4. Select **Disabled** or **Not Configured** if you find this policy enabled.  
![The Remove Task Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-window.jpg)
5. Click **Apply** to set the new option for enabling Task Manager.
6. Then close the Remove Task Manager window by clicking **OK**.

 If this policy is not enabled, try turning it on and off. Click **Enabled** and **Apply** to activate the policy. Then select **Disabled**/**Not configured** to disable it.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Initiate an Antivirus Scan

 Malware can sometimes be the reason for the Task Manager not working. Task Manager is targeted by malware because it’s an important system utility. So, [run an antivirus scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) with Windows Security or third-party security software to check for and purge malware from your PC. Select the most thorough antivirus scanning option in whatever option you utilize.

![The antivirus scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scan-now-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Edit the Policies Key

 Note that running an antivirus scan might only eliminate the cause of this issue. Then you would still need to re-enable Task Manager to get it working after purging malware that disabled it. A virus will have likely disabled Task Manager in the registry. You can re-enable the Task Manager by editing the Policies registry key like this:

1. To access Registry Editor, press the **Windows key + S** key combination, enter a **regedit** keyword, and click the matching result shown in the search tool.
2. Next, go to the **Policies** key by inputting this path inside the registry address bar:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Skip to step seven if you can see a **System** subkey. If you can’t, right-click **Policies** and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-options.jpg)
4. Enter **System** in the new key’s text box.
5. Right-click **System** and select **New** \> **DWORD**.

1. Input **DisableTaskMgr** inside the DWORD’s text box.
2. Double-click the **DisableTaskMgr** DWORD within the **System** key.  
![The DisableTaskMgr DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabletskmgr-dword.jpg)
3. The value for the **DisableTaskMrg** DWORD should be **0**. If it’s set any differently, erase the number in the **Value** box and input **0**.
4. Click **OK** to set the **DisableTaskMgr** value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-edit-dword-window.jpg)
5. Now close the Registry Editor. To ensure the changes take effect, [restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) after editing the registry.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Run the PowerShell Command for Re-Registering Apps

 Some users say they managed to fix Task Manager by running a PowerShell command for reinstalling and registering built-in Windows 11/10 apps. If that worked for them, maybe this resolution will fix Task Manager not working on your PC. This is how you can run that PowerShell command:

1. Activate the **Type here to search** box by utilizing the **Windows key + S** keyboard shortcut.
2. Enter **PowerShell** inside the file search box.
3. Click **Run as administrator** for the matching PowerShell app search result.
4. Input this command:  
`Get-AppXPackage | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The PowerShell command that can fix Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-reinstall-apps-command.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
5. Press **Enter** to execute the command and wait for it to finish before exiting PowerShell.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 6\. Change Your User Account

 Windows user account issues can also cause Task Manager to stop working. For example, your user account might be corrupted in some way. In this case, you can try to repair the corrupted user account or set up an entirely new one. Task Manager might work fine in a new user account.

 First, set up a new user account and sign into it to see if Task Manager works there. If it does, transfer all the user files from your old Windows account to the new one. Our guide to [fixing Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes instructions for applying this troubleshooting method.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)

## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## Use Task Manager Within Windows Again

 Task Manager is not something most users can do without. Fortunately, the potential resolutions in this guide will likely resolve many of the Task Manager issues that prevent users from opening and utilizing that utility. At least one will probably kick-start Task Manager on your PC, enabling you to use that tool as required again.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-cutting-edge-tech-analysis-the-best-screen-recorder-roundup/"><u>[New] 2024 Approved  Cutting Edge Tech Analysis  The Best Screen Recorder Roundup</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-elevate-your-story-game-with-multiple-image-strategies/"><u>[Updated] 2024 Approved  Elevate Your Story Game with Multiple Image Strategies</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-perfect-your-technique-how-to-on-overwatch-audio-recordings/"><u>[Updated] Perfect Your Technique  How-To on Overwatch Audio Recordings</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-soniccapture-pro-review-and-download-steps/"><u>[Updated] SonicCapture Pro Review & Download Steps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-create-nfts-a-straightforward-no-fuss-approach/"><u>2024 Approved  Create NFTs  A Straightforward, No Fuss Approach</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-restore-your-usb-wi-fi-on-a-pc/"><u>7 Key Steps to Restore Your USB Wi-Fi On a PC</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-backing-up-and-restoring-notebooks/"><u>A Practical Approach: Backing Up & Restoring Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-creating-windows-11-folders-en-masse/"><u>Accelerate Workflow: Creating Windows 11 Folders En Masse</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-microphone-linkage-in-pc-gaming-with-valorant/"><u>Addressing Disrupted Microphone Linkage in PC Gaming with Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-software-instability-in-windows-store-purchases/"><u>Addressing Software Instability in Windows Store Purchases</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-repair-tool-guide/"><u>Breaking Down Windows Repair Tool Guide</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-windows-11s-integrity-quick-checks/"><u>Confirming Windows 11'S Integrity: Quick Checks</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-complexity-set-terminal-as-the-default-cli/"><u>Cut-Down Complexity: Set Terminal as the Default CLI</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/detecting-changes-in-your-instagram-network-for-2024/"><u>Detecting Changes in Your Instagram Network for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pcs-archives-functionality/"><u>Enhance Your PC's Archives Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/fix-unrecognized-app-warning-during-windows-setup/"><u>Fix Unrecognized App Warning During Windows Setup</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-honor-90-lite-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Honor 90 Lite Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-audit-your-windows-drive-space-usage-efficiently/"><u>How to Audit Your Windows Drive Space Usage Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rescue-your-windows-mail-app-from-the-clutches-of-0x800713f/"><u>How to Rescue Your Windows Mail App From the Clutches of 0X800713F</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-xs-max-to-other-iphone-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone XS Max to other iPhone? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-infinix-note-30-pro-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Infinix Note 30 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-11-experience-introducing-an-augmented-run-feature/"><u>Master Your Windows 11 Experience: Introducing an Augmented Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-missing-driver-issues/"><u>Overcoming Windows Error: Missing Driver Issues</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-issues-troubleshooting-the-vr-game-crashes-on-your-pc/"><u>Resolving Issues: Troubleshooting the VR Game Crashes on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/security-simplified-defaults-in-windows-11-setup/"><u>Security Simplified: Defaults in Windows 11 Setup</u></a></li>
<li><a href="https://win-dash.techidaily.com/speedy-setup-for-your-hp-envy-5055-downloading-the-right-drivers-with-ease/"><u>Speedy Setup for Your HP Envy 5055 - Downloading the Right Drivers with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-unlock-regular-startup-for-outlook-on-safe-mode/"><u>Steps to Unlock Regular Startup for Outlook on Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-interrupt-error-in-windows-11-screensaver/"><u>Swift Solution to INTERRUPT ERROR in Windows 11 Screensaver</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-samsung-galaxy-s23-fe-by-drfone-android/"><u>Three Ways to Sim Unlock Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-access-issues-with-these-top-5-windows-fixes-on-security-keys/"><u>Unlock Access Issues with These Top 5 Windows Fixes on Security Keys</u></a></li>
<li><a href="https://win11.techidaily.com/wired-for-security-swiftly-repairing-windows-features/"><u>Wired for Security: Swiftly Repairing Windows Features</u></a></li>
</ul></div>
