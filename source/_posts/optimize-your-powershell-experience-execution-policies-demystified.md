---
title: "Optimize Your PowerShell Experience: Execution Policies Demystified"
date: 2024-07-13T10:41:48.247Z
updated: 2024-07-14T10:41:48.247Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Your PowerShell Experience: Execution Policies Demystified"
excerpt: "This Article Describes Optimize Your PowerShell Experience: Execution Policies Demystified"
keywords: PowerShell Optimization,Policy Execution Guide,Advanced PS Settings,Script Security Controls,Permission Management,Enhanced Execution PS,Secure Powershell Practices
thumbnail: https://thmb.techidaily.com/3c3e9aebd6b49c0af91473b8783124a08a04e227f020283ad8022a46d57974e6.jpg
---

## Optimize Your PowerShell Experience: Execution Policies Demystified

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
<li><a href="https://extra-tips.techidaily.com/timeless-classics-most-iconic-anime-openers/"><u>Timeless Classics  Most Iconic Anime Openers</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-ai-tools-in-windows/"><u>Efficient Installation of AI Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-reno-11-pro-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo Reno 11 Pro 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-microsoft-store-operation-on-windows-11/"><u>Unhindered Microsoft Store Operation on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-skype-or-discord-finding-your-ideal-chat-app/"><u>In 2024, Skype or Discord  Finding Your Ideal Chat App</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-the-comprehensive-resource-for-w11-enthusiasts/"><u>DevHome: The Comprehensive Resource for W11 Enthusiasts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-technique-to-effortlessly-install-win11-with-workstation-17/"><u>Unveiling the Technique to Effortlessly Install Win11 with Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/5-hacks-for-accessing-windows-repair-options/"><u>5 Hacks for Accessing Windows Repair Options</u></a></li>
<li><a href="https://win11.techidaily.com/usb-wi-fi-anomalies-on-windows-heres-the-solution-guide-you-need/"><u>USB Wi-Fi Anomalies on Windows? Here's the Solution Guide You Need</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-11s-app-collection/"><u>Unveiling the Secrets of Windows 11'S App Collection</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-samsung-galaxy-m14-4g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Samsung Galaxy M14 4G phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-bitlocker-here-are-4-steps-to-stay-secure/"><u>Windows Without Bitlocker? Here Are 4 Steps to Stay Secure</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-5-best-hd-hunting-recorders-reviewed/"><u>2024 Approved  5 Best HD Hunting Recorders Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-tell-if-your-pc-needs-restarting/"><u>5 Simple Ways to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-master-download-manager-facebook-and-firefox-edition-tools/"><u>[Updated] Master Download Manager  Facebook & FireFox Edition Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-navigating-the-zoom-interface-a-focus-on-windows-10/"><u>[Updated] Navigating the Zoom Interface  A Focus on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-for-exploring-windows-policy-settings/"><u>Three Methods for Exploring Windows Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-language-of-windows-updates/"><u>Decoding the Language of Windows Updates</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-how-to-change-your-voice-on-instagram/"><u>2024 Approved  How to Change Your Voice on Instagram?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-crafting-clearer-communication-the-art-of-adding-text-to-video-media/"><u>[Updated] 2024 Approved  Crafting Clearer Communication  The Art of Adding Text to Video Media</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stop-microsoft-teams-from-crashing-windows-1110/"><u>Steps to Stop Microsoft Teams From Crashing Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-persistent-ps4-controller-connections-in-windows/"><u>Strategies for Persistent PS4 Controller Connections in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-windows-users-generative-erase-wonders/"><u>Clean Slate for Windows Users: Generative Erase Wonders</u></a></li>
<li><a href="https://extra-resources.techidaily.com/trending-14-moving-text-design-illustrations/"><u>Trending 14 Moving Text Design Illustrations</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-low-usb-availability-windows-wise/"><u>Steps to Rectify Low USB Availability Windows-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-rectifying-windows-error-code-0x80040610/"><u>Swift Solutions for Rectifying Windows Error Code 0X80040610</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-linguistic-edge-influential-expressions-for-leaders/"><u>The Linguistic Edge  Influential Expressions for Leaders</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Tecno Spark 20 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-customizable-spotlight-picture-guide/"><u>Windows Customizable Spotlight Picture Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-hidden-gems-unlocking-full-potential/"><u>Windows 11'S Hidden Gems: Unlocking Full Potential</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-potential-of-openais-ai-for-voice-to-text-in-windows/"><u>Unlocking the Potential of OpenAI's AI for Voice-to-Text in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-the-footprints-of-your-latest-window-use/"><u>Tracing the Footprints of Your Latest Window Use</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-video-driver-crash-on-win1110/"><u>Addressing Video Driver Crash on Win11/10</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-your-apple-iphone-12-from-your-apple-id-by-drfone-ios/"><u>How To Unlink Your Apple iPhone 12 From Your Apple ID</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reopen-nvidia-control-panel-in-win-11/"><u>Steps to Reopen Nvidia Control Panel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/sync-chrome-and-pc-time-seamlessly-on-windows/"><u>Sync Chrome and PC Time Seamlessly on Windows</u></a></li>
</ul></div>
