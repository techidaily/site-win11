---
title: Overcoming Non-Previewable File Trouble on Outlook 365 PC
date: 2024-06-25T11:22:46.127Z
updated: 2024-06-26T11:22:46.127Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Non-Previewable File Trouble on Outlook 365 PC
excerpt: This Article Describes Overcoming Non-Previewable File Trouble on Outlook 365 PC
keywords: Overcome Unseen Files in Outlook,Fixing Outlook 365 Hidden Issues,Outlook 365 File Display Troubleshooting,Previewable Images on Office 365,Solving Outlook Missing Content,Enhance Email Viewability in Outlook,Accessing Files in Outlook Pro
thumbnail: https://thmb.techidaily.com/0be5a94dd3d4589909d5a9db46fde9f5e7dc17aa86b034cba9990542387160cd.jpg
---

## Overcoming Non-Previewable File Trouble on Outlook 365 PC

 Do you keep getting the "this file cannot be previewed" error when previewing attachments in Outlook? The good news is that you don't need to download attachments every time you want to view them, as it is possible to fix this annoying issue.

 Below, we share eight quick and easy fixes for resolving the “this file cannot be previewed” error in Outlook for Windows.

## 1\. Install Relevant Apps to Preview Files

 Outlook may fail to preview attachments if the appropriate app for the file format is not installed on your PC. For instance, if you don’t have a[PDF reader app on your PC](https://www.makeuseof.com/tag/6-pdf-readers-windows/) , Outlook may display the “this file cannot be previewed because there is no previewer installed for it” error.

 To avoid this, ensure that the appropriate app or software for the file format is available on your computer. After that, Outlook should be able to preview your files without any problems.

## 2\. Disable Preview Handler in PowerToys

 Using Microsoft PowerToys is an excellent way to[boost your productivity on Windows computers](https://www.makeuseof.com/set-up-windows-pc-maximum-productivity/) . However, these PowerToys utilities can sometimes interfere with app processes and prevent apps from working properly.

 Several users on the forums reported fixing Outlook’s “this file cannot be previewed” error by disabling the Preview Handler feature. You can also give this method a shot.

1. Open the**PowerToys** app using the search menu.
2. Switch to the**File Explorer add-ons** tab using the left sidebar.
3. Under the**Preview Pane** section, disable the toggle next to**Portable Document Format** .  
![Disable Preview Handlers in PowerToys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-preview-handlers-in-powertoys.jpg)

## 3\. Enable Attachment Preview in Outlook

 It's possible that Outlook is failing to preview attachments because the file previewer feature is disabled in the app. To overrule this possibility, you need to check the attachment handling settings in Outlook.

1. Open the**Outlook** app on your PC.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left sidebar.
4. Navigate to the**Trust Center** tab and click the**Trust Center Settings** button.
5. In the**Attachment Handling** tab, clear the**Turn off Attachment Preview** checkbox.
6. Click on**Attachment and Document Previewers** and make sure all the previewers are active. Then, click**OK** .
7. Restart the Outlook app after this and see if you can preview attachments.  
![Attachment Handling in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/attachment-handling-in-outlook.jpg)

## 4\. Change Outlook User Interface Settings

 Another thing you can do is tweak the User Interface Settings in Outlook and see if that gets the app to load attachment previews on Windows. Here are the steps for the same:

1. Open the Outlook app and click the**File** menu at the top.
2. Select**Options** from the left column.
3. In the Outlook Options window, navigate to the**General** tab.
4. Under the**User Interface Settings** section, select**Optimize for compatibility** option.  
![Optimize Outlook for Compatibility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/optimize-outlook-for-compatibility.jpg)

 Restart the Outlook app after this and check if the issue is still there.

## 5\. Clear Outlook Cache

 Outlook, like most apps, stores cache files on your computer to reduce loading times. Although this data is supposed to improve app performance, it’s not uncommon for it to become corrupted over time. When this happens, Outlook may malfunction or throw strange errors. You can try deleting the Outlook cache and see if that helps.

To delete Outlook cache data on Windows, use these steps:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Run** from the list.
3. Type**%localappdata%\\Microsoft\\Outlook** in the text box and press**Enter** .
4. In the**RoamCache** folder that appears, select all the files and click the**trash icon** at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 6\. Enable Windows Firewall

 Have you disabled Windows Defender Firewall on your computer? That could prevent Outlook from previewing attachments.

 Here's how to check if the Windows Defender Firewall is enabled on your PC.

1. Press**Win + S** to open the search menu.
2. Type**Windows Security** in the search box and press**Enter** .
3. Select**Firewall & network protection** tab from the left pane.
4. Choose a network profile.
5. Enable the toggle for**Windows Defender Firewall** .  
![Enable Microsoft Defender Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-microsoft-defender-firewall.jpg)

## 7\. Modify Registry Files

 Incorrect[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) settings could also cause such anomalies. If that's the case, you'll need to correct the Registry settings manually on your PC.

 Since Registry files contain important settings for Windows and its apps, you should only use this method if you’re familiar with editing Registry files. Also, it’s a good idea to back up all the Registry files before you proceed. If you need help with that, check our guide on[how to back up Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > ​SOFTWARE > ​Microsoft > ​Windows > ​CurrentVersion > ​PreviewHandlers** .
5. Look for the following string values and check the associated**Data** on the right side.  
`{00020827-0000-0000-C000-000000000046} = Microsoft Excel previewer  
{21E17C2F-AD3A-4b89-841F-09CFE02D16B7} = Microsoft Visio previewer  
{65235197-874B-4A07-BDC5-E65EA825B718} = Microsoft PowerPoint previewer  
{84F66100-FF7C-4fb4-B0C0-02CD7FB668FE} = Microsoft Word previewer  
{DC6EFB56-9CFA-464D-8880-44885D7DC193} = Adobe PDF Preview Handler for Vista`  
![Preview Handlers in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/preview-handlers-in-registry.jpg)
6. If any of the above-mentioned values are missing, right-click on an empty spot and select**New > String Value** .
7. Double-click on the newly created string value.
8. Enter the name of the application handler in the**Value data** field and click**OK** .
9. Right-click on the string value, select**Rename** and type the value associated with the application handler.
10. Exit the Registry Editor window and restart your PC.  
![Edit String in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-string-in-registry.jpg)

## 8\. Run the Microsoft Office Repair Tool

 Microsoft Office includes a repair tool for fixing Office apps on Windows. So, if nothing works, you can run this tool to repair the Outlook app. Here's how:

1. [Use one of the many ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
2. Go to**Programs and Features** .
3. Locate and select**Microsoft Office** on the list. Then, click the**Change** button at the top.
4. Select**Quick Repair** and then click**Repair** .  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 Wait for the process to finish and check if you can preview files. If you can't, repeat the above steps to perform an**Online Repair** . As suggestive of its name, this process does necessitate an active internet connection on your computer.

## Preview Your Outlook Attachments Again on Windows

 One of these eight fixes should take care of the “this file cannot be previewed” error in Outlook. If not, you can consider reinstalling the Outlook app as a last resort.

 If you're tired of dealing with the Outlook app's recurring problems, there are plenty of excellent email clients for Windows.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigating-windows-file-properties-and-date-adjustments/"><u>Navigating Windows File Properties and Date Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-school-inspired-themes-for-win-11/"><u>Turn On School-Inspired Themes for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/recording-games-simply-mastering-screen-captures-with-intel-tools/"><u>Recording Games Simply: Mastering Screen Captures with Intel Tools</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unverified-session-error-by-steams-vac/"><u>Fixing Unverified Session Error by Steam's VAC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-folders-reverting-to-read-only-mode-in-windows-10-and-11/"><u>How to Fix Folders Reverting to Read-Only Mode in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/master-system-configurations-optimizing-usage-options/"><u>Master System Configurations: Optimizing Usage Options</u></a></li>
<li><a href="https://win11.techidaily.com/ending-failed-operations-fix-code-0x0000011b/"><u>Ending Failed Operations: Fix Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-driver-verification-on-windows-enforcement-off-unsigned-loaded/"><u>Bypass Driver Verification on Windows: Enforcement Off, Unsigned Loaded</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tiktok-beats-as-ringtones-practical-approach-for-mobile-users/"><u>[Updated] TikTok Beats as Ringtones  Practical Approach for Mobile Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-from-click-to-chatter-turning-titles-into-talk-on-fb/"><u>[New] 2024 Approved  From Click to Chatter  Turning Titles Into Talk on FB</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-samsung-galaxy-s23-tactical-edition-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Samsung Galaxy S23 Tactical Edition? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-realme-v30-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Realme V30 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-no-caps-lock-required-android-and-ios-downloader-hacks/"><u>[Updated] No Caps Lock Required  Android and iOS Downloader Hacks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/luts-unveiled-transforming-the-lands-market/"><u>LUTs Unveiled  Transforming the Lands Market</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-mastering-sound-on-mac-navigating-through-the-top-5-audio-mixer-choices-for-2024/"><u>Updated Mastering Sound on Mac Navigating Through The Top 5 Audio Mixer Choices for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-most-shared-tweets-of-the-year-viewer-analysis/"><u>In 2024, Most Shared Tweets of the Year  Viewer Analysis</u></a></li>
</ul></div>
