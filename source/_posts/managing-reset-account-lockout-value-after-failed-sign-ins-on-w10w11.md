---
title: Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
date: 2025-02-10T03:40:52.514Z
updated: 2025-02-15T20:57:13.557Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-ultimate-laptops-your-go-to-machine-for-expert-video-editing/"><u>[New] Ultimate Laptops Your Go-To Machine for Expert Video Editing</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-pro-tips-for-utilizing-green-screen-effects-professionally/"><u>[Updated] 2024 Approved Pro Tips for Utilizing Green Screen Effects Professionally</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-building-a-robust-360-video-broadcast-framework-for-fb/"><u>[Updated] In 2024, Building a Robust 360 Video Broadcast Framework for FB</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-thorough-examination-an-in-depth-review-of-gecata-log/"><u>[Updated] In 2024, Thorough Examination An In-Depth Review of Gecata Log</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-open-mov-files-on-motorola-razr-40-ultra-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't open MOV files on Motorola Razr 40 Ultra</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-repair-techniques-for-when-your-system-cant-find-d3dx924dll/"><u>Easy Repair Techniques for When Your System Can't Find d3dx9_24.dll</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-nokia-c22-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Nokia C22 Face Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/guarantee-stable-performance-of-your-windows-ui/"><u>Guarantee Stable Performance of Your Window's UI</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-vivo-g2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-approach-to-quiet-background-programs-in-win11/"><u>Methodical Approach to Quiet Background Programs in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/replacing-original-windows-pdf-displayer/"><u>Replacing Original Windows PDF Displayer</u></a></li>
<li><a href="https://win11.techidaily.com/turn-back-the-clock-stripping-webp-from-your-browsers-saves/"><u>Turn Back the Clock: Stripping WebP From Your Browser's Saves</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/ultimate-smartphone-camera-recording-tools-iphoneandroid-edition-for-2024/"><u>Ultimate Smartphone Camera Recording Tools - iPhone/Android Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-drop-error-step-by-step-solutions/"><u>Win11's Drop Error: Step-by-Step Solutions</u></a></li>
</ul></div>

