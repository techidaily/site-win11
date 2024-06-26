---
title: The Ultimate Guide to PowerShell Security Controls
date: 2024-06-25T11:33:46.649Z
updated: 2024-06-26T11:33:46.649Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to PowerShell Security Controls
excerpt: This Article Describes The Ultimate Guide to PowerShell Security Controls
keywords: PowerShell Secure,Secure Scripting,Controlled PowerShell,Secure Shell Guide,PowerShell Safety,Protective PS Tools,Guidelines for Security
thumbnail: https://thmb.techidaily.com/a04f09fd3f332adf9ea1d2c4b6687272d88f08a364f88560f34c633d621d6cbc.jpg
---

## The Ultimate Guide to PowerShell Security Controls

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
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-skyrocketing-your-workflow-with-windows-apps/"><u>The Ultimate Guide to Skyrocketing Your Workflow with Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-network-access-for-chrome-amidst-windows-security-barriers/"><u>Enabling Network Access for Chrome Amidst Windows Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/time-travel-in-tech-flipping-old-games-with-dosbox-x/"><u>Time Travel in Tech: Flipping Old Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-control-your-network-storage-on-windows-11/"><u>Navigate and Control Your Network Storage on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-disabling-error-0xc00000f-on-pc/"><u>Solutions for Disabling Error 0Xc00000f on PC</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/3-methods-to-shorten-windows-11-boot-time-effectively/"><u>3 Methods to Shorten Windows 11 Boot Time Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-desktop-trash-bin-for-permanently-deleting-files-on-windows-11-and-11/"><u>How to Add a Desktop Trash Bin for Permanently Deleting Files on Windows 11 & 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-dive-into-discoworld-our-top-10-theme-picks/"><u>[New] In 2024, Dive Into DiscoWorld - Our Top 10 Theme Picks</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-beyond-premiere-top-10-video-editing-software-alternatives-for-beginners-and-pros/"><u>New In 2024, Beyond Premiere Top 10 Video Editing Software Alternatives for Beginners and Pros</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-8-iphone-video-production-secrets-for-high-quality-shoots/"><u>In 2024, Top 8 iPhone Video Production Secrets for High-Quality Shoots</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-a-compreenasional-approach-to-earning-through-vimeos-revenue-systems/"><u>[New] In 2024, A Compreenasional Approach to Earning Through Vimeo's Revenue Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-resounding-videos-a-tutorial-on-instagrams-musical-integration/"><u>2024 Approved  Resounding Videos  A Tutorial on Instagram's Musical Integration</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-edit-like-a-pro-top-10-free-mp4-video-editors-you-need-for-2024/"><u>New Edit Like a Pro Top 10 Free MP4 Video Editors You Need for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/12-leading-audio-converters-which-one-is-right-for-you/"><u>12 Leading Audio Converters Which One Is Right for You?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-discover-the-top-hand-drawing-whiteboard-animation-creators/"><u>2024 Approved Discover the Top Hand Drawing Whiteboard Animation Creators</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-direct-connection-navigating-desktop-display-integration-on-facebook/"><u>[Updated] Direct Connection  Navigating Desktop Display Integration on Facebook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/bridging-the-media-gap-coordinating-vids-on-twitter-and-tumblr-for-2024/"><u>Bridging the Media Gap  Coordinating Vids on Twitter & Tumblr for 2024</u></a></li>
</ul></div>
