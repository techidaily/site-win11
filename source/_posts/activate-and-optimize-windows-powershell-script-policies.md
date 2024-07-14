---
title: Activate and Optimize Windows PowerShell Script Policies
date: 2024-07-13T11:05:02.425Z
updated: 2024-07-14T11:05:02.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate and Optimize Windows PowerShell Script Policies
excerpt: This Article Describes Activate and Optimize Windows PowerShell Script Policies
keywords: PowerShell Policy Enable,PowerShell Policy Management,Windows Scripting PowerSave,PowerShell Optimization Techniques,Execute PowerShell Scripts,Windows Policy Configuration,Improve PowerShell Efficiency
thumbnail: https://thmb.techidaily.com/5e6778b56bd7ea57ea083d57b5f2921418b00d25e671abbc75a29215718a300d.jpg
---

## Activate and Optimize Windows PowerShell Script Policies

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
<li><a href="https://win11.techidaily.com/essential-tips-for-reading-qr-codes-on-windows-devices/"><u>Essential Tips for Reading QR Codes on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-learning-7-strategies-for-windows-users/"><u>Enhancing Learning: 7 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-5-ways-to-open-windows-help-hub/"><u>Enhance Accessibility: 5 Ways to Open Windows Help Hub</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-file-management-crafting-multitudes-of-subfolders-instantly/"><u>Conquer File Management: Crafting Multitudes of Subfolders Instantly</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-twists-that-tell-stories-mastering-the-art-and-technique-of-spinning-visuals-for-maximum-impact-on-social-media-platforms/"><u>In 2024, Twists That Tell Stories  Mastering the Art and Technique of Spinning Visuals for Maximum Impact on Social Media Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blocked-experience-in-roblox-addressing-account-restrictions/"><u>Fixing Blocked Experience in Roblox: Addressing Account Restrictions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/edge-of-insanity-the-10-most-chaotic-tiktok-contests-for-2024/"><u>Edge of Insanity  The 10 Most Chaotic TikTok Contests for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conducting-harmonious-auditory-performance-in-windows/"><u>Conducting Harmonious Auditory Performance in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-professional-audio-setup-unveiling-our-picks-for-6-excellent-mics/"><u>[New] Professional Audio Setup  Unveiling Our Picks for 6 Excellent Mics</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/navigating-the-path-to-customized-sound-audacity-for-voice-modification-for-2024/"><u>Navigating the Path to Customized Sound Audacity for Voice Modification for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/add-subtitles-to-videos-with-kapwing-step-by-step/"><u>Add Subtitles To Videos With Kapwing Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-ai-capabilities-at-ms-store/"><u>Delving Into AI Capabilities at MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-installation-of-arm-based-windows-11-from-iso/"><u>Mastering the Installation of ARM-Based Windows 11 From ISO</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-eye-catching-insta-highlights-unveiling-3-secrets/"><u>[New] Eye-Catching Insta Highlights  Unveiling 3 Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-absence-of-hypervisor-on-windows-sandbox/"><u>Identifying and Fixing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-quick-recording-keyboard-shortcut-tips-for-win-11/"><u>Mastering the Art of Quick Recording: Keyboard Shortcut Tips for Win 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-the-evolution-of-video-from-full-length-to-yt-shorts/"><u>[Updated] 2024 Approved  The Evolution of Video  From Full-Length to YT Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-image-display-windows-11-style/"><u>Maximizing Window Image Display: Windows 11 Style</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-dead-after-upgrading-graphics-card/"><u>Display Dead After Upgrading Graphics Card</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-launch-windows-11-access-control-panel/"><u>Locate and Launch Windows 11 Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/go-pure-with-linux-avoid-wsl/"><u>Go Pure with Linux - Avoid WSL</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/expert-techniques-for-changing-your-instagram-sound-for-2024/"><u>Expert Techniques for Changing Your Instagram Sound for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dual-screen-delight-personalized-pixels-per-monitor-of-windows-1011/"><u>Dual Screen Delight: Personalized Pixels per Monitor of Windows 10/11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-vloggers-ultimate-gear-list-17-100/"><u>[Updated] Vloggers' Ultimate Gear List #17-100</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prodigious-8-cameras-enhancing-video-quality-in-broadcast/"><u>In 2024, Prodigious 8 Cameras Enhancing Video Quality in Broadcast</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-a-celebs-brief-appearance-scrutiny/"><u>In 2024, A Celeb’s Brief Appearance Scrutiny</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unintentional-tiktok-update-restore-past-content/"><u>[Updated] In 2024, Unintentional TikTok Update – Restore Past Content</u></a></li>
</ul></div>
