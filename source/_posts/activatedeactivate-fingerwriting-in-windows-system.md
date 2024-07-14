---
title: Activate/Deactivate Fingerwriting in Windows System
date: 2024-07-13T11:15:40.235Z
updated: 2024-07-14T11:15:40.236Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate/Deactivate Fingerwriting in Windows System
excerpt: This Article Describes Activate/Deactivate Fingerwriting in Windows System
keywords: Activate Fingerwriting,Deactivate Fingerwriting,Windows Fingerwriting Control,Enable Handwriting on PC,Disable Windows Handwriting,Windows System Writing Feature,Handwriting Function in Windows
thumbnail: https://thmb.techidaily.com/bcabaab591bfcab705d7b78fa9328071af132a2f5e82388216c0b539cc0ef7e4.jpg
---

## Activate/Deactivate Fingerwriting in Windows System

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also [convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-from-iphone-13-pro-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID From iPhone 13 Pro Making It Possible</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-the-art-of-movement-enhancing-your-photos-with-illustrators-motion-blur/"><u>[New] In 2024, The Art of Movement  Enhancing Your Photos with Illustrator's Motion Blur</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-extended-monitor-lag-in-windows/"><u>Strategies to Combat Extended Monitor Lag in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions.</u></a></li>
<li><a href="https://win11.techidaily.com/securing-off-screen-windows-6-methods-for-win11-users/"><u>Securing Off-Screen Windows: 6 Methods for Win11 Users</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-revitalizing-urban-areas-with-environmental-vision-and-purpose/"><u>[Updated] 2024 Approved  Revitalizing Urban Areas with Environmental Vision and Purpose</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-wi-fi-access-via-windows-11-the-hotspot-setup-process/"><u>Streamlining Wi-Fi Access via Windows 11: The Hotspot Setup Process</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-drafting-dynamic-denouements/"><u>In 2024, Drafting Dynamic Denouements</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-large-group-renames-with-powertoys/"><u>Simplify Large Group Renames with PowerToys</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-leap-into-instagram-stardom-with-ease/"><u>[New] In 2024, Leap Into Instagram Stardom with Ease</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/counteracting-sonic-overlap-3-proven-techniques-for-clear-audio/"><u>Counteracting Sonic Overlap 3 Proven Techniques for Clear Audio</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-from-free-to-profitable-unlocking-youtubes-monetization-at-500plus/"><u>[New] From Free to Profitable  Unlocking YouTube's Monetization at 500+</u></a></li>
<li><a href="https://win11.techidaily.com/tethering-tech-microsofts-vision-in-windows-11-phones/"><u>Tethering Tech: Microsoft's Vision in Windows 11 Phones</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-exodus-of-followers-instagrams-new-map/"><u>2024 Approved  The Exodus of Followers  Instagram's New Map</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-terminal-in-quake-mode-on-windows/"><u>Utilizing Terminal in Quake Mode on Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tiktok-top-ten-for-cutting-edge-content-creation/"><u>TikTok Top Ten for Cutting-Edge Content Creation</u></a></li>
<li><a href="https://win11.techidaily.com/sly-settings-shuffle-disguising-power-buttons-on-desktop/"><u>Sly Settings Shuffle: Disguising Power Buttons on Desktop</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-online-viewers-count-counter/"><u>[Updated] In 2024, Online Viewers Count Counter</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-cannot-end-task-on-your-computer/"><u>Tackling 'Cannot End Task' On Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/seven-vintage-windows-traits-that-made-it-to-version-11/"><u>Seven Vintage Windows Traits That Made It to Version 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-accurate-game-detection-failure-in-discord-windows-pc/"><u>Solutions for Accurate Game Detection Failure in Discord (Windows PC)</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-swap-genders-on-snapchat-facebook-or-instagram-photos/"><u>[Updated] 2024 Approved  How to Swap Genders on Snapchat, Facebook or Instagram Photos</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-crafting-stories-the-ultimate-youtube-channel-list/"><u>2024 Approved  Crafting Stories - The Ultimate YouTube Channel List</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/global-english-education-programs/"><u>Global English Education Programs</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-image-editing-efficiently-removing-backdrops/"><u>The Art of Image Editing: Efficiently Removing Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-mandatory-components-not-available-in-win10win11/"><u>Sidestep Mandatory Components Not Available in WIN10/WIN11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-vimeo-cash-flow-maximizing-income-through-content-marketing-for-2024/"><u>[New] Vimeo Cash Flow  Maximizing Income Through Content Marketing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocks-lost-luster-await-wise-wisdom-before-shift/"><u>BitLocks Lost Luster: Await Wise Wisdom Before Shift</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-clear-up-your-photos-best-10-online-image-enhancers-revealed/"><u>In 2024, Clear Up Your Photos  Best 10 Online Image Enhancers Revealed</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-stabilizing-your-gopro-footage-a-step-by-step-guide/"><u>[New] Stabilizing Your GoPro Footage  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/why-win10-is-more-than-enough-in-the-current-tech-scene/"><u>Why Win10 Is More Than Enough in the Current Tech Scene</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-assemble-an-impactful-visual-saga-with-montage-skills/"><u>[Updated] 2024 Approved  Assemble an Impactful Visual Saga with Montage Skills</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-art-of-crafting-compelling-video-testimonials/"><u>2024 Approved  Mastering the Art of Crafting Compelling Video Testimonials</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-fbm-hiccups-today/"><u>Swiftly Solve Your Windows FBM Hiccups Today</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-phones-capability-for-windows-recording/"><u>Streamline Phone's Capability for Windows Recording</u></a></li>
<li><a href="https://network-issues.techidaily.com/reclaiming-functionality-of-asus-internal-cam/"><u>Reclaiming Functionality of Asus Internal Cam</u></a></li>
<li><a href="https://win11.techidaily.com/unrestricted-windows-dialogue-embrace-freedomgpt/"><u>Unrestricted Windows Dialogue: Embrace FreedomGPT</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-best-academy-for-storytellers-top-8-recommendations/"><u>[Updated] 2024 Approved  Best Academy for Storytellers – [Top 8 Recommendations]</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/loom-studio-sync-screen-record-features-explained/"><u>Loom Studio  Sync Screen Record Features Explained</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-apple-iphone-13-location-on-viber-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change/Fake Your Apple iPhone 13 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-inner-gamer-strategic-play-and-success-at-zero-cost/"><u>Unleash Your Inner Gamer: Strategic Play & Success at Zero-Cost</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/breaking-the-screens-top-10-most-popular-female-youtubers/"><u>Breaking the Screens  Top 10 Most Popular Female YouTubers</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-life-top-11-fixes-for-windows-11-issues/"><u>Simplify Your Life: Top 11 Fixes for Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-lost-connection-top-9-remedies-for-missing-bluetooth-on-win-11/"><u>Revive the Lost Connection: Top 9 Remedies for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-spoofing-success-the-path-to-parody-proficiency-for-2024/"><u>[Updated] Spoofing Success  The Path to Parody Proficiency for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-best-low-cost-android-calls-compared-ranking/"><u>In 2024, Best Low-Cost Android Calls Compared Ranking</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-oneplus-nord-3-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From OnePlus Nord 3 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-secondary-antivirus-without-defenders-hindrance/"><u>Tips for Integrating Secondary Antivirus Without Defender’s Hindrance</u></a></li>
</ul></div>
