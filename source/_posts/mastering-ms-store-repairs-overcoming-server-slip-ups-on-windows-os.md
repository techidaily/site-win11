---
title: "Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS"
date: 2024-07-13T10:38:22.017Z
updated: 2024-07-14T10:38:22.017Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS"
excerpt: "This Article Describes Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS"
keywords: Mastering MS Store,Fix Server Slips,Win OS Troubleshooting,MSI Store Repairs,Windows OS Maintenance,Solve OS Glitches,Prevent Errors in MS
thumbnail: https://thmb.techidaily.com/c2522eefb8fbc96fa570f56849cfdf92d72e221bd3a27b7e0b7d3fec1332bd02.png
---

## Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS

 Some Microsoft Store users have reported a “server stumbled” error on support forums. Those users have seen this error message within the Microsoft Store app: “The server stumbled… We all have bad days.” That error message usually has 0x80072F05, 0x80131500, or 0x80072ee7 codes.

 This is yet another error that makes the Microsoft Store app unusable when users launch it. Does the same “server stumble” error message crash your Microsoft Store app? If that’s the case, this is how you can resolve that “server stumble” error in Windows 11 and 10.

## 1\. Run the Troubleshooter for Microsoft Store Apps

 The Windows Store App troubleshooter can resolve issues that stop the Microsoft Store app from working. Running that troubleshooter isn’t a surefire fix for every Microsoft Store error, but it’s worth a try.

 These are the steps for running the Windows Store App troubleshooter in Windows:

1. Press**Win + I** keyboard shortcut to open Settings.
2. Then select the**Troubleshoot** navigation bar within Settings’ default**System** tab.
3. Click**Other troubleshooters** to reach the troubleshooting tools.
4. Select the**Run** option for launching Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-run-button.jpg)
5. Click to apply any potential fix suggested within the troubleshooter.  
![Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-store-apps-troubleshooter.jpg)

 The steps for opening the same troubleshooter in Windows 10 aren’t exactly the because of the Settings app’s different layout. You’ll need to click**Update & Security** \>**Troubleshoot** \>**Additional Troubleshooters** in Windows 10’s Settings app. Click Windows Store Apps to press a**Run the troubleshooter** button that opens that troubleshooting tool.

## 2\. Check the Date & Time Settings on Your PC

 Date & time discrepancies on your PC can cause Microsoft Store connectivity issues like the “server stumbled” error to arise. Check the time zone you’ve got set matches up with your PC’s regional configuration. You can verify your PC’s time by selecting to sync its clock. This is how you can check the time configuration within Settings:

1. Open Settings and select the**Time & language** tab.
2. Then click**Date & time** to view those settings.
3. Make sure the correct time zone for your region is selected on the**Time zone** drop-down menu.  
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/time-zone-drop-down-menu.jpg)
4. Press the**Sync now** button to synchronize with the Windows time server.

## 3\. Start or Restart the Windows Update Service

 MS Store users have confirmed they’ve fixed the “server stumbled” error by starting or restarting the Windows Update service. The Windows Update service is linked with Microsoft Store. So, make sure that the update service is enabled and running as follows:

1. Press**Win + S** to access the Windows Search tool.
2. Type "services," then select**Services** to access the app.
3. Double-click**Windows Update** to view the various settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-service.jpg)
4. Select**Automatic** if any other option is set on the**Startup** type drop-down menu.
5. Then click the service’s**Start** option if Windows Update is stopped.
6. Press**Apply** to set the service settings.  
![The Windows Update Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-properties-window.jpg)
7. Click**OK** or the**X** button to exit Windows Update’s properties window.

 Restart Windows Update if you find that the service is already running with an**Automatic** startup set. You can do that by clicking Windows Update with your mouse’s right button and selecting**Restart** . Or select**Stop** and then**Start** within its properties window.

![The Restart option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-option.jpg)

## 4\. Reset the Microsoft Store Cache

 The Microsoft Store has a cache containing temporary, thumbnail, and log file data. A clogged-up cache with corrupted data can cause many MS Store issues. So, some users might need to reset (clear) that cache to fix the “server stumbled” error.

 You can clear that cache by entering the**WSreset.exe** command as outlined in method two within our guide on [how to reset the Microsoft Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/) .

![The wsreset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsreset-command.jpg)

## 5\. Turn Off Any Active Proxy Server Settings

 Some users use a proxy server to mask their IP address, but doing sooften causes Microsoft Store connection errors. If you’ve got an intermediary proxy server enabled on your PC, disable it via Settings or the Control Panel.

 Our guide on [how to disable the proxy server settings on Windows](https://www.makeuseof.com/windows-11-disable-proxy/) provides step-by-step instructions for both methods.

![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/use-a-proxy-server-option.jpg)

## 6\. Set Up a Connection to Google's DNS Servers

 The “server stumbled” error message highlights that the error could be linked to your PC’s DNS (Domain Name System) server. So, changing to a more reliable public server like Google DNS is a potential resolution that could feasibly work for some users.

 It is indeed the case some users have confirmed setting a Google DNS fixed this error on their PCs. To do that, check out our article about [how to change a DNS server](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) , which also includes Google’s IPv4 addresses.

![DNS settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/dns-settings.jpg)

## 7\. Disable Any Active Third-Party Security Software

 Third-party security software packages that incorporate antivirus shields and firewalls can interfere with MS Store’s network connection. The firewall components of security apps will more likely do so since they monitor inbound and outbound network traffic. So, try temporarily disabling a firewall within any third-party security installed on your PC before opening MS Store.

 However, don’t rule out the possibility that an antivirus component of an installed third-party security app could also be causing the “server stumbled” error. You can usually disable an antivirus shield by right-clicking the security software’s system tray icon and selecting a turnoff option.

 Should this troubleshooting method work, you don’t necessarily need to leave your security software disabled or uninstall it. Instead, add MS Store to the firewall’s allowed app list within your antivirus software. In addition, add that app to the antivirus component’s whitelist.

## 8\. Enable TLS

 If you’re seeing a “server stumbled” error with 80072EFD or 80072EFF codes, you might need to enable some TLS (Transport Layer Security) protocol settings to resolve the issue. Enable TLS with the following steps:

1. Activate Run by pressing**Win + R** .
2. Type**inetcpl.cpl** (for Internet Options) inside Run and select OK.
3. Click**Advanced** to view that tab’s options.
4. Select the Use**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The TLS checkboxes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/tls-settings.jpg)
5. Press**Apply** in the Internet Properties window.
6. Click**OK** to exit Internet Properties.

## 9\. Reregister the Microsoft Store

 Reregistering Microsoft Store will reset that app to its factory defaults. That’s a troubleshooting method worth trying if nothing else resolves the “server stumbled” error. You can apply this potential fix by executing a PowerShell command that generally reregisters pre-installed Windows apps.

 Our article about [reregistering Microsoft Store apps on Windows](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) includes step-by-step instructions for executing that command.

![The reregister command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reregister-command.jpg)

## Download and Install Apps From the Microsoft Store Again

 Many users have stopped the “server stumbled” error crashing MS Store by applying the potential fixes outlined above. So, there’s a strong likelihood that one of those resolutions will get that issue sorted on your Windows 11/10 PC. Then you can get back to downloading and installing apps from Microsoft Store.

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
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-woes-a-script-error-cure-all-guide/"><u>Tackling Windows Woes: A Script Error Cure-All Guide</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/capturing-the-essence-of-cricket-soundscape-for-2024/"><u>Capturing the Essence of Cricket Soundscape for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-cross-device-iptv-broadcasting/"><u>[Updated] In 2024, Cross-Device IPTV Broadcasting</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-store-issues-address-x80072f17/"><u>Streamlining Windows Store Issues: Address X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/running-task-manager-administrative-command-for-windows-11/"><u>Running Task Manager: Administrative Command for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-xiaomi-redmi-note-12t-pro-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-itel-a60s-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Itel A60s FRP Bypass</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-elite-groups-top-12-camcorders-featuring-gps-mapping-capabilities/"><u>[Updated] Elite Group's Top 12 Camcorders  Featuring GPS Mapping Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-network-failure-on-modern-pc-win11/"><u>Tackling Steam Network Failure on Modern PC, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/clear-path-to-correctness-resolving-server-stumbled-issues-in-win-store/"><u>Clear Path to Correctness: Resolving Server Stumbled Issues in Win Store</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-everlasting-deactivation-of-microsoft-defender/"><u>Secrets to Everlasting Deactivation of Microsoft Defender</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-capture-and-convert-fb-videos-immediitsly-to-mp3/"><u>[Updated] In 2024, Capture and Convert FB Videos Immediitsly to MP3</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-the-hidden-traps-in-inexpensive-keys/"><u>Windows Activation: The Hidden Traps in Inexpensive Keys</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-filmora-coupon-guide-4-easy-ways-to-redeem-exclusive-offers/"><u>2024 Approved Filmora Coupon Guide 4 Easy Ways to Redeem Exclusive Offers</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-motorola-edge-40-neo-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Motorola Edge 40 Neo If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-post-update-linux-subsystem-challenges-on-windows-11/"><u>Unraveling Post-Update Linux Subsystem Challenges on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-conquer-collages-with-these-12-examples/"><u>[Updated] How to Conquer Collages with These 12 Examples</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/capturing-slideshows-on-screen-webcam-tips-and-tricks/"><u>Capturing Slideshows on Screen  Webcam Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-fresh-air-reviving-outdated-microsoft-store-apps/"><u>Breath of Fresh Air: Reviving Outdated Microsoft Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/address-excel-display-issue-in-windows-notepad/"><u>Address: Excel Display Issue in Windows Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-tasks-with-the-magic-of-flow-launcher/"><u>Supercharge Your Tasks with the Magic of Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-encryption-apps-for-windows/"><u>The 7 Best Encryption Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-bandwidth-gap-between-laptops-phones/"><u>Bridging the Bandwidth Gap Between Laptops, Phones</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/how-to-minimize-stress-in-ipad-screen-recordings-heres-a-way-for-2024/"><u>How to Minimize Stress in iPad Screen Recordings? Here's a Way for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://win11.techidaily.com/steering-device-interactions-from-power-save-mode/"><u>Steering Device Interactions From Power Save Mode</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/win11-mastering-custom-key-combos-for-fixed-text-insertions/"><u>Win11: Mastering Custom Key Combos for Fixed Text Insertions</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-why-excel-opens-fail-in-notepad/"><u>Understanding Why Excel Opens Fail in Notepad</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-vivo-v27-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Vivo V27 Phone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-utilizing-apples-messaging-service-on-pc/"><u>Understanding and Utilizing Apple's Messaging Service on PC</u></a></li>
</ul></div>
