---
title: How to Unclog the Secondary User' Writes Access Issue
date: 2024-09-05T08:29:43.897Z
updated: 2024-09-06T08:29:43.897Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unclog the Secondary User' Writes Access Issue
excerpt: This Article Describes How to Unclog the Secondary User' Writes Access Issue
keywords: Unclog User Write Issues,Fix Write Errors Login,Resolve Write Permissions,Remove Write Lock Error,Eliminate Write Denial,Clear Write Access Block,Overcome Write Failure
thumbnail: https://thmb.techidaily.com/f7c3dfb51630ea312d0721a61ab19847e1113bba58f7b17ac94759c2d0864364.jpg
---

## How to Unclog the Secondary User' Writes Access Issue

 So you're trying to sign in to your Windows device with a Microsoft account, but it throws an error that reads, "another user on this device uses this Microsoft account." You're certain that the account isn't signed in to the device, so why is Windows showing an error?

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.

## What Is the "Another User on This Device Uses This Microsoft Account" Error?

![Windows displaying an error when adding account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-already-signedin.jpg)

 The "another user on this device uses this Microsoft account" error is a message that appears when you are trying to sign in to a Microsoft account on a device that already has a user signed in with the same account. This can happen if multiple users share a computer or if you are trying to access your account from a different device.

 The error message is a security measure to prevent unauthorized access to your account. In most scenarios, this error pops up if you've previously signed in with your account on that device, then deleted your account. If your account wasn't completely wiped off the device, you'll get this error message when you try to log in with it again.

 Another variation of this error reads "account already has been added to this PC." Fortunately, the solutions for both these errors are the same. Let's explore these solutions in more detail.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Remove the Device from Your Microsoft Account

 When you log in to a Windows device with your Microsoft account, the two begin communicating with one another. The device adds your account to its list of recognized users, while your account also adds the device to its list of connected devices.

 However, there may be instances when your account stays linked to a device even after you've removed it. This could be a possible reason why you are encountering the "another user on this device uses this Microsoft account" error.

![Removing a device from Microsoft accounts.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-account-devices.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Thus, the first solution you can try is to remove the device from your Microsoft account. Here's how you can do it:

1. Go to the [Microsoft account website](https://account.microsoft.com) and sign in with your account credentials.
2. Go to the **Devices** tab and select the device you want to sign in on.
3. Click on the **Remove** hyperlink to remove the device from your Microsoft account.
4. Check **I'm ready to remove this device** and then click **Remove**.

 Restart your device and try signing in to your Microsoft account again. If this doesn't fix the error, you'll need to get your hands slightly dirty.

 The other solutions for this error require you to have access to an administrator account on the Windows device. If you don't have access to an administrator account, you'll have to ask the device owner to apply these solutions.

## 2\. Delete the Account From the Local Users and Groups Settings

 As the name implies, the Local Users and Groups Settings let you manage your computer's users and groups. You can change the permissions and memberships of each user, and in this case, you can use it to delete the excess user.

![Windows local users and groups settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-local-users.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 There are several [ways to access Windows' Local Users and Groups settings](https://www.makeuseof.com/windows-open-local-users-and-groups/). Once it's open, in the Local Users and Groups window, navigate to **Users**. Find the user account that's causing the error, right-click on it, then select **Delete**.

 Restart your device and try signing in to your Microsoft account again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Delete the Account Using the Registry Editor

 To ensure that the Microsoft account leaves no trails behind, you can clean up the remnants using the [Windows Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). However, if the previous solution worked properly for you, you won't find the account in Registry Editor.

 Here's how you can delete the account with Registry Editor:

1. Open the Start menu and search for **Registry Editor**.
2. Open **Registry Editor**.
3. On the left-side pane, navigate to **HKEY\_USERS > .DEFAULT > Software > Microsoft > IdentityCRL > StoredIdentities**.
4. Once you expand **StoredIdentities**, you'll see a list of signed-in Microsoft accounts.  
![Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windwos-registery-user.jpg)
5. Right-click the account and select **Delete**.

 Note that this time you'll only see the Microsoft accounts on the device, not the local accounts. If these do not resolve the issue, it is likely that the problem extends beyond this specific account.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Change the Local Security Policy Settings

 Ever since Windows 10, Microsoft has been pushing users to sign in with their Microsoft accounts rather than local Windows accounts.

 Although you can now easily [create a local account in Windows](https://www.makeuseof.com/windows-11-create-local-user-account/), security policies regarding the accounts on your computer might be causing the "another user on this device uses this Microsoft account" error.

![Local security policies in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-security-policy.jpg)

 You can change the local security policy on your device so that it doesn't block Microsoft accounts from logging in. You can do this through the Local Security Policies settings in Windows. Here's how:

1. Open the Local Security Policy window (see [how to open the Local Security Policy in Windows](https://www.makeuseof.com/windows-11-local-security-policy/) if you need help).
2. In the Local Security Policy window, navigate to **Security Settings** \> **Local Policies** \> **Security Options**.
3. Find the **Accounts: Block Microsoft accounts** policy and double-click on it.
4. From the drop-down list, select **This policy is disabled**.
5. Click on **Apply** and **OK** to save the changes.

 Restart your device and try signing in to your Microsoft account. If the error still persists, it might be time to outsource your solutions and [contact Microsoft support](https://www.makeuseof.com/contact-microsoft-support/) to have them help you out.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix the "Another User on This Device Uses This Microsoft Account" Error and Get Back to Work

 This error becomes frustrating when it persists even after you've long deleted the account from that device. Hopefully, the solutions mentioned here will help you thoroughly sever the tie between your account and the device so you can sign in again.

 If all the measures here fail, you can contact Microsoft support and ask them for help. If that too fails, then there's no better fixer than a fresh installation of Windows.

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-a-look-at-earnings-understanding-your-monthly-income-from-youtubes-adsense/"><u>[New] 2024 Approved  A Look at Earnings  Understanding Your Monthly Income From YouTube's AdSense</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-advanced-techniques-for-efficient-media-navigation/"><u>[Updated] 2024 Approved  Advanced Techniques for Efficient Media Navigation</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-clearing-your-browsers-watched-videos-for-2024/"><u>[Updated] Clearing Your Browser's Watched Videos for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-tune-and-trends-a-guide-to-sound-in-social-media-snapshots/"><u>2024 Approved  Tune & Trends  A Guide to Sound in Social Media Snapshots</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-disabled-powershell-script-policy-4-efficient-solutions/"><u>Confronting Disabled PowerShell Script Policy: 4 Efficient Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-pc-conflicts-with-pct-guide/"><u>Conquer PC Conflicts with PCT Guide</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-disabling-the-mystery-of-0x8007045d-on-windows-11/"><u>Decoding and Disabling the Mystery of 0X8007045d on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-infinix-device-sim-by-drfone-android/"><u>Easily Unlock Your Infinix Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-slide-show-creation-in-windows-seven-ways-to-go/"><u>Effortless Slide Show Creation in Windows – Seven Ways to Go</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-integrating-msixbundle-and-msix-extensions-into-windows/"><u>Essential Guide: Integrating Msixbundle & MSIX Extensions Into Windows</u></a></li>
<li><a href="https://article-files.techidaily.com/expertise-in-easel-alterations-color-command-for-2024/"><u>Expertise in Easel Alterations - Color Command for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/family-fortification-the-top-5-corrections-for-safe-haven/"><u>Family Fortification: The Top 5 Corrections for Safe Haven</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-latest-nvidia-1080-drivers-for-windows-10-now/"><u>Get Your Latest NVIDIA 1080 Drivers for Windows 10 Now!</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-handling-java-vm-creation-failure/"><u>Guidelines for Handling Java VM Creation Failure</u></a></li>
<li><a href="https://win11.techidaily.com/handling-printer-id-clashes-in-windows/"><u>Handling Printer ID Clashes in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-solutions-for-activating-windows-updates/"><u>Hassle-Free Solutions for Activating Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correctly-handle-read-only-folders-on-windows/"><u>How to Correctly Handle Read-Only Folders on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-on-the-apple-iphone-6s-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock On the Apple iPhone 6s Without Previous Owner?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-premier-5-ios-photo-background-swap-apps/"><u>In 2024, The Premier 5 iOS Photo Background Swap Apps</u></a></li>
<li><a href="https://win11.techidaily.com/linux-flourish-windows-subsystem-effect/"><u>Linux Flourish: Windows Subsystem Effect?</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/master-mac-security-learn-to-encrypt-and-decrypt-your-hard-drive-effectively/"><u>Master Mac Security: Learn to Encrypt and Decrypt Your Hard Drive Effectively!</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-fixing-windows-1011-filesystem-issues/"><u>Navigating and Fixing Windows 10/11 Filesystem Issues</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-downloads-a-guide-to-the-microsoft-store/"><u>Optimize Your Downloads: A Guide to the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-win-11-experience-with-added-movecopy-context-menu/"><u>Optimize Your Win 11 Experience with Added 'Move'/'Copy' Context Menu</u></a></li>
<li><a href="https://win-answers.techidaily.com/pc-troubles-heres-why-the-ascent-game-continues-to-experience-crashes-and-how-to-fix-it/"><u>PC Troubles? Here's Why 'The Ascent' Game Continues to Experience Crashes and How to Fix It</u></a></li>
<li><a href="https://extra-support.techidaily.com/peak-psd-layer-magic-for-2024/"><u>Peak PSD Layer Magic for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-round-corners-on-windows-11/"><u>Rectify Round Corners on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-stream-disconnection-in-remote-pc-mode/"><u>Resolving Stream Disconnection in Remote PC Mode</u></a></li>
<li><a href="https://win11.techidaily.com/shake-off-frozen-clicks-top-6-tips-for-windows-users/"><u>Shake Off Frozen Clicks: Top 6 Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-output-5-essential-windows-productivity-hacks/"><u>Skyrocketing Output: 5 Essential Windows Productivity Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-win11-cc-troubleshooting-made-easy/"><u>Step-by-Step Guide: Win11 CC Troubleshooting Made Easy</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-by-step-ringtones-and-sounds-personalization-for-android-users-for-2024/"><u>Step-By-Step Ringtones and Sounds Personalization for Android Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-stranded-site-stories-seven-windows-workarounds-for-access-issues/"><u>The Stranded Site Stories: Seven Windows Workarounds for Access Issues</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-honor-magic-5-lite-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Honor Magic 5 Lite without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-adjusting-creation-and-modification-dates-in-windows/"><u>Understanding and Adjusting Creation & Modification Dates in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-potential-mastering-the-run-command-enhancement/"><u>Unlock Windows 11 Potential: Mastering the Run Command Enhancement</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>