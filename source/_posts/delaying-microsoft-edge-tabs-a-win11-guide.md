---
title: "Delaying Microsoft Edge Tabs: A Win11 Guide"
date: 2025-01-31T17:27:20.413Z
updated: 2025-02-03T21:49:51.837Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Delaying Microsoft Edge Tabs: A Win11 Guide"
excerpt: "This Article Describes Delaying Microsoft Edge Tabs: A Win11 Guide"
keywords: Win11 Browser Optimization,Delay Tabs Edges,Microsoft Edge Tweaks,Windows 11 Performance,Tab Management Win11,Speed Up Edge in Win11,Manage Browsing Windows
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Delaying Microsoft Edge Tabs: A Win11 Guide

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.

## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-explore-mp4-recording-tools-today/"><u>[New] 2024 Approved Explore MP4 Recording Tools Today</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-saving-instagrams-a-step-by-step-approach-for-windowsmacos-users/"><u>[New] In 2024, Saving Instagrams A Step-by-Step Approach for Windows/macOS Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lens-legends-battle-sj6-versus-xiaomis-yi-4k-visionary/"><u>[New] Lens Legends Battle SJ6 Versus Xiaomi's Yi 4K Visionary</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1716069754229-updated-2024-approved-employing-inbuilt-screen-recording-tools-on-mate-p-models-p20-p10/"><u>[Updated] 2024 Approved Employing Inbuilt Screen Recording Tools on Mate, P Models (P20, P10).</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-captivating-clips-transforming-footage-vertically-in-final-cut-x/"><u>[Updated] In 2024, Captivating Clips Transforming Footage Vertically in Final Cut X</u></a></li>
<li><a href="https://video-capture.techidaily.com/1726029847038-dvdusb/"><u>「対面レンダリングとの比較: DVDからUSBへデータ移行の新手法 - 無料ソフト推薦」</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-viral-videos-how-to-excel-in-youtubers-music-reactions-for-2024/"><u>Crafting Viral Videos How to Excel in Youtubers' Music Reactions for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-stop-your-bluetooth-headphones-from-jittery-sounds-on-windows-1011/"><u>How to Stop Your Bluetooth Headphones From Jittery Sounds on Windows 10/11?</u></a></li>
<li><a href="https://fox-links.techidaily.com/instantly-fashion-company-symbols-with-open-source-tools-for-2024/"><u>Instantly Fashion Company Symbols with Open-Source Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/realignment-of-data-win11-hdd-optimization-techniques/"><u>Realignment of Data: Win11 HDD Optimization Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functionality-to-windows-photos-with-registering-packages/"><u>Reinstating Functionality to Windows Photos with Registering Packages</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-and-solving-winerror-0x80071a90-in-windows/"><u>Simplifying & Solving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-apps-to-help-you-write-better-on-a-windows-pc/"><u>The 5 Best Apps to Help You Write Better on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/winning-task-managers-for-windows-10-and-11-users/"><u>Winning Task Managers for Windows 10 & 11 Users</u></a></li>
</ul></div>

