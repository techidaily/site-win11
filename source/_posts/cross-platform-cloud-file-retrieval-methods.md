---
title: Cross-Platform Cloud File Retrieval Methods
date: 2024-07-13T11:05:09.375Z
updated: 2024-07-14T11:05:09.375Z
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
6. Finally, click on your account name, and in the **Permissions for <account name>** section, check the **Full Control** box and hit **Apply**.  
![Adding permissions to the user account and confimring changes by pressing on Apply](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-permissions-to-the-user-account-and-confimring-changes-by-pressing-on-apply.jpg)

 That's all the steps to share your drive on the local network. However, if you run into any trouble, it's recommended you check out the [dedicated guide on enabling Windows Network Share](https://www.makeuseof.com/how-network-file-share-windows-10/).

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

![Typing in the IP of the Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-the-ip-of-the-windows-pc.jpeg)

![Typing in user account credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-user-account-credentials.jpeg)

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpeg)

![The shared drive being listed on the Browse Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-shared-drive-being-listed-on-the-browse-menu.jpeg)

Close

 Now you should be able to view the files on the shared drive. You can now download, upload or modify the local files on your Windows PC with ease and without having to download any third-party application.

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
<li><a href="https://win11.techidaily.com/reclaiming-missing-window-panes-with-win11-6-tips/"><u>Reclaiming Missing Window Panes with Win11 (6 Tips)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-sleep-aid-asmr-techniques-unveiled/"><u>[Updated] Sleep Aid  ASMR Techniques Unveiled</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-utilizing-fb-features-for-broadcasting-historical-video-footage-for-2024/"><u>[New] Utilizing FB Features for Broadcasting Historical Video Footage for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-htc-u23-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from HTC U23 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-file-viewer-rights-in-windows-1011/"><u>How to Regain File Viewer Rights in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-compatibility-of-brightness-controls-via-fn-key-win-11/"><u>Restoring Compatibility of Brightness Controls via Fn Key Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-windows-webcam-transition-techniques/"><u>Seamless Android-Windows Webcam Transition Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-reviving-copy-paste-feature-across-browsers/"><u>Quick Guide: Reviving Copy-Paste Feature Across Browsers</u></a></li>
<li><a href="https://extra-support.techidaily.com/low-cost-gopro-cameras-where-to-find-them-for-2024/"><u>Low-Cost GoPro Cameras  Where to Find Them for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-lsa-protection-error-on-windows/"><u>How to Fix the LSA Protection Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-prime-audiosubtitle-malfunctions-on-windows-11-systems/"><u>Resolve Prime Audio/Subtitle Malfunctions on Windows 11 Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On OnePlus 12? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-revolutionize-your-social-media-strategy-use-free-video-creation-kit/"><u>[New] In 2024, Revolutionize Your Social Media Strategy – Use Free Video Creation Kit</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-services-console-a-list-of-7-restoration-techniques/"><u>Reviving a Dormant Services Console: A List of 7 Restoration Techniques</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-clones-playbook-secrets-to-mirror-success-on-the-tiktok-sphere/"><u>2024 Approved  The Clone's Playbook  Secrets to Mirror Success on the TikTok Sphere</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-elevate-your-presence-the-best-5-practices-for-max-viewers/"><u>[New] Elevate Your Presence  The Best 5 Practices for Max Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-microsofts-phone-link-on-mobile-devices/"><u>How to Utilize Microsoft's Phone Link on Mobile Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-essential-tips-for-youtube-audio-optimization/"><u>[Updated] In 2024, Essential Tips for YouTube Audio Optimization</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-essential-tips-for-mov-saving-on-windows-10-for-2024/"><u>[Updated] Essential Tips for MOV Saving on Windows 10 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-windows-update-failure-code-xc004f050/"><u>Reverse Windows Update Failure Code XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-windows-n-editions-for-business-purposes/"><u>Investigating Windows N Editions: For Business Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-path-alteration-guide-for-windows-11-users/"><u>OneDrive Path Alteration Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-google-nearby-to-link-devices-easily/"><u>Leveraging Google Nearby to Link Devices Easily</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-save-locations-on-windows-devices/"><u>How to Resolve Save Locations on Windows Devices</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-streamlined-processes-how-to-make-and-modify-multi-snap-chats-for-2024/"><u>[Updated] Streamlined Processes  How To Make & Modify Multi-Snap Chats for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-top-tweets-review-the-full-year-in-videos-for-2024/"><u>[New] Top Tweets Review  The Full Year in Videos for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unveiling-the-power-of-a-sturdy-tripod-in-video-content-production/"><u>[Updated] Unveiling the Power of a Sturdy Tripod in Video Content Production</u></a></li>
<li><a href="https://win11.techidaily.com/roblox-error-403-resolving-access-denied-in-win/"><u>Roblox Error 403: Resolving Access Denied in Win</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unravel-winerror-incorrect-file-backups-in-windows/"><u>How to Unravel WinError: Incorrect File Backups in Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/5-excellent-gaming-keyboards-within-a-100-budget-for-2024/"><u>5 Excellent Gaming Keyboards Within a $100 Budget for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-unsupported-devices-warning/"><u>Quick Guide: Fixing Unsupported Devices Warning</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-fbx-guide-to-flawless-gameplay-archives/"><u>[Updated] FBX Guide to Flawless Gameplay Archives</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-display-technology-an-in-depth-exploration-of-windows-11s-hdr/"><u>Reimagining Display Technology: An In-Depth Exploration of Windows 11'S HDR</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-integrate-youtube-content-for-dynamic-google-slides-for-2024/"><u>[Updated] Integrate YouTube Content for Dynamic Google Slides for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-1110s-d3d11-gpu-woes-to-fixable-errors/"><u>Simplifying Windows 11/10'S D3D11 GPU Woes to Fixable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-legacy-boot-configurations/"><u>Reinstating Legacy Boot Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-for-disabling-onedrive-indicator-in-windows-11/"><u>Methodology for Disabling OneDrive Indicator in Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-the-best-free-video-meeting-software-roundup-for-professional-and-educational-purposes/"><u>[Updated] In 2024, The Best Free Video Meeting Software Roundup for Professional and Educational Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-devices-in-sleep-mode-of-win11-pc/"><u>Resurrecting Devices in Sleep Mode of Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-windows-audioscape-via-driver-update-steps/"><u>Revamping Windows Audioscape via Driver Update Steps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-exception-handling-error-in-windows-devices/"><u>How to Overcome Exception Handling Error in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-greyed-out-pin-deletion-in-windows-11-interface/"><u>Resetting Greyed-Out Pin Deletion in Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-to-connect-to-a-network/"><u>Navigating Windows to Connect to a Network</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-on-mac-via-parallels/"><u>Mastering Windows 11 on Mac via Parallels</u></a></li>
</ul></div>
