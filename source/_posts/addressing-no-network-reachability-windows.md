---
title: Addressing No Network Reachability (Windows)
date: 2024-07-13T11:20:05.418Z
updated: 2024-07-14T11:20:05.418Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing No Network Reachability (Windows)
excerpt: This Article Describes Addressing No Network Reachability (Windows)
keywords: Windows Net Issues,Win No Internet Access,Windows Network Errors,Fix No PC Connection,Resolve Windows Disconnect,Windows Offline Troubleshoot,Connect Windows PC Online
thumbnail: https://thmb.techidaily.com/c8cc0b50d6a862024b28911d2e2409173d05c3a9fcb60009ede2fce73e839885.jpg
---

## Addressing No Network Reachability (Windows)

 Microsoft allows devices that are connected to the same network to access each other's data and share files remotely. When you need to use two devices simultaneously, this process of data and resource sharing can be quite useful. However, there are times when users encounter errors, which can make the process quite a hassle and unpleasant.

 One such common issue is the "network path name was not found" error, which occurs when users attempt to connect to a remote device. If you are facing a similar problem, we have discussed six troubleshooting methods below that will help you fix the error in no time.

## 1\. Double-Check the Path Names

 If you encounter the "network path name was not found" error, then the first thing that you should do is double-check the path name you entered. A small mistake within the path name will prevent the system from finding the path to the connected network.

 While you are at it, we also recommend checking if the device you want to share files with has the sharing feature enabled. If not, enable it and then try performing the action that was previously causing the error.

 Here is how you can make the targeted drive on the remote computer shareable:

1. Right-click on the targeted drive and choose **Properties** from the context menu.  
![Drive properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/drive-properties.jpg)
2. In the following dialog, head over to the **Sharing tab** and check the status of Network Path.
3. If it says Not Shared, then click on the **Advanced Sharing** button.  
![Advanced sharing button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/drive-properties-advanced-sharing.jpg)
4. Checkmark the box associated with **Share this folder** and note the Share name of the drive.  
![Type folder name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/drive-share-this-folder.jpg)
5. Once done, click on **Apply** \> **OK** to save the changes.

 You can now check if the drive is accessible after following the steps above.

## 2\. Temporarily Disable Your Antivirus

 Another common culprit that often prevents users from connecting to networks, sharing files, and downloading applications from third-party sources is an overly protective antivirus.

 Antivirus’s job is to identify malicious activities and block them, but there are times when these security programs start labeling legitimate processes as threats as well, blocking them completely.

 If you are using a third-party security program on your operating system, we recommend that you disable it temporarily and then try connecting to the remote computer and sharing files. If the antivirus was causing the problem, disabling it should fix the issue for you. If this happens, you can consider switching to a better security program to avoid such issues in the future. See our guide on [the best antivirus apps for Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) to make an informed decision.

 You can also try [disabling Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) if you are using it and see if that helps. However, once you are done sharing the files, make sure you enable the antivirus back immediately since keeping it disabled for a long period can expose your PC to threats.

## 3\. Try to Connect Using an IP Address

 You can also connect to the remote computer using the IP address. In this method, we will be using Command Prompt to make this work.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type "cmd" in the text field of Run and hit **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. In the Command Prompt window, type the command mentioned below and hit **Enter** to execute it:  
`ipconfig /all​​​`  
![ipconfig all command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ipconfig-all.jpg)
4. Scroll down and bit and note down the address for IPv4 Address.  
![ipv4 address in cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ipconfig-all-ipv4-address.jpg)
5. Now, open a Run dialog again and paste the IPv4 Address you noted in the text field here.  
![ipv4 address in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/cmd-ipv4-address.jpg)
6. Click **Enter** and see if you can connect to the remote computer successfully.

## 4\. Restart the TCP/IP NetBIOS Helper Service

 To connect to a remote device and share files with it, certain services on Windows should be functioning properly. One of the most important services, in this case, is the TCP/IP NetBIOS Helper service. As such, we recommend that you restart it to ensure that it is working.

 Here is what you need to do:

1. Open Run by pressing **Win** \+ **R**.
2. Type services.msc in Run and hit **Enter**.
3. In the Services window, look for TCP/IP NetBIOS Helper and right-click on it.
4. Choose **Properties** from the context menu.  
![Properties of TCP/IP helper service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/services-tcp-ip-netbios-helper-properties.jpg)
5. In the following dialog, click on the **Stop** button.  
![Stop button in Properties dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/services-tcp-ip-netbios-helper-stop.jpg)
6. Wait for a few seconds and then click **Start**.
7. Now, expand the dropdown for Startup type and choose **Automatic**.  
![Startup type of service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/services-tcp-ip-netbios-helper-automatic.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Once done, check if that fixes the issue for you.

## 5\. Enable SMB 1.0

 SMB is a network protocol that allows users access to shared files and printers on Windows. This is disabled by default in Windows, but enabling it can help you connect to a remote device and share files across the network.

 In this method, we will enable it to share the files. However, we strongly suggest that you disable it after usage since it is known to have some security vulnerabilities that can mess up your system.

 Here is what you need to do:

1. Type Control Panel in Windows search and click **Open**.
2. In the following window, head over to **Programs** \> **Programs and Features**.  
![Programs option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/control-panel-programs.jpg)
3. Choose **Turn Windows features on or off** from the left pane.  
![Turn Windows feature on or off option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-windows-features-on-or-off.jpg)
4. Now, look for "SMB 1.0/CIFS File Sharing Support" and checkmark the box associated with it.  
![SMB 1.0 option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/smb-cifs-file-sharing-support.jpg)
5. Click **OK** to save the changes and check if the error is now fixed.

## 6\. Modify Network Security Settings

 There can also be a problem with the network security settings of your computer, which might block access to shared resources, resulting in the error. Here is how you can ensure that you have the correct network settings to effectively communicate with other devices or resources on the network.

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Network Security: LAN Manager authentication level
4. Expand the dropdown and choose **Send LM & NTLM-use NTLMv2 session security if negotiated**.  
![Modify network security settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/local-security-policy-settings.jpg)
5. Click **Apply** \> **OK** to save the changes.

## 7\. Reset TCP/IP

 Finally, if the methods above have not worked for you, then you can consider [resetting TCP/IP](https://www.makeuseof.com/windows-connection-failed-error-651-fix/#:~:text=next%20method%20below.-,3.%20Reset%20TCP/IP,-You%20might%20also), which will revert all the IP protocols and DNS entries to their default state.

 This fix is known to fix almost all the network-related issues that pop up in Windows now and then, and will hopefully fix the error at hand for you as well.

## The Windows Network Path Error, Resolved

 Connecting to another device over the network and sharing files should be a seamless process. Hopefully, the troubleshooting methods mentioned above will help you get the network functionality up and running in no time. However, if the error persists, you can consider using another file-sharing service like Google Drive till Microsoft launches an official fix for this issue.

 One such common issue is the "network path name was not found" error, which occurs when users attempt to connect to a remote device. If you are facing a similar problem, we have discussed six troubleshooting methods below that will help you fix the error in no time.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/shaping-the-user-experience-with-wins-console/"><u>Shaping the User Experience with Win’s Console</u></a></li>
<li><a href="https://win11.techidaily.com/make-windows-resemble-macos-with-these-5-simple-changes/"><u>Make Windows Resemble MacOS with These 5 Simple Changes</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-flight-comrade-copilot-in-ws11/"><u>Restore Your Flight Comrade (Copilot) in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/rebuilding-with-purpose-windows-11-from-scratch/"><u>Rebuilding with Purpose: Windows 11 From Scratch</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-samsung-galaxy-z-fold-5-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Samsung Galaxy Z Fold 5 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-non-functional-xbox-controller/"><u>Reviving Your Non-Functional Xbox Controller</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-windows-safescreensaver-alteration/"><u>Preventive Measures for Windows SafeScreensaver Alteration</u></a></li>
<li><a href="https://win11.techidaily.com/from-emulator-to-operating-system-windows-for-steam-deck/"><u>From Emulator to Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-charting-a-course-youtubes-best-brands/"><u>2024 Approved  Charting a Course  YouTube's Best Brands</u></a></li>
<li><a href="https://win11.techidaily.com/pro-guide-how-to-locate-and-setup-shortcuts-near-win11s-power-icon/"><u>Pro Guide: How to Locate & Setup Shortcuts Near Win11's Power Icon</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-in-windows-11-dissecting-update-wxxs-additions/"><u>New Horizons in Windows 11: Dissecting Update W.x.x's Additions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-yellow-tint-on-a-windows-laptop-screen/"><u>How to Fix a Yellow Tint on a Windows Laptop Screen</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-detect-camera-in-win11/"><u>Overcoming Unable to Detect Camera in Win11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-create-hilarious-memes-with-these-10-awesome-apps-2023-edition/"><u>New In 2024, Create Hilarious Memes with These 10 Awesome Apps (2023 Edition)</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-audio-free-video-guide-five-steps-to-remove-unwanted-sounds-online/"><u>New 2024 Approved Audio-Free Video Guide Five Steps to Remove Unwanted Sounds Online</u></a></li>
<li><a href="https://win11.techidaily.com/harness-windows-11s-netstat-power-for-traffic-observation/"><u>Harness Windows 11'S Netstat Power for Traffic Observation</u></a></li>
<li><a href="https://win11.techidaily.com/measuring-electrical-use-for-windows-pcs-effectively/"><u>Measuring Electrical Use for Windows PCs Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reverse-error-code-0x80780119-in-windows/"><u>Guide to Reverse Error Code 0X80780119 in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Come up With the Best Pokemon Team On Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-comprehensible-list-best-games-music-found-online/"><u>In 2024, Comprehensible List  Best Games’ Music Found Online</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-correct-office-365-problem-code-30015-26/"><u>Methods to Correct Office 365 Problem Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-group-policy-management-in-windows-108/"><u>Simplifying Group Policy Management in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-shift-away-from-windows-xp-7-and-81-support/"><u>Navigating the Shift Away From Windows XP, 7 & 8.1 Support</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-0x80072efd-on-windows-devices/"><u>Remedying Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-empty-login-screen-dilemma-in-win1011/"><u>Overcoming the Empty Login Screen Dilemma in WIN10/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-realme-11x-5g-device-sim-by-drfone-android/"><u>Easily Unlock Your Realme 11X 5G Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-app-changes-in-the-latest-windows-11-update/"><u>Navigating App Changes in the Latest Windows 11 Update</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/imageslice-editor/"><u>ImageSlice Editor</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-leading-360-degree-pro-cams-2023-edition-review/"><u>2024 Approved  Leading 360-Degree Pro Cams  2023 Edition Review</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-file-explorer-running-with-helpful-windows-11-tricks/"><u>Keep Your File Explorer Running with Helpful Windows 11 Tricks</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/top-picks-windows-movie-maker-replacements-youll-love/"><u>Top Picks Windows Movie Maker Replacements Youll Love</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-samsung-galaxy-a23-5g-by-drfone-android/"><u>How to Bypass FRP from Samsung Galaxy A23 5G?</u></a></li>
<li><a href="https://win11.techidaily.com/introduction-to-windows-hello-for-fingerprint-recognition/"><u>Introduction to Windows Hello for Fingerprint Recognition</u></a></li>
</ul></div>
