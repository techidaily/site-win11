---
title: Cross-Platform Cloud File Retrieval Methods
date: 2024-08-15T23:30:07.977Z
updated: 2024-08-16T23:30:07.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cross-Platform Cloud File Retrieval Methods
excerpt: This Article Describes Cross-Platform Cloud File Retrieval Methods
keywords: Cross-Cloud Access,Platform File Sharing,Multiplatform Storage,Cloud File Retrieval,Universal File Access,Secure Data Transfer,Cloud Services Interoperability
thumbnail: https://thmb.techidaily.com/e274a732c7d0d3f61527d48aecc65a65fbbf84ca45a89dafe19b065f7716c31c.jpg
---

## Cross-Platform Cloud File Retrieval Methods

 If you searched for ways to access your Windows files from your Android/iOS devices, chances are you landed on guides suggesting you to download all sorts of external applications, free or paid. Did you know that you absolutely don't need any external application for file transfers across your devices? Well, now you do. Windows Network Share is a really easy way of sharing files, folders, or entire drives across devices on the same network. Let's learn how to set up Windows Network Share to access your PC files from Android/iOS.

## What Is Network File Sharing?

 When you want to share a file or folder with someone, sometimes it is faster to share it over your local network, rather than uploading to the cloud or looking for a USB flash drive. This process is called network file sharing. File Transfer Protocol (FTP) is also a valid option for file sharing remotely or on the local network but, it's much more of a hassle to set up than Windows Network Share.

 Windows Network Share utilizes the SMB protocol internally to make files, directories, or, entire drives available for read/write access for devices on the local network. While it's super easy and swift to set up, it's also a common target for adversaries. So, it's wise that you learn [how the SMB protocol works and some common SMB vulnerabilities](https://www.makeuseof.com/what-is-smb-protocol-and-what-are-its-risks/) to ensure that your network perimeter isn't breached.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## How to Share a Windows Drive on Your Local Network

 To access your computer's files, you need to share them on the local network. For the demonstration, I'll be sharing a drive on the local network. If you wish to share a folder or a single file instead, you can follow the same steps but with only the folder(s) and file(s) selected.

 Before you dive into the steps, it's recommended you [create a separate, local Windows user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to be used solely for network drive access.

 Here are the steps to share files on the local network in Windows 10/11:

1. **Right-click** on the drive you want to share.
2. From the drop-down menu, click on **Properties**.
3. In the **Properties** menu, go to the **Sharing** tab.  
![sharing tab open in properties menu of a drive-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sharing-tab-open-in-properties-menu-of-a-drive-1.jpg)
4. Click on **Advanced Settings** in the new pop-up menu, check the **Share this folder** box, and wait, it's not over yet. Now to prevent unsolicited access to your locally shared drives, click on **Permissions**.
5. In the new menu that pops up, click on **Add**. Yet another box should pop up. Here, type in the username of your user account. Use a dedicated user account only for network access or use your primary account's username and press **Enter**. You should find your name is present on the list of users with permission to the shared drive.  
![Adding a new user in the access group of the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-a-new-user-in-the-access-group-of-the-shared-drive.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
6. Finally, click on your account name, and in the **Permissions for <account name>** section, check the **Full Control** box and hit **Apply**.  
![Adding permissions to the user account and confimring changes by pressing on Apply](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-permissions-to-the-user-account-and-confimring-changes-by-pressing-on-apply.jpg)

 That's all the steps to share your drive on the local network. However, if you run into any trouble, it's recommended you check out the [dedicated guide on enabling Windows Network Share](https://www.makeuseof.com/how-network-file-share-windows-10/).

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Access Your Windows Files From an Android Device

 Now that you have shared the drive on the local network you'll be able to access your newly shared drives and files from your Android device in just a few taps. Make sure your Android device and Windows PC are connected to the same Wi-Fi network. With these checks out of the way, let's look at the steps to access Windows network shared files from Android:

1. Fire up the **Files** application on your Android device.
2. On the **Files** application, scroll to **Network Storage** and tap on it.
3. Inside **Network Storage**, tap on **Add network storage**. You might be asked to select an option from a list of protocols. Tap on **Network Drive** or any option with **SMB** in the name.
4. Your device will start to scan for locally shared drives. Wait for it to locate your Windows drive. If your device is unable to locate it follow the next steps. First, you need to [find the IP address of your Windows PC](https://www.makeuseof.com/find-ip-mac-address-windows-powershell/).
5. After noting the IP address, go back to your Android device and tap on **Add Manually**.
6. In the new window, type in the IPv4 address you copied earlier into the Address field. Then, type **445** into the **Port** field. Finally, fill in the **Username** and **Password** fields with your account credentials and hit on **Add** or **Connect**.

![Selecting Network Share on Files app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-network-share-on-files-app.jpg)

![Selecting SMB Protocol](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-smb-protocol.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->

![Manually adding the device and account details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/manually-adding-the-device-and-account-details.jpg)

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpg)

Close

 Now, you should be able to access files on your Windows PC from your Android device. You can modify the files or download them to your Android device. All done without ever needing any external application!

 On some devices, such as Samsung phones, when you click on **Network Storage**, you might be asked to update the Files app to add the network access functionality. Proceed to do so, and then return to the guide.

## How to Access Your Windows Files From an iOS Device

 The steps to access Windows files from iOS are pretty much identical to the steps required for Android devices. Here's how you can access your Windows PC's files from iOS:

1. Before opening your iOS device. You need to grab the IP address of your Windows PC. There are multiple ways to do it. The easiest one being typing in **cmd** in the search box and then using the **ipconfig** command to fetch network-related details. Note down the value of the IPv4 field.
2. Fire up the **Files** application on your iOS device.
3. Click on the three horizontal dots (ellipsis) in the top right corner. From there, select **Connect to Server**.
4. A new window should open up asking you to input the IP address of the shared drive. Type in the IP address that you previously noted down and tap on **Next**.
5. Then, you will be prompted to enter the user account credentials to access the shared drive. Type them in and tap on **Next**.

![Connecting to the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/connecting-to-the-shared-drive.jpeg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Typing in the IP of the Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-the-ip-of-the-windows-pc.jpeg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Typing in user account credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-user-account-credentials.jpeg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpeg)

![The shared drive being listed on the Browse Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-shared-drive-being-listed-on-the-browse-menu.jpeg)

Close

 Now you should be able to view the files on the shared drive. You can now download, upload or modify the local files on your Windows PC with ease and without having to download any third-party application.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Access Your PC Files on iOS/Android Without Third-Party Apps

 Now that you know how to access your PC files using Windows Network Share, uploading, downloading, and modifying files should be super easy to do. You won't have to rely on downloading and testing third-party applications for minor tasks like copying over a PDF file from your Windows PC to your Android/iOS devices.

 If you wish to share files between computers on the same network, that is possible as well. But, for heavy file sharing between two computers, a few alternatives to network sharing may be worth checking out if you'll be sharing large chunks of data.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-adobes-quest-for-giggles-and-grins/"><u>[Updated] In 2024, Adobe's Quest for Giggles and Grins</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-unveiling-social-media-stars-your-niches-influencers-guide/"><u>[Updated] In 2024, Unveiling Social Media Stars  Your Niche’s Influencers Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-innovating-with-ideas-constructing-your-unique-tiktok-sequence-for-2024/"><u>[Updated] Innovating with Ideas  Constructing Your Unique TikTok Sequence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wsl-2-streamline-docker-usage/"><u>Boosting WSL 2: Streamline Docker Usage</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-tasks-custom-windows-shortcuts-for-uwp/"><u>Breeze Through Tasks: Custom Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/bring-task-manager-above-all-step-guide/"><u>Bring Task Manager Above All: Step Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/concealed-viewers-guide-to-instagram-live-broadcasting-without-attention/"><u>Concealed Viewers' Guide to Instagram Live Broadcasting Without Attention</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-save-configuration-errors-in-pubg/"><u>Correcting Save Configuration Errors in PUBG</u></a></li>
<li><a href="https://facebook.techidaily.com/curbing-covid-through-snapchat-tweet-and-facebook-campaigns/"><u>Curbing COVID Through Snapchat, Tweet, and Facebook Campaigns</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-ideal-nvidia-drivers-gaming-vs-production-sector/"><u>Deciding on Ideal Nvidia Drivers: Gaming vs Production Sector</u></a></li>
<li><a href="https://article-helps.techidaily.com/diving-into-drones-syma-x5c-review-beginners-dream-uav/"><u>Diving Into Drones? Syma X5C Review  Beginner's Dream UAV</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-with-top-5-affordable-car-update-tools/"><u>Elevate Your Windows Experience with Top 5 Affordable Car Update Tools</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuity-with-powertoys-settings-transfer/"><u>Ensuring Continuity with PowerToys Settings Transfer</u></a></li>
<li><a href="https://win11.techidaily.com/essential-sync-software-windows-and-android-unite/"><u>Essential Sync Software: Windows & Android Unite</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/exporting-tweets-as-webmaac-audio-for-2024/"><u>Exporting Tweets as WebM/AAC Audio for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-geforce-error-x0001-on-windows-pcs/"><u>Fixing Common GeForce Error X0001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-ctrl-keys-in-windows-11/"><u>Fixing Non-Operational Ctrl Keys in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-y56-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo Y56 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/inside-scoop-on-apples-automotive-endeavour-news-coverage-estimated-pricing-details-launch-schedule-and-intriguing-rumors/"><u>Inside Scoop on Apple's Automotive Endeavour: News Coverage, Estimated Pricing Details, Launch Schedule & Intriguing Rumors</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://extra-information.techidaily.com/loopers-toolkit/"><u>Looper's Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-auditory-cuts-and-segments-convenient-methods-to-divide-your-music-files/"><u>New 2024 Approved Auditory Cuts and Segments Convenient Methods to Divide Your Music Files</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-your-pcs-touchpad-gestures/"><u>Regaining Control Over Your PC's Touchpad Gestures</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/stay-true-to-tech-avoiding-impostor-apps-on-windows-platform/"><u>Stay True to Tech: Avoiding Impostor Apps on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-shortcut-placement-near-win11s-power-button/"><u>Strategizing Shortcut Placement Near Win11's Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-incompatible-application-downloads-on-microsoft-store/"><u>Tackling Incompatible Application Downloads on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-ui-5-steps-toward-mac-os-aesthetics/"><u>Transforming Windows UI: 5 Steps Toward Mac OS Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-second-display-on-w11/"><u>Troubleshooting Missing Second Display on W11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-detailed-settings-app-tour/"><u>Windows 11: A Detailed Settings App Tour</u></a></li>
<li><a href="https://win11.techidaily.com/windows-methods-for-engaging-wordpad/"><u>Windows Methods for Engaging WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/winxpxo11-how-to-prevent-closed-folders-double-clicked/"><u>WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked</u></a></li>
</ul></div>
