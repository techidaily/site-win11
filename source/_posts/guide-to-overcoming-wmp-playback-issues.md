---
title: Guide to Overcoming WMP Playback Issues
date: 2024-07-13T10:41:36.421Z
updated: 2024-07-14T10:41:36.421Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/windows-networking-essentials-managing-arp-cache/"><u>Windows Networking Essentials: Managing ARP Cache</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-vivo-x-fold-2-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your Vivo X Fold 2 Device</u></a></li>
<li><a href="https://win11.techidaily.com/five-keys-to-a-streamlined-firewall-configuration/"><u>Five Keys to a Streamlined Firewall Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-advice-on-optimal-live-cricket-broadcast-watching/"><u>Expert Advice on Optimal Live Cricket Broadcast Watching</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-11-file-transfers-that-halt/"><u>How to Resolve Windows 11 File Transfers That Halt</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-copy-paste-with-predefined-text-in-w10w11/"><u>Efficient Copy-Paste with Predefined Text in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-impact-do-widgets-streamline-win-11s-usage/"><u>Assessing the Impact: Do Widgets Streamline Win 11'S Usage?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-finest-5-mp3-fusion-applications-to-enhance-your-macs-sound-quality-for-2024/"><u>Updated The Finest 5 MP3 Fusion Applications to Enhance Your Macs Sound Quality for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-floodproof-favorites-compiling-top-7-cameras-list-for-2024/"><u>[Updated] Floodproof Favorites  Compiling Top 7 Cameras List for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-insufficient-installation-authorization-errors/"><u>Addressing Insufficient Installation Authorization Errors</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-the-complete-starters-kit-for-podcast-edits-your-pathway-to-audio-excellence/"><u>Updated The Complete Starters Kit for Podcast Edits Your Pathway to Audio Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-insufficient-storage-warning-in-vmware-hosts/"><u>Dealing with Insufficient Storage Warning in VMware Hosts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-honor-80-pro-straight-screen-edition-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Honor 80 Pro Straight Screen Edition Phone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/real-world-impact-of-instagram-reels-10-things-you-should-know/"><u>Real-World Impact of Instagram Reels (10 Things You Should Know)</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-cause-behind-error-0x80370102-in-wsl-distribution/"><u>Unraveling the Cause Behind Error 0X80370102 in WSL Distribution</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-locate-vocal-noise-sample/"><u>Updated In 2024, Locate Vocal Noise Sample</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-variability-between-offline-and-online-windows-installation-processes/"><u>Delving Into Variability Between Offline and Online Windows Installation Processes</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-an-everlasting-trash-can-icon-for-windows-1011/"><u>Crafting an Everlasting Trash Can Icon for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-strategies-for-resolving-password-hash-misalignment-on-windows/"><u>Essential Strategies for Resolving Password Hash Misalignment on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ignoring-the-windows-lsa-protection-deactivation/"><u>Ignoring the Windows LSA Protection Deactivation</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-secure-free-footage-streaming-through-key-youtube-channels/"><u>In 2024, Secure Free Footage Streaming Through Key YouTube Channels</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/he-floor-with-optimal-posting-hours/"><u>Hit the Floor with Optimal Posting Hours</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-quieting-the-chaos-techniques-for-refining-and-purifying-digital-audio-online/"><u>New 2024 Approved Quieting the Chaos Techniques for Refining and Purifying Digital Audio Online</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/faster-teams-cleaner-systems-microsofts-pivot/"><u>Faster Teams, Cleaner Systems: Microsoft's Pivot</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-secrets-to-successful-tiktok-videos-via-mac-or-pc-for-2024/"><u>[Updated] Secrets to Successful TikTok Videos via MAC or PC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cleaning-slates-in-windows-the-3-reset-routes/"><u>Cleaning Slates in Windows: The 3 Reset Routes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/why-professionals-choose-final-cut-pro-over-express-for-2024/"><u>Why Professionals Choose Final Cut Pro Over Express for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-a-closed-captioning-guru-windows-10-insights/"><u>Becoming a Closed Captioning Guru: Windows 10 Insights</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-why-are-social-media-suggested-videos-evanescent-in-2024/"><u>[New] Why Are Social Media Suggested Videos Evanescent, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-console-collapse-avoiding-sudden-df-closures/"><u>Counteracting Console Collapse: Avoiding Sudden DF Closures</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-startup-item-disappearance/"><u>Identifying & Fixing Startup Item Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-ultimate-technique-for-capturing-time-on-iphone/"><u>2024 Approved  The Ultimate Technique for Capturing Time on iPhone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-engagement-amplify-audience-youtube-marketing-for-2024/"><u>Elevate Engagement, Amplify Audience (YouTube Marketing) for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-stay-updated-the-latest-on-changing-win11-walls/"><u>[Updated] Stay Updated  The Latest on Changing Win11 Walls</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719276552494-unlock-windows-free-up-space-no-more-temp-files/"><u>Unlock Windows Free Up Space, No More Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/winrars-file-consistency-fixing-summation-discrepancies/"><u>WinRAR's File Consistency: Fixing Summation Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-xc0000142-in-winoses/"><u>Addressing Error XC0000142 in WinOSes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msresourceappname-text-glitch-in-w11/"><u>Addressing 'MsResource/AppName Text' Glitch in W11</u></a></li>
</ul></div>
