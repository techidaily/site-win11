---
title: Tailoring Lockout Timer After Failed Windows Sign-In
date: 2024-10-18T02:06:00.695Z
updated: 2024-10-21T01:15:32.400Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Lockout Timer After Failed Windows Sign-In
excerpt: This Article Describes Tailoring Lockout Timer After Failed Windows Sign-In
keywords: Lockout Timer Fix,Sign-In Failure Timer,Windows Security Adjustment,Timer Lock Issue Resolution,Extend Lockout Timer,Failed Login Timer Setup,Windows Lockout Timing
thumbnail: https://thmb.techidaily.com/e1e3cd6b008cdab8aeee33309c0a15674cf83671f125b94d0f79189ce7d24b4f.jpg
---

## Tailoring Lockout Timer After Failed Windows Sign-In

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
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-streamlining-your-itunes-video-recordings-for-2024/"><u>[New] Streamlining Your iTunes Video Recordings for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-real-value-of-selfie-verifications-in-2024/"><u>[New] The Real Value of Selfie Verifications, In 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unbeatable-tag-analyzers-for-facebook-twitter-and-instagram-sites/"><u>[Updated] 2024 Approved Unbeatable Tag Analyzers for Facebook, Twitter & Instagram Sites</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-utilizing-smartphones-for-effective-home-based-filming/"><u>2024 Approved Utilizing Smartphones for Effective Home-Based Filming</u></a></li>
<li><a href="https://fox-tips.techidaily.com/advanced-iis-settings-configuration-panel/"><u>Advanced IIS Settings Configuration Panel</u></a></li>
<li><a href="https://win11.techidaily.com/critical-hardware-scan-tools/"><u>Critical Hardware Scan Tools</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-dev-drive-setup-in-windows-11-development-space/"><u>Demystifying Dev Drive Setup in Windows 11 Development Space</u></a></li>
<li><a href="https://fox-access.techidaily.com/hidden-horizons-in-hand-drawn-harmony/"><u>Hidden Horizons in Hand-Drawn Harmony</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-apple-iphone-xs-max-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your Apple iPhone XS Max without Security Questions?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-drive-labels-the-candd-dynamics/"><u>Interpreting Drive Labels: The C&D Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-photo-slideshows-and-spot-corrections-on-win11s-gallery/"><u>Mastering Photo Slideshows & Spot Corrections on Win11's Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-restricted-administrator-error-in-winsec/"><u>Overcoming Restricted Administrator Error in WinSec</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-disregard-must-have-components-issue-in-win10win11/"><u>Quick Guide to Disregard Must-Have Components Issue in Win10/Win11</u></a></li>
<li><a href="https://fox-that.techidaily.com/revive-your-iphone-flashlight-a-guide-with-12-effective-methods/"><u>Revive Your iPhone Flashlight: A Guide with 12 Effective Methods</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-best-video-edits-and-scripting-tools-in-windows-11/"><u>The Ultimate List: Best Video Edits & Scripting Tools in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-way-you-use-windows-11s-search-feature/"><u>Transforming the Way You Use Windows 11'S Search Feature</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-the-dll-dilemma-quick-fixes-for-when-fm20dll-wont-load/"><u>Troubleshooting the DLL Dilemma: Quick Fixes for When fm20.dll Won’t Load</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-group-policy-settings-an-exploration-in-3-dimensions/"><u>Unraveling Windows Group Policy Settings: An Exploration in 3 Dimensions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    