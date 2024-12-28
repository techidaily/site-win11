---
title: Tips to Adjust Your Windows Clock Without Regional Defaults
date: 2024-12-23T05:38:15.793Z
updated: 2024-12-28T03:24:04.716Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Adjust Your Windows Clock Without Regional Defaults
excerpt: This Article Describes Tips to Adjust Your Windows Clock Without Regional Defaults
keywords: Set Windows Time Quickly,Custom Windows Date/Time,Disable Region Clock,Change Windows Clock Manually,Adjust Clock Precision,Skip Default Windows Settings,Override Clock Timezone
thumbnail: https://thmb.techidaily.com/23c1e788c86a1fe74b0e576c3c163c7e8cc36d0f77392a611796a9122444764d.jpg
---

## Tips to Adjust Your Windows Clock Without Regional Defaults

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-essential-gif-creation-best-tools-reviewed-and-compared/"><u>[New] 2024 Approved Essential GIF Creation Best Tools Reviewed & Compared</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-boost-iphone-cinematic-experience-essential-film-gear/"><u>[New] Boost iPhone Cinematic Experience Essential Film Gear</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-incorporate-subtitles-for-improved-viewing-wmp-guide-for-2024/"><u>[New] Incorporate Subtitles for Improved Viewing WMP Guide for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/edit-with-precision-mastery-of-photoshops-eraser/"><u>Edit with Precision Mastery of Photoshop's Eraser</u></a></li>
<li><a href="https://win11.techidaily.com/escaping-the-shadows-reclaiming-light-from-darkness/"><u>Escaping the Shadows: Reclaiming Light From Darkness</u></a></li>
<li><a href="https://os-tips.techidaily.com/guide-enabling-icloud-keychain-on-your-pc-a-step-by-step-tutorial/"><u>Guide: Enabling iCloud Keychain on Your PC - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-server-stumbled-microsoft-store-error-in-windows-10-and-11/"><u>How to Fix the “Server Stumbled” Microsoft Store Error in Windows 10 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-samsung-galaxy-z-fold-5-lock-screen-password-by-drfone-android/"><u>How to Reset your Samsung Galaxy Z Fold 5 Lock Screen Password</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-learn-to-harvest-the-richness-of-facebook-live-experiences/"><u>In 2024, , Learn to Harvest the Richness of Facebook Live Experiences</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insight-guide-reviewing-and-removing-windows-history/"><u>Insight Guide: Reviewing & Removing Windows History</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-loadlibrary-error-87-in-windows/"><u>Resolving LoadLibrary Error 87 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-the-taskbar-in-windows-11-top-6-suggested-enhancements/"><u>Revolutionizing the Taskbar in Windows 11: Top 6 Suggested Enhancements</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/screen-recorder-showdown-features-and-prices-compared-for-2024/"><u>Screen Recorder Showdown Features and Prices Compared for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-your-watching-youtube-performance-in-chrome/"><u>Turbocharge Your Watching: YouTube Performance in Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/unfreeze-opera-downloads-tips-for-windows-users/"><u>Unfreeze Opera Downloads: Tips for Windows Users</u></a></li>
</ul></div>

