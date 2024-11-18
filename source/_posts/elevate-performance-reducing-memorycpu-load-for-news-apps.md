---
title: "Elevate Performance: Reducing Memory/CPU Load for News Apps"
date: 2024-11-14T02:59:12.116Z
updated: 2024-11-17T18:27:33.097Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevate Performance: Reducing Memory/CPU Load for News Apps"
excerpt: "This Article Describes Elevate Performance: Reducing Memory/CPU Load for News Apps"
keywords: News App Optimization,Low Latency News Viewing,Efficient News Display,High-Performance News,Reduced Memory Usage News,CPU Light News Experience,Performance-Boosted News Apps
thumbnail: https://thmb.techidaily.com/dccb34317888d85bf5b03242f6ff077822b2720dd93141b57f6f0f2fbe555fd1.jpg
---

## Elevate Performance: Reducing Memory/CPU Load for News Apps

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to[manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to[Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902319/19272" target="_top" id="1902319">
  <img src="//a.impactradius-go.com/display-ad/19272-1902319" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902319/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-how-to-edit-vertical-videos-for-instagram-in-final-cut-pro-x/"><u>[New] 2024 Approved How to Edit Vertical Videos for Instagram in Final Cut Pro X?</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-editors-deep-dive-into-pixelcut-pro-latest-features-in-review/"><u>[New] In 2024, Editor's Deep Dive Into PixelCut Pro - Latest Features in Review</u></a></li>
<li><a href="https://win-data.techidaily.com/access-vmwares-fusion-and-workstation-pro-at-no-cost-for-individual-users-a-comprehensive-guide/"><u>Access VMware's Fusion & Workstation Pro at No Cost for Individual Users: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-boost-feature/"><u>Diminish Windows Volume Boost Feature</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-resolving-disk-read-failures-on-pcs/"><u>Fast Track: Resolving Disk Read Failures on PCs</u></a></li>
<li><a href="https://driver-download.techidaily.com/free-download-updated-hp-laserjet-p1007-printer-drivers-and-software-upgrades/"><u>Free Download: Updated HP LaserJet P1007 Printer Drivers & Software Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-vmi-feature-in-windows-11-builds/"><u>How to Disable VMI Feature in Windows 11 Builds</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-14-plusipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock on Apple iPhone 14 Plus/iPad/iPod</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-spotlight-on-distinguished-videographer-reputations/"><u>In 2024, Spotlight on Distinguished Videographer Reputations</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-ways-to-clear-win11s-domain-nameservers/"><u>Innovative Ways to Clear Win11's Domain Nameservers</u></a></li>
<li><a href="https://some-tips.techidaily.com/instant-slideshow-creator-download-now/"><u>Instant Slideshow Creator - Download Now!</u></a></li>
<li><a href="https://win11.techidaily.com/key-management-for-customized-windows-tasks/"><u>Key Management for Customized Windows Tasks</u></a></li>
<li><a href="https://extra-support.techidaily.com/navigate-like-a-pro-with-top-windows-10-hacks-for-2024/"><u>Navigate Like a Pro with Top WINDOWS 10 Hacks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-smooth-sync-route-with-ms-to-do-app/"><u>Navigating a Smooth Sync Route with MS To-Do App</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-odds-5-ways-to-end-dark-screen-anomaly/"><u>Overcoming Odds: 5 Ways to End Dark Screen Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-to-mend-win-10win11-rd-errors/"><u>Tips and Tricks to Mend Win 10/Win11 RD Errors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-dark-screen-fix-mouse-appears/"><u>Win11 Dark Screen Fix: Mouse Appears</u></a></li>
</ul></div>

