---
title: Addressing Non-Verified App Alerts for Windows Users
date: 2024-07-13T11:27:43.374Z
updated: 2024-07-14T11:27:43.374Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Non-Verified App Alerts for Windows Users
excerpt: This Article Describes Addressing Non-Verified App Alerts for Windows Users
keywords: WinAlertNonVerif,WindowsAppNotify,VerifyAlertWin,UnverifiedAppWin,NonVerifWIndes,AlertStatusCheck,AppWarningSignal
thumbnail: https://thmb.techidaily.com/3b4fc9801ceec8439e874198c6f456d3f60986d5a7e58819eb6db488dc36873e.jpg
---

## Addressing Non-Verified App Alerts for Windows Users

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/boosting-wired-internet-overcoming-100mbps-limit-in-windows/"><u>Boosting Wired Internet: Overcoming 100Mbps Limit in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/backup-basics-protecting-your-digital-adventures-in-epic-games/"><u>Backup Basics: Protecting Your Digital Adventures in Epic Games</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-realme-gt-5-pro-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-androids-favorite-is-pickup-superior-to-other-photo-editors/"><u>[Updated] In 2024, Android’s Favorite  Is PickUp Superior to Other Photo Editors?</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-mastering-the-search-function-of-windows-11/"><u>Boost Productivity: Mastering the Search Function of Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-vertical-by-design-optimizing-your-mobile-video-strategy/"><u>New In 2024, Vertical by Design Optimizing Your Mobile Video Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-the-new-search-feature-in-windows-11/"><u>Boost Productivity with the New Search Feature in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-essential-win11-and-cmd-commands/"><u>Boosting Productivity: Essential Win11 and Cmd Commands</u></a></li>
<li><a href="https://win11.techidaily.com/bolster-window-app-interactions-via-efficient-internet-accessing-methods/"><u>Bolster Window App Interactions via Efficient Internet Accessing Methods</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-savory-storytelling-in-video-cooking-top-7-insights/"><u>2024 Approved  Savory Storytelling in Video Cooking - Top 7 Insights</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/universal-unlock-pattern-for-realme-gt-neo-5-se-by-drfone-android/"><u>Universal Unlock Pattern for Realme GT Neo 5 SE</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-utility-of-windows-11s-initial-interface/"><u>Boosting the Utility of Windows 11'S Initial Interface</u></a></li>
<li><a href="https://win11.techidaily.com/boost-brainpower-proven-techniques-to-master-studying-on-windows/"><u>Boost Brainpower: Proven Techniques to Master Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-crashes-solving-0x80072f30-error/"><u>Avoiding Microsoft Store Crashes: Solving 0X80072F30 Error</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-directx-titles-with-dxvk-on-windows/"><u>Boosting Classic DirectX Titles with DXVK on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/intense-evaluation-the-detailed-study-of-bublcam-360/"><u>Intense Evaluation  The Detailed Study of Bublcam 360</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-making-the-most-of-both-worlds-tweeting-and-sending-videos-with-whatsapp/"><u>[Updated] Making the Most of Both Worlds  Tweeting & Sending Videos with WhatsApp</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-game-loading-times-for-epic-universe/"><u>Boosting Game Loading Times for Epic Universe</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-essential-steps-to-game-folder-opening/"><u>Break the Code: Essential Steps to Game Folder Opening</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-troubles-15-windows-fixes-to-consider/"><u>Arrow Troubles? 15 Windows Fixes to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-code-breakdowns-quick-windows-fixes/"><u>Breaking Free From Code Breakdowns: Quick Windows Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-unlicensed-adobe-errors/"><u>Avoid Windows 'Unlicensed' Adobe Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-value-dome-cams-affordable-360-filmmaking-tools/"><u>Top Value Dome Cams  Affordable 360° Filmmaking Tools</u></a></li>
<li><a href="https://win11.techidaily.com/beating-full-screen-freezes-and-crashes-in-sonic-games-on-w11-os/"><u>Beating Full-Screen Freezes and Crashes in Sonic Games on W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-media-player-for-a-streamlined-start/"><u>Activating Windows Media Player for a Streamlined Start</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-visual-quality-enable-win11s-color-adjustment/"><u>Boosting Visual Quality: Enable Win11's Color Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disruptions-to-wsl-after-installing-windows-11/"><u>Avoiding Disruptions to WSL After Installing Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-sony-xperia-1-v-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Sony Xperia 1 V Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-why-windows-dominates-in-gaming-landscape/"><u>Breaking Down Why Windows Dominates in Gaming Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unauthorized-user-error-on-windows-11-and-11/"><u>Avoiding Unauthorized User Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-nubia-red-magic-8s-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Nubia Red Magic 8S Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/banish-old-wallpaper-memories-triple-approach/"><u>Banish Old Wallpaper Memories: Triple Approach</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-in-win-11-with-top-7-essential-widgets/"><u>Boost Productivity in Win 11 with Top 7 Essential Widgets</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-htc-u23-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from HTC U23 to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-infrastructure-with-windows-software/"><u>Augmenting Linux Infrastructure with Windows Software</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-discover-how-these-15-advanced-facebook-gadgets-boost-e-commerce-sale-traffic/"><u>[Updated] In 2024, Discover How These 15 Advanced Facebook Gadgets Boost E-Commerce Sale Traffic</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-app-aesthetics-with-win11s-automatic-tuning/"><u>Boosting App Aesthetics with Win11's Automatic Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-update-autopilot-hurdles/"><u>Breaking Down Windows Update Autopilot Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/big-bulky-minipcs-with-brainy-bare-performance/"><u>Big, Bulky Minipcs with Brainy Bare Performance</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breach-are-windows-fingerprint-scanners-safe/"><u>Biometric Breach: Are Windows Fingerprint Scanners Safe?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-enable-quiet-youtube-bgplay-for-iphone-and-android/"><u>[New] Enable Quiet YouTube BGPlay for iPhone & Android</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-unveiling-the-strengths-and-weaknesses-of-presenter-8/"><u>[New] In 2024, Unveiling the Strengths and Weaknesses of Presenter 8</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-minipc-ample-storage-average-speed/"><u>Blackview MiniPC: Ample Storage, Average Speed</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-do-perfect-match-paint-100-the-easy-way/"><u>2024 Approved How to Do Perfect Match Paint 100 the Easy Way</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-the-thermal-load-of-windows-11-devices/"><u>Balancing the Thermal Load of Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-minipc-storage-space-speeds-still-sparse/"><u>Blackview MiniPC: Storage Space - Speeds Still Sparse</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-science-behind-catching-fire-on-instagram/"><u>[Updated] In 2024, The Science Behind Catching Fire on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/baffling-taskers-display-with-edge-and-others/"><u>Baffling Tasker's Display with Edge & Others</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-non-working-cut-and-paste-in-win-11/"><u>Ameliorating Non-Working Cut and Paste in Win 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-vanguard-firefox-recording-software-for-2024/"><u>[New] Vanguard FireFox Recording Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-energy-drain-auto-shutdown-at-idle-in-win11/"><u>Avoiding Energy Drain: Auto-Shutdown at Idle in Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>