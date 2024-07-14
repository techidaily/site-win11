---
title: Unblocking RDP Connection Issues in Modern OSes
date: 2024-07-13T10:13:42.196Z
updated: 2024-07-14T10:13:42.196Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unblocking RDP Connection Issues in Modern OSes
excerpt: This Article Describes Unblocking RDP Connection Issues in Modern OSes
keywords: Resolve RDP Glitches,Fix Remote Desktop Errors,Tackle RDP Connectivity,Unblock RDP Access,Solve OS-Based RDP Block,Clear RDP Disconnect Causes,Enhance RDP Windows Connection
thumbnail: https://thmb.techidaily.com/e7a938c8213dc5d370405bab4afa736e010a188d2f4d2dd7c34adab834ad1c13.jpg
---

## Unblocking RDP Connection Issues in Modern OSes

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
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-ultimate-guide-to-video-editing-on-your-phone-iphone-and-android-apps/"><u>New 2024 Approved The Ultimate Guide to Video Editing on Your Phone IPhone and Android Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-the-art-of-screen-enhancement-in-teams/"><u>[Updated] Mastering the Art of Screen Enhancement in Teams</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-time-whats-new-between-windows-10-and-11/"><u>Ahead of Time: What's New Between Windows 10 & 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-poco-c51-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Poco C51 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlined-process-for-upgrading-macos-sierra/"><u>2024 Approved  Streamlined Process for Upgrading macOS Sierra</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-pulsepundit-critique-of-live-performances/"><u>[Updated] 2024 Approved  PulsePundit  Critique of Live Performances</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-memory-shortage-in-the-magical-school-of-hogwarts-game/"><u>Addressing Memory Shortage in The Magical School of Hogwarts Game</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-blackout-in-widows-remote-desktop-connection/"><u>Addressing Blackout in Widows Remote Desktop Connection</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-loading-lag-quick-fix-for-lol-on-win/"><u>Avoid Loading Lag: Quick Fix for LOL on Win</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-crafting-pure-designs-erasing-backgrounds-with-canva-expertise/"><u>In 2024, Crafting Pure Designs  Erasing Backgrounds with Canva Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-transform-your-footage-top-rated-1080p-video-editing-software/"><u>2024 Approved Transform Your Footage Top-Rated 1080P Video Editing Software</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-management-application-hiccups/"><u>Avoid Windows Management Application Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sci-fis-virtual-quest-the-best-movies-to-discover-alien-universes/"><u>In 2024, Sci-Fi's Virtual Quest  The Best Movies to Discover Alien Universes</u></a></li>
<li><a href="https://win11.techidaily.com/age-friendly-features-in-pre-windows-10-systems/"><u>Age-Friendly Features in Pre-Windows 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-breaking-the-monotony-innovative-yt-playlist-shuffling/"><u>[Updated] In 2024, Breaking the Monotony  Innovative YT Playlist Shuffling</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-decoding-whatsapp-voice-communication/"><u>In 2024, Decoding WhatsApp Voice Communication</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-tecno-spark-20-pro-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-ultimate-mac-os-guide-for-screen-casting-for-2024/"><u>[Updated] The Ultimate Mac OS Guide for Screen Casting for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-call-failed-problems-in-windows-devices/"><u>Addressing 'Call Failed' Problems in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-sound-controls-in-windows-os/"><u>Addressing Faulty Sound Controls in Windows OS</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/integrating-tailored-thumbnails-in-your-videos/"><u>Integrating Tailored Thumbnails in Your Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/revived-adventure-monster-hunt-error-cleared/"><u>Revived Adventure: Monster Hunt Error Cleared</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-what-is-an-ai-avatar-for-2024/"><u>Updated What Is an AI Avatar for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/first-steps-in-youtube-profitability-starting-a-channel-and-revenue-streams-for-2024/"><u>First Steps in YouTube Profitability  Starting a Channel & Revenue Streams for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/navigating-the-world-of-audio-editing-with-garageband-for-2024/"><u>Navigating the World of Audio Editing with GarageBand for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-efficiency-strategies-for-effective-multitasking-with-windows-11/"><u>Amplify Efficiency: Strategies for Effective Multitasking with Windows 11</u></a></li>
</ul></div>
