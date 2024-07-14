---
title: Advanced User Management via Windows Terminal
date: 2024-07-13T11:24:58.244Z
updated: 2024-07-14T11:24:58.244Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced User Management via Windows Terminal
excerpt: This Article Describes Advanced User Management via Windows Terminal
keywords: Windows Terminal Admin,Terminal User Control,Advanced Terminal Access,Secure Terminal Management,Terminal Role Handling,PowerShell Terminal Use,Command Line Administration
thumbnail: https://thmb.techidaily.com/0608abec5e89fbdabfc438dbc05f250f26c6343ebf5ad117060d9466fac18ee3.jpg
---

## Advanced User Management via Windows Terminal

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
<li><a href="https://win11.techidaily.com/avoiding-missed-messages-solutions-to-windows-mail-alert-issues/"><u>Avoiding Missed Messages: Solutions to Windows Mail Alert Issues</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-tools-for-win-1011s-dropdowns/"><u>Beneath-the-Surface Tools for Win 10/11'S Dropdowns</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-tray-displaying-cpu-and-memory-usage/"><u>Boosting System Tray: Displaying CPU & Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-security-with-improved-graphics-on-windows-11/"><u>Boosting Security with Improved Graphics on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-youtube-viewing-on-chrome-windows/"><u>Achieving Flawless YouTube Viewing on Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-the-best-podcast-host-options/"><u>Navigating the Best Podcast Host Options</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/make-a-lasting-impression-5-leading-photo-slideshow-software-for-2024/"><u>Make a Lasting Impression 5 Leading Photo Slideshow Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-your-virtual-space-windows-11-home/"><u>Accessing Your Virtual Space: Windows 11 Home</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-wait-winning-strategies-to-fasten-upstart-in-win11/"><u>Beat The Wait: Winning Strategies to Fasten Upstart in Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-craft-top-quality-youtube-thumbnails-fast-for-2024/"><u>How To Craft Top Quality YouTube Thumbnails Fast for 2024</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-users-guide-how-to-create-photo-talking-videos-with-the-best-tools-in-2024/"><u>Updated Users Guide How To Create Photo Talking Videos With the Best Tools, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-blue-screens-in-your-daily-computing-life/"><u>Beating Back Blue Screens in Your Daily Computing Life</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-complete-profile-makeover-a-no-nonsense-guide-to-tiktok-image-enhancement/"><u>In 2024, Complete Profile Makeover  A No-Nonsense Guide to TikTok Image Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mismatch-of-speaker-assignment-due-to-another-app/"><u>Avoiding Mismatch of Speaker Assignment Due to Another App</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-meet-mycam-cam-the-home-video-revolution-unfolding/"><u>[New] In 2024, Meet MyCam Cam  The Home Video Revolution Unfolding</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-tecno-phantom-v-flip-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Tecno Phantom V Flip to Protect Your Individual Information</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-zte-nubia-flip-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to ZTE Nubia Flip 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-cursor-signal-strength-in-win-11-os/"><u>Boosting Cursor Signal Strength in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functioning-windows-conditional-filters/"><u>Addressing Non-Functioning Windows Conditional Filters</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-spotifys-default-auto-play-on-windows/"><u>Avoid Spotify's Default Auto-Play on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/optimal-strategies-for-enhancing-vhs-photos-digitally/"><u>Optimal Strategies for Enhancing VHS Photos Digitally</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-customized-windows-cmd/"><u>Boosting Productivity with Customized Windows Cmd</u></a></li>
<li><a href="https://win11.techidaily.com/boost-chat-speed-enable-bing-ai-in-windows-11-menu-bar/"><u>Boost Chat Speed: Enable Bing AI in Windows 11 Menu Bar</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-master-audio-on-chrome-selecting-the-best-web-based-speech-modifiers/"><u>[Updated] Master Audio on Chrome  Selecting the Best Web-Based Speech Modifiers</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1715860255016-2024-approved-no-money-down-best-free-video-chat-platforms/"><u>2024 Approved  No Money Down? Best Free Video Chat Platforms!</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-devices-performance-with-quick-android-apk-installation-in-windows-11/"><u>Boost Your Device's Performance with Quick Android APK Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-already-in-use-errors-and-unique-device-naming/"><u>Banish 'Already in Use' Errors and Unique Device Naming</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-curb-instagrams-auto-suggest-feature/"><u>[New] 2024 Approved  Curb Instagram's Auto-Suggest Feature</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/full-disclosure-unpacking-the-dji-inspire-1/"><u>Full Disclosure  Unpacking the DJI Inspire 1</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pubg-setup-failures-a-windows-guide/"><u>Addressing PUBG Setup Failures: A Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mishaps-validate-your-webcammic-on-windows-pc/"><u>Avoiding Mishaps: Validate Your Webcam/Mic on Windows PC</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-pinnacle-resources-for-3d-type-art/"><u>[Updated] 2024 Approved  Pinnacle Resources for 3D Type Art</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-action-packed-comparisons-gopro-vs-star-sj7/"><u>[New] Action-Packed Comparisons  GoPro Vs Star SJ7</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-decoding-youtubes-legal-framework-for-video-creators/"><u>[New] 2024 Approved  Decoding YouTube's Legal Framework for Video Creators</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/screencapturepro-review-expert-insights-and-comparisons-for-2024/"><u>ScreenCapturePro Review  Expert Insights and Comparisons for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mastering-sound-integrating-music-into-kinemaster-for-2024/"><u>Mastering Sound Integrating Music Into KineMaster for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pc-life-after-declining-windows-11-upgrade/"><u>Boost Your PC Life After Declining Windows 11 Upgrade</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-stand-out-yt-thumbnail-size-and-engagement-strategies-for-2024/"><u>How to Stand Out  YT Thumbnail Size and Engagement Strategies for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-prioritize-privacy-in-conversations-the-best-10-free-secure-mobile-calling-apps-for-iosandroid-for-2024/"><u>[New] Prioritize Privacy in Conversations – The Best 10 Free, Secure Mobile Calling Apps for iOS/Android for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-vivo-x-fold-2-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Vivo X Fold 2 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/lenovo-y470-device-integration-w7-support-guide/"><u>Lenovo Y470 Device Integration - W7 Support Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-saturated-chatgpt-windows-error/"><u>Addressing Saturated ChatGPT Windows Error</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tune-into-unparalleled-music-video-watching-best-android-vids-for-you/"><u>[Updated] Tune Into Unparalleled Music Video Watching  Best Android Vids for You</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-tactics-to-quiet-down-distractions-during-google-meets/"><u>[Updated] 2024 Approved  Tactics to Quiet Down Distractions During Google Meets</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-hiccup-error-0x00000000-solution/"><u>Avoiding Microsoft Store Hiccup: Error 0X00000000 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-failure-starting-services-on-windows-efficiently/"><u>Avoiding Failure: Starting Services on Windows Efficiently</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-boosting-facebook-ad-revenue-with-strategic-animated-content-design/"><u>[Updated] Boosting Facebook Ad Revenue with Strategic Animated Content Design</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-vivacut-video-editing-complete-guide-for-24/"><u>[New] Step-by-Step VivaCut Video Editing  Complete Guide for '24</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-microsoft-paint-in-windows-11/"><u>Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-excellent-selection-of-top-8-blu-ray-player-models/"><u>2024 Approved  Excellent Selection of Top 8 Blu-Ray Player Models</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-compiling-top-10-most-accessible-recorder-software/"><u>[Updated] 2024 Approved  Compiling Top 10 Most Accessible Recorder Software</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://win11.techidaily.com/boost-efficiency-navigating-windows-11s-disk-management-quickly/"><u>Boost Efficiency: Navigating Windows 11'S Disk Management Quickly</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/identifying-core-functionalities-in-digital-sound-editors-for-mac-for-2024/"><u>Identifying Core Functionalities in Digital Sound Editors for Mac for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>