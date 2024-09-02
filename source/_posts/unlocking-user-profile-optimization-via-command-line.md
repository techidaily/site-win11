---
title: Unlocking User Profile Optimization via Command Line
date: 2024-09-01T04:37:36.914Z
updated: 2024-09-02T04:37:36.914Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking User Profile Optimization via Command Line
excerpt: This Article Describes Unlocking User Profile Optimization via Command Line
keywords: CLI User Profiles,Profile Enhancement CLI,Command Line Optimize,UI Command Tuning,CLI Profile Boost,User Profiling CLI,Command Profiles Upgrade
thumbnail: https://thmb.techidaily.com/ab712e6369c11731fb797565c1d31f34a50ed98f4e3e4e20f2e0bcfb8f432b00.jpg
---

## Unlocking User Profile Optimization via Command Line

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Set User Account Expiry Date

![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-into-the-fray-with-polaroid-cubeplus-action-recorder/"><u>[New] 2024 Approved  Into the Fray with Polaroid Cube+ Action Recorder</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-quick-steps-to-capture-ios-audio-files-for-2024/"><u>[New] Quick Steps to Capture iOS Audio Files for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-crafting-youtube-video-trailers-with-filmoras-guide/"><u>[Updated] Crafting YouTube Video Trailers with Filmora's Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-delving-into-vimeo-your-ultimate-video-partner/"><u>[Updated] Delving Into Vimeo  Your Ultimate Video Partner</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-remobell-security-camera-review-top-choices-for-less-than-100/"><u>Affordable RemoBell Security Camera Review – Top Choices for Less Than $100</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-windows-ram-cache/"><u>Comprehensive Guide to Window’s RAM Cache</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-a-legacy-youtubers-playbook-for-success/"><u>Crafting a Legacy  YouTuber’s Playbook for Success</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-error-code-0xc00000f-in-windows/"><u>Deciphering and Resolving Error Code 0xC00000F in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-erasing-your-windows-11-actions-trail/"><u>Decoding and Erasing Your Windows 11 Actions Trail</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-vcplusplus-distribution-essence/"><u>Decoding VC++ Distribution Essence</u></a></li>
<li><a href="https://win11.techidaily.com/ease-into-windows-11-troubleshooting-update-issue-0x30017/"><u>Ease Into Windows 11: Troubleshooting Update Issue #0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/easing-expiry-headache-fixing-windows-license-alarms/"><u>Easing Expiry Headache: Fixing Windows License Alarms</u></a></li>
<li><a href="https://win11.techidaily.com/empowered-windows-operations-advanced-run-enhancements-guide/"><u>Empowered Windows Operations: Advanced Run Enhancements Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-custom-pin-lengths-for-windows-users/"><u>Enhance Accessibility: Custom PIN Lengths for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/essential-preparations-what-you-need-prior-to-windows-overhaul/"><u>Essential Preparations: What You Need Prior To Windows Overhaul</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-for-simultaneous-wi-fi-and-ethernet-use-in-windows/"><u>Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-efficient-installation-of-msixbundle-and-apppackages-from-microsoft-store/"><u>Fast Track: Efficient Installation of MSixbundle & Apppackages From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-best-of-linux-ditch-wsl/"><u>Get the Best of Linux - Ditch WSL</u></a></li>
<li><a href="https://win11.techidaily.com/harness-tdarr-to-multiply-windows-pc-video-conversion-efficiency/"><u>Harness Tdarr to Multiply Window's PC Video Conversion Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-error-code-0x80004004-in-defender/"><u>How to Address Error Code 0X80004004 in Defender</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-xiaomi-redmi-12-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Xiaomi Redmi 12 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-ace-2-pro-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Ace 2 Pro to Outlook | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-record-the-essence-of-your-facebook-page/"><u>In 2024, Record the Essence of Your FACEbook Page</u></a></li>
<li><a href="https://games-able.techidaily.com/inside-java-games-our-favorite-features-listed-out/"><u>Inside Java Games: Our Favorite Features Listed Out</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-tasks-with-these-excellent-8-windows-timer-apps/"><u>Master Your Tasks with These Excellent 8 Windows Timer Apps</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-win11-startup-efficiency/"><u>Maximizing Win11 Startup Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-spotify-crash-in-windows-11-without-it-help/"><u>Overcoming Spotify Crash in Windows 11 without IT Help</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-taskbar-concealment-when-maximizing-browser/"><u>Overcoming Taskbar Concealment When Maximizing Browser</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-mcuicnt-execution-error-on-modern-windows-pcs/"><u>Overhauling McUICnt Execution Error on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/pros-choice-top-video-trimming-apps-for-windows-pcs/"><u>Pro's Choice: Top Video Trimming Apps for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quantifying-storage-quotient-for-windows-programs/"><u>Quantifying Storage Quotient for Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-stopping-windows-11-from-running/"><u>Quick Fixes: Stopping Windows 11 From Running</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-vintage-windows-pcs-for-elders/"><u>Reimagining Vintage Windows PCs for Elders</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steams-unavailable-content-servers-issue-on-pc/"><u>Resolving Steam's Unavailable Content Servers Issue on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revert-to-regular-contrast-on-windows/"><u>Revert to Regular Contrast on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/separating-the-sincere-from-the-spoof-in-the-windows-store/"><u>Separating the Sincere From the Spoof in the Windows Store</u></a></li>
<li><a href="https://win11.techidaily.com/staying-ahead-insights-into-windows-11s-enhanced-security-updates/"><u>Staying Ahead: Insights Into Windows 11'S Enhanced Security Updates</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-elevate-taskmanager-on-desktop/"><u>Strategies to Elevate TaskManager on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-performance-via-virtual-memory-adjustment-in-windows-11/"><u>Streamlining Performance via Virtual Memory Adjustment in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-ux-a-blueprint-of-essential-taskbar-amendments-in-windows-11/"><u>Streamlining UX: A Blueprint of Essential Taskbar Amendments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-eliminate-autominimize-effects/"><u>Streamlining Windows: Eliminate AutoMinimize Effects</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-the-best-cpu-coolers-all-in-one-and-air-options-reviewed/"><u>The Ultimate Guide to the Best CPU Coolers : All-in-One & Air Options Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-11-22h2-moment-update-could-bring-7-exciting-features/"><u>The Windows 11 22H2 Moment Update Could Bring 7 Exciting Features</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-6-translation-devices-for-media-files-for-2024/"><u>Top 6 Translation Devices for Media Files for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-nighttime-paints-dark-aesthetics/"><u>Transition to Nighttime: Paint's Dark Aesthetics</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-steps-to-bring-back-your-inoperative-iphoneipad/"><u>Troubleshooting Steps to Bring Back Your Inoperative iPhone/iPad</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-poco-x6-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Poco X6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-the-ultimate-guide-to-windows-powertoy-features/"><u>Unleash Potential: The Ultimate Guide to Windows PowerToy Features</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-code-mastery-reclaiming-your-windows-1011-key/"><u>Unlock Code Mastery: Reclaiming Your Windows 10/11 Key</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-bulk-directory-formation-on-windows-10-and-11-systems/"><u>Unlock the Power of Bulk Directory Formation on Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/win11-image-camouflage-techniques-for-zip-files/"><u>Win11 Image Camouflage Techniques for ZIP Files</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>