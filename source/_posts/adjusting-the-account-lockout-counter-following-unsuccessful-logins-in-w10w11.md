---
title: Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11
date: 2024-07-13T11:17:04.303Z
updated: 2024-07-14T11:17:04.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11
excerpt: This Article Describes Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11
keywords: Windows Login Limit Adjustment,Account Lockout Management (Win10),Win11 Unauthorized Access Control,Failed Logins Security Measures,Lockout Counter Tuning W10/W11,Resetting Login Attempts Windows,Enhancing Account Protection WS20
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-booting-mechanics-and-settings/"><u>Delving Deep Into Windows' Booting Mechanics and Settings</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-local-data-exchange-protocols-google-and-windows-showdown/"><u>Comparing Local Data Exchange Protocols: Google & Windows Showdown</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-discover-your-rhythm-assembling-tailored-youtube-playlists-for-the-digital-age-webmobile/"><u>2024 Approved  Discover Your Rhythm  Assembling Tailored YouTube Playlists for the Digital Age (Web/Mobile)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-chroma-key-techniques-in-live-broadcasts/"><u>[Updated] Mastering Chroma Key Techniques in Live Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/learn-win-11s-network-proxy-configuration/"><u>Learn Win 11'S Network Proxy Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-to-windows-11s-auto-hdr-techniques/"><u>Essential Guide to Windows 11'S Auto HDR Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-cr2-photos-to-jpeg-format/"><u>Windows Guide: Converting CR2 Photos to JPEG Format</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-languages-on-demand-through-windows-keyboard-shortcuts/"><u>Mastery of Languages on Demand Through Windows Keyboard Shortcuts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-harmonizing-photo-and-video-in-one-iphone-session/"><u>In 2024, Harmonizing Photo & Video in One iPhone Session</u></a></li>
<li><a href="https://win11.techidaily.com/3-keyways-to-refresh-file-explorer-in-win1011/"><u>3 Keyways to Refresh File Explorer in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/essential-guide-to-screen-capturing-on-hp-devices-for-2024/"><u>Essential Guide to Screen Capturing on HP Devices for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/mastering-iphone-hdr-imaging-techniques-for-2024/"><u>Mastering iPhone HDR Imaging Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-ultimate-remedies-for-a-disconnected-usb-wi-fi-adapter-in-windows/"><u>7 Ultimate Remedies for a Disconnected USB Wi-Fi Adapter in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-microsofts-innovative-ai-integration-for-windows-11-taskbar/"><u>Accelerating Workflow: Microsoft's Innovative AI Integration for Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/curated-list-best-weather-trackers-for-w10w11/"><u>Curated List: Best Weather Trackers for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-end-non-registered-user-sessions-on-windows-11/"><u>A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-elitepixel-recorder-winos-series/"><u>In 2024, ElitePixel Recorder WinOS Series</u></a></li>
<li><a href="https://win11.techidaily.com/wintime-discrepents-resolved/"><u>WinTime Discrepents Resolved</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-unchanged-environment-powertoys-settings-replication/"><u>Ensuring Unchanged Environment: PowerToys Settings Replication</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-upgrades-techniques-for-ensuring-optional-components-on-windows-os/"><u>Optimal Upgrades: Techniques for Ensuring Optional Components on Windows OS</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-oppo-f25-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-nokia-c02-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-drawing-on-windows-desktop/"><u>Elevate Your Workspace: Drawing on Windows Desktop</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-comparing-real-time-audio-changes-our-reliable-review-of-the-top-tools/"><u>Updated Comparing Real-Time Audio Changes Our Reliable Review of the Top Tools</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-vm-picks-to-enhance-your-windows-11-experience/"><u>Ideal VM Picks to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-chromebooks-voice-alteration-guide-the-leading-online-text-to-speech-apps/"><u>[Updated] Chromebook's Voice Alteration Guide  The Leading Online Text-to-Speech Apps</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/a-comprehensive-guide-to-video-and-subtitle-translation-with-veedio-for-2024/"><u>A Comprehensive Guide to Video and Subtitle Translation with Veed.io for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/basics-on-windows-exepe-files-an-overview/"><u>Basics on Windows EXE/PE Files: An Overview</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-windows-taskmanager-on-top-techniques/"><u>Mastery Over Windows: TaskManager on Top Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-power-spike-issues-during-multiplayer-adventures/"><u>Fixing Power Spike Issues During Multiplayer Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/a-primer-on-locating-and-navigating-components-management-console/"><u>A Primer on Locating & Navigating Components Management Console</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-mic-silenced-tips-to-unmute-for-google-meet-on-pc/"><u>Microsoft Mic Silenced: Tips to Unmute for Google Meet on PC</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-systray-information-showcasing-cpu-and-ram-in-ui/"><u>Elevate SysTray Information: Showcasing CPU & RAM in UI</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-the-windows-11-taskbars-search-icon/"><u>Concealing the Windows 11 Taskbar's Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-smooth-operational-flow-for-wsl-after-win-11s-installation/"><u>Ensuring a Smooth Operational Flow for WSL After Win 11'S Installation</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-poco-x6-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Poco X6 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-value-minimize-expenses-on-w11-pro-upgrade/"><u>Maximize Value, Minimize Expenses on W11 Pro Upgrade</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/easy-voice-cutting-a-comprehensive-audacity-resource/"><u>Easy Voice Cutting A Comprehensive Audacity Resource</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-recording-with-precision-perfecting-ios-device-features-on-youtube/"><u>[New] Recording with Precision  Perfecting iOS Device Features on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reinstate-missing-mfc71udll-in-windows/"><u>How to Reinstate Missing Mfc71u.dll in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/betrayed-by-touch-the-latest-vulnerabilities-in-windows-fingerprint-tech/"><u>Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-building-a-thriving-igtv-following-the-ultimate-guide/"><u>2024 Approved  Building a Thriving IGTV Following  The Ultimate Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transforming-windows-photos-viewer-with-creative-filter-settings-and-soundscape-for-2024/"><u>Transforming Windows Photos Viewer with Creative Filter Settings & Soundscape for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-crafting-a-holiday-ambiance/"><u>Windows 11: Crafting a Holiday Ambiance</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-essential-guide-to-transferring-tunes-across-platforms/"><u>[Updated] The Essential Guide to Transferring Tunes Across Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-safety-blocks-set-by-high-ranking-admins/"><u>Easing Windows Safety Blocks Set By High-Ranking Admins</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-integrating-video-conferencing-mastering-skypes-screen-sharing-functionality-for-2024/"><u>[New] Integrating Video Conferencing  Mastering Skype's Screen Sharing Functionality for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-geforce-x0001-failure-codes-in-windows-devices/"><u>Overcoming GeForce X0001 Failure Codes in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-apples-messaging-on-your-windows-machine/"><u>Embracing Apple's Messaging on Your Windows Machine</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-quick-setup-for-smartphones-as-personalized-vr-headsets/"><u>The Quick Setup for Smartphones as Personalized VR Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-windows-11-to-suit-your-auditory-preferences/"><u>Configure Your Windows 11 to Suit Your Auditory Preferences</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-securing-your-scene-minimize-camera-jostle/"><u>[Updated] Securing Your Scene  Minimize Camera Jostle</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-converting-text-to-mp3-insider-secrets-for-maximum-impact/"><u>In 2024, Converting Text to MP3 Insider Secrets for Maximum Impact</u></a></li>
<li><a href="https://win11.techidaily.com/from-windows-to-kali-an-installation-journey/"><u>From Windows to Kali: An Installation Journey</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-poco-x6-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Poco X6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-incorrectly-assigned-speaker-error-windows-style/"><u>Fixing Incorrectly Assigned Speaker Error, Windows Style</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/light-up-your-media-select-5-excellent-apps/"><u>Light Up Your Media  Select 5 Excellent Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-live-and-learn-twitter-video-chronicles-of-23/"><u>[Updated] In 2024, Live and Learn  Twitter Video Chronicles of '23</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-errors-wows-glitches-in-windows-11/"><u>Navigating Through Errors: WoW's Glitches in Windows 11</u></a></li>
</ul></div>
