---
title: Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
date: 2024-07-13T09:49:15.730Z
updated: 2024-07-14T09:49:15.730Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
excerpt: This Article Describes Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
keywords: Secure Boot Mastery,TPM Control Guide,VMBoost 7 Security,TPM Enablement Tips,VBox Secure Startup,Advanced TPM Activation,VBox 7.0 TPM Management
thumbnail: https://thmb.techidaily.com/abb5b783422357ac326d246e72e8c7f9c8f3c9e301b0d6289c4da0aac55fb642.jpg
---

## Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-top-voip-platforms-face-off-discord-vs-skype-showdown/"><u>[New] 2024 Approved  Top VoIP Platforms Face-Off  Discord Vs Skype Showdown</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-have-you-ever-wondered-how-to-add-camera-shake-to-video-in-adobe-after-effects-let-us-share-with-you-some-tips-and-tricks-on-how-to-do-just-th/"><u>2024 Approved Have You Ever Wondered How to Add Camera Shake to Video in Adobe After Effects? Let Us Share with You some Tips and Tricks on How to Do Just That</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnect-error-during-discord-setup-in-windows-os/"><u>Fixing Disconnect Error During Discord Setup in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-effective-rgb-light-settings-in-win11/"><u>Tips for Effective RGB Light Settings in Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/copyright-free-game-audio-repositories-for-2024/"><u>Copyright-Free Game Audio Repositories for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-11-quick-selective-copy-and-move/"><u>Unlock the Power of Windows 11: Quick Selective Copy & Move</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-shortened-terms-alias-and-application-lifecycle/"><u>Diving Into Shortened Terms: Alias & Application Lifecycle</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-top-linux-video-editors-for-adobe-premiere-users/"><u>In 2024, Top Linux Video Editors for Adobe Premiere Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-most-reliable-vehicle-monitoring-cameras-ranked/"><u>2024 Approved  Most Reliable Vehicle Monitoring Cameras Ranked</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-phantom-3-tussle-shade-4-rises/"><u>[Updated] Phantom 3 Tussle  Shade 4 Rises</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-free-mov-video-editing-software-top-6-cutting-tools/"><u>Updated 2024 Approved Free MOV Video Editing Software Top 6 Cutting Tools</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-bandicam-mastery-your-essential-checklist-for-2024/"><u>[New] Bandicam Mastery – Your Essential Checklist for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-eradicate-fluctuating-display-on-windows-1011/"><u>Expert Tips to Eradicate Fluctuating Display on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/path-pursuit-6-efficient-strategies-for-copying-file-and-folder-paths-in-windows-11/"><u>Path Pursuit: 6 Efficient Strategies for Copying File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-elevating-your-instagram-presence-with-optimized-video-sizes-for-2024/"><u>[New] Elevating Your Instagram Presence with Optimized Video Sizes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-best-flv-editor-for-windows-8-professional-video-editing-made-easy/"><u>New Best FLV Editor for Windows 8 Professional Video Editing Made Easy</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-honor-90-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Honor 90? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/continuous-edge-background-on-windows-11-tips/"><u>Continuous Edge Background on Windows 11 - Tips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tailored-fit-videos-the-key-to-great-instagram-posts-for-2024/"><u>[New] Tailored-Fit Videos  The Key to Great Instagram Posts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-11-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 11 & 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-navigating-windows-10-for-audio-capture/"><u>[New] Navigating Windows 10 for Audio Capture</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-enhancing-your-discord-experience-with-recordings/"><u>[New] In 2024, Enhancing Your Discord Experience with Recordings</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-the-potential-of-youtube-partnerships-tips-for-successful-collabs/"><u>2024 Approved  Unlocking the Potential of YouTube Partnerships  Tips for Successful Collabs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win1011-unraveling-error-code-0x800704b3/"><u>Fixing Win10/11: Unraveling Error Code 0X800704B3</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-honor-magic-v2-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Honor Magic V2 FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-11s-fatal-error/"><u>Deciphering and Resolving Windows 11'S Fatal Error</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-top-10-free-online-animated-logo-makers-everyone-should-know/"><u>New Top 10 Free Online Animated Logo Makers Everyone Should Know</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-windows-movie-maker-free-download-a-comprehensive-guide/"><u>Updated Windows Movie Maker Free Download A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-tasks-as-an-admin-in-windows-11/"><u>Securely Manage Tasks as an Admin in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-systematic-approach-to-rejuvenating-your-media-software/"><u>A Systematic Approach to Rejuvenating Your Media Software</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-clandestine-windows-11-taskbar-seeker/"><u>Accessing Clandestine Windows 11 Taskbar Seeker</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-unreachable-issue-in-windows/"><u>Resolving 'Network Unreachable' Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-reddits-crowned-champions-the-10-most-upvoted-posts/"><u>[New] Reddit's Crowned Champions  The 10 Most Upvoted Posts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-art-of-vrecorder-integration-simple-download-and-use-tutorials/"><u>2024 Approved  The Art of VRecorder Integration  Simple Download & Use Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-win1011-screen-flicker/"><u>How to Quickly Resolve WIN10/11 Screen Flicker</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
</ul></div>
