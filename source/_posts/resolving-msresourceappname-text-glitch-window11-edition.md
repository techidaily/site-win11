---
title: "Resolving 'MsResource:AppName Text' Glitch, Window11 Edition"
date: 2024-08-15T23:57:53.638Z
updated: 2024-08-16T23:57:53.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving 'MsResource:AppName Text' Glitch, Window11 Edition"
excerpt: "This Article Describes Resolving 'MsResource:AppName Text' Glitch, Window11 Edition"
keywords: Fix MsResource Error,Resolve App Name Glitch,Windows 11 Resource Issue,Eliminate Text Error in Win11,Rectify Window11 Resource Glitch,MsResource Fix,Overcome App Name Bug
thumbnail: https://thmb.techidaily.com/cbf413290d1b7e29d9934e3ea1990c5dc72e7e77a07dc3de6c6added5ee7ee53.jpg
---

## Resolving 'MsResource:AppName Text' Glitch, Window11 Edition

 If you have performed an upgrade recently and noticed a weird "ms-resource:Appname/text" entry in the Start Menu, you are not alone. You may also encounter this error when opening a setting or app.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

## 1\. How to Fix the "ms-resource:Appname/Text" Error in the Start Menu

 You can remove the "ms-resource:Appname/Text" entry from the Start Menu by removing the affected application package using PowerShell. Additionally, you can kill the StartMenuExperienceHost.exe process in Task Manager to restart the service.

 Before attempting to remove the app, package, and restart the services, check if you have any Windows updates pending. If you are running a fresh install, try to install all the pending Windows updates. These updates often include bug fixes and may be the only thing you need to do to fix this issue.

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 To check and install Windows updates:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Windows Update** tab.
3. Click on **Check of updates**. Continue to download and install all pending updates.
4. Restart your computer to apply the updates and check if the issue is resolved.

 If the issue persists, you can use PowerShell to remove the affected app package and then restart the associated services to fix the problem.

 To remove the "ms-resource:Appname/Text" entry from the Start Menu:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows** **PowerShell** and select **Run as administrator**.  
![remove holographicsfirstrun app powershell windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-holographicsfirstrun-app-powershell-windows.jpg)
3. In the PowerShell window, type the following command and press **Enter**:  
`Get-AppxPackage -all *HolographicFirstRun* | Remove-AppPackage -AllUsers`

 Once you've run the command, be sure to restart your computer.

1. After the computer restarts, [open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/).
2. Next, open the **Details** tab in Task Manager. On Windows 11, click the three horizontal lines icon to access the details tab.
3. Now you need to locate both **StartMenuExperienceHost.exe** and **Explorer** **.exe**. On Windows 11, you can use the search feature in **Task Manager** to locate the processes.  
![end start menu experience host task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/end-start-menu-experience-host-task-manager.jpg)
4. Right-click on each process and **End Task**.
5. In Task Manager, click **Run new task**. On Windows 10 and older versions, click **File** and select **Run new task**.  
![run new task open tempstate folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-new-task-open-tempstate-folder-file-explorer.jpg)
6. In the **Create new task** dialog, type the following path and click the **Browse** button.  
`%localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy`
7. In the File Explorer window, delete the **TempState** folder.
8. Go back to Task Manager, and click **Run new task**.
9. Type **explorer.exe** and select the **Create this task with administrative privileges** option.

 Once done, give your PC another restart.

## 2\. Re-Register Your Microsoft Store Apps

 You can [re-register Microsoft Store apps using PowerShell](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) to stop the error appearing when using Microsoft apps. Doing so should remove any leftover entries showing up in the Start Menu after the update.

 Wait for the process to complete. This may take a few minutes as the command will try to re-register all the apps, including existing ones. Once the process is complete, restart your computer and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 3\. Check the Microsoft Store for App Updates

 You may see the "ms-resource:Appname/Text" entry if Windows attempted an unsuccessful app installation. To fix the issue, check if an update exists for the app in the Microsoft Store.

 To determine the app name click on the app entry and check if you can find any information about the app. If not, right-click on the app entry in the **Start Menu** and select **Open File Location**.

![view application folder windows 11 run shell apps folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/view-application-folder-windows-11-run-shell-apps-folder.jpg)

 Alternatively, you can view the application directory to view the installed apps. Press **Win + R** to open Run, type **shell:appsfolder**, and click **OK**. It will open the **Applications** folder. Go through the apps to see if you can locate an app named **ms-resource:Appname/Text** or similar to the entry in the Start Menu.

 Once you have the app name, open the Microsoft Store. Search for the app and check if an update exists. Click **Update** to download and install the update. Once installed, restart your computer and check for any improvements.

## What if the "Ms-resource:Appname/Text" Error Appears When Launching an App?

 At times, you may encounter this error when opening a built-in Microsoft Store app. In this instance, you can run the Microsoft Store apps troubleshooter to fix the issue. Here are a few additional troubleshooting steps to fix this error when launching an app.

## 4\. Run the Microsoft Store Apps Troubleshooter

![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-run-button-for-the-app-troubleshooter.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

 You can use the built-in Microsoft Store Apps troubleshooter to fix issues with the store apps. Here’s how to do it.

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.
3. Next, click on **Other troubleshooters**.
4. Click the **Run** button for **Windows Store Apps**. Wait for the troubleshooter to launch and follow the on-screen instructions. It will scan your system against the common Microsoft Store app issues. Apply any recommended fixes and restart your computer to see if the issue is resolved.

 If you don’t see a Windows Store App troubleshooter option, you are likely running a newer version of the OS without this option. In this instance, try to repair the Microsoft Store app.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Repair the Microsoft Store App

![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the Windows Store Apps troubleshooter is missing or didn’t help, try to repair the Microsoft Store App. You can use the built-in repair option to find and fix common issues with the official app store.

 To repair the Microsoft Store app:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab and click on **Installed Apps.**
3. Locate and click the **three-dots** menu beside the **Microsoft Store** app.
4. Select **Advanced Options**.
5. Scroll down to the **Reset** section.
6. Click the **Repair** button, wait for the process to complete, and show a checkmark. If the repair is successful, restart your computer.

### Reset the Microsoft Store App

 In addition to performing a repair, you can also reset the Microsoft Store app to resolve common issues with the store apps. You can perform a reset from the Advanced Options section. Before that, run the wsreset.exe tool to clear the store cache to see if that helps.

 To reset the Microsoft Store App cache:

![wsreset.exe command in the Run tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsreset-exe-command.jpg)

1. Press **Win + R** to open the **Run** dialog.
2. Type **wsreset.exe** and click **OK**.

 Still not resolved? Try to [perform a Microsoft Store reset](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). Doing so will delete all app data, and you may need to sign in to your Microsoft account again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 6\. Other Troubleshooting Steps You Can Try

 If the issue persists, here are a few additional troubleshooting steps you can follow:

1. **Create a new user account** – Try to [create a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to see if the error exists in the new account. This is a handy workaround for a newly set up Windows computer.
2. **Perform a repair reinstall of Windows 11** – You can reinstall [Windows 11 without deleting your apps and files](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). This is an upgrade reinstall and should fix any issues triggered due to issues with the system files.
3. **Perform a reset** – If an in-place upgrade doesn’t help, consider [performing a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). You can perform a complete reset while choosing to keep your files, but all your apps will be removed.
4. **Clean install** – [Performing a Windows clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) will erase everything on your computer and reinstall Windows 11 from scratch. Make sure to back up important data before attempting a clean install.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the "ms-resource:Appname/Text" Error in Windows 11

 Often this entry in the start menu is a ghost entry from an unsuccessful or leftover installation of a Microsoft app. To remove the entry or restore the app, you can re-register the Microsoft app, remove the affected app package or run the Windows Store Apps Troubleshooter.

 If the issue persists, an in-place upgrade, factory reset, or a clean install may be necessary to resolve the issue. This is a time-consuming process, and you may need to set up your computer from scratch.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-essential-gadgets-for-capturing-zoom-sessions/"><u>[New] 2024 Approved  Essential Gadgets for Capturing Zoom Sessions</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-ultimate-guide-to-video-dimensions-on-the-yt-platform/"><u>[New] 2024 Approved  The Ultimate Guide to Video Dimensions on the YT Platform</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-decoding-instagrams-maximum-video-duration-length-limit-for-2024/"><u>[New] Decoding Instagram’s Maximum Video Duration Length Limit for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-zoom-mastery-for-podcasters-a-complete-guide-to-exceptional-audio-capture/"><u>[New] In 2024, Zoom Mastery for Podcasters  A Complete Guide to Exceptional Audio Capture</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagram-to-mp4-perfection-uncover-2-most-effective-techniques/"><u>[Updated] 2024 Approved  Instagram to MP4 Perfection  Uncover 2 Most Effective Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-evaluating-the-efficacy-of-magix-picture-tool/"><u>[Updated] Evaluating the Efficacy of MAGIX Picture Tool</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computing-enable-hyper-v-in-windows-11-homes/"><u>Boost Your Computing: Enable Hyper-V in Windows 11 Homes</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-and-correcting-windows-11-errors/"><u>Confronting and Correcting WINDOWS 11 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-differences-of-windows-terminal-vs-powershell/"><u>Dissecting the Differences of Windows Terminal Vs. PowerShell</u></a></li>
<li><a href="https://tech-revival.techidaily.com/efficient-online-content-production-using-canva-and-chatgpt-integration/"><u>Efficient Online Content Production Using Canva and ChatGPT Integration</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-visibility-on-windows-11-discreet-features/"><u>Enabling Visibility on Windows 11 Discreet Features</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-steam-sound-fidelity/"><u>Enhancing Windows Steam Sound Fidelity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exciting-news-chatgpt-on-iphone/"><u>Exciting News: ChatGPT on iPhone!</u></a></li>
<li><a href="https://win11.techidaily.com/facing-browser-blockades-top-tactics-to-reach-sites-on-your-system/"><u>Facing Browser Blockades: Top Tactics to Reach Sites on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err0r-code-e1-in-w10w11/"><u>Fixing Err0r: Code E1 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unreachable-friends-list-on-steam-win-11/"><u>Fixing Unreachable Friends List on Steam (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-with-msoffice-on-win11-os/"><u>Getting Started with MSOffice on Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-an-inactive-itunes-on-your-pc/"><u>How to Reactivate an Inactive iTunes on Your PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-xiaomi-14-pro-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Xiaomi 14 Pro</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-achieving-smooth-volume-decreases-using-lumafusion/"><u>In 2024, Achieving Smooth Volume Decreases Using Lumafusion</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Samsung Galaxy S21 FE 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-13-pro-max-drfone-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/install-windows-11-on-mac-with-parallels-step-by-step/"><u>Install Windows 11 on Mac with Parallels Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-flexibility-in-your-windows-environment-with-alomware/"><u>Maximize Flexibility in Your Windows Environment with AlomWare</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-read-only-windows-folder-problems/"><u>Navigating and Resolving Read-Only Windows Folder Problems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-unidentified-hdd-situations/"><u>Navigating Through Unidentified HDD Situations</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-admin-mode-execution-in-windows-console/"><u>Overcoming Failed Admin Mode Execution in Windows Console</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-save-game-errors-civ-5/"><u>Overcoming Save Game Errors, Civ 5</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-recordings-best-free-windows-programs/"><u>Perfect Your Recordings: Best FREE Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-seamlessly-on-windows-1110-systems/"><u>Reinstating Synapse Seamlessly on Windows 11/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-windows-lock-screen-timer-breakage/"><u>Repairing Window's Lock Screen Timer Breakage</u></a></li>
<li><a href="https://win11.techidaily.com/restore-steam-game-symbols-from-nowhere/"><u>Restore Steam Game Symbols From Nowhere</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-screens-overcoming-windows-setup-woes/"><u>Secure Your Screens: Overcoming Windows Setup Woes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-combat-breakpoint-exception-error-in-windows/"><u>Solutions to Combat Breakpoint Exception Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solving-rdp-connectivity-issues-in-win10plus/"><u>Solving RDP Connectivity Issues in Win10+</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-unpopular-version-11-among-users/"><u>Windows Update – Unpopular Version 11 Among Users</u></a></li>
<li><a href="https://win11.techidaily.com/winning-against-access-denied-a-comprehensive-guide-to-5-solutions/"><u>Winning Against 'Access Denied': A Comprehensive Guide to 5 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-games-on-windows-avoid-common-setup-pitfalls/"><u>Xbox Games on Windows: Avoid Common Setup Pitfalls</u></a></li>
</ul></div>
