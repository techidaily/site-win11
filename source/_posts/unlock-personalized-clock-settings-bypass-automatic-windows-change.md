---
title: Unlock Personalized Clock Settings, Bypass Automatic Windows Change
date: 2025-01-29T21:28:58.434Z
updated: 2025-02-04T07:28:43.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Personalized Clock Settings, Bypass Automatic Windows Change
excerpt: This Article Describes Unlock Personalized Clock Settings, Bypass Automatic Windows Change
keywords: Custom Clock Controls,Bypass Window Time,Manual Clock Edit,Unlocked Clock Settings,Personalized Windows Hours,Avoid Auto Time Change,Customize Windows Timer
thumbnail: https://thmb.techidaily.com/0ab25ce0bb8d4ab2078e845cda986fa9a30d3de551640bc5deeb7f8730f9ba76.jpg
---

## Unlock Personalized Clock Settings, Bypass Automatic Windows Change

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 Now restart your computer and check if Windows can set the time zone automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/new-enhancing-gameplay-with-switch-pro-a-compreran-guide-for-steam-gamers/"><u>[New] Enhancing Gameplay with Switch Pro A Compreran Guide for Steam Gamers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-essential-blueprint-for-home-based-podcasting/"><u>[New] The Essential Blueprint for Home-Based Podcasting</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-seamless-integration-of-fb-video-on-tv-screens/"><u>[Updated] In 2024, Seamless Integration of Fb Video on TV Screens</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-strategic-locations-to-upgrade-youtube-content-for-2024/"><u>[Updated] Strategic Locations to Upgrade YouTube Content for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-five-protocols-for-documenting-youtube-live-broadcasts-for-2024/"><u>[Updated] Top Five Protocols for Documenting YouTube LIVE Broadcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/convert-and-save-the-quick-guide-from-esd-to-iso-format-on-pcs/"><u>Convert and Save: The Quick Guide From ESD to ISO Format on PCs</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exceptional-endurance-a-moto-g-power-assessment-stellar-battery-performance-meets-style/"><u>Exceptional Endurance: A Moto G Power Assessment - Stellar Battery Performance Meets Style</u></a></li>
<li><a href="https://win11.techidaily.com/fast-tracking-your-path-to-epic-game-access/"><u>Fast Tracking Your Path to Epic Game Access</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-microsoft-store-error-on-win11-with-code-0x80073cf3/"><u>Fixing the Microsoft Store Error on Win11 with Code 0X80073cf3</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11s-0x8007045d-blue-screen-issue/"><u>Fixing Windows 11'S 0X8007045D Blue Screen Issue</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/immerse-in-gaming-bliss-discover-the-ultimate-philips-49-curved-oled-monitor-experience/"><u>Immerse in Gaming Bliss: Discover the Ultimate Philips 49 Curved OLED Monitor Experience</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-realme-gt-5-pro-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Realme GT 5 Pro Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-move-custom-ringtones-from-apple-iphone-15-plus-to-android-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Move Custom Ringtones from Apple iPhone 15 Plus to Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-disabled-windows-menu-items/"><u>Methods to Rectify Disabled Windows Menu Items</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-svchostexes-excessive-cpu-drain-in-windows-10-comprehensive-fixes/"><u>Resolving svchost.exe's Excessive CPU Drain in Windows 10 - Comprehensive Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reduce-cpu-load-from-dropbox-applications/"><u>Techniques to Reduce CPU Load From Dropbox Applications</u></a></li>
<li><a href="https://win11.techidaily.com/timely-updates-pick-the-superior-time-screen-savers/"><u>Timely Updates: Pick the Superior Time Screen Savers</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-inactive-shadow-copy-on-pc/"><u>Troubleshooting Inactive Shadow Copy on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-potential-analyzing-windows-reliable-tools/"><u>Unleashing Potential: Analyzing Windows' Reliable Tools</u></a></li>
</ul></div>

