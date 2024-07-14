---
title: Addressing Pathway Errors with Windows Devices
date: 2024-07-13T10:10:51.130Z
updated: 2024-07-14T10:10:51.130Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Pathway Errors with Windows Devices
excerpt: This Article Describes Addressing Pathway Errors with Windows Devices
keywords: Fix Device Path Errors,Windows Path Correction,Resolve Device Routing,Windows Devices Navigation,Reduce Device Access Errors,Correct Windows Traffic Path,Enhance Windows Network Flow
thumbnail: https://thmb.techidaily.com/d77d95aa486b91c6469c5ee9cc4e937e8d3af5aa50ced6b44ad4148b7b19bd91.jpg
---

## Addressing Pathway Errors with Windows Devices

 Are you encountering the "Windows cannot access the specified device, path, or file." error on Windows 10 or 11? This issue usually appears when you try to run an EXE application or open a document. When this error happens, you can't run some programs or access some documents, limiting your computer's usefulness.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.

## 1\. Run the App as an Administrator

 Some programs, for a variety of reasons, need administrator privileges to perform specific tasks. In fact in certain situations, you might not be able to open them either.

 In your case, the "Windows Cannot Access the Specified Device, Path or File” error might be the result of this error as well. So if you are looking to fix this error, running it as an administrator will be your best bet. Here’s how you can get started:

1. Right-click on the app you want to run.
2. From the context menu, select **Run as administrator**.

 If the issue was the lack of administrator privileges, your app will run by the end of these steps.

## 2\. Disable Potentially Unwanted App Blocking

 Unwanted app blocking is a [Windows Security](https://www.makeuseof.com/windows-11-quick-security-guide/) feature that prevents low-reputation apps and software from running. That feature can cause the "cannot access the specified device" error when enabled. You can check if unwanted app blocking is enabled and disable it as follows:

1. Double-click the shield (Windows Security) icon inside the system tray area on the right of the taskbar. You may also need to click a small up arrow on the taskbar to see the system tray icons.
2. Select the **App & browser control** tab in Windows Security.
3. Then click the **Reputation-based protection** **settings** link to view more settings.  
![The Reputation-based protection settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reputation-based-settings-option.jpg)
4. Deselect the **Block apps** checkbox if that feature is enabled.  
![The Block apps checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-block-apps-checkbox.jpg)

## 3\. Deselect the "Unblock File" Setting

 Sometimes [Windows blocks access to files or folders](https://www.makeuseof.com/windows-askadmin-guide/) downloaded from untrusted online sources, which can cause the "cannot access the specified device" error. When that happens, you'll see an **Unblock** checkbox on an affected files properties window. This is how you can deselect the "unblock file" setting:

 Make sure that you trust the file's source before doing this. If you unblock an infected file, it can damage your computer and cause file loss.

1. Right-click **Start** (the taskbar button) and select the **File Explorer** option from the menu.  
![The File Explorer shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/file-explorer.jpg)
2. Open a folder that includes a file for which the error occurs.
3. Right-click the affected file and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/properties-option.jpg)
4. Click **General** if the properties window doesn't open with that tab by default.
5. Then uncheck the selected **Unblock** checkbox if you can see one.  
![The Unblock checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unblock-checkbox.jpg)
6. Select **Apply** to save the new file settings.
7. Click **OK** to close the file's properties window.

## 4\. Edit the File's Permissions

 Another cause of the "cannot access the specified device" error message is insufficient file permissions. That's something you can remedy by editing the permissions for affected files. So, try editing an affected file's permissions as follows:

1. Bring up a directory with a file that throws up the "cannot access the specified device" error.
2. Click an affected file with the right mouse button and select its **Properties** option.
3. Select **Security** in the properties window.
4. Then select the Windows user account you signed into.
5. Press the **Edit** button.
6. Select your Windows user account on the permissions window that opens.
7. Deselect (uncheck) all selected **Deny** permission checkboxes.  
![The Deny checkboxes for file permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deny-checkboxes.jpg)
8. Select **Apply** to set the new permission settings.
9. Press the **OK** buttons on all windows.

## 5\. Recreate a Program's Shortcut

 If the "cannot access the specified device" error occurs when you try to run a program shortcut, the issue might lie within the shortcut itself. In this case, setting up a new shortcut for affected software could resolve the issue. This is how to do so on your desktop:

1. Right-click any part of the desktop without overlapping icons to select **New**.
2. Click **Shortcut** to bring up a tool for adding desktop shortcuts.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/shortcut-option.jpg)
3. Then click **Browse** to select an EXE file the error occurs for and press the **OK** button.  
![The Create Shortcut tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/create-shortcut-window.jpg)
4. Select **Next** and input a shortcut title in the text box.
5. Click **Finish** to add the new program shortcut.
6. Right-click the program's old shortcut to select **Delete** (the trash can button in Windows 11).

## 6\. Double-Check the File's Location

 Do you install software and save some files to an external or network drive? If so, it could be the case that the access error is occurring because a file is on a drive that's not currently accessible.

 Double-check the locations of the files you're trying to run or open by right-clicking desktop shortcuts for them and selecting **Properties**. Then you can check the path for the shortcut in the **Targe**t box shown directly below.

![The Target box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-target-box.jpg)

 That **Target** box will show whether the file is on another drive. If it is, connect the external drive that includes the file to your PC to access it. Double-check that the file specified hasn't been deleted if the **Target** box references the local C: drive. To do that, open the folder path specified in File Explorer.

 Should you discover a shortcut's file has been deleted, you might be able to retrieve it. Open the Recycle Bin to see if the file is in it. If so, right-click the file and select **Restore**.

## 7\. Enable Admin Permissions With the Group Policy Editor

 Users have confirmed enabling admin approval mode in Group Policy Editor can resolve this file access error. However, Group Policy Editor is only available in Windows 11 and 10 Pro and Enterprise editions. If you can utilize Group Policy Editor, try enabling admin approval mode as follows:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and select **Computer Configuration** in that utility.
2. Double-click **Windows Settings** to expand that configuration category.
3. Then double-click **Security Settings** \> **Local Policies** \> **Security Options** in Group Policy Editor's sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/group-policy-editor.jpg)
4. Double-click the **Admin Approval Mode for Built-in Administrator** account policy.
5. Then select the **Enabled** radio button.  
![The Admin Approval Mode policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-admin-approval-mode-policy-settings.jpg)
6. Click **Apply** to set the policy.
7. Select **OK** to exit the window for the policy setting and close the Group Policy Manager utility.

## 8\. Set Up a Windows Security Exclusion Affected Software or File

 As Windows Security blocks can cause this error, we recommend users add affected files to that antivirus app's exclusion list. Doing so will exclude the file from Defender's antivirus protection. Check out our guide to [whitelisting files in Microsoft (formerly Windows) Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) for details about how to apply this potential solution.

![Add an exclusion button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-exclusion-button.jpg)

## 9\. Temporarily Disable Any Active Third-Party Security Software

 Some third-party antivirus apps share similar app-blocking features to Windows Security. Thus, alternative security software can also feasibly cause the same issue to occur much the same. So, try turning off any third-party antivirus software installed on your PC before attempting to run affected EXE software.

![A laptop computer is seen on a desk during an antivirus scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/manual-antivirus-scan.jpg)

 How exactly you turn off different third-party antivirus apps varies slightly. However, most have context menus from which you can select to disable their shields. Click the system tray icon for your antivirus software with the right mouse button to view its context menu. Then choose an option for disabling its antivirus shield from there.

 Should this potential solution work, you'll know what's causing it. However, don't leave your antivirus software disabled. Add affected files to the security software's exceptions list.

## 10\. Repair or Reinstall the File

 If you are facing this issue due to corruption in the file, then repairing or reinstalling it is your best bet. Using the Control Panel will be your best bet in this case. Here's how you can do it:

1. Head to the **Start menu** search bar, type in 'control panel', and select the best match.
2. From there, head to the **Programs**.
3. Then, select **Programs and Features**.
4. Right-click on any program and select **Uninstall/Change**.

![control panel on windows pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/control-panel-on-windows-pc.jpg)

 Depending on the app, you will get an option to either uninstall the app or change its settings. That's it—from there just follow the on-screen instructions, and you will be done in no time. If you installed the app, make sure you get it from a trusted source again and then see if you are facing the same error again.

## Get the "Cannot Access the Specified Device" Error Sorted in Windows 10 and 11

 We don't promise guaranteed solutions, but the potential resolutions here will likely resolve the "cannot access the specified device" error on your PC. Many users have sorted that file access issue out in Windows by applying the above fixes.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-managing-directories-without-renaming-feature-in-win-11/"><u>The Ultimate Guide to Managing Directories Without Renaming Feature in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/procedures-for-resolving-unresponsive-installation-on-windows-os/"><u>Procedures for Resolving Unresponsive Installation on Windows OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-tagging-towards-triumph-the-best-instagram-hashtags/"><u>2024 Approved  Tagging Towards Triumph  The Best Instagram Hashtags</u></a></li>
<li><a href="https://win11.techidaily.com/guide-repairing-windows-based-pen-tablets/"><u>Guide: Repairing Windows-Based Pen Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/organize-your-workspace-attaching-this-pc-icon-to-desktop/"><u>Organize Your Workspace: Attaching 'This PC' Icon to Desktop</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-hidden-network-sight-fixing-windows-issue/"><u>Reviving Hidden Network Sight: Fixing Windows Issue</u></a></li>
<li><a href="https://win11.techidaily.com/swift-steps-to-elevate-account-type/"><u>Swift Steps To Elevate Account Type</u></a></li>
<li><a href="https://extra-resources.techidaily.com/incredible-drone-photoshoot-contenders-10/"><u>Incredible Drone Photoshoot Contenders #10</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/pro-tools-compared-an-in-depth-look-at-the-top-alternative-audio-recording-platforms/"><u>Pro Tools Compared An In-Depth Look at the Top Alternative Audio Recording Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-blue-screen-errors-with-vmware-on-win11/"><u>Strategies to Address Blue Screen Errors with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-10-and-11-apps-temp-and-forecast-picks/"><u>Prime Windows 10 & 11 Apps: Temp & Forecast Picks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-creme-de-la-creativite-youtube-subscriber-list/"><u>[Updated] The Crème De La Créativité  YouTube Subscriber List</u></a></li>
<li><a href="https://win11.techidaily.com/screen-notes-made-easy-winning-sticky-pad-solutions-for-pc/"><u>Screen Notes Made Easy: Winning Sticky Pad Solutions for PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-11x-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme 11X 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-10-ultimate-virtual-worlds-for-party-gaming/"><u>2024 Approved  10 Ultimate Virtual Worlds for Party Gaming</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-apple-iphone-se-2022-by-drfone-ios/"><u>How Do You Remove Restricted Mode on Apple iPhone SE (2022)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-app-size-metrics-in-windows/"><u>Navigating Through App Size Metrics in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/keep-it-neat-how-to-make-windows-recycle-bin-self-cleanse/"><u>Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-unlocking-the-potential-of-sound-in-animated-windows-gif-creations/"><u>New 2024 Approved Unlocking the Potential of Sound in Animated Windows GIF Creations</u></a></li>
<li><a href="https://win11.techidaily.com/master-windows-integration-with-steam-deck/"><u>Master Windows Integration with Steam Deck</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pushing-boundaries-top-virtual-reality-game-development-tools/"><u>[Updated] Pushing Boundaries  Top Virtual Reality Game Development Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-power-user-permissions-issues-in-windows-os/"><u>Resolving Power-User Permissions Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-displaying-messages-errors-in-discord-for-windows/"><u>Fixing Non-Displaying Messages Errors in Discord for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-key-combinations-for-effortless-recalibration/"><u>Mastering Windows: Key Combinations for Effortless Recalibration</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-itel-s23plus-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Itel S23+ Location by Number | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Xiaomi Redmi A2? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/suppress-sound-enhancement-in-windows-os/"><u>Suppress Sound Enhancement in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-overcoming-geforce-nows-xc0f1103f-problem-in-win11/"><u>Guides to Overcoming GeForce Now’s Xc0f1103f Problem in Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/framing-the-future-expert-tips-for-picture-perfection/"><u>Framing the Future  Expert Tips for Picture Perfection</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-revamp-your-channels-smart-tips-for-yt-profiles/"><u>[Updated] Revamp Your Channels  Smart Tips for YT Profiles</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-file-transfers-in-battlenet-windows/"><u>Mastering Fast File Transfers in Battle.net Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-overcoming-fullscreen-malfunctions-in-obs/"><u>[New] In 2024, Overcoming Fullscreen Malfunctions in OBS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-smiles-on-signal-best-humorous-tones-online/"><u>In 2024, Smiles on Signal  Best Humorous Tones Online</u></a></li>
<li><a href="https://win11.techidaily.com/stop-flickering-mouse-immediate-troubleshooting-guide/"><u>Stop Flickering Mouse - Immediate Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-semaphore-timeout-period-ended-in-windows-1011/"><u>Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-make-every-xbox-moment-count-expert-recording-advice/"><u>[Updated] In 2024, Make Every Xbox Moment Count  Expert Recording Advice</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-essential-checklist-for-selecting-a-top-notch-youtube-mp3-downloader/"><u>New 2024 Approved The Essential Checklist for Selecting a Top-Notch YouTube MP3 Downloader</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-to-reclaim-blank-login-screen-on-windows-11/"><u>Fixes to Reclaim Blank Login Screen on Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-essential-guide-to-recording-films-on-windowsmac-and-phones/"><u>[New] 2024 Approved  Essential Guide to Recording Films on Windows/Mac & Phones</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/comprehensive-guide-to-live-streaming-with-obs-and-platforms-for-2024/"><u>Comprehensive Guide to Live-Streaming with OBS and Platforms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-permission-restrictions-and-open-hidden-folders/"><u>How to Disable Permission Restrictions and Open Hidden Folders</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-crowded-taskbar-image-space-in-windows-11/"><u>Resetting Crowded Taskbar Image Space in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instant-setup-acquiring-adobe-reader-via-ms-store/"><u>Instant Setup: Acquiring Adobe Reader via MS Store</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-low-res-to-hd-your-first-foray-into-frame-rates/"><u>2024 Approved  From Low-Res to HD  Your First Foray Into Frame Rates</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-approach-to-disable-unnecessary-windows-11-services/"><u>Proactive Approach to Disable Unnecessary Windows 11 Services</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-basics-windows-system-configuration/"><u>Master the Basics: Windows System Configuration</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-focusing-on-roblox-elements-closeup-for-2024/"><u>The Art of Focusing on Roblox Elements Closeup for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/streamlined-strategies-for-gaming-screen-recording/"><u>Streamlined Strategies for Gaming Screen-Recording</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-taskbar-size-tweaks/"><u>Mastering Windows 11 Taskbar Size Tweaks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/harmonizing-youtube-production-with-a-9-to-5-routine-for-2024/"><u>Harmonizing YouTube Production with a 9-to-5 Routine for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-workspace-switching-themes-on-win11/"><u>Personalize Your Workspace: Switching Themes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mitigate-application-crashes-unhandled-exception-error/"><u>Steps to Mitigate Application Crashes: Unhandled Exception Error</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-guide-to-top-sierra-dvd-makers-for-2024/"><u>Ultimate Guide to Top Sierra DVD Makers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-11-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/making-the-most-of-windows-11-using-dev-drive-effectively/"><u>Making the Most of Windows 11: Using Dev Drive Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/silence-windows-software-update-messages/"><u>Silence Windows Software Update Messages</u></a></li>
</ul></div>
