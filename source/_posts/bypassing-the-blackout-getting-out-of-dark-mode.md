---
title: "Bypassing The Blackout: Getting Out Of Dark Mode"
date: 2024-07-13T10:31:44.661Z
updated: 2024-07-14T10:31:44.661Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bypassing The Blackout: Getting Out Of Dark Mode"
excerpt: "This Article Describes Bypassing The Blackout: Getting Out Of Dark Mode"
keywords: Dark Mode Exit,Light Display,Mode Bypass,Bright Switch,Dark-to-Light,Luminance Change,Disabling DarkMode
thumbnail: https://thmb.techidaily.com/36f771b0e455ffd27a9b597a4a43e9338a94fa4efcb33fd8811a101c2c676422.png
---

## Bypassing The Blackout: Getting Out Of Dark Mode

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


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
<li><a href="https://win11.techidaily.com/facing-browser-blockades-top-tactics-to-reach-sites-on-your-system/"><u>Facing Browser Blockades: Top Tactics to Reach Sites on Your System</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-14-plus-without-apple-id-password-by-drfone-ios/"><u>In 2024, How To Erase an iPhone 14 Plus Without Apple ID Password?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-dont-make-these-top-8-mistakes/"><u>Mastering Windows 11: Don't Make These Top 8 Mistakes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-transitions-for-professional-videos/"><u>2024 Approved  Innovative Transitions for Professional Videos</u></a></li>
<li><a href="https://win11.techidaily.com/install-windows-11-on-mac-with-parallels-step-by-step/"><u>Install Windows 11 on Mac with Parallels Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-reclaiming-faulty-usb-connectivity-windows/"><u>Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-oppo-find-n3-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Oppo Find N3 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-apple-iphone-xs-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From Apple iPhone XS Online</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-resolving-windows-error-code-c0000022/"><u>Expert Guide to Resolving Windows Error Code C0000022</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-mastering-anime-soundscape-transformations-top-pick-software-for-desktop-and-mobile-devices/"><u>2024 Approved Mastering Anime Soundscape Transformations - Top Pick Software for Desktop & Mobile Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-vivo-s18e-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-vivo-y28-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Vivo Y28 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-remedies-to-address-instantaneous-failure-when-adding-a-folder-in-the-windows-onedrive-environment/"><u>Efficient Remedies to Address Instantaneous Failure when Adding a Folder in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-your-computers-warmup-time-in-win11/"><u>Cut Down Your Computer's Warmup Time in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unreachable-friends-list-on-steam-win-11/"><u>Fixing Unreachable Friends List on Steam (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-with-msoffice-on-win11-os/"><u>Getting Started with MSOffice on Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/disentangle-clustered-taskbar-items-in-windows-11/"><u>Disentangle Clustered Taskbar Items in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-visibility-on-windows-11-discreet-features/"><u>Enabling Visibility on Windows 11 Discreet Features</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-how-to-capture-your-nintendo-switch-game-video-for-2024/"><u>[Updated] How To Capture Your Nintendo Switch Game Video for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-zte-blade-a73-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP on ZTE Blade A73 5G?</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-differences-of-windows-terminal-vs-powershell/"><u>Dissecting the Differences of Windows Terminal Vs. PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-flexibility-in-your-windows-environment-with-alomware/"><u>Maximize Flexibility in Your Windows Environment with AlomWare</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-ultimate-guide-to-premium-audio-editors-for-creative-distortion/"><u>Updated The Ultimate Guide to Premium Audio Editors for Creative Distortion</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-easeus-review-inclusivity-in-action-for-2024/"><u>[Updated] EaseUS Review  Inclusivity in Action for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-ai-synergy-with-windows-11-features/"><u>Exploring AI Synergy with Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-and-correcting-windows-11-errors/"><u>Confronting and Correcting WINDOWS 11 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-steam-sound-fidelity/"><u>Enhancing Windows Steam Sound Fidelity</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-link-your-windows-product-key-to-a-microsoft-account/"><u>How to Link Your Windows Product Key to a Microsoft Account</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-layering-youtube-songs-onto-video-plays/"><u>2024 Approved  Layering YouTube Songs Onto Video Plays</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err-87-for-incompatible-library-loading/"><u>Fixing Err 87 for Incompatible Library Loading</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-how-to-record-video-calls-on-facebook-4-methods/"><u>[Updated] How to Record Video Calls on Facebook [4 Methods]</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err0r-code-e1-in-w10w11/"><u>Fixing Err0r: Code E1 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-an-inactive-itunes-on-your-pc/"><u>How to Reactivate an Inactive iTunes on Your PC</u></a></li>
</ul></div>
