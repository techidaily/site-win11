---
title: Deciphering and Rectifying Spotify's Code 4 Error
date: 2024-07-13T10:21:23.637Z
updated: 2024-07-14T10:21:23.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering and Rectifying Spotify's Code 4 Error
excerpt: This Article Describes Deciphering and Rectifying Spotify's Code 4 Error
keywords: Fixing Spotify Error 4,Solve Spotify Error 4,Troubleshooting Spotify Error 4,Resolving Spotify Code 4,Spotify Error 4 Guide,Overcome Spotify Error 4,Understanding Spotify Error 4
thumbnail: https://thmb.techidaily.com/dc576bce0a179ba7a635140f867e3e38f81d54c67172be73149cea5622762395.jpg
---

## Deciphering and Rectifying Spotify's Code 4 Error

 Spotify is one of the best Windows apps for streaming and downloading music. However, some Spotify users can’t stream and download music with that app because of error code 4\. Error code 4 is a Spotify connectivity issue with a message that says, “No internet connection detected.” Yet, users can usually still open and view websites when that issue arises.

 Users who need to fix error code 4 can’t utilize the Spotify app online. That means things like radio and streaming don’t work. This is how you can fix Spotify error code 4 on a Windows 10 or 11 PC.

## 1\. Run the Flush DNS Command

![The flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/flushdns-command.jpg)

 One confirmed solution for error code 4 is to flush the DNS cache. The DNS (Domain Name System) cache is a local storage repository of IP addresses on your PC. Your web browser retrieves DNS lookup data from that cache.

 Clearing the DNS cache will flush out and refresh its data. You can clear the DNS cache by running a flush DNS command in Command Prompt or Run. Check out our guide about [how to flush the DNS](https://www.makeuseof.com/flush-dns-cache-windows-11/) on Windows for further details about how to apply this solution.

## 2\. Select the HTTP Option in Spotify

 Spotify includes alternative proxy settings you can select to configure how that app connects with the Internet. Changing the proxy option to**HTTP** can reputedly resolve error code 4\. You can select the**HTTP** option in Spotify as follows:

1. Open your Spotify app.
2. Click the username button at the top of Spotify to view its menu.
3. Select**Settings** to view Spotify’s options.  
![The Settings menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-settings-option.jpg)
4. Click the**Proxy type** drop-down menu to select**HTTP** .  
![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to [changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

## 4\. Tweak the Registry

 Some Spotify users have confirmed tweaking a DWORD value in the registry resolved error 4 for them. Those users changed the EnableActiveProbing DWORD’s value, which was set to 0 (disabled) on their PCs. These are the steps for fixing error code 4 by editing the registry:

1. Press the search box’s**Win + S** hotkey.
2. To locate the Registry Editor, enter**regedit** inside the**Type here to search** box.
3. Select Registry Editor inside the search tool.
4. Next, click within the address bar at the top of Registry Editor to clear the current location in it.
5. Go to the Internet key by inputting the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet`
6. Then right-click the**EnableActiveProbing** DWORD and select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/modify-option.jpg)
7. If**EnableActiveProbing** is set to**0** , clear the**Value data** box. Then input**1** inside that data box.  
![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.

## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

 Our article about [setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to [disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about [allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

## 7\. Reinstall Spotify

 Reinstalling Spotify could resolve unknown reasons for error code 4 arising and will at least ensure you’re using the latest app version. However, note that reinstalling the app will wipe your Spotify playlists. Back up (export) any playlists you wish to keep so you can restore them. Then reinstall Spotify with the following steps:

1. Press the Start menu button and select**All apps** (in Windows 11).
2. Scroll down to the Spotify app on the Start menu.
3. Right-click Spotify and select**Uninstall** .  
![Spotify's Uninstall option on the Start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-start-menu-s-uninstall-option.jpg)
4. If you’ve installed the desktop Spotify app, Programs and Features will open from which you can select the software and click**Uninstall** . Users who’ve installed the UWP Spotify app can select**Uninstall** on a confirmation prompt.
5. Then open the [Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

## Enjoy Spotify Music Online Again

 There’s a very good chance at least one Windows troubleshooting method in this guide will resolve Spotify error code 4 on your PC. They’re user-confirmed fixes that address the most common reasons for error 4 arising. With that app connection issue sorted, you can then enjoy all the best online music and radio Spotify has to offer again.

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
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-elite-sound-polishing-programme-perfect-your-digital-storytelling/"><u>Updated 2024 Approved Elite Sound Polishing Programme Perfect Your Digital Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/instant-use-of-snipping-tool-on-modern-windows-os/"><u>Instant Use of Snipping Tool on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-ip-command-prompt-guide-for-pcs/"><u>Discover Your IP: Command Prompt Guide for PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/driving-income-through-youtube-shorts-crucial-elements-and-earnings-potential/"><u>Driving Income Through YouTube Shorts  Crucial Elements and Earnings Potential</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-snipit-try-these-top-tips-for-repairing/"><u>Trouble with SnipIt? Try These Top Tips for Repairing</u></a></li>
<li><a href="https://review-topics.techidaily.com/itel-p40plus-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Itel P40+ Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-transform-fb-video-tunes-to-mp3/"><u>[Updated] In 2024, Transform Fb Video Tunes to MP3</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tips-and-tricks-to-tell-if-your-apple-iphone-7-is-unlocked-by-drfone-ios/"><u>Tips And Tricks To Tell if Your Apple iPhone 7 Is Unlocked</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-reverse-an-accidental-tiktok-reload-quick-guide/"><u>[Updated] In 2024, Reverse an Accidental TikTok Reload – Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-anydesk-troubleshooting-in-windows/"><u>Essential Techniques: AnyDesk Troubleshooting in Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-vivo-v30-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Vivo V30 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/total-extraction-of-wsl-from-windows-11-screens/"><u>Total Extraction of WSL From Windows 11 Screens</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevating-brand-presence-a-guide-to-influencer-marketing-on-instagram/"><u>In 2024, Elevating Brand Presence  A Guide to Influencer Marketing on Instagram</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-the-best-no-cost-voice-change-tools-for-discord-a-review-guide/"><u>[Updated] 2024 Approved  The Best No-Cost Voice Change Tools for Discord - A Review Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-realme-11-5g-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Realme 11 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/top-8-video-editor-with-useful-masking-for-2024/"><u>Top 8 Video Editor with Useful Masking for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-windows-movie-maker-replacements-the-best-of-the-rest/"><u>2024 Approved Windows Movie Maker Replacements The Best of the Rest</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-rearranged-letters-in-windows-system/"><u>Eradicating Rearranged Letters in Windows System</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-poco-f5-pro-5g-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Poco F5 Pro 5G Phone Screen?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/critical-15-broadcast-websites/"><u>Critical 15 Broadcast Websites</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-8-top-motion-graphics-online-tools-for-your-inspiration/"><u>New 2024 Approved 8 Top Motion Graphics Online Tools for Your Inspiration</u></a></li>
<li><a href="https://win11.techidaily.com/clear-your-screen-clutter-advanced-window-organization-win11-and-10/"><u>Clear Your Screen Clutter: Advanced Window Organization (Win11 & 10)</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-productivity-with-top-6-windows-apps/"><u>Elevate Your Productivity with Top 6 Windows Apps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-the-ultimate-playbook-for-exceptional-obs-studio-content-for-2024/"><u>[New] The Ultimate Playbook for Exceptional OBS Studio Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-from-celluloid-to-screen-adapting-your-vids-for-ig/"><u>[New] 2024 Approved  From Celluloid to Screen  Adapting Your Vids for IG</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/essential-tips-for-keeping-up-with-tiktoks-new-wave/"><u>Essential Tips for Keeping Up with TikTok’s New Wave</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-hibernate-depression-in-windows/"><u>Combatting Hibernate Depression in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-windows-mobility-settings-quick-guide-win-11/"><u>Turn Off Windows Mobility Settings Quick Guide (Win 11)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-adding-emojis-in-youtube-discussions/"><u>[Updated] Adding Emojis in YouTube Discussions</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-key-games-for-every-sandbox-enthusiast/"><u>[New] In 2024, Key Games for Every Sandbox Enthusiast</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-becoming-part-of-the-global-community-your-guide-to-facebook/"><u>2024 Approved  Becoming Part of the Global Community  Your Guide to Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-vanished-panes-top-strategies-to-recover-off-screen-apps-on-win-10/"><u>Breathe Life Into Vanished Panes! Top Strategies to Recover Off-Screen Apps on Win 10</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-watching-wonders-amazon-primes-top-series-on-twitter/"><u>[New] Watching Wonders  Amazon Prime's Top Series on Twitter</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-free-discolinking-techniques-desktop-and-smartphone-edition/"><u>[New] In 2024, Free DiscoLinking Techniques  Desktop & Smartphone Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusion-how-to-handle-installation-hiccups-win11/"><u>Clearing Up Confusion: How to Handle Installation Hiccups (Win11)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-maccam-essentials-tips-and-tricks-recording-for-2024/"><u>[Updated] MacCam Essentials  Tips and Tricks Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-success-removing-0x800700e9-from-your-xbox-game-pass-windows-11-setup/"><u>Unlocking Success: Removing 0X800700E9 From Your Xbox Game Pass, Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-typing-speed-7-latency-fixes-revealed/"><u>Enhance Windows 11 Typing Speed: 7 Latency Fixes Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-beginners-guide-to-github-desktop-for-windows-users/"><u>A Compreenas Beginners Guide to GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-stream-like-a-pro-top-5-cams-revolutionizing-live-broadcasts-on-twitch-for-2024/"><u>[Updated] Stream Like a Pro  Top 5 Cams Revolutionizing Live Broadcasts on Twitch for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-powerful-tools-for-windows-users/"><u>Conjuring Powerful Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-restrictive-settings-from-steam-libraries-win-11/"><u>Eradicating Restrictive Settings From Steam Libraries Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-file-access-failures-in-windows/"><u>Correcting File Access Failures in Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-cross-platform-video-editing-made-easy-a-chromebook-users-guide/"><u>2024 Approved Cross-Platform Video Editing Made Easy A Chromebook Users Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-peace-sleep-functions-in-windows/"><u>Bringing Peace: Sleep Functions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-writable-html-in-email-settings/"><u>Addressing Windows 11' Writable HTML in Email Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-limit-windows-sonic-amplification/"><u>How To Limit Windows Sonic Amplification</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-prime-coverage-pro-iphone-plus-android-insta-covers-app/"><u>[Updated] Prime Coverage Pro  IPhone + Android Insta Covers App</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-precision-ditch-delays-top-fixes-for-bf2-players/"><u>Unleash Precision, Ditch Delays: Top Fixes for BF2 Players</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-speeding-up-your-instagram-video-watch-time/"><u>[New] Speeding Up Your Instagram Video Watch Time</u></a></li>
<li><a href="https://win11.techidaily.com/assigning-custom-codes-to-windows-software/"><u>Assigning Custom Codes to Windows Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-make-your-cash-flow-with-these-13-reddit-techniques-for-beginners/"><u>[Updated] Make Your Cash Flow with These 13 Reddit Techniques for Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-office-hours-the-top-5-task-boosting-tools-for-win-11/"><u>Elevate Your Office Hours: The Top 5 Task-Boosting Tools for Win 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-top-8-best-screen-recorders-with-no-lag/"><u>[Updated] 2024 Approved  Top 8 Best Screen Recorders with No Lag</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-corrupted-filesystems-in-windows-11/"><u>Correcting Corrupted Filesystems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/digging-into-drive-labels-c-and-d-unpacked/"><u>Digging Into Drive Labels: C & D Unpacked</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-window-11-apps-essential-tips/"><u>Fast-Track Window 11 Apps: Essential Tips</u></a></li>
</ul></div>
