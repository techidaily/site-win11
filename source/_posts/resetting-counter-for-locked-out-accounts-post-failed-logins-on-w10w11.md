---
title: Resetting Counter for Locked Out Accounts Post-Failed Logins on W10/W11
date: 2024-09-15T09:13:27.610Z
updated: 2024-09-22T07:25:15.502Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Counter for Locked Out Accounts Post-Failed Logins on W10/W11
excerpt: This Article Describes Resetting Counter for Locked Out Accounts Post-Failed Logins on W10/W11
keywords: Reset User Lockout,Password Recovery,Failed Login Fix,Windows Account Unlock,Security Credentials Update,Post-Login Restore,Locked Out Access
thumbnail: https://thmb.techidaily.com/b5dfde40e2a9ad5275b840b5f0fbb161aac4de7d7745911720b5a34076945390.jpg
---

## Resetting Counter for Locked Out Accounts Post-Failed Logins on W10/W11

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/new-prime-window-viewer-for-speedy-images/"><u>[New] Prime Window Viewer for Speedy Images</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-accelerate-creativity-in-photo-editing-using-pixlr/"><u>[Updated] Accelerate Creativity in Photo Editing Using Pixlr</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-easy-methods-for-saving-online-meetings-for-2024/"><u>[Updated] Easy Methods for Saving Online Meetings for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-and-purchased-color-tools-for-the-discerning-canon-user/"><u>[Updated] Free & Purchased Color Tools for the Discerning Canon User</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-key-elements-of-successful-youtube-channel-imagery/"><u>[Updated] Key Elements of Successful YouTube Channel Imagery</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-screen-shutter-essentials/"><u>Decoding Windows Screen Shutter Essentials</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-vivo-s17-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Vivo S17 Phones with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-account-restrictions-quickly/"><u>Overcoming Windows Account Restrictions Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-restoring-accessibility-of-ubisoft-launcher/"><u>Quick Guide to Restoring Accessibility of Ubisoft Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-failed-windows-search-service-start-up/"><u>Remedying Failed Windows Search Service Start-Up</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

