---
title: Overcoming Permission Barriers in Windows Updates
date: 2024-07-13T10:19:46.859Z
updated: 2024-07-14T10:19:46.859Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Permission Barriers in Windows Updates
excerpt: This Article Describes Overcoming Permission Barriers in Windows Updates
keywords: Win Update Access Control,Bypassing Windows Updates,Disable UAC for Updates,Unblock Windows Patches,Update Permissions Fix,Eliminate Barriers in UWP,Secure Windows Update Entry
thumbnail: https://thmb.techidaily.com/72ca63d6325a67d4b7a844299776fc3c0b1aca6440d5ca1111f8174af4b16af4.jpg
---

## Overcoming Permission Barriers in Windows Updates

 Some users have reported an uninstall issue on Microsoft’s forum with an error message that says, “You do not have sufficient access to uninstall.” That error message pops up when users try to uninstall certain software in Windows 11/10\. As a result, users can’t uninstall whatever software packages that error occurs for.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

## 1\. Enable the Windows Admin Account

 First, make sure you’re utilizing an admin account. You can [activate a built-in Windows admin account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) via the Command Prompt. Then log in to that built-in admin account and try uninstalling the software from there.

 Alternatively, you can switch a current standard user account to an admin one. Check out this guide to [changing Windows account types](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) for full instructions about how to do so.

## 2\. Run the Affected Software’s Uninstaller File as an Administrator

 Also, run the software’s uninstaller file as an administrator. The software’s installation directory will include its uninstaller file. Right-click that file to select a **Run as administrator** context menu option.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option5.jpg)

## 3\. Troubleshoot With the Program Install and Uninstall Troubleshooter

 Windows doesn’t include any troubleshooter for fixing uninstallation issues. However, there is a Microsoft Program Install and Uninstall troubleshooter that might be useful for fixing the “You do not have sufficient access to uninstall” error. This is how you can run the Program Install and Uninstall troubleshooter:

1. Bring up the troubleshooter's [Microsoft download page](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d).
2. Then click on the **Download** troubleshooter button.
3. Double-click on the **MicrosoftProgram\_Install\_and\_Uninstall.meta.diagcab** troubleshooter file.  
![The Program Install and Uninstall troubleshooter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-install-and-uninstall-troubleshooter.jpg)
4. Click on **Next** \> **Uninstalling** to bring up a program list.  
![The Uninstalling option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstalling-option.jpg)
5. Then select the program you can’t uninstall and select **Next**.  
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
4. Select your user account name.
5. Click the **Full control** checkbox to select that setting if it’s not already.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-control-window.jpg)
6. Then select **Apply** \> **OK** on the folder’s permissions window.
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
<li><a href="https://win11.techidaily.com/how-to-handle-unsupported-devices-warning-when-upgrading-windows/"><u>How to Handle Unsupported Devices Warning When Upgrading Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-smooth-directx-installation-on-pc/"><u>Step-by-Step Guide to Smooth DirectX Installation on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-icon-resolution-on-windows-11-taskbar/"><u>Mastering Icon Resolution on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/edge-persistent-operation-on-win11/"><u>Edge: Persistent Operation on Win11?</u></a></li>
<li><a href="https://win11.techidaily.com/enable-system-sounds-despite-muted-status/"><u>Enable System Sounds Despite Muted Status</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-dull-cursors-simple-steps/"><u>Brightening Dull Cursors: Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-100mbps-wired-internet-limit-in-windows/"><u>Break Free From 100Mbps Wired Internet Limit in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ntoskrnlexe-overload-issue/"><u>Addressing Ntoskrnl.exe Overload Issue</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-assistive-center-in-five-moves/"><u>Unlock Windows' Assistive Center in Five Moves</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-err0r-x7e1-in-win1011/"><u>Remedying Err0r: X7E1 in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/boundary-defying-tech-windows-for-apple-devices-breaks-new-ground/"><u>Boundary-Defying Tech: Windows for Apple Devices Breaks New Ground</u></a></li>
<li><a href="https://win11.techidaily.com/erasing-email-on-windows-sign-in-a-guide/"><u>Erasing Email on Windows Sign-In: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-obstacles-hindering-discord-setup-success/"><u>Eliminating Obstacles Hindering Discord Setup Success</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-ultimate-video-production-for-earth/"><u>2024 Approved  Ultimate Video Production for Earth</u></a></li>
<li><a href="https://win11.techidaily.com/3-key-steps-for-a-quick-return-to-desktop-in-wins-1011/"><u>3 Key Steps for a Quick Return to Desktop in Wins 10/11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-best-practices-for-vlc-video-capturing/"><u>[New] In 2024, Best Practices for VLC Video Capturing</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/type-smartly-and-fast-typingaid-secrets/"><u>Type Smartly and Fast - TypingAid Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/openai-whisper-for-windows-voice-to-text-techniques-unveiled/"><u>OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/stabilize-task-manager-app-placement-techniques/"><u>Stabilize Task Manager App Placement Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-reboot-file-explorer-on-win1011/"><u>Methods to Reboot File Explorer on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-purging-partitions-on-your-win-os/"><u>Mastering the Art of Purging Partitions on Your Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fix-kit-conquering-error-code-0x80-cookies/"><u>Microsoft Store Fix Kit: Conquering Error Code 0X80 Cookies</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-strategies-for-eradicating-microsoft-defender-footprints/"><u>Win 11 Strategies for Eradicating Microsoft Defender Footprints</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/from-tiktok-to-instagram-stardom-replicating-popular-reel-techniques-for-2024/"><u>From TikTok to Instagram Stardom  Replicating Popular Reel Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-11-ui/"><u>The Essentials of Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-stuck-scrolling-in-excel-window-edition/"><u>Solutions for Stuck Scrolling in Excel, Window Edition</u></a></li>
<li><a href="https://win11.techidaily.com/reinstalling-the-redundant-or-missing-windows-tools-and-add-ons/"><u>Reinstalling the Redundant or Missing Windows Tools & Add-Ons</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-altered-captions-a-video-guide/"><u>2024 Approved  Altered Captions  A Video Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/delete-gmail-account-withwithout-password-on-samsung-galaxy-s24plus-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Samsung Galaxy S24+</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-device-sticky-note-integration-on-win11/"><u>Seamless Multi-Device Sticky Note Integration on WIN11</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-open-the-appsfolder-in-windows-11/"><u>7 Ways to Open the AppsFolder in Windows 11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-transform-your-android-footage-with-stunning-time-lapse-videos/"><u>[Updated] Transform Your Android Footage with Stunning Time-Lapse Videos</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-recovering-lost-access-to-launcher/"><u>Quick Fixes for Recovering Lost Access to Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/speak-up-against-silence-fixes-to-free-your-spacebar/"><u>Speak Up Against Silence: Fixes to Free Your Spacebar</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-navigation-for-uwp-apps-with-windows-11-links/"><u>Rapid Navigation for UWP Apps with Windows 11 Links</u></a></li>
<li><a href="https://win11.techidaily.com/best-web-browsing-practices-minimizing-resources-across-platforms/"><u>Best Web Browsing Practices: Minimizing Resources Across Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/gaining-admin-access-in-command-prompt/"><u>Gaining Admin Access in Command Prompt</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-mastering-google-meet-creation-and-scheduling-guide/"><u>[Updated] 2024 Approved  Mastering Google Meet  Creation & Scheduling Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-account-sign-in-troubleshooting/"><u>Mastering Windows 11 Account Sign-In Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-windows-11s-help-interaction/"><u>How to Revive Windows 11'S Help Interaction</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-on-windows/"><u>Mastering the Art of CR2 to JPG Conversion on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-corruption-errors-fixing-file-issues-code-0x80070570-on-windows-11/"><u>Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-with-linuxs-sudo-feature/"><u>Navigating Windows with Linux's Sudo Feature</u></a></li>
</ul></div>
