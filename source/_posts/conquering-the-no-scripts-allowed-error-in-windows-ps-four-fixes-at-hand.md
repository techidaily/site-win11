---
title: "Conquering the 'No Scripts Allowed' Error in Windows PS: Four Fixes at Hand"
date: 2024-12-31T17:10:21.736Z
updated: 2025-01-06T19:46:35.772Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Conquering the 'No Scripts Allowed' Error in Windows PS: Four Fixes at Hand"
excerpt: "This Article Describes Conquering the 'No Scripts Allowed' Error in Windows PS: Four Fixes at Hand"
keywords: NoScriptsPSErrorFix,WindowsPSNoScriptsError,ConquerWindowsPSErrors,PSScriptsErrorSolution,PSErrorWinTroubleshoot,ErrorHandlingWindowsPS,FixingPSNoScriptsError
thumbnail: https://thmb.techidaily.com/0ef39d9a604e71499226be4f237e87d1b86c04c6f94c96b9949bbc0cc087d2d2.jpg
---

## Conquering the 'No Scripts Allowed' Error in Windows PS: Four Fixes at Hand

 You’re running some commands on PowerShell and suddenly see an error message that reads, “PowerShell cannot be loaded because running scripts is disabled on this system.”

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run PowerShell in Administrator Mode

 Are you currently running PowerShell without proper administrative rights? If so, then perhaps that’s where the issue lies.

 So, let’s explore the steps you should apply to run the tool in administrator mode:

1. Press **Win + X** to open the Quick Access menu.
2. Select the **Windows PowerShell (Admin)** option.

![Selecting the Windows PowerShell (Admin) option on the Quick Access Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/selecting-the-windows-powershell-admin-option-on-the-quick-access-menu.jpg)

 And if that doesn’t help, check out [the various ways to open Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/). But you should only focus on the methods that show you how to run the tool with administrative privileges.

## 2\. Change the Execution Policy in PowerShell

 In some instances, changing the execution policy could help. But before we explore the solutions, let’s first take you through what the execution policy is and how it works.

### What Is the Execution Policy, and How Does It Work?

 The execution policy is a security feature that controls the way you run PowerShell scripts on your device. It simply determines which types of scripts can be run and which ones should be avoided. The best part is that you can configure this policy to your liking.

 Here are the options you can pick from when configuring the execution policy:

* **Restricted**: This policy prohibits you from running any PowerShell script.
* **Unrestricted**: Allows you to run any script but shows you a warning message when you run suspicious scripts.
* **RemoteSigned**: This policy requires a digital signature when you run the scripts that you downloaded online. However, it doesn’t require a signature for local scripts.
* **ByPass**: This allows you to run any script without any restrictions. Unlike the "Unrestricted" policy, the "ByPass" policy won’t show you any warning messages when you run suspicious scripts. So, always apply this policy only when running legit scripts.
* **AllSigned**: This policy only runs scripts that are signed by a trusted publisher.

 Now, if you use PowerShell regularly, then you might want to change the execution policy from time to time. However, some execution policies might display error messages when you run your PowerShell scripts.

 For example, enabling the “Restricted,” “AllSigned,” or “RemoteSigned” policies might lead to error messages like the "running scripts is disabled" error.

 To resolve the problem, you'd simply have to change the execution policy to “Unrestricted” or “ByPass.” But that’s not all; you'd also need to decide how the policy should be implemented. For example, do you want to apply the policy for all users or just for your current PowerShell session?

 Let's explore all the additional [PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) you’ll have to add when changing the execution policy:

* **CurrentUser**: This policy will only be applied to all the PowerShell sessions of the person who has currently logged in on the device.
* **LocalMachine**: Applies to all the users that have an account on the device. This policy can only be configured by local users that have administrative privileges.
* **Process**: Only applies on the current PowerShell session. This means you’ll have to execute the policy again if you start a new session.
* **MachinePolicy**: This policy applies to all the users who have an account on your device. However, it can only be configured by network administrators who have appropriate permissions. But it's often possible for local administrators to configure this execution policy using the Local Group Policy Editor.
* **UserPolicy**: Applies to all PowerShell sessions and the scripts executed by a particular user.

 Now that everything is clear, let’s explore how you can execute the relevant policies to tackle the "PowerShell cannot load" issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How to Change the Execution Policy to "Unrestricted"

 The best way to tackle the issue at hand is to change the execution policy to "unrestricted." But before that, you need to check how each execution policy is configured.

 Here are the steps for checking how the execution policies are configured:

1. Press **Win + X** to open the Quick Access Menu.
2. Select **Windows PowerShell (Admin)** from the options.
3. Type the following command and press **Enter**:

`Get-ExecutionPolicy -List`

![Displaying the list of execution policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/displaying-the-list-of-execution-policies.jpg)

 This should show you how the execution policies are configured for different users and systems.

 To can change the execution policy to “Unrestricted” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

![Setting the execution policy on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/setting-the-execution-policy-on-powershell.jpg)

 To change the execution policy to “Unrestricted” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope LocalMachine`

 When you finish running the command, close PowerShell and restart your PC to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How to Change the Execution Policy to "ByPass"

 The "ByPass" execution policy will allow you to run any PowerShell script without a hassle. But remember that it might also allow you to run buggy files. So, always configure this execution policy only when running trustworthy PowerShell files.

 To change the execution policy to “ByPass” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope CurrentUser`

 And to change the execution policy to “ByPass” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope LocalMachine`

 When you finish, close PowerShell and then restart your device.

## 3\. Change the Execution Policy Via the Local Group Policy Editor

![A lady using a Windows PC while holding a cup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-a-Windows-PC-while-holding-a-cup.jpg)

 The Local Group Policy Editor (LGPE) also makes it easy for you to change the execution policy. In fact, this tool can also help you configure various system settings or troubleshoot tons of PC issues.

 Remember, the main aim is to change the execution policy such that you’ll be able to run your PowerShell scrips without a hassle. And by so doing, you’ll get rid of the “running scripts is disabled” error on PowerShell.

 Here’s how to change the execution policy in the LGPE:

1. Type **Edit group policy** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the LGPE](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell**.
3. Double-click on the **Turn on Script Execution** option.

![Clicking the Turn on Script Execution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-turn-on-script-execution-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Check the **Enabled** box. From there, click the **Execution Policy** drop-down menu and select **Allow local scripts and remote signed scripts**. This option is similar to the "RemoteSigned" option that we discovered earlier.

 If you want to run all scripts without restrictions, pick the **Allow all scripts** option from the "Execution Policy" drop-down menu.

 From there, click **Apply** and then click **OK** to save these changes.

## 4\. Change the Execution Policy Using the Registry Editor

![A lady using her Windows PC while sitting on bed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-her-Windows-PC-while-sitting-on-bed.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the other methods didn’t help, then try changing the execution policy using the Registry Editor. However, you need to be careful when editing Registry keys. If you tweak the wrong keys, then you might end up damaging your PC.

 Now, here’s how to change the execution policy via the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds\Microsoft.PowerShell`

 Locate the **ExecutionPolicy** value on the right-hand side.

![Selecting the ExecutionPolicy value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/selecting-the-executionpolicy-value.jpg)

 If the value is missing, create it through these steps:

1. Right-click on a blank space on the right-hand side.
2. Select **New > DWORD (32-bit) Value**.
3. Name the value as **ExecutionPolicy** and press **Enter**.

 Double-click on the **ExecutionPolicy** value. Next, type **RemoteSigned** in the "Value data" section. This will allow PowerShell to execute local and signed scripts.

 Alternatively, type **ByPass** in the "Value data" section. This will allow PowerShell to execute any script without limitations.

 After entering your preferred value in the "Value data" section, press **OK** to save the changes. Finally, close the Registry Editor and then restart your device.

## Run Your PowerShell Scripts Without Any Restrictions

 It can be quite frustrating when you suddenly can’t execute certain commands on Windows PowerShell. But if you come across the “scripts is disabled” error, the solutions we’ve covered should help.

 Now, does PowerShell often give you other issues? Well, there are more solutions that can help you out.

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-unleash-the-power-of-messaging-mastering-pinning-on-discord/"><u>[New] In 2024, Unleash the Power of Messaging Mastering Pinning on Discord</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-top-10-filmora-editing-traits-for-fan-loyalty-for-2024/"><u>[New] Top 10 Filmora Editing Traits for Fan Loyalty for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-the-perfect-playback-top-strategies-to-record-and-share-your-vr-experiences/"><u>[Updated] In 2024, The Perfect Playback Top Strategies to Record and Share Your VR Experiences</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-turn-off-youtube-preview-in-one-easy-step-guide/"><u>[Updated] Turn Off YouTube Preview in One Easy Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-common-windows-crash-codes-0xc0000001/"><u>Correcting Common Windows Crash Codes (0xC0000001)</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-webcam-activity-notifications-for-ws11-users/"><u>Enabling Webcam Activity Notifications for WS11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/enlarge-your-windows-11-pin-for-better-protection/"><u>Enlarge Your Windows 11 PIN for Better Protection</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-reinstall-non-operational-store-applications/"><u>Guides to Reinstall Non-Operational Store Applications</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/joining-forces-in-video-marketing-on-youtube/"><u>Joining Forces in Video Marketing on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-overcome-silent-microphone-on-pc-while-recording/"><u>Methods to Overcome Silent Microphone on PC While Recording</u></a></li>
<li><a href="https://fox-search.techidaily.com/unveiling-social-dynamics-in-china-analyzing-the-consequences-of-a-single-child-per-family-mandate-insights-from-yl-software/"><u>Unveiling Social Dynamics in China: Analyzing the Consequences of a Single Child Per Family Mandate – Insights From YL Software</u></a></li>
</ul></div>

