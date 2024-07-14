---
title: Addressing Remote Desktop Failures in Current Windows
date: 2024-07-13T10:33:51.039Z
updated: 2024-07-14T10:33:51.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Remote Desktop Failures in Current Windows
excerpt: This Article Describes Addressing Remote Desktop Failures in Current Windows
keywords: Win RDP Issues,Windows DPCR Troubleshoot,RDP Connection Fixes,Redoing Remote Deskts,Windows Remote Failure,Resolve RDP Errors,Stable Window RDS
thumbnail: https://thmb.techidaily.com/ac86b0aa564fee722115c20830e542db073002bfbdd584be2acd66419238b8a6.png
---

## Addressing Remote Desktop Failures in Current Windows

 Many users utilize the Remote Desktop Connection app included with Windows to connect with remote PCs. However, some users have reported a Remote Desktop Connection error message that says, “An internal error has occurred.” Consequently, they can’t connect to remote PCs with RDC when that error occurs.

 This error means RDC’s Remote Desktop Protocol can’t establish a server connection with the remote PC selected. Does the “internal error has occurred” error message pop up when you try to connect to another computer with Remote Desktop Connection? If it does, this is how you can resolve that RDP issue in Windows 10 and 11.

## 1\. Select the "Allow Remote Connections" Setting

 First, check the basic settings required for remote connections are enabled. The**Allow the remote connection** setting needs to be enabled on the host computer (the remote one you’re trying to connect to). This is how you can select the**Allow remote connection** setting in Windows 10 and 11:

1. Click the search box or button (the magnifying glass icon) that’s on the Windows taskbar.
2. Type**advanced system settings** inside the search box.
3. Select**View advanced system settings** to bring a System Properties window.
4. Click the System Properties window’s**Remote** tab.
5. Enable remote assistance by selecting the**Allow Remote Assistance** checkbox.
6. Select the**Allow Remote connections** **to this computer** radio button if that feature is not enabled.  
![The Allow remote connections option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-tab.jpg)
7. Click**Apply** and**OK** to save the new remote connection settings.

 If you don’t see the**Allow connections only from computers** option, that probably means the Windows platform isn’t a Pro or Enterprise edition. You can only enable remote connections on host computers with Windows Pro and Enterprise. However, you can still connect to host PCs with Windows Home client PCs.

## 2\. Disable Network Layer Authentication

 There’s an **Allow connections only from computers running Remote Desktop with Network Level Authentication** setting just below the**Allow Remote connection** radio button. Selecting that option implements tighter Network Layer Authentication security for remote connections. However, some users confirm that disabling NLA by unticking that checkbox can fix the “internal error has occurred” error. So, deselect that option if you’ve got it selected.

## 3\. Start or Restart the Remote Desktop Connection Service

 Remote Desktop Services is a service needed for connecting to remote PCs. So, it could be the case you need to fix the “internal error has occurred” error because that service isn’t enabled on your PC. This is how you can start the Remote Desktop Services in Windows 11/10:

1. Open the search utility for finding files and apps in Windows 11/10.
2. Enter**Services** within Windows’ search box and select to open that app from there.
3. Double-click**Remote Desktop Services** to access some configuration settings for that service.  
![The Remote Desktop Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/services-window.jpg)
4. If disabled, select**Automatic** on the**Startup** drop-down menu for Remote Desktop Services.
5. Click**Start** (inside the properties window) to run Remote Desktop Services.  
![The Remote Desktop Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-desktop-services-service.jpg)
6. Select**Apply** to set the new service options.
7. Then you can exit the window by clicking**OK** or**X** .
8. If Remote Desktop Services is already running, you can try restarting it instead. Right-click**Remote Desktop Services** to view its context menu and select**Restart** from there.

## 4\. Select the "Reconnect if the Connection Is Dropped" Setting

 Some Remote Desktop Connection users have confirmed that selecting a**Reconnect if the connection is dropped** setting in that app can resolve this error. That simple potential resolution is certainly worth a try. You can select that**Reconnect** setting like this:

1. Start the RDC app with a method in our [how-to open Remote Desktop Connection guide](http://www.makeuseof.com/windows-11-open-remote-desktop-connection/) .
2. Click**Show Options** to view RDC’s settings.  
![The Remote Desktop Connections app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-desktop-connections.jpg)
3. Select the**Experience** tab.  
![The Experience tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/experience-tab.jpg)
4. Then select the**Reconnect if the connection is dropped** checkbox.
5. Press the**Connect** button.

## 5\. Set an Automatic DNS Server

 If you’ve set a specific DNS server on your PC, change to an automatic DNS server instead. There could be an issue with the DNS server you’ve set. You can set an automatic DNS server like this:

1. Open Run (press the**Win + R** hotkey or see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) ) and enter**ncpa.cpl** in that command box.
2. Click**OK** to view the Network Connections applet.
3. Right-click the internet connection to select its**Properties** context menu option.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option-1.jpg)
4. Select**Internet Protocol Version 4** and click**Properties** .
5. Then click**Obtain DNS server automatically** radio button.  
![The Obtain DNS server radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/obtain-dns-server-option.jpg)
6. Also, click**Obtain an IP address automatically** if that option isn’t selected.
7. Select**OK** to confirm the new DNS and IP address settings.

## 6\. Enable the "Require Use of Specific Security Layer" Group Policy Setting

 Group Policy includes a**Require use of specific security layer policy** setting. Enabling an RDP security layer with that policy might fix the “internal error has occurred” error for some users. To do so, set the**Require use of specific security layer** policy setting as follows:

1. Open Local Group Policy Editor with a method in our guide on [how to launch gpedit.msc](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) guide. If you're using Windows Home, be sure to check out [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Next, you’ll need to double-click**Computer Configuration** \>**Administrative Templates** in the Group Policy’s sidebar.
3. Double-click**Windows Components** \>**Remote Desktop Services** \>**Remote Desktop Session Host** in the console tree.
4. Click**Security** to view its policy settings.
5. Double-click the **Require use of specific security layer for remote (RDP) connections** policy.  
![The Security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-policies.jpg)
6. Select the**Enabled** radio button for that policy.
7. Choose**RDP** in the**Security Layer** drop-down menu.  
![The Security Layer RDP option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/rdp-option.jpg)
8. Click**Apply** \>**OK** inside the**Require use of specific security layer** for remote (RDP) connections policy window.
9. Restart Windows and then open the Remote Desktop Connection app to check if that fixes the issue.

## 7\. Turn Off UDP on the Client via Group Policy

 Users have also confirmed they fixed the “internal error has occurred” issue by enabling a**Turn off UDP** **on Client** policy setting. This is how you can enable that policy setting.

1. Start Group Policy Editor and go to this policy setting location:  
`Computer Configuration\Admin Templates\Windows Components\Remote Desktop Services\Remote Desktop Connection Client`
2. Then double-click**Turn off UDP on Client** on the right side of Group Policy Editor.  
![The Security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-policies.jpg)
3. Select that policy’s**Enabled** option.  
![The Turn Off UDP On Client window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-udp-client-window.jpg)
4. Click**Apply** to set the new**Turn off UDP** on Client policy.
5. Select**OK** in the**Turn off UDP on Client** window and exit Group Policy Editor.

## 8\. Disconnect a Domain Account

 Is your PC connected with a domain (work or school) account? If so, that domain account could be causing the remote connection issue. Try disconnecting a domain account like this:

1. Press**Win + I** to open Settings.
2. Then select the**Accounts** tab or category.
3. Click**Access work or school** to view connected domain accounts.  
![Domain account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/access-work-or-school-accounts.jpg)
4. Select**Disconnect** for a domain account.
5. Press your Start menu’s**Restart** button.
6. Then try connecting to the remote computer with RDC again.

## 9\. Turn Off Any Active VPNs

 VPNs that route connections to different servers can also cause the “internal error has occurred” issue to arise. If you’re utilizing a VPN, at least try temporarily disabling it. This is how you can turn off a VPN in Settings:

1. Open the Windows Settings app to select**Network & internet** .
2. Click the**VPN** navigation option or tab.  
![The VPN navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/vpn-navigation-option.jpg)
3. Select your VPN’s**Disconnect** option.  
![Domain account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/access-work-or-school-accounts.jpg)

## Re-establish Remote PC Access on Windows

 Those potential fixes for the “internal error has occurred” issue will probably re-establish remote PC access in most cases. The issue is often caused by RDP security, network, or remote connection setting configurations that many of the above solutions will address. So, those potential resolutions are certainly worth a try.

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
<li><a href="https://win11.techidaily.com/5-fun-tricks-you-can-do-in-command-prompt/"><u>5 Fun Tricks You Can Do in Command Prompt</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-oppo-reno-10-pro-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Oppo Reno 10 Pro 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719351823246-fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-ultimate-guide-to-fb-timing-and-free-tools/"><u>In 2024, The Ultimate Guide to FB Timing & Free Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-microphone-experience-with-win-11s-voice-shortcuts/"><u>Accelerate Your Microphone Experience with Win 11'S Voice Shortcuts</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-social-scoop-twitters-trending-talks/"><u>[New] In 2024, Social Scoop  Twitter’s Trending Talks</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-iscsi-initiator/"><u>A Comprehensive Look at Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-essential-windows-saver-techniques/"><u>A Guide to Essential Windows Saver Techniques</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-visual-communication-video-creation-techniques-in-windows-10/"><u>2024 Approved  The Art of Visual Communication  Video Creation Techniques in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-windows-11-shortcuts/"><u>A Step-by-Step Approach to Windows 11 Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-google-drive-not-syncing-on-windows/"><u>7 Ways to Fix Google Drive Not Syncing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719322467309-troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes!</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-unexpected-tiktok-rewind-recover-lost-posts-easily/"><u>2024 Approved  Unexpected TikTok Rewind – Recover Lost Posts Easily?</u></a></li>
<li><a href="https://win11.techidaily.com/27-tips-for-personalizing-your-windows-11-experience/"><u>27 Tips for Personalizing Your Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-entering-and-exiting-terminals-zen-space/"><u>A Step-by-Step Breakdown of Entering & Exiting Terminal's Zen Space</u></a></li>
<li><a href="https://win11.techidaily.com/1719347016533-unlock-your-computers-print-command-solutions-for-faulty-wwinplusp-operations/"><u>Unlock Your Computer's Print Command: Solutions for Faulty WWin+P Operations.</u></a></li>
<li><a href="https://win11.techidaily.com/1719364992381-unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now!</u></a></li>
<li><a href="https://win11.techidaily.com/9-updated-w11-key-enhancements-unveiled-by-recent-patch/"><u>9 Updated W11: Key Enhancements Unveiled by Recent Patch</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-tier-reddit-discussions-a-list-of-the-ten-greatest/"><u>[Updated] Top Tier Reddit Discussions - A List of the Ten Greatest</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-5-best-dvd-creators-on-mac-os/"><u>In 2024, 5 Best DVD Creators on Mac OS</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/5-tips-for-opening-windows-help-and-support-promptly/"><u>5 Tips for Opening Windows Help and Support Promptly</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-personalized-typing-mastering-keybinding-w11/"><u>A Window Into Personalized Typing: Mastering Keybinding W11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/text-animations-unleashed-try-these-14-dynamic-showcases/"><u>Text Animations Unleashed  Try These 14 Dynamic Showcases</u></a></li>
<li><a href="https://win11.techidaily.com/1719347210677-access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings.</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-ensuring-authenticity-and-compliance-in-your-tiktoks/"><u>[New] Ensuring Authenticity & Compliance in Your TikToks</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-look-at-windows-11-efficiency-mastering-processes-and-customizing-themes/"><u>A Deeper Look at Windows 11 Efficiency: Mastering Processes and Customizing Themes</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-from-snap-to-cinema-mastering-vertical-aspect-ratio-on-your-phone/"><u>Updated In 2024, From Snap to Cinema Mastering Vertical Aspect Ratio on Your Phone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-digital-rights-unexpected-content-take-downs/"><u>[Updated] In 2024, Digital Rights  Unexpected Content Take-Downs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-bringing-youtube-to-life-on-google-slides/"><u>[Updated] In 2024, Bringing YouTube to Life on Google Slides</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-exploring-soft-cessation-of-audio-tracks-with-audacity-for-2024/"><u>[New] Exploring Soft Cessation of Audio Tracks with Audacity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-keyboard-shortcuts-not-working-in-windows/"><u>9 Ways to Fix Keyboard Shortcuts Not Working in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/22h2-windows-fixes-for-recurring-issues/"><u>22H2 Windows Fixes for Recurring Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-fast-setup-moving-media-from-pc-to-your-iphone/"><u>In 2024, Fast Setup  Moving Media From PC To Your iPhone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-mastering-sound-clarity-a-guide-to-eliminating-ambient-sounds-in-filmora-for-2024/"><u>New Mastering Sound Clarity A Guide to Eliminating Ambient Sounds in Filmora for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-strategies-to-solve-vmware-booting-woes-on-win11/"><u>8 Strategies to Solve VMware Booting Woes on Win11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-tale-weavers-hub-hall-of-fame-picks/"><u>[Updated] Tale Weavers Hub - Hall of Fame Picks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-ace-your-online-presence-youtubes-studio-command-center-for-2024/"><u>[New] Ace Your Online Presence  YouTube's Studio Command Center for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-policy-settings-with-windows-11-expertise/"><u>Accelerate Policy Settings with Windows 11 Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-discrepancies-in-to-do-app/"><u>A Comprehensive Guide to Fixing Discrepancies in To-Do App</u></a></li>
<li><a href="https://win11.techidaily.com/4-keys-to-reviving-a-device-stuck-in-night-setting/"><u>4 Keys to Reviving a Device Stuck in Night Setting</u></a></li>
<li><a href="https://win11.techidaily.com/1719334307866-skip-wsl-save-time/"><u>Skip WSL, Save Time</u></a></li>
<li><a href="https://win11.techidaily.com/1719347165719-restore-order-in-your-keyboard-chaos-with-these-9-fixes-for-broken-windows-shortcuts-and-combinations/"><u>Restore Order in Your Keyboard Chaos with These 9 Fixes for Broken Windows Shortcuts and Combinations.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/posting-tweets-with-vids-check-the-aspect-ratio/"><u>Posting Tweets with Vids? Check the Aspect Ratio</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-solving-directdraw-mistakes/"><u>A Step-by-Step Approach to Solving DirectDraw Mistakes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-examine-recorded-conversation/"><u>[Updated] 2024 Approved  Examine Recorded Conversation</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-secret-behind-successful-igtv-uploads-from-h-videos/"><u>[Updated] In 2024, The Secret Behind Successful IGTV Uploads From H-Videos</u></a></li>
<li><a href="https://win11.techidaily.com/6-android-apps-perfect-for-a-windows-11-enthusiast/"><u>6 Android Apps Perfect for a Windows 11 Enthusiast</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-zte-nubia-z60-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-blueprint-of-dynamic-dialogue-in-scripts/"><u>[Updated] The Blueprint of Dynamic Dialogue in Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/9-proven-remedies-for-perfectly-printing-your-powerpoint-presentations-in-windows/"><u>9 Proven Remedies for Perfectly Printing Your PowerPoint Presentations in Windows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-master-class-on-cutting-unwanted-backdrops/"><u>2024 Approved  Master Class on Cutting Unwanted Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-winning-website-conversion/"><u>A Step-by-Step for Winning Website Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-desktop-window-managers-high-gpu-usage-on-windows-11/"><u>7 Ways to Fix the Desktop Window Manager's High GPU Usage on Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-unlocking-the-meaning-behind-tiktoks-pfp-emoji/"><u>[New] Unlocking the Meaning Behind TikTok's PFP Emoji</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-xiaomi-redmi-k70-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Xiaomi Redmi K70 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
</ul></div>
