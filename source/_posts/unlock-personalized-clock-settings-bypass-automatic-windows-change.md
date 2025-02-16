---
title: Unlock Personalized Clock Settings, Bypass Automatic Windows Change
date: 2025-02-11T21:50:50.061Z
updated: 2025-02-16T05:05:41.409Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-10-best-live-streaming-services-for-church-you-should-know/"><u>[New] 2024 Approved 10 Best Live Streaming Services for Church You Should Know</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-ultimate-roadmap-to-crafting-memorable-tiktok-videos/"><u>[Updated] 2024 Approved The Ultimate Roadmap to Crafting Memorable TikTok Videos</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-boost-online-presence-innovative-youtube-channel-names-for-2024/"><u>[Updated] Boost Online Presence Innovative YouTube Channel Names for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-parrots-in-flight-a-deep-dive-into-bebops-essence/"><u>[Updated] Parrots in Flight A Deep Dive Into Bebop's Essence</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-ultimate-guide-to-using-obs-in-android-for-2024/"><u>[Updated] The Ultimate Guide to Using OBS in Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/de-clog-your-desktop-with-order/"><u>De-Clog Your Desktop with Order</u></a></li>
<li><a href="https://win11.techidaily.com/easing-your-way-through-typical-anydesk-troubles-on-windows-os/"><u>Easing Your Way Through Typical AnyDesk Troubles on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-errant-apps-resolving-0xc000003e-on-windows-11-and-11/"><u>Fixing Errant Apps: Resolving 0xC000003E on Windows 11 & 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-oneplus-11-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change OnePlus 11 5G Lock Screen Password?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-poco-m6-pro-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Poco M6 Pro 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-call-of-duty-vanguard-bugs-how-the-pc-edition-has-improved-by-2024/"><u>Overcoming Call of Duty Vanguard Bugs: How the PC Edition Has Improved by 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overriding-defenders-firewall-restrictions-in-win11/"><u>Overriding Defender's Firewall Restrictions in Win11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-lava-blaze-curve-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Lava Blaze Curve 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722991745791-rainbow-six-siege-connections-woes-heres-how-you-can-repair-them/"><u>Rainbow Six Siege Connections Woes? Here's How You Can Repair Them!</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-smoothness-in-windows-hellos-fingerprint-functionality/"><u>Reclaiming Smoothness in Windows Hello's Fingerprint Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-non-operational-discord-widget-in-your-os/"><u>Reviving a Non-Operational Discord Widget in Your OS</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-in-store-file-transfers-on-microsoft-devices/"><u>Revolutionize Your In-Store File Transfers on Microsoft Devices</u></a></li>
<li><a href="https://hardware-help.techidaily.com/secure-your-logitech-m525-mouse-experience-with-official-drivers-and-downloads/"><u>Secure Your Logitech M525 Mouse Experience with Official Drivers & Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/switching-off-geforce-visual-enhancements-on-pc/"><u>Switching Off GeForce Visual Enhancements on PC</u></a></li>
</ul></div>

