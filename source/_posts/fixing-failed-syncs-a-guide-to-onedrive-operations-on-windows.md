---
title: "Fixing Failed Syncs: A Guide to OneDrive Operations on Windows"
date: 2024-07-13T11:02:56.301Z
updated: 2024-07-14T11:02:56.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Failed Syncs: A Guide to OneDrive Operations on Windows"
excerpt: "This Article Describes Fixing Failed Syncs: A Guide to OneDrive Operations on Windows"
keywords: Sync Fix Guide,OneDrive Windows Troubleshoot,Resolve Drive Errors,OneDrive Sync Restore,Sync Issue Solutions,Data Loss Prevention,OneDrive Operations Tips
thumbnail: https://thmb.techidaily.com/485101ae8f555e145174a15eda6071c25617b2b00c96089d339b8e4537366b75.jpg
---

## Fixing Failed Syncs: A Guide to OneDrive Operations on Windows

 OneDrive is Microsoft’s cloud storage app included with Windows, and many users save their files to the cloud with it. However, some users have had issues accessing shared OneDrive files because of error 0x80070185\. When users try to copy or download shared OneDrive files, they see this message: “Error 0x80070185: The cloud operation was unsuccessful.”

 Users can’t copy or download shared files from OneDrive once error 0x80070185 appears. If you're also experiencing this issue, here is how you can fix error 0x80070185 in Windows 10 and 11.

## 1\. Log Out and Back Into OneDrive

 First, try logging out and back into your OneDrive account. To do so, you’ll need to unlink your PC with your OneDrive account. This is how you can log out and sign back into OneDrive:

1. Right-click the**OneDrive** icon in the system tray.
2. Click the**Help & Settings** cog button.
3. Select**Settings** to bring up an**Account** tab.  
![The Settings option in OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-option.jpg)
4. Click the**Unlink this PC** option.  
![The Unlink this PC option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unlink-this-pc.jpg)
5. Select**Unlink account** to sign out.

1. If a sign-in window doesn’t automatically open, input OneDrive in the Windows search box and select to open it there.
2. Input your OneDrive email address (for your Microsoft account), and click the**Sign in** option.  
![The Sign in button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-in-button.jpg)
3. Enter a password, and press the**Sign in** button.
4. Keep clicking**Next** to reach the last option on the OneDrive setup window.
5. Press the**Open my OneDrive** **folder** button.

## 2\. Free Up Hard Drive Space

 Error 0x80070185 can arise when there’s very little free space available on the local drive. As such, your PC’s hard drive may have insufficient space for the larger files in your OneDrive cloud storage.

 First, check your PC’s drive storage space by launching File Explorer and clicking**This PC** . The C: drive icon there shows you how much free storage is available.

![The Local Disk storage icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/local-disk-storage-icon.jpg)

 If your PC’s hard drive is full, or close to it, free up some storage space. You can make more space on your hard drive by uninstalling software, deleting unneeded user files, and erasing junk data. Our guide about [how to free up storage space in Windows 11](https://www.makeuseof.com/windows-11-free-up-storage-space/) includes numerous methods for making space on a drive.

## 3\. Reset the OneDrive App

 Corrupted OneDrive cache data is a potential cause for error 0x80070185 that you can address by resetting the app. Reset OneDrive with Run as follows:

1. Bring up the Power User shortcuts menu by pressing the**Win + X** keys.
2. Select**Run** to view that command dialog.
3. Type or paste the following command for resetting OneDrive into Run:  
`%localappdata%\Microsoft\OneDrive\OneDrive.exe /reset`  
![The reset OneDrive Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-reset-one-drive-command.jpg)
4. Click**OK** to execute the reset command for OneDrive.
5. If the OneDrive icon doesn’t reappear after the reset, input this command into Run and click**OK** :  
`%localappdata%\Microsoft\OneDrive\onedrive.exe`

## 4\. Sync OneDrive to Another Drive Location

 Do you have another drive partition on your PC? If you do, try linking the OneDrive app with the alternative partition instead. You can sync OneDrive to a different drive location like this:

1. First, unlink the OneDrive app as outlined in steps one to five of this guide’s first potential resolution.
2. Then input the email address and password for the Microsoft account you utilize with the OneDrive app.
3. Press the**Sign in** button.
4. Click the**Change location** option.  
![The Change location option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-location-option.jpg)
5. Select an alternative drive partition on your PC to link OneDrive with.
6. Click**Select Folder** to confirm the chosen location.
7. Keep clicking**Next** a few times, and select the**Open my OneDrive folder** option.  
![The Open my OneDrive folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-my-onedrive-folder.jpg)

## 5\. Enable the "Always Keep on Device" and "Free Up Space" Options

 Some OneDrive users have confirmed selecting to always keep affected files on the device, along with a "free up space" option, can fix error 0x80070185\. Selecting the "always keep on this device" option makes a OneDrive file available offline.

 This is how you can select those options for an affected OneDrive file:

1. Press**Win + E** to open File Explorer.
2. Click the arrow for your OneDrive storage on the left of Explorer.
3. Right-click the file affected by error 0x80070185 and select**Always keep on this** **device** .  
![The Always keep on this device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/always-keep-on-this-device-option.jpg)
4. Then right-click the same file again to select**Free up** **space** .
5. Repeat these steps for all files you can’t access because of error 0x80070185.

## 6\. Turn Off Any Active Firewalls

 Firewall blocks applied to OneDrive can sometimes cause the error 0x80070185 to occur. We recommend users temporarily turn off firewalls to see if they’re causing this issue. You can turn off the Windows Defender Firewall with the following steps:

1. Click the**Search** box or a magnifying glass icon on your Windows taskbar.
2. Input**Windows Defender Firewall** to find the applet.
3. Select the**Windows Defender Firewall** search result to view the applet in the Control Panel.
4. Click**Turn Windows Defender Firewall on or off** to access the settings.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-defender-firewall-applet.jpg)
5. Select the two**Turn off Windows Defender Firewall** network settings, and click**OK** to apply.  
![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-windows-defender-firewall-option.jpg)
6. Return to OneDrive to see if the 0x80070185 error persists with the firewall off.

 It’s also recommended to turn off any third-party firewalls installed. Some antivirus utilities also have firewalls. If you’ve installed any additional security software, select the option to disable its firewall if it has one.

 Should this potential solution resolve error 0x80070185, set up a firewall exception for OneDrive. You can do that for the Windows firewall as instructed in our [how to allow apps through Windows Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) piece. Users with third-party firewalls can allow OneDrive through them with the exclusion settings in their security apps.

## 7\. Reinstall OneDrive

 Reinstalling OneDrive is a solution that’s worked for some users. This will give you a completely fresh and up-to-date OneDrive app. These are the steps for uninstalling and reinstalling OneDrive:

1. Launch Run (see [how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for instructions) and input**ms-settings:appsfeatures** inside its**Open** box.
2. Select**OK** to view Apps & features in Settings.
3. If you’re using Windows 11’s Settings app, click OneDrive’s three-menu button and click**Uninstall** . You can select OneDrive and press**Uninstall** in Windows 10.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-option.jpg)
4. Select**Uninstall** for confirmation.
5. Open the [OneDrive page on the Microsoft Store](https://apps.microsoft.com/store/detail/onedrive/9WZDNCRFJ1P3?hl=en-gb&gl=gb) .
6. Click OneDrive’s**Get in Store** button.
7. Select**Open Microsoft Store** to view the OneDrive page in that app.  
![The Get button for OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-button-for-onedrive.jpg)
8. Click**Get** to reinstall OneDrive.

## Access your OneDrive Files again

 OneDrive’s error 0x80070185 is not always easy to fix. However, users have got error 0x80070185 resolved by applying the troubleshooting methods above. Hopefully, one of them will restore access to your affected OneDrive files as well.

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
<li><a href="https://win11.techidaily.com/overcoming-insufficient-rights-for-program-removal-in-win-11/"><u>Overcoming Insufficient Rights for Program Removal in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permission-barriers-in-windows-updates/"><u>Overcoming Permission Barriers in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-network-defenses-with-5-tweaks-to-firewall/"><u>Revitalizing Network Defenses with 5 Tweaks to Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-protection-enable-windows-11s-controlling-access/"><u>Setting Up Protection: Enable Windows 11’S Controlling Access</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-out-windows-11-drag-and-drop-issues/"><u>Smooth Out Windows 11 Drag-and-Drop Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-directx-update-failure-in-windows-systems/"><u>Overcoming DirectX Update Failure in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hidden-wi-fi-in-the-realm-of-windows-11/"><u>Resurrecting Hidden Wi-Fi in the Realm of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-ascertaining-your-pcs-intel-core-gen/"><u>Techniques for Ascertaining Your PC's Intel Core Gen</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-gaps-in-systems-startup-list/"><u>Troubleshooting Gaps in System's Startup List</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-tale-of-htc-vive-and-total-immersion/"><u>[Updated] The Ultimate Tale of HTC Vive and Total Immersion</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-couldnt-load-page-in-windows-marketplace/"><u>Troubleshooting 'Couldn't Load Page' In Windows Marketplace</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-chuckle-away-with-premium-complimentary-meme-templates/"><u>In 2024, Chuckle Away with Premium Complimentary Meme Templates</u></a></li>
<li><a href="https://win11.techidaily.com/turning-off-google-chrome-alerts-windows-edition/"><u>Turning Off Google Chrome Alerts, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-inaccessible-pin-unlock-routine-in-windows-11/"><u>Resetting Inaccessible Pin Unlock Routine in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-initial-load-issues-in-lol/"><u>Overcoming Initial Load Issues in LOL</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-connection-speed-clearing-steam-dns-in-windows/"><u>Revamping Connection Speed: Clearing Steam DNS in Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-video-editing-software-similar-to-virtualdub-features-and-pricing/"><u>New Video Editing Software Similar to VirtualDub Features and Pricing</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-auto-opens-on-microsofts-marketplace-app/"><u>Ceasing Auto-Opens on Microsoft's Marketplace App</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-craft-an-invisible-taskbar-on-windows-11/"><u>Steps to Craft an Invisible Taskbar on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fresh-windows-11-setup/"><u>Mastering Fresh Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-void-seven-strategies-for-stabilizing-obs-studio-link/"><u>Avoiding the Void: Seven Strategies for Stabilizing OBS Studio Link</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-technique-for-mkv-to-mp4-change/"><u>Step-by-Step Windows Technique for MKV to MP4 Change</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-file-navigation-on-windows-implementing-movecopy-actions/"><u>Optimizing File Navigation on Windows: Implementing 'Move'/'Copy' Actions</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-installation-mishaps-on-windows-10-and-11/"><u>Repairing Installation Mishaps on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/compreenas-a-solution-for-xbox-app-failure-error-0x80073d26/"><u>Compreenas a Solution for Xbox App Failure: Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-local-drive-space-in-win11-without-loss-of-files-max-156-chars/"><u>Securely Manage Local Drive Space in Win11 Without Loss of Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/merrymaking-with-gifted-windows-apps-on-xmas-day/"><u>Merrymaking with Gifted Windows Apps on Xmas Day</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-honor-magic5-ultimate-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Honor Magic5 Ultimate Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-discord-search-on-windowed-devices/"><u>Optimizing Discord Search on Windowed Devices</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-hardware-requirements-for-games/"><u>Resolving Windows Hardware Requirements for Games</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-vivo-x100-pro-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Vivo X100 Pro Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-window-bar-transparency-in-win11/"><u>A Step-by-Step for Window Bar Transparency in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-chroma-keying-mastery-advanced-fcp-x-tutorials-for-professionals/"><u>New Chroma Keying Mastery Advanced FCP X Tutorials for Professionals</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-mastering-the-samsung-s10s9-voice-recording-feature-a-step-by-step-guide/"><u>In 2024, Mastering the Samsung S10/S9 Voice Recording Feature A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-virtual-boxs-capabilities-with-v70-on-windows-11-systems/"><u>Maximize Virtual Box's Capabilities with v7.0 on Windows 11 Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-insiders-guide-to-ultimate-audio-equipment/"><u>In 2024, The Insider's Guide to Ultimate Audio Equipment</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-insights-into-average-gain-from-each-watched-online-content/"><u>2024 Approved  Insights Into Average Gain From Each Watched Online Content</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-xpatch-issues-error-0x80073712/"><u>Navigating Through XPatch Issues: Error 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winerror-740-resolving-operation-needs-promotion-in-windows-os/"><u>Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-expert-tips-for-youtube-short-pitfall-prevention/"><u>In 2024, Expert Tips for YouTube Short Pitfall Prevention</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-google-pixel-8-pro-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Google Pixel 8 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-bluetooth-device-unable-to-use-buttons-or-mute/"><u>Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-reveal-the-vocalization-of-a-wolveshow/"><u>Updated In 2024, Reveal the Vocalization of a Wolveshow</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-gear-use-windows-widgets-for-efficiency/"><u>Streamlining Your Gear Use: Windows Widgets for Efficiency</u></a></li>
</ul></div>
