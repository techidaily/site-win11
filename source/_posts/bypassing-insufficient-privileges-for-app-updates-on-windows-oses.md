---
title: Bypassing Insufficient Privileges for App Updates on Windows OSes
date: 2025-01-29T16:39:36.979Z
updated: 2025-02-03T16:19:19.829Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Insufficient Privileges for App Updates on Windows OSes
excerpt: This Article Describes Bypassing Insufficient Privileges for App Updates on Windows OSes
keywords: Update Windows Access,Privilege Bypass Tricks,WinOS Permission Issues,Security Patching Guide,User Rights Management,App Upgrade Override,OS Update Protocols
thumbnail: https://thmb.techidaily.com/b7ac3fecaf39cbf4ad53ade68b5607328fb5fc5fabf85fb01691cb6e94c786a0.jpg
---

## Bypassing Insufficient Privileges for App Updates on Windows OSes

 Some users have reported an uninstall issue on Microsoft’s forum with an error message that says, “You do not have sufficient access to uninstall.” That error message pops up when users try to uninstall certain software in Windows 11/10\. As a result, users can’t uninstall whatever software packages that error occurs for.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

## 1\. Enable the Windows Admin Account

 First, make sure you’re utilizing an admin account. You can [activate a built-in Windows admin account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) via the Command Prompt. Then log in to that built-in admin account and try uninstalling the software from there.

 Alternatively, you can switch a current standard user account to an admin one. Check out this guide to [changing Windows account types](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) for full instructions about how to do so.

## 2\. Run the Affected Software’s Uninstaller File as an Administrator

 Also, run the software’s uninstaller file as an administrator. The software’s installation directory will include its uninstaller file. Right-click that file to select a **Run as administrator** context menu option.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Troubleshoot With the Program Install and Uninstall Troubleshooter

 Windows doesn’t include any troubleshooter for fixing uninstallation issues. However, there is a Microsoft Program Install and Uninstall troubleshooter that might be useful for fixing the “You do not have sufficient access to uninstall” error. This is how you can run the Program Install and Uninstall troubleshooter:

1. Bring up the troubleshooter's [Microsoft download page](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d).
2. Then click on the **Download** troubleshooter button.
3. Double-click on the **MicrosoftProgram\_Install\_and\_Uninstall.meta.diagcab** troubleshooter file.  
![The Program Install and Uninstall troubleshooter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-install-and-uninstall-troubleshooter.jpg)
4. Click on **Next** \> **Uninstalling** to bring up a program list.  
![The Uninstalling option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstalling-option.jpg)
5. Then select the program you can’t uninstall and select **Next**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Program Install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-list.jpg)

## 4\. Turn Off User Account Control

 The “You do not have sufficient access to uninstall” error can sometimes arise because User Account Control is set to high. So, try temporarily turning UAC off before uninstalling the affected software. Our guide on [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off UAC.

![The User Account Control settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control.jpg)

## 5\. Set Full Control Permissions for the Software’s Installation Folder

 You might need to fix this error because the full user control permission setting isn’t set for the software installation’s folder. So, check the control permission settings for the software installation folder. This is how you can set full control permission for a folder:

1. Open the folder that contains the installation directory of the affected software.
2. Right-click on the installation folder and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option3.jpg)
3. Click **Edit** on the **Security** tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select your user account name.
5. Click the **Full control** checkbox to select that setting if it’s not already.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-control-window.jpg)
6. Then select **Apply** \> **OK** on the folder’s permissions window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Select **OK** to exit the properties window.
8. Repeat the above instructions for the program’s EXE (application) file.

## 6\. Uninstall the Software With an UninstallString Value

 Some users have resolved this error by uninstalling the affected software packages with their UninstallString values. You can do that by copying and pasting the UninstallString value for a program from the registry into the Command Prompt. These are the steps for uninstalling software with an UninstallString value:

1. Open Windows Search with **Win + S**.
2. Type in **regedit** to find the Registry Editor.
3. Select Registry Editor to launch that app.
4. Next, input this location into Registry Editor’s address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall`
5. Click on the subkeys in the **Uninstall** key to view the **DisplayName** strings for them.

1. Select the key for the software you can’t install by identifying it with the **DisplayName** string.  
![DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/display-name.jpg)
2. Double-click on the key's **UninstallString** string.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Copy the text in the **Value data** box by selecting it and pressing **Ctrl** \+ **C**.  
![The Edit String window for the UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window3.jpg)
4. Open Command Prompt as an admin (See [how to open Command Prompt with admin permissions](https://www.makeuseof.com/windows-run-command-prompt-admin/)).
5. Click inside the Command Prompt and press **Ctrl** \+ **V** to paste in the string.  
![An uninstall command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/undostring-command.jpg)
6. Press **Enter** to run the command and remove the software.

 Note that the above registry string is for 64-bit software. To find the strings for 32-bit software, you’ll need to go to this registry path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`

## 7\. Try Uninstalling the Software With a Third-Party Uninstaller Tool

 Third-party uninstaller tools have helped some users fix the “do not have sufficient access to uninstall” error. The [best third-party uninstaller tools](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) are superior to Windows’ Programs and Features applet for removing software. So, try uninstalling the software with a freely available utility like Revo Uninstaller, IObit Uninstaller, or Advanced Uninstaller Pro. This is how you can do that with IObit Uninstaller:

1. Open this [IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) download page.
2. Select **Free Download** to save IObit Uninstaller’s setup wizard within a folder.
3. Bring up the directory containing the **iobituninstaller.exe** file.
4. Double-click the **iobituninstaller.exe** file and click **Install** in the setup wizard.
5. Open IObit Uninstaller and select the **All programs** tab.  
![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-iobit-uninstaller-software.jpg)
6. Select the program and click **Uninstall**.
7. Click on the checkbox labeled **Automatically remove residual files**.
8. Select **Uninstall** to remove the software.  
![The Uninstall button in IObit Uninstaller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Uninstall the Software Within Safe Mode

 Safe mode is Windows troubleshooting mode in which only essential drivers and services run. Uninstalling affected software in that mode might work since it will disable things like UAC that can interfere with the uninstallation process. This guide about [entering Windows safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) covers the different ways you can enter that mode.

 However, the safe mode also disables Windows Installer (MSI). So, you’ll need to tweak the registry to prevent the disabling of Windows Installer before entering safe mode. Edit the registry as follows:

1. Start the Registry Editor as covered in steps one to three of the sixth potential solution.
2. Then input the following registry key address:  
`HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\SafeBoot\Minimal`
3. Click the **Minimal** key with your right mouse button and select **New**.
4. Select **Key** and input **MSIServer** within the text box. If that key already exists, then you need not set up a new key.  
![The New > Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-key-option.jpg)
5. Next, select the **MSIServer** key and double-click its **(Default)** string.
6. Enter **Service** in the **Value data** box and select **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window4.jpg)
7. Then enter safe mode and try uninstalling the affected software.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall the Software You Need to Remove on Windows

 Although not guaranteed, there’s a pretty good chance one of the resolutions in this guide will resolve the “do not have sufficient access to uninstall” error on your PC. If not, consider troubleshooting the issue with a third-party PC repair tool.

 A more drastic troubleshooting method, like resetting Windows 11/10 or performing an in-place upgrade, might be required to fix system file and registry issues.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-can-i-view-all-shared-videos-and-photos-on-messenger/"><u>[Updated] 2024 Approved Can I View All Shared Videos And Photos on Messenger?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-maximize-your-view-with-lg-27ud88-w-monitor/"><u>[Updated] How to Maximize Your View with LG 27UD88-W Monitor</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-transition-tactics-in-audio-leveraging-adobes-fading-effects/"><u>[Updated] In 2024, Transition Tactics in Audio Leveraging Adobe’s Fading Effects</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-showcase-video-reversal-techniques/"><u>[Updated] Instagram Showcase Video Reversal Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/1726029672091-2024441khz48khz/"><u>最新オーディオ処理ガイド: 2024年ファイルを44.1kHzより高い48kHzにアップグレードする方法</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-chipsets-your-guide-to-uhd-rendering/"><u>Elite Chipsets Your Guide to UHD Rendering</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-remove-black-bars-from-youtube-videos/"><u>How to Remove Black Bars From YouTube Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-tecno-camon-20-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Tecno Camon 20 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/reparieren-sie-kostenlos-eine-beschadigte-mp4-datei-auf-mac-oder-pc-schritt-fur-schritt-anleitung/"><u>Reparieren Sie Kostenlos Eine Beschädigte MP4-Datei Auf Mac Oder PC - Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://win11.techidaily.com/1726028821180-tiktok/"><u>TikTokで携帯電話・パソコンに対応したスクリーン録画ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-the-top-6-superior-desktop-and-web-based-chrome-audio-recording-tools/"><u>Ultimate Guide: The Top 6 Superior Desktop and Web-Based Chrome Audio Recording Tools</u></a></li>
<li><a href="https://win11.techidaily.com/usb-movie-player-for-ps4-a-step-by-step-guide-to-watch-films-directly-from-a-flash-drive/"><u>USB Movie Player for PS4 - A Step-by-Step Guide to Watch Films Directly From a Flash Drive</u></a></li>
<li><a href="https://win11.techidaily.com/video-compilation-magic-a-trio-of-app-solutions-for-your-images/"><u>Video Compilation Magic: A Trio of App Solutions for Your Images</u></a></li>
<li><a href="https://win11.techidaily.com/1726026987488-windows/"><u>Windows向け最適動画変更アプリと手順ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/1726029889258-3/"><u>オンライン上で最適なビデオカットサービス3つをご紹介</u></a></li>
<li><a href="https://win11.techidaily.com/1726027232178-hd/"><u>クオリティアップ! 標準画質からHD画質への完全なフェイスライブラリー</u></a></li>
</ul></div>

