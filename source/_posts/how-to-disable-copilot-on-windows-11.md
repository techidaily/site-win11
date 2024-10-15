---
title: How to Disable Copilot on Windows 11
date: 2024-10-14T18:17:32.224Z
updated: 2024-10-15T16:42:48.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable Copilot on Windows 11
excerpt: This Article Describes How to Disable Copilot on Windows 11
keywords: Turn Off AI Assistant,Stop Windows Copilot,Disable Windows Copilot,Remove Copilot Feature,Eliminate Copilot on Win 11,Deactivate Microsoft Copilot,Stop AI Suggestions in Windows
thumbnail: https://thmb.techidaily.com/0fc33f78a6ac7efb4d7528f193803031f45ec9e70c0aa03967d621fbfa5bc6d6.jpg
---

## How to Disable Copilot on Windows 11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080342/19272" target="_top" id="2080342">
  <img src="//a.impactradius-go.com/display-ad/19272-2080342" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080342/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144274/7443" target="_top" id="2144274">
  <img src="//a.impactradius-go.com/display-ad/7443-2144274" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144274/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-leapfrogging-into-digital-marketing-establishing-a-yt-channel-on-mobile/"><u>[New] 2024 Approved Leapfrogging Into Digital Marketing Establishing a YT Channel on Mobile</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-the-ultimate-list-best-7-camcorders-for-waterproof-use/"><u>[Updated] 2024 Approved The Ultimate List Best 7 Camcorders for Waterproof Use</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-saga-selection-the-top-10-best-action-adventure-games/"><u>[Updated] Saga Selection The Top 10 Best Action-Adventure Games</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-periscope-explained-costs-accessibility-and-registration-guide/"><u>2024 Approved Periscope Explained Costs, Accessibility & Registration Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/discovery-at-work-a-one-man-review-on-3dr-printers/"><u>Discovery at Work A One-Man Review on '3DR' Printers</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-file-sorting-utilizing-w11s-copy-and-move/"><u>Effortless File Sorting: Utilizing W11’s Copy and Move</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visuals-and-performance-fps-upgrade-techniques/"><u>Enhancing Visuals & Performance: FPS Upgrade Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-audio-on-your-hp-laptop-solutions-for-windows-10-users/"><u>Fixing No Audio on Your HP Laptop - Solutions for Windows 10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-disk-defragmenter-not-working-in-windows/"><u>How to Fix the Disk Defragmenter Not Working in Windows</u></a></li>
<li><a href="https://os-tips.techidaily.com/kid-friendly-tunes-repurposing-older-cellphones-as-fun-music-and-podcast-hubs/"><u>Kid-Friendly Tunes: Repurposing Older Cellphones as Fun Music & Podcast Hubs</u></a></li>
<li><a href="https://win11.techidaily.com/next-level-art-software-alternatives-to-procreates-win-version/"><u>Next-Level Art Software: Alternatives To Procreate's Win Version</u></a></li>
<li><a href="https://win-hot.techidaily.com/rehabilitasi-iklan-langsung-di-sumber-daya-hr-dalam-windows-11-10-8-dan-7/"><u>Rehabilitasi Iklan Langsung Di Sumber Daya HR Dalam Windows 11, 10, 8 Dan 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/simplifying-smartphone-browsing-discover-how-to-use-gestures-for-google-image-and-visual-searches/"><u>Simplifying Smartphone Browsing: Discover How to Use Gestures for Google Image and Visual Searches</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-clearing-dark-screen-on-steam-os/"><u>Strategies for Clearing Dark Screen on Steam OS</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-monitoring-with-interactive-windows-panels/"><u>Streamline System Monitoring with Interactive Windows Panels</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-a-complete-guide-to-translate-video-with-google/"><u>Updated 2024 Approved A Complete Guide To Translate Video With Google</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    