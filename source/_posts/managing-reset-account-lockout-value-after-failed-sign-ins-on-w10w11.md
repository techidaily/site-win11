---
title: Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
date: 2025-02-02T09:55:15.698Z
updated: 2025-02-04T04:32:36.952Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/updated-a-step-by-step-guide-to-using-polarr-for-stunning-images-for-2024/"><u>[Updated] A Step-by-Step Guide to Using Polarr for Stunning Images for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-immerse-in-imagery-top-10-sticker-apps-for-appleandroid-users/"><u>[Updated] Immerse in Imagery – Top 10 Sticker Apps for Apple/Android Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-reviewing-the-impression-of-high-dynamic-range-on-aurora-tv/"><u>[Updated] Reviewing the Impression of High Dynamic Range on Aurora TV</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-windows-11s-top-video-capture-tools-essentials-edition-for-2024/"><u>[Updated] Windows 11'S Top Video Capture Tools Essentials Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-manage-apps-using-window-11-shortcuts/"><u>Efficiently Manage Apps Using Window 11 Shortcuts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-asus-touchpad-driver-download-and-installation-tips-for-windows-11-users/"><u>Effortless ASUS Touchpad Driver Download & Installation Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-lost-network-discoveries-on-windows-pc/"><u>Enabling Lost Network Discoveries on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/give-your-inbox-a-personal-touch-with-fav-photos/"><u>Give Your Inbox a Personal Touch with Fav Photos</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-not-enough-memory-available-error-for-vms/"><u>How to Overcome 'Not Enough Memory Available' Error for VMs</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-custom-folder-options-adding-movecopy-to-context-menu/"><u>Implementing Custom Folder Options: Adding 'Move'/'Copy' To Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-buy-adobe-reader-in-microsoft-store/"><u>Navigate to Buy Adobe Reader in Microsoft Store</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-red-screen-errors-on-windows-10-a-simple-fix-guide/"><u>Resolve Your Red Screen Errors on Windows 10 - A Simple Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/shortening-windows-screen-saver-timeout/"><u>Shortening Windows Screen Saver Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-pairing-process-for-airpods-and-windows-pcs/"><u>Streamlined Pairing Process for AirPods and Windows PCs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-the-missing-d3dx9e933dll-issue/"><u>Troubleshooting the Missing d3dx9_e9_33.dll Issue</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-troubleshooting-how-to-hard-reset-problematic-software-in-windows-11/"><u>Ultimate Troubleshooting: How to Hard Reset Problematic Software in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-from-iphone-11-by-drfone-ios/"><u>Unlock Apple ID without Phone Number From iPhone 11</u></a></li>
</ul></div>

