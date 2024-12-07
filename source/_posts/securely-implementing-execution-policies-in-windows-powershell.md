---
title: Securely Implementing Execution Policies in Windows PowerShell
date: 2024-12-05T08:53:14.987Z
updated: 2024-12-07T11:44:10.792Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-resources.techidaily.com/30plus-metaverse-quotes-to-inspire-you-include-ar-and-vr-for-2024/"><u>30+ Metaverse Quotes to Inspire You [Include AR & VR] for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/aif-to-flac-with-movavi/"><u>無料変換サービス：オンデマンドAIF to FLAC with Movavi ― 音質を維持したプロセス</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ring-the-best-visuals-in-vlogs-for-2024/"><u>Capturing the Best Visuals in Vlogs for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-samsung-galaxy-f34-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Samsung Galaxy F34 5G Phone Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-block-inadvertent-key-combinations-on-pc/"><u>How to Block Inadvertent Key Combinations on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resuscitate-your-unresponsive-windows-start-button/"><u>How to Resuscitate Your Unresponsive Windows Start Button</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/master-your-mobile-communications-skype-and-zoom-on-android/"><u>Master Your Mobile Communications Skype & Zoom on Android</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-mcuicntexe-not-found-problem-on-windows/"><u>Overcoming McUICnt.exe Not Found Problem on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/quelles-sont-les-methodes-faciles-pour-copier-et-sauvegarder-un-fichier-dvd-sur-windows-et-macos/"><u>Quelles Sont Les Méthodes Faciles Pour Copier Et Sauvegarder Un Fichier DVD Sur Windows Et macOS ?</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-dormant-office-outlook-alerts/"><u>Reactivating Dormant Office Outlook Alerts</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-when-your-torrent-fails-to-download-correctly/"><u>Solutions When Your Torrent Fails to Download Correctly</u></a></li>
<li><a href="https://blog-min.techidaily.com/ultimate-guide-to-quick-and-easy-dvd-extraction-leading-software-picks-for-windows-and-macos-users/"><u>Ultimate Guide to Quick and Easy DVD Extraction: Leading Software Picks for Windows & macOS Users</u></a></li>
<li><a href="https://win11.techidaily.com/uninstalling-wsl-entirely-on-windows-11-systems/"><u>Uninstalling WSL Entirely on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-full-ram-capacity-on-windows-systems/"><u>Unleashing Full RAM Capacity on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-perfect-way-to-clear-your-frozen-updates/"><u>Unraveling the Perfect Way to Clear Your Frozen Updates</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-traits-that-set-ai-devices-aside/"><u>Unveiling the Traits That Set AI Devices Aside</u></a></li>
</ul></div>

