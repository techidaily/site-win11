---
title: Fine-Tuning Windows Account Access Lockouts
date: 2024-10-10T19:07:53.424Z
updated: 2024-10-15T21:13:42.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tuning Windows Account Access Lockouts
excerpt: This Article Describes Fine-Tuning Windows Account Access Lockouts
keywords: Window Lockout Fix,Acces Restrictions,User Lockouts Resolve,Optimize Login Blocks,Unlock Windows Users,Account Access Halt,Access Control Tuning
thumbnail: https://thmb.techidaily.com/852437a8f4dc8f33eb3a839d8b7d9a1e3df217c9c33ef7947ef934470397fa43.jpg
---

## Fine-Tuning Windows Account Access Lockouts

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-essential-voice-capturing-apps-for-ipads-3-top-picks/"><u>[New] Essential Voice Capturing Apps for iPads #3 Top Picks</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-amateur-to-professional-iphone-filmmaking-8-key-tips/"><u>[New] From Amateur to Professional iPhone Filmmaking (8 Key Tips)</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-virality-of-jake-paul-a-youtube-odyssey/"><u>[Updated] In 2024, The Virality of Jake Paul A YouTube Odyssey</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-xiaomi-redmi-a2plus-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Xiaomi Redmi A2+ via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-activation-lock-on-apple-iphone-8-4-easy-ways-by-drfone-ios/"><u>Bypass Activation Lock On Apple iPhone 8 - 4 Easy Ways</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-kali-a-windows-users-guide/"><u>Dive Into Kali: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-fullscreen-experience-tackling-windows-overscan/"><u>Enhance Fullscreen Experience: Tackling Windows Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-ctrl-key-malfunction-fixes-on-win11/"><u>Guiding You Through Ctrl Key Malfunction Fixes on Win11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-apple-iphone-11-by-drfone-ios/"><u>How to jailbreak iCloud locked Apple iPhone 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-decoding-the-mystery-of-youtube-shorts/"><u>In 2024, Decoding the Mystery of YouTube Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/off-the-cuff-tricks-to-work-with-onedrive-locally/"><u>Off-the-Cuff Tricks to Work with OneDrive Locally</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-multiscreen-woes-in-windows/"><u>Overcoming Multiscreen Woes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-adding-dolby-atmos-in-win-11-pro/"><u>Quick Steps for Adding Dolby Atmos in Win 11 Pro</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-game-console-network-issues-how-to-tell-if-the-problem-is-universal-or-personal/"><u>Understanding Game Console Network Issues: How to Tell if the Problem Is Universal or Personal</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-typing-lag-seven-effective-fixes-for-win-os/"><u>Win over Typing Lag: Seven Effective Fixes for WIN OS</u></a></li>
</ul></div>

