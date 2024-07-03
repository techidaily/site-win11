---
title: Bypassing 'Elevate Needed' Errors with Ease in Windows OS
date: 2024-06-25T11:44:37.734Z
updated: 2024-06-26T11:44:37.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing 'Elevate Needed' Errors with Ease in Windows OS
excerpt: This Article Describes Bypassing 'Elevate Needed' Errors with Ease in Windows OS
keywords: Bypass Elevation Error,Overcome Windows Error,Fix Elevate Need Error,Avoid Elevation Failure,Resolve Windows Issue,Eliminate Need for Elevation,Tackle Elevate Needed Problems
thumbnail: https://thmb.techidaily.com/84fef5f35988a89f310851ba69e27f36f222e4900085b075caa3fb4e05a962a8.jpg
---

## Bypassing 'Elevate Needed' Errors with Ease in Windows OS

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-desktop-menus-in-win-1011/"><u>Troubleshooting Non-Responsive Desktop Menus in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unravel-winerror-incorrect-file-backups-in-windows/"><u>How to Unravel WinError: Incorrect File Backups in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-and-prevent-windows-drive-vanishing/"><u>Pinpoint and Prevent Windows Drive Vanishing</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-prevent-unauthorized-access-on-windows/"><u>7 Ways to Prevent Unauthorized Access on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-using-github-desktop-for-windows-11-dev-teams/"><u>Tailored Guide to Using GitHub Desktop for Windows 11 Dev Teams</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-screen-captures-adding-sound-in-the-snipping-tool-max-156/"><u>Elevate Your Screen Captures: Adding Sound in the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-steam-sync-problems/"><u>Deciphering and Fixing Steam Sync Problems</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-discard-a-drives-divisional-structure-in-windows/"><u>Simplified Techniques to Discard a Drive's Divisional Structure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-reversing-macos-sierra-update-to-os-x-el-capitan/"><u>In 2024, Reversing MacOS Sierra Update to OS X El Capitan</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitter-video-requirement-you-can-know-aspect-ratio-included/"><u>[Updated] Twitter Video Requirement You Can Know [Aspect Ratio Included]</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2023-how-to-find-facebook-recently-watched-videos/"><u>2023 | How to Find Facebook Recently Watched Videos?</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-vivo-y100a-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hidden-gems-in-the-world-of-google-podcasts/"><u>In 2024, Hidden Gems in the World of Google Podcasts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-fast-track-channel-growth-to-partner-status-aim-for-10000-views/"><u>[New] Fast-Track Channel Growth to Partner Status – Aim for 10,000 Views!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-how-to-choose-best-audio-formats-for-2024/"><u>Updated How to Choose Best Audio Formats for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-social-media-whizs-playbook-analyzing-user-behavior-with-insta-insights/"><u>2024 Approved  The Social Media Whiz's Playbook  Analyzing User Behavior with Insta Insights</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/captivating-comedy-crafted-step-by-step-meme-tutorial-for-2024/"><u>Captivating Comedy Crafted  Step-by-Step Meme Tutorial for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-enrich-your-video-narratives-with-background-melodies-on-fb/"><u>In 2024, Enrich Your Video Narratives with Background Melodies on FB</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>