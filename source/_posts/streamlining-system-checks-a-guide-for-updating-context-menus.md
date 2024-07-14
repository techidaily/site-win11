---
title: "Streamlining System Checks: A Guide for Updating Context Menus"
date: 2024-07-13T10:06:17.641Z
updated: 2024-07-14T10:06:17.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining System Checks: A Guide for Updating Context Menus"
excerpt: "This Article Describes Streamlining System Checks: A Guide for Updating Context Menus"
keywords: Context Menu Update,Streamlined Checkup,System Updates Quickly,Menu Optimization Guide,Efficient System Review,Context Menu Improvement,Navigation Enhancement
thumbnail: https://thmb.techidaily.com/75afd5a2790c3528915ac28a66faf57312a6eb60abbc500be807cdf0c4c1fe06.jpg
---

## Streamlining System Checks: A Guide for Updating Context Menus

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
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-tecno-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Tecno</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-demystified-how-to-resolve-windows-crashes-quickly/"><u>Blue Screen Demystified: How To Resolve Windows Crashes Quickly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-how-to-change-the-privacy-setting-on-your-youtube-videos/"><u>In 2024, How to Change the Privacy Setting on Your YouTube Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-maximizing-your-camera-masterful-android-time-lapse-videography/"><u>[New] Maximizing Your Camera  Masterful Android Time-Lapse Videography</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-tips-for-successful-home-based-podcasts/"><u>Essential Tips for Successful Home-Based Podcasts</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-canary-your-security-ally/"><u>Intro to Windows Canary: Your Security Ally</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/aesir-rebellion-skies-of-valhalla/"><u>Aesir Rebellion  Skies of Valhalla</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-greyed-out-display-changes-on-windows-system/"><u>Eliminate Greyed-Out Display Changes on Windows System</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-quick-and-accurate-screenshot-of-uac-prompts/"><u>Techniques for Quick and Accurate Screenshot of UAC Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-feature-flashback-the-surviving-anniversary-of-7-elements/"><u>Windows 11 Feature Flashback: The Surviving Anniversary of 7 Elements</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-the-insiders-path-to-joining-others-tiktok-gigs/"><u>[Updated] The Insider's Path to Joining Others' TikTok Gigs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sharing-with-the-top-5-software-picks-for-pcs/"><u>Streamlined Sharing with the Top 5 Software Picks for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-puzzle-of-non-opening-apps-in-w11/"><u>Unlocking the Puzzle of Non-Opening Apps in W11</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sector-mastering-windows-methods-for-adapter-velocity-check/"><u>Speed Sector: Mastering Windows Methods for Adapter Velocity Check</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/discover-the-secret-to-affordable-final-cut-pro-education-bundle-revealed-for-2024/"><u>Discover the Secret to Affordable Final Cut Pro Education Bundle Revealed for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-honor-magic-5-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Honor Magic 5</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-pc-power-for-distributed-video-conversion-by-tdarr/"><u>Optimize PC Power for Distributed Video Conversion by Tdarr</u></a></li>
<li><a href="https://win11.techidaily.com/dynamic-walls-for-windows-11-setting-lively-desktop-backdrops/"><u>Dynamic Walls for Windows 11: Setting Lively Desktop Backdrops</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-easy-path-to-pure-audio-advanced-noise-reduction-tactics-for-audacity-and-filmorapro-users-for-2024/"><u>New The Easy Path to Pure Audio Advanced Noise Reduction Tactics for Audacity and FilmoraPro Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-requires-privilege-error-code-0x80070522-in-windows-devices/"><u>Eradicating Requires Privilege Error (Code 0X80070522) in Windows Devices</u></a></li>
<li><a href="https://techidaily.com/why-are-your-photos-lost-from-iphone-12-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Why are your photos lost from iPhone 12? | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tech-tutorial-how-to-launch-calculator/"><u>Windows 11 Tech Tutorial: How to Launch Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-addressing-windows-non-response-to-powershell-command/"><u>Steps for Addressing Windows Non-Response to PowerShell Command</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-abrupt-device-removal-errors-dxgi/"><u>Fixing Abrupt Device Removal Errors (DXGI)</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-integrating-cg-centrals-luts-into-vfx-production-flows/"><u>2024 Approved  Integrating CG Central's Luts Into VFX Production Flows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-unlocking-your-potential-in-youtube-video-production-scripts/"><u>[New] Unlocking Your Potential in YouTube Video Production Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-workstation-access-the-hidden-side-of-rdp-in-win-11/"><u>Zero-Entry Workstation Access: The Hidden Side of RDP in Win 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nati-ajay-mastering-the-art-and-science-of-online-income/"><u>Carminati (Ajay)  Mastering the Art and Science of Online Income</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-windows-11-desktop-sparkle-with-lively-wallpaper-art/"><u>Make Your Windows 11 Desktop Sparkle with Lively Wallpaper Art</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-reopen-stuck-adobe-photoshop-in-windows/"><u>Guidelines to Reopen Stuck Adobe Photoshop in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-efficiency-via-powertoys/"><u>Accelerate Keyboard Efficiency via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-editing-with-these-win11-videoscripts/"><u>Streamline Editing with These Win11 Videoscripts</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-microsofts-smartguard-in-win-10/"><u>Enabling/Disabling Microsoft's SmartGuard in Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-deactivated-speech-recognition-microsofts-windows-11-guide/"><u>Addressing Deactivated Speech Recognition: Microsoft's Windows 11 Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-youtube-potential-try-these-12-effective-strategies-for-2024/"><u>Unlocking YouTube Potential - Try These 12 Effective Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-for-battery-life-extension-on-notebooks/"><u>Effective Techniques for Battery Life Extension on Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-typing-experience-changing-layouts-on-windows-11/"><u>Tailoring Your Typing Experience: Changing Layouts on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-ultimate-guide-to-collecting-key-tools-in-your-toolkit/"><u>[Updated] 2024 Approved  The Ultimate Guide to Collecting Key Tools in Your Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-overestimated-cpu-usage-in-windows-performance-tool/"><u>Addressing Overestimated CPU Usage in Windows Performance Tool</u></a></li>
<li><a href="https://facebook.techidaily.com/5-innovative-apps-to-manage-social-content-scheduling/"><u>5 Innovative Apps to Manage Social Content Scheduling</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-tiktok-earnings-gurus-choice-top-6-tools/"><u>[Updated] In 2024, TikTok Earnings Gurus' Choice  Top 6 Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/detailed-audit-unveiling-the-dji-inspire-1/"><u>Detailed Audit  Unveiling the DJI Inspire 1</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-unlock-the-secrets-of-measuring-ethernet-speeds/"><u>Windows Wonders: Unlock the Secrets of Measuring Ethernet Speeds</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-samsung-galaxy-z-flip-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Samsung Galaxy Z Flip 5? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/four-practical-alternatives-to-bitlocker-in-winoss/"><u>Four Practical Alternatives to BitLocker in WinOSs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for Apple iPhone 14 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/check-it-out-quick-fixes-for-your-webcam-and-mic-test/"><u>Check It Out: Quick Fixes for Your Webcam & Mic Test</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-infinix-smart-7-hd-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Infinix Smart 7 HD?</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-types-and-methods-for-hand-detection-systems/"><u>[Updated] Unveiling Types and Methods for Hand Detection Systems</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-elevate-your-creativity-6-aplus-apps-for-instagram-reels/"><u>[New] 2024 Approved  Elevate Your Creativity  6 A+ Apps for Instagram Reels</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-top-10-high-quality-android-voice-capture-software/"><u>Updated Top 10 High-Quality Android Voice Capture Software</u></a></li>
<li><a href="https://extra-tips.techidaily.com/revolutionize-selfies-with-top-android-and-ios-face-modifiers/"><u>Revolutionize Selfies with Top Android & iOS Face Modifiers</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-discords-inadequate-search-mechanism/"><u>Reviving Windows Discord's Inadequate Search Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-administrator-experience-via-terminals-every-time/"><u>Unhindered Administrator Experience via Terminals Every Time</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-photographic-face-off-legend-sj6-vs-xiaomis-yi-kickstarter/"><u>2024 Approved  Ultimate Photographic Face-Off  Legend SJ6 Vs. Xiaomi's Yi Kickstarter</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-10-best-video-editing-apps-for-creating-mind-bending-glitch-art-on-mobile/"><u>2024 Approved 10 Best Video Editing Apps for Creating Mind-Bending Glitch Art on Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-windows-voice-recording/"><u>A Step-By-Step Guide to Windows Voice Recording</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-visibility-to-system-startups-on-win-os/"><u>Restoring Visibility to System Startups on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-overcoming-geforce-x0001-on-w10w11-pcs/"><u>Quick Tips: Overcoming GeForce X0001 on W10/W11 PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/ditch-adobe-10-free-and-open-source-video-editors-for-linux-for-2024/"><u>Ditch Adobe 10 Free and Open-Source Video Editors for Linux for 2024</u></a></li>
</ul></div>
