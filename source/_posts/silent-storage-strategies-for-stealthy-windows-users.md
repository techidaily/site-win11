---
title: Silent Storage Strategies for Stealthy Windows Users
date: 2024-07-13T10:33:33.558Z
updated: 2024-07-14T10:33:33.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Silent Storage Strategies for Stealthy Windows Users
excerpt: This Article Describes Silent Storage Strategies for Stealthy Windows Users
keywords: Stealthy PC Tips,Silent Windows Save,Secure Data Storage,Low-Noise Backups,Windows Quiet Saves,Hush PC Strategies,Invisible Storage Plan
thumbnail: https://thmb.techidaily.com/4916a6d483134297a5c5a01cc889f69aabd6291d81f85c697a7c6a88a387b0cb.jpg
---

## Silent Storage Strategies for Stealthy Windows Users

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on [how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful [not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.


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
<li><a href="https://youtube-tips.techidaily.com/ed-the-art-of-condensation-editing-youtube-video-durations/"><u>[Updated] The Art of Condensation  Editing YouTube Video Durations</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-feature-flashback-the-surviving-anniversary-of-7-elements/"><u>Windows 11 Feature Flashback: The Surviving Anniversary of 7 Elements</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-visibility-to-system-startups-on-win-os/"><u>Restoring Visibility to System Startups on Win OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-path-to-digital-riches-on-facebook/"><u>2024 Approved  The Path to Digital Riches on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-secrets-5-entertaining-hacks/"><u>Command Prompt Secrets: 5 Entertaining Hacks</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-journey-discovering-top-online-practitioners-for-2024/"><u>Yogic Journey  Discovering Top Online Practitioners for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workspace-multi-screen-setup-for-windows-11-users/"><u>Streamline Your Workspace: Multi-Screen Setup for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-editing-with-these-win11-videoscripts/"><u>Streamline Editing with These Win11 Videoscripts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-methods-to-access-apples-podcast-library/"><u>[New] Innovative Methods to Access Apple's Podcast Library</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-best-youtube-shorts-video-editing-apps-for-ios-and-android/"><u>2024 Approved  Best YouTube Shorts Video Editing Apps for iOS and Android</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-lava-blaze-curve-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Lava Blaze Curve 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bitlockers-encryption-is-broken-but-its-still-not-time-to-switch/"><u>BitLocker's Encryption Is Broken, But It's Still Not Time to Switch</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-nvidias-opengl-failure-no-3-in-windows-11/"><u>Eliminating NVIDIA's OpenGL Failure No. 3 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-workstation-access-the-hidden-side-of-rdp-in-win-11/"><u>Zero-Entry Workstation Access: The Hidden Side of RDP in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/four-practical-alternatives-to-bitlocker-in-winoss/"><u>Four Practical Alternatives to BitLocker in WinOSs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/screenplay-central-user-feedback-summary/"><u>Screenplay Central - User Feedback Summary</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-prime-7-cameras-elevating-virtual-event-coverage-and-vlogging/"><u>[New] Prime 7 Cameras Elevating Virtual Event Coverage and Vlogging</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-driver-verification-on-windows-enforcement-off-unsigned-loaded/"><u>Bypass Driver Verification on Windows: Enforcement Off, Unsigned Loaded</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-how-to-overlay-photos-on-computer-desktop-and-online/"><u>[Updated] In 2024, How to Overlay Photos on Computer (Desktop & Online)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-control-your-network-storage-on-windows-11/"><u>Navigate and Control Your Network Storage on Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/quickly-enhance-graphics-performance-with-a-simple-intel-hd-update-on-w10/"><u>Quickly Enhance Graphics Performance with a Simple Intel HD Update on W10.</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-aerial-choreography-the-fresh-take-on-bebops-parrot/"><u>In 2024, Aerial Choreography – The Fresh Take on Bebop's Parrot</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fps-in-csgo-essential-insights/"><u>Mastering FPS in CS:GO - Essential Insights</u></a></li>
<li><a href="https://win11.techidaily.com/dynamic-walls-for-windows-11-setting-lively-desktop-backdrops/"><u>Dynamic Walls for Windows 11: Setting Lively Desktop Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-verification-loading-unsigned-drivers-in-windows-2000xp/"><u>Bypassing Verification: Loading Unsigned Drivers in Windows 2000/XP</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-prevent-vscode-failures-w11/"><u>Essential Steps to Prevent VSCode Failures W11</u></a></li>
<li><a href="https://win11.techidaily.com/check-it-out-quick-fixes-for-your-webcam-and-mic-test/"><u>Check It Out: Quick Fixes for Your Webcam & Mic Test</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-vivo-s17-pro-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Vivo S17 Pro</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-endorsed-webcams-for-top-notch-zoom-engagement/"><u>[Updated] Expert-Endorsed Webcams for Top-Notch Zoom Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launchers-secure-login-failures-on-windows-os/"><u>Overcoming Launcher's Secure Login Failures on Windows OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/bring-your-hauls-to-life-the-ultimate-editing-tips-for-2024/"><u>Bring Your Hauls to Life  The Ultimate Editing Tips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-puzzle-of-non-opening-apps-in-w11/"><u>Unlocking the Puzzle of Non-Opening Apps in W11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-samsung-galaxy-a23-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-tecno-spark-20c-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-6-windows-usage-analysis-programs/"><u>Explore the Finest 6 Windows Usage Analysis Programs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-ultimate-recorder-toolkit-for-windows-1110-enthusiasts/"><u>[New] 2024 Approved  The Ultimate Recorder Toolkit for Windows 11/10 Enthusiasts</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-in-depth-evaluation-of-the-next-gen-slomo-video-tool/"><u>In 2024, The In-Depth Evaluation of the Next-Gen SloMo Video Tool</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-windows-11-to-notify-you-when-someone-accesses-your-camera/"><u>How to Force Windows 11 to Notify You When Someone Accesses Your Camera</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-xiaomi-redmi-a2plus-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Xiaomi Redmi A2+ to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-for-battery-life-extension-on-notebooks/"><u>Effective Techniques for Battery Life Extension on Notebooks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-s17t-phone-without-password-by-drfone-android/"><u>How To Unlock Vivo S17t Phone Without Password?</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-overestimated-cpu-usage-in-windows-performance-tool/"><u>Addressing Overestimated CPU Usage in Windows Performance Tool</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-discords-inadequate-search-mechanism/"><u>Reviving Windows Discord's Inadequate Search Mechanism</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-creative-channel-themes-get-them-for-free/"><u>[New] 2024 Approved  Creative Channel Themes  Get Them for Free</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-deadly-world-of-warcraft-fatality-windows-fix-guide/"><u>Beating the Deadly World of Warcraft Fatality: Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-for-the-delayed-folder-upload-issue-onedrive-errors/"><u>Swift Remedies for the Delayed Folder Upload Issue: OneDrive Errors</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-how-to-remove-static-noise-from-audio-in-seconds/"><u>New 2024 Approved How to Remove Static Noise From Audio in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-deactivated-speech-recognition-microsofts-windows-11-guide/"><u>Addressing Deactivated Speech Recognition: Microsoft's Windows 11 Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-erase-apple-iphone-11-pro-max-when-its-locked-within-seconds-by-drfone-ios/"><u>3 Ways to Erase Apple iPhone 11 Pro Max When Its Locked Within Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-abrupt-device-removal-errors-dxgi/"><u>Fixing Abrupt Device Removal Errors (DXGI)</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-quick-and-accurate-screenshot-of-uac-prompts/"><u>Techniques for Quick and Accurate Screenshot of UAC Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanics-of-controlling-gpgpu-priority-on-winos/"><u>The Mechanics of Controlling GPGPU Priority on WINOS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/strategies-to-mute-facebook-ads-on-videos/"><u>Strategies to Mute Facebook Ads on Videos</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unverified-session-error-by-steams-vac/"><u>Fixing Unverified Session Error by Steam's VAC</u></a></li>
</ul></div>
