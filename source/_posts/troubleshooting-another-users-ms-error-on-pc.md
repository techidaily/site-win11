---
title: "Troubleshooting: Another User's MS Error on PC"
date: 2024-07-13T10:11:40.788Z
updated: 2024-07-14T10:11:40.788Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Another User's MS Error on PC"
excerpt: "This Article Describes Troubleshooting: Another User's MS Error on PC"
keywords: Fixing Other's MSE Errors,Resolve Unique PC Errors,Identifying MSE Issues Others Face,Addressing Non-Owner MS Errors,Tackling External User’s MSE Problems,Remedy Third-User MSE on Computer,Correcting Others' MSE on PC Troubleshoot
thumbnail: https://thmb.techidaily.com/7a3b2432a9d08b9e553576af71c0365aa49f025a4ccec0f85070f5a5f457c917.jpg
---

## Troubleshooting: Another User's MS Error on PC

 So you're trying to sign in to your Windows device with a Microsoft account, but it throws an error that reads, "another user on this device uses this Microsoft account." You're certain that the account isn't signed in to the device, so why is Windows showing an error?

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.

## What Is the "Another User on This Device Uses This Microsoft Account" Error?

![Windows displaying an error when adding account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-already-signedin.jpg)

 The "another user on this device uses this Microsoft account" error is a message that appears when you are trying to sign in to a Microsoft account on a device that already has a user signed in with the same account. This can happen if multiple users share a computer or if you are trying to access your account from a different device.

 The error message is a security measure to prevent unauthorized access to your account. In most scenarios, this error pops up if you've previously signed in with your account on that device, then deleted your account. If your account wasn't completely wiped off the device, you'll get this error message when you try to log in with it again.

 Another variation of this error reads "account already has been added to this PC." Fortunately, the solutions for both these errors are the same. Let's explore these solutions in more detail.

## 1\. Remove the Device from Your Microsoft Account

 When you log in to a Windows device with your Microsoft account, the two begin communicating with one another. The device adds your account to its list of recognized users, while your account also adds the device to its list of connected devices.

 However, there may be instances when your account stays linked to a device even after you've removed it. This could be a possible reason why you are encountering the "another user on this device uses this Microsoft account" error.

![Removing a device from Microsoft accounts.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-account-devices.jpg)

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

 There are several [ways to access Windows' Local Users and Groups settings](https://www.makeuseof.com/windows-open-local-users-and-groups/). Once it's open, in the Local Users and Groups window, navigate to **Users**. Find the user account that's causing the error, right-click on it, then select **Delete**.

 Restart your device and try signing in to your Microsoft account again.

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

## Fix the "Another User on This Device Uses This Microsoft Account" Error and Get Back to Work

 This error becomes frustrating when it persists even after you've long deleted the account from that device. Hopefully, the solutions mentioned here will help you thoroughly sever the tie between your account and the device so you can sign in again.

 If all the measures here fail, you can contact Microsoft support and ask them for help. If that too fails, then there's no better fixer than a fresh installation of Windows.

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-spectral-perfection-program/"><u>[New] Spectral Perfection Program</u></a></li>
<li><a href="https://win11.techidaily.com/fortifying-data-travel-best-practices-for-ws11w10/"><u>Fortifying Data Travel: Best Practices for WS11/W10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-digital-audio-mastery-fb-video-conversion-wizardry/"><u>[Updated] Digital Audio Mastery  FB Video Conversion Wizardry</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-your-windows-pcs-character-map-functionality-succeeds/"><u>Ensuring Your Windows PC's Character Map Functionality Succeeds</u></a></li>
<li><a href="https://video-capture.techidaily.com/starry-secrets-a-guide-to-capturing-the-perfect-night-portraits-for-2024/"><u>Starry Secrets  A Guide to Capturing the Perfect Night Portraits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-fuchsia-to-functional-8-fixes-for-windows-color-issues/"><u>From Fuchsia to Functional: 8 Fixes for Windows Color Issues</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-spotifys-code-4-error/"><u>Deciphering and Rectifying Spotify's Code 4 Error</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-0x80070194-a-guide-to-onedrive-in-ws/"><u>Counteracting 0X80070194: A Guide to OneDrive in WS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-xc0f1103f-issue-with-geforce-now-on-windows/"><u>Fixing XC0F1103F Issue with GeForce Now on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-efficiency-and-productivity-discover-powertoys-top-usage-tips/"><u>Enhance Efficiency & Productivity: Discover PowerToys' Top Usage Tips</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-perfecting-instagrams-audio-emoji-placement/"><u>[Updated] 2024 Approved  Perfecting Instagram's Audio Emoji Placement</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-effective-engagement-incorporating-youtube-videos-into-slides/"><u>[New] In 2024, Effective Engagement  Incorporating YouTube Videos Into Slides</u></a></li>
<li><a href="https://extra-information.techidaily.com/astonishing-critique-and-comparable-products-for-2024/"><u>Astonishing Critique & Comparable Products for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-oneplus-nord-n30-se-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 OnePlus Nord N30 SE Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-remedying-outlook-failures/"><u>Essential Steps for Remedying Outlook Failures</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-bluetooth-device-unable-to-use-buttons-or-mute/"><u>Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/saving-your-focus-a-guide-to-quieting-naysayers-on-google-video-calls-for-2024/"><u>Saving Your Focus  A Guide to Quieting Naysayers on Google Video Calls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-it-admin-cant-do-more-on-windows-os/"><u>Fixing 'Your IT Admin Can't Do More' On Windows OS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-online-learning-campaign-comprehensive-insights-streamed-live/"><u>Updated 2024 Approved Online Learning Campaign Comprehensive Insights Streamed Live</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-volume-mixer-in-the-action-center-in-windows-11/"><u>How to Enable the Volume Mixer in the Action Center in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-read-only-filters-in-win-os/"><u>Eliminating Read-Only Filters in Win OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-vimeo-profile-picture-constraints/"><u>[New] In 2024, Vimeo Profile Picture Constraints</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-how-to-intensify-your-gaming-view-on-roblox-platforms/"><u>[New] 2024 Approved  How to Intensify Your Gaming View on Roblox Platforms</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unboxing-the-essence-of-dji-inspire-2/"><u>2024 Approved  Unboxing the Essence of DJI Inspire 2</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-vivo-y36i-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Vivo Y36i System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-revenue-generation-from-windows-11/"><u>Exploring Revenue Generation From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-smoothly-integrate-icloud-with-your-windows-machine/"><u>How to Smoothly Integrate iCloud with Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/compreenas-a-solution-for-xbox-app-failure-error-0x80073d26/"><u>Compreenas a Solution for Xbox App Failure: Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-signals-secure-connections-windows-wi-fi-tips/"><u>Hidden Signals, Secure Connections: Windows Wi-Fi Tips</u></a></li>
<li><a href="https://win11.techidaily.com/find-the-folder-windows-captured-photos/"><u>Find the Folder: Windows Captured Photos</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-terminal-in-quake-mode/"><u>How to Engage Terminal in Quake Mode</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photo-artistry-unleashed-advanced-techniques-in-distorted-imagery/"><u>[New] Photo Artistry Unleashed  Advanced Techniques in Distorted Imagery</u></a></li>
<li><a href="https://win11.techidaily.com/freedom-from-epic-game-launcher-in-windows-11-steps-explained/"><u>Freedom From Epic Game Launcher in Windows 11: Steps Explained</u></a></li>
</ul></div>
