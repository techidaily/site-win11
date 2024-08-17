---
title: Overcoming Windows' Non-Automatic Timezone Change
date: 2024-08-15T23:42:59.219Z
updated: 2024-08-16T23:42:59.219Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows' Non-Automatic Timezone Change
excerpt: This Article Describes Overcoming Windows' Non-Automatic Timezone Change
keywords: Fix Automatic TZ Switch,Stop TZ Change WOI,Prevent Unwanted TZ Update,Control Windows Time Zone,Disable Automatic TZ Shift,Secure Windows Time Setting,Halt Non-Automatic TZ Alteration
thumbnail: https://thmb.techidaily.com/f78d1d150df9704e5a6635f2d8f1d9b65ffaf1875700edcd569333cc9eed6a06.jpg
---

## Overcoming Windows' Non-Automatic Timezone Change

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)

 Now restart your computer and check if Windows can set the time zone automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Set the Windows Time Service to Automatic

 If the location services are already enabled, but Windows still can't detect the time zone, the problem may be related to the Windows Time Service. This background service keeps your system clock synchronized with time servers.

 Windows won't detect the time zone if the service is not running. To fix this issue, set Windows Time Service to Automatic.

 Here's how to do that:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **services.msc** in the text box and press **Enter**.
3. Scroll down in the Services window and locate the **Windows Time** service.
4. Right-click the service and select **Properties**.
5. In the Properties window, set the **Startup type** to **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
6. Now check the **Service status**. If it reads **Stopped**, click the **Start** button to start the service.
7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Tweak the Registry Editor

 If Windows still fails to detect the time zone or the "Set time zone automatically" option is still grayed out, you may need to tweak your registry. This is a more technical solution and requires registry knowledge. If you're not good at registry editing, skip this step or ask a professional for help.

 Follow these steps to make the changes:

 Modifying the registry incorrectly may cause serious problems. Before making any changes, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **regedit** in the search bar and press **Enter**.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following directory.  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\tzautoupdate`
5. In the right pane, double-click the **Start** (DWORD) value.  
![Modify Registry to change the Set time zone automatically setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-the-set-time-zone-automatically-setting.jpg)
6. When the Edit DWORD Value window pops up, set the Value data to **3** and click **OK**.
7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the Group Policy Editor

 If you're comfortable with registry editing, use the Group Policy Editor instead. However, the tool is only compatible with Windows Pro and Enterprise editions. If you're not a Pro user, [activate the Group Policy for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Right-click on Start and select **Run**.
2. Type **gpedit.msc** in the text field and click **OK**. The Local Group Policy Editor window will open.
3. On the left navigation panel, browse to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Location and Sensors > Windows Location Provider`
4. Go to the right pane and double-click on **Turn off Windows Location Provider**.  
![Turn off Windows Location Provider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/turn-off-windows-location-provider.jpg)
5. In the pop-up window, check the **Not Configured** option.
6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

## 6\. Reset the Windows Time Service

 This problem may also occur if the Windows Time Service or time synchronization settings become corrupted. In that case, reset the service to its default settings and see if that helps. Here's how to do it:

1. Click on Start and type **cmd** in the search box.
2. Press **Ctrl + Shift + Enter** on your keyboard simultaneously. This opens the Command Prompt in administrator mode.
3. If the pop-up window appears, click **Yes** to grant permission.
4. In the Command Prompt window, type net **stop w32time** and press **Enter**. Running this command will stop the Windows Time Service.
5. Now, type **w32tm /unregister** in the Command Prompt window and hit **Enter**. This unregisters the service.
6. Next, type **w32tm /register** and press **Enter**. This will re-register the Windows Time Service.
7. After that, type net **start w32time** to restart the Windows Time Service.

 Once done, close the Command Prompt and restart your computer to check if it solves the problem.

## 7\. Try Some Generic Windows Fixes

 There are also generic fixes you can try:

1. **Run the System File Checker tool:**[running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) scans for corrupted system files and replaces them if necessary.
2. **Perform a Clean Boot:** If that didn't work, [try a Windows clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This determines if third-party applications interfere with Windows Time Service.
3. **Update Windows:** Finally, [update Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to ensure you have all the latest fixes and security patches.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Windows Can Now Automatically Set the Time Zone

 We hope the article helped you resolve timing issues on your Windows computer. It may occur due to missing or corrupted system files or incorrect time zone settings. Make sure to try these solutions and perform a System Restore if the problem persists.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-5-simple-steps-to-record-your-youtube-streams-for-2024/"><u>[New] 5 Simple Steps to Record Your YouTube Streams for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-concept-to-completion-essential-design-actions/"><u>[New] From Concept to Completion  Essential Design Actions</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-visionary-logo-tactics-elevating-your-podcasts-look-for-2024/"><u>[New] Visionary Logo Tactics  Elevating Your Podcast's Look for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-9-key-approaches-to-free-webinar-archiving/"><u>[Updated] 2024 Approved  9 Key Approaches to Free Webinar Archiving</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-strategies-to-alleviate-vr-motion-woes/"><u>[Updated] 2024 Approved  Strategies to Alleviate VR Motion Woes</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-creating-a-memorable-and-unique-moniker-for-your-filmora-content/"><u>[Updated] Creating a Memorable and Unique Moniker for Your Filmora Content</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-ensuring-thumbnails-show-shorts-video-troubleshooting-for-2024/"><u>[Updated] Ensuring Thumbnails Show  Shorts Video Troubleshooting for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-10-free-legal-chants-and-sounds-for-meditation-practice/"><u>2024 Approved  10 Free Legal Chants and Sounds for Meditation Practice</u></a></li>
<li><a href="https://win11.techidaily.com/4-easy-ways-to-create-a-new-folder-in-windows-11/"><u>4 Easy Ways to Create a New Folder in Windows 11</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-vivo-s18e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/a-fourfold-approach-to-ai-governance-by-state-authorities/"><u>A Fourfold Approach to AI Governance by State Authorities</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-windows-11-pitfalls/"><u>Addressing Common Windows 11 Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-saturated-capacity-in-chatgpt/"><u>Alleviating Saturated Capacity in ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-app-migration-tips-to-fix-windows-task-manager-positions/"><u>Avoid App Migration: Tips to Fix Windows Task Manager Positions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-correcting-not-working-error-in-windows/"><u>Breaking Down and Correcting 'Not Working' Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-read-only-folders-without-compromise-in-windows/"><u>Correcting Read-Only Folders Without Compromise in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/curb-the-constant-reopening-of-windows-file-explorer/"><u>Curb the Constant Reopening of Windows' File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-the-summary-size-of-your-pics/"><u>Customizing the Summary Size of Your Pics</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-windows-restoration-options/"><u>Dive Deep Into Windows Restoration Options</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-xfffeeee-error-on-your-office-printer/"><u>Eliminating XFFFEEEE Error on Your Office Printer</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-add-music-to-facebook-videos-for-2024/"><u>How to Add Music to Facebook Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-adjust-metric-tracking-features-for-a-wi-fi-network-in-windows-11/"><u>How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80072f30-on-windows/"><u>How to Fix the Microsoft Store Error 0X80072F30 on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-windows-11s-system-settings-problems/"><u>How to Mend Windows 11'S System Settings Problems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-upscale-your-old-videos-with-madvr-for-windows/"><u>How to Upscale Your Old Videos With MadVR for Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-from-iphone-6s-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock From iPhone 6s?</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-indefinite-deletion-settings-in-windows-desktop-bin/"><u>Initiating Indefinite Deletion Settings in Windows Desktop Bin</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-mouse-lagging-in-star-wars-battlefront-2-on-windows-try-these-8-fixes/"><u>Is Your Mouse Lagging in Star Wars Battlefront 2 on Windows? Try These 8 Fixes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/mac-snapshot-strategies-revealed-the-top-5-innovative-approaches-for-2024/"><u>Mac Snapshot Strategies Revealed  The Top 5 Innovative Approaches for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719322242538-mastering-printer-troubles-reactivating-missing-wwinplusp-on-windows/"><u>Mastering Printer Troubles: Reactivating Missing WWin+P on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-complex-windows-11-install-issues/"><u>Navigating Through Complex Windows 11 Install Issues</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-pomodoro-strategies-best-windows-timer-selections/"><u>Optimal Pomodoro Strategies - Best Windows Timer Selections</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-vscode-errors-in-latest-windows-update/"><u>Preventing VSCode Errors in Latest Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-normalcy-in-corporate-governed-chromium-and-microsoft-edge-browsing/"><u>Regaining Normalcy in Corporate-Governed Chromium & Microsoft Edge Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-your-pcs-dead-hub-a-windows-fix-guide/"><u>Resurrecting Your PC's Dead Hub: A Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/security-essentials-pre-upgrade-activation-of-tpm-and-secure-boot/"><u>Security Essentials: Pre-Upgrade Activation of TPM & Secure Boot</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-a-stopped-netflix-window-program/"><u>Solutions for a Stopped Netflix Window Program</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-11-fs-data-loss-and-corruption/"><u>Solutions for Windows 11 FS Data Loss and Corruption</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-microsoft-offices-0x80041015-problematic-error/"><u>Solutions to Microsoft Office's 0X80041015 Problematic Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-write-operation-failures-in-winos/"><u>Steps to Rectify Write Operation Failures in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-the-application-was-unable-to-start-xc000003e-on-win11-and-11/"><u>Strategies to Address The Application Was Unable to Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-deletion-with-windows-context-add-ons/"><u>Streamlining Deletion with Windows Context Add-Ons</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-game-access-issues-windows-and-xbox-edition/"><u>Tackling Game Access Issues - Windows and Xbox Edition</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-windows-11-workspace-in-minutes/"><u>Tidy Up Windows 11 Workspace in Minutes</u></a></li>
<li><a href="https://article-posts.techidaily.com/transform-your-photos-canons-cost-effective-color-tools-for-2024/"><u>Transform Your Photos  Canon's Cost-Effective Color Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-look-of-windows-11s-basic-text-editor/"><u>Transforming the Look of Windows 11'S Basic Text Editor</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-techniques-for-xlive-dll-file-not-found-problems/"><u>Troubleshooting Techniques for Xlive DLL File Not Found Problems</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-0xca00a009-in-microsoft-windows/"><u>Unraveling Error 0xCA00A009 in Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-w11s-0x8004def5-onedrive-malfunction/"><u>Unraveling the Mystery of W11's 0X8004def5 OneDrive Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-windows-canary-channel-explained/"><u>Unraveling the Mystery: Windows Canary Channel Explained</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-difference-between-chkdsk-sfc-and-dism-in-windows/"><u>What Is the Difference Between CHKDSK, SFC, and DISM in Windows?</u></a></li>
</ul></div>
