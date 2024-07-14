---
title: Steps to Remove Programs Without Permission in Windows
date: 2024-07-13T09:51:40.551Z
updated: 2024-07-14T09:51:40.551Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Remove Programs Without Permission in Windows
excerpt: This Article Describes Steps to Remove Programs Without Permission in Windows
keywords: Unauthorized Windows Cleanup,Remove Programs Safely,Delete Applications WIndows,Erase Non-Consented Software,Windows App Removal Guide,Control Panel Cleanup Steps,Safe PC Deletion Methods
thumbnail: https://thmb.techidaily.com/3d4f10ff7575c64862599f681c5c76c2a7860b5686d5a4ad72e83eea7dc08de2.jpg
---

## Steps to Remove Programs Without Permission in Windows

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
<li><a href="https://screen-recording.techidaily.com/a-comprehensive-overview-of-cost-free-cloud-communication-software-for-2024/"><u>A Comprehensive Overview of Cost-Free Cloud Communication Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/alert-systems-top-7-windows-processes-for-infection-scrutiny/"><u>Alert Systems: Top 7 Windows Processes for Infection Scrutiny</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/jaycut-101-unlocking-the-power-of-free-online-video-editing/"><u>Jaycut 101 Unlocking the Power of Free Online Video Editing</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-melodic-matchups-finding-the-right-song-for-your-insta-story-for-2024/"><u>[Updated] Melodic Matchups  Finding the Right Song for Your Insta Story for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-mouse-experience/"><u>Customize Your Windows Mouse Experience</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-snipping-tool-in-windows-11/"><u>How to Open the Snipping Tool in Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-blender-green-screen-effects/"><u>New In 2024, Blender Green Screen Effects</u></a></li>
<li><a href="https://win11.techidaily.com/grasping-group-policies-in-windows-environments/"><u>Grasping Group Policies in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-starlit-secrets-dos-and-donts-of-astrophotography-for-2024/"><u>[New] Starlit Secrets  Do's & Don'ts of Astrophotography for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-much-information-do-you-have-about-mp4-digital-file-storage-let-us-tell-you-more-about-the-mp4-file-format-get-ready-to-increase-your-knowledge/"><u>New How Much Information Do You Have About MP4 Digital File Storage? Let Us Tell You More About the MP4 File Format; Get Ready to Increase Your Knowledge</u></a></li>
<li><a href="https://win11.techidaily.com/from-sealed-boxes-to-digital-realm-unlocking-windows-11-with-a-window-7-key/"><u>From Sealed Boxes to Digital Realm: Unlocking Windows 11 With a Window 7 Key</u></a></li>
<li><a href="https://win11.techidaily.com/correction-procedure-for-windows-error-0xca00a009/"><u>Correction Procedure for Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-a-list-of-quick-access-techniques-for-credentials-in-win11/"><u>Break the Code: A List of Quick Access Techniques for Credentials in Win11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlock-potential-with-best-free-text-psdfree/"><u>In 2024, Unlock Potential with Best Free Text PSDFree</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-budget-friendly-vlogging-cameras-unveiled-our-picks/"><u>[New] 2024 Approved  Budget-Friendly Vlogging Cameras Unveiled  Our Picks</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-rated-free-video-trimming-apps-for-windows-10-users-for-2024/"><u>New Top-Rated Free Video Trimming Apps for Windows 10 Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-pc-repair-access-with-windows-troubleshooting-hotkeys/"><u>Enhancing PC Repair Access with Windows Troubleshooting Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-connectivity-the-5g-challenge/"><u>Addressing Windows 11 Connectivity: The 5G Challenge</u></a></li>
<li><a href="https://win11.techidaily.com/historical-code-to-contemporary-computing-windows-7-to-11-activation/"><u>Historical Code to Contemporary Computing: Windows 7 to 11 Activation</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-taskbar-space-on-windows-11-os/"><u>Customizing Taskbar Space on Windows 11 OS</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/ethical-tiktok-following-purchase-with-peace-of-mind-for-2024/"><u>Ethical TikTok Following  Purchase with Peace of Mind for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-conquering-video-design-challenges-with-filmora-tips/"><u>In 2024, Conquering Video Design Challenges with Filmora Tips</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-step-by-step-path-to-smm-victory/"><u>[Updated] 2024 Approved  Step-by-Step Path to SMM Victory</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-read-only-on-windows-folders-amidst-issues/"><u>Bypassing Read-Only on Windows Folders Amidst Issues</u></a></li>
<li><a href="https://win11.techidaily.com/windows-methods-for-engaging-wordpad/"><u>Windows Methods for Engaging WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-chromes-erroneous-virus-protection-alerts/"><u>How to Reset Chrome's Erroneous Virus Protection Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-windows-camera-app-malfunctions/"><u>Fixing Common Windows Camera App Malfunctions</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-vivo-y55s-5g-2023-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-file-properties-a-windowayers-manual/"><u>Fine-Tuning File Properties: A Window'ayer's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-in-use-errors-unique-device-names-on-windows-pcs/"><u>Clearing Up In Use Errors: Unique Device Names on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/winxpxo11-how-to-prevent-closed-folders-double-clicked/"><u>WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-elite-photo-safe-houses-online/"><u>2024 Approved  Elite Photo Safe Houses Online</u></a></li>
</ul></div>
