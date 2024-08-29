---
title: Overcoming Taskbar Buttons Display Problems
date: 2024-08-28T00:51:40.957Z
updated: 2024-08-29T00:51:40.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Taskbar Buttons Display Problems
excerpt: This Article Describes Overcoming Taskbar Buttons Display Problems
keywords: Fix Taskbar Glitches,Taskbar Button Issue Resolution,Correcting Taskbar Icons,Improve Taskbar Display,Eliminate Taskbar Errors,Enhance Taskbar UI,Tackle Buttons on Taskbar
thumbnail: https://thmb.techidaily.com/8c3061c39eb85dd875af824e1d1149fd13be54628fb79ee748ce5191efb525e2.jpg
---

## Overcoming Taskbar Buttons Display Problems

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-innovative-methods-for-mac-screenshot-format-change-for-2024/"><u>[New] Innovative Methods for Mac Screenshot Format Change for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-converting-in-meeting-google-meet-to-youtube-broadcasts-your-guide-for-2024/"><u>[Updated] Converting In-Meeting Google Meet to YouTube Broadcasts  Your Guide for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-decoding-the-magic-behind-seamless-musical-segments-for-2024/"><u>[Updated] Decoding the Magic Behind Seamless Musical Segments for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-decoding-the-visual-language-of-live-videos-on-youtube-for-2024/"><u>[Updated] Decoding the Visual Language of Live Videos on YouTube for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-elevate-your-visual-content-a-guide-to-videoleap-zooming/"><u>[Updated] Elevate Your Visual Content  A Guide to Videoleap Zooming</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-fb-flicks-grabber-tool/"><u>[Updated] FB Flicks Grabber Tool</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-step-by-step-perfecting-fbs-360-streams/"><u>[Updated] Step-by-Step  Perfecting FB's 360 Streams</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-deconstructing-sharex-and-its-challengers/"><u>2024 Approved  Deconstructing ShareX and Its Challengers</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-honor-x50-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Honor X50? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/easily-modify-windows-11-highlight-features/"><u>Easily Modify Windows 11 Highlight Features</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-game-optimal-adventure-play-in-full-hd-via-windows-and-scummvm/"><u>Elevate Your Gaming Game: Optimal Adventure Play in Full HD via Windows & ScummVM</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-pcs-space-top-7-free-volume-enhancers-for-windows/"><u>Elevate Your PC's Space: Top 7 Free Volume Enhancers for Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevating-your-iphone-photos-through-hdr-methods/"><u>Elevating Your iPhone Photos Through HDR Methods</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-exploring-and-expunging-windows-history/"><u>Essential Steps for Exploring and Expunging Windows History</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-filing-techniques-max-156/"><u>Essential Windows Filing Techniques (Max 156)</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-affordability-and-efficiency-in-wearables-the-fitbit-versa-unveiled/"><u>Exploring Affordability & Efficiency in Wearables: The Fitbit Versa Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/five-gone-windows-feature-retrospective/"><u>Five Gone: Windows Feature Retrospective</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-0x80070522-secure-privilege-protocol-in-windows/"><u>Fixing Error Code 0X80070522: Secure Privilege Protocol in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-discord-overlay-failure-a-step-by-step-guide/"><u>Fixing Windows Discord Overlay Failure: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-windows-11-screensaver-quickly/"><u>How to Sidestep Windows 11 Screensaver Quickly</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-legal-framework-the-fine-print-for-facebook-video-postings/"><u>In 2024, Legal Framework  The Fine Print for Facebook Video Postings</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-review-how-the-apple-iphone-xs-max-elevates-the-standard-for-top-tier-iphones/"><u>In-Depth Review: How the Apple iPhone XS Max Elevates the Standard for Top-Tier iPhones</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-repair-tool-access-crafting-shortcuts-for-win-1011/"><u>Mastering Repair Tool Access: Crafting Shortcuts for Win 10/11</u></a></li>
<li><a href="https://techidaily.com/mastering-the-art-of-effortless-screen-captures-in-windows-8/"><u>Mastering the Art of Effortless Screen Captures in Windows 8</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-win1110-store-issue-0x80072efd/"><u>Mastering the Resolution of Win11/10 Store Issue 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-ssd-capabilities-integrate-windows-and-fresh-optimization/"><u>Maximize SSD Capabilities: Integrate Windows & Fresh Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/mimicking-macos-layout-in-windows-5-essential-tweaks/"><u>Mimicking macOS Layout in Windows: 5 Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-high-load-on-cpu-by-wlanextexe/"><u>Mitigating High Load on CPU by Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-xbox-console-choices-and-installation/"><u>Navigating Xbox Console Choices and Installation</u></a></li>
<li><a href="https://win11.techidaily.com/playnite-enhancement-embracing-emulated-titles/"><u>Playnite Enhancement: Embracing Emulated Titles</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-errors-validating-windows-11-temporary-folder/"><u>Preventing Errors: Validating Windows 11 Temporary Folder</u></a></li>
<li><a href="https://win11.techidaily.com/propelling-linux-with-powerful-windows-integration/"><u>Propelling Linux with Powerful Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-windows-os-not-found-issue/"><u>Quick Guide to Resolve Windows OS Not Found Issue</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-input-devices-on-a-windows-system/"><u>Resolving Faulty Input Devices on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-diagnostics-error-on-pc/"><u>Solutions for Fixing 'Diagnostics Error' On PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-tweaking-proxy-settings-in-windows-11/"><u>Step-by-Step Guide to Tweaking Proxy Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-journey-through-original-diablo/"><u>Step-by-Step Journey Through Original Diablo</u></a></li>
<li><a href="https://program-issues.techidaily.com/the-definitive-fix-for-a-frozen-playstation-4-simple-troubleshooting-techniques/"><u>The Definitive Fix for a Frozen PlayStation 4: Simple Troubleshooting Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/the-hidden-dangers-opting-for-budgeted-windows-auth-keys/"><u>The Hidden Dangers: Opting for Budgeted Windows Auth Keys</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-affordable-drivers-to-elevate-your-windows-system/"><u>Top 5 Affordable Drivers to Elevate Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/top-strategies-for-a-smoothly-running-google-drive-in-windows/"><u>Top Strategies for a Smoothly Running Google Drive in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-windows-11-wallpaper-location-secret/"><u>Uncover Windows 11 Wallpaper Location Secret</u></a></li>
<li><a href="https://win11.techidaily.com/uninstalling-wsl-an-all-inclusive-guide/"><u>Uninstalling WSL: An All-Inclusive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-productivity-dragging-and-dropping-tabs-windows-11-style/"><u>Unleashing Productivity: Dragging and Dropping Tabs, Windows 11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/why-and-how-to-ditch-integrated-video-on-windows/"><u>Why and How to Ditch Integrated Video on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-slowdown-beneath-calm-exteriors-lurk-resource-hogging-tools/"><u>Windows 11 Slowdown: Beneath Calm Exteriors Lurk Resource Hogging Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>