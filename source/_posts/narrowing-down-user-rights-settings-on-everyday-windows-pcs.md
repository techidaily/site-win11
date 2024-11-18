---
title: Narrowing Down User Rights Settings on Everyday Windows PCs
date: 2024-11-10T22:22:55.474Z
updated: 2024-11-18T04:29:49.429Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Narrowing Down User Rights Settings on Everyday Windows PCs
excerpt: This Article Describes Narrowing Down User Rights Settings on Everyday Windows PCs
keywords: Windows Privacy Controls,PC User Rights Management,Customize Windows Rules,Adjust PC Security,Personal Data Settings,Navigate PC Permissions,Tailor Windows Access
thumbnail: https://thmb.techidaily.com/c35bb55569306b5428a10bd1ab44596d5c722993db7a19d5db6d527a1da8e1b4.png
---

## Narrowing Down User Rights Settings on Everyday Windows PCs

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-colors-unveiled-the-comprehensive-tutorial/"><u>[New] Colors Unveiled The Comprehensive Tutorial</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-determinants-of-youtube-video-prominence-and-success/"><u>[New] Determinants of YouTube Video Prominence and Success</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-motorcycle-mastery-the-top-ranked-action-cameras-for-23-riders/"><u>[New] Motorcycle Mastery – The Top-Ranked Action Cameras for '23 Riders</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-blurred-taskbars-in-windows-11/"><u>Breeze Through Blurred Taskbars in Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-insights-elevating-your-watchlist-game/"><u>ChatGPT Insights: Elevating Your Watchlist Game</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722731632222-discover-why-gamers-love-the-xbox-one-elite-series-2-an-ultimate-gamepad-assessment/"><u>Discover Why Gamers Love the Xbox One Elite Series 2: An Ultimate Gamepad Assessment.</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210257828-9781662415180-faith/"><u>F.A.I.T.H. | Free Book</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-vintage-racing-spectacles-top-five/"><u>In 2024, Vintage Racing Spectacles Top Five</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-process-to-remove-wsl-from-windows/"><u>Mastering the Process to Remove WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrated-workflows-joining-ifttt-and-to-do/"><u>Orchestrated Workflows: Joining IFTTT and To-Do</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/prime-video-communication-experience-the-top-10-mobile-apps-for-2024/"><u>Prime Video Communication Experience The Top 10 Mobile Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/securing-save-configurations-in-your-windows-pubg-game/"><u>Securing Save Configurations in Your Windows PUBG Game</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-swiftly-finding-and-fixing-windows-update-problems/"><u>Strategies for Swiftly Finding and Fixing Windows Update Problems</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199745283-troubleshoot-and-fix-windows-ten-bad-pool-caller-issue-once-and-for-all/"><u>Troubleshoot and Fix Windows ˈTen Bad Pool Caller Issue Once & For All!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    