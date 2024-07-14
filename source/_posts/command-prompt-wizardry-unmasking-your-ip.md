---
title: "Command Prompt Wizardry: Unmasking Your IP"
date: 2024-07-13T10:40:11.000Z
updated: 2024-07-14T10:40:11.000Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Prompt Wizardry: Unmasking Your IP"
excerpt: "This Article Describes Command Prompt Wizardry: Unmasking Your IP"
keywords: IP Unveil Secrets,Command IP Hack,Dissect IP Address,Uncover IP Details,Master IP Exposure,Decode IP Info,Reveal IP Mystery
thumbnail: https://thmb.techidaily.com/fe142fc722967440c0a67173b1e546447bf0e801339eadf58291eb4451fb4b01.jpg
---

## Command Prompt Wizardry: Unmasking Your IP

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

 Windows offers multiple ways to view your network information, including the IP address. For instance, you can easily [check your IP address from the Settings app](https://www.makeuseof.com/tag/find-ip-address-windows-10/). You can also use the Network and Sharing Center in Control Panel or dig a little bit in the Task Manager’s Performance tab to access your system’s network details.

 But if you would rather skip multiple clicks and are comfortable with Command Prompt, the ipconfig (Internet Protocol configuration) command is all you need. It is easy to remember and shows more information quickly than the Settings app.

 Follow these steps to get your Private IP address using Command Prompt:

1. Press the **Win** key, and type **cmd**. From the search result, click on **Command Prompt**.
2. Next, type the following command in the Command Prompt window and press Enter:  
`ipconfig`
3. The output will display a host of network information. Look for the IPv4 address for your Ethernet or Wireless LAN adapter to identify your private IP address.
4. If you need complete information, including NetBIOS over TCPIP, DHCP status, and Physical IP address, use the following command instead:  
`Ipconfig /all`
5. You’ll likely see multiple network adapter entries with unique IP addresses. This is usually due to your computer having multiple network adapters, including Ethernet, Wireless LAN, and vEthernet switches.

 If you need to share the output for troubleshooting purposes, you can export the output to a text file. In Command Prompt, run **ipconfig > NetworkInfo.txt** to save the output to a **NetworkInfo.text** file. By default, it is saved to the **C:\\Users\\Username** directory.

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

 Unlike the private IP address, the **ipconfig** command cannot retrieve the public IP address of your ISP. Instead, you’ll need to [use the curl command-line utility to make HTTP requests](https://www.makeuseof.com/curl-how-make-http-requests/) using a third-party service, like ifconfig.me, to obtain IP address mapping information.

 The newer versions of the OS, Windows 10 and 11, come with the curl utility built-in. If you are using an older version, you may need to install curl for Windows to run the utility.

 Follow these steps to get the public IP address using Command Prompt:

1. Press **Win + R**, type **cmd** and click **OK** to [open Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/)
2. Type the following command in the Command Prompt window and press Enter:  
`curl ifconfig.me`
3. The above command sends an HTTP request to the **ifconfig.me** server, which returns your public IP address information. Similarly, you can visit the **ifconfig.me** URL using your web browser to view your public IP address.
4. That said, if the **ifconfig.me** command doesn’t return a public IPv6 address, use the following command instead:  
`nslookup myip.opendns.com resolver1.opendns.com`
5. The above command uses the **nslookup** command-line utility to retrieve your public IP address using the OpenDNS service. Your public IPv6 address will look something like this 2401:\*\*00:1c08:55f0:594b:cdbe:\*\*\*\*.\*\*\*\*.

 If you check your public IPv6 address again after a few hours or days—depending on the router's configuration—you may notice a different IPv6 address. Due to privacy concerns, your router dynamically assigns and changes the IPv6 address for all connected devices.

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/crack-the-ms-pc-manager-install-issue-on-windows-xp/"><u>Crack the MS PC Manager Install Issue on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-correcting-not-working-error-in-windows/"><u>Breaking Down and Correcting 'Not Working' Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/4-easy-ways-to-create-a-new-folder-in-windows-11/"><u>4 Easy Ways to Create a New Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-reasons-why-pcs-outshine-macs-9/"><u>Essential Reasons Why PCs Outshine Macs (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unable-to-open-error-in-geforce-experience-windows/"><u>Resolving Unable to Open Error in GeForce Experience Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/venturing-into-virtual-steps-top-treadmill-analysis-for-2024/"><u>Venturing Into Virtual Steps  Top Treadmill Analysis for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-understanding-aspect-ratio-regulations-on-twitter/"><u>[Updated] Understanding Aspect Ratio Regulations on Twitter</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-streamlining-the-process-of-converting-zip-to-srt/"><u>[Updated] Streamlining the Process of Converting Zip to Srt</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-extend-a-volume-on-windows-without-erasing-personal-data/"><u>How to Extend a Volume on Windows Without Erasing Personal Data</u></a></li>
<li><a href="https://win11.techidaily.com/1719322242538-mastering-printer-troubles-reactivating-missing-wwinplusp-on-windows/"><u>Mastering Printer Troubles: Reactivating Missing WWin+P on Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-from-chaos-to-clarity-mastering-xiaomis-screen-recording/"><u>[New] 2024 Approved  From Chaos to Clarity  Mastering Xiaomi's Screen Recording</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/achieve-perfect-youtube-broadcasts-with-superior-webcams/"><u>Achieve Perfect YouTube Broadcasts with Superior Webcams</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-top-3ips-most-acclaimed-ipad-audio-capturing-tools/"><u>[New] Top 3iP's Most Acclaimed iPad Audio Capturing Tools</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-tip-revive-missing-windows-xp10-printer/"><u>[Tech Tip] Revive Missing Windows XP/10 Printer</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-saturated-capacity-in-chatgpt/"><u>Alleviating Saturated Capacity in ChatGPT</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/seamless-video-watch-removing-youtube-barriers-for-2024/"><u>Seamless Video Watch  Removing YouTube Barriers for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-voice-muting-breakthroughs-a-comprehensive-compilation-of-10-leading-applications-and-platforms/"><u>New 2024 Approved Voice Muting Breakthroughs A Comprehensive Compilation of 10 Leading Applications & Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-settings-managing-device-permissions/"><u>Navigating Windows Settings: Managing Device Permissions</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-game-access-issues-windows-and-xbox-edition/"><u>Tackling Game Access Issues - Windows and Xbox Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-onedrive-and-microsoft-id-for-pc-users/"><u>Bridging the Gap: OneDrive & Microsoft ID for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-read-only-folders-without-compromise-in-windows/"><u>Correcting Read-Only Folders Without Compromise in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unwanted-windows-start-up-in-bios-landing/"><u>Overcoming Unwanted Windows Start-Up in BIOS Landing</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-perfecting-webp-conversion-to-jpeg-format/"><u>In 2024, Perfecting WebP Conversion to JPEG Format</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tips-for-a-pristine-image-canvas-background-technique/"><u>[Updated] Tips for a Pristine Image  Canva's Background Technique</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-error-0xfffffff-with-ease/"><u>Solving Windows' Error 0xFFFFFFF with Ease</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-honor-90-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Honor 90 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-notification-interface-in-win-11/"><u>Tailoring Your Notification Interface in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-windows-restoration-options/"><u>Dive Deep Into Windows Restoration Options</u></a></li>
<li><a href="https://win11.techidaily.com/five-smart-choices-of-windows-devices/"><u>Five Smart Choices of Windows Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/impeccable-photo-cleanup-with-top-6-iphone-tools-for-objection-exclusion/"><u>Impeccable Photo Cleanup with Top 6 iPhone Tools for Objection Exclusion</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-w11s-0x8004def5-onedrive-malfunction/"><u>Unraveling the Mystery of W11's 0X8004def5 OneDrive Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-normalcy-in-corporate-governed-chromium-and-microsoft-edge-browsing/"><u>Regaining Normalcy in Corporate-Governed Chromium & Microsoft Edge Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-is-now-microsofts-new-ai-enhanced-taskbar-for-windows-11-users/"><u>The Future Is Now: Microsoft’s New AI-Enhanced Taskbar for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-windows-11-pitfalls/"><u>Addressing Common Windows 11 Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/a-blueprint-for-an-enhanced-taskbar-in-microsofts-next-windows-release/"><u>A Blueprint for an Enhanced Taskbar in Microsoft's Next Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/risks-and-precautions-deleting-windows-bt-folder/"><u>Risks & Precautions: Deleting Windows ~BT Folder</u></a></li>
<li><a href="https://win11.techidaily.com/restarting-routine-efficiently-installing-windows-11/"><u>Restarting Routine: Efficiently Installing Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-tecno-pop-8-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Tecno Pop 8 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rearranging-display-panel-configurations/"><u>Rearranging Display Panel Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-your-pcs-dead-hub-a-windows-fix-guide/"><u>Resurrecting Your PC's Dead Hub: A Windows Fix Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-fcpx-lower-thirds-mastery-best-practices-and-techniques/"><u>Updated In 2024, FCPX Lower Thirds Mastery Best Practices and Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/silence-non-pertinent-windows-advisory-messages/"><u>Silence Non-Pertinent Windows Advisory Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-switching-on-updated-widget-selection-interface-in-windows-11/"><u>Seamlessly Switching on Updated Widget Selection Interface in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-tech-appbrowser-rule/"><u>Understanding Windows Tech: App/Browser Rule</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-cultivate-creativity-10-inspiration-boosting-videos/"><u>[Updated] In 2024, Cultivate Creativity  10 Inspiration-Boosting Videos</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-file-format-alterations-on-your-pc/"><u>Streamline File Format Alterations on Your PC</u></a></li>
<li><a href="https://audio-editing.techidaily.com/banned-from-omegle-how-to-get-unbanned/"><u>Banned From Omegle? How to Get Unbanned?</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-indefinite-deletion-settings-in-windows-desktop-bin/"><u>Initiating Indefinite Deletion Settings in Windows Desktop Bin</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-microsoft-offices-0x80041015-problematic-error/"><u>Solutions to Microsoft Office's 0X80041015 Problematic Error</u></a></li>
<li><a href="https://win11.techidaily.com/decrypting-wacatacbml-trojan-a-step-by-step-windows-cleanup/"><u>Decrypting Wacatac.B!ml Trojan: A Step-by-Step Windows Cleanup</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-upscale-your-old-videos-with-madvr-for-windows/"><u>How to Upscale Your Old Videos With MadVR for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumbled-glitches-win-1111-store-correction-guide/"><u>Bypassing 'Server Stumbled' Glitches: Win 11/11 Store Correction Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-error-code-0x80070570-repair-corrupted-filesdirectories/"><u>Reversing Error Code 0X80070570: Repair Corrupted Files/Directories</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-deletion-with-windows-context-add-ons/"><u>Streamlining Deletion with Windows Context Add-Ons</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-common-anydesk-errors-on-windows/"><u>Mastering the Art of Resolving Common AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-difference-between-chkdsk-sfc-and-dism-in-windows/"><u>What Is the Difference Between CHKDSK, SFC, and DISM in Windows?</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-digital-game-chronicles/"><u>[New] 2024 Approved  Digital Game Chronicles</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-customize-your-outlook-calendar-on-windows/"><u>How to Customize Your Outlook Calendar on Windows</u></a></li>
</ul></div>
