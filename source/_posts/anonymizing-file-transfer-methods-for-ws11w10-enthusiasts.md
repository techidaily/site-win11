---
title: "Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts"
date: 2024-08-15T23:17:21.778Z
updated: 2024-08-16T23:17:21.778Z
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

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-enlightenment-streams-foremost-ed-resources-online/"><u>[New] 2024 Approved  Enlightenment Streams  Foremost Ed Resources Online</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-perfect-your-video-calls-essential-10-free-recording-solutions-for-slack/"><u>[New] 2024 Approved  Perfect Your Video Calls  Essential 10 Free Recording Solutions for Slack</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-become-a-meme-genius-with-kinemaster-skills/"><u>[New] In 2024, Become a Meme Genius with KineMaster Skills</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-interest-to-action-formulating-video-topics-with-google-trends/"><u>[New] In 2024, From Interest to Action  Formulating Video Topics with Google Trends</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-prime-5-replacements-for-twitter-users/"><u>[New] In 2024, Prime 5 Replacements for Twitter Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-top-tips-for-quick-and-reliable-recording-of-presentations/"><u>[New] In 2024, Top Tips for Quick and Reliable Recording of Presentations</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-inexpensive-mirrorless-and-dslr-options/"><u>[New] Inexpensive Mirrorless & DSLR Options</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-photography-tips-accurately-annotating-dates-on-pictures/"><u>[New] Photography Tips  Accurately Annotating Dates on Pictures</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-analyzing-hero5-black-and-yi-4k-cameras-for-modern-adventurers/"><u>[Updated] 2024 Approved  Analyzing Hero5 Black & Yi 4K Cameras for Modern Adventurers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-download-free-mcb-logo-templates-for-2024/"><u>[Updated] Download Free MCB Logo Templates for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-essential-tips-for-applying-luts-in-adobe-photoshop-cc-for-2024/"><u>[Updated] Essential Tips for Applying LUTs in Adobe PhotoShop CC for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-preserving-your-online-reputation-amidst-faux-endorsements/"><u>[Updated] Preserving Your Online Reputation Amidst Faux Endorsements</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-notable-book-trailers-showcasing-stories/"><u>2024 Approved  Notable Book Trailers Showcasing Stories</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/4-ways-to-unlock-iphone-13-mini-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>4 Ways to Unlock iPhone 13 mini to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-scripting-techniques-upgraded-file-system-interactions/"><u>Advanced Scripting Techniques: Upgraded File System Interactions</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-void-seven-strategies-for-stabilizing-obs-studio-link/"><u>Avoiding the Void: Seven Strategies for Stabilizing OBS Studio Link</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/backup-your-memories-camera-roll-to-snapchat-explained/"><u>Backup Your Memories  Camera Roll to Snapchat Explained</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-gionee-f3-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Gionee F3 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-no-sound-on-connected-devices-windows-edition/"><u>Clearing Up No Sound on Connected Devices, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-bluetooth-device-unable-to-use-buttons-or-mute/"><u>Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-synchronization-for-ios-and-windows-calendars/"><u>Cross-Platform Synchronization for iOS & Windows Calendars</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-solving-the-failure-errors-in-discord-installation/"><u>Decoding and Solving the Failure Errors in Discord Installation</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-credentials-a-fix-guide/"><u>Decoding Windows Credentials: A Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/direct-download-tactics-for-new-windows-users/"><u>Direct Download Tactics for New Windows Users</u></a></li>
<li><a href="https://facebook.techidaily.com/diving-deep-into-the-practicality-and-privacy-implications-of-social-app-sign-ins-via-facebook/"><u>Diving Deep Into the Practicality & Privacy Implications of Social App Sign-Ins via Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-read-only-filters-in-win-os/"><u>Eliminating Read-Only Filters in Win OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/from-creation-to-apple-your-podcasts-journey/"><u>From Creation to Apple  Your Podcast's Journey</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-ge-share-function-failures/"><u>Guide to Rectify GE Share Function Failures</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-signals-secure-connections-windows-wi-fi-tips/"><u>Hidden Signals, Secure Connections: Windows Wi-Fi Tips</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-deal-with-windows-error-x70-a-comprehensive-checklist/"><u>How To Deal with Windows Error X70: A Comprehensive Checklist</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-brightness-function-key-not-working-in-windows-11/"><u>How to Fix the Brightness Function Key Not Working in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-power-plans-to-default-in-windows/"><u>How to Reset Power Plans to Default in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-speed-up-download-speeds-in-utorrent-for-windows/"><u>How to Speed Up Download Speeds in uTorrent for Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-from-ideas-to-action-how-to-transform-photos-into-engaging-mobile-videos/"><u>In 2024, From Ideas to Action  How to Transform Photos Into Engaging Mobile Videos</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-disabled-apple-iphone-15-plusipad-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock Disabled Apple iPhone 15 Plus/iPad Without Computer</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-xiaomi-redmi-k70-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Xiaomi Redmi K70? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-speedy-shots-masterful-iphone-time-lapse-methods/"><u>In 2024, Speedy Shots  Masterful iPhone Time Lapse Methods</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-silent-mode-malfunction-a-step-by-step-guide-to-workaround-solutions/"><u>IPhone Silent Mode Malfunction: A Step-by-Step Guide to Workaround Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-media-8-superior-windows-video-slicers/"><u>Master Your Media - 8 Superior Windows Video Slicers</u></a></li>
<li><a href="https://buynow-help.techidaily.com/mastering-big-screen-brilliance-an-insightful-look-at-the-samsung-galaxy-note-review/"><u>Mastering Big-Screen Brilliance: An Insightful Look at the Samsung Galaxy Note Ⅸ Review</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-proxy-configuration-in-win-11/"><u>Mastery of Proxy Configuration in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/merrymaking-with-gifted-windows-apps-on-xmas-day/"><u>Merrymaking with Gifted Windows Apps on Xmas Day</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-xpatch-issues-error-0x80073712/"><u>Navigating Through XPatch Issues: Error 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winerror-740-resolving-operation-needs-promotion-in-windows-os/"><u>Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-installation-mishaps-on-windows-10-and-11/"><u>Repairing Installation Mishaps on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-connection-speed-clearing-steam-dns-in-windows/"><u>Revamping Connection Speed: Clearing Steam DNS in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-post-zestful-days-of-life-on-windows-pcs/"><u>Reviving Post-Zestful Days of Life on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-local-drive-space-in-win11-without-loss-of-files-max-156-chars/"><u>Securely Manage Local Drive Space in Win11 Without Loss of Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-out-windows-11-drag-and-drop-issues/"><u>Smooth Out Windows 11 Drag-and-Drop Issues</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-silent-audio-during-powerpoint-presentations/"><u>Solutions to Silent Audio During PowerPoint Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/stealthy-controls-for-displaying-windows-clock/"><u>Stealthy Controls for Displaying Windows Clock</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-browsing-game-master-microsoft-edge-gestures-on-windows-11/"><u>Step-Up Your Browsing Game: Master Microsoft Edge Gestures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-gear-use-windows-widgets-for-efficiency/"><u>Streamlining Your Gear Use: Windows Widgets for Efficiency</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-picks-must-watch-lgbt-films-streaming-on-netflix-this-july/"><u>Top Picks: Must-Watch LGBT Films Streaming On Netflix This July</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-couldnt-load-page-in-windows-marketplace/"><u>Troubleshooting 'Couldn't Load Page' In Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-gaps-in-systems-startup-list/"><u>Troubleshooting Gaps in System's Startup List</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-infinix-note-30-vip-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Infinix Note 30 VIP Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Realme 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-rename-your-user-account-directory/"><u>Win 11: Rename Your User Account Directory</u></a></li>
<li><a href="https://win11.techidaily.com/win11-steps-to-correct-steam-file-privileges-failure/"><u>Win11 Steps to Correct Steam File Privileges Failure</u></a></li>
</ul></div>
