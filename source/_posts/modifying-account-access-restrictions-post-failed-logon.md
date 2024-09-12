---
title: Modifying Account Access Restrictions Post-Failed Logon
date: 2024-09-11T09:46:53.359Z
updated: 2024-09-12T09:46:53.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Account Access Restrictions Post-Failed Logon
excerpt: This Article Describes Modifying Account Access Restrictions Post-Failed Logon
keywords: Login Failure Limits,Account Lockout Policy,Unauthorized Access Control,Revise Login Rejections,Manage Failed Login Attempts,Enhance Security Restrictions,Adjust Access Denial Settings
thumbnail: https://thmb.techidaily.com/4c8d9f631d7921c719a1941a590fa8e1cb22a0616837cda48eb590a45fbdddeb.png
---

## Modifying Account Access Restrictions Post-Failed Logon

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118304/7443" target="_top" id="2118304">
  <img src="//a.impactradius-go.com/display-ad/7443-2118304" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118304/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-seo-innovation-pivotal-tech-to-elevate-your-vids/"><u>[New] 2024 Approved SEO Innovation Pivotal Tech to Elevate Your Vids</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-synergy-of-style-and-functionality-in-ae-plugins/"><u>[Updated] Synergy of Style and Functionality in AE Plugins</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-3d-worlds-on-your-android-mastering-vr-and-360-videos/"><u>2024 Approved 3D Worlds on Your Android Mastering VR & 360 Videos</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-exploring-and-expressing-a-comprehensible-guide-to-becoming-a-travel-videographer/"><u>2024 Approved Exploring & Expressing A Comprehensible Guide to Becoming a Travel Videographer</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-mouseclicklock-usage-on-windows-pcs/"><u>Demystifying MouseClickLock Usage on Windows PCs</u></a></li>
<li><a href="https://techtrends.techidaily.com/diy-repair-tips-making-your-uncooperative-keyboard-work-again/"><u>DIY Repair Tips: Making Your Uncooperative Keyboard Work Again</u></a></li>
<li><a href="https://win11.techidaily.com/effective-booting-technique-startup-windows-unveil-notebooks/"><u>Effective Booting Technique: Startup Windows, Unveil Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/escaping-the-shadows-reclaiming-light-from-darkness/"><u>Escaping the Shadows: Reclaiming Light From Darkness</u></a></li>
<li><a href="https://win11.techidaily.com/fasten-the-toggling-of-microsofts-taskbar-integrated-chat/"><u>Fasten the Toggling of Microsoft’s Taskbar-Integrated Chat</u></a></li>
<li><a href="https://some-techniques.techidaily.com/finding-your-ideal-viewing-experience-with-projection-or-television-for-2024/"><u>Finding Your Ideal Viewing Experience with Projection or Television for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-file-creation-on-win11s-camera-app/"><u>Fixing Failed File Creation on Win11's Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-server-stumbled-microsoft-store-error-in-windows-10-and-11/"><u>How to Fix the “Server Stumbled” Microsoft Store Error in Windows 10 & 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-crafting-captivating-cinematic-experiences-in-youtube-videos/"><u>In 2024, Crafting Captivating Cinematic Experiences in YouTube Videos</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-poco-m6-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Poco M6 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/insight-guide-reviewing-and-removing-windows-history/"><u>Insight Guide: Reviewing & Removing Windows History</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-updated-epson-wf-3620-printer-drivers-for-seamless-printing-experience-on-windows-11-8-and-7/"><u>Install Updated Epson WF-3620 Printer Drivers for Seamless Printing Experience on Windows 11, 8 & 7</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-pc-potential-through-processor-options/"><u>Maximizing PC Potential Through Processor Options</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-camera-error-a00f425d/"><u>Navigating Through Windows Camera Error A00F425D</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-11-notes-for-universal-accessibility/"><u>Optimize Windows 11 Notes for Universal Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-high-usage-chatgpt-alerts-on-pc/"><u>Overcoming High Usage ChatGPT Alerts on PC</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722970554945-quick-setup-tutorials-for-brother-mfc7360n-drivers-on-windows-1187-get-your-perfect-printouts/"><u>Quick Setup Tutorials for Brother MFC7360N Drivers on Windows 11/8/7: Get Your Perfect Printouts</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-loadlibrary-error-87-in-windows/"><u>Resolving LoadLibrary Error 87 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-the-taskbar-in-windows-11-top-6-suggested-enhancements/"><u>Revolutionizing the Taskbar in Windows 11: Top 6 Suggested Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/shattered-scenery-9-ways-to-restore-win11-screen-snapshots/"><u>Shattered Scenery? 9 Ways to Restore Win11 Screen Snapshots</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-addressing-launch-failed-lunar-client-issues/"><u>Techniques for Addressing “Launch Failed Lunar Client” Issues</u></a></li>
<li><a href="https://win11.techidaily.com/the-roadmap-for-utilizing-the-calculator-in-windows-11/"><u>The Roadmap for Utilizing the Calculator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/triggers-for-launching-system-restore-in-windows-11-environment/"><u>Triggers for Launching System Restore in Windows 11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-your-watching-youtube-performance-in-chrome/"><u>Turbocharge Your Watching: YouTube Performance in Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/unfreeze-opera-downloads-tips-for-windows-users/"><u>Unfreeze Opera Downloads: Tips for Windows Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-6-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking Apple iPhone 6 Passcode without a Computer</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-system-index-adjustments/"><u>Unlocking System Index Adjustments</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/zmi-powerpack-20000-critique-the-essential-guide-to-high-capacity-portable-chargers/"><u>ZMI PowerPack 20000 Critique: The Essential Guide to High-Capacity Portable Chargers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    