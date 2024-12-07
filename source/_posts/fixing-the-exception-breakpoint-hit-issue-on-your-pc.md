---
title: Fixing The Exception Breakpoint Hit Issue on Your PC
date: 2024-12-04T16:10:51.513Z
updated: 2024-12-06T16:01:33.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing The Exception Breakpoint Hit Issue on Your PC
excerpt: This Article Describes Fixing The Exception Breakpoint Hit Issue on Your PC
keywords: Fix Breakpoint Issue,Resolve Exception Error,Debugger Problem Fix,Error Hit Point Resolve,Cleanup Code Glitch,Patch Debug Crash,Stop Exception Stop
thumbnail: https://thmb.techidaily.com/61e1fbca092ac5d2ffa00e76582e3823f6ee9bd8608e03fb6613489ba0869657.jpg
---

## Fixing The Exception Breakpoint Hit Issue on Your PC

 When you try to shut down or restart your PC, you may encounter an error that reads "the exception breakpoint has been reached." This error can also occur when you try to open specific apps on your PC.

 Issues with your system files, glitchy apps, memory leaks, and bad disk sectors are common contributing factors to this error. If you experience this error, here is a quick troubleshooting guide to help you fix the "the exception breakpoint has been reached" error on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Any Automatic Startup Apps

 Apart from the essential Windows services, third-party apps enabled to run during startup can cause conflicts and cause problems. To determine the cause, disable all the automatic startup apps and restart your PC.

To disable startup apps on Windows:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Task Manager** to open the app.
3. In Task Manager, open the**Startup apps** tab.
4. Click the**Status** column to sort the table with the enabled apps at the top.
5. Select all the apps one by one and click**Disabled** .  
![disable startup apps windows 11 new](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/disable-startup-apps-windows-11-new.jpg)

 Once done, restart your PC and check if the error persists. If not, enable the apps again one by one until you find the problematic application. Depending on the use, you can update, uninstall or find an alternative for the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the System File Checker and the DISM Tools

 The Deployment Image Service Management (DISM) tool is a command-line utility that can find and fix issues with your Windows image. If your error is triggered by a corrupt system image, the DISM command can help you fix the error.

 In addition, we'll also run the System File Checker utility. Like DISM, the System File Checker is a built-in command-line utility to detect and fix corrupted or missing system files on Windows computers.

Follow these steps to run the DISM and System File Checker tools:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you need help).
2. In the Command Prompt window, type the following command to check your system health:  
`Dism /Online /Cleanup-Image /CheckHealth`
3. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt-1.jpg)  
 Next, type the following command and press**Enter** to scan your PC's health:  
`Dism /Online /Cleanup-Image /ScanHealth`
4. Once done, type the following command to repair the system image:  
`Dism /Online /Cleanup-Image /RestoreHealth`
5. This process may take several minutes, so wait till the verification reaches 100%.
6. Once done, type the following command to execute the System File Checker utility:  
`sfc /scannow`
7. This process can take some time to complete. Once the verification reaches 100%, it will display the result and any actions taken.
8. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check Your Hard Drive for Errors With CHKDSK

 Check Disk (CHKDSK) is a Windows command-line utility to find and fix issues on your hard drive due to bad sectors. You can run the tool on your traditional mechanical hard drive and Solid State Drives (SSDs).

 You can use the CHKDSK utility with multiple parameters. Here we'll use the /r parameter to locate bad sections and recover readable information.

To run the CHKDSK tool:

1. Open Command Prompt as administrator, as you did in method two.
2. In the Command Prompt window, type the following command and press**Enter** to run the CHKDSK utility:  
`chkdsk C: /r`

![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-chkdsk-command.jpg)

 When executed, it will scan and check your system drive (C:/) for bad sectors. Wait for the scan to finish and close the Command Prompt window.

## 4\. Turn Off Any GPU Overclocking

 If the error is triggered while performing a graphic-intensive task (such as playing a game or rendering 3D models), it can be due to an overclocked GPU.

 While an overclocked GPU offers performance benefits, it can cause your system to crash and trigger multiple errors if not done correctly. Whether you have used a third-party GPU overclocking tool or a proprietary app from your GPU manufacturer, undo all the recent instances of GPU overclocking to see if that helps fix this error.

 If you need help with overclocking, check out[the best GPU overclocking tools](https://www.makeuseof.com/best-gpu-overclocking-tools/) to get the best results.

## 5\. Check for Memory Leaks

 The "the exception breakpoint has been reached" 0x80000003 can occur if your system fails to efficiently utilize the available memory resulting in a memory leak. Fortunately, Window comes with a built-in Memory Diagnostic Tool to check your computer for memory problems. Here's how to do it.

1. Make sure to save all the work and close all the running apps.
2. Press**Win + R** to open**Run** .
3. Type**mdsched.exe** and click**OK** .
4. In the**Windows Memory Diagnostic** dialog, click**Restart now and check for problems (recommended)** .  
![Windows memory diagnostic tool restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-memory-diagnostic-tool-restart.jpg)
5. Your computer will restart and boot into the Windows Memory Diagnostic Tool menu, and the system will start a test automatically.  
![Windows memory diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-memory-diagnostic-tooljpg.jpg)
6. You can also perform**Basic, Standard, or Extended** test manually. To do this, press**F1** to access the**Options** menu and select from the**Basic, Standard, and Extended** option under the**Test Mix** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. If a problem is detected, you can view it under the Status section. Even if the test appears inactive or stuck, do not shut down your computer until testing is complete.
8. Once done, the PC will start, and the Windows Memory Diagnostic Tool will display the test result after you log on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Create a New Windows Local Account

 A corrupted user profile may cause the "the exception breakpoint has been reached" error. To fix the error, you can[create a new user local user profile on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) and give it administrator privilege. Sign into your new user profile and launch the app to see if the error is resolved.

## 7\. Update or Uninstall the Problematic App

 If specific apps trigger the error, such as the Origin launcher or the Steam client, consider reinstalling the app to solve the issue.

 Before you uninstall it, check if your app has any pending updates. Install any update available and check for any improvements. If the issue persists, reinstalling the app may be necessary.

To uninstall an application on Windows:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Install** **apps** .  
![windows 11 settings installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-installed-apps.jpg)
4. Type the name of your app in the search bar.  
![uninstall apps windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-apps-windows-11.jpg)
5. Next, click**the three-dots menu** next to the app name and**Uninstall** .
6. Click on**Uninstall** again to confirm the action.
7. Once uninstalled, download the app installer and install the app. Restart your PC and check for any improvements.

 Note that, at times, the issue can be with a specific version of the app. To fix this, try to install an older version of the app to see if that works.

## Fixing the "The Exception Breakpoint Has Been Reached" Error on Windows

 This error is often related to your system's inability to utilize the memory resources available due to system file corruption or issues with your hard disk. Use the built-in Windows image repair and System File Checker too to resolve system issues. Also, install pending updates for the app or reinstall the problematic app to fix the problem.

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
<li><a href="https://youtube-zero.techidaily.com/n-2024-audiovisual-quality-its-significance-in-video-ranking/"><u>[New] In 2024, Audiovisual Quality Its Significance in Video Ranking</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-step-by-step-ps4-recording-techniques-for-gamers/"><u>[New] In 2024, Step-by-Step PS4 Recording Techniques for Gamers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-macpros-screenflow-insight-a-comprehensive-guide-for-2024/"><u>[New] MacPro's ScreenFlow Insight A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transforming-vr-skeletons-into-your-ideal-digital-persona/"><u>[New] Transforming VR Skeletons Into Your Ideal Digital Persona</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-intellectual-property-guidelines-for-instahits/"><u>[Updated] 2024 Approved Intellectual Property Guidelines for InstaHits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-crafting-soundscapes-how-to-use-auditions-fade-in-effect/"><u>[Updated] Crafting Soundscapes How to Use Audition's Fade In Effect</u></a></li>
<li><a href="https://win11.techidaily.com/dont-want-to-upgrade-tips-for-optimizing-your-existing-os/"><u>Don't Want to Upgrade? Tips for Optimizing Your Existing OS</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-user-experience-with-phones-and-windows-11/"><u>Empowering User Experience with Phones & Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-diagnose-and-repair-chatgpt-problems-on-iphone-9-effective-fixes/"><u>How To Diagnose & Repair ChatGPT Problems on iPhone - 9 Effective Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-or-bypass-the-unable-to-terminate-process-error-on-windows/"><u>How to Fix or Bypass the Unable to Terminate Process Error on Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-get-in-on-invite-only-bargains-for-amazons-prime-day-event-your-ultimate-registration-walkthrough-zdnet/"><u>How to Get in on Invite-Only Bargains for Amazon's Prime Day Event - Your Ultimate Registration Walkthrough | ZDNet</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/innovative-tiktok-pfps-to-captivate-your-followers-for-2024/"><u>Innovative TikTok PFPs to Captivate Your Followers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-method-enablingdisabling-power-saving-modes/"><u>Quick Method: Enabling/Disabling Power Saving Modes</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-code-x80780119-error-in-windows-imaging/"><u>Remedy Code X80780119 Error in Windows Imaging</u></a></li>
<li><a href="https://win11.techidaily.com/surge-productivity-incorporating-flow-launcher-into-routine/"><u>Surge Productivity: Incorporating Flow Launcher Into Routine</u></a></li>
<li><a href="https://win11.techidaily.com/surge-your-vm-efficiency-on-windows-master-these-6-techniques/"><u>Surge Your VM Efficiency on Windows: Master These 6 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-classic-ribbon-in-new-windows-era/"><u>The Path to Classic Ribbon in New Windows Era</u></a></li>
</ul></div>

