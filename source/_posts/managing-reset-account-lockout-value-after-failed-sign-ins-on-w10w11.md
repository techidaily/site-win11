---
title: Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
date: 2025-02-28T00:37:21.465Z
updated: 2025-03-04T17:32:48.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
excerpt: This Article Describes Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
keywords: Account Lockout Management,Windows 10/11 Login Issues,Reset Password After Fail,Sign-In Troubleshooting,W10 Security Settings,Lockout Policy Adjustment,Failed Sign-In Fixation
thumbnail: https://thmb.techidaily.com/3485122afbd86c9e9c462c3f4114e1a2939bb988f69531afc473f2a12af7b022.jpg
---

## Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-perfect-pc-playthrough-captures-6-tips-and-tricks/"><u>[Updated] 2024 Approved Perfect PC Playthrough Captures 6 Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/debugging-java-virtual-machine-creation-failure-on-windows/"><u>Debugging Java Virtual Machine Creation Failure on Windows</u></a></li>
<li><a href="https://win-hot.techidaily.com/discover-the-finest-selection-of-7-premium-ad-free-video-trimmers-for-seamless-edits/"><u>Discover the Finest Selection of 7 Premium, Ad-Free Video Trimmers for Seamless Edits</u></a></li>
<li><a href="https://win11.techidaily.com/get-back-into-the-microsoft-store-top-login-solutions/"><u>Get Back Into the Microsoft Store - Top Login Solutions</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-x-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone X to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-keeping-track-of-facetime-with-facebooks-live-feature/"><u>In 2024, Keeping Track of FaceTime with Facebook's Live Feature</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-masterclass-choosing-the-pinnacle-in-hdr-cameras/"><u>In 2024, Masterclass Choosing the Pinnacle in HDR Cameras</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-maximize-your-green-screen-potential-with-these-top-8-download-sites/"><u>In 2024, Maximize Your Green Screen Potential with These Top 8 Download Sites</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-server-connection-in-the-latest-win11-version/"><u>Mastering File Server Connection in the Latest Win11 Version</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-non-selectable-text-windows-pdf-guide/"><u>Navigate Non-Selectable Text: Windows' PDF Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/online-swfflv-movavi/"><u>Online 무료 SWF/FLV 변환기 - Movavi 용인 편집기</u></a></li>
<li><a href="https://win-able.techidaily.com/1723013942899-resolved-issues-with-launching-rainbow-six-siege-fixed/"><u>Resolved: Issues with Launching Rainbow Six Siege Fixed!</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-error-with-amd-195-software/"><u>Resolving Windows Error with AMD 195 Software</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-development-best-practices-for-wsl-2-on-pcs/"><u>Supercharge Development: Best Practices for WSL 2 on PCs</u></a></li>
<li><a href="https://fox-that.techidaily.com/what-to-do-when-an-iphone-app-goes-missing-recovery-techniques-explained/"><u>What to Do When an iPhone App Goes Missing: Recovery Techniques Explained</u></a></li>
<li><a href="https://win11.techidaily.com/winning-csgo-on-w11-troubleshooting-non-start-issues/"><u>Winning CS:GO on W11 – Troubleshooting Non-Start Issues</u></a></li>
</ul></div>

