---
title: Remedy Non-Functional Window Preview Issues
date: 2024-12-03T04:25:27.526Z
updated: 2024-12-07T11:04:54.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy Non-Functional Window Preview Issues
excerpt: This Article Describes Remedy Non-Functional Window Preview Issues
keywords: Fix Window View Problems,Clear Screen Glitches,Resolve Display Errors,Stop Preview Failures,End Vision Lags,Stop Windows Freeze,Eliminate Screenshots Issues
thumbnail: https://thmb.techidaily.com/d273051a98d6681ad00d9eef8a0a1e7b14cf2a7e1a69ef55a0c0753824f4548a.jpg
---

## Remedy Non-Functional Window Preview Issues

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/correcting-mcuicntexe-not-found-message-in-win-1011/"><u>Correcting McUICnt.exe Not Found Message in Win 10/11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exclusive-deal-save-on-the-smart-tp-link-tapo-video-doorbell-75-with-free-ai-and-no-hidden-charges-use-our-codes/"><u>Exclusive Deal: Save on the Smart TP-Link Tapo Video Doorbell ($75) with Free AI & No Hidden Charges – Use Our Codes!</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-lava-blaze-2-pro-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/fallout-4-and-pc-users-overcome-game-freezes-with-these-simple-solutions/"><u>Fallout 4 & PC Users: Overcome Game Freezes with These Simple Solutions</u></a></li>
<li><a href="https://games-able.techidaily.com/high-speed-monitors-at-240hz-for-gamers/"><u>High-Speed Monitors at 240Hz for Gamers</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Poco M6 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-google-pixel-fold-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Google Pixel Fold Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-upgrade-glitch-windows-11s-error-0x80246007/"><u>Swift Solution to Upgrade Glitch: Windows 11'S Error 0X80246007</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-prose-best-5-desktop-writing-helpers/"><u>Transform Your Prose: Best 5 Desktop Writing Helpers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-itel-p55plus-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-steams-internet-connection-on-windows/"><u>Unlocking Steam's Internet Connection on Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-the-potential-of-8-alternative-chatgpt-jobs-do-they-really-boost-your-income/"><u>Unlocking the Potential of 8 Alternative ChatGPT Jobs: Do They Really Boost Your Income?</u></a></li>
<li><a href="https://win11.techidaily.com/yule-joy-tech-treats-through-ms-store-purchases/"><u>Yule Joy: Tech Treats Through MS Store Purchases</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    