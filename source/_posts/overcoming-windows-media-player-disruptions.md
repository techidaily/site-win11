---
title: Overcoming Windows Media Player Disruptions
date: 2024-07-13T10:24:55.989Z
updated: 2024-07-14T10:24:55.989Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Media Player Disruptions
excerpt: This Article Describes Overcoming Windows Media Player Disruptions
keywords: Fix WMPlayer Glitches,Stop WMP Crashes,Mend Media Player Errors,Resolve WMP Issues,End Windows Media Troubles,Stop WMPlayer Freezing,Prevent Media Disruptions
thumbnail: https://thmb.techidaily.com/8b677f86d933a2dc57f7b5d236aa4e6146da7e283f8be4d58f50e47e9bc2eba3.jpg
---

## Overcoming Windows Media Player Disruptions

 Windows Media Player is old software, but many users still utilize it for playing music and video. However, some WMP users have reported a “server execution failed” error message pops up when they try to play media files in Windows Media Player. Consequently, users can’t listen to music or watch videos in Windows Media Player.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.

## 1\. Try Restarting the Windows Media Player Process

 Some WMP users have confirmed that ending the Windows Media Player process in Task Manager can fix the “Server execution failed” error. That’s a very simple potential resolution that amounts to little more than restarting the software, albeit via Task Manager. You can end the Windows Media Player process in Task Manager like this:

1. Open Task Manager by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** key combination for launching that utility.
2. Click **Processes** to view that tab if it doesn’t open with Task Manager.
3. Select the **Windows Media Player** process in Task Manager.  
![The Processes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-process-tab.jpg)
4. Press the **End task** button to terminate the selected WMP process.
5. Then exit Task Manager and open Windows Media Player to see if the error persists.

## 2\. Run the Video Playback Troubleshooter

 Windows 11 and 10 both include a Video Playback troubleshooter that might be useful for resolving the “Server execution failed” error. That’s a troubleshooter for resolving video playback issues, and some users have said it helped them fix this issue. These are the steps for running the Video Playback troubleshooting tool:

1. First, [bring up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) the quick way by holding the **Windows** logo key and pressing **I**.
2. Then select **System** and the **Troubleshoot** navigation option included within that tab.
3. Click **Other trouble-shooters** to proceed to a list of troubleshooting utilities.
4. Open the Video Playback troubleshooter by clicking its **Run** option.  
![The Run button for the Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-video-playback-troubleshooter.jpg)
5. Select **I want to continue** **with this troubleshooter** in Video Playback.  
![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/video-playback-troubleshooter.jpg)
6. Apply any possible fixes the Video Playback troubleshooter offers.

 To utilize the same Video Playback troubleshooter in Windows 10, select the Update & Security settings category. Then you can reach the Video Playback repair utility by selecting **Troubleshoo**t > **Additional troubleshooters**. Select Video Playback and click **Run the troubleshooter**.

## 3\. Register DLL Files

 Registering the jscript and vbscript DLL files is a widely confirmed fix for the “Server execution failed” error. You can register those files by executing a couple of simple regsvr commands like this:

1. [Open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=In%20the%20Run%20dialog%20box,Command%20Prompt%20with%20administrative%20privileges.) to utilize that app with elevated privileges.
2. Then input this regsvr command and hit **Enter**: regsvr32 jscript.dll  
![The regsvr32 jscript.dll](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsvr32-command.jpg)
3. Click **OK** on RegSvr32 confirmation box.
4. Next, execute this command to register the VBScript file: regsvr32 vbscript.dll  
![The regsvr32 vbscript.dll command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsver32-vbscript-command.jpg)
5. Then select **OK** again.
6. Go to your Start menu and select **Restart** from there.

## 4\. Disable the Windows Media Player Network Sharing Service

 Windows Media Player Network Sharing is a service required for sharing WMP libraries via the UPnP protocol. That’s not a service needed for playing media files on one PC, and some WMP users have fixed the “Server execution failed” error by disabling that service. This is how you can disable that service:

1. Click on the taskbar’s magnifying glass icon or search box.
2. Enter a **services** keyword to find the app that matches that search phrase.
3. Run Services by clicking that app within your search results.
4. Double-click **Windows Media Player Network Sharing** to access that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-window2.jpg)
5. Select the **Disabled** option on the **Startup** menu.  
![The Disabled option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-disabled-option.jpg)
6. Click **Stop** just below the **Startup type** menu.
7. Select **Apply** \> **OK** to save settings and exit the Windows Media Player Network Sharing Service Properties window.

## 5\. Apply Full Access to Your Local User Folder

 Another possibility is that Windows Media Player can’t access media files in your user folder because of permission changes. Re-establishing full access to your local user folder will resolve such an issue. These are the steps for applying full access to a user folder:

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and go to the following folder path:  
`C:\Users`
2. Right-click your user folder that includes media files and select **Properties**.  
![The Properties context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option.jpg)
3. Select **Security** on the properties window.
4. Click **Advanced** to bring up more security settings.
5. Next, click the **Change** option for the owner.  
![The Advanced Security Settings for Users window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/advanced-security-window.jpg)

1. Click **Advanced** \> **Find now** on the Select User or Group window.
2. Then choose your user account from there and click **OK** twice.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/select-user-or-group.jpg)
3. Press **Add** on the Advanced Security Settings window.
4. Click **Select a Principal** to bring up a user group selection window.
5. Select your user account again, as covered in steps six and seven.
6. Click the **Full control** checkbox to select that basic permission setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-full-control-option.jpg)
7. Select **OK** on the Permissions Entry window and others open.

## 6\. Disable Third-Party Startup Items

 Disabling all third-party startup items (apps and services) is called clean booting. The purpose of clean booting is to prevent software conflicts by stopping third-party background programs and services from starting automatically. This troubleshooting method is recommended to check if a third-party app or service conflict with Windows Media Player is causing the “Server execution failed” error on your PC.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-tab-in-msconfig.jpg)

 Our guide to [clean-booting Windows](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to apply this potential fix by disabling third-party apps and services with Task Manager and MSConfig. When you’ve done that, you’ll need to restart your PC open for a clean boot to take effect. Then open Windows Media Player and try playing some media files again.

## 7\. Reinstall Windows Media Player

 Reinstalling Windows Media Player is a last resort potential resolution to try if none of the above works for you. However, you can’t reinstall WMP like regular software by uninstalling with Programs and Features and downloading a setup file. Instead, you’ll need to disable and re-enable WMP via Windows Features as follows:

1. Bring up the Windows uninstaller tool with a method within this article about [how to open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/).
2. Then click **Turn Windows features on or off** to bring up a utility for enabling/disabling features.  
![Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/programs-and-features-window.jpg)
3. Double-click Media Features to extend it.
4. Deselect the **Windows Media Player** checkbox and select **Yes**.  
![The Windows Media Player checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-windows-media-player-checkbox.jpg)
5. Click **OK** to disable Windows Media Player.
6. Restart Windows after disabling WMP.
7. Then reopen the Windows Features window.
8. Select the **Windows Media Player** checkbox.
9. Click **OK** to reinstall the software.

## Enjoy Your Music and Videos in Windows Media Player

 Many WMP users have fixed the “Server execution failed” error with the potential solutions outlined in this guide. So, don’t ditch Windows Media Player until you’ve at least tried applying most of those potential fixes. One will probably get the “Server execution failed” WMP error fixed on your Windows PC. Then you can enjoy all the music and videos in your Windows Media Player playlists again.

 Nevertheless, there are still plenty of freely available alternatives to Windows Media Player you can always consider. Software like VLC, 5KPlayer, and KMPlayer are among the best freeware media players for Windows.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/transforming-esd-format-to-compatible-windows-isos/"><u>Transforming ESD Format to Compatible Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-fixing-search-service-disruptions/"><u>Understanding and Fixing Search Service Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/easy-fixes-for-common-win-printer-issues/"><u>Easy Fixes for Common Win-Printer Issues</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-troubleshooting-freezing-spotify-app-on-windows-11/"><u>Tips for Troubleshooting Freezing Spotify App on Windows 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ips-for-stellar-video-conclusions-for-2024/"><u>[New] Tips for Stellar Video Conclusions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-users-handbook-on-amplifying-mouse-cursor-lighting-on-win-11/"><u>A User's Handbook on Amplifying Mouse Cursor Lighting on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/correction-of-errors-in-organization-managed-windows-11-settings/"><u>Correction of Errors in Organization-Managed Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-shared-access-tools-google-vs-microsofts-nearby-sharing/"><u>Assessing Shared Access Tools: Google Vs. Microsoft's Nearby Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visual-appeal-with-custom-pointer-design/"><u>Enhancing Visual Appeal with Custom Pointer Design</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-audio-configuration-for-spatiality/"><u>Windows 11 Audio Configuration for Spatiality</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-x-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone X?</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-ms-office-erase-error-code-0x80041015/"><u>Unlocking Windows MS Office: Erase Error Code 0X80041015</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-honor-x9a-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Honor X9a | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-a-sleeker-system-auto-delete-files-on-windows/"><u>The Key to a Sleeker System: Auto-Delete Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-repeated-sign-in-alerts-team-collaboration-edition/"><u>Avoiding Repeated Sign-In Alerts: Team Collaboration Edition</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-speaker-breakdown-latest-models/"><u>2024 Approved  Speaker Breakdown  Latest Models</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-emotions-easy-emoji-15-integration-for-win11/"><u>Avoid Missed Emotions: Easy Emoji 15 Integration for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-file-error-xc10100bf/"><u>Addressing Windows File Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dual-users-conflict-with-one-ms-login/"><u>Bypassing Dual Users’ Conflict with One MS Login</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/steps-to-acquire-free-picture-frame-videos-for-2024/"><u>Steps to Acquire Free Picture Frame Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-winning-streak-with-fps-techniques/"><u>Elevating Your Winning Streak with FPS Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-your-printer-fast-windows-fixes/"><u>Turbocharge Your Printer: Fast Windows Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/the-easy-guide-to-opening-iis-explorer/"><u>The Easy Guide to Opening IIS Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-overlooked-duo-of-windows-monitoring-metrics/"><u>The Overlooked Duo of Windows Monitoring Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-dual-camera-request-error-code-0xa00f4243/"><u>Dealing with Dual Camera Request Error (Code 0xA00F4243)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-preserving-profile-prestige-from-pretend-popularity-pitfalls-for-2024/"><u>[New] Preserving Profile Prestige From Pretend Popularity Pitfalls for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-top-10-premium-audio-editors-for-pcs-and-macs-beyond-audacity/"><u>Updated Top 10 Premium Audio Editors for PCs and Macs Beyond Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-breakdown-an-insiders-approach/"><u>Blue Screen Breakdown: An Insider's Approach</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-contacts-on-iphone-14-pro-4-methods-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Restore Contacts on iPhone 14 Pro (4 Methods) | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/the-quintessential-4-password-sentinels-of-windows-11-era/"><u>The Quintessential 4 Password Sentinels of Windows 11 Era</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-edit-mp4-files-with-ease-best-windows-8-video-editor-for-2024/"><u>Updated Edit MP4 Files with Ease Best Windows 8 Video Editor for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/full-guide-to-unlock-iphone-8-with-itunes-by-drfone-ios/"><u>Full Guide to Unlock iPhone 8 with iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-managing-setup-host-cpu-use/"><u>Efficiently Managing Setup Host CPU Use</u></a></li>
<li><a href="https://win11.techidaily.com/win11-audit-steps-for-default-user-permission-reset/"><u>Win11 Audit: Steps for Default User Permission Reset</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-another-users-ms-error-on-pc/"><u>Troubleshooting: Another User's MS Error on PC</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/a-brief-review-of-capcut-translate-with-alternative/"><u>A Brief Review of CapCut Translate With Alternative</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/adobe-premiere-rush-not-meeting-your-needs-explore-these-top-4-alternatives/"><u>Adobe Premiere Rush Not Meeting Your Needs? Explore These Top 4 Alternatives</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-samsung-galaxy-a15-5g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Samsung Galaxy A15 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-discovering-and-perfecting-your-individual-style-for-2024/"><u>[Updated] Discovering & Perfecting Your Individual Style for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-transitional-soundscapes-in-cubase/"><u>[Updated] Crafting Transitional Soundscapes in Cubase</u></a></li>
</ul></div>
