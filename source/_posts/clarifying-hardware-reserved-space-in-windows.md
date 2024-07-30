---
title: Clarifying Hardware Reserved Space in Windows
date: 2024-07-29T15:55:04.139Z
updated: 2024-07-30T15:55:04.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clarifying Hardware Reserved Space in Windows
excerpt: This Article Describes Clarifying Hardware Reserved Space in Windows
keywords: Hardware Space Windows,Reserved PC Space,Windows Storage Limits,Device Allocation Windows,System Reserve Capacity,OS Hardware Slot Usage,Computing Space Management
thumbnail: https://thmb.techidaily.com/ade566529a7bc97aed23a78dd1be17314340f234a16c9d2f0b2b465091d3ea91.jpg
---

## Clarifying Hardware Reserved Space in Windows

 There’s no doubt that when it comes to a computer's performance, one of the most important roles is played by RAM (or Random Access Memory). However, Windows can’t use the amount of RAM mentioned in your computer specifications. This is because some of it is “reserved” by your system.

 But what is Hardware Reserved Memory? Can you check how much memory is reserved on your computer and can you adjust the value?

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## What Is Hardware Reserved Memory?

 Windows saves a part of the available RAM, so your hardware components have enough resources to work properly. This is known as Hardware Reserved Memory, and Windows allocates it to hardware devices such as the network adapter, Bluetooth devices, sound card, and GPU, among other hardware devices.

 This way, Windows makes sure these components function as expected when you need them.

## How to Check Your Hardware Reserved Memory

 Windows makes it quite easy to check the amount of hardware reserved memory. Press**Ctrl + Shift + Esc** to bring up Task Manager. There, open the**Performance** tab and select**Memory** . Check the value next to**Hardware reserved** .

![Check hardware reserved memory on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-reserved-memory-1.jpg)

## How Your PC's Hardware Reserved Memory Impacts Performance

 If your system allocates too much of the RAM to the Hardware Reserved Memory, it will negatively impact your computer performance. Especially if you don’t have a lot of RAM to start with.

 Also, certain hardware components, such as high-end Graphics Processing Units or sound cards, need more memory to manage their assigned tasks. Moreover, Windows uses reserved memory to store drivers for peripheral devices, even if you don’t use them that often.

 If Windows reserves too much of your RAM, you might deal with longer boot-up times or even Windows crashing and freezing as it doesn’t have enough resources to keep all processes running.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Adjust the Hardware Reserved Memory on Windows

 In general, the value for Hardware Reserved Memory should be a few hundred megabytes. The 32-bit version of Windows can reserve up to 3.5 GB of RAM, while the 64-bit system usually needs around 1GB. If the value is around a couple of GB, or even more, you’ll have to adjust the value. Fortunately, Windows has a few ways you can do it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
### 1\. Update Your Drivers

 Outdated or corrupt[computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) will increase the amount of memory Windows reserves to keep your hardware devices running smoothly. Updating the drivers, especially the GPU drivers, might help Windows reduce the amount of reserved memory.

 Additionally, it might help to disable drivers for devices that you no longer use, as Windows will keep managing them. Launch Device Manager, go through the list, then locate any unneeded drivers. Click them and select**Disable device** .

![Disable device through Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-1.jpg)

 When disabling hardware devices, make sure you no longer need them, as you might be causing issues within your system.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Install 64-Bit Windows

 There are a few[differences between 32-bit and 64-bit Windows](https://www.makeuseof.com/tag/difference-32-bit-64-bit-windows/) , including the amount of Hardware Reserved Memory. As we’ve mentioned, a 64-bit Windows assigns less RAM to the Hardware Reserved Memory, so updating from 32-bit to the 64-bit Windows version should reduce the amount of reserved memory.

 If you’re not sure which version you’re currently running, press**Windows key + I** to bring up the Settings menu. There, head to**System** , scroll to the bottom of the page, and click**About** . Check the value next to**System type** to check if your system is 32 or 64-bit.

![Check Windows version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-64bit-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Set a Preferred GPU

 There’s a chance your computer has two GPUs, and one of them is better when managing high-intensive graphics tasks. Instead of using the integrated graphics card to process complex tasks, you should[choose a preferred GPU for games or editing software](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) to reduce the memory reserved by Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Run the Hardware and Devices Troubleshooter

 If one of your connected devices isn’t working properly, Windows might reserve more of your system memory. To fix it, you should run Windows’ Hardware and Devices troubleshooter. Here’s how you can do it:

1. Launch Command Prompt with administrative rights.
2. Type**msdt.exe -id DeviceDiagnostic** and press**Enter** .
3. In the Hardware and Devices window, click**Advanced** , and check the**Apply repairs automatically** option.
4. Click**Next** to start the process.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![Running the hardware and devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-devices-1.jpg)

### 4\. Edit Your System Configuration

 In general, Windows is the only one deciding how much of your system memory it reserves. However, you can control the maximum amount of reserved memory through System Configuration. Here’s how you can do it:

1. Press**Win + R** to bring up a Run box.
2. Type**msconfig** and press**Enter** .
3. In the System Configuration window, open the**Boot** tab.
4. Click**Advanced options** .
5. Check**Maximum memory** and edit the value.
6. Click**OK** .

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change boot settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/boot-settings-1.jpg)

 Keep in mind this will have a direct impact on how much memory Windows reserves to keep your system running properly. Don’t set a value too low to make sure Windows has enough resources.

### 5\. Restore the BIOS to Its Default Settings

 You can use your computer for years without thinking of BIOS. But it plays an important role in your computer’s stability. If you notice your system assigns too many resources to the Hardware Reserved Memory, the problem might be caused by improper BIOS settings. In this case, reverting it to its default settings should fix the issue.

 First, press**Del** or**F2** to enter BIOS during the Windows startup screen. From the bottom of the page, click Load Defaults (or Restore Settings) and confirm the action. Then, exit BIOS, restart your computer, and check the Hardware Reserved Memory value.

 If you can’t access BIOS during the startup screen, there are more[methods you could try to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) and reset it.

## Manage the Hardware Reserved Memory on Windows

 Hopefully, our guide helped you know more about your computer’s hardware reserved memory. The truth is, you may not even think about it until it negatively impacts your system’s performance, but if this happens, the tips above should help you manage the situation.

 But there are so many system tricks that you could use to avoid having Windows take too much of your resources. If you’re looking for a permanent fix, you might have to upgrade your computer’s hardware.


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
<li><a href="https://youtube-web.techidaily.com/024-approved-cultivate-1000-fanbase-followers-quickly/"><u>[New] 2024 Approved  Cultivate 1,000 Fanbase Followers Quickly</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-leading-green-screen-systems-expert-utilization-tips/"><u>[New] 2024 Approved  Leading Green Screen Systems  Expert Utilization Tips</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-detailed-process-for-creating-professional-voice-recordings-for-2024/"><u>[New] Detailed Process for Creating Professional Voice Recordings for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-from-celluloid-to-screen-adapting-your-vids-for-ig/"><u>[New] In 2024, From Celluloid to Screen  Adapting Your Vids for IG</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-perfect-pairings-combining-song-and-scene-in-tiktok-vids-for-2024/"><u>[New] Perfect Pairings  Combining Song and Scene in TikTok Vids for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-streamlined-process-to-download-parts-from-youtube-videos/"><u>[New] Streamlined Process to Download Parts From YouTube Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tech-insight-pulling-and-keeping-twitters-vids-in-phone-for-2024/"><u>[New] Tech Insight  Pulling and Keeping Twitters Vids in Phone for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-snip-youtube-videos-effortlessly/"><u>[Updated] 2024 Approved  How to Snip YouTube Videos Effortlessly</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-elevate-your-stream-with-these-5-top-tier-cams-for-2024/"><u>[Updated] Elevate Your Stream with These 5 Top-Tier Cams for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-navigating-discords-video-sharing-feature-with-expertise/"><u>[Updated] Navigating Discord's Video Sharing Feature with Expertise</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-premier-ios-choice-best-emulators-of-psp-games-for-2024/"><u>[Updated] Premier iOS Choice  Best Emulators of PSP Games for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-smooth-transition-uploading-imovie-films-into-vimeo-for-2024/"><u>[Updated] Smooth Transition  Uploading iMovie Films Into Vimeo for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-practical-approach-to-zoom-meetings/"><u>2024 Approved  A Practical Approach to Zoom Meetings</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-authentic-praise-amplified-branding/"><u>2024 Approved  Authentic Praise, Amplified Branding</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-camera-lens-to-screen-your-step-by-step-guide-to-gopro-video-mastery/"><u>2024 Approved  From Camera Lens to Screen  Your Step-by-Step Guide to GoPro Video Mastery</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-guidance-for-effortless-addition-of-youtube-playlists-to-your-site/"><u>2024 Approved  Guidance for Effortless Addition of YouTube Playlists to Your Site</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-srt-optimization-the-ultimate-performance-boosters-for-computers/"><u>2024 Approved  SRT Optimization  The Ultimate Performance Boosters for Computers</u></a></li>
<li><a href="https://win11.techidaily.com/22h2-windows-fixes-for-recurring-issues/"><u>22H2 Windows Fixes for Recurring Issues</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-stop-automatic-office-updates-on-windows/"><u>4 Ways to Stop Automatic Office Updates on Windows</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-microsoft-should-improve-the-windows-11-taskbar/"><u>6 Ways Microsoft Should Improve the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/7-symptoms-your-pc-may-need-a-new-beginning/"><u>7 Symptoms Your PC May Need A New Beginning</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-desktop-window-managers-high-gpu-usage-on-windows-11/"><u>7 Ways to Fix the Desktop Window Manager's High GPU Usage on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-winning-bittorrent-clients/"><u>A Comprehensive Guide to Winning BitTorrent Clients</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://win11.techidaily.com/access-from-afar-zero-password-connectivity-on-win-11/"><u>Access From Afar: Zero-Password Connectivity on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-the-call-not-invoked-issue-in-malwarebytes/"><u>Addressing and Fixing the Call Not Invoked Issue in Malwarebytes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-blackout-in-widows-remote-desktop-connection/"><u>Addressing Blackout in Widows Remote Desktop Connection</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-chrome-downloads-disruptions-in-the-windows-os/"><u>Addressing Chrome Downloads Disruptions in the Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-epic-games-account-unlock-on-windows/"><u>Addressing Epic Games Account Unlock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/1719376423944-addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies</u></a></li>
<li><a href="https://extra-hints.techidaily.com/advanced-subtitle-editing-unlocking-potential-with-macos/"><u>Advanced Subtitle Editing  Unlocking Potential with MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/android-as-a-w11-secondary-display-step-by-step-guide/"><u>Android as a W11 Secondary Display: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/android-extension-in-w11-workspace-enhancing-productivity/"><u>Android Extension in W11 Workspace: Enhancing Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/anonymizing-file-transfer-methods-for-ws11w10-enthusiasts/"><u>Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-disruption-bypass-game-glitches-immediately/"><u>Avoid Disruption - Bypass Game Glitches Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-windowed-app-repositioning-techniques/"><u>Avoidance of Windowed App Repositioning Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/banish-temp-files-quick-windows-fixes/"><u>Banish Temp Files: Quick Windows Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-how-to-stop-apex-legends-freezes/"><u>Beat the Bug: How to Stop Apex Legends Freezes</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-deletion-windows-innovative-erasing-technique/"><u>Beyond Deletion: Windows' Innovative Erasing Technique</u></a></li>
<li><a href="https://win11.techidaily.com/bluescreenview-explained-with-ease-and-clarity/"><u>BlueScreenView Explained with Ease and Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-through-strategic-task-management-in-windows-11/"><u>Boosting Productivity Through Strategic Task Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-repairing-windows-charmap-issues/"><u>Breaking Down and Repairing Windows' CharMap Issues</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-much-could-you-make-on-youtube-snippets-for-2024/"><u>How Much Could You Make on YouTube Snippets for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-apple-iphone-12-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your Apple iPhone 12 Apple ID and Apple Pay</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-vivo-v27-pro-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Vivo V27 Pro For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-realme-12plus-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Realme 12+ 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-eluding-digital-footprints-while-enjoying-instagram-stories-online/"><u>In 2024, Eluding Digital Footprints While Enjoying Instagram Stories Online</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-what-are-facebook-reels-and-how-to-make/"><u>In 2024, What Are Facebook Reels and How to Make</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719218745181-panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks!</u></a></li>
<li><a href="https://win11.techidaily.com/1719249883200-revive-keys-in-crisis-arrows-rescued/"><u>Revive Keys in Crisis: Arrows Rescued!</u></a></li>
<li><a href="https://extra-information.techidaily.com/sdr-to-hdri-pioneers-expert-tips-and-techniques/"><u>SDR to HDRI Pioneers  Expert Tips and Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/step-by-step-perfectly-sharing-your-photography-on-youtube-for-2024/"><u>Step-by-Step  Perfectly Sharing Your Photography on YouTube for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-15-plus-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue From Apple iPhone 15 Plus</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-7-apps-altering-vocal-soundtracks-for-2024/"><u>Top 7 Apps Altering Vocal Soundtracks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719358387590-troubleshoot-frozen-shift-key-on-pc/"><u>Troubleshoot Frozen Shift Key on PC.</u></a></li>
<li><a href="https://some-guidance.techidaily.com/understanding-transient-suppression-via-audacity-for-2024/"><u>Understanding Transient Suppression via Audacity for 2024</u></a></li>
</ul></div>
