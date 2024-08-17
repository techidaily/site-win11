---
title: "Demonstrating the Power of PowerShell: Removing Restrictions on Windows"
date: 2024-08-16T00:06:44.280Z
updated: 2024-08-17T00:06:44.280Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Demonstrating the Power of PowerShell: Removing Restrictions on Windows"
excerpt: "This Article Describes Demonstrating the Power of PowerShell: Removing Restrictions on Windows"
keywords: PowerShell Mastery,Unlock Windows Potential,PowerShell Enhancement,Overcoming OS Limitations,Elevate System Management,Streamline Server Control,Optimize OS Functionality
thumbnail: https://thmb.techidaily.com/ef0c500c1ff8cdea11d6b2ce7132e969a27a23353363cc6a48d15e2d1d290c96.jpg
---

## Demonstrating the Power of PowerShell: Removing Restrictions on Windows

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on [how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-brief-snippet-analysis-for-beginners/"><u>[New] 2024 Approved  Brief Snippet Analysis for Beginners</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-ensure-your-video-fits-the-instagram-aesthetic-perfectly/"><u>[New] Ensure Your Video Fits the Instagram Aesthetic Perfectly</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-full-slomo-recording-app-evaluation-future-outlook/"><u>[New] Full SloMo Recording App Evaluation - Future Outlook</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-affordable-acoustic-amps-and-mics-for-video-voyagers/"><u>[New] In 2024, Affordable Acoustic Amps and Mics for Video Voyagers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-capturing-horizon-views-for-successful-drone-livestreams/"><u>[New] In 2024, Capturing Horizon Views for Successful Drone Livestreams</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-techniques-for-finding-no-cost-image-frame-films/"><u>[New] Techniques for Finding No-Cost Image Frame Films</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/he-art-of-thumbnail-design-choosing-best-fonts-for-2024/"><u>[New] The Art of Thumbnail Design  Choosing Best Fonts for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-10-iphone-camera-features-you-should-know-in-ios-11/"><u>[Updated] 10 iPhone Camera Features You Should Know in iOS 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-innovative-techniques-for-capturing-every-play-of-your-ps3-games/"><u>[Updated] 2024 Approved  Innovative Techniques for Capturing Every Play of Your PS3 Games</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unleash-your-ugc-making-memes-and-marks-on-fb/"><u>[Updated] In 2024, Unleash Your UGC  Making Memes and Marks on FB</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-commanders-quest-the-ultimate-list-of-total-war-classics/"><u>2024 Approved  Commanders’ Quest  The Ultimate List of Total War Classics</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-navigating-the-path-of-adobe-presenter-video-creation/"><u>2024 Approved  Navigating the Path of Adobe Presenter Video Creation</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-checks-with-these-9-fixes-on-windows-setup/"><u>Accelerate Update Checks with These 9 Fixes on Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-writable-driver-verifier/"><u>Activating Windows 11' Writable Driver Verifier</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-failure-codes-0x80072f8f/"><u>Addressing Windows Failure Codes: 0X80072f8f</u></a></li>
<li><a href="https://article-tips.techidaily.com/apply-spiral-depth-enhancement-to-images-psx-for-2024/"><u>Apply Spiral Depth Enhancement to Images PSX for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-metered-connection-for-wifi-networks-on-win11/"><u>Configuring Metered Connection for Wifi Networks on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-non-persistent-nvidia-panel-changes/"><u>Correcting Non-Persistent Nvidia Panel Changes</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-top-windows-to-do-apps/"><u>Enhance Your Workflow with Top Windows To-Do Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-new-horizons-top-5-samsung-gear-vr-games-for-2024/"><u>Exploring New Horizons - Top 5 Samsung Gear VR Games for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://win-blog.techidaily.com/gta-5-online-not-responding-heres-how-to-solve-it/"><u>GTA 5 Online Not Responding? Here's How to Solve It</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-and-opening-verifier-manager-w11/"><u>Guide: Accessing and Opening Verifier Manager W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-vivo-y17s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unterminated-process-failures-in-windows/"><u>How to Resolve Unterminated Process Failures in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-vivo-y78-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Vivo Y78 5G to Another | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-enhance-your-video-impact-with-slow-motion-on-ig/"><u>In 2024, Enhance Your Video Impact with Slow Motion on IG</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-samsung-galaxy-m14-4g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Samsung Galaxy M14 4G Phone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-learn-the-mechanics-behind-self-playing-videos-in-fb/"><u>In 2024, Learn the Mechanics Behind Self-Playing Videos in Fb</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-lively-captions-how-to-add-motion-to-instagram-posts/"><u>In 2024, Lively Captions  How to Add Motion to Instagram Posts</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-prior-to-starting-the-window-operating-system-renewal/"><u>Key Steps Prior to Starting the Window Operating System Renewal</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-sending-love-with-keyboard-emojis-a-step-by-step-guide/"><u>Mastering the Art of Sending Love with Keyboard Emojis: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mending-microsoft-outlook-glitches-on-windows-devices/"><u>Mending Microsoft Outlook Glitches on Windows Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/modernizing-the-papacy-understanding-pope-franciss-approach-to-using-email/"><u>Modernizing the Papacy? Understanding Pope Francis's Approach to Using Email</u></a></li>
<li><a href="https://win11.techidaily.com/opening-editing-and-personalizing-your-win11-fax-cover-page/"><u>Opening, Editing & Personalizing Your Win11 Fax Cover Page</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disruptive-discord-js-error-in-windows-environments/"><u>Overcoming Disruptive Discord JS Error in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unresponsive-windows-11-cortana-commands/"><u>Overcoming Unresponsive Windows 11 Cortana Commands</u></a></li>
<li><a href="https://win11.techidaily.com/1719352195023-quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-hidden-notifications-on-desktops/"><u>Recovering Hidden Notifications on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-undetermined-status-messages-on-windows/"><u>Remedying 'Undetermined' Status Messages on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-device-integration-using-googles-nearby/"><u>Seamless Device Integration Using Google's Nearby</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-stress-relief-track-drivers-fixed/"><u>Seamless Stress Relief: Track Drivers Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/silent-storage-strategies-for-stealthy-windows-users/"><u>Silent Storage Strategies for Stealthy Windows Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/swift-recovery-reviving-windows-photo-viewer-on-modern-os-for-2024/"><u>Swift Recovery  Reviving Windows Photo Viewer on Modern OS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-of-windows-11-is-ai-whether-you-like-it-or-not/"><u>The Future of Windows 11 Is AI, Whether You Like It or Not</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-new-standard-how-does-av1-outperform-vp9-in-2024/"><u>The New Standard  How Does AV1 Outperform VP9, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-supercharge-video-memory-on-windows-devices/"><u>Tips to Supercharge Video Memory on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-11-app-error-afc/"><u>Understanding and Remedying Windows 11 APP Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-9-indisputable-reasons-to-choose-a-pc-over-a-mac/"><u>Unveiling 9 Indisputable Reasons to Choose a PC Over a Mac</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-unlinking-saved-wi-fi/"><u>Win 11: Unlinking Saved Wi-Fi</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-eliminate-auto-change-backgrounds/"><u>Windows 11: Eliminate Auto-Change Backgrounds</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-oneplus-nord-n30-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On OnePlus Nord N30 5G? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
