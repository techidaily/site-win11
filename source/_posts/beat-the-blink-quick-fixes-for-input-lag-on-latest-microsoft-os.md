---
title: "Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS"
date: 2024-07-13T10:16:01.768Z
updated: 2024-07-14T10:16:01.768Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS"
excerpt: "This Article Describes Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS"
keywords: Beat Lag,Input Lag Fix,Microsoft OS Input,Blink Quick Fixes,Latest OS Performance,Reduce Blink Latency,Optimize OS Speed
thumbnail: https://thmb.techidaily.com/c2896db39f882c98719dcfe14e4ab3efb1b4a55af204f20cceb82eb23a04b0c6.jpg
---

## Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS

 A laggy-feeling keyboard can drive you up the wall, especially when you're working on something important and the keyboard refuses to cooperate. If you're a writer, web developer, programmer, or professional who spends hours punching keys, this problem can slow you down.

 Before you troubleshoot the issue, ensure that it really is the keyboard that's causing the problem. Sometimes, you may be inadvertently doing things that cause your Windows PC to slow down, which can also be a reason for keyboard input lag. However, if that's not the case, here are some easy fixes you can try to rid yourself of the annoying keyboard input lag.

## 1\. Change the Keyboard Properties

 Changing a few keyboard properties may help resolve the input lag. Here is all that you need to do:

1. Press the **Win + R** keys together and type "**control keyboard**" in the text field of the Run dialog that opens.
2. Click **Enter**. This will open the keyboard properties window, where you will see the option to adjust the **Repeat delay** and **Repeat rate**. The Repeat delay allows you to set the delay between you press-holding a key and the initiation of the repeated output of the key. The Repeat rate allows you to adjust the speed at which this output is repeated.  
![changing keyboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/keyboard-settings.jpg)
3. Shorten the **Repeat delay** and increase the **Repeat rate** to eliminate the input lag. This may require some experimentation before you find the sweet spot, but there's a convenient test box built right into the Keyboard properties window to help you find the right balance.
4. When you've found an ideal Repeat delay and Repeat rate, press **OK** at the bottom to save and exit.

## 2\. Update or Reinstall the Keyboard Driver

 Your system's driver tells your PC how to handle external hardware like your keyboard. If your keyboard's driver is outdated, your computer will struggle to communicate with the hardware. As such, an outdated driver is a possible cause of your keyboard input lag.

 There are a few ways to [find and replace outdated Windows drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/). Here is how you can this utility to update or reinstall your keyboard driver:

1. Press the **Win** \+ **S** keys together to open the Search utility.
2. Type "Device Manager" and click **Open**.
3. Right-click on the keyboard driver and choose **Update driver** from the context menu.
4. Click on **Search automatically for drivers**. If your system has an updated version available, it will notify you, and you can proceed with installing it. .
5. Otherwise, you can choose **Search for updated drivers on Windows Update** and install the updated version if available.  
![Searching for updated drivers using Windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/search-for-updated-drivers.jpg)

 Alternatively, you can download the latest available version of the driver manually from the manufacturer's website. Then, follow these steps:

1. Repeat steps 1-3 from above and choose **Browse my computer for drivers**.
2. Locate and select the updated version you just downloaded and install it.

## 3\. Disable Filter Keys

 Filter keys is an accessibility feature that instructs Windows to ignore brief or repeated keystrokes. This could potentially be a reason for the delayed output of your keyboard. You can fix this by disabling Filter keys from the keyboard settings.

1. Open **Settings** by searching for “**settings**” in the Start Menu.
2. Select **Ease of Access** and scroll down to the **Keyboard** section from the right pane.
3. Click on **Keyboard** and look for **Use Filter Keys**.
4. Under this head, you will find a toggle button. If it's enabled, disable it and close the Settings app.  
![Turning off the Use Filter Keys button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turning-off-the-use-filter-keys-button.jpg)

 If you're running Windows 11, you'll find the option to disable Filter Keys in **Settings > Accessibility > Keyboard > Filter Keys**.

![disabling filter keys on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/update.jpg)

 Then, try typing something into your text editor and see if it still lags.

## 4\. Run the Windows Keyboard Troubleshooter

 Fortunately, Windows comes with some great built-in troubleshooting tools. Whether you're experiencing an input lag or your [keyboard isn't working at all](https://www.makeuseof.com/tag/laptop-keyboard-not-working/), the keyboard troubleshooter can provide you with a solution. Follow these steps to use the troubleshooter:

1. Open the Settings app and navigate to **Update & Security** \> **Troubleshoot**.
2. You'll now see a list of recommended troubleshooters. If there are none, simply click on **Additional troubleshooters** and look for **Keyboard**. Click on it and select **Run the troubleshooter**.  
![Run the keyboard troubleshooter in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/keyboard-troubleshooter-1.jpg)

 If you're running Windows 11, you'll find the Keyboard troubleshooter in **Settings > System > Troubleshoot > Other Troubleshooter > Keyboard**.

![running the keyboard troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/keyboard-troubleshooter.jpg)

 The troubleshooter will look for potential issues. If it finds something to fix, go ahead and follow the directions. When you're done, see if the issue has been resolved.

## 5\. Use the DISM Command Line Tool

 DISM is an administrator-level command-line tool that you can use to repair your system's Windows image. This tool can help address your keyboard input lag when it's being caused by an error rooted deeper into your Windows image that the system file checker can't repair.

1. Start by running the Command Prompt as an administrator. If you do not know how to do this, our guide on [the different ways of running Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) can help you.
2. Then, run the following commands in this order:

`DISM /Online /Cleanup-Image /ScanHealth  
DISM /Online /Cleanup-Image /CheckHealth  
DISM /Online /Cleanup-Image /RestoreHealth`

![RestoreHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/dism-online-restore-health.jpg)

 Let the process finish, then verify if this trick solved the keyboard input lag.

## 6\. Perform Specific Fixes for Wireless Keyboards

 The above issues apply to keyboards in general. However, some issues are specific to wireless keyboards. If your keyboard is wireless, try the following fixes.

### 1\. Replace the Batteries

 Start by ruling out the possibility of the lag being caused by a drained battery. To do this, replace the battery or recharge your keyboard to full. If this doesn't fix the problem, try the next solution.

### 2\. Check the Connection

 Start by trying to re-sync your keyboard with the USB receiver. If that doesn't help, insert the USB receiver into a different USB port on your computer if the current port lacks enough power. Try placing the keyboard closer to the USB receiver if possible.

### 3\. Remove Interference From Wireless Devices

 If you've placed other Wi-Fi devices such as a router or a cell phone near the computer, move it away and see if that eliminates the input lag.

## 7\. Consider Getting a New Keyboard

 If none of these solutions work, it could be a sign of hardware damage. So before you start searching online for [the best keyboards](https://www.makeuseof.com/tag/best-wireless-mouse-and-keyboard/), try plugging in a different keyboard that works fine on another computer to confirm hardware damage as the cause.

 While you're waiting for your new keyboard, you can use the Windows onscreen keyboard. Search for "**onscreen keyboard**" in the Start Menu and launch the Best Match.

![launching on screen keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/on-screen-keyboard.jpg)

 Alternatively, you can use one of the several [virtual keyboard apps](https://www.makeuseof.com/windows-best-virtual-keyboards/) available out there. If you don't like the idea of virtual keyboards, you can use speech-to-text software to type without having the user your keyboard.

## Back to Buttery-Smooth Typing on Windows

 Keyboard input lag can be a real annoyance. Hopefully, one of these solutions worked for you, and you're now back to blazing-fast typing as usual. If you want to type even faster, consider creating a custom keyboard layout.

 A laggy-feeling keyboard can drive you up the wall, especially when you're working on something important and the keyboard refuses to cooperate. If you're a writer, web developer, programmer, or professional who spends hours punching keys, this problem can slow you down.

 Before you troubleshoot the issue, ensure that it really is the keyboard that's causing the problem. Sometimes, you may be inadvertently doing things that cause your Windows PC to slow down, which can also be a reason for keyboard input lag. However, if that's not the case, here are some easy fixes you can try to rid yourself of the annoying keyboard input lag.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/offline-process-for-extra-users-in-windows-11/"><u>Offline Process for Extra Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-set-default-touch-input-placement/"><u>Win 11: Set Default Touch Input Placement</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-windows-steam-speed-eliminating-zero-downloads/"><u>Elevate Windows Steam Speed: Eliminating Zero-Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-10-and-11s-0x0000011b-faults/"><u>Addressing Windows 10 & 11'S 0X0000011B Faults</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-access-issues-with-these-top-5-windows-fixes-on-security-keys/"><u>Unlock Access Issues with These Top 5 Windows Fixes on Security Keys</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-microphone-linkage-in-pc-gaming-with-valorant/"><u>Addressing Disrupted Microphone Linkage in PC Gaming with Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rescue-your-windows-mail-app-from-the-clutches-of-0x800713f/"><u>How to Rescue Your Windows Mail App From the Clutches of 0X800713F</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-windows-pin-entry/"><u>Troubleshooting Non-Responsive Windows PIN Entry</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-comparing-leading-cam-tech-with-mymanycam/"><u>[New] 2024 Approved  Comparing Leading Cam Tech with MyManyCam</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-samsung-galaxy-a34-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Samsung Galaxy A34 5G FRP Locks</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-importance-in-preserving-win-11-notifications/"><u>Unveiling the Importance in Preserving Win 11 Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-repair-tool-guide/"><u>Breaking Down Windows Repair Tool Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-tactics-for-elevating-your-videos-popularity-at-vimeo-for-2024/"><u>[New] Tactics for Elevating Your Video's Popularity at Vimeo for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/awesome-free-apps-to-transform-your-mobile-images/"><u>Awesome FREE Apps to Transform Your Mobile Images</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-microsoft-ai-hub-features/"><u>Exploring Microsoft AI Hub Features</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-missing-driver-issues/"><u>Overcoming Windows Error: Missing Driver Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-the-win-network-access-issue/"><u>How to Mend the WIN Network Access Issue</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-bt-folder-functionality/"><u>Understanding Windows ~BT Folder Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-new-windows-11-taskbar-features/"><u>Mastering the New Windows 11 Taskbar Features</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-editing-videos-on-mac-try-vn-video-editor-or-these-alternatives-for-2024/"><u>Updated Editing Videos on Mac? Try VN Video Editor or These Alternatives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fix-unrecognized-app-warning-during-windows-setup/"><u>Fix Unrecognized App Warning During Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-unlock-regular-startup-for-outlook-on-safe-mode/"><u>Steps to Unlock Regular Startup for Outlook on Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-walkthrough-for-transferring-old-games-to-windows-gallery/"><u>A Walkthrough for Transferring Old Games to Windows Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-audit-your-windows-drive-space-usage-efficiently/"><u>How to Audit Your Windows Drive Space Usage Efficiently</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-10-secret-tips-to-better-use-canva-photo-editor/"><u>[Updated] 10 Secret Tips to Better Use Canva Photo Editor</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-black-screen-during-games-on-win/"><u>Resolving Black Screen During Games on WIN</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-11-experience-introducing-an-augmented-run-feature/"><u>Master Your Windows 11 Experience: Introducing an Augmented Run Feature</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-asus-rog-phone-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-software-instability-in-windows-store-purchases/"><u>Addressing Software Instability in Windows Store Purchases</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-complexity-set-terminal-as-the-default-cli/"><u>Cut-Down Complexity: Set Terminal as the Default CLI</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-windows-11s-integrity-quick-checks/"><u>Confirming Windows 11'S Integrity: Quick Checks</u></a></li>
<li><a href="https://win11.techidaily.com/scrutinizing-password-ingress-windows-pass-and-no-pass-outcomes/"><u>Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-play-your-srt-files-easily-winmac-tips/"><u>[New] Play Your SRT Files Easily  Win/Mac Tips</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-mystery-of-continuous-pauses-in-photo-booths/"><u>2024 Approved  Mystery of Continuous Pauses in Photo Booths</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-the-veiled-query-power-in-windows-11/"><u>Awakening the Veiled Query Power in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-bluetooth-attempt-error-in-windows/"><u>Mastering the Fix: Bluetooth Attempt Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-enhance-video-production-7-best-free-sounds-for-editors/"><u>[New] In 2024, Enhance Video Production - 7 Best Free Sounds for Editors</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-new-folders-into-windows-11s-menu/"><u>Integrating New Folders Into Windows 11'S Menu</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-crafting-professional-ppt-video-content/"><u>[Updated] 2024 Approved  Crafting Professional PPT Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pcs-archives-functionality/"><u>Enhance Your PC's Archives Functionality</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-foremost-video-starters-the-leading-16-youtube-openers/"><u>[Updated] In 2024, Foremost Video Starters  The Leading 16 YouTube Openers</u></a></li>
<li><a href="https://win11.techidaily.com/yourdevice-link-assessing-risks-and-benefits-in-w10-systems/"><u>YourDevice Link - Assessing Risks and Benefits in W10 Systems</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-safeguard-your-subjects-face-blurring-techniques-in-video-editing-for-2024/"><u>New Safeguard Your Subjects Face Blurring Techniques in Video Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-restore-your-usb-wi-fi-on-a-pc/"><u>7 Key Steps to Restore Your USB Wi-Fi On a PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pcs-powertoys-10-essential-tips/"><u>Mastering Windows PCs: PowerToys' 10 Essential Tips</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-create-shareable-memes-with-adobe-photoshop/"><u>[Updated] 2024 Approved  Create Shareable Memes with Adobe Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-backing-up-and-restoring-notebooks/"><u>A Practical Approach: Backing Up & Restoring Notebooks</u></a></li>
</ul></div>
