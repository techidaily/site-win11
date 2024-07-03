---
title: "Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS"
date: 2024-06-25T11:32:16.655Z
updated: 2024-06-26T11:32:16.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS"
excerpt: "This Article Describes Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS"
keywords: Fixing WinError 740,Operation Promotion Error,WinError Resolution,Promote Operations in OS,Overcoming WinError Errors,Windows OS Promotion Issue,Handling 'Operation Needs Promotion'
thumbnail: https://thmb.techidaily.com/b84b835099bbd2f060100cf1ff53df1a6537fd5a4b5a03be31336b43fbf43c35.jpg
---

## Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS

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
<li><a href="https://win11.techidaily.com/expertly-restoring-erased-data-in-a-microsoft-world/"><u>Expertly Restoring Erased Data in a Microsoft World</u></a></li>
<li><a href="https://win11.techidaily.com/from-ios-to-desktop-seamless-sync-with-windows-os/"><u>From iOS to Desktop: Seamless Sync with Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-activate-windows-media-player/"><u>Simplified Steps to Activate Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-wsl-registration-failure-with-error-x80370102/"><u>Mastering The Fix: WSL Registration Failure with Error X80370102</u></a></li>
<li><a href="https://win11.techidaily.com/15-key-improvements-added-to-windows-11s-next-version/"><u>15 Key Improvements Added to Windows 11'S Next Version</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/copying-powertoys-preferences-to-another-pc/"><u>Copying PowerToys Preferences to Another PC</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-efficiently-engaging-recovery-tool/"><u>Key Steps for Efficiently Engaging Recovery Tool</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-leveraging-likes-shares-and-comments-tiktoks-commerce-magic-for-2024/"><u>[Updated] Leveraging Likes, Shares, and Comments  TikTok's Commerce Magic for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-comedic-continuum-top-tiktok-stars-and-their-funnies/"><u>[New] Comedic Continuum  Top TikTok Stars and Their Funnies</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-motivational-cinema-the-ultimate-guide-to-empowerment-films/"><u>2024 Approved  Motivational Cinema  The Ultimate Guide to Empowerment Films</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-14-pro-max-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone 14 Pro Max After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-smartphone-streaming-success-without-a-massive-subscriber-base/"><u>2024 Approved  Smartphone Streaming Success Without a Massive Subscriber Base</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-enhance-your-feed-top-15-instagram-free-safe-following-aids-for-2024/"><u>[Updated] Enhance Your Feed  Top 15 Instagram Free, Safe Following Aids for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-infinix-smart-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-pinnacle-of-presence-a-strategic-approach-for-live-video-graphics/"><u>[New] Pinnacle of Presence  A Strategic Approach for Live Video Graphics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-streamlining-the-timestamp-process-for-youtubers/"><u>In 2024, Streamlining the Timestamp Process for YouTubers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-updated-query-catalog-to-connect-with-podcast-loyalists/"><u>[Updated] Updated Query Catalog to Connect with Podcast Loyalists</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>