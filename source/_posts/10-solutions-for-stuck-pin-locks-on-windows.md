---
title: 10 Solutions for Stuck PIN Locks on Windows
date: 2024-07-13T10:41:07.867Z
updated: 2024-07-14T10:41:07.867Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 10 Solutions for Stuck PIN Locks on Windows
excerpt: This Article Describes 10 Solutions for Stuck PIN Locks on Windows
keywords: Fix Stuck Windows Pin Lock,Bypass PIN Lock Issue,Unlock Windows Pin Code,Pin Lock Error Resolve,Windows Pin Pad Help,Free PIN Unlock Tips,Easy PIN Lock Solution
thumbnail: https://thmb.techidaily.com/69a1f779573ffb1d9703aa1f0c2a82407b77bc35052e19faef90f3eeabcd3dc4.jpg
---

## 10 Solutions for Stuck PIN Locks on Windows

 Is your Windows Hello PIN not being accepted by Windows? In most cases, it occurs when you enter the wrong PIN. Other factors that could contribute to this issue include corruption of the Ngc folder, a problem with your Microsoft or local accounts, or misconfigured PIN settings in the Group Policy Editor.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.

## 1\. Ensure You Aren't Entering the Incorrect PIN

 You could simply be entering the wrong PIN, which is the first possible cause of your PIN not working. To eliminate this possibility, reset your PIN once.

 Your computer must be connected to an active internet connection to reset your PIN. Therefore, turn on your computer and ensure that the internet is connected. To reset your PIN, go to the profile's login page and click on **I forgot my PIN**.

![Clicking on I Forgot My PIN in Windows Home Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Clicking-on-I-Forgot-My-PIN-in-Windows-Home-Screen.jpg)

 You can either reset the PIN by verifying your identity with your Microsoft account password or choose an alternative sign-in option by clicking **Send code**, which sends a code to your email address.

![Windows Notifying About Receiving the Code to Reset Pin on the Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Windows-Notifying-About-Receiving-the-Code-to-Reset-Pin-on-the-Windows-Login-Screen-Censor-1.jpg)

 If you select the latter option, enter the code you received by email and click **Continue**. Windows will direct you to enter a new PIN here, so enter it, confirm it once, and click **OK**.

![Adding a New Pin to Change the Old One in Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Adding-a-New-Pin-to-Change-the-Old-One-in-Windows-Login-Screen.jpg)

 Restart your computer once more, add your new PIN on the login screen, and try logging in again to make sure it was the wrong PIN that wasn't letting you enter the computer previously. You are good to go if you can log in this time - just don't forget your new PIN.

 If the PIN again does not work after resetting and you are sure that the PIN you are entering is correct, the problem may reside elsewhere. Therefore, use an alternate way to log in to your account and then rule out other possibilities.

## 2\. Sign-In Using Alternative Methods

 If resetting the PIN from the login screen does not resolve the issue, you can use your account password instead. To do that, follow the below steps:

1. Click **Sign-in options** to view other options for logging in.
2. Click the **key icon**, which is usually located on the left.  
![sign in options windows 11 password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11-password.jpg)
3. Type the password associated with your account here.

 Once logged in, you can start applying the remaining fixes.

 If you don't remember your account password, you can reset it just like you can your PIN. Unlike resetting the PIN, resetting the password mostly goes smoothly and lets you sign in.

## 3\. Delete the Ngc Folder in Windows

 Windows stores all your PIN-related settings in this folder, so if the OS isn't accepting your PIN, which is correct, you should delete this folder. This process will wipe out all PIN-related data from the OS. You can then set up a new PIN, which should work fine.

 You can delete the Ngc folder by following these steps:

1. Log in to your administrator account.
2. Navigate to **C: drive > Windows> ServiceProfiles > LocalService > AppData > Local> Microsoft**.
3. Locate the Ngc folder, right-click on it, and hit **Delete**.  
![Deleting Ngc Folder in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Deleting-Ngc-Folder-in-Windows-10-Edit.jpg)

 Navigate to **Settings > Accounts > Sign-in options** to set up a new PIN after deleting the old one. Afterward, click on **Windows Hello PIN**, add a new PIN, and hopefully, the PIN will start working on your operating system.

![Windows Hello PIN In Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/3-Windows-Hello-PIN-In-Windows-Settings-App.jpg)

 If this fix also doesn't resolve the issue, it lies somewhere else that needs to be investigated further.

## 4\. Rule Out User Account Specific Issues

 When troubleshooting PIN issues, it's essential to rule out account-specific problems first. To begin with, check that the problem does not persist on a single Microsoft account. The best way to confirm this is to switch to a local account. To do that, follow the below steps:

1. Open the Windows Settings app.
2. Go to **Accounts**.
3. Navigate to **Your info** in the left-sidebar.
4. Click on **Sign in with a local account instead**.  
![changing accounts settings in windows 10 settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/changing-accounts-settings-in-windows-10-settings-app-edit.jpg)
5. Click on **Next**.
6. Enter your PIN.
7. Set up your local account by adding your username and password.
8. Once done, hit **Next**.  
![Setting Up Local Account in Windows 10 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/2-Setting-Up-Local-Account-in-Windows-10-Settings-App.jpg)
9. Click on **Sign out and finish**.

 By following the above steps, you will return to the login screen. Type in your PIN again to confirm it works. If it does, it's your Microsoft account that is to blame. Creating another user account and checking if the PIN works there could help confirm that.

 Therefore, if the issue originates from your Microsoft user account, you should copy your files to the new account and start using the new account permanently.

 If the PIN does not work on any account, move on to the next fix.

## 5\. Tweak PIN Sign-In Settings in Group Policy Editor

 When the convenience PIN sign-in setting in the Group Policy Editor is disabled, the PIN will not work. Therefore, it's essential to ensure it's not causing the problem during sign-in.

 Some Windows versions, however, might not have this feature. If this applies to you as well, skip this step.

 Follow the below steps to adjust the settings in the Group Policy Editor:

1. Search for the **Run** app in the Windows search bar.
2. Type **gpedit.msc** and click on **OK**.
3. Navigate to **Administrative Templates > System > Logon**.
4. In the right-hand pane, locate and double-click on **Turn on convenience PIN sign-in setting**.
5. Check the **Enabled** checkbox, click **Apply**, and hit **OK**.

 If the setting is already enabled, continue to apply the remaining fixes.

 Group Policy Editor isn't available in the Windows Home edition by default. You can skip this fix if you're using the Home edition or try [alternative ways to get the Group Policy Editor](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

## 6\. Update or Downgrade Your OS

 According to [Microsoft support helpers](https://answers.microsoft.com/en-us/windows/forum/all/pin-not-working-on-windows-10/d444ebfb-d643-40b5-be62-1569454118d1), one of the possible causes of PIN not working on Windows may be recent updates. If you remember doing an update recently, you need to [roll the update back](https://www.makeuseof.com/tag/regret-update-windows-10-revert-version/).

 Conversely, if you haven't updated your computer for quite some time, maybe the problem stems from an outdated Windows OS. In that case, follow the below steps to update your computer:

1. Open the Windows Settings app.
2. Go to **Update & Security**.
3. Navigate to **Windows Update** in the left sidebar.
4. Click on **Check for updates** box.  
![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

 Windows will automatically check for the latest updates and update itself if necessary. After your OS has been updated, try logging in again with your PIN if it works this time.

 If you're experiencing this issue on Windows 11, see our guide on [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) to update your system. If you've started experiencing this issue after installing an update, follow our guide on [how to uninstall updates in Windows 11](https://www.makeuseof.com/windows-11-uninstall-updates/) and uninstall the most recent updates you installed.

 If the issue persists, run a malware scan to rule out the possibility of malware interference.

## 7\. Turn Off Your Antivirus and Run a Malware Scan

 Possible interference from antivirus may also result in your PIN being rejected. To prevent this from happening, temporarily turn off any third-party antivirus you're using. If turning off the third-party security suite fixes the problem, turn it off permanently.

 In addition, you can [temporarily disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) (now known as Microsoft Defender), the built-in security suite, to ensure that it's not the culprit. Remember to re-enable the security suite, as turning it off for too long can expose your device to malware.

 Aside from that, malware infections can also impair many system functions. Thus, it is imperative to rule out this possibility. You can easily do this by [running a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/). By scanning the system, you can ensure that no hidden malware is affecting its performance.

## 8\. Run an SFC Scan

 When you remove malware from your computer, make sure it hasn't corrupted any Windows files that might have caused the issue at hand.

 The easiest way to do this is to run an SFC scan. The scan automatically searches for corrupted files and replaces them with a cached copy. You can check out how to use the SFC tool in our guide on [how to repair corrupt Windows files with its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 If running the SFC scan does not fix the problem, you can [revert your system to an earlier restore point](https://www.makeuseof.com/use-system-restore-windows/) where the PIN was working. You can only do this if you've already created a restore point. Otherwise, it's impossible.

## PIN Still Isn’t Working on Windows?

 After you have tried all fixes listed above and the issue persists, consider restoring your computer to a previous point where the PIN was working fine. If that doesn't solve the problem either, it's best to factory reset your computer as a last resort.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-beyond-the-screen-vrs-creative-applications/"><u>In 2024, Beyond the Screen  VR's Creative Applications</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-from-jitters-to-smooth-mastering-video-stabilization-in-after-effects/"><u>New 2024 Approved From Jitters to Smooth Mastering Video Stabilization in After Effects</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-image-display-windows-11-style/"><u>Maximizing Window Image Display: Windows 11 Style</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-gopro-video-editing-on-mac-made-easy-tips-and-tricks/"><u>New 2024 Approved GoPro Video Editing on Mac Made Easy Tips and Tricks</u></a></li>
<li><a href="https://audio-editing.techidaily.com/artisan-soundscapes-for-blog-and-youtube-visionaries-for-2024/"><u>Artisan Soundscapes for Blog and YouTube Visionaries for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-file-management-crafting-multitudes-of-subfolders-instantly/"><u>Conquer File Management: Crafting Multitudes of Subfolders Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/processors-and-windows-discovering-your-cpus-generation-in-8-steps/"><u>Processors & Windows: Discovering Your CPU's Generation in 8 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-analyzing-the-core-upgrades-of-windows-11/"><u>Windows Reimagined: Analyzing the Core Upgrades of Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-poco-m6-pro-4g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Poco M6 Pro 4G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-ai-capabilities-at-ms-store/"><u>Delving Into AI Capabilities at MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-reading-qr-codes-on-windows-devices/"><u>Essential Tips for Reading QR Codes on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blocked-experience-in-roblox-addressing-account-restrictions/"><u>Fixing Blocked Experience in Roblox: Addressing Account Restrictions</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/7-ways-to-lock-apps-on-iphone-11-and-ipad-securely-by-drfone-ios/"><u>7 Ways to Lock Apps on iPhone 11 and iPad Securely</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Xiaomi 14? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-ribbon-to-windows-explorer/"><u>Restoring Legacy Ribbon to Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-quick-recording-keyboard-shortcut-tips-for-win-11/"><u>Mastering the Art of Quick Recording: Keyboard Shortcut Tips for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-installation-of-arm-based-windows-11-from-iso/"><u>Mastering the Installation of ARM-Based Windows 11 From ISO</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-crashes-during-xbox-app-update-process/"><u>Resolving Crashes During Xbox App Update Process</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How Do I Stop Someone From Tracking My Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/speak-up-troubleshooting-and-fixing-microphone-errors-on-microsoft-powered-google-meet/"><u>Speak Up! Troubleshooting and Fixing Microphone Errors on Microsoft-Powered Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-learning-7-strategies-for-windows-users/"><u>Enhancing Learning: 7 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-and-optimizing-windows-11-service-usage-wisely/"><u>Prioritizing and Optimizing Windows 11 Service Usage Wisely</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-absence-of-hypervisor-on-windows-sandbox/"><u>Identifying and Fixing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-audio-outliers-best-sound-distortion-apps-for-your-device/"><u>[Updated] In 2024, Audio Outliers  Best Sound Distortion Apps for Your Device</u></a></li>
<li><a href="https://driver-install.techidaily.com/configure-correctly-optimize-jetprinter-performance-in-windows/"><u>Configure Correctly: Optimize JetPrinter Performance in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-reno-10-5g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Oppo Reno 10 5G Phone with Broken Screen</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-apex-gk-quizmasters-video-channel-list/"><u>2024 Approved  Apex GK Quizmasters' Video Channel List</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-pcs-wi-fi-woes-six-effective-steps-from-fixing-adapter-failure/"><u>Reviving Your PC's Wi-Fi Woes - Six Effective Steps From Fixing Adapter Failure</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-win-os-cease-df-glitching-issues/"><u>Stabilizing Win OS: Cease DF Glitching Issues</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-save-money-stay-legal-free-filmora-options-you-can-trust/"><u>In 2024, Save Money, Stay Legal Free Filmora Options You Can Trust</u></a></li>
<li><a href="https://win11.techidaily.com/conducting-harmonious-auditory-performance-in-windows/"><u>Conducting Harmonious Auditory Performance in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-5-ways-to-open-windows-help-hub/"><u>Enhance Accessibility: 5 Ways to Open Windows Help Hub</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/dual-screen-delight-personalized-pixels-per-monitor-of-windows-1011/"><u>Dual Screen Delight: Personalized Pixels per Monitor of Windows 10/11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-grab-tiktok-videos-online-for-free/"><u>[New] 2024 Approved  Grab TikTok Videos Online for FREE</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-launch-windows-11-access-control-panel/"><u>Locate and Launch Windows 11 Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/go-pure-with-linux-avoid-wsl/"><u>Go Pure with Linux - Avoid WSL</u></a></li>
<li><a href="https://win11.techidaily.com/successful-virtualbox-setup-in-winscape/"><u>Successful VirtualBox Setup in Winscape</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-the-failed-file-synchronization-on-steam/"><u>Remedy for the Failed File Synchronization on Steam</u></a></li>
</ul></div>
