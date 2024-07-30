---
title: Bypassing Windows' Signature Checks for Easy Updates
date: 2024-07-29T15:53:13.256Z
updated: 2024-07-30T15:53:13.256Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Windows' Signature Checks for Easy Updates
excerpt: This Article Describes Bypassing Windows' Signature Checks for Easy Updates
keywords: Bypass Signature Update,Windows Quick Update,Skip Verification Process,Update Without Windows Signatures,Unblock Software Upgrades,Ease-Updater Compliance,Fast Windows Patching Methods
thumbnail: https://thmb.techidaily.com/796380b2f6e477c41fdb5986a336623e799bf688b4a29cd4a3d817de3e2d744c.jpg
---

## Bypassing Windows' Signature Checks for Easy Updates

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-cross-platform-soundtrack-strategy-for-facebook-profiles-for-2024/"><u>[New] Cross-Platform Soundtrack Strategy for Facebook Profiles for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-mastering-instagram-narratives-through-captioning/"><u>[Updated] 2024 Approved  Mastering Instagram Narratives Through Captioning</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-advanced-steps-a-compre-point-of-view-on-screen-record-with-adobe-captivate/"><u>[Updated] Advanced Steps  A Compre Point of View on Screen Record with Adobe Captivate</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-how-mycam-changes-video-recording-at-home-an-in-depth-review-for-2024/"><u>[Updated] How MyCam Changes Video Recording at Home – An In-Depth Review for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-easy-steps-to-save-youtube-videos/"><u>[Updated] In 2024, Easy Steps to Save YouTube Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-privacy-in-focus-the-leading-10-no-cost-highly-secured-video-calling-platforms/"><u>[Updated] In 2024, Privacy in Focus  The Leading 10 No-Cost, Highly-Secured Video Calling Platforms</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unleash-creative-fb-ad-videos-access-free-video-tools-now/"><u>[Updated] Unleash Creative FB Ad Videos - Access FREE Video Tools Now</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-visual-storytelling-of-pc-playtime-top-6-screenshot-secrets/"><u>[Updated] Visual Storytelling of PC Playtime - Top 6 Screenshot Secrets</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-effortless-resolution-of-macs-green-screen-problem-for-youtubers/"><u>2024 Approved  Effortless Resolution of Mac's Green Screen Problem for YouTubers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-myth-busting-realities-of-instagram-story-followers/"><u>2024 Approved  Myth-Busting  Realities of Instagram Story Followers</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-the-ultimate-list-of-10-vectors-stock-pics-websites/"><u>2024 Approved  The Ultimate List of 10 Vectors Stock Pics Websites</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-unleash-the-full-potential-of-your-live-streams-using-onestream/"><u>2024 Approved  Unleash the Full Potential of Your Live Streams Using OneStream</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-speed-up-secrets-eliminating-unwanted-sound-waves/"><u>2024 Approved Speed-Up Secrets Eliminating Unwanted Sound Waves</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-elite-selection-of-virtual-audio-editing-experts/"><u>2024 Approved The Elite Selection of Virtual Audio Editing Experts</u></a></li>
<li><a href="https://win11.techidaily.com/a-users-handbook-on-amplifying-mouse-cursor-lighting-on-win-11/"><u>A User's Handbook on Amplifying Mouse Cursor Lighting on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-file-error-xc10100bf/"><u>Addressing Windows File Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-shared-access-tools-google-vs-microsofts-nearby-sharing/"><u>Assessing Shared Access Tools: Google Vs. Microsoft's Nearby Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-emotions-easy-emoji-15-integration-for-win11/"><u>Avoid Missed Emotions: Easy Emoji 15 Integration for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-repeated-sign-in-alerts-team-collaboration-edition/"><u>Avoiding Repeated Sign-In Alerts: Team Collaboration Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-breakdown-an-insiders-approach/"><u>Blue Screen Breakdown: An Insider's Approach</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dual-users-conflict-with-one-ms-login/"><u>Bypassing Dual Users’ Conflict with One MS Login</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-custom-volume-control-commands-for-windows-11-users/"><u>Creating Custom Volume Control Commands for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-dual-camera-request-error-code-0xa00f4243/"><u>Dealing with Dual Camera Request Error (Code 0xA00F4243)</u></a></li>
<li><a href="https://extra-information.techidaily.com/drone-visual-spectrum-20-first-time-free-luts-included/"><u>Drone Visual Spectrum - 20 First-Time FREE LUTS Included</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visual-appeal-with-custom-pointer-design/"><u>Enhancing Visual Appeal with Custom Pointer Design</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-how-to-locate-and-utilize-hidden-windows-11-enhancements/"><u>Fix the Gap: How to Locate & Utilize Hidden Windows 11 Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute!</u></a></li>
<li><a href="https://video-capture.techidaily.com/greatest-7-web-based-recording-tools-2023-for-2024/"><u>Greatest 7 Web-Based Recording Tools 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-reviving-a-stuck-download-space-on-windows-os/"><u>Guide for Reviving a Stuck Download Space on Windows OS</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-samsung-galaxy-m34-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-10-leading-free-online-recording-tools-expert-opinions/"><u>In 2024, 10 Leading Free Online Recording Tools - Expert Opinions</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-fixes-to-solve-apple-iphone-13-pro-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve Apple iPhone 13 Pro Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-vivo-y200e-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Vivo Y200e 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-in-depth-analysis-of-youtube-adrevenue-average-payout-per-1000-viewers-engagement/"><u>In 2024, In-Depth Analysis of YouTube AdRevenue  Average Payout per 1,000 Viewers' Engagement</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-peak-of-primes-amazons-hot-tweets-and-shows-23/"><u>In 2024, The Peak of Primes  Amazon’s Hot Tweets & Shows, '23</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-video-vibrance-10-tips-for-dynamic-color-manipulation/"><u>In 2024, Video Vibrance  10 Tips for Dynamic Color Manipulation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-xiaomi-11-series-brings-cinema-quality-into-mobile-devices/"><u>In 2024, Xiaomi 11 Series Brings Cinema Quality Into Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-nooks-for-mac-address-in-windows-11/"><u>Navigating Network Nooks for Mac Address in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/next-gen-access-management-for-windows-administrators/"><u>Next-Gen Access Management for Windows Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-streaming-on-windows-counteracting-zero-speed-phenomenon/"><u>Optimize Streaming on Windows: Counteracting Zero-Speed Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-cannot-determine-error-on-windows-computers/"><u>Overcoming Cannot Determine Error on Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-package-registration-problems-in-windows-operating-system/"><u>Overcoming Package Registration Problems in Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-down-your-laptop-keyboard-with-simple-steps-in-win10win11/"><u>Quiet Down Your Laptop Keyboard with Simple Steps in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reconnecting-windows-remotes-resolving-unacceptable-links/"><u>Reconnecting Windows Remotes: Resolving Unacceptable Links</u></a></li>
<li><a href="https://win11.techidaily.com/reel-in-efficiency-with-these-premium-video-editors-on-window-11/"><u>Reel-In Efficiency with These Premium Video Editors on Window 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-disconnect-error-for-malwarebytes-services-in-windows-11/"><u>Remedying Disconnect Error for Malwarebytes Services in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-media-player-server-crashes/"><u>Remedying Media Player Server Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/repair-restore-function-keys-in-windows-11/"><u>Repair: Restore Function Keys in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-your-windows-backup-preferences/"><u>Resetting Your Windows Backup Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-seamless-link-for-windows-steam-streaming/"><u>Restoring Seamless Link for Windows Steam Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screen-interaction-proficient-use-of-windows-narrator-shortcuts/"><u>Streamlined Screen Interaction: Proficient Use of Windows Narrator Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-pc-finder-power-with-everythingapp/"><u>Supercharge PC Finder Power with EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-enabling-additional-av-software-on-windows/"><u>Techniques for Enabling Additional AV Software on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-nullifying-windows-tracking-mechanism/"><u>Techniques for Nullifying Windows' Tracking Mechanism</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/transforming-doubt-into-action-channeling-vlogger-excellence-for-2024/"><u>Transforming Doubt Into Action  Channeling Vlogger Excellence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-mute-reactivate-slack-alerts-in-win-11/"><u>Troubleshoot Mute: Reactivate Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-open-exes-without-issues/"><u>Troubleshooting Windows: Open EXEs Without Issues</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>