---
title: "Leading Edge of Power Management: Max & Min States"
date: 2024-09-05T08:37:47.356Z
updated: 2024-09-06T08:37:47.356Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Leading Edge of Power Management: Max & Min States"
excerpt: "This Article Describes Leading Edge of Power Management: Max & Min States"
keywords: Power State Leadership,Energy Efficiency Peak,Optimal Power Control,Max/Min Energy States,Advanced Battery Management,Energy Minimization Strategies,Power Maximization Techniques
thumbnail: https://thmb.techidaily.com/8823459ab6574b19c976d6905c67df41ee5da35193b7ba8be663bba21950e5e8.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Leading Edge of Power Management: Max & Min States

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115945/19272" target="_top" id="2115945">
  <img src="//a.impactradius-go.com/display-ad/19272-2115945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115945/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-discovering-facebooks-quintessential-updates/"><u>[New] 2024 Approved  Discovering Facebook's Quintessential Updates</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-the-ultimate-guide-to-trending-youtubers/"><u>[New] In 2024, The Ultimate Guide to Trending YouTubers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-srt-to-sub-pivotal-approaches-for-content-transformation/"><u>[New] SRT to SUB  Pivotal Approaches for Content Transformation</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-perfect-text-animation-for-tiktok-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Perfect Text Animation for TikTok  A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-7-proven-strategies-for-astonishing-ig-films/"><u>[Updated] 7 Proven Strategies for Astonishing IG Films</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-behind-the-mascara-youtubes-top-makeup-artists-unveiled-for-2024/"><u>[Updated] Behind the Mascara  YouTube's Top Makeup Artists Unveiled for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-download-your-favorite-videos-without-limits-for-2024/"><u>[Updated] Download Your Favorite Videos Without Limits for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-screenshot-on-snapchat-without-them-knowing-5-ways-for-2024/"><u>[Updated] How to Screenshot on Snapchat without Them Knowing  5 Ways for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-igtv-video-sharing-to-facebook-explained-in-3-ways-for-2024/"><u>[Updated] IGTV Video Sharing to Facebook Explained in 3 Ways for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-masterclass-guide-top-free-apps-for-iphone-and-ipad-edits/"><u>[Updated] In 2024, Masterclass Guide  Top Free Apps for iPhone & iPad Edits</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-the-perfect-pixel-a-guide-to-captivating-pc-gaming-moments/"><u>[Updated] In 2024, The Perfect Pixel  A Guide to Captivating PC Gaming Moments</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-open-access-mindful-harmonies-for-2024/"><u>[Updated] Open Access Mindful Harmonies for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-selections-of-the-year-best-snowboard-and-ski-cams/"><u>2024 Approved  Selections of the Year  Best Snowboard & Ski Cams</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-conversion-guide-youtube-to-igtv/"><u>2024 Approved  The Ultimate Conversion Guide  YouTube to IGTV</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-loss-the-top-8-windows-recovery-tips/"><u>Avoiding Loss: The Top 8 Windows Recovery Tips</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-samsung-galaxy-f54-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Samsung Galaxy F54 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/cod-black-ops-cold-war-fixed-resolve-error-code-80070057-now/"><u>Cod: Black Ops Cold War Fixed - Resolve Error Code 80070057 Now</u></a></li>
<li><a href="https://win11.techidaily.com/comprehending-winservicesexe-for-effective-troubleshooting/"><u>Comprehending Winservices.exe for Effective Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-error-0x8e00c/"><u>Correcting Windows Update Failure (Error 0X8e00c)</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-repairing-the-application-failed-to-launch-code-0xc000003e-on-win11/"><u>Deciphering and Repairing The Application Failed to Launch: Code 0XC000003E on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-11s-net-settings/"><u>Delving Into Windows 11'S Net Settings</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-windows-11-taskbars-task-view-control/"><u>Disguising Windows 11 TaskBar's Task View Control</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11-update-failure-code-0x800f0922/"><u>Eliminating Windows 11 Update Failure - Code 0X800f0922</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-thunderbolt-driver-downloads-for-windows-10-and-11-systems/"><u>Free Thunderbolt Driver Downloads for Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-off-virtualization-on-windows-11/"><u>How to Switch Off Virtualization on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unmute-yourself-on-google-meet-windows-edition/"><u>How to Unmute Yourself on Google Meet, Windows Edition</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-breaking-boundaries-with-6-top-rated-nft-services/"><u>In 2024, Breaking Boundaries with 6 Top-Rated NFT Services</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expertly-edited-entries-anywhere-at-the-tap-of-a-finger-in-2e23/"><u>In 2024, Expertly Edited Entries, Anywhere at the Tap of a Finger in 2E23</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-apple-iphone-xs-data-to-iphone-12-a-complete-guide-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Apple iPhone XS Data to iPhone 12 A Complete Guide | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-knowledge-keepers-premier-10-tools-to-record-teaching-sessions/"><u>In 2024, Knowledge Keepers  Premier 10 Tools to Record Teaching Sessions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-timing-of-youtube-earnings-a-closer-insight/"><u>In 2024, Timing of YouTube Earnings  A Closer Insight</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlock-creative-potential-with-10-best-backdrop-modification-software/"><u>In 2024, Unlock Creative Potential with 10 Best Backdrop Modification Software</u></a></li>
<li><a href="https://win11.techidaily.com/mending-failed-volume-backup-in-microsoft-os/"><u>Mending Failed Volume Backup in Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-git-branches-using-github-desktop-in-win-11/"><u>Navigating Git Branches Using GitHub Desktop in Win 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-your-next-purchase-playstation-portables-cost-hardware-specs-and-launch-details/"><u>Navigating Your Next Purchase: PlayStation Portable's Cost, Hardware Specs & Launch Details</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-collaboration-and-efficiency-master-these-5-innovative-window-tips/"><u>Optimize Collaboration and Efficiency: Master These 5 Innovative Window Tips</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-freeze-fixing-error-0x887a0006/"><u>Overcoming Device Freeze: Fixing Error 0X887A0006</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-file-organization-skills-in-windows-11-edition/"><u>Perfect Your File Organization Skills in Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-windows-blue-screen-due-to-not-handled-errors/"><u>Preventing Windows Blue Screen Due to Not Handled Errors</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-handle-user-profile-errors-in-w11os/"><u>Quick Fixes to Handle User Profile Errors in W11OS</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-inconsistent-windows-thx-audio-output/"><u>Rectifying Inconsistent Windows THX Audio Output</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11s-video-conferencing-snag-code-1132/"><u>Rectifying Windows 11'S Video Conferencing Snag: Code 1132</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-ios-images-errors-when-importing-to-windows-os/"><u>Resolving iOS Images Errors When Importing to Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unauthorized-user-profile-issue-in-windows/"><u>Resolving Unauthorized User Profile Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-effect-of-zoom-failure-1132-in-windows-11/"><u>Reversing the Effect of Zoom Failure #1132 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-code-0x0000004e-on-pcs/"><u>Solutions for Correcting Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-reactivating-closed-nvidia-cp-win-11/"><u>Strategies for Reactivating Closed Nvidia CP, Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-recalibration-windows-update-restart-guide/"><u>Streamlining System Recalibration: Windows Update Restart Guide</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-math-behind-making-money-youtubes-viewer-insights/"><u>The Math Behind Making Money  YouTube’s Viewer Insights</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-resurrecting-non-operative-resource-monitors-in-win11/"><u>Tips & Tricks for Resurrecting Non-Operative Resource Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-strategies-for-a-more-efficient-windows-11-search-experience/"><u>Top 5 Strategies for a More Efficient Windows 11 Search Experience</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-the-invisible-how-to-check-pc-security-manually/"><u>Uncover the Invisible: How to Check PC Security Manually</u></a></li>
<li><a href="https://win11.techidaily.com/ungroup-taskbar-on-win-11-simple-steps/"><u>Ungroup Taskbar on Win 11 - Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-high-fidelity-audio-dolby-atmos-integration-steps/"><u>Unlocking High-Fidelity Audio: Dolby Atmos Integration Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-more-secure-future-with-windows-11s-updated-support-schedule/"><u>Unveiling More Secure Future With Windows 11'S Updated Support Schedule</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-arm-installation-made-simple-via-iso-download-guide/"><u>Windows 11 ARM Installation Made Simple via ISO Download Guide</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-13c-5g-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Xiaomi Redmi 13C 5G Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
</ul></div>
