---
title: How to Uninstall Programs Without Admin Privileges on WINDOWS
date: 2024-07-13T10:45:29.338Z
updated: 2024-07-14T10:45:29.338Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Uninstall Programs Without Admin Privileges on WINDOWS
excerpt: This Article Describes How to Uninstall Programs Without Admin Privileges on WINDOWS
keywords: Non-Admin Remove Windows Programs,Unauthorized Deletion Windows Software,User-Level App Removal Win,Safe Delete Windows Progs Without Admin,Regular Users Uninstall Windows,Bypass Administrator to Clear Apps,Execute Program Removal WITHOUT Admin
thumbnail: https://thmb.techidaily.com/909f3c7957e52f6fe9de5cd9ae15915a5af92e86352ca57ab485a51d50b112ab.png
---

## How to Uninstall Programs Without Admin Privileges on WINDOWS

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
<li><a href="https://win11.techidaily.com/mastering-windows-11-dont-make-these-top-8-mistakes/"><u>Mastering Windows 11: Don't Make These Top 8 Mistakes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-vivo-y27s-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Vivo Y27s without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-differences-of-windows-terminal-vs-powershell/"><u>Dissecting the Differences of Windows Terminal Vs. PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/win11-volume-personalized-hotkeys-and-control-creation-guide/"><u>Win11 Volume: Personalized Hotkeys and Control Creation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err-87-for-incompatible-library-loading/"><u>Fixing Err 87 for Incompatible Library Loading</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-2022s-pinnacle-moments-in-snowboarding-x/"><u>[New] 2022'S Pinnacle Moments in Snowboarding X</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-charting-the-course-for-your-youtube-music-narrative-for-2024/"><u>[Updated] Charting the Course for Your YouTube Music Narrative for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-nokia-105-classic-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err0r-code-e1-in-w10w11/"><u>Fixing Err0r: Code E1 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/install-windows-11-on-mac-with-parallels-step-by-step/"><u>Install Windows 11 on Mac with Parallels Step-by-Step</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-find-x7-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo Find X7 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-your-computers-warmup-time-in-win11/"><u>Cut Down Your Computer's Warmup Time in Win11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-tech-bites-the-future-of-screen-capture-apps-for-2024/"><u>[New] Tech Bites  The Future of Screen Capture Apps for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-enhancing-content-reach-keeping-creative-commons-engagement-high/"><u>[Updated] 2024 Approved  Enhancing Content Reach  Keeping Creative Commons Engagement High</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-12-animated-slideshow-powerpoint-templates-and-tools-to-make-them/"><u>In 2024, 12 Animated Slideshow PowerPoint Templates and Tools to Make Them</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-mastering-advertising-for-profit-the-ultimate-vimeo-guidebook/"><u>[New] In 2024, Mastering Advertising for Profit  The Ultimate Vimeo Guidebook</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-from-photos-to-film-mastering-video-slideshows-in-final-cut-pro-for-2024/"><u>New From Photos to Film Mastering Video Slideshows in Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/facing-browser-blockades-top-tactics-to-reach-sites-on-your-system/"><u>Facing Browser Blockades: Top Tactics to Reach Sites on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-ai-synergy-with-windows-11-features/"><u>Exploring AI Synergy with Windows 11 Features</u></a></li>
<li><a href="https://howto.techidaily.com/infinix-smart-8-hd-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Infinix Smart 8 HD Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/symphony-for-statuses-whatsapps-melodic-feature-for-2024/"><u>Symphony for Statuses  WhatsApp's Melodic Feature for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-steam-sound-fidelity/"><u>Enhancing Windows Steam Sound Fidelity</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-writing-errors-for-files-in-windows-systems/"><u>Overcoming Writing Errors for Files in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-link-your-windows-product-key-to-a-microsoft-account/"><u>How to Link Your Windows Product Key to a Microsoft Account</u></a></li>
<li><a href="https://win11.techidaily.com/merging-windows-credentials-with-microsoft-identity-hub/"><u>Merging Windows Credentials with Microsoft Identity Hub</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/uncover-these-top-ten-thriving-youtube-communities-today/"><u>Uncover These Top Ten Thriving YouTube Communities Today</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/effective-guide-to-cast-apple-iphone-12-to-macbook-without-hindrance-drfone-by-drfone-ios/"><u>Effective Guide to Cast Apple iPhone 12 to MacBook without Hindrance | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unreachable-friends-list-on-steam-win-11/"><u>Fixing Unreachable Friends List on Steam (Win 11)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-jokesonscreen-pro/"><u>[Updated] JokesOnScreen Pro</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-reclaiming-faulty-usb-connectivity-windows/"><u>Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-an-inactive-itunes-on-your-pc/"><u>How to Reactivate an Inactive iTunes on Your PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-unlocking-features-advanced-logitech-webcam-techniques/"><u>[Updated] 2024 Approved  Unlocking Features  Advanced Logitech Webcam Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-resolving-windows-error-code-c0000022/"><u>Expert Guide to Resolving Windows Error Code C0000022</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-tecno-pova-5-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Tecno Pova 5 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-guide-to-streaming-and-recording-webcasts-professionally/"><u>2024 Approved  In-Depth Guide to Streaming and Recording Webcasts Professionally</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-enhance-tweet-management-the-most-effective-apps-for-tweets/"><u>[Updated] In 2024, Enhance Tweet Management  The Most Effective Apps for Tweets</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-read-only-windows-folder-problems/"><u>Navigating and Resolving Read-Only Windows Folder Problems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-color-management-in-windows/"><u>Navigating the Nuances of Color Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-operational-health-mastering-the-top-5-availability-tests/"><u>Windows 11 Operational Health: Mastering the Top 5 Availability Tests</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-streamlined-techniques-for-efficient-apple-screenshots/"><u>2024 Approved  Streamlined Techniques for Efficient Apple Screenshots</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-flexibility-in-your-windows-environment-with-alomware/"><u>Maximize Flexibility in Your Windows Environment with AlomWare</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-poco-c50-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Poco C50 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/1714258720165-new-here-is-how-you-can-do-it-effectively-either-with-built-in-tools-provided-by-tiktok-or-with-additional-pieces-of-reverser-tools-to-reverse-a-tiktok-vide/"><u>New Here Is How You Can Do It Effectively, Either with Built-In Tools Provided by TikTok or with Additional Pieces of Reverser Tools to Reverse a TikTok Video for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-facebook-mp3-converter-top-8-online-options/"><u>2024 Approved Facebook MP3 Converter Top 8 Online Options</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-unidentified-hdd-situations/"><u>Navigating Through Unidentified HDD Situations</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-visibility-on-windows-11-discreet-features/"><u>Enabling Visibility on Windows 11 Discreet Features</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-remedies-to-address-instantaneous-failure-when-adding-a-folder-in-the-windows-onedrive-environment/"><u>Efficient Remedies to Address Instantaneous Failure when Adding a Folder in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/disentangle-clustered-taskbar-items-in-windows-11/"><u>Disentangle Clustered Taskbar Items in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-samsung-galaxy-m34-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Samsung Galaxy M34 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computing-enable-hyper-v-in-windows-11-homes/"><u>Boost Your Computing: Enable Hyper-V in Windows 11 Homes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/illuminating-the-art-of-iphone-long-exposure/"><u>Illuminating the Art of iPhone Long Exposure</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Motorola Moto G13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-and-correcting-windows-11-errors/"><u>Confronting and Correcting WINDOWS 11 Errors</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-language-of-gratitude-30-global-lessons-157-trimmed-to-fit/"><u>The Language of Gratitude: 30 Global Lessons (157) [Trimmed to Fit]</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-trending-topics-tally-10-tweets-triumphing/"><u>[New] In 2024, Trending Topics Tally  10 Tweets Triumphing</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-admin-mode-execution-in-windows-console/"><u>Overcoming Failed Admin Mode Execution in Windows Console</u></a></li>
<li><a href="https://video-capture.techidaily.com/expert-techniques-for-gameplay-recordings-via-obs/"><u>Expert Techniques for Gameplay Recordings via OBS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-art-of-haul-videography-pre-and-post-editing-processes/"><u>In 2024, The Art of Haul Videography  Pre and Post Editing Processes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-essential-tips-for-smooth-screen-sharing-on-skype-while-working-from-home/"><u>2024 Approved  Essential Tips for Smooth Screen Sharing on Skype While Working From Home</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-recordings-best-free-windows-programs/"><u>Perfect Your Recordings: Best FREE Windows Programs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-art-of-antiquated-visuals-for-modern-audienciplines-for-2024/"><u>The Art of Antiquated Visuals for Modern Audienciplines for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-with-msoffice-on-win11-os/"><u>Getting Started with MSOffice on Win11 OS</u></a></li>
</ul></div>
