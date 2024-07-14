---
title: Solutions for 'Memory Shortage' Error in Windows-Based VMs
date: 2024-07-13T11:00:35.592Z
updated: 2024-07-14T11:00:35.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for 'Memory Shortage' Error in Windows-Based VMs
excerpt: This Article Describes Solutions for 'Memory Shortage' Error in Windows-Based VMs
keywords: VM Memory Woes,Fixing Windows Memory Issue,Remedy Windows Memory Error,Eradicate Memory Shortage Windows,Solve Memory Gap Windows VMs,Overcoming Windows Short Memory,Troubleshoot Windows Virtual Memory
thumbnail: https://thmb.techidaily.com/c8c0a761aab973c79a26bc00df92df723a573173c058dc152cef52dc4b741fd1.jpg
---

## Solutions for 'Memory Shortage' Error in Windows-Based VMs

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out [how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.
5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about [uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on [how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the [VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the [VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://win11.techidaily.com/making-vintage-windows-computers-more-elderly-friendly/"><u>Making Vintage Windows Computers More Elderly Friendly</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-overcoming-onedrive-errors-on-windows/"><u>Winning at Overcoming OneDrive Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-error-4294967295-a-comprehensive-guide/"><u>Eliminating WSL Error 4294967295: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-bluetooth-headphones-playing-sound-without-volume-control/"><u>Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control</u></a></li>
<li><a href="https://win11.techidaily.com/swift-pc-exploration-via-everythingapp/"><u>Swift PC Exploration via EverythingApp</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-shoguns-call-a-list-of-top-10-games-reflecting-tsushi-values-for-2024/"><u>[New] Shogun's Call  A List of Top 10 Games Reflecting Tsushi Values for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-best-4k-screen-recorder-applications/"><u>In 2024, Best 4K Screen Recorder Applications</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-vivo-y17s-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Vivo Y17s online without jailbreak</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-ultimate-guide-to-best-in-class-racing-games/"><u>[New] The Ultimate Guide to Best-in-Class Racing Games</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-nokia-g310-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Nokia G310 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-moonbeam-methods-crafting-perfect-night-photography/"><u>[New] Moonbeam Methods  Crafting Perfect Night Photography</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-transform-your-igtv-visuals-with-updated-covers-for-2024/"><u>[Updated] Transform Your IGTV Visuals with Updated Covers for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-boosting-engagement-navigate-to-these-8-best-apps-for-post-timers/"><u>2024 Approved  Boosting Engagement  Navigate to These 8 Best Apps for Post Timers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-video-ventures-uploading-to-twtplustumble-feeds-for-2024/"><u>[Updated] Video Ventures  Uploading to Twt+Tumble Feeds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-windows-tools-for-superior-macos-experience/"><u>Utilizing Windows Tools for Superior macOS Experience</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mend-media-player-server-faults/"><u>Steps to Mend Media Player Server Faults</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-system-failures-blue-screen-aftermath-in-windows/"><u>Delving Into System Failures: Blue Screen Aftermath in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/stalling-windows-auto-updates-four-methods/"><u>Stalling Windows Auto-Updates: Four Methods</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-screen-captures-adding-sound-in-the-snipping-tool-max-156/"><u>Elevate Your Screen Captures: Adding Sound in the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/linking-legacy-and-modernity-initiating-windows-11-with-a-window-7-code/"><u>Linking Legacy and Modernity: Initiating Windows 11 with a Window 7 Code</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-tackling-windows-security-anomalies/"><u>Strategies for Tackling Windows Security Anomalies</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-experts-handbook-for-voice-alteration-via-morphvox-for-2024/"><u>The Ultimate Expert's Handbook for Voice Alteration via MorphVOX for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-beginners-guide-to-earning-on-reddit-top-13-simple-money-making-ideas/"><u>The Beginner's Guide to Earning on Reddit  Top 13 Simple Money-Making Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-10-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-outlook-error-0x80040610-on-windows-devices/"><u>Quick Fix for Outlook Error 0X80040610 on Windows Devices</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-mastering-flight-a-complete-review-of-the-dji-inspire-2-drone/"><u>[Updated] 2024 Approved  Mastering Flight  A Complete Review of the DJI Inspire 2 Drone</u></a></li>
<li><a href="https://win11.techidaily.com/transform-spending-habits-with-premium-windows-11-pro-key/"><u>Transform Spending Habits with Premium Windows 11 Pro Key</u></a></li>
<li><a href="https://win11.techidaily.com/total-flush-out-of-windows-subsystem/"><u>Total Flush Out of Windows Subsystem</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-securing-your-shots-top-15-mounting-options-for-gopro/"><u>2024 Approved  Securing Your Shots  Top 15 Mounting Options for GoPro</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-11s-cam-access-silence-protocol/"><u>Altering Windows 11'S Cam Access Silence Protocol</u></a></li>
<li><a href="https://win11.techidaily.com/1719361152872-lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever!</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-nokia-c12-pro-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Nokia C12 Pro without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-create-epic-gaming-intros-top-10-tools-for-windows-and-mac-free-and-paid/"><u>Updated In 2024, Create Epic Gaming Intros Top 10 Tools for Windows and Mac Free & Paid</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-basics-top-10-windows-store-picks/"><u>Mastering the Basics: Top 10 Windows Store Picks</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/0-youtube-music-rippers-for-android-and-ios-for-2024/"><u>[New] 10 YouTube Music Rippers for Android and iOS for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/cutting-and-compositing-for-youtube-videos-using-premiere-pro-for-2024/"><u>Cutting and Compositing for YouTube Videos Using Premiere Pro for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-10-virtual-world-games-on-ios-and-android/"><u>[Updated] Best 10 Virtual World Games on iOS & Android</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-quality-with-auto-hdr-in-w11/"><u>Maximizing Image Quality with Auto HDR in W11</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-batch-renaming-made-simple/"><u>PowerToys' Batch Renaming Made Simple</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-video-invitation-apps-that-will-make-your-event-unforgettable/"><u>In 2024, Video Invitation Apps That Will Make Your Event Unforgettable</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-startup-in-windows-11/"><u>Mastering Fast Startup in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-niche-networking-smaller-bizs-video-strategies/"><u>2024 Approved  Niche Networking  Smaller Biz's Video Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-admin-control-in-windows-os-security/"><u>Redefining Admin Control in Windows OS Security</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-roundup-post-vlc-media-players/"><u>[Updated] The Ultimate Roundup  Post-VLC Media Players</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-music-from-infinix-note-30-vip-racing-edition-by-fonelab-android-recover-music/"><u>Best Android Data Recovery - Undelete Lost Music from Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-essential-tutorial-on-using-instagram-filters/"><u>[New] 2024 Approved  The Essential Tutorial on Using Instagram Filters</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-over-windows-input-methods/"><u>Unlock Full Control over Windows' Input Methods</u></a></li>
<li><a href="https://win11.techidaily.com/holiday-harmony-delightful-wrapped-apps-through-ms-store/"><u>Holiday Harmony: Delightful Wrapped Apps Through MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-gpu-capabilities-the-6-best-testers-in-windows/"><u>Navigate Through GPU Capabilities: The 6 Best Testers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-complications-with-java-installer/"><u>Steps to Fix Windows Complications with Java Installer</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-performance-with-smart-use-of-windows-11s-bar/"><u>Boosted Performance with Smart Use of Windows 11'S Bar</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-realme-12-pro-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Realme 12 Pro 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/uncovering-old-social-media-narratives-on-laptops-and-mobile-devices-for-2024/"><u>Uncovering Old Social Media Narratives on Laptops and Mobile Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-update-and-clean-the-cache-of-windows-symbols/"><u>Techniques to Update and Clean the Cache of Windows Symbols</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-key-features-and-uses/"><u>Microsoft Family Safety: Key Features and Uses</u></a></li>
</ul></div>
