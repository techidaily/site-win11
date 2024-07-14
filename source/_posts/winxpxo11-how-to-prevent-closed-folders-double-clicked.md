---
title: WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked
date: 2024-07-13T10:36:56.784Z
updated: 2024-07-14T10:36:56.784Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked
excerpt: This Article Describes WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked
keywords: WinXPSecurityTips,XPFolderProtectionGuide,XO11FixClosedFolders,PreventDoubleClickError,XPSecureFoldersMethod,ClosingFolderTroubleshoot,DoubleClickedErrorXP
thumbnail: https://thmb.techidaily.com/e1b4d87010351d8cde0b7e296f0f8bee20d2f2f6dcddada5b81adefe0c805246.JPG
---

## WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked

 Some users have posted on help chat forums about folders not opening when they double-click them in Windows File Explorer. This means users can’t access folders by double-clicking on directories. There isn’t a specific error message associated with this issue.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.

## 1\. Adjust File Explorer Options

 File Explorer has alternative single-click and double-click options for opening items. If single-click is set, double-clicking folders won’t open them. Try single-clicking a folder to see if that works. If it does, then you probably need to select the **Double-click to open an item** option like this:

1. Right-click on your taskbar’s **Start** button to select a **Search** shortcut.
2. Type "File Explorer options" to find a matching search result.
3. Click **File Explorer Options** to bring up the window with that title.
4. Select the **Double-click to open an item** radio button.  
![The Double-click to open an item option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-to-open-an-item-option.jpg)
5. Click the **Apply** button for saving settings.
6. Select **OK** to close the File Explorer Options window.

 If you find the **Double-click to open item** option is already selected, you could try selecting the single-click setting instead. That way, you might at least be able to access your folders by single-clicking them. Or, proceed with applying the other resolutions below.

## 2\. Adjust the Double-Click Mouse Speed

 The mouse **Double-click speed** setting can feasibly cause this issue if it’s set too fast. So, you might need to lower that setting a little bit. This is how you can adjust the mouse double-click speed:

1. First, bring up the tool for finding files with the **Windows** key + **S** hotkey that opens it.
2. Type the "mouse settings" keyword phrase.
3. Click **Mouse settings** to open a Settings window.
4. Next, click the **Additional mouse** options in Settings.  
![The Additional mouse settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/additional-mouse-settings.jpg)
5. Drag the **Double-click speed** bar’s slider left to slow it down.  
![The Double-click speed setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-speed-setting.jpg)
6. Select **Apply** and click **OK** to set the new double-click speed.

 The required double-click speed for opening folders will now be slower than before. So, you won’t need to double-click so quickly.

## 3\. Scan and Repair Windows System Files

 Microsoft advises users to run system file scans when Windows functions aren’t working right. In this case, there’s an issue with the folders’ double-click functionality.

 So, [run a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to see if Windows Resource Protection detects any corrupted system files. If so, Windows Resource Protection will probably also repair the files detected, which could fix the double-clicking of folders not opening.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow3.jpg)

## 4\. Edit the Shell Registry Key

 Quite a few users have confirmed editing the **shell** registry key can fix the double-clicking of folders not working in Windows 11/10\. Those users changed that key’s **(Default)** string value to fix the issue. These are the steps for editing the **shell** key:

1. Press the **Windows** logo keyboard key + **R** to start Run.
2. Input a **regedit** (Registry Editor) Run command inside the **Open** box and select **OK**.
3. Bring up the shell key by inputting this path inside the registry address box:  
`Computer\HKEY_CLASSES_ROOT\Directory\shell`
4. Double-click **(Default)** inside the **shell** key.  
![The shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-shell-key.jpg)
5. If the **Value data** box is empty, or set differently, input **none** there as in the snapshot directly below.  
![The (Default) string value for the shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-default-string-value.jpg)
6. Click **OK** to save the new **(Default)** string value.

 You might need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for this registry tweak to take effect. Alternatively, restart Windows and then try double-clicking a folder to see if it opens.

## 5\. Edit the Mouse Registry Key

 Double-click issues can arise when string values for the **Mouse** registry key have been altered from their default settings (typically by third-party apps). To be more specific, **MouseHoverWidth**, **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** are four **Mouse** key strings you might need to restore to default values for to fix this issue.

 To do so, edit the **Mouse** registry key like this:

1. Bring up Registry Editor as instructed for the first two steps of the previous potential solution.
2. Next, go to the **Mouse** key by entering this path within Registry Editor’s address bar:  
`Computer\HKEY_CURRENT_USER\Control Panel\Mouse`
3. Double-click the **MouseHoverWidth** string.  
![The Mouse key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/mouse-key.jpg)
4. If set any differently, input **4** inside the **Value data** box and select **OK**.  
![The MouseHoverWidth string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-mousehoverwidth-string-value.jpg)
5. Repeat the previous two steps for the **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** strings in the **Mouse** key. Set their values to **4**, just like you did for the **MouseHoverWidth**string.

 When you’ve finished adjusting those string values, exit the Registry Editor and restart your PC. If you find all those strings are already set to four, you don’t need to change them.

## 6\. Turn Off Controlled Folder Access

 Some users have said they fixed the double-clicking of folders not working by turning off controlled folder access. Controlled folder access is the Windows Security feature that blocks unauthorized apps from modifying contents inside protected directories. Thus, enabling that feature restricts folder access.

 So, try turning off controlled folder access like this:

1. Open Windows Security by double-clicking the small shield icon inside the system tray area of your taskbar.
2. Click **Virus & threat protection** in Windows Security’s left navigation sidebar.  
![The tab sidebar in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-security-s-tab-sidebar.jpg)
3. Scroll down a little and click on **Manage ransomware protection**.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/manage-ransomware-protection.jpg)
4. Click the **Controlled folder access** toggle switch to turn off that setting.  
![The Controlled folder access setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/controlled-folder-access-setting.jpg)

 Then, go into File Explorer and try opening some folders again to see if disabling that security feature makes a difference. If it does, then it’s probably best to leave controlled folder access off.

## 7\. Revert Windows to a Restore Point

 Rolling Windows back to a saved restoration point is one of the last things to try if no other potential fixes for this issue work. Applying this potential fix will undo system changes made and remove software installed after your chosen restore point date.

 However, it’s only worth reverting Windows if you can select a restore point that will roll back the OS to a time when you could open folders by double-clicking them.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-system-restore-tool.jpg)

 To apply this potential fix, check out our guide on [utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/). The System Restore tool will need to be enabled for you to select a restoration point. Be prepared to reinstall software packages a selected restore point deletes, which you can check by clicking **Scan for affected programs** in System Restore.

## Make Double-Clicking Open Folders on Windows Again

 Those potential fixes for double-clicking folders not working will probably resolve that Windows 11/10 issue in most cases. We can’t promise they’re guaranteed, but lots of users have confirmed some of them work.

 Beyond those possible resolutions, you might have to try something more drastic, like a full system reset or in-place Windows upgrade.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-how-to-change-text-in-premiere-pro/"><u>New In 2024, How To Change Text In Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-visual-impact-with-auto-color-settings-in-windows-11/"><u>Maximize Visual Impact with Auto Color Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clumped-up-windows-11-icon-grouping/"><u>Adjusting Clumped-Up Windows 11 Icon Grouping</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-domain-users-biometric-use-on-w11/"><u>Strategizing Domain Users' Biometric Use on W11</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-winning-strategy-running-windows-11-on-mac-via-parallels/"><u>Craft a Winning Strategy: Running Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-ultimate-guide-to-dynamic-youtube-openers-in-imovie/"><u>[Updated] The Ultimate Guide to Dynamic YouTube Openers in iMovie</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastery-overcoming-adobe-premieres-srt-barriers-for-2024/"><u>Mastery Overcoming Adobe Premiere's SRT Barriers for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-elevate-online-engagement-unlocking-the-potential-of-voicemod-on-discord-for-2024/"><u>[New] Elevate Online Engagement  Unlocking the Potential of VoiceMod on Discord for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/pcandroid-tutorial-successful-facebook-video-sharing-for-2024/"><u>PC/Android Tutorial  Successful Facebook Video Sharing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bring-home-the-fun-smartphone-games-to-desktop-with-win-11-and-google-play/"><u>Bring Home the Fun: Smartphone Games to Desktop with Win 11 & Google Play</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-how-to-edit-mp4-video-in-macwindows-windows-8-included/"><u>Updated 2024 Approved How to Edit MP4 Video in Mac/Windows (Windows 8 Included)</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-stop-laptops-internal-keystrokes/"><u>Step-by-Step: Stop Laptop's Internal Keystrokes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-desktop-trash-bin-for-permanently-deleting-files-on-windows-11-and-11/"><u>How to Add a Desktop Trash Bin for Permanently Deleting Files on Windows 11 & 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-elevate-your-video-production-adobe-premiere-pro-on-mac-for-2024/"><u>New Elevate Your Video Production Adobe Premiere Pro on Mac for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-identifiable-usb-port-error-on-windows-11/"><u>Fixing Non-Identifiable USB Port Error on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-clearing-up-opaque-video-views-on-youtube/"><u>[New] Clearing Up Opaque Video Views on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-data-handling-mastering-windows-11s-disk-access-methods/"><u>Streamline Data Handling: Mastering Windows 11'S Disk Access Methods</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-reversing-rdp-monochrome/"><u>Strategies for Reversing RDP Monochrome</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unwinding-upside-down-asmr-to-support-zzzs/"><u>In 2024, Unwinding Upside-Down  ASMR to Support Zzz's</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-tecno-pova-5-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Tecno Pova 5 FRP Bypass Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/no-plug-just-play-connect-dualshock-3-to-pc/"><u>No Plug, Just Play: Connect DualShock 3 to PC</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-zoom-for-beginners-essential-webinar-skills-unveiled/"><u>2024 Approved  Zoom for Beginners  Essential Webinar Skills Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-the-windows-firewall-with-precision/"><u>Resetting the Windows Firewall with Precision</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-seeking-clearance-can-you-upload-media-on-fb/"><u>2024 Approved  Seeking Clearance  Can You Upload Media on FB?</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-enable-widgets-on-windows-11-system/"><u>Harness the Power: Enable Widgets on Windows 11 System</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unearthed-30-window-11-insider-strategies-to-boost-performance/"><u>[New] 2024 Approved  Unearthed  30 Window 11 Insider Strategies to Boost Performance</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crafting-a-viral-phenomenon-on-igtv-with-savvy-hash-tags-for-2024/"><u>Crafting a Viral Phenomenon on IGTV with Savvy Hash Tags for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-pre-buying-your-ideal-win-pc/"><u>The Ultimate Guide to Pre-Buying Your Ideal Win PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/silly-suggestions-10-hilarious-concepts-for-quick-quirky-videos-for-2024/"><u>Silly Suggestions  10 Hilarious Concepts for Quick, Quirky Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/end-session-of-unknown-windows-users-effectively/"><u>End Session of Unknown Windows Users Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-pc-graphics-fix-in-windows-1011/"><u>Mastering PC Graphics Fix in Windows 10/11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/elevate-your-conversation-game-mastering-the-art-of-sending-gifs-in-snapchat-for-2024/"><u>Elevate Your Conversation Game  Mastering the Art of Sending GIFs in Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-refusal-to-execute-exe-files/"><u>Decoding Windows' Refusal to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-memory-shortage-error-in-windows-based-vms/"><u>Solutions for 'Memory Shortage' Error in Windows-Based VMs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-iphone-14-pro-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from iPhone 14 Pro</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-elite-zero-cost-fb-picturemovie-composer-for-2024/"><u>[Updated] Elite Zero-Cost FB Picture/Movie Composer for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-how-to-manual-for-time-stamped-videos-on-youtubes/"><u>[New] 2024 Approved  The How-To Manual for Time-Stamped Videos on YouTubes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-realme-gt-neo-5-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Realme GT Neo 5 to iPhone Easily | Dr.fone</u></a></li>
</ul></div>
