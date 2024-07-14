---
title: "Facilitating Regular Updates: Toolbar Integration in the Windows UI"
date: 2024-07-13T10:17:22.082Z
updated: 2024-07-14T10:17:22.082Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Facilitating Regular Updates: Toolbar Integration in the Windows UI"
excerpt: "This Article Describes Facilitating Regular Updates: Toolbar Integration in the Windows UI"
keywords: Window UI Toolbar Update,Windows Enhancement Toolbar,Toolbar UI Regularity,Interface Toolbar Adjustment,Toolbar Integration Ease,Windows UI Toolbar Upgrade,User Interface Toolbar Synergy
thumbnail: https://thmb.techidaily.com/623365f2ffae0d2d8c9a44d31ae5f64f961d3fb3d2838be2d2e5cf0ae63c28b6.jpg
---

## Facilitating Regular Updates: Toolbar Integration in the Windows UI

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
5. Enter the string title **DelegateExecute**, and press the **Return** key.  
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-zte-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of ZTE Without PUK Codes</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-extended-monitor-lag-in-windows/"><u>Strategies to Combat Extended Monitor Lag in Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-the-markets-youtubes-top-picks/"><u>2024 Approved  Navigating the Markets  YouTube's Top Picks</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/boosting-engagement-uploading-and-sharing-on-instagram-desktop-for-2024/"><u>Boosting Engagement  Uploading and Sharing on Instagram Desktop for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/securing-off-screen-windows-6-methods-for-win11-users/"><u>Securing Off-Screen Windows: 6 Methods for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-windows-system-preferences-to-adjust-after-dark-mode/"><u>Mastery of Windows System Preferences to Adjust After Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/unrestricted-windows-dialogue-embrace-freedomgpt/"><u>Unrestricted Windows Dialogue: Embrace FreedomGPT</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-fostering-connection-and-engagement-for-brands-on-tiktok-for-2024/"><u>[New] Fostering Connection and Engagement for Brands on TikTok for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-secondary-antivirus-without-defenders-hindrance/"><u>Tips for Integrating Secondary Antivirus Without Defender’s Hindrance</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-art-of-capturing-imagination-best-shot-tips/"><u>In 2024, The Art of Capturing Imagination  Best Shot Tips</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-large-group-renames-with-powertoys/"><u>Simplify Large Group Renames with PowerToys</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-the-silencers-guide-banishing-background-buzz/"><u>2024 Approved  The Silencer's Guide  Banishing Background Buzz</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-fbm-hiccups-today/"><u>Swiftly Solve Your Windows FBM Hiccups Today</u></a></li>
<li><a href="https://win11.techidaily.com/seven-vintage-windows-traits-that-made-it-to-version-11/"><u>Seven Vintage Windows Traits That Made It to Version 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-nullifying-windows-11s-eyes-on-you/"><u>Mastery in Nullifying Windows 11'S Eyes on You</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-phones-capability-for-windows-recording/"><u>Streamline Phone's Capability for Windows Recording</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-apple-iphone-se-2022-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from Apple iPhone SE (2022)</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions.</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-vivo-x-fold-2-by-drfone-android/"><u>Full Guide to Unlock Your Vivo X Fold 2</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-terminal-in-quake-mode-on-windows/"><u>Utilizing Terminal in Quake Mode on Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/discover-the-best-free-and-paid-subtitle-edit-alternatives-for-mac-for-2024/"><u>Discover the Best Free and Paid Subtitle Edit Alternatives for Mac for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-inner-gamer-strategic-play-and-success-at-zero-cost/"><u>Unleash Your Inner Gamer: Strategic Play & Success at Zero-Cost</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-tales-leading-academies-for-aspiring-narrators/"><u>Mastering Tales  Leading Academies for Aspiring Narrators</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-discover-the-best-pc-intro-creators-free-and-paid-options-for-2024/"><u>New Discover the Best PC Intro Creators Free and Paid Options for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-silencing-ambient-wrongdoers-a-comprehensible-guide-on-audacitys-noise-reduction/"><u>2024 Approved  Silencing Ambient Wrongdoers  A Comprehensible Guide on Audacity's Noise Reduction</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-essential-tips-for-attending-tiktok-live-events-for-2024/"><u>[New] Essential Tips for Attending TikTok Live Events for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-guide-to-effortless-acquisition-of-exquisite-royalty-free-images/"><u>The Guide to Effortless Acquisition of Exquisite Royalty-Free Images</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/personalized-music-collection-enhancement-from-spotify-to-youtube-music/"><u>Personalized Music Collection Enhancement From Spotify to YouTube Music</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-wi-fi-access-via-windows-11-the-hotspot-setup-process/"><u>Streamlining Wi-Fi Access via Windows 11: The Hotspot Setup Process</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-infinix-zero-5g-2023-turbo-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-cannot-end-task-on-your-computer/"><u>Tackling 'Cannot End Task' On Your Computer</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-filming-friends-directly-share-videos-on-twitter/"><u>[New] Filming Friends  Directly Share Videos on Twitter</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevating-your-channels-profits-with-impactful-and-effective-trailers/"><u>2024 Approved  Elevating Your Channels' Profits with Impactful and Effective Trailers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/harmonizing-audio-and-visuals-add-apple-music-to-videos/"><u>Harmonizing Audio and Visuals  Add Apple Music to Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-explore-free-fb-visual-creation-tools-best/"><u>In 2024, Explore Free FB Visual Creation Tools - Best</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optic-zenith-premier-choices-in-the-realm-of-8k/"><u>2024 Approved  Optic Zenith  Premier Choices in the Realm of 8K</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-blue-windows-fails/"><u>Mastering the Art of Fixing Blue Windows Fails</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-accounts-after-fails/"><u>Bypassing Disabled Windows Accounts After Fails</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-chart-topping-tunes-compiling-an-impressive-youtube-playlist/"><u>[New] 2024 Approved  Chart-Topping Tunes  Compiling an Impressive YouTube Playlist</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>4 solution to get rid of pokemon fail to detect location On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocks-lost-luster-await-wise-wisdom-before-shift/"><u>BitLocks Lost Luster: Await Wise Wisdom Before Shift</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h-265-on-xiaomi-redmi-note-13-proplus-5g-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Xiaomi Redmi Note 13 Pro+ 5G, is it possible?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-10-best-free-video-editing-software-for-ubuntu/"><u>New In 2024, Top 10 Best Free Video Editing Software for Ubuntu</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-text-actions-in-the-snipping-tool-on-windows-11/"><u>How to Use Text Actions in the Snipping Tool on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-10-top-tools-for-dynamic-image-background-alterations/"><u>[New] 10 Top Tools for Dynamic Image Background Alterations</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-ways-to-transfer-messages-from-apple-iphone-8-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>4 Ways to Transfer Messages from Apple iPhone 8 to iPhone Including iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-top-7-action-and-sports-cameras-under-200/"><u>In 2024, Top 7 Action and Sports Cameras Under $200</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-audio-post-production-in-fcp-tips-and-tricks-for-2024/"><u>Updated Audio Post-Production in FCP Tips and Tricks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-mandatory-components-not-available-in-win10win11/"><u>Sidestep Mandatory Components Not Available in WIN10/WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-accurate-game-detection-failure-in-discord-windows-pc/"><u>Solutions for Accurate Game Detection Failure in Discord (Windows PC)</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-lost-connection-top-9-remedies-for-missing-bluetooth-on-win-11/"><u>Revive the Lost Connection: Top 9 Remedies for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-calculating-best-podcast-debut-days/"><u>[New] Calculating Best Podcast Debut Days</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-your-journey-through-the-world-of-iphone-memos/"><u>[Updated] In 2024, Your Journey Through the World of iPhone Memos</u></a></li>
<li><a href="https://win11.techidaily.com/why-win10-is-more-than-enough-in-the-current-tech-scene/"><u>Why Win10 Is More Than Enough in the Current Tech Scene</u></a></li>
<li><a href="https://win11.techidaily.com/overhaul-your-inbox-and-calendar-use-custom-images/"><u>Overhaul Your Inbox and Calendar: Use Custom Images</u></a></li>
<li><a href="https://win11.techidaily.com/sly-settings-shuffle-disguising-power-buttons-on-desktop/"><u>Sly Settings Shuffle: Disguising Power Buttons on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-life-top-11-fixes-for-windows-11-issues/"><u>Simplify Your Life: Top 11 Fixes for Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-mp3-to-mp4-converter-how-to-convert-mp3-to-mp4-in-2024/"><u>New MP3 to MP4 Converter How to Convert MP3 to MP4, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-image-editing-efficiently-removing-backdrops/"><u>The Art of Image Editing: Efficiently Removing Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
<li><a href="https://win11.techidaily.com/tethering-tech-microsofts-vision-in-windows-11-phones/"><u>Tethering Tech: Microsoft's Vision in Windows 11 Phones</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/quick-tips-for-textual-overlay-in-vimeo-content/"><u>Quick Tips for Textual Overlay in Vimeo Content</u></a></li>
</ul></div>
