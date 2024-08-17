---
title: Activate and Personalize Your PC's Audio with Windows 11 Mixer
date: 2024-08-15T23:19:20.430Z
updated: 2024-08-16T23:19:20.430Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate and Personalize Your PC's Audio with Windows 11 Mixer
excerpt: This Article Describes Activate and Personalize Your PC's Audio with Windows 11 Mixer
keywords: Windows 11 Sound Control,Personalized PC Audio,Activating Windows 11 Mixer,Customize PC Audio Settings,Enhance PC Audio Quality,Windows 11 Audio Manager,Tailor PC Sound Experience
thumbnail: https://thmb.techidaily.com/61dcd74c9ca257bd7a3583ce0e08424eaf979002cdc0aa0e847be271477f189f.jpg
---

## Activate and Personalize Your PC's Audio with Windows 11 Mixer

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend [using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download [ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-cutting-edge-content-tips-for-excelling-in-facebook-video-sharing/"><u>[New] 2024 Approved  Cutting-Edge Content  Tips for Excelling in Facebook Video Sharing</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-echoes-of-sound-how-to-enhance-tweeted-visuals/"><u>[New] 2024 Approved  Echoes of Sound  How to Enhance Tweeted Visuals</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-optimizing-channel-branding-to-skyrocket-subscriber-numbers/"><u>[New] 2024 Approved  Optimizing Channel Branding to Skyrocket Subscriber Numbers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-unearthing-springs-full-potential-for-desktop-recorders/"><u>[New] 2024 Approved  Unearthing Spring's Full Potential for Desktop Recorders</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-8-pioneering-exercise-videos-to-keep-your-viewers-active-for-2024/"><u>[New] 8 Pioneering Exercise Videos To Keep Your Viewers Active for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-assessing-the-right-level-of-luminosity-in-creative-hdr-ventures/"><u>[New] Assessing the Right Level of Luminosity in Creative HDR Ventures</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-concealing-content-securing-video-data-ethics-for-2024/"><u>[New] Concealing Content  Securing Video Data Ethics for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-plex-vs-streaming-titanique-for-2024/"><u>[New] Plex vs Streaming Titanique for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-uncomplicatedscreensave-free-recording-software/"><u>[New] UncomplicatedScreenSave  Free Recording Software</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-dissecting-video-platform-distinctions-youtube-vs-dailymention/"><u>[Updated] In 2024, Dissecting Video Platform Distinctions  YouTube Vs. DailyMention</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-trim-youtube-videos/"><u>[Updated] In 2024, How to Trim YouTube Videos?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-metaverse-vs-multimetverse-what-are-the-differences-ultimate-guide/"><u>[Updated] Metaverse Vs. MultiMetverse  What Are the Differences [Ultimate Guide]</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-binaural-bliss-broken-recovery-steps/"><u>2024 Approved  Binaural Bliss Broken  Recovery Steps</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-constructing-the-ideal-setup-for-advanced-4k-video-production/"><u>2024 Approved  Constructing the Ideal Setup for Advanced 4K Video Production</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-proven-strategies-in-advanced-obs-studio-filmmaking/"><u>2024 Approved  Proven Strategies in Advanced OBS Studio Filmmaking</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-top-8-best-kept-video-download-secrets/"><u>2024 Approved  Top 8 Best-Kept Video Download Secrets</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-x-flip-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo X Flip by Name | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-microsoft-should-improve-the-windows-11-taskbar/"><u>6 Ways Microsoft Should Improve the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-resize-images-in-windows-11/"><u>6 Ways to Resize Images in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenhensive-guide-to-windows-graphics-reset-techniques/"><u>A Compreenhensive Guide to Windows Graphics Reset Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-winning-bittorrent-clients/"><u>A Comprehensive Guide to Winning BitTorrent Clients</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-the-call-not-invoked-issue-in-malwarebytes/"><u>Addressing and Fixing the Call Not Invoked Issue in Malwarebytes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-chrome-downloads-disruptions-in-the-windows-os/"><u>Addressing Chrome Downloads Disruptions in the Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-sevenzeronine-in-windows/"><u>Addressing Error SevenZeroNine in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-windows-programs-a-fixers-manual/"><u>Addressing Inoperative Windows Programs: A Fixer’s Manual</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/1719376423944-addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-login-failure-threshold-step-by-step-for-windows-11-users/"><u>Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-quick-access-for-file-explorer-through-onedrive/"><u>Adjusting Quick Access for File Explorer Through OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/ais-impact-on-modern-windows-os-innovation/"><u>AI's Impact on Modern Windows OS Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://win11.techidaily.com/anonymizing-file-transfer-methods-for-ws11w10-enthusiasts/"><u>Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-for-correcting-err-87-invalid-parameters-on-winos/"><u>Approaches for Correcting Err 87: Invalid Parameters on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-excellence-through-windows/"><u>Augmenting Linux Excellence Through Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-disruption-bypass-game-glitches-immediately/"><u>Avoid Disruption - Bypass Game Glitches Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-offer-best-price-keys-fan-unlocked-for-all-year-lifetime-windows-11/"><u>Black Friday Offer: Best Price Keys Fan Unlocked for All-Year Lifetime Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bluescreenview-explained-with-ease-and-clarity/"><u>BlueScreenView Explained with Ease and Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-cycles-of-compliance-my-defiance-against-app-guard-norms/"><u>Breaking Cycles of Compliance: My Defiance Against App Guard Norms</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-activation-error-0x8007251d-fixes-and-tips/"><u>Breaking Down Windows Activation Error 0X8007251D: Fixes and Tips</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-motorola-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Motorola?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-infinix-note-30-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Infinix Note 30 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-brief-blueprints-iphone-content-for-desktop/"><u>In 2024, Brief Blueprints  IPhone Content for Desktop</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-comprehensively-addressed-best-tools-for-efficient-unfollowing/"><u>In 2024, Comprehensively Addressed  Best Tools for Efficient Unfollowing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-find-muted-conversations-on-snapchat/"><u>In 2024, How to Find Muted Conversations on Snapchat</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-vivo-v30-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Vivo V30 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-iphone-13-when-phone-is-broken-drfone-by-drfone-ios/"><u>In 2024, How to Turn Off Find My iPhone 13 when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-ae-text-styles-for-impact/"><u>In 2024, Innovative AE Text Styles for Impact</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-oneplus-ace-2v-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change OnePlus Ace 2V IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-11-pros-window-secrets/"><u>In 2024, Unlocking 11  Pro's Window Secrets</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/inside-the-world-of-pc-parts-and-devices-a-look-with-toms-hardware/"><u>Inside the World of PC Parts & Devices – A Look with Tom's Hardware</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-the-darkness-in-depth-strategies-for-repairing-a-nonresponsive-screen-on-dell-notebooks/"><u>Navigating the Darkness: In-Depth Strategies for Repairing a Nonresponsive Screen on Dell Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719218745181-panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks!</u></a></li>
<li><a href="https://win11.techidaily.com/1719284853027-ready-set-gain-administrator-status/"><u>Ready, Set, Gain Administrator Status!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-the-xinput13dll-file-absent-issue-a-comprehensive-guide/"><u>Solving the xinput1_3.dll File Absent Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-13-mini-drfone-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-sound-issues-unresponsive-speakers-and-headphones-in-windows-operating-systems/"><u>Troubleshoot Sound Issues: Unresponsive Speakers and Headphones in Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/1719330765099-troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments!</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-how-to-translate-audiovideo-content-from-spanish-to-english-and-vice-versa-for-2024/"><u>Updated How to Translate Audio/Video Content From Spanish to English and Vice Versa for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719258150800-win-rpc-problems-here-are-5-fixes-you-need/"><u>Win RPC Problems? Here Are 5 Fixes You Need</u></a></li>
</ul></div>
