---
title: Turning Off/On Registry Editor on Windows 11
date: 2024-11-03T23:59:51.585Z
updated: 2024-11-07T23:47:29.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turning Off/On Registry Editor on Windows 11
excerpt: This Article Describes Turning Off/On Registry Editor on Windows 11
keywords: Windows 11 Regedit Tutorial,Enable/Disable Windows Registry,Windows Registry Switch Command,Turning Off Windows Registry,Regedit Usage Guide,Managing Windows Registry Settings,How to Revert Registry Changes
thumbnail: https://thmb.techidaily.com/13632811731c559bc127701456401507af159186a9de22e1aa59a5e7f9127b24.jpg
---

## Turning Off/On Registry Editor on Windows 11

 Although the Registry Editor on Windows makes it easy for administrators to access critical settings and configurations, making incorrect changes to registry files can cause the system to become unstable and compromise its security. This is a common concern among Windows users who share their computers with others.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable or Enable Registry Editor Access via the Group Policy Editor

 The most straightforward way to block access to the Registry Editor on Windows is via the Group Policy Editor. However, it’s important to note that this tool is only available on Windows Pro, Education, and Enterprise editions. If you happen to be using Windows Home, refer to our guide on [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > System**.
4. Double-click the **Prevent access to registry editing tools** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** followed by **OK**.  
![Block Registry Editor Access via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-group-policy-editor.jpg)

 Following this, users will see the “Registry editing has been disabled by your administrator” message when they attempt to access the Registry Editor. If you want to re-enable Registry Editor later, repeat the above steps and set the **Prevent access to registry editing tools** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable or Enable Registry Editor Access via the Registry Editor

 Another way to restrict the Registry Editor access on Windows involves using the Registry Editor itself. Here are the steps you can follow.

1. Click the **search icon** on the taskbar to access the search menu.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when [the User Account Control (UAC) prompt](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies**.
5. Right-click on the **Policies** key and select **New > Key**. Name it **System**.
6. Right-click on the **System** key and select **New > DWORD (32-bit) Value**. Name it **DisableRegistryTools**.
7. Double-click the newly created DWORD, type **1** in the Value data field, and hit **OK**.  
![Block Registry Editor Access via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, the Registry Editor will be disabled on your PC.

 Although you cannot access the Registry Editor to reverse the above changes, it's still possible to re-enable Registry Editor access. For that, you will have to [create and run a REG file](https://www.makeuseof.com/windows-registry-file-guide/). Here’s how you can go about it.

1. Press **Win + S** to open the search menu.
2. Type **notepad** in the search box and press **Enter**.
3. In the notepad window, paste the following command.  
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] "DisableRegistryTools"=dword:00000000`  
![Create Reg File to Enable Registry Editor Access on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-reg-file-to-enable-registry-editor-access-on-windows.jpg)
4. Click the **File** menu and select **Save as**.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select **Desktop** in the **Save as** dialog box.
6. Enter a suitable name followed by ".reg" and hit **Save**. For instance, you could name the file **ReEnableRegistry.reg** or something similar.
7. Use one of the many [ways to open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
8. Type the following command in the console and hit **Enter**. Make sure you replace the **\[username\]** in the following command with your actual username.  
`cd C:\Users\[username]\Desktop`
9. Paste the following command, replace **FileName** with the actual name of the REG file, and press **Enter**.  
`regedit.exe /s FileName.reg`

 Once you run the above command, the Registry Editor will become accessible again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-every-creators-guide-to-youtube-revenue/"><u>[New] 2024 Approved Every Creator's Guide to YouTube Revenue</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-oppo-find-n3-flip-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Oppo Find N3 Flip Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/movavi-f4v-avi/"><u>逐步指南：如何利用 Movavi 轉換器無限制地將 F4V 圖像翻轉成 AVI</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-must-have-components-warning-on-windows-1011/"><u>Eradicating Must-Have Components Warning on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/error-x-demystified-correcting-the-0x80072746-mail-flaw/"><u>Error X Demystified: Correcting the 0X80072746 Mail Flaw</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-motorola-defy-2-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Motorola Defy 2 Phone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-look-at-pc-and-gadget-performance-tips-straight-from-toms-hardware/"><u>Inside Look at PC and Gadget Performance: Tips Straight From Tom's Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/monitors-unleashed-personalized-themes-for-multitaskers-on-win-1011/"><u>Monitors Unleashed: Personalized Themes for Multitaskers on Win 10/11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-audio-artistry-the-step-by-step-process-of-mixing-sounds-for-movie-scenes/"><u>New Audio Artistry The Step-by-Step Process of Mixing Sounds for Movie Scenes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steamuidll-not-found-complication/"><u>Overcoming Steamui.dll Not Found Complication</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/passos-simples-para-transformar-suas-imagens-em-fotografias-classicas-com-o-mais-recente-tecnologia-de-filtragem/"><u>Passos Simples Para Transformar Suas Imagens Em Fotografias Clássicas Com O Mais Recente Tecnologia De Filtragem</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-cloud-issues-in-win-10/"><u>Resolving Steam Cloud Issues in Win 10</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-and-improve-yoga-900s-download-official-windows-10-drivers/"><u>Secure & Improve Yoga 900S: Download Official Windows 10 Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-flickering-screens-on-windows-11/"><u>Troubleshooting Flickering Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-frozen-epic-game-launcher-instances/"><u>Troubleshooting Frozen Epic Game Launcher Instances</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-guide-for-non-responsive-webcams-in-microsoft-teams-on-pc-operating-systems-windows-11107/"><u>Troubleshooting Guide for Non-Responsive Webcams in Microsoft Teams on PC Operating Systems (Windows 11/10/7)</u></a></li>
</ul></div>

