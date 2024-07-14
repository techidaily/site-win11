---
title: Addressing Window Preview Failures in Win 8/10
date: 2024-07-13T10:56:57.742Z
updated: 2024-07-14T10:56:57.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Window Preview Failures in Win 8/10
excerpt: This Article Describes Addressing Window Preview Failures in Win 8/10
keywords: Windows View Failures,Win 8/10 Screen Issues,Window Preview Crashes,OS X Window Problems,Fixing Windows 8 Display,Resolving Win 10 Glitches,Overcoming View Errors
thumbnail: https://thmb.techidaily.com/66474ad3ea796bd372c3cdc425ee2c1b3cee0dd881c03ccdd13266e6df3b21d0.jpg
---

## Addressing Window Preview Failures in Win 8/10

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
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://network-issues.techidaily.com/fixing-inability-to-preserve-display-configuration-state/"><u>Fixing Inability to Preserve Display Configuration State</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-a54-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Samsung Galaxy A54 5G</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-key-strategies-for-gaining-facebooks-top-marker/"><u>[New] Key Strategies for Gaining Facebook's Top Marker</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-windows-photo-workflow-with-keys/"><u>Optimizing Your Windows Photo Workflow with Keys</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-ultimate-playbook-capturing-ps3-game-highlights-for-2024/"><u>[Updated] The Ultimate Playbook  Capturing PS3 Game Highlights for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-vanishing-battery-time-indicator-in-windows-11/"><u>How to Fix the Vanishing Battery Time Indicator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-insufficient-vram-for-enchanted-learning-environment/"><u>Tackling Insufficient VRAM for Enchanted Learning Environment</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/navigating-through-youtubes-challenging-green-screen/"><u>Navigating Through YouTube's Challenging Green Screen</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-the-primary-web-portal-on-w11/"><u>Modifying the Primary Web Portal on W11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-utilize-copy-features-with-edge-protector-win11/"><u>Methods to Utilize Copy Features with Edge Protector, Win11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-to-make-your-choice-easier-from-thousands-of-software-i-am-listing-the-top-five-in-the-businesslet-us-go-over-the-specifications-and-shed-/"><u>New 2024 Approved To Make Your Choice Easier From Thousands of Software I Am Listing the Top Five in the business.Let Us Go over the Specifications and Shed Light on the Comparisons</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-cmd-skills-with-these-20-must-learn-commands/"><u>Boost Your CMD Skills with These 20 Must-Learn Commands</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-frontiers-in-3d-visualization-tech/"><u>In 2024, Frontiers in 3D Visualization Tech</u></a></li>
<li><a href="https://win11.techidaily.com/from-here-to-innovation-the-post-11-windows-journey/"><u>From Here to Innovation: The Post-11 Windows Journey</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-efficiency-essential-strategies-for-windows-11-users/"><u>Mastering Efficiency: Essential Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-frozen-discord-overlay-on-your-windows-system/"><u>Combat the Frozen Discord Overlay on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/learn-mouse-gesture-tricks-in-microsofts-modern-edge-browser/"><u>Learn Mouse Gesture Tricks in Microsoft's Modern Edge Browser</u></a></li>
<li><a href="https://win11.techidaily.com/re-enabling-razer-device-discovery-on-win1011/"><u>Re-Enabling Razer Device Discovery on Win10/11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/finding-the-absent-hypervisor-fix-for-xc0351000-error/"><u>Finding the Absent Hypervisor - Fix for XC0351000 Error</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-add-on-of-portable-software-to-windows-oses/"><u>Seamless Add-On of Portable Software to Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-calendar-game-with-personalization-tips-on-a-windows-pc/"><u>Step Up Your Calendar Game with Personalization Tips on a Windows PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-investing-successfully-with-a-makeup-channel/"><u>[Updated] Investing Successfully with a Makeup Channel</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-trick-turn-off-nvidias-visual-effects/"><u>Command Line Trick: Turn Off NVIDIA's Visual Effects</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-use-windows-11s-home-space/"><u>How to Access and Use Windows 11'S Home Space</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-0x80860010-a-guide-to-fixes-for-windows/"><u>Navigating Through The 0X80860010: A Guide to Fixes for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-powertoys-top-10-must-have-features/"><u>Boosting Productivity: PowerToys' Top 10 Must-Have Features</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-external-access-to-insider-developer-sets/"><u>Preventing External Access to Insider Developer Sets</u></a></li>
<li><a href="https://win11.techidaily.com/creating-harmony-between-android-tablets-and-windows-11-desktops/"><u>Creating Harmony Between Android Tablets and Windows 11 Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/explore-win-11s-top-ranked-to-do-list-software-selections/"><u>Explore Win 11'S Top-Ranked To-Do List Software Selections</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-hover-over-sensitivity-and-trail-in-windows-11/"><u>Perfect Your Hover Over Sensitivity and Trail in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtubes-golden-rule-for-profit-partnership/"><u>[Updated] YouTube's Golden Rule for Profit Partnership</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011-ad-ds-printer-errors-effectively-and-efficiently/"><u>Addressing Win 10/11 AD DS Printer Errors Effectively and Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-non-genuine-adobe-app-warning/"><u>Prevent Non-Genuine Adobe App Warning</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/mastering-text-in-visuals-the-top-5-tips-for-tiktok-captions/"><u>Mastering Text in Visuals  The Top 5 Tips for TikTok Captions</u></a></li>
</ul></div>
