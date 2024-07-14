---
title: Defeating Inaccessible Program Uninstall in Microsoft's Latest OS
date: 2024-07-13T10:26:33.109Z
updated: 2024-07-14T10:26:33.109Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Defeating Inaccessible Program Uninstall in Microsoft's Latest OS
excerpt: This Article Describes Defeating Inaccessible Program Uninstall in Microsoft's Latest OS
keywords: Uninstalling Windows,Overcoming Access Issues,Fixing OS Errors,Removing Programs Safely,Restarting System Successfully,Disabling Hardware Inaccessibility,Master OS Troubleshooting
thumbnail: https://thmb.techidaily.com/151496d9a19ba95beb3641cc868ae237a3532fbd921c881e6672274d100dff06.jpg
---

## Defeating Inaccessible Program Uninstall in Microsoft's Latest OS

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
<li><a href="https://win11.techidaily.com/uninstall-simplified-top-methods-for-windows-11-users-111-chars/"><u>Uninstall Simplified: Top Methods for Windows 11 Users (111 Chars)</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-video-steadicam-top-mobile-apps-for-smooth-footage/"><u>New 2024 Approved Video Steadicam Top Mobile Apps for Smooth Footage</u></a></li>
<li><a href="https://win11.techidaily.com/add-on-troubleshooters-for-improved-software-functionality/"><u>Add-On Troubleshooters for Improved Software Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-unravelled-enabling-windows-update/"><u>Error 2E Unravelled: Enabling Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/concealed-commands-disguise-power-settings-in-start-screen/"><u>Concealed Commands: Disguise Power Settings in Start Screen</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-path-not-found-on-pc-systems/"><u>Fixing Path Not Found on PC Systems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-fb-cover-video-excellence-strategies-for-leadership-in-social-media/"><u>[New] FB Cover Video Excellence  Strategies for Leadership in Social Media</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-pc-performance-deficiencies-amidst-intel-errors/"><u>Tackling PC Performance Deficiencies Amidst Intel Errors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/getting-started-with-hd-video-a-guide-to-pixel-size-and-resolution-for-2024/"><u>Getting Started with HD Video A Guide to Pixel Size and Resolution for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-create-stunning-intros-top-10-websites-with-free-and-paid-options/"><u>New In 2024, Create Stunning Intros Top 10 Websites with Free and Paid Options</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-lenovo-thinkphone-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Lenovo ThinkPhone FRP Bypass With Best Methods</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-boosting-call-joy-with-5-hilarious-voice-transformation-hacks/"><u>New 2024 Approved Boosting Call Joy with 5 Hilarious Voice Transformation Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-github-desktop-on-windows-11-a-complete-guide/"><u>Mastering GitHub Desktop on Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-discovery-of-software-installs-for-windows-users/"><u>Seamless Discovery of Software Installs for Windows Users</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-how-to-add-a-touch-of-personality-to-your-discord-status-a-pc-and-mobile-walkthrough/"><u>[New] 2024 Approved  How to Add a Touch of Personality to Your Discord Status  A PC & Mobile Walkthrough</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-snapchat-highlight-101-usage-techniques/"><u>2024 Approved  Snapchat Highlight 101  Usage Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-the-aw-snap-error-in-chrome/"><u>How to Stop the Aw, Snap! Error in Chrome</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-best-free-cloud-based-video-editing-tools-for-2024/"><u>[Updated] The Best Free, Cloud-Based Video Editing Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-way-to-clean-clear-notes/"><u>The Obsidian Way to Clean, Clear Notes</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-disk-differentiation-hdd-and-ssd-recognition-on-pcs/"><u>Simplifying Disk Differentiation: HDD & SSD Recognition on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/top-quick-strategies-for-black-screen-in-wins-1011/"><u>Top Quick Strategies for Black Screen in Wins 10/11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweeting-videos-to-tweenish-animations-for-no-fee-for-2024/"><u>Tweeting Videos to Tweenish Animations for No Fee for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-looks-like-youre-stranded-on-xbox-error/"><u>Guide to Overcoming 'Looks Like You're Stranded' On Xbox Error</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-to-remove-microsoft-store-from-pcs/"><u>Three Methods to Remove Microsoft Store From PCs</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-google-nearby-sharing-service-in-windows/"><u>Re-Establishing Google Nearby Sharing Service in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-online-audio-enhancement-a-step-by-step-guide-to-adjusting-speed-and-pitch-for-2024/"><u>New Online Audio Enhancement A Step-by-Step Guide to Adjusting Speed & Pitch for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-elite-unmanned-aerial-vehicles-up-for-grabs/"><u>2024 Approved  Elite Unmanned Aerial Vehicles Up for Grabs</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-list-of-supported-iphone-video-formats-and-best-iphone-video-editor-for-2024/"><u>New List of Supported iPhone Video Formats and Best iPhone Video Editor for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-no-click-spaces-within-windows-11-interface/"><u>Combatting No-Click Spaces Within Windows 11 Interface</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/becoming-a-facetime-videographer-extraordinaire/"><u>Becoming a Facetime Videographer Extraordinaire</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-what-users-find-flawed-in-windows-11/"><u>Deciphering What Users Find Flawed in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-turn-off-unsolicited-game-suggestions-for-w11/"><u>Learn to Turn Off Unsolicited Game Suggestions for W11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-discover-the-most-effective-5-screen-capturing-tools-for-chromebook-for-2024/"><u>[Updated] Discover the Most Effective 5 Screen Capturing Tools for Chromebook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pc-potential-by-clearing-windows-temp-files/"><u>Unlock Your PC Potential by Clearing Windows Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-no-permission-on-windows-file-viewing/"><u>Strategies to Avoid 'No Permission' On Windows File Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-google-chrome-from-creating-random-tabs/"><u>How To Prevent Google Chrome From Creating Random Tabs</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/snapchat-screen-recording-via-mobile-devices-a-guide/"><u>Snapchat Screen Recording via Mobile Devices  A Guide</u></a></li>
</ul></div>
