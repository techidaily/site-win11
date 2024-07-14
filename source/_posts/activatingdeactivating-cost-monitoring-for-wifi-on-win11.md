---
title: Activating/Deactivating Cost Monitoring for Wifi on Win11
date: 2024-07-13T11:19:23.782Z
updated: 2024-07-14T11:19:23.782Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating/Deactivating Cost Monitoring for Wifi on Win11
excerpt: This Article Describes Activating/Deactivating Cost Monitoring for Wifi on Win11
keywords: WiFi Cost Control Win11,Activate Deactivate Wifi Tracking,Windows Wifi Expense Management,Manage Wifi Monitoring in Win11,Win11 Wifi Budgeting Features,Adjust Win11 Wifi Costs,Enable/Disable WiFi Monitoring Win11
thumbnail: https://thmb.techidaily.com/33bb4081d4eeefa2b002761f140e6d8a1ab23c4b8fc2690daa04e9c88bdd81bd.jpg
---

## Activating/Deactivating Cost Monitoring for Wifi on Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://extra-lessons.techidaily.com/updated-a-comprehensive-manual-on-motion-detection-systems/"><u>[Updated] A Comprehensive Manual on Motion Detection Systems</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-7-best-free-online-youtube-tag-extractors-for-2024/"><u>[New] 7 Best Free Online YouTube Tag Extractors for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/ultimate-collection-free-tiktok-edits-for-mac-users/"><u>Ultimate Collection  Free TikTok Edits for Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-pushing-boundaries-with-vr-choosing-your-ultimate-game-platform/"><u>[New] Pushing Boundaries with VR  Choosing Your Ultimate Game Platform</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-techniques-to-improve-visibility-during-youtube-playback/"><u>In 2024, Techniques to Improve Visibility During YouTube Playback</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/quelling-the-0x800736cc-dilemran-in-windows-update/"><u>Quelling the 0X800736CC Dilemran in Windows Update</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-honor-x9b-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Honor X9b | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-in-depth-look-at-lg-27uhd68-4k-sync-technology/"><u>[Updated] In-Depth Look at LG 27UHD68, 4K Sync Technology</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/locate-vanished-settings-a-guide-to-finding-them-on-win11/"><u>Locate Vanished Settings: A Guide to Finding Them on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-comprehensive-report-dji-inspire-1-reviewed/"><u>[New] Comprehensive Report  DJI Inspire 1 Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-charmap-incompatibility-challenges/"><u>Overcoming Windows CharMap Incompatibility Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-individual-gpo-settings-for-windows-users-1111-edition/"><u>Implementing Individual GPO Settings for Windows Users 11/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-audiovisual-symphony-top-tunes-to-accompany-every-style-of-video-content/"><u>Updated In 2024, Audiovisual Symphony Top Tunes to Accompany Every Style of Video Content</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-key-to-unlocking-the-best-video-production-talents/"><u>In 2024, The Key to Unlocking the Best Video Production Talents</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-taskbar-datetime-visibility/"><u>Adjusting Windows 11 Taskbar Date/Time Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-enabling-earnings-a-step-by-step-approach-for-mobile-youtubers/"><u>[New] 2024 Approved  Enabling Earnings  A Step-by-Step Approach for Mobile YouTubers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-unveiling-wintv-magic-compre-written-guide-to-capturing-live-on-windows-pc/"><u>[Updated] In 2024, Unveiling WinTV Magic  Compre Written Guide to Capturing Live on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-instantaneous-folder-upload-failures-in-the-windows-onedrive-environment/"><u>Quick Fixes for Instantaneous Folder Upload Failures in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/selecting-the-best-downloader-choco-vs-windows-package-tool/"><u>Selecting the Best Downloader: Choco Vs. Windows Package Tool</u></a></li>
</ul></div>
