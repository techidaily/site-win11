---
title: Fixing No Logging in Run Commands on PCs
date: 2024-07-13T10:52:14.433Z
updated: 2024-07-14T10:52:14.433Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing No Logging in Run Commands on PCs
excerpt: This Article Describes Fixing No Logging in Run Commands on PCs
keywords: Stop PC No-Log Commands,Disable Command Line Logout,Prevent Run Command Logouts,Halt Console No-Record Feature,Cease Ignored Terminal Events,Block Unlogged Command Execution,Quell Non-Logging Commands
thumbnail: https://thmb.techidaily.com/acc4624304fa10f6661dcbd0f5aeeaf72266dc48176909da6153f980695e7df6.png
---

## Fixing No Logging in Run Commands on PCs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://activate-lock.techidaily.com/full-guide-to-apple-iphone-13-mini-icloud-bypass-by-drfone-ios/"><u>Full guide to Apple iPhone 13 mini iCloud Bypass</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-design-youtube-introductory-videos-two-pathways/"><u>How to Design YouTube Introductory Videos  Two Pathways</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-xbox-mic-in-windows-11/"><u>Troubleshooting Non-Functional Xbox Mic in Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-vivo-t2x-5g-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-trending-on-twitter-unpacking-top-10-tiktok-videos/"><u>2024 Approved  Trending on Twitter  Unpacking Top 10 TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-screens-overcoming-windows-setup-woes/"><u>Secure Your Screens: Overcoming Windows Setup Woes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-combat-breakpoint-exception-error-in-windows/"><u>Solutions to Combat Breakpoint Exception Error in Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-streamlining-sound-a-look-at-the-best-5-directional-microphones-and-windshields/"><u>New 2024 Approved Streamlining Sound A Look at the Best 5 Directional Microphones and Windshields</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-no-cost-solutions-the-best-free-online-video-merger-options/"><u>New In 2024, No-Cost Solutions The Best Free Online Video Merger Options</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-seamlessly-on-windows-1110-systems/"><u>Reinstating Synapse Seamlessly on Windows 11/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-boost-engagement-with-these-5-caption-tricks-on-tiktok-videos/"><u>[Updated] Boost Engagement with These 5 Caption Tricks on TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/solving-rdp-connectivity-issues-in-win10plus/"><u>Solving RDP Connectivity Issues in Win10+</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-0x800700e1-on-w10w11/"><u>Resolving Error Code: 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-direct-video-tweet-release-avoid-the-rt/"><u>[Updated] In 2024, Direct Video Tweet Release  Avoid the 'RT'</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-windows-lock-screen-timer-breakage/"><u>Repairing Window's Lock Screen Timer Breakage</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-key-syndrome-cure-for-muted-mouse-clicks/"><u>The Silent Key Syndrome: Cure for Muted Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/restore-steam-game-symbols-from-nowhere/"><u>Restore Steam Game Symbols From Nowhere</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-boost-your-channels-income-understanding-critical-view-thresholds/"><u>2024 Approved  Boost Your Channel's Income  Understanding Critical View Thresholds</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/next-gen-online-meeting-apps-azoom-no-more-in-2024/"><u>Next-Gen Online Meeting Apps  Azoom No More, In 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-adobe-cloud-essential-storage-insights-and-top-alternatives/"><u>2024 Approved  Mastering Adobe Cloud  Essential Storage Insights & Top Alternatives</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-htc-u23-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For HTC U23 Phones</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/surging-downloads-overcome-the-01kbs-stall-on-windows/"><u>Surging Downloads: Overcome the 0.1KB/S Stall on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-oppo-find-n3-flip-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Oppo Find N3 Flip? Look No Further | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exclusive-mcb-logo-designs-and-templates-for-2024/"><u>[Updated] Exclusive MCB Logo Designs and Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-windows-understanding-report-generation-and-analysis/"><u>The Art of Windows Understanding: Report Generation & Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functionality-to-windows-tablet-gestures/"><u>Restoring Full Functionality to Windows Tablet Gestures</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-vsdc-capture-expert-analysis-and-top-replacements/"><u>[New] 2024 Approved  VSDC Capture  Expert Analysis & Top Replacements</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-twitch-reversion-made-simple-top-ten-instructions-at-hand/"><u>[New] Twitch Reversion Made Simple  Top Ten Instructions at Hand</u></a></li>
</ul></div>
