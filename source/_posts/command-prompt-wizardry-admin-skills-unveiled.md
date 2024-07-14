---
title: "Command Prompt Wizardry: Admin Skills Unveiled"
date: 2024-07-13T10:24:29.659Z
updated: 2024-07-14T10:24:29.659Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-make-a-slideshow-with-icecream-slideshow-maker/"><u>2024 Approved How to Make a Slideshow with Icecream Slideshow Maker</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-resource-drains-in-windows-managing-multimedia-consumption/"><u>Cutting Down Resource Drains in Windows: Managing Multimedia Consumption</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Oppo A79 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-best-way-to-stitch-gopro-clips-into-360-videos/"><u>2024 Approved  Best Way to Stitch GoPro Clips Into 360 Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-frame-rate-showdown-evaluating-30fps-and-60fps-in-videography-for-2024/"><u>[Updated] Frame Rate Showdown  Evaluating 30Fps and 60Fps in Videography for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-trendsetting-tags-top-10-to-make-your-post-pop/"><u>[Updated] Trendsetting Tags  Top 10 To Make Your Post Pop</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-motorola-razr-40-ultra-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Motorola Razr 40 Ultra Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-innovation-unveiled-5-cutting-edge-webcams-with-sound-tech-for-2024/"><u>[New] Innovation Unveiled  5 Cutting-Edge Webcams With Sound Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solving-full-screen-glitches-in-sonic-frontiers-windows-11/"><u>Solving Full-Screen Glitches in Sonic Frontiers (Windows 11)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-transforming-youtube-footage-for-ultimate-quality/"><u>[Updated] Transforming YouTube Footage for Ultimate Quality</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-scanning-problems-effectively/"><u>Tackle Windows GeForce Scanning Problems Effectively</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-f34-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy F34 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-excessive-windows-contrast-effects/"><u>Disabling Excessive Windows Contrast Effects</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-application-failures-due-to-net-not-installed/"><u>Addressing Application Failures Due to .NET Not Installed</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-6-oddities-in-windows-11-design/"><u>Decoding the 6 Oddities in Windows 11 Design</u></a></li>
<li><a href="https://win11.techidaily.com/creative-steps-to-obliviate-win-11s-taskbar-button/"><u>Creative Steps to Obliviate Win 11'S Taskbar Button</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-earning-beats-for-your-ears-the-art-of-accessing-free-audio-music-legally/"><u>In 2024, Earning Beats for Your Ears The Art of Accessing FREE Audio Music Legally</u></a></li>
<li><a href="https://win11.techidaily.com/automating-zipunzip-tasks-in-windows-using-scripting-tools/"><u>Automating Zip/Unzip Tasks in Windows Using Scripting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-celebrity-inspired-glamour-videos/"><u>[Updated] Celebrity-Inspired Glamour Videos</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-motorola-moto-g04-by-drfone-android/"><u>In 2024, How to Bypass FRP on Motorola Moto G04?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fast-tracking-fb-content-efficiency-strategies-explored/"><u>2024 Approved  Fast-Tracking FB Content  Efficiency Strategies Explored</u></a></li>
<li><a href="https://win11.techidaily.com/should-you-embrace-windows-11s-secure-environment/"><u>Should You Embrace Windows 11'S Secure Environment?</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11-drag-and-drop-failures-now/"><u>Fix Windows 11 Drag-and-Drop Failures Now</u></a></li>
<li><a href="https://win11.techidaily.com/color-confusion-correcting-windows-desktop-hues-quickly/"><u>Color Confusion? Correcting Windows Desktop Hues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/the-clear-sight-crusade-nine-methods-to-sharpen-your-monitor/"><u>The Clear Sight Crusade: Nine Methods to Sharpen Your Monitor</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ranscendental-tranquility-youtubes-best-yoga-channels/"><u>[New] Transcendental Tranquility – YouTube’s Best Yoga Channels</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-memory-caching-in-windows-os/"><u>Breaking Down Memory Caching in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/whats-in-store-for-windows-11-with-update-22h2/"><u>What's in Store for Windows 11 with Update #22H2?</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charging-your-app-downloads-from-microsoft/"><u>Turbo-Charging Your App Downloads From Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-unblocking-steam-when-playing-games/"><u>Essential Tips for Unblocking Steam When Playing Games</u></a></li>
<li><a href="https://win11.techidaily.com/stop-blue-screen-bsos-quick-fix-strategies-for-win11/"><u>Stop Blue Screen BSOS: Quick Fix Strategies for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-no-cost-player-titles-for-pcs-and-viewing/"><u>The Top 7 No-Cost Player Titles for PCs & Viewing</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-rotate-avi-in-verticalportrait-orientation-windows-macandro-for-2024/"><u>Updated How to Rotate AVI in Vertical/Portrait Orientation Windows, Mac,Andro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-email-notifications-glitches-on-windows-devices/"><u>Addressing Email Notifications Glitches on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-quickly-resolving-operation-requirement-errors/"><u>Troubleshooting Steps for Quickly Resolving Operation Requirement Errors</u></a></li>
<li><a href="https://win11.techidaily.com/break-down-drives-hdd-vs-ssd-explained/"><u>Break Down Drives: HDD vs SSD Explained</u></a></li>
<li><a href="https://fox-access.techidaily.com/what-lies-beneath-understanding-trillers-different-tiktok-approach/"><u>What Lies Beneath  Understanding Triller's Different TikTok Approach</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-process-for-downloading-adobe-on-microsoft-store/"><u>The Complete Process for Downloading Adobe on Microsoft Store</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-boost-views-strategic-partnerships-on-youtube-for-rapid-growth/"><u>In 2024, Boost Views  Strategic Partnerships on YouTube for Rapid Growth</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-tech-epochs-windows-7-key-to-boot-windows-11/"><u>Bridging the Tech Epochs: Windows 7 Key to Boot Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-distinctions-of-windows-terminal-vs-powershell/"><u>Unraveling The Distinctions of Windows Terminal Vs. PowerShell</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-fb-videobot-downloader-tool-for-2024/"><u>[New] FB Videobot Downloader Tool for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-important-aspects-of-leveraging-youtubes-sound-selection/"><u>The Important Aspects of Leveraging YouTubes Sound Selection</u></a></li>
</ul></div>
