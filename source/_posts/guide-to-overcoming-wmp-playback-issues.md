---
title: Guide to Overcoming WMP Playback Issues
date: 2024-06-25T10:32:22.838Z
updated: 2024-06-26T10:32:22.838Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Overcoming WMP Playback Issues
excerpt: This Article Describes Guide to Overcoming WMP Playback Issues
keywords: Fix WMP Errors Guide,Resolve Media Player Problems,Troubleshoot WMP Playback,Overcome Audio Glitches,Streaming Media Issue Solver,Remedy Video Format Hurdles,Unblock Sound Disruptions
thumbnail: https://thmb.techidaily.com/53ddbe6924d2ddfb268e4678d76937abc181d4038a95a53ae70246e54e37c443.jpg
---

## Guide to Overcoming WMP Playback Issues

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-to-fix-the-repairing-disk-errors-issue-on-windows/"><u>How to Fix the Repairing Disk Errors Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-null-space-in-your-system-drive/"><u>Step-by-Step Guide: Removing Null Space in Your System Drive</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-disabling-of-windows-11-alerts/"><u>Speedy Disabling of Windows 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/organize-like-a-pro-5-must-try-windows-folder-tricks/"><u>Organize Like a Pro: 5 Must-Try Windows Folder Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/correction-procedure-for-windows-error-0xca00a009/"><u>Correction Procedure for Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-blank-login-screen-in-windows-11-and-11/"><u>How to Fix a Blank Login Screen in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-java-functionality-after-failed-installation/"><u>Restoring Java Functionality After Failed Installation</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-hidden-notifications-on-desktops/"><u>Recovering Hidden Notifications on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/nine-strategies-for-precise-pdf-conversions-from-powerpoint-windows/"><u>Nine Strategies for Precise PDF Conversions From PowerPoint Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-oppo-a78-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Oppo A78 Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-everything-about-facebook-live-split-screen-you-should-know/"><u>[Updated] In 2024, Everything About Facebook Live Split Screen You Should Know</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-dance-the-viral-dance-mix-in-some-tiktok-flavor-for-insta-success-for-2024/"><u>[Updated] Dance the Viral Dance  Mix in Some TikTok Flavor for Insta Success for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-honor-magic-6-by-drfone-android/"><u>In 2024, How to Bypass FRP on Honor Magic 6?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-titlegenius-revolutionizing-video-title-generation/"><u>2024 Approved  TitleGenius  Revolutionizing Video Title Generation</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-itel-p40-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Itel P40 Data? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-seamless-integration-of-fb-video-on-tv-screens/"><u>2024 Approved  Seamless Integration of Fb Video on TV Screens</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-infinix-smart-8-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Infinix Smart 8 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-the-convert-waters-10-tips-for-youtube-to-mp4mpeg/"><u>Navigating the Convert Waters  10 Tips for YouTube to MP4/MPEG</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>