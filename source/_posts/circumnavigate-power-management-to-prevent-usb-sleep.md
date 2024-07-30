---
title: Circumnavigate Power Management to Prevent USB Sleep
date: 2024-07-29T15:51:22.810Z
updated: 2024-07-30T15:51:22.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Circumnavigate Power Management to Prevent USB Sleep
excerpt: This Article Describes Circumnavigate Power Management to Prevent USB Sleep
keywords: USB Sleep Prevention,Power Management Circumnavigate,Circumnavigate Power Control,USB Efficiency Optimization,Power Loss Avoidance,System Sleep Mitigation,Battery-Saving Techniques,Prevent USB Sleep,Optimize USB Efficiency,Avoid System Loss,Mitigate Power Sleeps,Enhance Battery Life
thumbnail: https://thmb.techidaily.com/20c1b79c602928e68eb827f2805a2d6c02102230fc6f02657f8a03a2a51b45e9.jpg
---

## Circumnavigate Power Management to Prevent USB Sleep

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-simplified-game-video-capture-via-nvidia/"><u>[New] 2024 Approved  Simplified Game Video Capture via NVIDIA</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-effortless-multichannel-publishing-tweets-plus-tumbles/"><u>[New] Effortless Multichannel Publishing  Tweets + Tumbles</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-essential-recording-steps-in-gh/"><u>[New] Essential Recording Steps in GH</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-quick-and-fun-make-a-meme-with-kinemaster/"><u>[New] Quick & Fun  Make a Meme with KineMaster</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-the-full-potential-of-iphones-hdr-capabilities/"><u>[New] Unlocking the Full Potential of iPhone's HDR Capabilities</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagram-integrity-at-stake-with-artificial-approvals/"><u>[Updated] 2024 Approved  Instagram Integrity at Stake with Artificial Approvals</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-precisionsync-analyst-perspectives/"><u>[Updated] 2024 Approved  PrecisionSync Analyst Perspectives</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-beyond-flat-canvas-elevating-text-to-new-heights/"><u>[Updated] Beyond Flat Canvas  Elevating Text to New Heights</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-content-game-perfectly-tailored-youtube-shorts-thumbnails-for-2024/"><u>[Updated] Elevate Your Content Game  Perfectly Tailored YouTube Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-basics-to-advanced-the-hand-trackers-playbook/"><u>[Updated] From Basics to Advanced  The Hand Tracker's Playbook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-privacy-focused-instagram-story-insight-methodology/"><u>[Updated] In 2024, Privacy-Focused Instagram Story Insight Methodology</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-potential-secrets-for-career-growth-in-designing/"><u>[Updated] Unleash Potential  Secrets for Career Growth in Designing</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-capturing-desktop-anytime-on-windows/"><u>2024 Approved  Capturing Desktop, Anytime on Windows</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-elite-transcribers-for-youtube-clips/"><u>2024 Approved  Elite Transcribers for YouTube Clips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-explore-and-master-group-communication-using-zoom-on-phone/"><u>2024 Approved  Explore & Master Group Communication  Using Zoom on Phone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-step-by-step-guide-to-instant-signature-bg-removal/"><u>2024 Approved  Step-by-Step Guide to Instant Signature Bg Removal</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-the-essential-guide-to-snap-mastery/"><u>2024 Approved  The Essential Guide to Snap Mastery</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-ultimate-voice-memo-reference-manual/"><u>2024 Approved  The Ultimate Voice Memo Reference Manual</u></a></li>
<li><a href="https://win11.techidaily.com/best-lighter-browsing-options-tested-for-memory-conservation/"><u>Best Lighter Browsing Options Tested For Memory Conservation</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-journey-10-key-windows-store-tools/"><u>Boost Your Journey: 10 Key Windows Store Tools</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-in-window-systems-reliability-vs-performance/"><u>Bridging Gaps in Window Systems: Reliability Vs. Performance</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-icon-badges-non-display-issue/"><u>Counteracting Icon Badges Non-Display Issue</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-0x800713f-issue-for-smooth-function-of-win11s-mail-app/"><u>Decoding 0X800713F Issue for Smooth Function of Win11's Mail App</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-steps-to-initiate-system-restore-on-windows-11/"><u>Decoding the Steps to Initiate System Restore on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-disastrous-dism-0x800f082f-error/"><u>Demystifying Windows' Disastrous DISM 0X800F082F Error</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-users-with-precision-four-easy-techniques-on-win11/"><u>Disabling Users with Precision: Four Easy Techniques on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-voice-over-on-microsofts-document-reader/"><u>Fixing Inactive Voice-Over on Microsoft's Document Reader</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-low-memory-warning-in-vmware-hosted-windows-environments/"><u>Fixing Low Memory Warning in VmWare-Hosted Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-inability-to-connect-error-for-malwarebytes-on-win11/"><u>Fixing the Inability to Connect Error for Malwarebytes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/forecasting-with-finesse-windows-11s-prime-weather-tools/"><u>Forecasting with Finesse: Windows 11'S Prime Weather Tools</u></a></li>
<li><a href="https://win11.techidaily.com/handling-virtualbox-usb-disconnect-issues-effectively-on-windows/"><u>Handling VirtualBox USB Disconnect Issues Effectively on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-12-mini-learn-all-4-methods-drfone-by-drfone-ios/"><u>How Do You Unlock your Apple iPhone 12 mini? Learn All 4 Methods | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-honor-x9b-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Honor X9b Quickly? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-an-mp4-on-galaxy-a24-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How to play an MP4 on Galaxy A24?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-embracing-the-world-one-post-at-a-time-with-insta-captions/"><u>In 2024, Embracing the World, One Post at a Time with Insta Captions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-smooth-soundscape-fading-techniques-with-lumafusion/"><u>In 2024, Smooth Soundscape  Fading Techniques with Lumafusion</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-indispentiall-10-must-have-ms-store-tools/"><u>Innovative Indispentiall: 10 Must-Have MS Store Tools</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-ai-assistance-in-development-an-introduction-to-microsoft-copilot/"><u>Leveraging AI Assistance in Development: An Introduction to Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-edges-cpu-load-a-user-guide/"><u>Lowering Edge's CPU Load: A User Guide</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-reset-windows-11-search-bar-aesthetics/"><u>Method to Reset Windows 11 Search Bar Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-interface-effective-process-filtering-and-customizing-themes-in-w11/"><u>Navigating the Interface: Effective Process Filtering & Customizing Themes in W11</u></a></li>
<li><a href="https://win11.techidaily.com/no-more-grouped-taskbars-win-11-edition/"><u>No More Grouped Taskbars: Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-isdonedll-isarcextract-failures/"><u>Overcoming Common ISDone.dll (ISArcExtract) Failures</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-systemsettings-crashes-in-windows-11/"><u>Overcoming SystemSettings Crashes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-system-sounds-in-windows-11-by-activating-mixer-feature/"><u>Perfect System Sounds in Windows 11 by Activating Mixer Feature</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-window-11-dual-screen-usage/"><u>Perfecting Window 11 Dual Screen Usage</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/prime-facebook-extra-tools-secure-file-grabber-firefox-version-for-2024/"><u>Prime Facebook Extra Tools  Secure File Grabber, Firefox Version for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-to-try-connections-glitch-on-windows-pcs/"><u>Quick Fix to 'Try Connections' Glitch on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-mending-windows-hello-fingerprint-issues/"><u>Quick Steps for Mending Windows Hello Fingerprint Issues</u></a></li>
<li><a href="https://iphone-location.techidaily.com/quick-steps-to-change-weather-location-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Quick Steps to Change Weather Location on Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-disk-management-virtual-disk-hiccups/"><u>Rectifying Disk Management Virtual Disk Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-win-lol-initial-load-issue/"><u>Resolving Win: LOL Initial Load Issue</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-your-workflow-dragging-tabs-in-windows-11/"><u>Simplifying Your Workflow: Dragging Tabs in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/steps-for-deleting-discord-on-computermobile-for-2024/"><u>Steps for Deleting Discord on Computer/Mobile for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-address-non-signed-windows-update-files/"><u>Tactics to Address Non-Signed Windows Update Files</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-window-resolution-on-windows-11/"><u>Tailoring Window Resolution on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-link-between-edge-and-irrelevant-taskers/"><u>The Link Between Edge and Irrelevant Taskers</u></a></li>
<li><a href="https://win11.techidaily.com/top-benefits-of-windows-11-overtaking-macos/"><u>Top Benefits of Windows 11 Overtaking macOS</u></a></li>
<li><a href="https://video-capture.techidaily.com/transforming-online-meetings-choose-from-these-top-5-recorders-for-2024/"><u>Transforming Online Meetings  Choose From These Top 5 Recorders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-wsl-a-guide-to-windows-linux-integration/"><u>Turn on WSL: A Guide to Windows' Linux Integration</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-sound-experience-dolby-atmos-windows-install/"><u>Ultimate Sound Experience: Dolby Atmos Windows Install</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlocking-korean-mastery-the-top-6-online-linguistic-hubs/"><u>Unlocking Korean Mastery: The Top 6 Online Linguistic Hubs</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Realme C67 4G? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-path-top-10-pioneers-in-virtual-practice/"><u>Yogic Path  Top 10 Pioneers in Virtual Practice</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>