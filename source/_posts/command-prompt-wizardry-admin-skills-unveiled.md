---
title: "Command Prompt Wizardry: Admin Skills Unveiled"
date: 2024-06-25T11:33:24.933Z
updated: 2024-06-26T11:33:24.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Prompt Wizardry: Admin Skills Unveiled"
excerpt: "This Article Describes Command Prompt Wizardry: Admin Skills Unveiled"
keywords: Command Prompt Mastery,Admins' Command Guide,PowerShell Expertise,Windows Administration,CLI Proficiency,Admin Scripting Tips,System Command Skills
thumbnail: https://thmb.techidaily.com/7210d597b33981cf8e8bc74bc3a1da89a343d982eff67b18284889061aed1be5.jpg
---

## Command Prompt Wizardry: Admin Skills Unveiled

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts

![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

## 2\. Show All the Information of a User Account

![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

## 4\. Enable and Disable a User Account

![deactivating an account with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/deactivating-an-account-with-net-user.jpg)

 If there's a user you wish to temporarily restrict so they can't access their account, you can simply disable it instead of deleting it. Here's the basic syntax of that action, making sure to use the **/active:no** switch at the end of the command to tell **net user** you're disabling it:

`net user Username /active:no`

 So, here's an example of what disabling an account would look like after replacing **Username** with the name of the actual user account:

`net user Jack /active:no`

 And if you want to enable a disabled account, you just have to change the **/active:no** switch to **/active:yes**.

## 5\. Enable and Disable a Domain User Account

 Sometimes, you might not want a user to access all the resources in a particular domain. The easier way to restrict them is to disable their account in that domain. You can do this by adding the **/domain** switch to the syntax discussed in the previous section.

 Here's the syntax for disabling an account on a particular domain using **net user**, making sure to replace **Username** with the name of the user you want to disable:

`net user Username /domain /active:no`

 If you want to enable an account on a domain, just use the **/active:yes** switch in the above command structure instead.

## 6\. Set User Account Login Times

 If you want to specify the times someone can log in, you can use the **/time** parameter to specify the account login times. You can use the basic syntax below:

`net user Username /time login_times`

 In the above command structure, replace **Username** with the user you want to limit the login times for, and **login\_times** with a time range in the format **D-D,00:00**. Here's an example of how you'd do this:

`net user Jack /time:M-F,09:00-17:00`

 As per the example above, that user can only log in from Monday to Friday between 9 a.m. and 5 p.m. If Jack tried to log in, he'd get a message saying **Your account has time restrictions that prevent you from signing in**.

 To remove the time restrictions, you'd use the below command:

`net user Jack /time:all`

 Now Jack can go back to logging in whenever he wants.

## 7\. Set User Account Expiry Date

![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

## 10\. Set a Password Policy for Users

![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

## 11\. Set a Home Directory for Users

 When creating a new user profile using **net user**, you can set the home directory, which is where Windows will store the user's personal files and settings. By default, Windows places the home directory of each user account in **This PC > Local Disk (C:) > Users**. To change this with **net user** during account creation, the basic syntax is as follows:

`net user Username Password /add /homedir:Path-to-directory`

 A real-world example of this would be:

`net user Jack Pa$w0rd /add /homedir:D:\Other Users\Jack`

 The above command will place the home directory of **Jack**, as it creates the account, in the **D:\\Other Users\\Jack** folder.

## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/resolving-picturesaveerror-in-windows-11/"><u>Resolving PictureSaveError in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-11-pro/"><u>How to Install Dolby Atmos in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-roadblocks-in-windows-app-functionality/"><u>Overcoming Common Roadblocks in Windows App Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-google-nearby-to-link-devices-easily/"><u>Leveraging Google Nearby to Link Devices Easily</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-tactics-for-repeated-usernamepassword-alerts/"><u>Bypass Tactics for Repeated Username/Password Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/freezing-wi-fi-mouse-how-to-reset-and-restore-functionality-in-windows/"><u>Freezing Wi-Fi Mouse? How to Reset and Restore Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-global-scripts-a-windows-font-guide/"><u>Unleashing Global Scripts: A Windows Font Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-gaming-potential-android-on-win-11-through-google-services-access/"><u>Unlock Gaming Potential: Android on Win 11 Through Google Services Access</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-apps-to-monitor-win-os-temperatures/"><u>Ideal Apps to Monitor Win OS Temperatures</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-list-websites-with-free-thrones-audio-downloads/"><u>In 2024, A-List Websites with Free Thrones Audio Downloads</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-full-time-employees-guide-to-video-content-success-for-2024/"><u>The Full-Time Employee's Guide to Video Content Success for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-infinix-note-30-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Infinix Note 30 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-elite-9-directors-cuts-downloader/"><u>[Updated] In 2024, Elite 9 Directors' Cuts Downloader</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-master-quick-red-eye-correction-in-iphone-photos-for-free/"><u>[Updated] In 2024, Master Quick Red-Eye Correction in iPhone Photos for FREE</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-how-to-keep-your-videos-quiet-and-clear/"><u>[New] How to Keep Your Videos Quiet and Clear</u></a></li>
<li><a href="https://howto.techidaily.com/fix-infinix-note-30-pro-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Infinix Note 30 Pro Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-vivo-x-fold-2-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Vivo X Fold 2 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-download-youtube-beats-on-android-the-ultimate-6-app-guide/"><u>[Updated] 2024 Approved  Download YouTube Beats on Android  The Ultimate 6-App Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-creating-an-unforgettable-meme-requires-inspiration-and-inspiration-can-strike-at-any-moment-so-if-you-dont-want-to-forget-a-potentially-viral-meme-/"><u>Updated Creating an Unforgettable Meme Requires Inspiration, and Inspiration Can Strike at Any Moment, so if You Dont Want to Forget a Potentially Viral Meme, You Can Install an Android or iOS App on Your Sm for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>