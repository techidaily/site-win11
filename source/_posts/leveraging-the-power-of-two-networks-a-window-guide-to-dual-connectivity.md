---
title: "Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity"
date: 2024-07-29T15:44:46.054Z
updated: 2024-07-30T15:44:46.054Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity"
excerpt: "This Article Describes Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity"
keywords: Dual Connectivity Basics,Enhancing Wi-Fi Range,Mesh Networking Advantage,Wireless Coverage Expansion,Efficient Dual Links,Syncing Two Networks,Optimized Connectivity Combo
thumbnail: https://thmb.techidaily.com/0ca201532589a8340625e0277d57d7a6d8a4fe5f03caf08035754438a176d190.jpg
---

## Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can [merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons [why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-begin-webcam-footage-recording-with-vlc/"><u>[New] 2024 Approved  Begin Webcam Footage Recording with VLC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-curated-collection-best-free-footage-websites-ranked/"><u>[New] 2024 Approved  Curated Collection  Best Free Footage Websites Ranked</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-economic-guide-to-capturing-virtual-learning-spaces/"><u>[New] 2024 Approved  Economic Guide to Capturing Virtual Learning Spaces</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-elevate-your-content-game-perfectly-tailored-youtube-shorts-thumbnails/"><u>[New] 2024 Approved  Elevate Your Content Game  Perfectly Tailored YouTube Shorts Thumbnails</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-explore-and-review-free-powerful-and-user-friendly-ios-edits/"><u>[New] 2024 Approved  Explore & Review  Free, Powerful, and User-Friendly iOS Edits</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-immortalize-memories-prime-online-tools-for-photo-framing/"><u>[New] Immortalize Memories  Prime Online Tools for Photo Framing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-become-a-social-media-vanguard-top-10-pioneering-igtv-techniques-for-marketing-excellence/"><u>[New] In 2024, Become a Social Media Vanguard  Top 10 Pioneering IGTV Techniques for Marketing Excellence</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-instagram-insights-the-best-apps-to-supercharge-your-profile-for-2024/"><u>[New] Instagram Insights  The Best Apps to Supercharge Your Profile for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-keeping-consistent-pacing-in-obs-broadcasts-for-2024/"><u>[New] Keeping Consistent Pacing in OBS Broadcasts for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-optimizing-virtual-engagements-with-these-top-10-essential-apps-for-2024/"><u>[New] Optimizing Virtual Engagements with These Top 10 Essential Apps for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhancing-engagement-imovie-techniques-for-youtube-intros/"><u>[Updated] Enhancing Engagement  IMovie Techniques for YouTube Intros</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-guide-to-choosing-ideal-youtube-thumbnail-shapes-for-2024/"><u>[Updated] Guide to Choosing Ideal Youtube Thumbnail Shapes for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-restoring-sound-linkage-in-obs-broadcasts/"><u>[Updated] In 2024, Restoring Sound Linkage in OBS Broadcasts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-recapturing-moments-top-notch-free-cam-screens-and-alternatives/"><u>[Updated] Recapturing Moments  Top-Notch Free Cam Screens & Alternatives</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-ultimate-vivacut-edit-pro-comprehensive-review-and-tutorial-2024/"><u>[Updated] Ultimate VivaCut Edit Pro  Comprehensive Review & Tutorial 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-supercharge-youtube-traffic-with-key-hash-tags/"><u>2024 Approved  Supercharge YouTube Traffic with Key Hash Tags</u></a></li>
<li><a href="https://win11.techidaily.com/address-fixing-non-responsive-function-keys-in-win-11-os/"><u>Address: Fixing Non-Responsive Function Keys in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-audiovisual-capabilities-through-new-driver-installation/"><u>Boosting Windows Audiovisual Capabilities Through New Driver Installation</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/cutting-edge-tech-analysis-the-best-screen-recorder-roundup/"><u>Cutting Edge Tech Analysis  The Best Screen Recorder Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-windows-update-failure-0x800f0845/"><u>Dealing with Windows Update Failure - 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-source-of-windows-parse-error-0xc00ce556/"><u>Dissecting the Source of Windows' Parse Error 0xC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workflow-adding-tasks-to-file-context-menus/"><u>Elevate Your Workflow: Adding Tasks to File Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/fix-slow-download-issues-in-steam-on-windows-platform/"><u>Fix Slow Download Issues in Steam on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-application-not-installed-via-microsofts-store/"><u>Fixing an Application Not Installed via Microsoft's Store</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-installer-access-rights-shortcomings/"><u>Fixing Windows Installer Access Rights Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/from-emulator-to-operating-system-windows-for-steam-deck/"><u>From Emulator to Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/fundamentals-of-copywriting-for-engaging-fb-campaigns-for-2024/"><u>Fundamentals of Copywriting for Engaging FB Campaigns for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reverse-error-code-0x80780119-in-windows/"><u>Guide to Reverse Error Code 0X80780119 in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-oneplus-nord-n30-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from OnePlus Nord N30 5G Devices</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-motorola-moto-g73-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Motorola Moto G73 5G Devices</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-nokia-g310-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-inside-outlook-unveiling-vrs-downfalls/"><u>In 2024, Inside Outlook  Unveiling VR's Downfalls</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-file-explorer-running-with-helpful-windows-11-tricks/"><u>Keep Your File Explorer Running with Helpful Windows 11 Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-proficiency-the-path-to-mastering-project/"><u>Keyboard Proficiency: The Path to Mastering Project</u></a></li>
<li><a href="https://win11.techidaily.com/1719286453674-library-installation/"><u>Library Installation:</u></a></li>
<li><a href="https://screen-recording.techidaily.com/maximizing-quality-in-ppt-recordings-for-2024/"><u>Maximizing Quality in PPT Recordings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-app-changes-in-the-latest-windows-11-update/"><u>Navigating App Changes in the Latest Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-detect-camera-in-win11/"><u>Overcoming Unable to Detect Camera in Win11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-honor-90-pro-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Honor 90 Pro? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-windows-safescreensaver-alteration/"><u>Preventive Measures for Windows SafeScreensaver Alteration</u></a></li>
<li><a href="https://win11.techidaily.com/pro-guide-how-to-locate-and-setup-shortcuts-near-win11s-power-icon/"><u>Pro Guide: How to Locate & Setup Shortcuts Near Win11's Power Icon</u></a></li>
<li><a href="https://win11.techidaily.com/reset-and-reboot-your-way-back-into-the-ms-store-windows-11/"><u>Reset & Reboot Your Way Back Into the MS Store (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-flight-comrade-copilot-in-ws11/"><u>Restore Your Flight Comrade (Copilot) in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-group-policy-management-in-windows-108/"><u>Simplifying Group Policy Management in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/squared-up-strategies-boosting-video-popularity-on-the-platform/"><u>Squared Up Strategies  Boosting Video Popularity on the Platform</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-security-keys-mismatch-in-windows-11-networks/"><u>Strategies for Correcting Security Keys Mismatch in Windows 11 Networks</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-vm-workflow-6-expert-tips-for-windows-users/"><u>Supercharge Your VM Workflow: 6 Expert Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/tech-guide-uninstalling-the-microsoft-store/"><u>Tech Guide: Uninstalling the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-speed-mastering-double-click-on-windows-pc/"><u>Triumph in Speed: Mastering Double-Click on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-program-install-pathways-in-windows/"><u>Unveiling Program Install Pathways in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y78t-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y78t Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-enlargement-and-reduction-the-top-six-methods/"><u>Windows 11 Image Enlargement and Reduction – The Top Six Methods</u></a></li>
</ul></div>
