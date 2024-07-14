---
title: Overcoming 'Unable to Display' Errors in Microsoft Store
date: 2024-07-13T09:58:39.602Z
updated: 2024-07-14T09:58:39.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming 'Unable to Display' Errors in Microsoft Store
excerpt: This Article Describes Overcoming 'Unable to Display' Errors in Microsoft Store
keywords: Fixing MSStore Display Issue,Troubleshooting Store Error,Resolving Unavailable Product Error,Clearing Microsoft Store Glitches,Overcoming Store Display Failures,Addressing Unable To Load Items,Removing Store Inaccessibility Errors
thumbnail: https://thmb.techidaily.com/762eb58aca659c7ab398016eac456ae67d371642f3000355e426b137b3698ca6.jpg
---

## Overcoming 'Unable to Display' Errors in Microsoft Store

 The Microsoft Store is a great place to get apps on Windows 11\. But despite its huge usability, you'll find it running into issues every now and then. One such issue is the "Page could not be loaded" error message that appears upon searching for apps on the Microsoft Store.

 As such, if you also see this error message on the Microsoft Store, then this is the place where you need to be. Here, we'll share seven different ways to fix the "Page could not be loaded" error message.

## What Is the Microsoft Store "Page Could Not Be Loaded" Error?

 Usually, the "Page could not be loaded" error message appears when the app you are searching for is unavailable on the Microsoft Store. But sometimes, it appears even on searching for available apps like Minecraft. The error message comes along with the 0x80131505 code.

 Some of the prime culprits behind this error are corruption in the Microsoft Store, misconfigured date and time, and any active proxy server. Fortunately, you can make certain changes to troubleshoot the problem.

## 1\. Sign Out and Back Into the Microsoft Store

 Most Microsoft Store errors often appear due to a temporary account glitch and can be resolved by signing in again to the Microsoft Store. So, sign out and back into the Microsoft Store to check if it fixes the issue. Here's how to do that:

1. Launch the Microsoft Store app and click your profile icon at the top bar.
2. Choose the**Sign out** option.  
![Sign Out option in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-out-option.jpg)
3. Next, restart the Microsoft Store, click the profile icon and choose**Sign in.**  
![Sign In Option of the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-in-option.jpg)
4. Select your account and then click the**Continue** option.
5. Enter your PIN to confirm your identity.

## 2\. Change the Microsoft Store Region to the Country You're In

 If you're using the Microsoft Store in a different country, make sure to change the region; otherwise, you will face issues accessing it. You can do this by following the below instructions:

1. Press the**Win + S** hotkeys to open the**Search menu.**
2. In the search bar, type**Region settings** and choose**Open** from the right pane.  
![Region Settings option in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/region-settings-1.jpg)
3. Click the drop-down icon next to**Country and region** and choose your country name from the list.  
![Choose Region in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choose-region.jpg)

 That's it. You might need to restart your computer (see [how to restart a Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) for the changes to take effect.

## 3\. Use the Built-In Windows Troubleshooter

 Microsoft is aware of issues users face regularly; that's why they offer [various troubleshooters](https://www.makeuseof.com/windows-11-troubleshooters/) that can come in handy in fixing them. To eliminate any kind of Microsoft Store issue, you can use the Windows Store Apps troubleshooter.

 Here's how to access and use the Windows Store Apps troubleshooter:

1. Press the**Win + I** hotkeys to open the**Settings app.**
2. Select**System** from the left sidebar and then**Troubleshoot** option in the right pane.
3. Choose**Other troubleshooters.**
4. Under the**Other** section, click the**Run** button next to the**Windows Store Apps** troubleshooter.  
![The Run button for Windows Store Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-run-button.jpg)

 Now, the troubleshooter window will appear and start detecting problems. If it finds any, it will automatically fix it without much user input.

## 4\. Check Your System Date and Time

 It doesn't matter how outlandish it may sound; the "Page could not be loaded" error message is likely to appear if your computer is showing an incorrect date and time. The reason is that Microsoft Store matches the official time with the time shown on your computer.

 If there's a difference between them, then Microsoft Store throws different issues, including one at hand. So, you must correctly configure your computer's date and time to eliminate the error. Here's how:

1. In the Settings app, choose**Time & language** from the left sidebar.
2. Click**Date** **& time** .
3. Enable the toggle next to the**Set time automatically** and**Set time zone automatically** options.  
![Change Date and Time in Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-date-and-time.jpg)

 Now open the Microsoft Store and check if you are still facing the problem. If yes, then try the next solution on the list.

## 5\. Reset the SoftwareDistribution Folder

 Corruption in the SoftwareDistribution folder can also be a reason behind the error message. You'll have to reset this folder to remove the corruption.

Here's how to do that:

 Before getting into the steps, ensure your computer is disconnected from the internet. This is because if you try to run the below command with an active internet connection, you might see the "Some files are in use" or "Modification cannot be made" prompt.

1. Open the Windows Search, type**Command Prompt** in the search bar, and choose**Run as administrator** from the right pane.
2. If**Yes** to the UAC that crops up.
3. In the elevated Command Prompt window, type and press Enter after each of the following commands.  
`Net Stop bits  
Net Stop wuauserv  
Net Stop appidsvc  
Net Stop cryptsvc  
Ren %systemroot%\SoftwareDistribution SoftwareDistribution.bak  
Ren %systemroot%\system32\catroot2 catroot2.bak  
Net Start bits  
Net Start wuauserv  
Net Start appidsvc  
Net Start cryptsvc`

## 6\. Turn Off Any Active Proxy Server Settings

 Using a [proxy server](https://www.makeuseof.com/tag/what-is-a-proxy-server/) can come in handy when you want to access websites and apps blocked in your region. But on the negative side, it can cause issues in apps like the Microsoft Store, Xbox, and YouTube.

 So, disable any proxy server and check if it resolves the problem. Follow these steps to do that:

1. In the Settings app, choose**Network & internet** from the left sidebar.
2. Choose**Proxy.**
3. Click the**Set up** button.
4. Disable the toggle under the**Use a proxy server** option.  
![Use a Proxy Server option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/use-a-proxy-server-option.jpg)

## 7\. Repair and Reset the Microsoft Store

 Windows offer Repair and Reset troubleshooting options for most of the built-in applications. The Repair option repairs the broken and corrupt files of the app. In contrast, the Reset option deletes all the app's data.

To use these troubleshooting options, follow the below instructions:

1. Open**Apps & Features** in the Settings app. Our guide on [launching Apps and Features in Windows 11](https://www.makeuseof.com/9-ways-to-open-the-apps-features-tool-in-windows-11/) tells you how to access this option.
2. Search for and click on the**three dots** next to the Microsoft Store.
3. Choose**Advanced options.**
4. Click the**Repair.**  
![MS Store Repair Option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ms-store-repair-option.jpg)

 Windows will now start repairing the Microsoft Store. After the process is complete, you'll see a checkmark next to the repair option.

 Now, launch the Microsoft store and check if the problem continues. If yes, then click**Reset** present under the Repair option.

## Fixing the "Page Could Not Be Loaded" Error in the Windows Store

 It's very common to face issues in the Microsoft Store. Fortunately, most of these issues can easily be resolved by applying some simple fixes. If you see the "Page could not be loaded" error message, you can fix it using the above solutions.

 However, if none of the solutions was helpful, consider resetting your computer to factory defaults.


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
<li><a href="https://audio-shaping.techidaily.com/updated-unlocking-real-time-voice-manipulation-top-6-application-choices/"><u>Updated Unlocking Real-Time Voice Manipulation Top 6 Application Choices</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11-drive-map-techniques/"><u>Unlocking Win11 Drive Map Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missed-display-after-windows-starts/"><u>Overcoming Missed Display After Windows Starts</u></a></li>
<li><a href="https://win11.techidaily.com/passwords-and-files-a-comprehensive-guide-to-windows-1011/"><u>Passwords and Files: A Comprehensive Guide to Windows 10/11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitchconverter-tweets-to-streams-for-2024/"><u>TwitchConverter  Tweets to Streams for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-apeaks-leap-forward-in-screen-capture-review-and-results/"><u>[New] In 2024, Apeak’s Leap Forward in Screen Capture – Review and Results</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-vms-with-virtualbox-70-now-for-windows-11-users/"><u>Boosting Your VMs with VirtualBox 7.0, Now for Windows 11 Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/perfecting-instagram-the-art-of-caption-placement/"><u>Perfecting Instagram  The Art of Caption Placement</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xbox-live-games-access-failures-on-windows-os/"><u>Troubleshooting: Xbox Live Games Access Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-update-failure-code-0x80246007/"><u>Overcoming Windows 11'S Update Failure: Code 0X80246007</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/speed-up-your-story-two-easy-ways-to-create-stunning-time-lapse-videos-for-2024/"><u>Speed Up Your Story Two Easy Ways to Create Stunning Time Lapse Videos for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-innovative-approaches-to-gameplay-and-webcam-captures/"><u>[New] In 2024, Innovative Approaches to Gameplay and Webcam Captures</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-profit-from-youtube-shorts-key-requirements-and-possible-returns-for-2024/"><u>How to Profit From YouTube Shorts  Key Requirements & Possible Returns for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reestablish-clear-view-fixing-black-screens-on-win11/"><u>Reestablish Clear View: Fixing Black Screens on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-how-to-modify-the-saving-place-for-onedrive-on-pc/"><u>Unlocking How to Modify the Saving Place for OneDrive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-systems-replacing-aged-windows-drivers-efficiently/"><u>Streamlining Systems: Replacing Aged Windows Drivers Efficiently</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-above-and-beyond-uavs-for-gopro-recording-excellence/"><u>In 2024, Above and Beyond UAVs for GoPro Recording Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-from-vpn-client-errors/"><u>Addressing Disconnected From VPN Client Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-organized-print-setup-in-windows-systems/"><u>The Key to Organized Print Setup in Windows Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-realme-11-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Realme 11 5G without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-insights-into-repairing-windows-error-0x80040610/"><u>Unlocking Insights Into Repairing Windows' Error 0X80040610</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-maximize-yandex-translate-in-video-translation-and-beyond/"><u>Updated 2024 Approved Maximize Yandex Translate in Video Translation and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-cpu-woes-strategies-from-windows-rm-window/"><u>Unraveling CPU Woes: Strategies From Windows' RM Window</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-read-failure-errors-in-windows-1011/"><u>Overcoming Read Failure Errors in Windows 10/11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-essential-8-strategies-for-digital-sound-recording/"><u>[New] Essential 8 Strategies for Digital Sound Recording</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wizardry-entering-control-panel-quickly/"><u>Windows Wizardry: Entering Control Panel Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-file-properties-and-date-adjustments/"><u>Navigating Windows File Properties and Date Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-display-experience-an-in-depth-look-at-windows-11s-hdr/"><u>Transforming Display Experience: An In-Depth Look at Windows 11'S HDR</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-infinite-gaming-space-10-ssds-hdds-for-ps5/"><u>[Updated] 2024 Approved  Infinite Gaming Space  #10 SSDs, HDDs for PS5</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-hello-authentication-compatibility-issue/"><u>Remedying Windows Hello Authentication Compatibility Issue</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-routines-installing-app-shortcuts-in-desktop-menu/"><u>Convenient Routines: Installing App Shortcuts in Desktop Menu</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-powershell-experience-execution-policies-demystified/"><u>Optimize Your PowerShell Experience: Execution Policies Demystified</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-infinix-hot-30i-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from Infinix Hot 30i</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-win11-screen-scaling-preference/"><u>Personalizing Your Win11 Screen Scaling Preference</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-11-search-11-tricks-for-a-functional-bar/"><u>Boost Windows 11 Search: 11 Tricks for a Functional Bar</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-metadata-management-unveiling-the-best-7-affordable-online-tags-extractors/"><u>[New] In 2024, Elevate Your Metadata Management  Unveiling the Best 7 Affordable Online Tags Extractors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-bend-and-shape-your-text-with-3d-effects-in-illustrator/"><u>[New] Bend and Shape Your Text with 3D Effects in Illustrator</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-create-and-change-video-cover-on-facebook/"><u>[Updated] How to Create and Change Video Cover on Facebook</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-artisans-guide-to-using-garageband-for-recording-and-editing-audio-projects-for-2024/"><u>New The Artisans Guide to Using GarageBand for Recording and Editing Audio Projects for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-making-stagnant-batch-files-work-again/"><u>Winning Strategies: Making Stagnant Batch Files Work Again</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-recovering-windows-11s-aid-features/"><u>Steps for Recovering Windows 11'S Aid Features</u></a></li>
<li><a href="https://win11.techidaily.com/searching-for-a-slender-browser-footprint-on-your-desktop/"><u>Searching For a Slender Browser Footprint on Your Desktop</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Honor 90 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-webcam-capture-basics-for-hp-and-chromebook-owners-for-2024/"><u>[New] Webcam Capture Basics for HP and Chromebook Owners for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-preventing-random-keyboard-hotkeys-at-work/"><u>Tips for Preventing Random Keyboard Hotkeys at Work</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-comprehensive-guide-for-high-quality-presentation-capture/"><u>[New] Comprehensive Guide for High-Quality Presentation Capture</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-s18-pro-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo S18 Pro Phones</u></a></li>
</ul></div>
