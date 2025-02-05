---
title: Bypassing Elevation Requirement Hurdle on WINOS
date: 2025-01-31T08:37:38.138Z
updated: 2025-02-03T18:16:58.443Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Elevation Requirement Hurdle on WINOS
excerpt: This Article Describes Bypassing Elevation Requirement Hurdle on WINOS
keywords: Bypass Elevation Limit Windows OS,Overcome WinOs Height Restrictions,Skip Elevation Bar Windows,Eliminate Window OS Heights,Bypass High Elevations WINOS,Disable Elevation Requirement Windows,Ignore Elevation in WINOS
thumbnail: https://thmb.techidaily.com/a6f140ff4ddda64bd14cec3cab639274aa642e4bb60e8fa6d0c6031cee3c6ed0.jpg
---

## Bypassing Elevation Requirement Hurdle on WINOS

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-keeping-your-audience-engaged-in-a-revised-social-lands-ward/"><u>[New] In 2024, Keeping Your Audience Engaged in a Revised Social Lands Ward</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-mastering-adventure-the-best-6-gopro-mounts-revealed-for-2024/"><u>[New] Mastering Adventure The Best 6 GoPro Mounts Revealed for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-unraveling-the-secrets-of-recording-hulu-across-computersmobile-for-2024/"><u>[New] Unraveling the Secrets of Recording Hulu Across Computers/Mobile for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-keep-your-audience-engaged-top-6-strategies-for-higher-youtube-stickiness/"><u>[Updated] 2024 Approved How To Keep Your Audience Engaged Top 6 Strategies for Higher YouTube Stickiness</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-google-collage-made-fast-and-easy-essential-tips-unveiled/"><u>2024 Approved Google Collage Made Fast & Easy - Essential Tips Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/access-and-enjoy-christian-melodies-anytime-download-free-yt-mp3s/"><u>Access and Enjoy Christian Melodies Anytime: Download Free YT Mp3s!</u></a></li>
<li><a href="https://win11.techidaily.com/audacity-youtube-recording-mastery-easy-tutorial-for-capturing-video-clips/"><u>Audacity YouTube Recording Mastery: Easy Tutorial for Capturing Video Clips</u></a></li>
<li><a href="https://win11.techidaily.com/best-high-quality-audio-formats-which-offers-smaller-sizes/"><u>Best High-Quality Audio Formats: Which Offers Smaller Sizes?</u></a></li>
<li><a href="https://win11.techidaily.com/best-top-rated-flac-audio-software-for-windows-11-a-comprehensive-guide/"><u>Best Top-Rated FLAC Audio Software for Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tutorial-on-capturing-your-slide-show-in-action-using-powerpoint/"><u>Comprehensive Tutorial on Capturing Your Slide Show in Action Using PowerPoint</u></a></li>
<li><a href="https://win11.techidaily.com/custom-ringtones-made-simple-transform-mp3-into-m4r-for-iphone/"><u>Custom Ringtones Made Simple: Transform MP3 Into M4R for iPhone!</u></a></li>
<li><a href="https://win11.techidaily.com/dvdwindows-10mp4/"><u>DVD化のコツ：Windows 10上でMP4動画保存ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/dvdtsutaya/"><u>DVDがTSUTAYAで貸し出されている場合、どのようにしてデータを正当化的に複写・リップするか</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-flawless-audio-extraction-from-dvds/"><u>Easy Guide: Flawless Audio Extraction From DVDs</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-nokia-c110-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-10-youtube-video-ideas-for-sharing-your-personal-story/"><u>In 2024, 10 YouTube Video Ideas for Sharing Your Personal Story</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/set-up-and-manage-slack-alerts-with-your-apple-watch-a-step-by-step-guide/"><u>Set Up and Manage Slack Alerts with Your Apple Watch: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/top-7-solutions-overcome-issues-with-warzone-20-pc-startup/"><u>Top 7 Solutions: Overcome Issues with Warzone 2.0 PC Startup</u></a></li>
<li><a href="https://tech-revival.techidaily.com/which-media-formats-are-optimized-for-editing-with-davinci-resolve/"><u>Which Media Formats Are Optimized for Editing with DaVinci Resolve?</u></a></li>
</ul></div>

