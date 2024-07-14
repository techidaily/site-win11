---
title: Skirting Enforced Driver Checks for Easier Updates
date: 2024-07-13T10:45:44.461Z
updated: 2024-07-14T10:45:44.461Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Skirting Enforced Driver Checks for Easier Updates
excerpt: This Article Describes Skirting Enforced Driver Checks for Easier Updates
keywords: DriveCheckBypassing,EasyDriversUpdates,SkippedDriverChecks,QuickUpdateAccess,ForgetfulFeeDodging,FastLanePassage,UpdateAvoidance
thumbnail: https://thmb.techidaily.com/1f664839b3fc6a46ff6691f07770bf51fb0f595eeeafca125d1de50733e104c7.jpg
---

## Skirting Enforced Driver Checks for Easier Updates

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/simplified-procedure-for-restoring-original-windows-11-search-settings/"><u>Simplified Procedure for Restoring Original Windows 11 Search Settings</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-controlled-chromeedge-configurations-for-work-computers/"><u>Steps to Tweak Controlled Chrome/Edge Configurations for Work Computers</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-pc-resources-by-unrealcefsubprocess-in-windows/"><u>Tackling Excessive PC Resources by UnrealCEFSubprocess in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-htc-u23-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any HTC U23 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-speakers-not-detected-issue/"><u>Resolving Windows: Speakers Not Detected Issue</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-professionals-way-of-removing-backgrounds/"><u>2024 Approved  The Professional's Way of Removing Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-mitigate-winerror-0x80780119/"><u>Strategies to Mitigate WinError 0X80780119</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-crafting-unified-visuals-on-your-computer/"><u>2024 Approved  Crafting Unified Visuals on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-attaching-notes-to-windows-apps/"><u>The Art of Attaching Notes to Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-cpu-and-ram-overuse-caused-by-unrealcefsubprocess-on-pcs/"><u>Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-automatic-shutdown-for-w10w11/"><u>Setting Up Automatic Shutdown for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-setup-utilize-windows-11s-troubleshooting/"><u>Streamline Your Setup: Utilize Windows 11'S Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/reliability-monitor-vs-performance-monitor-comparing-two-underutilized-windows-tools/"><u>Reliability Monitor Vs. Performance Monitor: Comparing Two Underutilized Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/studio-2-unleashed-microsofts-near-perfect-creator-tool/"><u>Studio 2 Unleashed: Microsoft's Near-Perfect Creator Tool</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-vivo-t2x-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Vivo T2x 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cleanup-close-multiple-windows-with-one-click/"><u>Quick Cleanup: Close Multiple Windows with One Click</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-low-memory-error-on-fantasy-school-of-magical-art/"><u>Remedying Low-Memory Error on Fantasy School of Magical Art</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-laughter-ledger-twittersphere-tales/"><u>2024 Approved  Laughter Ledger  Twittersphere Tales</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-xiaomi-redmi-note-12r-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Xiaomi Redmi Note 12R via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-non-interactive-components-on-windows-11/"><u>How to Resolve Non-Interactive Components on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-0x80073cf3-in-windows-microsoft-shop/"><u>Resolving Error 0X80073CF3 in Windows' Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-directdraw-faults-on-windows-oses/"><u>Steps to Eliminate DirectDraw Faults on Windows OSes</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-the-art-of-crystal-clear-audio-removing-unwanted-frequency-alterations-in-film-and-videos/"><u>In 2024, The Art of Crystal Clear Audio Removing Unwanted Frequency Alterations in Film and Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unleashing-potential-the-ultimate-pathway-to-effective-youtube-banners/"><u>2024 Approved  Unleashing Potential  The Ultimate Pathway to Effective YouTube Banners</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-mend-failed-jvm-initialization-in-windows/"><u>Techniques to Mend Failed JVM Initialization in WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-labyrinth-of-identities-finding-sids-on-win11/"><u>Navigating the Labyrinth of Identities: Finding SIDs on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rekindle-your-computers-potential-with-windows-11-via-to-go-and-rufus-path/"><u>Rekindle Your Computer's Potential with Windows 11, Via To Go & Rufus Path</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-11-calendar-into-daily-life/"><u>Integrating Windows 11 Calendar Into Daily Life</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-photo-error-unregistered-package-fix/"><u>Remedying Windows Photo Error: Unregistered Package Fix</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-application-size-modification-with-keys-on-win11/"><u>Streamlining Application Size Modification with Keys on Win11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unraveling-instagrams-policies-on-sharing-songs/"><u>Unraveling Instagram's Policies on Sharing Songs</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-with-windows-11-changing-default-actions-smoothly/"><u>Syncing with Windows 11: Changing Default Actions Smoothly</u></a></li>
<li><a href="https://win11.techidaily.com/pivotal-security-titans-winning-passwords-in-windows-11/"><u>Pivotal Security Titans: Winning Passwords in Windows 11</u></a></li>
</ul></div>
