---
title: Understanding and Effectively Utilizing PowerShell Policies
date: 2024-10-25T23:44:07.874Z
updated: 2024-10-27T09:33:27.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Effectively Utilizing PowerShell Policies
excerpt: This Article Describes Understanding and Effectively Utilizing PowerShell Policies
keywords: PowerShell Policy Guide,Implementing PS Policies,Secure Scripts with PS,Managing PS Security Basics,Policy Enforcement in PS,Optimizing PS Control,Effective PowerShell Governance
thumbnail: https://thmb.techidaily.com/8b36213cf3c4388b8515bed526f0d42f540b1ba9bd34731fb80416cf28c2a508.jpg
---

## Understanding and Effectively Utilizing PowerShell Policies

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-blue.techidaily.com/new-from-obscurity-to-influence-5-strategies-to-dominate-reddit-advertising/"><u>[New] From Obscurity to Influence 5 Strategies to Dominate Reddit Advertising</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-record-the-essence-of-your-facebook-page/"><u>[Updated] In 2024, Record the Essence of Your FACEbook Page</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-navigating-the-subreddit-landscape-a-step-by-step-approach/"><u>[Updated] Navigating the Subreddit Landscape A Step-by-Step Approach</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-ultimate-tutorial-simplifying-youtube-subscriptions/"><u>2024 Approved Ultimate Tutorial Simplifying YouTube Subscriptions</u></a></li>
<li><a href="https://win-blog.techidaily.com/crack-the-mystery-behind-call-of-duty-black-ops-cold-war-error-code-80070057/"><u>Crack the Mystery Behind Call of Duty: Black Ops Cold War Error Code 80070057</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/discover-the-top-six-power-of-being-bi-lingual/"><u>Discover the Top Six Power of Being Bi-Lingual</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-win11-with-a-custom-screensaver/"><u>Enhance Win11 with a Custom Screensaver</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-computer-experience-with-these-win11-god-mode-secrets/"><u>Enhance Your Computer Experience with These Win11 God Mode Secrets</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-vivo-v29-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Vivo V29 FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/lock-out-period-customization-in-windows-os/"><u>Lock Out Period Customization in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-virtual-memory-expansion-in-windows-11-updates/"><u>Mastering Virtual Memory Expansion in Windows 11 Updates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/movavi-m4a-ogv/"><u>Movavi 電影編碼轉換器 - 免費線上更改 M4A 成 OGV格式</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-experience-the-top-10-for-windows-11-display-controls/"><u>Optimize Your Experience: The Top 10 for Windows 11 Display Controls</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-power-schemes-after-loss-on-ws-11/"><u>Redefining Power Schemes After Loss on WS 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-smooth-operations-anydesk-and-win11-synergy/"><u>Restoring Smooth Operations: AnyDesk & Win11 Synergy</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/supercharge-online-performance-through-state-of-the-art-cookiebot-solutions/"><u>Supercharge Online Performance Through State-of-the-Art Cookiebot Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-lockout-timer-after-failed-windows-sign-in/"><u>Tailoring Lockout Timer After Failed Windows Sign-In</u></a></li>
<li><a href="https://technical-tips.techidaily.com/why-is-windows-11-search-malfunctioning-correct-it-with-proven-techniques/"><u>Why Is Windows 11 Search Malfunctioning? Correct It With Proven Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/winsplit-solutions-for-syncing-displays/"><u>WinSplit: Solutions for Syncing Displays</u></a></li>
</ul></div>

