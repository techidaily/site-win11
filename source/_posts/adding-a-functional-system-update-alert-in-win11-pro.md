---
title: Adding a Functional System Update Alert in Win11 Pro
date: 2024-07-13T11:16:10.846Z
updated: 2024-07-14T11:16:10.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding a Functional System Update Alert in Win11 Pro
excerpt: This Article Describes Adding a Functional System Update Alert in Win11 Pro
keywords: Win11 Update Alert,Functional Windows Fix,Pro PC Updates Notify,Win11 Security Tips,User-Friendly System Patches,Enhanced OS Alerts Win11,Win11 Pro Update Guide
thumbnail: https://thmb.techidaily.com/c8e68cffef41fc4061ac722c7019bbd23a7bd74185b074d0cf9fcbe34770c5fd.jpg
---

## Adding a Functional System Update Alert in Win11 Pro

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
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-a-found-iphone-se-by-drfone-ios/"><u>How To Unlock A Found iPhone SE?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-achieve-high-rankings-on-youtube-with-top-seo-tips-1-11/"><u>[New] 2024 Approved  Achieve High Rankings on YouTube with Top SEO Tips (1-11)</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-prepare-win11-in-vmware-17-player/"><u>Step-by-Step Guide to Prepare Win11 in VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/precision-note-taking-adopting-obsidian-written-canvas/"><u>Precision Note-Taking: Adopting Obsidian' Written Canvas</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-listening-made-easy-with-direct-recording/"><u>2024 Approved  YouTube Listening Made Easy with Direct Recording</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-3d-video-production-made-easy-free-and-paid-software-options/"><u>New 2024 Approved 3D Video Production Made Easy Free and Paid Software Options</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-setting-up-the-jdk-in-windows-11-efficiently/"><u>Unlocking Potential: Setting Up the JDK in Windows 11 Efficiently</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-iphone-14-pro-max-without-itunes-drfone-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked iPhone 14 Pro Max Without iTunes | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-seamless-ocean-footage-with-these-7-hacks/"><u>[Updated] Unlocking Seamless Ocean Footage with These 7 Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-lost-link-a-comprehensive-guide-to-reinstating-defective-adapters-in-windows/"><u>Reviving the Lost Link: A Comprehensive Guide to Reinstating Defective Adapters in Windows</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-what-is-ai-advertising/"><u>Updated What Is AI Advertising?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/top-7-icloud-activation-bypass-tools-for-your-iphone-12-pro-max-by-drfone-ios/"><u>Top 7 iCloud Activation Bypass Tools For your iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-5ghz-connection-in-windows-11-effective-fixes-here/"><u>Reintroduce Missing 5GHz Connection in Windows 11: Effective Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-clustered-icon-issue-in-windows-11-taskbar/"><u>Troubleshooting Clustered Icon Issue in Windows 11 Taskbar</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-subtitle-services-the-ultimate-convertors-guide/"><u>2024 Approved  Free Subtitle Services  The Ultimate Convertors Guide</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-the-updated-blueprint-for-incorporating-decay-effects-into-digital-soundtracks/"><u>Updated 2024 Approved The Updated Blueprint for Incorporating Decay Effects Into Digital Soundtracks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/google-data-retrieval-tool-restore-lost-data-from-google-pixel-fold-by-fonelab-android-recover-data/"><u>Google Data Retrieval tool – restore lost data from Google Pixel Fold</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-predominant-rainmeter-malfunctions-in-windows/"><u>Remedying Predominant Rainmeter Malfunctions in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-crafting-the-rhythm-adding-beats-and-melodies-to-your-fb-vids-for-2024/"><u>[New] Crafting the Rhythm  Adding Beats and Melodies to Your FB Vids for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-gt-3-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme GT 3 Device</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-everyones-guide-to-youtube-success-10-straightforward-video-tips/"><u>[Updated] Everyone's Guide to YouTube Success  10 Straightforward Video Tips</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-network-visibility-in-windows/"><u>Solving Disabled Network Visibility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/solving-issues-with-ccleaner-not-working-on-windows-1011/"><u>Solving Issues with CCleaner Not Working on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-windows-installer-cpu-spikes/"><u>Reducing Windows Installer CPU Spikes</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-audiophiles-guide-to-the-premier-8-4k-blu-rays/"><u>2024 Approved  Audiophile's Guide to the Premier 8 4K Blu-Rays</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-flourish-in-fame-elevate-from-zero-to-1000-followersmonthly-for-2024/"><u>[New] Flourish in Fame  Elevate From Zero to 1,000 Followers/Monthly for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/steering-the-path-of-your-onedrive-file-space-in-windows/"><u>Steering the Path of Your OneDrive File Space in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-podcast-live-the-straightforward-fix/"><u>In 2024, Podcast Live  The Straightforward Fix</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-advice-for-efficiently-creating-srt-files/"><u>In 2024, Expert Advice for Efficiently Creating SRT Files</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-polishing-your-tiktok-content-a-guide-to-filters/"><u>[New] Polishing Your TikTok Content  A Guide to Filters</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-compelling-youtube-content-through-split-screens/"><u>[New] 2024 Approved  Crafting Compelling YouTube Content Through Split-Screens</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-blank-screen-issues-after-attempting-to-connect/"><u>Tackling Blank Screen Issues After Attempting to Connect</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-art-of-discrete-audio-erosion-in-audacity/"><u>[New] The Art of Discrete Audio Erosion in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-graphics-restoration-on-latest-windows-oses/"><u>Simplifying Graphics Restoration on Latest Windows OSes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-stardews-guide-ginger-isle-essentials/"><u>[Updated] In 2024, Stardew's Guide  Ginger Isle Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-the-ultimate-guide-to-choosing-the-best-audio-converter-software/"><u>Updated The Ultimate Guide to Choosing the Best Audio Converter Software</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-vivo-g2-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Vivo G2 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/best-voice-changer-and-editor-for-singing-for-2024/"><u>Best Voice Changer and Editor for Singing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-windows-11s-error-codes/"><u>Navigating Through the Maze of Windows 11'S Error Codes</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/5-easy-ways-to-transfer-contacts-from-apple-iphone-13-to-android-drfone-by-drfone-transfer-from-ios/"><u>5 Easy Ways to Transfer Contacts from Apple iPhone 13 to Android | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-cartoonhub-master-review-2024-overview/"><u>[Updated] CartoonHub Master Review 2024 Overview</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-meme-mayhem-top-twenty-from-reddit-and-twitter/"><u>[New] 2024 Approved  Meme Mayhem  Top Twenty From Reddit & Twitter</u></a></li>
<li><a href="https://win11.techidaily.com/severing-non-primary-users-in-the-windows-ecosystem/"><u>Severing Non-Primary Users in the Windows Ecosystem</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-download-facebook-audio-as-mp3-best-converter-websites/"><u>Updated Download Facebook Audio as MP3 Best Converter Websites</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcome-ppt-save-blunders-6-quick-fixes-windows-users-need/"><u>Swiftly Overcome PPT Save Blunders: 6 Quick Fixes Windows Users Need</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-xiaomi-redmi-note-13-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Xiaomi Redmi Note 13 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/take-control-of-your-system-utilizing-alomware-tools-effectively/"><u>Take Control of Your System: Utilizing AlomWare Tools Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-mkv-conversion-to-mp4-in-windows-systems/"><u>Simplifying MKV Conversion to MP4 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-vision-capture-expert-insights-into-video-tech-for-2024/"><u>[Updated] Vision Capture  Expert Insights Into Video Tech for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-navigating-whatsapp-with-ease-advanced-functions-revealed/"><u>[New] 2024 Approved  Navigating WhatsApp with Ease  Advanced Functions Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winservicesexe-a-comprehensive-guide/"><u>Mastering Winservices.exe: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-secure-entry-into-windows-admin-console/"><u>Steps for Secure Entry Into Windows' Admin Console</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-realme-11-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Realme 11 Pro to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11-sign-in-complexity/"><u>Simplifying Windows 11 Sign-In Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
</ul></div>
