---
title: Methods to Restart Stuck Windows Task Bar
date: 2024-09-11T09:46:30.331Z
updated: 2024-09-12T09:46:30.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Restart Stuck Windows Task Bar
excerpt: This Article Describes Methods to Restart Stuck Windows Task Bar
keywords: Restart Windows Taskbar,Fix Taskbar Freeze,Windows TaskBar Reset,Unfreezing Taskbar,Start Taskbar Issue,Reboot Taskbar,TaskBar Stuck Fix
thumbnail: https://thmb.techidaily.com/8122148ffac7fe0a0e1d193ba9a136b7cccae081b7348173d3861777fbb2c2bf.jpg
---

## Methods to Restart Stuck Windows Task Bar

 Task Manager is one of the most important Windows 11/10 system utilities. So, it’s a big issue when Task Manager is not working. Some users have reported Task Manager not opening (working) for them when they try to access it.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run System File and Image Repair Commands

 Many users have confirmed running system file and image repair commands can fix the Task Manager not working. So, that’s one of the first things you should try for fixing Task Manager when it’s not opening.

 To apply this potential solution, you’ll need to input separate Command Prompt commands for running the DISM (Deployment Image Servicing and Management) and SFC (System File Checker) tools. The SFC tool repairs system files and DISM services the Windows image.

 Follow the instructions in our article about [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) to run the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Select **Disabled** or **Not Configured** if you find this policy enabled.  
![The Remove Task Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-window.jpg)
5. Click **Apply** to set the new option for enabling Task Manager.
6. Then close the Remove Task Manager window by clicking **OK**.

 If this policy is not enabled, try turning it on and off. Click **Enabled** and **Apply** to activate the policy. Then select **Disabled**/**Not configured** to disable it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118318/7443" target="_top" id="2118318">
  <img src="//a.impactradius-go.com/display-ad/7443-2118318" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Initiate an Antivirus Scan

 Malware can sometimes be the reason for the Task Manager not working. Task Manager is targeted by malware because it’s an important system utility. So, [run an antivirus scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) with Windows Security or third-party security software to check for and purge malware from your PC. Select the most thorough antivirus scanning option in whatever option you utilize.

![The antivirus scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scan-now-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click **OK** to set the **DisableTaskMgr** value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-edit-dword-window.jpg)
5. Now close the Registry Editor. To ensure the changes take effect, [restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) after editing the registry.

## 5\. Run the PowerShell Command for Re-Registering Apps

 Some users say they managed to fix Task Manager by running a PowerShell command for reinstalling and registering built-in Windows 11/10 apps. If that worked for them, maybe this resolution will fix Task Manager not working on your PC. This is how you can run that PowerShell command:

1. Activate the **Type here to search** box by utilizing the **Windows key + S** keyboard shortcut.
2. Enter **PowerShell** inside the file search box.
3. Click **Run as administrator** for the matching PowerShell app search result.
4. Input this command:  
`Get-AppXPackage | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The PowerShell command that can fix Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-reinstall-apps-command.jpg)
5. Press **Enter** to execute the command and wait for it to finish before exiting PowerShell.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Change Your User Account

 Windows user account issues can also cause Task Manager to stop working. For example, your user account might be corrupted in some way. In this case, you can try to repair the corrupted user account or set up an entirely new one. Task Manager might work fine in a new user account.

 First, set up a new user account and sign into it to see if Task Manager works there. If it does, transfer all the user files from your old Windows account to the new one. Our guide to [fixing Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes instructions for applying this troubleshooting method.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

## Use Task Manager Within Windows Again

 Task Manager is not something most users can do without. Fortunately, the potential resolutions in this guide will likely resolve many of the Task Manager issues that prevent users from opening and utilizing that utility. At least one will probably kick-start Task Manager on your PC, enabling you to use that tool as required again.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-understanding-and-executing-photo-gender-modification-across-platforms/"><u>[New] 2024 Approved Understanding and Executing Photo Gender Modification Across Platforms</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-avoid-legal-pitfalls-pre-upload-video-copyright-on-tiktok/"><u>[New] Avoid Legal Pitfalls Pre-Upload Video Copyright on TikTok</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-survive-and-thrive-on-the-streak-frontier-for-2024/"><u>[New] How to Survive and Thrive on the Streak Frontier for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-tips-for-creating-highly-sharable-insta-unpacked-content/"><u>[New] Top Tips for Creating Highly Sharable Insta Unpacked Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-concealed-viewing-of-instagrams-private-content-on-devices/"><u>[Updated] Concealed Viewing of Instagram's Private Content on Devices</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-obs-supreme-vs-streamlabs-empire/"><u>[Updated] In 2024, OBS Supreme vs Streamlabs Empire</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-obs-video-magic-top-5-editing-secrets-revealed/"><u>[Updated] In 2024, OBS Video Magic Top 5 Editing Secrets Revealed</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-profitable-streaming-start-top-8-income-strategies/"><u>[Updated] In 2024, Profitable Streaming Start Top 8 Income Strategies</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-revisiting-radeon-review-and-restore-for-2024/"><u>[Updated] Revisiting Radeon Review and Restore for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-stepwise-instructions-preserve-your-memories-by-uploading-to-snapchat/"><u>[Updated] Stepwise Instructions Preserve Your Memories by Uploading to Snapchat</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-unveiling-the-hidden-treasure-troves-of-snapchat-tones-for-2024/"><u>[Updated] Unveiling the Hidden Treasure Troves of Snapchat Tones for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-prime-screen-snaps-on-apple-devices-max-length-156/"><u>2024 Approved Prime Screen Snaps on Apple Devices (Max Length 156)</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-windows-canary-vulnerability-alerts/"><u>Demystifying the Windows Canary Vulnerability Alerts</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-realme-c33-2023-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Realme C33 2023 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/guarding-against-android-security-risks-how-to-uncover-malicious-software-using-revouninstaller/"><u>Guarding Against Android Security Risks: How to Uncover Malicious Software Using RevoUninstaller</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-achieving-auditory-perfection-top-tips-for-quality-audio/"><u>In 2024, Achieving Auditory Perfection Top Tips for Quality Audio</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-font-power-boosters-secrets-to-stellar-video-thumbnails/"><u>In 2024, Font Power Boosters Secrets to Stellar Video Thumbnails</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-poco-c50-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Poco C50 Lock Screen Password?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-mastering-ppt-a-comprehensive-voice-guidance-manual/"><u>In 2024, Mastering PPT A Comprehensive Voice Guidance Manual</u></a></li>
<li><a href="https://win11.techidaily.com/increase-efficiency-and-control-with-advanced-wsl-2-docker-tactics/"><u>Increase Efficiency and Control with Advanced WSL 2 Docker Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-your-gamer-goals-intact-a-guide-to-epic-saves/"><u>Keeping Your Gamer Goals Intact: A Guide to Epic Saves</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-strategy-behind-extended-updates-for-windows-11/"><u>Microsoft's Strategy Behind Extended Updates for Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/night-of-the-living-dead-games-an-epic-selection/"><u>Night of the Living Dead Games An Epic Selection</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unity-graphical-glitches-fixed-failure-to-initialize-solutions/"><u>Overcoming Unity Graphical Glitches - Fixed Failure to Initialize Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-abrupt-game-endings-fix-tips-for-roblox-on-pc/"><u>Preventing Abrupt Game Endings: Fix Tips for Roblox on PC</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-seamless-file-downloads-in-windows-11/"><u>Re-Establishing Seamless File Downloads in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-microsoft-store-functionality-on-windows-devices/"><u>Reclaiming Microsoft Store Functionality on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-camera-not-found-on-win11-a-step-by-step-guide/"><u>Resolving Camera Not Found on Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-renewal-why-not-go-beyond-windows/"><u>Rethink Renewal: Why Not Go Beyond Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-loadlibrary-failure-code-87/"><u>Steps to Correct LoadLibrary Failure Code 87</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11s-camera-app-failures-error-afc/"><u>Steps to Overcome Windows 11'S Camera App Failures: Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-commands-define-wins-cli/"><u>Streamlining Your Commands: Define Win's CLI</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-technicolor-turnover-desktop-color-fix-tips-for-windows/"><u>Taming the Technicolor Turnover: Desktop Color Fix Tips for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-manual-for-windows-users-using-imessage/"><u>The Ultimate Manual for Windows Users: Using iMessage</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-overcome-local-security-offline-warning/"><u>Tips to Overcome Local Security Offline Warning</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-read-only-reverting-in-file-systems/"><u>Troubleshooting Read-Only Reverting in File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-policies-on-windows-discover-3-vital-approaches/"><u>Unlock Policies on Windows: Discover 3 Vital Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-process-for-ms-office-on-windows-1011/"><u>Unveiling the Process for MS Office on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-methods-to-activate-cortana-in-windows/"><u>ViveTool Methods to Activate Cortana in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-gamers-secret-7-insider-moves-to-up-your-score/"><u>Win 11 Gamers' Secret: 7 Insider Moves to Up Your Score</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    