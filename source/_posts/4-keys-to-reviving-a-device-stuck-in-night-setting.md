---
title: 4 Keys to Reviving a Device Stuck in Night Setting
date: 2024-08-15T23:24:53.524Z
updated: 2024-08-16T23:24:53.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Keys to Reviving a Device Stuck in Night Setting
excerpt: This Article Describes 4 Keys to Reviving a Device Stuck in Night Setting
keywords: Night Mode Recovery,Fixing Device Dusk Halt,Unstick Devices at Nite,Restart Locked Settings,Revive Night Display,Reverse Dark Screen,Reactivate Nocturnal Mode
thumbnail: https://thmb.techidaily.com/a8faf3762ec0652876e641b0799340042cad57c242c2210395cb978ced6a8dea.jpg
---

## 4 Keys to Reviving a Device Stuck in Night Setting

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

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://visual-screen-recording.techidaily.com/new-pure-audio-on-mac-studio-overview/"><u>[New] Pure Audio on Mac  Studio Overview</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-streamlined-screencasting-experts-top-recommendations/"><u>[Updated] In 2024, Streamlined Screencasting  Experts' Top Recommendations</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-transforming-business-with-metaverse-ideas/"><u>2024 Approved  Transforming Business with Metaverse Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-boot-into-safe-mode-in-windows-11/"><u>6 Ways to Boot Into Safe Mode in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-signal-failures-windows-steam-fix-guide/"><u>Addressing Signal Failures: Windows Steam Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-login-validity-and-failures/"><u>Assessing Windows Login Validity and Failures</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-to-troubleshoot-function-keys-in-win-11/"><u>Fix: Guide to Troubleshoot Function Keys in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-ordering-clumped-taskbar-icons/"><u>Guidelines for Ordering Clumped Taskbar Icons</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-infinix-smart-8-hd-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Infinix Smart 8 HD Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-stuttering-in-warhammer-40000-boltgun-on-windows/"><u>How to Fix Stuttering in Warhammer 40,000: Boltgun on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-steam-cloud-error-in-windows/"><u>How to Fix the Steam Cloud Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-windows-11-wait-longer-when-shutting-down-if-you-have-running-tasks/"><u>How to Make Windows 11 Wait Longer When Shutting Down if You Have Running Tasks</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-oppo-a59-5g-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Oppo A59 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-temporarily-turn-off-your-pcs-firewall/"><u>How to Temporarily Turn Off Your PC's Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-linux-capabilities-on-windows-10/"><u>How to Unlock Linux Capabilities on Windows 10</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-joyfuljourney-sign-up-share-and-create-fun-videos/"><u>In 2024, JoyfulJourney  Sign Up, Share and Create Fun Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-live-on-air-how-to-broadcast-on-youtube-and-twitch-using-obs/"><u>In 2024, Live on Air  How to Broadcast on YouTube & Twitch Using OBS</u></a></li>
<li><a href="https://win11.techidaily.com/innovation-at-your-fingertips-windows-erase-feature/"><u>Innovation at Your Fingertips: Window's Erase Feature</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-compression-command-prompt-and-powershell-techniques/"><u>Mastering File Compression: Command Prompt & PowerShell Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-unraveling-the-sixest-methods-for-copying-file-and-folders-locations/"><u>Mastering Windows 11: Unraveling the Sixest Methods for Copying File & Folders' Locations</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-configuring-multimonitors-in-win11/"><u>Maximize Productivity: Configuring Multimonitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-save-errors-in-windows/"><u>Overcoming Unauthorized Save Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-qt-engine-initialization-problem-in-software/"><u>Rectifying Qt Engine Initialization Problem in Software</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-gpu-settings-on-windows-11-pcs/"><u>Revitalize GPU Settings on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-access-tackling-onedrive-logins-in-windows/"><u>Reviving Access: Tackling OneDrive Logins in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-desktop-efficiency-with-wmdesk/"><u>Revolutionize Desktop Efficiency with WmDesk</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-image-snap-shot-size/"><u>Setting Up Your Image Snap Shot Size</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/short-video-showdown-comparing-success-on-youtubes-vs-tiktok-for-2024/"><u>Short Video Showdown  Comparing Success on YouTubes Vs. TikTok for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-ram-cache-cleanse-procedures/"><u>Step-by-Step: Windows RAM Cache Cleanse Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-windows-1011-automatic-file-deletion/"><u>Streamlining Storage: Windows 10/11 Automatic File Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-top-windows-11-challenges-with-ease/"><u>Tackling Top Windows 11 Challenges with Ease</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-motorola-razr-40-ultra-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Motorola Razr 40 Ultra Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-down-excessive-ntoskrnlexe-utilization/"><u>Trimming Down Excessive Ntoskrnl.exe Utilization</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-and-repair-your-fortnite-audio-issues-today-a-comprehensive-tutorial/"><u>Troubleshoot & Repair Your Fortnite Audio Issues Today - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-errors-in-windows-installer/"><u>Understanding and Resolving Errors in Windows Installer</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-gateway-command-windows-11s-appsunlocked/"><u>Unlock the Gateway: Command Windows 11'S AppsUnlocked</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Xiaomi Redmi Note 13 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-xiaomi-14-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-h2-update-rolls-out-more-options/"><u>Windows 11 H2 Update Rolls Out More Options</u></a></li>
</ul></div>
