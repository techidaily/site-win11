---
title: "Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11"
date: 2024-07-13T09:58:03.243Z
updated: 2024-07-14T09:58:03.243Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11"
excerpt: "This Article Describes Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11"
keywords: Fix Network Error Win11,Resolve Net Issues Windows 11,Unblock Internet Windows Pro,Overcome Connectivity Failure W11,Eliminate 'Not Reachable' WIN11,Correct Disconnect Window 11,Rectify Network Not Reachable Win11
thumbnail: https://thmb.techidaily.com/09207a7f08746a7a51db3d8aa3727dd060158727f29a32ea31aadbe48cebcd72.jpg
---

## Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11

 A common network issue that Windows 11 users face, is the "Windows can't connect to this network" error. This error can be quite frustrating, as Windows doesn’t give you any instructions on how to fix it. Sometimes, you just have to update the network driver or run the network troubleshooter.

 However, the solution might be a bit more complicated, but there's no need don’t worry. We’ll walk you through a complete troubleshooting process to get rid of the “Windows can’t connect to this network” error.

## 1\. Connect to the Network Using Another Device

 There’s a chance there’s nothing wrong with your Windows 11 computer, but you get the “Windows can’t connect to this network” error due to a network-related issue. To test it, try to connect to the same network using a different device. If you run into the same error, you’ll have to solve your network issues.

 If you can connect to the same network on a different device, go through the troubleshooting tips below.

## 2\. Manage the Network Drivers on Windows 11

 In many cases, connection issues such as the "Windows can't connect to this network" error can be resolved by updating your PC's network drivers. However, if you recently updated the drivers and the error appeared soon afterward, you should roll back the drivers to the previous version until the new ones are fixed. You can also try reinstalling the drivers to see if that fixes the problem.

 All these actions can be performed by accessing the Device Manager, so let's dive in and try some fixes.

### 1\. Update Network Drivers

To update your network drivers, perform the following:

![Update network driver in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-driver-1.jpg)

1. Right-click the**Start** button and select**Device Manager** .
2. In the Device Manager window, expand the**Network adapters** section.
3. Right-click on the wireless adapter for your device, and click on**Update driver** .
4. On the next window, choose**Search automatically for drivers** .
5. Windows will download and install the latest drivers for your device.

### 2\. Roll Back the Network Drivers

 If the issue started after you installed a new network driver, here's how to go back to the drivers you had before:

![Roll back driver version in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties-1.jpg)

1. Open Device Manager.
2. Expand the**Network adapters** section.
3. Right-click on the network driver and select**Properties** .
4. In the Properties window, go to the**Driver** tab.
5. Click on the**Roll back** driver option. The option will be grayed out if the driver wasn't recently updated.
6. Windows will install the previous version of the network driver.
7. Reboot your computer.

### 3\. Uninstall the Network Drivers

 If you want to do a fresh install, first download your network drivers from your manufacturer's website. It's a good idea to do this first before you uninstall your current network drivers; once they're gone, you won't be able to connect to the internet through that network adapter until you reinstall its drivers again.

 Once you have your new drivers ready, it's time to scrub away the old one:

![Uninstall network driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-driver-1.jpg)

1. Open Device Manager.
2. Again, expand the**Network adapters** section.
3. Right-click the network driver.
4. Click on**Uninstall device** .
5. Check the**Attempt to remove the driver for this device** option.
6. Click on**Uninstall** .
7. When you reboot your PC, Windows will automatically reinstall the driver.

 If this method didn't work, there are [other ways to uninstall drivers in Windows 11](https://www.makeuseof.com/windows-11-uninstall-drivers/) .

## 3\. Check for Windows Updates

 Microsoft constantly releases updates to fix any bugs and glitches you may encounter while using your computer. If you’re using an older Windows version, you might miss the updates designed to keep your computer running smoothly.

 To update Windows to the latest version, press**Windows key + I** to bring up the**Settings** menu. Then, click**Windows Updates > Check for updates** .

 Windows will search for any updates and install them automatically. Once the process is complete, try to connect to the network.

![Check Windows 11 version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-windows-version-1-2.jpg)

## 4\. Disable IPv6

 IPv6 is really not needed for most connections unless explicitly specified by your router or ISP. So, you should disable it and try connecting to the wireless network again.

Here is how you can disable IPv6 on your computer:

![Network connection properties in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv-6.jpg)

1. Locate the network icon on the System Tray.
2. Right-click on the icon and choose**Network and Internet settings** .
3. Click on**Advanced network settings** .
4. Under Related settings, choose**More network adapter options** .
5. Right-click on the wireless network, then choose**Properties** . Ensure you have admin privileges.
6. Uncheck the Internet Protocol Version 6 (IPv6) option.
7. Click**OK** .
8. Reconnect to the wireless network again.

## 5\. Disable and Enable the Wireless Network Adapter

 Sometimes, an easy reset of the wireless network adapter can fix connection issues on Windows. You can do this using the Advanced network options in Windows 11:

![Disable wireless connection in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-connection-1.jpg)

1. Right-click on the Network icon located in the System Tray.
2. Click on**Network and Internet settings** .
3. Click on**Advanced network settings** .
4. On the next window, choose**More network adapter options** .
5. Now, right-click the wireless adapter and click on**Disable** .
6. Wait for a moment, then right-click the wireless adapter and choose**Enable** .
7. Reboot your PC and try reconnecting to the network.

## 6\. Release the IP and Flush the DNS Cashe in Command Prompt

 The "Windows can't connect to this network" error can be due to an IP error. To fix this, you'll need to release the IP and flush the DNS cache.

 This may sound complex, but all you need to do is run a few commands in the Windows Command Prompt, and Windows will handle the rest. Here's how to do that:

![Flush the DNS cache](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-command-1.jpg)

1. Type**cmd** in Windows Search.
2. Right-click on**Command Prompt > Run as administrator** .
3. In the Command Prompt console, type the following commands and press**Enter** after each one:  
   * netsh winsock reset  
   * netsh int ip reset  
   * ipconfig /release  
   * ipconfig /renew  
   * ipconfig /flushdns
4. Close Command Prompt and reboot your computer to see if the error is still there.

## 7\. Reset Windows' Network Configuration

 One of the most common culprits of the "Windows cannot connect to this network" error is an improper network configuration. An easy way to fix this is to simply reset your PC's network settings to the factory default.

 Fortunately, Windows allows you to reset all its network settings with a single option:

![Network settings in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-1.jpg)

1. Right-click on the**Start** button and head to**Settings** .
2. Click on the**Network & internet** option on the navigation bar towards the left.
3. In the next window, choose**Advanced network settings** .
4. Under More settings, click on**Network reset** .
5. Click on**Reset now** .
6. Your PC will reboot.

## 8\. Turn Airplane Mode On and Off

 This quick trick might be enough to solve your network issues. By turning on Airplane mode, you instruct Windows to completely disconnect from all networks. This allows you to re-establish a stable connection once you disable Airplane mode.

 Open Windows Action Center and click on the Airplane mode tile. Wait a couple of minutes and turn it off. Then, try to reconnect to your network.

 If Airplane Mode is missing from Action Center, there are other ways to enable and disable it.

## 9\. Use the Network Troubleshooter

 Windows 11 has an in-built troubleshooter to detect and fix network issues. It may be worth a try to see if the utility can detect and fix the issue causing the "Windows can't connect to this network" error.

To run the Windows Network Troubleshooter, follow these steps:

![Run network troubleshooter in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-troubleshooter-1.jpg)

1. In Windows Search, type**network troubleshooter** .
2. From the search results, click on the**Find and fix network problems** option.
3. Click on**Next** in the troubleshooter.
4. Windows will detect and attempt to fix connection issues on your PC

## 10\. Forget and Reconnect the Wi-Fi Network

 If you get the network connectivity error when trying to connect to certain networks, you should have Windows forget them.

![Forget wi-fi networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/forget-wi-fi-network-1.jpg)

 Here’s how you can manage every network that you have connected to:

1. Open Windows Settings.
2. Go to**Network & internet > Wi-Fi** .
3. Select**Manage known networks** .
4. Click the**Forget** button next to the network that you can’t connect to.
5. Now, reconnect to the Wi-Fi. You will have to re-enter the password.

## 11\. Restart or Reset the Router

 Sometimes your router gets a little stuck and requires a reboot to sort itself out again. As such, giving your router a quick reset is a good way to quickly and easily [fix an unstable Wi-Fi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) .

 The method for resetting a router will vary depending on what model router you own. However, there is usually a physical power button on the router itself that you can use to turn it off and on again. If not, you can also access the router's configuration page and reboot it from there.

 Failing that, you can try restoring the router to factory defaults, either via a button on the router or on its configuration page. However, you'll have to reconfigure the router after resetting it.

## 12\. Use an Ethernet Cable

 If you’ve tried anything on the list without any success, and you don’t have time to go through more time-consuming solutions such as installing a big Windows update or loading a restore point, there’s one quick fix. Connect to the network using an [Ethernet cable](https://www.makeuseof.com/what-is-an-ethernet-cable/) .

 Not only will it fix the issue, but Ethernet cables are more reliable and will offer better speeds.

## The "Windows Can't Connect to This Network" Error, Now Fixed

 Most likely, one of these fixes will resolve the "Windows can't connect to this network" error on your computer. And given how many Windows network issues can crop up, it's a good idea to learn the basics of resolving them so you're not stuck without the internet in the future.

 Once you fix the connectivity issue, you can focus on increasing the internet speed in Windows 11.


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
<li><a href="https://win11.techidaily.com/uncomplicated-linux-use-without-wsl/"><u>Uncomplicated Linux Use Without WSL</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hyper-v-error-0x8009030e/"><u>Overcoming Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-savings-with-windows-11-pro-secure-top-deals/"><u>Maximize Savings with Windows 11 Pro: Secure Top Deals</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-superstars-with-a-subscriber-base/"><u>In 2024, Superstars with a Subscriber Base</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-intelligence-of-microsofts-marketplace/"><u>Navigating the Intelligence of Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-windows-11-harnessing-background-blur-in-photos-app/"><u>Masterful Windows 11: Harnessing Background Blur in Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/end-of-windows-subsystem-preparing-for-androids-future/"><u>End of Windows Subsystem: Preparing For Android's Future</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-older-directx-applications-through-dxvk-transformation/"><u>Bolstering Older DirectX Applications Through DXVK Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-spiritual-command-center-of-windows-11-os/"><u>Unlocking The Spiritual Command Center of Windows 11 OS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-9-reasons-to-favor-pc-computing-over-macos/"><u>The Top 9 Reasons to Favor PC Computing Over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/cpu-age-determination-for-pc-users-8-effective-methods/"><u>CPU Age Determination for PC Users: 8 Effective Methods</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-xs-to-other-iphone-11-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone XS to other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-1111/"><u>How to Install Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/paperless-posting-essential-notebook-replacements-for-windows/"><u>Paperless Posting: Essential Notebook Replacements for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-start-experience-no-more-ads-in-w11/"><u>The Ultimate Start Experience: No More Ads in W11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-win11-powertoys-experience/"><u>Unveiling the Win11 PowerToys Experience</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-and-redo-store-registrations-in-win-11/"><u>How to Reset and Redo Store Registrations in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-app-install-failure-on-microsofts-marketplace/"><u>Addressing App Install Failure on Microsoft's Marketplace</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-top-virtual-recording-tools-online-for-2024/"><u>[New] Top Virtual Recording Tools Online for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-top-5-driving-and-race-replicas/"><u>[Updated] Top 5 Driving & Race Replicas</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-purify-videos-premium-mark-removal-apps-iosandroid/"><u>[Updated] Purify Videos  Premium Mark-Removal Apps iOS/Android</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-up-advanced-security-features-ms-defender-aguard-for-windows-11-edge/"><u>How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-cross-language-interactions-with-keyboard-shortcuts-on-windows-11/"><u>Enhance Cross-Language Interactions with Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-route-to-purchase-adobe-reader-in-microsoft-marketplace/"><u>Quick Route to Purchase Adobe Reader in Microsoft Marketplace</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/simplified-tiktok-video-extraction-to-mp4-format/"><u>Simplified TikTok Video Extraction to MP4 Format</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-complete-breakdown-enhancing-your-experience-with-advanced-mobizen-techniques/"><u>[Updated] 2024 Approved  Complete Breakdown  Enhancing Your Experience with Advanced Mobizen Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-compatibility-checklist-tool/"><u>Navigating Windows 11'S Compatibility Checklist Tool</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-mcuicnt-file-access-problem-on-pcs/"><u>Mitigating McUICnt File Access Problem on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/handling-the-mysterious-windows-subsystem-for-linux-error-4294967295/"><u>Handling the Mysterious Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-newcomers-primer-to-av1-codecs-for-2024/"><u>A Newcomer’s Primer to AV1 Codecs for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-masterful-moment-captures-with-expert-photo-frames-online/"><u>[Updated] Masterful Moment Captures with Expert Photo Frames Online</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamline-your-thumbnail-design-journey-today/"><u>In 2024, Streamline Your Thumbnail Design Journey Today</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-invalid-identifier-error-in-win11/"><u>Guide to Correct 'Invalid Identifier' Error in Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-samsung-galaxy-a14-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Samsung Galaxy A14 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-savings-black-friday-6e2-win10-forever/"><u>Unmatched Savings: Black Friday - $6E2 (Win10) Forever</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-lighten-load-time-for-epic-games-on-windows/"><u>How to Lighten Load Time for Epic Games on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-windows-11-registry-file-layout/"><u>Mastering the Windows 11 Registry File Layout</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-devices-performance-naturally-with-wintoys/"><u>Accelerate Your Device's Performance Naturally with WinToys</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-the-ultimate-guide-to-vimeo-record-features/"><u>In 2024, The Ultimate Guide to Vimeo Record Features</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-livestream-lifelines-combatting-common-interruption-issues-on-fb/"><u>[New] Livestream Lifelines  Combatting Common Interruption Issues on FB</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-in-windows-11-after-disruptions/"><u>Enhancing Wi-Fi Connectivity in Windows 11 After Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-utils-for-efficient-gpu-performance-testing/"><u>Top 6 Windows Utils for Efficient GPU Performance Testing</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/build-a-custom-facebook-coverage-for-2024/"><u>Build a Custom Facebook Coverage for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-the-maze-of-unspecified-obs-error-in-windows/"><u>Navigate Through the Maze of Unspecified OBS Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-stalled-win11-license-numbers/"><u>Breathing Life Into Stalled Win11 License Numbers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-unleash-your-inner-tech-wizard-xbox-one-snapshot-secrets-revealed-for-2024/"><u>[Updated] Unleash Your Inner Tech Wizard  Xbox One Snapshot Secrets Revealed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-setting-up-permanent-delete-on-your-windows-11-and-11-pcs/"><u>The Ultimate Guide to Setting up Permanent Delete on Your Windows 11 & 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/6-effective-techniques-to-resurrect-off-screen-windows-in-windows-11/"><u>6 Effective Techniques to Resurrect Off-Screen Windows in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-roadblocks-in-windows-app-functionality/"><u>Overcoming Common Roadblocks in Windows App Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-for-frozen-keys-in-snipping-tool/"><u>Immediate Solution for Frozen Keys in Snipping Tool</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlock-the-power-of-livestreaming-on-youtube-regardless-of-subscriber-numbers/"><u>[Updated] Unlock the Power of Livestreaming on YouTube, Regardless of Subscriber Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-repairing-disk-errors-issue-on-windows/"><u>How to Fix the Repairing Disk Errors Issue on Windows</u></a></li>
</ul></div>
