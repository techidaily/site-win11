---
title: Power Up with Enhanced Script Policy Management in Windows
date: 2024-10-01T21:53:58.751Z
updated: 2024-10-09T12:01:21.733Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Power Up with Enhanced Script Policy Management in Windows
excerpt: This Article Describes Power Up with Enhanced Script Policy Management in Windows
keywords: Power Script Policies,Windows Script Control,Boost Security Windows,Advanced Scripting,Optimize PC Settings,Enhance System Policy,Improve Script Efficacy
thumbnail: https://thmb.techidaily.com/cb7e01d77e11396989975642eff6b3a0f5621896796311364cd34b031c122e69.jpg
---

## Power Up with Enhanced Script Policy Management in Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-2024-approved-solo-spotlight-crafting-a-chart-topping-podcast/"><u>[New] 2024 Approved Solo Spotlight Crafting a Chart-Topping Podcast</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-guide-to-youtubes-latest-income-strategies/"><u>[Updated] 2024 Approved Guide to YouTube's Latest Income Strategies</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-simple-strategies-for-recording-on-youtube/"><u>[Updated] Simple Strategies for Recording on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagrams-video-chatting-techniques-a-complete-resource/"><u>2024 Approved Instagram’s Video Chatting Techniques A Complete Resource</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-youtube-monetization-a-cpm-perspective/"><u>2024 Approved Mastering YouTube Monetization A CPM Perspective</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-crafting-compelling-spotify-ads/"><u>2024 Approved The Art of Crafting Compelling Spotify Ads</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-success-must-haves-from-microsoft-store/"><u>Accelerated Success: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-setup-google-play-store-on-win11/"><u>Easy Steps: Setup Google Play Store on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-edges-unending-task-on-windows-11-pcs/"><u>Exploring Edge's Unending Task on Windows 11 PCs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-focusrite-scarlett-18i20-windows-audio-drivers-here/"><u>Get Your Focusrite Scarlett 18I20 Windows Audio Drivers Here</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-nokia-c12-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Nokia C12 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-display-after-power-on/"><u>Overcoming Missing Display After Power On</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-windows-secrets-to-handbrake-use/"><u>Reveal Windows' Secrets to HandBrake Use</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-cost-free-windows-password-gen-options-listed/"><u>Secure & Cost-Free Windows Password Gen Options Listed</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-prevent-and-fix-winscombsvrdll-crashes-on-pcs/"><u>Steps to Prevent and Fix WinscombSvr.dll Crashes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-cloud-using-microsoft-onedrive-offline/"><u>Taming the Cloud: Using Microsoft OneDrive Offline</u></a></li>
<li><a href="https://extra-tips.techidaily.com/uncovering-best-in-class-steadicams-for-high-end-dslr-projects/"><u>Uncovering Best-in-Class Steadicams for High-End DSLR Projects</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/winning-strategies-for-addressing-window-10s-power-error-internally/"><u>Winning Strategies for Addressing Window 10'S Power Error Internally</u></a></li>
</ul></div>

