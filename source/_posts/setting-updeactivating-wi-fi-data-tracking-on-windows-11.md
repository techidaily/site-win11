---
title: Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11
date: 2024-07-13T10:12:30.786Z
updated: 2024-07-14T10:12:30.786Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11
excerpt: This Article Describes Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11
keywords: Wi-Fi Privacy Control,Disable Data Tracking,Stop Windows Wi-Fi Monitoring,Wi-Fi Tracking Deactivation,Manage Windows Wi-Fi,Inhibit Win 11 Data Logging,Turn Off Wi-Fi Tracking Windows
thumbnail: https://thmb.techidaily.com/d20682484ee39b27689e93ff94b9b7638592055fcb925a693073d87e930189fb.jpg
---

## Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11

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
<li><a href="https://win11.techidaily.com/strategies-for-swiftly-finding-and-fixing-windows-update-problems/"><u>Strategies for Swiftly Finding and Fixing Windows Update Problems</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-your-machine-best-windows-software-to-ditch/"><u>Tidy Up Your Machine: Best Windows Software to Ditch</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-enforced-driver-checks-for-easier-updates/"><u>Skirting Enforced Driver Checks for Easier Updates</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-sony-xperia-10-v-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Sony Xperia 10 V Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-web-safety-including-reliable-domains-in-windows-11/"><u>Tailored Web Safety: Including Reliable Domains in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-snappy-narratives-on-the-social-scene/"><u>In 2024, Snappy Narratives on the Social Scene</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-exploration-of-win11s-voice-control-shortcuts/"><u>A Detailed Exploration of Win11's Voice Control Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/securing-save-configurations-in-your-windows-pubg-game/"><u>Securing Save Configurations in Your Windows PUBG Game</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-ai-influencer/"><u>New What Is AI Influencer?</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-connectivity-issues-with-quick-solutions/"><u>Enhancing Steam Connectivity Issues with Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-intel-wi-fi-6a-driver-failure-in-windows-os/"><u>Solutions for Intel Wi-Fi 6A Driver Failure in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-solutions-locating-and-correcting-windows-errors-via-the-power-of-command-prompt/"><u>Systematic Solutions: Locating & Correcting Windows Errors via the Power of Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-valorant-downloads-on-slow-systems/"><u>Supercharging Valorant Downloads on Slow Systems</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-how-to-be-a-good-podcast-host/"><u>2024 Approved How to Be a Good Podcast Host</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-simple-steps-for-correction-of-character-map-errors/"><u>Unveiling Simple Steps for Correction of Character Map Errors</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrated-workflows-joining-ifttt-and-to-do/"><u>Orchestrated Workflows: Joining IFTTT and To-Do</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-edit-videos-on-mac-vn-video-editor-and-beyond/"><u>New 2024 Approved Edit Videos on Mac VN Video Editor and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-amplifying-virtual-memory-on-microsofts-latest-os/"><u>Stepwise Guide to Amplifying Virtual Memory on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-blurred-taskbars-in-windows-11/"><u>Breeze Through Blurred Taskbars in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-depth-look-at-instagrams-video-time-restrictions-for-2024/"><u>In-Depth Look at Instagram's Video Time Restrictions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastery-directing-app-and-browser-traffic/"><u>Windows Mastery: Directing App and Browser Traffic</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-comfortable-computing-environment-configuring-active-periods-and-managing-updates-in-windows-11/"><u>Crafting a Comfortable Computing Environment: Configuring Active Periods & Managing Updates in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/system-tray-simplified-the-art-of-minimizing-apps-on-windows/"><u>System Tray Simplified: The Art of Minimizing Apps on Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-expert-picks-best-text-animation-and-tracking-software-2023-for-2024/"><u>Updated Expert Picks Best Text Animation and Tracking Software 2023 for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-get-instagram-audio-downloads-in-minutes/"><u>Updated In 2024, Get Instagram Audio Downloads in Minutes</u></a></li>
<li><a href="https://win11.techidaily.com/the-window-whisperers-guide-to-unveiling-off-screen-apps-in-win-1011-6-proven-steps/"><u>The Window Whisperer's Guide to Unveiling Off-Screen Apps in Win 10/11 (6 Proven Steps)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-virtualboxs-0x80004005-error/"><u>Mastering the Art of Correcting VirtualBox's 0X80004005 Error</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-error-code-31-in-windows-systems/"><u>Understanding and Solving Error Code 31 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-disk-space-save-personal-files/"><u>Amplify Windows Disk Space, Save Personal Files</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-the-expiring-windows-license-message/"><u>How To Silence the Expiring Window's License Message</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-troubled-waters-eliminating-error-code-80080300-in-win11-tech/"><u>Navigate Through Troubled Waters: Eliminating Error Code 80080300 in Win11 Tech</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-11-webcam-problem-a00f4289-expedition/"><u>Eradicating Windows 11 Webcam Problem: A00F4289 Expedition</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-user-interaction-ai-integration-into-windows-11/"><u>Redefining User Interaction: AI Integration Into Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-perfecting-your-facebook-video-cover-size-ratio-and-more/"><u>Updated In 2024, Perfecting Your Facebook Video Cover Size, Ratio, and More</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-melodic-mix-audio-meets-images-online/"><u>In 2024, Melodic Mix  Audio Meets Images Online</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/4-cool-things-you-can-do-with-windows-11-god-mode/"><u>4 Cool Things You Can Do With Windows 11 God Mode</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-dare-to-differentiate-using-square-videos-for-social-media-standout/"><u>In 2024, Dare to Differentiate  Using Square Videos for Social Media Standout</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/10-apps-to-make-videos-with-pictures-and-music/"><u>10 Apps to Make Videos with Pictures and Music</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-process-to-remove-wsl-from-windows/"><u>Mastering the Process to Remove WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-11-with-additional-firewall-options-via-context-menu/"><u>Securing Windows 11 with Additional Firewall Options via Context Menu</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/beginnings-of-bilingualism-spanish-for-youngsters/"><u>Beginnings of Bilingualism: Spanish for Youngsters</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-window-resolutions-8-simple-steps/"><u>Fixing Inaccessible Window Resolutions: 8 Simple Steps</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfect-package-presentation-transformative-openings/"><u>[New] Perfect Package Presentation  Transformative Openings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-login-after-windows-errors/"><u>How to Reactivate Login After Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-outlook-notification-popups/"><u>Addressing Failed Outlook Notification Popups</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-web-pages-as-windows-tools/"><u>Seamless Integration: Web Pages as Windows Tools</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-7-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 7 To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-business-best-windows-time-management-and-productivity-software/"><u>Boost Your Business: Best Windows Time Management and Productivity Software</u></a></li>
</ul></div>
