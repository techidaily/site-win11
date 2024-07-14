---
title: "Activate Secure Windows Scripting: Navigating Execution Policies"
date: 2024-07-13T11:21:04.899Z
updated: 2024-07-14T11:21:04.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Activate Secure Windows Scripting: Navigating Execution Policies"
excerpt: "This Article Describes Activate Secure Windows Scripting: Navigating Execution Policies"
keywords: WScriptExecutionPolicy,SecurityWindowsScript,PolicyWindowsNavigate,ExecPOLockWindows,SecureScriptPolicies,NavigateExecutionLimits,ActivateScriptSecurity
thumbnail: https://thmb.techidaily.com/6404644d3e1ec95170f598da6ea66bbff597c34cc3f9580cc8d7755b3643dcab.png
---

## Activate Secure Windows Scripting: Navigating Execution Policies

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

 You can use a [PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.


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
<li><a href="https://win11.techidaily.com/high-res-quests-ultimate-guide-to-playing-adventures-in-hd-using-scummvm/"><u>High-Res Quests: Ultimate Guide to Playing Adventures in HD Using ScummVM</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-peak-performance-pcs-top-rated-screen-capture-tools-reviewed/"><u>[Updated] 2024 Approved  Peak Performance PCs  Top-Rated Screen Capture Tools Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-efficiency-essential-strategies-for-windows-11-users/"><u>Mastering Efficiency: Essential Strategies for Windows 11 Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-facebook-streaming-made-simple-tips-for-android-and-iphones/"><u>In 2024, Facebook Streaming Made Simple  Tips for Android & iPhones</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-vanishing-battery-time-indicator-in-windows-11/"><u>How to Fix the Vanishing Battery Time Indicator in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-evaluating-mr-beasts-financial-heft-for-2024/"><u>[Updated] Evaluating Mr. Beast's Financial Heft for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-new-browsing-potential-with-gesture-controls-in-microsoft-written-by-ai/"><u>Unlocking New Browsing Potential with Gesture Controls in Microsoft' Written by AI</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-open-source-enable-linux-subsystem-for-windows/"><u>Transition to Open Source: Enable Linux Subsystem for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-battery-status-notifications-on-windows-os/"><u>Enhancing Battery Status Notifications on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-streamlined-sea-filmmaking-techniques/"><u>[New] The Ultimate Guide to Streamlined Sea Filmmaking Techniques</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/make-your-videos-pop-12-top-online-animation-creators-for-2024/"><u>Make Your Videos Pop 12 Top Online Animation Creators for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-the-stagnation-of-ideas-in-contemporary-vr/"><u>2024 Approved  The Stagnation of Ideas in Contemporary VR</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-effortless-audio-silencing-an-audacity-users-manual/"><u>In 2024, Effortless Audio Silencing An Audacity Users Manual</u></a></li>
<li><a href="https://win11.techidaily.com/windows-define-custom-idle-timeframe/"><u>Windows: Define Custom Idle Timeframe</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/leading-tech-in-snap-capture-for-2024/"><u>Leading Tech in Snap Capture for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-youtube-snippets-for-captivating-ig-stories/"><u>[New] In 2024, YouTube Snippets for Captivating IG Stories</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-utilize-copy-features-with-edge-protector-win11/"><u>Methods to Utilize Copy Features with Edge Protector, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-external-monitor-not-responding-in-windows-os/"><u>Resolving External Monitor Not Responding in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remediation-for-elusive-obs-studio-issue-on-win-11-pcs/"><u>Swift Remediation for Elusive OBS Studio Issue on Win 11 PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-5-best-hd-hunting-cameras-reviewed/"><u>[Updated] 5 Best HD Hunting Cameras Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/re-enabling-razer-device-discovery-on-win1011/"><u>Re-Enabling Razer Device Discovery on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/typingpros-guide-to-swift-typing-using-typingaid/"><u>TypingPros Guide to Swift Typing Using TypingAid</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-acquiring-free-music-youtube-video-edition/"><u>[Updated] Acquiring Free Music  YouTube Video Edition</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-nubia-red-magic-8s-pro-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Nubia Red Magic 8S Pro Phone Pattern Lock</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-display-with-best-time-clock-screen-savers/"><u>Enhance PC Display with Best Time Clock Screen Savers</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-fixing-wi-fi-mouse-malfunctions-in-windows/"><u>Regain Control: Fixing Wi-Fi Mouse Malfunctions in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unleashing-facebooks-auto-play-feature-for-youtube-clips/"><u>[Updated] Unleashing Facebook's Auto-Play Feature for YouTube Clips</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-supercharge-your-tiktok-experience-mastery-of-the-speed-control-feature/"><u>[Updated] Supercharge Your TikTok Experience  Mastery of the Speed Control Feature</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-favorites-compiled-top-6-fb-lite-downloads/"><u>[Updated] In 2024, Favorites Compiled  #Top 6 FB Lite Downloads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-tecno-camon-30-pro-5g-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Tecno Camon 30 Pro 5G Activity | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-gateways-to-googles-advertising-on-youtube-platforms/"><u>[Updated] In 2024, Gateways to Google's Advertising on YouTube Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-teams-screen-share-issues-quick-fixes/"><u>Microsoft Teams Screen Share Issues: Quick Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-conceptualizing-and-realizing-a-podcast-rss-strategy/"><u>[Updated] Conceptualizing and Realizing a Podcast RSS Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/end-hibernation-hurdles-with-easy-fixes-for-win/"><u>End Hibernation Hurdles with Easy Fixes for Win</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-6-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 6 to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-snap-configurations-in-win-os/"><u>Crafting Unique Snap Configurations in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-usefulness-of-pagefilesys-backup-storage/"><u>Decoding Windows’ Usefulness of Pagefile.sys Backup Storage</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-essential-mac-tech-tips-5-snapshot-strategies/"><u>[New] In 2024, Essential Mac Tech Tips  5 Snapshot Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/steam-and-internet-connectivity-woes-on-pc-heres-a-fix/"><u>Steam & Internet Connectivity Woes on PC? Here's a Fix</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-cpu-temp-controls-on-windows-1011/"><u>Customizing CPU Temp Controls on Windows 10/11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-how-to-preserve-your-gameplay-for-future-replays/"><u>[Updated] In 2024, How to Preserve Your Gameplay for Future Replays</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-slow-mo-scenes-on-instagram-a-filmmakers-manual/"><u>2024 Approved  Slow-Mo Scenes on Instagram  A Filmmaker's Manual</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-poco-x5-pro-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Poco X5 Pro Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unyielding-security-seven-ways-to-shield-your-system/"><u>Unyielding Security: Seven Ways to Shield Your System</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-package-open-failures-in-win11win10-systems/"><u>Navigating Package Open Failures in Win11/Win10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Realme 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-hidden-pitfalls-investing-in-fraudulent-subscribers-for-2024/"><u>[New] Hidden Pitfalls  Investing in Fraudulent Subscribers for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-elite-7-film-downloader-apps-for-2024/"><u>[New] Elite 7 Film Downloader Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/finding-and-fixing-non-functional-delete-keys-on-windows/"><u>Finding and Fixing Non-Functional Delete Keys on Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-a-clearer-sight-youtube-watching-tweets-at-1080p/"><u>[Updated] 2024 Approved  A Clearer Sight  YouTube, Watching Tweets at 1080P</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-configuration-with-microsofts-pc-manager-on-w11/"><u>Conquer Configuration with Microsoft's PC Manager on W11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/prowess-in-color-correction-the-ultimate-11-tutorials-for-2024/"><u>Prowess in Color Correction  The Ultimate 11 Tutorials for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-free-chants-and-sounds-a-guide-to-peaceful-meditation-for-2024/"><u>Top Free Chants & Sounds  A Guide to Peaceful Meditation for 2024</u></a></li>
</ul></div>
