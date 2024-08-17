---
title: "Optimize Your PowerShell Experience: Execution Policies Demystified"
date: 2024-08-15T23:53:47.905Z
updated: 2024-08-16T23:53:47.905Z
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-explore-unrestricted-stock-content-in-key-4-video-channels/"><u>[New] 2024 Approved  Explore Unrestricted Stock Content in Key 4 Video Channels</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-future-awaits-equipping-yourself-for-metaverse-life-top-7/"><u>[New] 2024 Approved  The Future Awaits  Equipping Yourself for Metaverse Life (Top 7)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unleashing-creativity-in-stories-adding-personalized-graphics/"><u>[New] In 2024, Unleashing Creativity in Stories  Adding Personalized Graphics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevate-your-content-with-insightful-channel-descriptions/"><u>[Updated] In 2024, Elevate Your Content with Insightful Channel Descriptions</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-essential-tips-for-cheap-gopro-shopping/"><u>2024 Approved  Essential Tips for Cheap GoPro Shopping</u></a></li>
<li><a href="https://win11.techidaily.com/5-steps-to-clear-windows-not-supported-error-hurdle/"><u>5 Steps to Clear Windows' 'Not Supported' Error Hurdle</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-fixing-loudspeaker-noise-a-guide-for-clear-audio-on-your-logitech-arctis-pro-windows/"><u>Diagnosing & Fixing Loudspeaker Noise: A Guide for Clear Audio on Your Logitech Arctis Pro (Windows)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/dominate-social-media-sales-5-strategic-moves-for-instagram-experts/"><u>Dominate Social Media Sales  5 Strategic Moves for Instagram Experts</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-solid-state-drive-harnessing-power-of-windows-and-fresh/"><u>Elevate Your Solid State Drive - Harnessing Power of Windows & Fresh</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-pro-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 Pro To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-f23-5g-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Oppo F23 5G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-update-or-install-hp-deskjet-ink-advantage-3520-drivers-a-step-by-step-guide/"><u>How to Update or Install HP DeskJet Ink Advantage 3520 Drivers: A Step-by-Step Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-srt-and-mp4-synergy-a-comprehensive-guide-edition/"><u>In 2024, SRT & MP4 Synergy  A Comprehensive Guide Edition</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-oppo-a38-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Oppo A38 Phone Hassle-Free</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-y100a-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Vivo Y100A Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hyper-v-installation-on-w11-home-edition/"><u>Mastering Hyper-V Installation on W11 Home Edition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-low-resource-utilization-wlanextexe/"><u>Mastering Low Resource Utilization: Wlanext.EXE</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-display-performance-with-high-ppi-settings/"><u>Maximizing Display Performance with High PPI Settings</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-perplexity-of-blued-in-windows-10/"><u>Overcoming the Perplexity of Blued in Windows 10</u></a></li>
<li><a href="https://buynow-help.techidaily.com/owc-mercury-pro-external-usb-31-gen-1-optical-drive-review/"><u>OWC Mercury Pro External USB 3.1 Gen 1 Optical Drive Review</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pathway-to-choosing-between-game-and-studio-nvidia-drivers/"><u>Personalized Pathway to Choosing Between Game and Studio Nvidia Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-older-bios-setup-elements/"><u>Refreshing Older BIOS Setup Elements</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-issues-with-windows-system-health-indicator/"><u>Remedying Issues with Windows System Health Indicator</u></a></li>
<li><a href="https://win11.techidaily.com/secure-file-access-preventing-read-only-windows-folders/"><u>Secure File Access: Preventing Read-Only Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-steam-sync-issue/"><u>Solving Windows Steam Sync Issue</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-unresponsive-windows-media-files/"><u>Steps to Rectify Unresponsive Windows Media Files</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-photoshop-performance-issues/"><u>Streamlining Windows Photoshop Performance Issues</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-0x800713f-malfunction-in-windows-mail/"><u>Swift Solution to 0X800713F Malfunction in Windows Mail</u></a></li>
<li><a href="https://win11.techidaily.com/targeted-user-group-policies-implementing-changes-step-by-step/"><u>Targeted User Group Policies: Implementing Changes Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tactics-avoiding-counterfeit-creations-on-microsofts-platform/"><u>Tech Tactics: Avoiding Counterfeit Creations on Microsoft's Platform</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-essential-guide-to-snap-mastery-for-2024/"><u>The Essential Guide to Snap Mastery for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-username-experience-on-windows-11-platform/"><u>Transforming UserName Experience on Windows 11 Platform</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-in-windows-cmd/"><u>Unlock Full Control in Windows CMD</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-10-streamline-your-bluetooth-setup/"><u>Windows 10: Streamline Your Bluetooth Setup</u></a></li>
<li><a href="https://win11.techidaily.com/windows-1011-reimagined-establishing-personalized-pin-patterns/"><u>Windows 10/11 Reimagined: Establishing Personalized Pin Patterns</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-alternatives-at-a-glance-choosing-the-best-platforms/"><u>YouTube Alternatives at a Glance  Choosing the Best Platforms</u></a></li>
</ul></div>
