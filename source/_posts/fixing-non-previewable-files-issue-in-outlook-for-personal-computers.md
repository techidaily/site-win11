---
title: Fixing Non-Previewable Files Issue in Outlook for Personal Computers
date: 2024-07-13T10:25:45.761Z
updated: 2024-07-14T10:25:45.761Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Non-Previewable Files Issue in Outlook for Personal Computers
excerpt: This Article Describes Fixing Non-Previewable Files Issue in Outlook for Personal Computers
keywords: Outlook File Preview,Fix Non-Viewable Emails,Outlook Readability Issues,Restore Email Display,Outlook Mail Problems,Personal Computer Email FIX,Email Rendering in Outlook
thumbnail: https://thmb.techidaily.com/24c0edcba484cab644836ae0bb31bb9d7220262ab1b4fd8d660fcbd9d1d07966.jpg
---

## Fixing Non-Previewable Files Issue in Outlook for Personal Computers

 Do you keep getting the "this file cannot be previewed" error when previewing attachments in Outlook? The good news is that you don't need to download attachments every time you want to view them, as it is possible to fix this annoying issue.

 Below, we share eight quick and easy fixes for resolving the “this file cannot be previewed” error in Outlook for Windows.

## 1\. Install Relevant Apps to Preview Files

 Outlook may fail to preview attachments if the appropriate app for the file format is not installed on your PC. For instance, if you don’t have a [PDF reader app on your PC](https://www.makeuseof.com/tag/6-pdf-readers-windows/) , Outlook may display the “this file cannot be previewed because there is no previewer installed for it” error.

 To avoid this, ensure that the appropriate app or software for the file format is available on your computer. After that, Outlook should be able to preview your files without any problems.

## 2\. Disable Preview Handler in PowerToys

 Using Microsoft PowerToys is an excellent way to [boost your productivity on Windows computers](https://www.makeuseof.com/set-up-windows-pc-maximum-productivity/) . However, these PowerToys utilities can sometimes interfere with app processes and prevent apps from working properly.

 Several users on the forums reported fixing Outlook’s “this file cannot be previewed” error by disabling the Preview Handler feature. You can also give this method a shot.

1. Open the**PowerToys** app using the search menu.
2. Switch to the**File Explorer add-ons** tab using the left sidebar.
3. Under the**Preview Pane** section, disable the toggle next to**Portable Document Format** .  
![Disable Preview Handlers in PowerToys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-preview-handlers-in-powertoys.jpg)

## 3\. Enable Attachment Preview in Outlook

 It's possible that Outlook is failing to preview attachments because the file previewer feature is disabled in the app. To overrule this possibility, you need to check the attachment handling settings in Outlook.

1. Open the**Outlook** app on your PC.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left sidebar.
4. Navigate to the**Trust Center** tab and click the**Trust Center Settings** button.
5. In the**Attachment Handling** tab, clear the**Turn off Attachment Preview** checkbox.
6. Click on**Attachment and Document Previewers** and make sure all the previewers are active. Then, click**OK** .
7. Restart the Outlook app after this and see if you can preview attachments.  
![Attachment Handling in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/attachment-handling-in-outlook.jpg)

## 4\. Change Outlook User Interface Settings

 Another thing you can do is tweak the User Interface Settings in Outlook and see if that gets the app to load attachment previews on Windows. Here are the steps for the same:

1. Open the Outlook app and click the**File** menu at the top.
2. Select**Options** from the left column.
3. In the Outlook Options window, navigate to the**General** tab.
4. Under the**User Interface Settings** section, select**Optimize for compatibility** option.  
![Optimize Outlook for Compatibility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/optimize-outlook-for-compatibility.jpg)

 Restart the Outlook app after this and check if the issue is still there.

## 5\. Clear Outlook Cache

 Outlook, like most apps, stores cache files on your computer to reduce loading times. Although this data is supposed to improve app performance, it’s not uncommon for it to become corrupted over time. When this happens, Outlook may malfunction or throw strange errors. You can try deleting the Outlook cache and see if that helps.

To delete Outlook cache data on Windows, use these steps:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Run** from the list.
3. Type**%localappdata%\\Microsoft\\Outlook** in the text box and press**Enter** .
4. In the**RoamCache** folder that appears, select all the files and click the**trash icon** at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 6\. Enable Windows Firewall

 Have you disabled Windows Defender Firewall on your computer? That could prevent Outlook from previewing attachments.

 Here's how to check if the Windows Defender Firewall is enabled on your PC.

1. Press**Win + S** to open the search menu.
2. Type**Windows Security** in the search box and press**Enter** .
3. Select**Firewall & network protection** tab from the left pane.
4. Choose a network profile.
5. Enable the toggle for**Windows Defender Firewall** .  
![Enable Microsoft Defender Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-microsoft-defender-firewall.jpg)

## 7\. Modify Registry Files

 Incorrect [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) settings could also cause such anomalies. If that's the case, you'll need to correct the Registry settings manually on your PC.

 Since Registry files contain important settings for Windows and its apps, you should only use this method if you’re familiar with editing Registry files. Also, it’s a good idea to back up all the Registry files before you proceed. If you need help with that, check our guide on [how to back up Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > ​SOFTWARE > ​Microsoft > ​Windows > ​CurrentVersion > ​PreviewHandlers** .
5. Look for the following string values and check the associated**Data** on the right side.  
`{00020827-0000-0000-C000-000000000046} = Microsoft Excel previewer  
{21E17C2F-AD3A-4b89-841F-09CFE02D16B7} = Microsoft Visio previewer  
{65235197-874B-4A07-BDC5-E65EA825B718} = Microsoft PowerPoint previewer  
{84F66100-FF7C-4fb4-B0C0-02CD7FB668FE} = Microsoft Word previewer  
{DC6EFB56-9CFA-464D-8880-44885D7DC193} = Adobe PDF Preview Handler for Vista`  
![Preview Handlers in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/preview-handlers-in-registry.jpg)
6. If any of the above-mentioned values are missing, right-click on an empty spot and select**New > String Value** .
7. Double-click on the newly created string value.
8. Enter the name of the application handler in the**Value data** field and click**OK** .
9. Right-click on the string value, select**Rename** and type the value associated with the application handler.
10. Exit the Registry Editor window and restart your PC.  
![Edit String in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-string-in-registry.jpg)

## 8\. Run the Microsoft Office Repair Tool

 Microsoft Office includes a repair tool for fixing Office apps on Windows. So, if nothing works, you can run this tool to repair the Outlook app. Here's how:

1. [Use one of the many ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
2. Go to**Programs and Features** .
3. Locate and select**Microsoft Office** on the list. Then, click the**Change** button at the top.
4. Select**Quick Repair** and then click**Repair** .  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 Wait for the process to finish and check if you can preview files. If you can't, repeat the above steps to perform an**Online Repair** . As suggestive of its name, this process does necessitate an active internet connection on your computer.

## Preview Your Outlook Attachments Again on Windows

 One of these eight fixes should take care of the “this file cannot be previewed” error in Outlook. If not, you can consider reinstalling the Outlook app as a last resort.

 If you're tired of dealing with the Outlook app's recurring problems, there are plenty of excellent email clients for Windows.


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
<li><a href="https://video-ai-editor.techidaily.com/updated-effortless-avi-video-editing-top-cutters-and-trimmers-for-any-device-for-2024/"><u>Updated Effortless AVI Video Editing Top Cutters and Trimmers for Any Device for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-nostalgia-in-streaming-restoring-yt-videos-removed/"><u>In 2024, Nostalgia in Streaming  Restoring YT Videos Removed</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-whisperer-guide-to-win11-menu-hiding/"><u>The Silent Whisperer Guide to Win11 Menu Hiding</u></a></li>
<li><a href="https://win11.techidaily.com/bring-task-manager-above-all-step-guide/"><u>Bring Task Manager Above All: Step Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-ultimate-guide-to-recording-your-lol-adventures-3-ways-for-2024/"><u>[Updated] The Ultimate Guide to Recording Your LOL Adventures (3 Ways) for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-on-your-iphone-15-pro-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock on your iPhone 15 Pro and iPad?</u></a></li>
<li><a href="https://win11.techidaily.com/discover-football-fortunes-for-free-with-old-championship-manager/"><u>Discover Football Fortunes for Free with Old Championship Manager</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-uncovering-the-method-of-anti-play-video-snapchat/"><u>[Updated] Uncovering the Method of Anti-Play Video Snapchat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-elite-imagery-the-finest-8k-camera-selections-for-2024/"><u>[New] Elite Imagery  The Finest 8K Camera Selections for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-need-privilege-escalation-issue-fixing-error-740/"><u>Tackling Need Privilege Escalation Issue: Fixing Error 740</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://screen-recording.techidaily.com/unlock-screen-saving-potential-on-android-devices-for-2024/"><u>Unlock Screen Saving Potential on Android Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/typography-transition-on-windows-multilingual-scripts/"><u>Typography Transition on Windows: Multilingual Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-mend-dormant-usb-ports-the-windows-manual/"><u>Diagnose & Mend Dormant USB Ports - The Windows Manual</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-with-top-5-affordable-car-update-tools/"><u>Elevate Your Windows Experience with Top 5 Affordable Car Update Tools</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-the-insiders-guide-to-audio-recordings-using-apowersoft-and-discovering-4-comparable-software-options/"><u>Updated 2024 Approved The Insiders Guide to Audio Recordings Using Apowersoft & Discovering 4 Comparable Software Options</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-ctrl-keys-in-windows-11/"><u>Fixing Non-Operational Ctrl Keys in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfersync-notes-from-apple-iphone-11-pro-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer/Sync Notes from Apple iPhone 11 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-functional-window-11-menu-bar/"><u>Tackling Non-Functional Window 11 Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuity-with-powertoys-settings-transfer/"><u>Ensuring Continuity with PowerToys Settings Transfer</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-space-hogs-on-your-windows-hard-drive/"><u>Unveiling Space Hogs on Your Windows Hard Drive</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-sign-out-of-apple-id-on-iphone-7-plus-without-password-by-drfone-ios/"><u>How to Sign Out of Apple ID On iPhone 7 Plus without Password?</u></a></li>
<li><a href="https://win11.techidaily.com/ten-strategies-to-keep-windows-safe-without-bitlocker-support/"><u>Ten Strategies to Keep Windows Safe without Bitlocker Support</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-potential-of-batch-files-via-exes/"><u>Unlock the Potential of Batch Files via EXEs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-geforce-error-x0001-on-windows-pcs/"><u>Fixing Common GeForce Error X0001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/winsecurely-solutions-for-windows-without-bitlocker/"><u>WinSecurely: Solutions for Windows Without Bitlocker</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wsl-2-streamline-docker-usage/"><u>Boosting WSL 2: Streamline Docker Usage</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-sync-software-windows-and-android-unite/"><u>Essential Sync Software: Windows & Android Unite</u></a></li>
<li><a href="https://extra-hints.techidaily.com/creating-captivating-podcast-highlights/"><u>Creating Captivating Podcast Highlights</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-save-configuration-errors-in-pubg/"><u>Correcting Save Configuration Errors in PUBG</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-ideal-nvidia-drivers-gaming-vs-production-sector/"><u>Deciding on Ideal Nvidia Drivers: Gaming vs Production Sector</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-tasks-custom-windows-shortcuts-for-uwp/"><u>Breeze Through Tasks: Custom Windows Shortcuts for UWP</u></a></li>
<li><a href="https://extra-information.techidaily.com/your-path-to-photo-wizardry-the-complete-guide-to-using-the-background-erase-in-photoshop/"><u>Your Path to Photo Wizardry  The Complete Guide to Using the Background Erase in Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-error-0x80070194-with-onedrive/"><u>Addressing the Error 0X80070194 with OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-iis-8-key-steps/"><u>Unlocking IIS: 8 Key Steps</u></a></li>
</ul></div>
