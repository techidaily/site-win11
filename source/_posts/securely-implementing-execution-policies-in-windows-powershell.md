---
title: Securely Implementing Execution Policies in Windows PowerShell
date: 2024-09-05T08:38:27.863Z
updated: 2024-09-06T08:38:27.863Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Implementing Execution Policies in Windows PowerShell
excerpt: This Article Describes Securely Implementing Execution Policies in Windows PowerShell
keywords: Secure PS Execution,ExecPol Setup Guide,PowerShell Security,ExecPolicy Enforcement,Safe Script Run,Implementing ExecPol,Windows PowerShell Safety
thumbnail: https://thmb.techidaily.com/69ee34b64cf92db1f2232edf38c3580f65ba5a6c1e5baa6cfa6ccd73ff711508.jpg
---

## Securely Implementing Execution Policies in Windows PowerShell

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

 You can use a[PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/024-approved-the-underappreciated-film-phenoms-of-this-year/"><u>[New] 2024 Approved  The Underappreciated Film Phenoms of This Year</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/xploring-the-finest-wedding-cinematography-youtube-and-vimeos-selection/"><u>[New] Exploring the Finest Wedding Cinematography - Youtube & Vimeo's Selection</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/remium-gaming-intro-ideas-for-youtube-free-vs-paid-models/"><u>[New] Premium Gaming Intro Ideas for YouTube  Free vs Paid Models</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-google-voice-calls-the-ultimate-guide/"><u>[Updated] 2024 Approved  Mastering Google Voice Calls  The Ultimate Guide</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-seamless-integration-12-stream-app-experience/"><u>[Updated] 2024 Approved  Seamless Integration  12 Stream App Experience</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-from-pc-to-smartphone-the-essential-guide-to-hulu-recording/"><u>[Updated] From PC to Smartphone  The Essential Guide to Hulu Recording</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-8-free-online-video-editors-for-youtube/"><u>[Updated] In 2024, 8 Free Online Video Editors for YouTube</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-minecrafts-oriental-elegance-6-top-ideas/"><u>[Updated] In 2024, Minecraft's Oriental Elegance  6 Top Ideas</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-leading-the-way-in-android-simulation-software-top-15-list/"><u>[Updated] Leading the Way in Android Simulation Software (Top 15 List)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-the-secrets-of-effective-free-youtube-video-transcriptions-revealed/"><u>2024 Approved  The Secrets of Effective, FREE YouTube Video Transcriptions Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-substitute-methods-for-the-ls-command-in-windows/"><u>Discovering Substitute Methods for the LS Command in Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/easy-installation-tutorial-configuring-auto-gpt-for-ubuntu-users/"><u>Easy Installation Tutorial: Configuring Auto-GPT for Ubuntu Users</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-listening-game-setup-of-win-1011s-atmos/"><u>Elevate Your Listening Game: Setup of Win 10/11'S Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/essential-adjustments-for-disabled-windows-defense/"><u>Essential Adjustments for Disabled Window's Defense</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-chromes-failed-virus-detected-error-on-windows/"><u>How to Fix Chrome's Failed - Virus Detected Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-bluetooth-speaker-volume-control-not-working-in-windows-11/"><u>How to Fix the Bluetooth Speaker Volume Control Not Working in Windows 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-initial-trial-ideal-accessories-to-boost-your-gopro-footage/"><u>In 2024, Initial Trial  Ideal Accessories to Boost Your GoPro Footage</u></a></li>
<li><a href="https://win11.techidaily.com/making-oculus-quest-compatible-with-windows-vr-systems/"><u>Making Oculus Quest Compatible with Windows VR Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-blue-screen-errors/"><u>Navigating Through the Maze of Blue Screen Errors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-systems-refusal-to-run-latest-windows-version/"><u>Overcoming System's Refusal to Run Latest Windows Version</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-update-issue-code-0x800f0845/"><u>Overcoming Update Issue: Code 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-search-service-error-on-pcs/"><u>Overcoming Windows Search Service Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wow-error-132-a-step-by-step-guide/"><u>Overcoming WoW Error #132: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/perfectly-pairing-words-and-images-emoji-15-in-win11/"><u>Perfectly Pairing Words and Images: Emoji 15 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/prime-fps-count-apps-to-enhance-your-win-11-gameplay/"><u>Prime FPS Count Apps to Enhance Your Win 11 Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-microphone-and-xbox-app-on-1011-pcs/"><u>Reconciling Microphone and Xbox App on 10/11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-programming-discrepancies-with-no-troubleshoot-tool/"><u>Resolve Programming Discrepancies with No Troubleshoot Tool</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-no-sound-issues-with-usb-headphones-on-a-windows-7-system-guide/"><u>Resolving No-Sound Issues with USB Headphones on a Windows 7 System [Guide]</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-paudio-quirks-on-wos-an-audacity-guide/"><u>Resolving PAudio Quirks on WOS: An Audacity Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-reset-lost-pin-after-a-software-glitch-in-windows-11/"><u>Solutions to Reset Lost PIN After a Software Glitch in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-printmanagement-msc-error-a-step-by-step-guide/"><u>Solving 'PrintManagement' MSC Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-deletions-with-customized-context-menus-in-windows/"><u>Speed up Deletions with Customized Context Menus in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-to-sync-music-from-ipod-with-itunes-and-pc-systems/"><u>Step-by-Step Guide to Sync Music From iPod with iTunes and PC Systems</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-cmd-appearance-without-prior-notice/"><u>Stopping CMD Appearance Without Prior Notice</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-unlock-device-driver-access-in-windows-11/"><u>Strategies to Unlock Device Driver Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-upgrades-with-windows-11-in-place-protocols/"><u>Streamlining Upgrades with Windows 11 In-Place Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-dism-failure-0x800f082f-with-ease/"><u>Tackling Windows' DISM Failure 0X800F082F with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-quiet-down-windows-hardware-keys/"><u>Tech Tip: Quiet Down Windows' Hardware Keys</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-eradicating-onedrive-from-explorer-window/"><u>Techniques for Eradicating OneDrive From Explorer Window</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-classy-rivalry-skagen-falster-2-vs-apples-mobile-monarchs-reviewed/"><u>The Classy Rivalry: Skagen Falster 2 Vs. Apple's Mobile Monarchs Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/the-ins-and-outs-of-socket-programming-with-python-servers-on-pcs/"><u>The Ins and Outs of Socket Programming with Python Servers on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-non-procreate-sketchers-for-pc-users/"><u>The Ultimate List of Non-Procreate Sketchers for PC Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-8-effective-conversations-starters-with-chatgpt-to-help-you-focus-and-boost-productivity/"><u>Top 8 Effective Conversations Starters with ChatGPT to Help You Focus and Boost Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-to-recover-lost-gpeditmsc-access/"><u>Unlocking Secrets to Recover Lost Gpedit.msc Access</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-nonexistent-device-alert-in-windows-11/"><u>Unraveling Nonexistent Device Alert in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-enigma-of-windows-security-errors/"><u>Unraveling the Enigma of Windows Security Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-windows-reawakened-swift-tips-for-win10-and-11-users/"><u>Unseen Windows Reawakened: Swift Tips for Win10 & 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-efficiency-pro-tips-for-scanning-qr-codes-via-windows/"><u>Unveiling Efficiency: Pro Tips for Scanning QR Codes via Windows</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-program-compatibility-troubleshooter-on-windows-11-and-how-do-you-use-it/"><u>What Is the Program Compatibility Troubleshooter on Windows 11, and How Do You Use It?</u></a></li>
<li><a href="https://win11.techidaily.com/why-isolating-audio-devices-may-be-a-windows-feature/"><u>Why Isolating Audio Devices May Be a Windows Feature?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-control-panel-hacks-usb-access-management/"><u>Windows Control Panel Hacks: USB Access Management</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-unveiling-their-differences/"><u>Windows Terminal & PowerShell: Unveiling Their Differences</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-not-written-memory-error-on-pc/"><u>Winning Over Not Written Memory Error on PC</u></a></li>
</ul></div>
