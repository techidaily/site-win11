---
title: "Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity"
date: 2024-07-13T09:44:15.700Z
updated: 2024-07-14T09:44:15.700Z
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

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can [merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons [why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

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
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

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
<li><a href="https://win11.techidaily.com/reset-and-reboot-your-way-back-into-the-ms-store-windows-11/"><u>Reset & Reboot Your Way Back Into the MS Store (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-achieving-expert-control-the-steam-switch-controllers-guide/"><u>[New] In 2024, Achieving Expert Control  The Steam Switch Controllers Guide</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-windows-hard-drive-sustainably/"><u>Expanding Windows Hard Drive Sustainably</u></a></li>
<li><a href="https://win11.techidaily.com/determining-the-ideal-nearby-networking-method-google-vs-windows/"><u>Determining the Ideal Nearby Networking Method: Google Vs. Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-complete-guide-to-record-desktop-screen-on-windows-for-free-3-ways-for-2024/"><u>[New] Complete Guide to Record Desktop Screen on Windows for Free [3 Ways] for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unveiling-the-power-of-consistency-in-your-tiktok-clone-journey/"><u>Unveiling the Power of Consistency in Your TikTok Clone Journey</u></a></li>
<li><a href="https://extra-resources.techidaily.com/script-extraordinary-showcase/"><u>Script Extraordinary Showcase</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-apps-to-monitor-win-os-temperatures/"><u>Ideal Apps to Monitor Win OS Temperatures</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-what-does-the-blue-marker-on-fb-chat-reveal/"><u>[New] 2024 Approved  What Does the Blue Marker on FB Chat Reveal?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-obs-studio-vs-bandicam-a-comprehensive-performance-review/"><u>2024 Approved  OBS Studio Vs. Bandicam  A Comprehensive Performance Review</u></a></li>
<li><a href="https://win11.techidaily.com/probing-the-heart-of-windows-systems-generating-insightful-reports/"><u>Probing the Heart of Windows Systems: Generating Insightful Reports</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-real-time-tv-broadcast-preservation-the-easy-guide/"><u>[Updated] 2024 Approved  Real-Time TV Broadcast Preservation - The Easy Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-login-delays-windows-and-rust-edition/"><u>Resolving Steam Login Delays: Windows & Rust Edition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ingenious-ways-to-enhance-trustworthiness-in-client-spots-on-screen/"><u>2024 Approved  Ingenious Ways to Enhance Trustworthiness in Client Spots on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win-error-no-access-to-network-paths/"><u>Solving WIN Error: No Access to Network Paths</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-an-ultimate-guide-to-edit-a-music-video-aspect-ratio-and-first-cut/"><u>Updated An Ultimate Guide to Edit a Music Video Aspect Ratio and First Cut</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-latency-and-silence-in-valorants-voice-communication-windows/"><u>Fixing Latency and Silence in Valorant's Voice Communication (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-pc-performance-installing-easy-to-use-enhancement-tool-for-windows/"><u>Maximizing PC Performance: Installing Easy-to-Use Enhancement Tool for Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-livetv-prowess-elevating-facebook-live-broadcasts-for-2024/"><u>[New] LiveTV Prowess  Elevating Facebook Live Broadcasts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-microsofts-bluetooth-app/"><u>A Step-by-Step Guide to Using Microsoft's Bluetooth App</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-online-broadcast-battle-fb-live-and-yt-live-vs-tweetstreams/"><u>[Updated] Online Broadcast Battle  FB LIVE & YT Live Vs. TweetStreams</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absent-windows-notification-icons/"><u>Fixes for Absent Windows Notification Icons</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-join-mpeg-videos-for-free-top-5-solutions/"><u>New In 2024, Join MPEG Videos for Free Top 5 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-data-discovery-on-pc-via-everythingapp/"><u>Effortless Data Discovery on PC via EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-mystery-of-the-blank-steam-window/"><u>Dealing With the Mystery of the Blank Steam Window</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-uncover-the-secrets-of-the-best-audio-conversion-tools/"><u>2024 Approved Uncover the Secrets of the Best Audio Conversion Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-playback-issues-with-windows-errors/"><u>Overcoming Playback Issues with Windows Errors</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revolutionize-visual-storytelling-by-incorporating-cg-centrals-look-up-tables-luts/"><u>2024 Approved  Revolutionize Visual Storytelling by Incorporating CG Central's Look-Up Tables (Luts)</u></a></li>
<li><a href="https://win11.techidaily.com/secure-edge-with-microsofts-advanced-protection-technology-aguard-on-windows-11/"><u>Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruption-nightmares-keeping-your-ps4-remote-connected/"><u>Overcoming Interruption Nightmares: Keeping Your PS4 Remote Connected</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disconnect-in-windows-remote-play-feature/"><u>Solving Disconnect in Windows Remote Play Feature</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-application-not-installed-via-microsofts-store/"><u>Fixing an Application Not Installed via Microsoft's Store</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-installer-access-rights-shortcomings/"><u>Fixing Windows Installer Access Rights Shortcomings</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-investors-intuition-selecting-stock-channel-wisely/"><u>In 2024, Investor's Intuition  Selecting Stock Channel Wisely</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-windows-defender-error-0x80004004/"><u>Deciphering & Correcting Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-how-to-fix-wsl-error-code-4294967295-on-your-pc/"><u>Mastering How to Fix WSL Error Code: 4294967295 on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-fixing-the-frozen-resource-monitor-app-in-win11/"><u>Diagnosing and Fixing the Frozen Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-proficiency-the-path-to-mastering-project/"><u>Keyboard Proficiency: The Path to Mastering Project</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-a-comprehensive-guide-to-adding-text-overlays-on-tiktok/"><u>[New] In 2024, A Comprehensive Guide to Adding Text Overlays on TikTok</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/top-rated-mp4-video-tagging-tools-for-windows-and-macos-for-2024/"><u>Top-Rated MP4 Video Tagging Tools for Windows and macOS for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-unveiling-the-youtube-creator-hub-a-guide/"><u>[Updated] Unveiling the YouTube Creator Hub  A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/countering-dxgideviceremoved-failsafe-techniques/"><u>Countering DXGI_DEVICE_REMOVED Failsafe Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-control-on-1011-windows-os/"><u>Reinstating Synapse Control on 10/11 Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-adding-folders-without-delays-in-windows-onedrive/"><u>Mastering the Art of Adding Folders without Delays in Windows OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/enable-microphone-and-camera-via-app-guard-in-windows-11/"><u>Enable Microphone & Camera via App Guard in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/accelerate-engagement-implementing-the-top-12-video-growth-strategies/"><u>Accelerate Engagement - Implementing the Top 12 Video Growth Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-your-galaxy-experience-utilizing-the-dex-app-in-windows/"><u>Enrich Your Galaxy Experience: Utilizing the DeX App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-education-themes-on-windows-11/"><u>How to Enable Education Themes on Windows 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-driving-engagement-from-few-followers-to-million-views/"><u>[New] In 2024, Driving Engagement  From Few Followers to Million Views</u></a></li>
<li><a href="https://win11.techidaily.com/lightening-windows-11-startup-latency-tips-for-a-speedy-launch/"><u>Lightening Windows 11 Startup Latency – Tips for a Speedy Launch</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-altering-file-deletion-alerts-in-win/"><u>Steps for Altering File Deletion Alerts in Win</u></a></li>
<li><a href="https://games-able.techidaily.com/deciphering-the-steam-user-alias-digitally/"><u>Deciphering the Steam User Alias Digitally</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-11-notification-settings/"><u>Tailor Windows 11 Notification Settings</u></a></li>
</ul></div>
