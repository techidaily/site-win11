---
title: PowerShell Scripts for Efficient Account Management
date: 2024-09-11T09:40:52.164Z
updated: 2024-09-12T09:40:52.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes PowerShell Scripts for Efficient Account Management
excerpt: This Article Describes PowerShell Scripts for Efficient Account Management
keywords: PowerShell Admin Tools,Account Automation PS,Efficiency PowerShell,Manage Users PScript,Secure Account Control,Streamline UserPS,Optimized Account Scripts
thumbnail: https://thmb.techidaily.com/b60c76ffc589ae0e04ed8d9626d309109b105480cf9bd2a5898ac2cac1fa41f0.jpg
---

## PowerShell Scripts for Efficient Account Management

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. List All User Accounts

![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Show All the Information of a User Account

![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 10\. Set a Password Policy for Users

![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-infusing-new-life-into-old-images-with-instagram-magic/"><u>[New] 2024 Approved Infusing New Life Into Old Images with Instagram Magic</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-integrating-voices-into-videos-effectively/"><u>[New] 2024 Approved Integrating Voices Into Videos Effectively</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-becoming-a-savvy-user-of-google-photos/"><u>[New] Becoming a Savvy User of Google Photos</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-create-awe-inspiring-gopro-time-lapse-cinematography/"><u>[New] In 2024, Create Awe-Inspiring GoPro Time-Lapse Cinematography</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-perfect-propeller-synergy-for-awe-inspiring-fpv-flights/"><u>[New] In 2024, Perfect Propeller Synergy for Awe-Inspiring FPV Flights</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-strategies-for-igtv-on-facebook-integration/"><u>[New] In 2024, Strategies for IGTV on Facebook Integration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-premier-filmmakers-digital-backdrop-changer/"><u>[New] Premier Filmmaker's Digital Backdrop Changer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transform-photos-with-ease-using-basic-adobe-tools/"><u>[New] Transform Photos with Ease Using Basic Adobe Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-quickscreen-log-review-and-alternative-apps/"><u>[Updated] 2024 Approved QuickScreen Log Review and Alternative Apps</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-jumpstart-your-channel-with-these-top-10-video-editing-tips/"><u>[Updated] Jumpstart Your Channel with These Top 10 Video Editing Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-monthly-revenue-streams-for-video-content-creators/"><u>2024 Approved Monthly Revenue Streams for Video Content Creators</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-streamline-video-communication-learn-to-add-timely-captions-on-fb-videos/"><u>2024 Approved Streamline Video Communication Learn to Add Timely Captions on FB Videos</u></a></li>
<li><a href="https://data-wizards.techidaily.com/banishing-blurry-frames-from-interlaced-footage/"><u>Banishing Blurry Frames From Interlaced Footage</u></a></li>
<li><a href="https://win11.techidaily.com/crucial-steps-to-idle-your-windowed-machine/"><u>Crucial Steps to Idle Your Windowed Machine</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-backbone-the-registry-explained/"><u>Exploring Windows 11'S Backbone: The Registry Explained</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-glitch-a-guide-to-overcoming-microsoft-store-errors/"><u>Fixing the Glitch: A Guide to Overcoming Microsoft Store Errors</u></a></li>
<li><a href="https://win11.techidaily.com/from-silence-to-sound-windows-11s-tale-beginnings/"><u>From Silence to Sound: Windows 11'S Tale Beginnings</u></a></li>
<li><a href="https://win11.techidaily.com/full-deletion-process-for-wsl-on-win-1011/"><u>Full Deletion Process for WSL on Win 10/11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-itel-p55plus-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Itel P55+?</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-from-apple-iphone-6-by-drfone-ios/"><u>How To Create an Apple Developer Account From Apple iPhone 6</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-active-directory-domain-services-printer-error-in-windows-11-and-11/"><u>How to Fix the “Active Directory Domain Services” Printer Error in Windows 11 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-files-after-iphone-xs-max-factory-reset-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Files after iPhone XS Max Factory Reset? | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-itel-a70-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Itel A70?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Realme C33 2023? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/installment-challenge-overcoming-mspm-errors/"><u>Installment Challenge: Overcoming MSPM Errors</u></a></li>
<li><a href="https://win11.techidaily.com/launching-the-speedy-assistance-mechanism-in-w11/"><u>Launching the Speedy Assistance Mechanism in W11</u></a></li>
<li><a href="https://win11.techidaily.com/maintaining-privacy-blocking-insider-windows-11-releases/"><u>Maintaining Privacy: Blocking Insider Windows 11 Releases</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-communication-what-to-do-when-your-samsung-galaxy-watch-ignores-calls/"><u>Mastering Communication: What To Do When Your Samsung Galaxy Watch Ignores Calls</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-cross-border-controls-the-complete-guide-to-powertoys/"><u>Mastering Cross-Border Controls: The Complete Guide to PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hurdles-with-handbrake/"><u>Overcoming Windows Hurdles with HandBrake</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-failures-8-strategies/"><u>Overcoming Windows Login Failures: 8 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-update-issue-0x8024800c-error/"><u>Overcoming Windows Update Issue: 0X8024800C Error</u></a></li>
<li><a href="https://screen-capture.techidaily.com/photo-your-desktop-windows-edition/"><u>Photo Your Desktop Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-black-window-after-system-ignition/"><u>Remedying Black Window After System Ignition</u></a></li>
<li><a href="https://win11.techidaily.com/saving-success-fixing-volume-mixer-glitches/"><u>Saving Success: Fixing Volume Mixer Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/security-spotlight-top-7-windows-procedures-vigilant-against-viruses/"><u>Security Spotlight: Top 7 Windows Procedures Vigilant Against Viruses</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-steam-download-routines-for-windows-pcs/"><u>Speedy Steam Download Routines for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-uninstalling-and-reinstalling-utorrent-on-windows-1087/"><u>Steps for Uninstalling and Reinstalling uTorrent on Windows 10/8/7</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-the-error-in-windows-activation-0x803f700f/"><u>Strategies for Overcoming the Error in Windows Activation 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/sudden-rav-virus-alert-where-it-comes-from-how-to-uninstall/"><u>Sudden Rav Virus Alert - Where It Comes From, How To Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-include-sound-with-snipping-tool-screen-captures-max-156/"><u>Techniques to Include Sound with Snipping Tool Screen Captures (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/the-keys-to-free-jumpstart-your-pc-with-unbeatable-windows-11-612lifetime/"><u>The Keys to Free: Jumpstart Your PC with Unbeatable Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-wipe-out-email-at-sign-in/"><u>The Ultimate Guide to Wipe Out Email at Sign-In</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-device-not-initialized-error-in-win-11/"><u>Troubleshooting 'Device Not Initialized' Error in Win 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-the-non-responsive-corsair-icue-software-in-windows-11-environments/"><u>Troubleshooting the Non-Responsive Corsair iCUE Software in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xc0f1103f-failure-on-geforce-now-and-windows-1011/"><u>Troubleshooting XC0F1103F Failure on GeForce Now & Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pcs-full-potential-in-games-the-win-11-master-plan-of-7-actions/"><u>Unlock Your PC's Full Potential in Games: The Win 11 Master Plan of 7 Actions</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-full-potential-narrator-keybindings-decoded/"><u>Unlocking Full Potential: Narrator Keybindings Decoded</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/king-youtubes-financial-framework-shifts/"><u>Unpacking YouTube’s Financial Framework Shifts</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-steps-to-eradicate-nonexistent-devices-in-pcs/"><u>Unveiling Steps to Eradicate 'Nonexistent' Devices in PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-solutions-the-ultimate-guide-to-fixing-e84-in-steam/"><u>Unwrapping Solutions: The Ultimate Guide to Fixing E84 in Steam</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    