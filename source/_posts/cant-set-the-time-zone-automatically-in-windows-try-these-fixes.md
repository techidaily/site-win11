---
title: Can’t Set the Time Zone Automatically in Windows? Try These Fixes
date: 2025-02-13T17:01:20.803Z
updated: 2025-02-15T19:01:25.294Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can’t Set the Time Zone Automatically in Windows? Try These Fixes
excerpt: This Article Describes Can’t Set the Time Zone Automatically in Windows? Try These Fixes
keywords: Auto Timezone Fix Win,Non-Automatic Timezone,Set Timezone Manually,Timezone Troubleshooting,Customize Windows Time,Update Windows Time Zone,Adjust Time in Windows
thumbnail: https://thmb.techidaily.com/74a4a1093c21fbed5ca77d48b3d1459dd3aa5036bc18134bd1752c7ab7f277b6.jpg
---

## Can’t Set the Time Zone Automatically in Windows? Try These Fixes

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer and check if Windows can set the time zone automatically.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/nhance-audio-quality-get-high-quality-fx-in-2024/"><u>[New] Enhance Audio Quality, Get High-Quality FX, In 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-bridging-the-gap-between-audience-and-action/"><u>2024 Approved Bridging the Gap Between Audience and Action</u></a></li>
<li><a href="https://win-dash.techidaily.com/declining-performance-of-copilot-feature-in-windows-11-whats-going-wrong/"><u>Declining Performance of Copilot Feature in Windows 11: What's Going Wrong?</u></a></li>
<li><a href="https://win11.techidaily.com/echoes-of-ancient-gaming-enhancing-titles-with-retroarchs-artistry/"><u>Echoes of Ancient Gaming: Enhancing Titles with RetroArch's Artistry</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-systray-ui-adding-key-indicators-on-win11/"><u>Enhancing SysTray UI: Adding Key Indicators on Win11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/finding-a-way-to-download-fcp-free-of-charge-for-2024/"><u>Finding a Way to Download FCP Free-Of-Charge for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/icloud-email-update-tutorial-how-to-easily-alter-your-current-icloud-id/"><u>ICloud Email Update Tutorial: How To Easily Alter Your Current iCloud ID</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-windows-11s-biometric-authentication/"><u>Implementing Windows 11'S Biometric Authentication</u></a></li>
<li><a href="https://win11.techidaily.com/mending-your-way-to-responsive-menu-bar-navigation/"><u>Mending Your Way to Responsive Menu Bar Navigation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/movaviwebmp4m4r/"><u>Movaviの使いやすいWeb版MP4からM4Rへの無料変換ツール</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-your-playthroughs-backup-and-repeat-screenshots/"><u>Secure Your Playthroughs: Backup and Repeat Screenshots</u></a></li>
<li><a href="https://win-amazing.techidaily.com/solution-long-term-sequelae-can-include-sensorineural-hearing-loss-developmental-delays-and-neurological-deficits-such-as-cerebral-palsy-or-seizures/"><u>Solution: Long-Term Sequelae Can Include Sensorineural Hearing Loss, Developmental Delays, and Neurological Deficits Such as Cerebral Palsy or Seizures.</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-tasks-on-windows-integrating-an-advanced-run-command-utility/"><u>Streamlining Tasks on Windows: Integrating an Advanced Run Command Utility</u></a></li>
<li><a href="https://win11.techidaily.com/students-delight-the-asus-vivobook-s-15s-smart-mix/"><u>Students' Delight: The ASUS Vivobook S 15'S Smart Mix</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-failure-0xa00f425d-error/"><u>Tackling Windows Camera Failure: 0XA00F425D Error</u></a></li>
<li><a href="https://win11.techidaily.com/the-pathway-to-linux-on-windows-10-enabling-wsl/"><u>The Pathway to Linux on Windows 10: Enabling WSL</u></a></li>
</ul></div>

