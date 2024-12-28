---
title: "Enhance Efficiency: Reducing Memory/CPU Load in Windows 10"
date: 2024-12-20T17:41:34.748Z
updated: 2024-12-27T23:24:53.585Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhance Efficiency: Reducing Memory/CPU Load in Windows 10"
excerpt: "This Article Describes Enhance Efficiency: Reducing Memory/CPU Load in Windows 10"
keywords: WinEfficiency Tips,LowMemoryWindows,CPULoadReduction,OptimizePerformance,EfficientPCTech,WindowsOptimization,ResourceManagementWin10
thumbnail: https://thmb.techidaily.com/ba4d76a3836c79aa2d1ffbc408b14921a58fa2b19ac7a8b8eb3ad2286e02cfeb.jpg
---

## Enhance Efficiency: Reducing Memory/CPU Load in Windows 10

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to[manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to[Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can[disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to[perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to[enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.

5. Close the Registry Editor and restart your computer to apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.

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
<li><a href="https://fox-helps.techidaily.com/new-swiftly-switch-srt-and-text-files-with-this-easy-guide-for-2024/"><u>[New] Swiftly Switch SRT and Text Files with This Easy Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-top-4-marvel-intro-makers-online/"><u>[New] Top 4 Marvel Intro Makers Online</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-direct-music-upload-top-tools-for-turning-spotify-into-youtube-listings/"><u>[Updated] Direct Music Upload Top Tools for Turning Spotify Into YouTube Listings</u></a></li>
<li><a href="https://fox-direct.techidaily.com/a-step-by-step-guide-through-the-landscape-of-srt/"><u>A Step-by-Step Guide Through the Landscape of SRT</u></a></li>
<li><a href="https://change-location.techidaily.com/additional-tips-about-sinnoh-stone-for-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-windows-hello-biometric-lock-in-windows-11/"><u>How to Utilize Windows Hello Biometric Lock in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oneplus-12-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from OnePlus 12 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-amd-chipset-software-for-windows-117881-free-download-links/"><u>Latest AMD Chipset Software for Windows 11/7/8/8.1 - Free Download Links</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-system-efficiency-through-cpu-settings/"><u>Maximizing System Efficiency Through CPU Settings</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-failure-windows-error-0x8007045d/"><u>Overcoming System Failure - Windows Error 0X8007045D</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/professional-animal-photography-and-backgrounds-for-pcmac-quality-wallpapers-from-yl-computing-studio/"><u>Professional Animal Photography & Backgrounds for PC/MAC - Quality Wallpapers From YL Computing Studio</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-path-errors-on-windows-810-systems/"><u>Remedying PATH Errors on Windows 8/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-selecthighlight-problems-in-windows-pdfs/"><u>Solutions for Select/Highlight Problems in Windows PDFs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-prevent-csgo-launch-issues-on-windows-11/"><u>Strategies to Prevent CS:GO Launch Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-online-journey-with-gesture-controls-in-ms-edge-win-11-edition/"><u>Streamline Your Online Journey with Gesture Controls in MS Edge, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-perfected-notes-on-obsidian-canvas/"><u>The Path to Perfected Notes on Obsidian Canvas</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-picks-for-phone-based-asmr-enthusiasts-for-2024/"><u>Top Picks for Phone-Based ASMR Enthusiasts for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-success-how-to-stop-escape-from-tarkov-from-freezing-and-crashing-on-your-desktop/"><u>Troubleshooting Success! How to Stop 'Escape From Tarkov' From Freezing and Crashing on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/windows-networks-decoded-arp-cache-understanding/"><u>Windows Networks Decoded: ARP Cache Understanding</u></a></li>
</ul></div>

