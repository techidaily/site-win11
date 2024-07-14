---
title: Best Approaches for Removing Wifi From Windows 11
date: 2024-07-13T11:22:37.763Z
updated: 2024-07-14T11:22:37.763Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Best Approaches for Removing Wifi From Windows 11
excerpt: This Article Describes Best Approaches for Removing Wifi From Windows 11
keywords: Wi-Fi Disabling Win11,Win11 Remove Wi-Fi,Optimal Wi-Fi Offset Win11,Removing Wifi in Windows 11,Best Wi-Fi Erase Win11,Effective Wi-Fi Delete Win11,Ideal Wi-Fi Toggle Win11
thumbnail: https://thmb.techidaily.com/9cc152d1aca0892df1ca5596ac3ad03cce388893be920721cefd3090f694d72e.png
---

## Best Approaches for Removing Wifi From Windows 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

 Like using the Quick Settings on Windows? Check out [how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

 Once you complete the above steps, the saved profile will be removed from your system.

## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on [different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.


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
<li><a href="https://win11.techidaily.com/tackling-cannot-end-task-on-your-computer/"><u>Tackling 'Cannot End Task' On Your Computer</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-az-video-logger-full-application-scrutiny/"><u>2024 Approved  AZ Video Logger - Full Application Scrutiny</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtube-shorts-tutorial-crafting-compact-engaging-videos/"><u>[Updated] YouTube Shorts Tutorial  Crafting Compact, Engaging Videos</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-accounts-after-fails/"><u>Bypassing Disabled Windows Accounts After Fails</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-best-screen-capturing-tools-reviewed-and-ranked-15-on-win11/"><u>[New] 2024 Approved  Best Screen Capturing Tools Reviewed & Ranked  #15 on Win11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-unveiling-the-power-of-screen-capture-showmores-review-breakdown/"><u>2024 Approved  Unveiling the Power of Screen Capture  ShowMore's Review Breakdown</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-speedy-streams-start-here-snapchat-for-starters/"><u>[Updated] Speedy Streams Start Here  Snapchat for Starters</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-wi-fi-access-via-windows-11-the-hotspot-setup-process/"><u>Streamlining Wi-Fi Access via Windows 11: The Hotspot Setup Process</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-phones-capability-for-windows-recording/"><u>Streamline Phone's Capability for Windows Recording</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-streamline-your-snapchat-chat-and-calls-with-3-key-steps/"><u>[Updated] In 2024, Streamline Your Snapchat Chat and Calls with 3 Key Steps</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-fbm-hiccups-today/"><u>Swiftly Solve Your Windows FBM Hiccups Today</u></a></li>
<li><a href="https://win11.techidaily.com/away-from-clouds-data-at-your-fingertips-onedrive-tutorial/"><u>Away From Clouds, Data at Your Fingertips - OneDrive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions.</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-proficiency-uncovering-the-best-5-online-title-creators/"><u>[Updated] Exploring Proficiency  Uncovering the Best 5 Online Title Creators</u></a></li>
<li><a href="https://win11.techidaily.com/tethering-tech-microsofts-vision-in-windows-11-phones/"><u>Tethering Tech: Microsoft's Vision in Windows 11 Phones</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-power-and-performance-in-windows-systems/"><u>Balancing Power and Performance in Windows Systems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/video-journey-mastery-10-leading-apps-to-up-your-youtube-short-game/"><u>Video Journey Mastery  10 Leading Apps to Up Your Youtube Short Game</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-accurate-game-detection-failure-in-discord-windows-pc/"><u>Solutions for Accurate Game Detection Failure in Discord (Windows PC)</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-get-the-edge-with-a-premier-zero-cost-voice-change-software-for-2024/"><u>[New] Get the Edge with a Premier, Zero-Cost Voice Change Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/why-win10-is-more-than-enough-in-the-current-tech-scene/"><u>Why Win10 Is More Than Enough in the Current Tech Scene</u></a></li>
<li><a href="https://win11.techidaily.com/unrestricted-windows-dialogue-embrace-freedomgpt/"><u>Unrestricted Windows Dialogue: Embrace FreedomGPT</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-secondary-antivirus-without-defenders-hindrance/"><u>Tips for Integrating Secondary Antivirus Without Defender’s Hindrance</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-challenge-write-permissions-for-steam-folders/"><u>Easing the Challenge: Write Permissions for Steam Folders</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-uncover-the-soundscape-of-fine-arts-tooling/"><u>Updated In 2024, Uncover the Soundscape of Fine Arts Tooling</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-platform-power-playout-which-streams-better-obs-or-twitch-studio/"><u>[Updated] In 2024, Platform Power Playout  Which Streams Better - OBS or Twitch Studio?</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-restore-visual-clarity-in-winos/"><u>Best Practices to Restore Visual Clarity in WinOS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unveiling-the-art-of-video-production-for-facebooks-youtube/"><u>In 2024, Unveiling the Art of Video Production for Facebook's YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-access-the-key-to-your-windows-11-folder/"><u>Conquering Access: The Key to Your Windows 11 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-image-editing-efficiently-removing-backdrops/"><u>The Art of Image Editing: Efficiently Removing Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-breakpoint-failed-on-your-windows-system/"><u>Addressing 'Breakpoint Failed' On Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/assisting-users-with-erratic-swipes-on-windows-systems/"><u>Assisting Users with Erratic Swipes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-winrars-summation-oversights-a-6-step-approach/"><u>Correcting WinRAR's Summation Oversights: A 6-Step Approach</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-cut-your-videos-without-a-price-7-free-trimmers/"><u>Updated Cut Your Videos Without a Price 7 Free Trimmers</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-productivity-the-ultimate-toolkit-of-5plus-apps/"><u>Boost Your Windows Productivity: The Ultimate Toolkit of 5+ Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fade-to-darkness-instantaneously/"><u>[New] Fade to Darkness Instantaneously</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-activation-issue-with-error-0x803f700f/"><u>Addressing Windows Activation Issue with Error 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-life-top-11-fixes-for-windows-11-issues/"><u>Simplify Your Life: Top 11 Fixes for Windows 11 Issues</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-lets-see-how-you-can-run-windows-and-mac-os-video-editing-apps-such-as-filmora-final-cut-pro-imovie-sony-vegas-pro-or-any-other-powerful-video-editi/"><u>Updated Lets See How You Can Run Windows and Mac OS Video Editing Apps, Such as Filmora, Final Cut Pro, iMovie, Sony Vegas Pro or Any Other Powerful Video Editing Software From Your Chromebook for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-future-visions-10-sci-fi-metaverse-movies-explore-worlds-anew/"><u>[New] Future Visions  10 Sci-Fi Metaverse Movies Explore Worlds Anew</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-extended-monitor-lag-in-windows/"><u>Strategies to Combat Extended Monitor Lag in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-xiaomi-redmi-note-13-proplus-5g-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Xiaomi Redmi Note 13 Pro+ 5G.</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/creating-captivating-content-for-instagram/"><u>Creating Captivating Content for Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-integrating-your-photos-smart-transfers-from-iphone-to-snapchat/"><u>In 2024, Integrating Your Photos  Smart Transfers From iPhone to Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/digital-diaries-7-excelent-notetakers-for-pcs-and-slate/"><u>Digital Diaries: 7 Excelent Notetakers for PCs & Slate</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
<li><a href="https://win11.techidaily.com/sly-settings-shuffle-disguising-power-buttons-on-desktop/"><u>Sly Settings Shuffle: Disguising Power Buttons on Desktop</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hue-harmony-the-definitive-guide-to-video-coloring/"><u>In 2024, Hue Harmony  The Definitive Guide to Video Coloring</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocks-lost-luster-await-wise-wisdom-before-shift/"><u>BitLocks Lost Luster: Await Wise Wisdom Before Shift</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-blunders-proper-techniques-for-file-explorer-use/"><u>Avoiding Blunders: Proper Techniques for File Explorer Use</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-charting-the-path-to-previous-imagery-a-facebook-centric-guide/"><u>[New] 2024 Approved  Charting the Path to Previous Imagery  A Facebook-Centric Guide</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-pristine-windows-display-perfection/"><u>Crafting Pristine Windows Display Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-terminal-in-quake-mode-on-windows/"><u>Utilizing Terminal in Quake Mode on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-inner-gamer-strategic-play-and-success-at-zero-cost/"><u>Unleash Your Inner Gamer: Strategic Play & Success at Zero-Cost</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-10-best-sony-lut-for-different-purposes/"><u>In 2024, 10 Best Sony LUT for Different Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/digital-detox-for-pcs-a-collection-of-13-revival-methods/"><u>Digital Detox for PCs: A Collection of 13 Revival Methods</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-poco-m6-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Poco M6 5G Without PUK Codes</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-a-compreenas-guide-to-auto-and-advanced-camera-exposure-methods/"><u>In 2024, A Compreenas Guide to Auto and Advanced Camera Exposure Methods</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-heart-of-windows-11-registry-explained/"><u>Delving Into the Heart of Windows 11: Registry Explained</u></a></li>
</ul></div>
