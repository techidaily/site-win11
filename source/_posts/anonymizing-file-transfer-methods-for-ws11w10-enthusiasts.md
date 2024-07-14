---
title: "Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts"
date: 2024-07-13T11:18:47.408Z
updated: 2024-07-14T11:18:47.408Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts"
excerpt: "This Article Describes Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts"
keywords: Anon File Transfer,Secure File Sharing,Wi-Fi Privacy Tools,Hide Transfers Online,Encrypt Data Files,Wireless Anonymity Methods,Stealth File Exchange
thumbnail: https://thmb.techidaily.com/ea0b0402d1ea26fd039e2c69b50b2f77be9bc5a66db4bea78463e158540cfbfa.jpg
---

## Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts

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
<li><a href="https://facebook-video-share.techidaily.com/youtube-snippets-guide-essential-insights-unveiled-for-2024/"><u>YouTube Snippets Guide  Essential Insights Unveiled for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-1-5-best-url-trimmer-tools-for-youtube-videos/"><u>[New] 2024 Approved  1-5 Best URL Trimmer Tools for YouTube Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-master-the-art-of-editing-on-sierra-with-1-5-tools/"><u>In 2024, Master the Art of Editing on Sierra with #1-#5 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/adding-animated-backgrounds-to-windows-11-pcs-effortlessly/"><u>Adding Animated Backgrounds to Windows 11 PCs Effortlessly</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/how-to-get-more-nfl-viewers-for-your-sports-live-streaming-channel-for-2024/"><u>How To Get More NFL Viewers For Your Sports Live Streaming Channel for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-memory-use-by-edges-view2-process/"><u>Addressing Excessive Memory Use by Edge's View2 Process</u></a></li>
<li><a href="https://win11.techidaily.com/access-gpos-securely-a-guide-to-win11s-tools/"><u>Access GPOs Securely: A Guide to Win11's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-problems-with-windows-hello-fingerprint-detection/"><u>Addressing Common Problems with Windows Hello Fingerprint Detection</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-s-best-pc-video-dubbing-programs-reviews-and-downloads/"><u>Updated S Best PC Video Dubbing Programs Reviews and Downloads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-digital-memory-keepers-taking-screenshots-on-xbox-one-for-2024/"><u>[Updated] Digital Memory Keepers  Taking Screenshots on Xbox One for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/address-keyboard-malfunction-fixing-unresponsive-function-keys-on-windows-11/"><u>Address: Keyboard Malfunction - Fixing Unresponsive Function Keys on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oneplus-nord-3-5g-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On OnePlus Nord 3 5G Device</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-how-to-make-3d-cartoon-of-yourself/"><u>New 2024 Approved How to Make 3D Cartoon of Yourself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switchtonightvisioninnotepadwin/"><u>SwitchToNightVisionInNotepadWin</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-empty-directory-issue-in-windows-11-error-0x80070091/"><u>Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-swift-strategies-to-silence-social-media-videos-for-2024/"><u>[Updated] Swift Strategies to Silence Social Media Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-the-curve-using-vivetool-on-your-pc/"><u>Ahead of the Curve: Using ViVeTool on Your PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-your-apple-iphone-7-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>How to Unlock Your Apple iPhone 7 Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-elevating-your-game-with-top-10-tiktok-analytics-instruments/"><u>[Updated] Elevating Your Game with Top 10 TikTok Analytics Instruments</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-printouts-from-powerpoint-in-windows-9-top-fixes-unveiled/"><u>Accurate Printouts From PowerPoint in Windows: 9 Top Fixes Unveiled</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-infinix-note-30-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Infinix Note 30 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-motorola-moto-g04-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Motorola Moto G04 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/activating-and-utilizing-end-task-option-in-windows-11-interface/"><u>Activating and Utilizing End Task Option in Windows 11 Interface</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-increase-length-of-youtube-creative-work/"><u>[New] Increase Length of YouTube Creative Work</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-broadcasting-with-breeze-tips-for-fb-video-sharing/"><u>[Updated] Broadcasting with Breeze  Tips for FB Video Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-installation-process-via-registry/"><u>Altering Windows Installation Process via Registry</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-mastering-the-deletion-of-drive-partitions-in-win-os/"><u>Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-fault-finders-in-windows/"><u>Addressing Inoperative Fault Finders in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/authorize-superuser-power-with-command-prompt/"><u>Authorize Superuser Power with Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-restart-utilizing-windows-11s-quick-start-function/"><u>Accelerating System Restart: Utilizing Windows 11'S Quick Start Function</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-tecno-spark-10-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Tecno Spark 10 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-action-to-archive-a-guide-to-top-screen-recording-tools-for-2024/"><u>[Updated] Action to Archive  A Guide to Top Screen Recording Tools for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-expert-shortcuts-for-savvy-screen-capture-on-your-pc/"><u>2024 Approved  Expert Shortcuts for Savvy Screen Capture on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-the-shrinkage-optimal-windows-11-icons/"><u>Avoid the Shrinkage: Optimal Windows 11 Icons</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-farm-frontier-favorites-similar-titles-galore/"><u>[New] In 2024, Farm Frontier Favorites  Similar Titles Galore</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-your-iphone-footage-into-vr/"><u>2024 Approved  Transforming Your iPhone Footage Into VR</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-s23-ultra-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy S23 Ultra Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-forbidden-page-in-windows-environment/"><u>Addressing Forbidden Page in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-quick-access-for-file-explorer-through-onedrive/"><u>Adjusting Quick Access for File Explorer Through OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-code-0xca00a009/"><u>Addressing Windows Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-configuration-of-win11-connectivity-options/"><u>Accessible Configuration of Win11 Connectivity Options</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-novices-map-to-snapseed-photoshop-wonders/"><u>[Updated] The Novice's Map to Snapseed Photoshop Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-security-strategies-in-powertoys/"><u>Advanced File Security Strategies in PowerToys</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/whatsapp-status-video-makers-free-paid-and-everything-in-between/"><u>WhatsApp Status Video Makers Free, Paid, and Everything in Between</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-a00f429f-in-windows-camera-functionality/"><u>Addressing Error A00F429F in Windows' Camera Functionality</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-oppo-a78-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Oppo A78 Phone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-unlocking-facebooks-full-potential-with-strategic-video-ads/"><u>[New] Unlocking Facebook's Full Potential with Strategic Video Ads</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-make-windows-11-search-invisible/"><u>Advanced Tactics: Make Windows 11 Search Invisible</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-unsatisfied-system-demands-sign-in-win11/"><u>Avoid Unsatisfied System Demands Sign in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-compression-and-archiving-tools/"><u>Activating Windows Compression & Archiving Tools</u></a></li>
<li><a href="https://win11.techidaily.com/adding-removable-storage-via-explore-navigation-menu/"><u>Adding Removable Storage via Explore Navigation Menu</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-data-breaches-proper-password-addition-in-windows/"><u>Avoiding Data Breaches: Proper Password Addition in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/activating-and-deactivating-the-essential-windows-key/"><u>Activating & Deactivating the Essential Windows Key</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-volume-control-on-windows-bluetooth/"><u>Amplifying Volume Control on Windows-Bluetooth</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-seamless-software-operation-with-4-key-pcts/"><u>Achieve Seamless Software Operation with 4 Key PCTs</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-with-11-troubleshooting-windows-tips/"><u>Avoid Frustration with 11 Troubleshooting Windows Tips</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-lockout-interval-after-multiple-login-failures/"><u>Adjusting Lockout Interval After Multiple Login Failures</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-unseen-viewers-route-navigating-instagram-stories-with-anonymous-viewing/"><u>[New] In 2024, The Unseen Viewer's Route  Navigating Instagram Stories with Anonymous Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/ai-driven-windows-11-an-inevitable-shift/"><u>AI-Driven Windows 11: An Inevitable Shift</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-deciphering-instagrams-video-snippet-size/"><u>In 2024, Deciphering Instagram's Video Snippet Size</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/schematic-gamers-graphs/"><u>SCHEMATIC GAMER'S GRAPHS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-rockalldlldll-unavailability-in-pcs/"><u>Addressing Rockalldll.dll Unavailability in PCs</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-achieve-fluent-fb-video-posting-windows-linux-ios-and-android-tips/"><u>[New] 2024 Approved  Achieve Fluent FB Video Posting  Windows, Linux, iOS & Android Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leading-virtual-reality-goggles-makers/"><u>In 2024, Leading Virtual Reality Goggles Makers</u></a></li>
</ul></div>
