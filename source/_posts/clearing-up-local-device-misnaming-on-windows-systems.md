---
title: Clearing Up Local Device Misnaming on Windows Systems
date: 2024-07-29T15:51:07.870Z
updated: 2024-07-30T15:51:07.870Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up Local Device Misnaming on Windows Systems
excerpt: This Article Describes Clearing Up Local Device Misnaming on Windows Systems
keywords: Windows Device Naming Errors,Resolve System Label Issues,Windows Label Fixation,Unnamed Devices in OS,Correcting PC Tags,Windows Identifier Correction,Eradicate Mislabeled Hardware
thumbnail: https://thmb.techidaily.com/5a612b69f151ee0b6ea165a5e0a8368a6294f13aca50623658d8bbb7241b81d0.jpg
---

## Clearing Up Local Device Misnaming on Windows Systems

 The Local device name is already in use error is not particularly unusual. If you work with any type of network, even a local network, you are quite likely to encounter it at some point. Luckily, it is also usually easy to resolve.

 Here are the most common causes of this error, along with the most likely solutions.

## What Causes the Local Device Name Error?

 There can be a couple of possible causes of this error, but pinpointing the exact cause can be difficult. The most common are unassigned drive letters and incorrect file and printer sharing settings.

 It is also possible that a lack of space on the network server can result in this error appearing. You should check this possibility first. If lack of storage is the cause, none of the following solutions will make a difference.

 If the network server has ample space, you can move on to trying the methods below to solve the problem on your local device.

## 1 Enable File and Printer Sharing

[You should always keep your firewall enabled](https://www.makeuseof.com/tag/5-reasons-use-firewall/) , but it can sometimes interfere with file and printer sharing. This can lead to seeing the Local device name is already in use error. Luckily you can enable file and printer sharing easily in the firewall settings.

 If you're using a third-party firewall, refer to the documentation to find the setting. Here's how to enable file and printer sharing in the Microsoft Firewall.

1. Search for Control Panel using Windows Search, and click the search result to open it.
2. Click**System and Security > Windows Defender Firewall** to see the firewall settings.
3. In the left menu, click**Allow an app or feature through the firewall** and then click the**Change settings** button.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![Windows firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-printer-sharing.jpg)
4. Scroll down to find**File and Printer Sharing** in the list, and click the**Public** checkbox.
5. Click**Ok** and restart your computer to apply the change.

 Occasionally, the file and printer sharing settings for the firewall can get reset after a major update. Just because you know you have enabled it in the past, it is worth checking again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## 2 Remap the Network Drive With Command Prompt

 Windows will automatically assign a letter to your network drive. During network mapping, the assigned letters can become mixed and even be missing altogether. Remapping the network drive can fix this and prevent the error.

1. The best way to remap the network drive is through the Command Prompt. Search for**cmd** in Windows Search and select**Run as Administrator** .
2. At the cursor, type:**net use D /delete** . Replace**D** with the drive letter you want to delete. Then press**Enter** .  
![the remap network drive command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remap-network-drive.jpg)
3. Now remap the drive by typing:**net use D: \\\\server\\share /user:username password** . Replace the drive letter and user and username password with the relevant details.

 If this doesn't help, you may need to try reassigning the drive letters manually. The end result is similar, but sometimes remapping won't work when manually reassigning the drive path will work.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3 Re-assign Drive Letters

 Another common cause of this error is an incorrectly assigned drive letter. Reassigning a drive letter is easy, as long as you don't run into the Drive letter not available error.

1. Search for**Disk Management** using Windows Search, or right-click the Start Menu and select it from the hidden menu.
2. In Disk Management, find the partition or drive you want to change and right-click on it.
3. Select**Change Drive Letter and Paths** , and then click the**Add** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![reassigning drive letter in disk management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reassign-drive-letter.jpg)
4. Click**Assign the following drive letter** and use the drop-down menu to choose a new letter for the partition or drive.

 If the drive letter you require is not available, it may already be being used on another drive or partition. It could also be associated with a removable drive that is not currently connected. If the A and B drive letters are available, and they often aren't, it is best not to use them. These letters are traditionally reserved for floppy drives and for use with old OS versions.

 Learn more about[why drive letters usually start with C on Windows](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4 Reinitialize the Computer Browser

 A less likely solution to this error, but one that does sometimes help, is reinitializing the browser. Browser settings can, in some cases, interfere with network drive settings. By stopping the browser and reinitializing it, those settings should be reverted.

1. Open Windows Search and type**cmd** . In the result, select**Command Prompt** and click**Run as Administrator** .
2. At the Command Prompt cursor, type:**net stop "Computer Browser"** and then press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![reinitialize the browser on command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinitialize-browser.jpg)
3. When the command finishes executing, type:**net start "Computer Browser"** and press**Enter** .
4. You can now close the Registry Editor and check to see if the error persists.

 Reinitializing the browser is different from simply closing and reopening the browser window. It is a much more forceful solution to clearing any browser settings that may be in conflict.

 Learn how to optimize and get the most from your computer with these[essential Windows performance tips](https://www.makeuseof.com/tag/windows-10-faster-performance/) .

## 5 Delete the MountPoints Registry Key

 If none of the above solutions have fixed the problem, you can try deleting the MountPoints registry key as a last resort. This key stores data about USB and other removable drives. Deleting the key can sometimes resolve conflicts in drive letter assignments.

1. Deleting the MountPoints key shouldn't cause problems, but it is best to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case. Do this before you continue.
2. Open the Registry Editor by searching for it in Windows Search.
3. Navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer** .  
![delete mountpoints in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-mountpoints.jpg)
4. Look for the**MountPoints2** key in the right-hand panel, right-click on it and select**Delete** .
5. Close the Registry Editor and restart your computer.

 The MountPoint registry key will be regenerated after deleting and restarting. You can then check to see if this fixed the Local Device name is already in use error.

## Fixing Local Device Name Errors on Windows

 The Local device name is already in use error is not uncommon, and it can be frustrating. But by working through the solutions here, you will normally be able to fix it within a few minutes. Just be sure to check the remaining storage on the network server before you start digging deeper.


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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-advanced-obs-setup-for-skype-screenshots/"><u>[New] 2024 Approved  Advanced OBS Setup for Skype Screenshots</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-amplify-your-youtubes-interaction-with-emojis/"><u>[New] 2024 Approved  Amplify Your Youtubes' Interaction with Emojis</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-how-to-effortlessly-share-vimeo-video-on-instagram-for-2024/"><u>[New] How to Effortlessly Share Vimeo Video on Instagram for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-blend-sounds-in-presentation-ppts/"><u>[New] In 2024, Blend Sounds in Presentation PPTs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-calming-chronicles-on-screen-evaluating-bedtime-story-videos/"><u>[New] In 2024, Calming Chronicles on Screen  Evaluating Bedtime Story Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-solutions-for-balancing-iphone-hdr-footage-with-advanced-premiere-pro-tools/"><u>[New] In 2024, Solutions for Balancing iPhone HDR Footage with Advanced Premiere Pro Tools</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-ultimate-battle-of-video-capturing-apps/"><u>[New] In 2024, Ultimate Battle of Video Capturing Apps</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-optimize-your-streams-with-advanced-obs-techniques-android-for-2024/"><u>[New] Optimize Your Streams with Advanced OBS Techniques, Android for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-mastering-youtube-clips-beginnings-and-conclusions-on-a-budget/"><u>[Updated] 2024 Approved  Mastering YouTube Clips  Beginnings & Conclusions on a Budget</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-unlock-hd-potential-for-your-social-media-platform-fb/"><u>[Updated] 2024 Approved  Unlock HD Potential for Your Social Media Platform (FB)</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-adding-dynamic-blurs-to-ai-designed-graphics/"><u>[Updated] In 2024, Adding Dynamic Blurs to AI-Designed Graphics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-flipping-the-script-on-instagrams-video-content/"><u>[Updated] In 2024, Flipping the Script on Instagram's Video Content</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-incorporating-on-screen-words-a-tiktok-video-transformation/"><u>[Updated] In 2024, Incorporating On-Screen Words  A TikTok Video Transformation</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigate-improved-output-with-mobile-lut-adjustments/"><u>[Updated] Navigate Improved Output with Mobile LUT Adjustments</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-archive-your-art-innovative-cost-effective-photo-storage-platforms/"><u>2024 Approved  Archive Your Art  Innovative, Cost-Effective Photo Storage Platforms</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-clearframew11-easy-instant-screen-recording-for-windows/"><u>2024 Approved  ClearFrameW11  Easy, Instant Screen Recording for Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-ps5-gaming-setup-top-5-display-recommendations/"><u>2024 Approved  PS5 Gaming Setup  Top 5 Display Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-from-vpn-client-errors/"><u>Addressing Disconnected From VPN Client Errors</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/best-live-sound-experience-service-for-2024/"><u>Best Live Sound Experience Service for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-vms-with-virtualbox-70-now-for-windows-11-users/"><u>Boosting Your VMs with VirtualBox 7.0, Now for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-backup-error-in-windows-file-history-configuration/"><u>Correcting “Backup Error” In Windows File History Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-how-choosing-a-pc-over-a-mac-can-benefit-you-more-9/"><u>Decoding How Choosing a PC Over A Mac Can Benefit You More (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-text-glyphs-in-windows-11/"><u>Discovering Text Glyphs in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-for-identifying-high-space-usage-windows/"><u>Effective Strategies for Identifying High-Space Usage Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliciting-hidden-taskbar-recon-in-windows-11/"><u>Eliciting Hidden Taskbar Recon in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-methods-for-tcpip-port-audits-on-windows/"><u>Exploring Methods for TCP/IP Port Audits on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-browsers-to-desktops-website-conversion-guide/"><u>From Browsers to Desktops: Website Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/growth-plans-for-windows-hard-drive-without-data-loss/"><u>Growth Plans for Windows Hard Drive without Data Loss</u></a></li>
<li><a href="https://win11.techidaily.com/guide-dealing-with-invalid-app-installs-on-windows/"><u>Guide: Dealing with Invalid App Installs on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-11-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-10-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-this-device-is-being-used-by-another-application-audio-error/"><u>How to Fix Windows' This Device Is Being Used by Another Application Audio Error</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-vivo-s17-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-samsung-galaxy-a54-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Samsung Galaxy A54 5G Device SIM</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-vivo-v27-easily-by-drfone-android/"><u>In 2024, How To Unlock a Vivo V27 Easily?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-motorola-g24-power-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Motorola G24 Power Phone Without Password?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-redefining-visual-standards-hdr-vs-standard-sdr/"><u>In 2024, Redefining Visual Standards  HDR Vs. Standard SDR</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-take-your-online-presence-to-new-heights-with-youtube-edits-in-sony-vegas/"><u>In 2024, Take Your Online Presence to New Heights with YouTube Edits in Sony Vegas</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-samsung-galaxy-a34-5g-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Samsung Galaxy A34 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/latest-rtx210-windows-compatibility-fix/"><u>Latest RTX210 Windows Compatibility Fix</u></a></li>
<li><a href="https://extra-support.techidaily.com/lift-run-dance-select-the-most-motivating-exercise-tracks-for-2024/"><u>Lift, Run, Dance - Select the Most Motivating Exercise Tracks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-elevated-commands-always-access-terminal-as-admin/"><u>Mastering Elevated Commands: Always Access Terminal as Admin</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-microsoft-store-eradicating-code-0x80072f30/"><u>Mastering the Microsoft Store: Eradicating Code 0X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-play-top-6-windows-11-fps-counters/"><u>Mastering Windowed Play: Top 6 Windows 11 FPS Counters</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-browser-blues-overcome-site-blockades-with-these-tips/"><u>Microsoft Browser Blues? Overcome Site Blockades with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/multitasking-made-simple-windows-1110-window-cascade-guide/"><u>Multitasking Made Simple: Windows 11/10 Window Cascade Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-deletion-warning-settings-on-pcs/"><u>Navigating Deletion Warning Settings on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/no-illusions-allowed-true-tales-of-unmasking-windows-ploys/"><u>No Illusions Allowed: True Tales of Unmasking Windows Ploys</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-pcs-idle-state-with-scheduled-shutdowns/"><u>Optimize Your PC's Idle State with Scheduled Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nonexistent-hardware-warning-in-windows/"><u>Overcoming Nonexistent Hardware Warning in WIndows</u></a></li>
<li><a href="https://win11.techidaily.com/proven-windows-11-ways-to-boost-workflow-and-productivity-45/"><u>Proven Windows 11 Ways to Boost Workflow and Productivity (45)</u></a></li>
<li><a href="https://data-wizards.techidaily.com/quick-troubleshooting-guide-to-fix-icon-on-macos/"><u>Quick Troubleshooting Guide to Fix ?-Icon on MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-cameras-to-device-manager-display/"><u>Reintroduce Missing Cameras to Device Manager Display</u></a></li>
<li><a href="https://win11.techidaily.com/reinvent-the-way-you-handle-aging-pcs-less-windows/"><u>Reinvent the Way You Handle Aging PCs: Less Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-a00f425d-on-windows-11-camera-app/"><u>Resolving Error Code A00F425D on Windows 11 Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unlinked-files-and-absence-of-assigned-apps-win/"><u>Resolving Unlinked Files and Absence of Assigned Apps (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/saving-yourself-from-install-error-in-discord-set-up/"><u>Saving Yourself From Install Error in Discord Set-Up</u></a></li>
<li><a href="https://fox-that.techidaily.com/solving-the-issue-why-youre-seeing-phone-numbers-rather-than-contact-names/"><u>Solving the Issue: Why You're Seeing Phone Numbers Rather Than Contact Names</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-mastery-in-artificially-inspired-visuals-using-paint-cocreator-on-win11/"><u>Step-by-Step Mastery in Artificially Inspired Visuals Using Paint Cocreator on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-performance-of-a-non-responsive-windows-folder/"><u>Strategies to Improve Performance of a Non-Responsive Windows Folder</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-administration-in-windows-11/"><u>Streamlining User Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-broken-usb-connections-on-windows-systems/"><u>Tackling Broken USB Connections on Windows Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-earning-cash-online-with-no-skills-needed/"><u>The Ultimate Guide to Earning Cash Online with No Skills Needed</u></a></li>
<li><a href="https://win11.techidaily.com/the-unopened-notepad-predicament-solutions-to-make-it-open-once-more/"><u>The Unopened Notepad Predicament: Solutions to Make It Open Once More</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-lava-blaze-pro-5g-by-fonelab-android-recover-data/"><u>Undelete lost data from Lava Blaze Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-explorers-gallery-view-capability/"><u>Unlocking File Explorer's Gallery View Capability</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/your-instagram-memories-unchained-and-safe/"><u>Your Instagram Memories, Unchained & Safe</u></a></li>
</ul></div>
