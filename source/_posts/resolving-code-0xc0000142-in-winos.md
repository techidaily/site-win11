---
title: Resolving Code 0XC0000142 in WINOS
date: 2024-07-13T09:55:36.765Z
updated: 2024-07-14T09:55:36.765Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Code 0XC0000142 in WINOS
excerpt: This Article Describes Resolving Code 0XC0000142 in WINOS
keywords: Windows Error Fixing,WinOS Bug Resolution,Code 0XC0000142 Solution,Debugging Windows OS,ZeroError WINOS,WINOS Exception Handling,Operating System Troubleshoot
thumbnail: https://thmb.techidaily.com/7d9570e63947f5c327258cd4fe6b134c780b31f6347726ee36443c69d0ab00f2.jpg
---

## Resolving Code 0XC0000142 in WINOS

 Error 0xc0000142 occurs when users try launching some Windows software packages. Those who encountered this issue usually see an error message that says, "The application was unable to start correctly (0xc0000142)." When that happens, the affected program refuses to launch.

 Unfortunately, error 0xc0000142 is a generic code that could affect many Windows software packages. However, many users report that it usually comes from Microsoft Office applications and games.

 So, if you're running into this issue, this is how you can fix error 0xc0000142 in Windows 11 and 10\.

## 1\. Run Affected Software With Admin Permissions

 Start your error 0xc0000142 troubleshooting by setting the affected software to run as an administrator. That will ensure the program can access more restricted file locations. You could potentially stop this error code by [setting the affected app to always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/).

## 2\. Set Affected Software to Run in Compatibility Mode

 If error 0xc0000142 arises for older software, there could be a compatibility issue with your PC's Windows 11/10 platform. Setting up an app or game to run in compatibility mode for an older Windows platform could resolve such an issue.

 This is how you can set your software to run in compatibility mode:

1. Press the **Windows** logo + **E** keyboard buttons and open the installation folder for your affected software.
2. Right-click the software's EXE (application) file to select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-properties-option.jpg)
3. Click on the properties window's **Compatibility** tab.
4. Select the checkbox labeled **Run this program in compatibility mode**.  
![Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-this-program-in-compatibility-mode-checkbox.jpg)
5. Choose the Windows OS that was the latest one in your software's release year within the drop-down menu. Selecting Windows 8 or 7 there will probably be sufficient for most apps.
6. Click **Apply** to set the new compatibility mode.
7. Select **OK** to exit the properties window.

 An alternative method is to [use the Windows 11 Program Compatibility Troubleshooter](https://www.makeuseof.com/program-compatibility-troubleshooter-windows-11-guide/). That tool automatically applies recommended compatibility settings, saving you time and effort.

## 3\. Scan Your PC's System Files

 Corrupted DLL (Dynamic Link Library) system files can cause error 0xc0000142\. You can check for and remedy system file corruption by [running the Windows System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-sfc-scannow-command5.jpg)

 We also recommend running a Deployment Imaging Servicing Management scan command. That utility can remedy issues with the Windows system image. To run that tool, execute this command in the Command Prompt:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 4\. Set the Right System Locale

 Setting a correct system locale is an error 0xc0000142 fix that's worked for some uses. To apply this fix, you must select a system locale setting for non-unicode software that matches the correct region for your PC. You can set the suitable system locale as follows:

1. Press **Windows** key + **R**, type **Control Panel** in Run, and select **OK**.
2. Click on **Region** inside the All Control Panel Items window.  
![The Region applet in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/region-in-control-panel.jpg)
3. Next, click on the **Administrative** tab.
4. Press the **Change system locale** button.  
![The Change system locale button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-system-locale-button.jpg)
5. Select the correct region for your PC in the drop-down menu.
6. Press **OK** in the Region Settings window.
7. Click on the **Apply** button to save your regional settings and **OK** to exit.

## 5\. Reregister DLL Files in Windows

 Lots of users have said reregistering all DLL files works for fixing error 0xc0000142\. This highlights that error 0xc0000142 arises because some required DLL files aren't correctly registered. There are many DLL files, but you can reregister them all by executing a single command as follows:

1. Press the **Windows** logo + **S** key simultaneously and input Command Prompt.
2. [Open the Command Prompt with admin privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) by selecting **Run as administrator** for that app's search result.
3. Input this command for reregistering DLLs and hit **Return**:  
`for %1 in (*.dll) do regsvr32 /s %1`  
![The reregister all DLLs command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/re-register-all-command.jpg)
4. Then wait until all the DLLs have been registered before closing the Command Prompt.

## 6\. Run a CHKDSK (Check Disk) Scan

 Another possible reason for the error 0xc0000142 is that your PC has bad disk sectors. You can check for and repair bad disk sectors by [running a CHKDSK (Check Disk) scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) in the Command Prompt.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/chkdsk-scan.jpg)

## 7\. Update the Driver for Your PC's GPU (Graphics Processing Unit)

 If you need to fix the error 0xc0000142 for a Windows game, [updating your PC's graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) might help. You can do that manually, using a third-party driver updater tool or AMD or NVIDIA software like GeForce Experience.

![A Download option in GeForce Experience](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/geforce-experience.jpg)

## 8\. Enable the .NET Framework 3.5 Feature

 Some programs need older .NET Framework versions to run in Windows. So, you might need to [enable .NET Framework 3.5 on Windows](https://www.makeuseof.com/windows-10-install-net-framework-version-35/) if that feature isn't available on your computer.

![The .NET Framework option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/net-framework-3-5.jpg)

## 9\. Edit the Windows Registry Key

 Many users who've fixed error 0xc0000142 confirm editing a Windows registry worked for them. Those users modified the value of a LoadAppInit\_DLL DWORD within the Windows key. These are the exact steps for applying this potential resolution:

 It's risky to edit the Registry. Always [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes to ensure you can revert to the original if you encounter issues after applying this fix.

1. Click on your taskbar's magnifying glass icon or the Search box to activate a file finder tool.
2. Enter the search phrase **regedit** into the file finder tool.
3. Select **Registry Editor** to view the registry window.
4. Go to this key location by entering the following path within Registry Editor's address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\Current Version\Windows`  
![The Windows key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-key.jpg)
5. Double-click on the **LoadAppInit\_DLLs** DWORD.
6. Then input **0** in the **Value data** box if that DWORD is set differently.  
![The EDIT DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-dword-window.jpg)
7. Click **OK** to apply the new value for the LoadAppInit\_DLLs DWORD.
8. Close out of the Registry Editor and restart your PC.

## 10\. Reinstall Affected Software Packages

 The final potential solution is reinstalling software packages for which the 0xc0000142 error occurs. Doing so will refresh and repair the software's files, which might be necessary if other resolutions don't work. Reinstalling is also another way to update apps.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-option.jpg)

 There are [many ways to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/), and you can choose any method to remove the app. However, if the error occurs when you open a game, you may need to uninstall it with its client software, such as the Epic Games Launcher. Then, reinstall the latest version of the app or game by downloading it from its website or gaming client.

## Get Error 0xc0000142 Sorted Out in Windows 11 and Windows 10

 Fixing error 0xc0000142 isn't always simple because that's an issue with many possible causes. There are numerous confirmed ways to fix that issue, many of which are covered here. So, you'll probably have to try applying at least a few of those troubleshooting methods to find one that gets error 0xc0000142 sorted out on your PC.

 Various third-party repair tools for Windows 11 and Windows 10 might also be useful for fixing error 0xc0000142\. Windows Repair, Advanced SystemCare, and Windows Repair Toolbox are among the best freeware repair tools for software troubleshooting.

 Unfortunately, error 0xc0000142 is a generic code that could affect many Windows software packages. However, many users report that it usually comes from Microsoft Office applications and games.

 So, if you're running into this issue, this is how you can fix error 0xc0000142 in Windows 11 and 10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/the-essence-of-version-numbering-in-windows/"><u>The Essence of Version Numbering in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-performance-with-smart-use-of-windows-11s-bar/"><u>Boosted Performance with Smart Use of Windows 11'S Bar</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-vlc-slow-motion-mode-how-to-activate-and-use-it/"><u>New 2024 Approved VLC Slow Motion Mode How to Activate and Use It</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-innovator-in-visual-symphony-production/"><u>In 2024, Innovator in Visual Symphony Production</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-lava-agni-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-victory-in-original-diablo/"><u>Beginner’s Blueprint to Victory in Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/making-vintage-windows-computers-more-elderly-friendly/"><u>Making Vintage Windows Computers More Elderly Friendly</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-embedding-google-play-into-windows-11/"><u>Guide to Embedding Google Play Into Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-convert-fast-videos-on-iphone-into-slow-motion-magic/"><u>[Updated] How to Convert Fast Videos on iPhone Into Slow Motion Magic</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-zero-price-zero-regrets-top-screen-recorder-tools/"><u>[Updated] Zero Price, Zero Regrets  Top Screen Recorder Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-future-of-advertising-in-the-metaverse/"><u>[Updated] The Future of Advertising in the Metaverse</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-unleash-your-creativity-top-rated-vignette-apps-for-iphone-and-android/"><u>Updated In 2024, Unleash Your Creativity Top-Rated Vignette Apps for iPhone and Android</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-security-account-manager-failures/"><u>Combatting Security Account Manager Failures</u></a></li>
<li><a href="https://win11.techidaily.com/1719361152872-lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever!</u></a></li>
<li><a href="https://win11.techidaily.com/advance-your-task-management-with-windows-flow-launcher/"><u>Advance Your Task Management with Windows' Flow Launcher</u></a></li>
<li><a href="https://some-techniques.techidaily.com/full-review-of-the-latest-powerdirector-app-24-for-2024/"><u>Full Review of the Latest PowerDirector App - '24 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-key-features-and-uses/"><u>Microsoft Family Safety: Key Features and Uses</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-startup-in-windows-11/"><u>Mastering Fast Startup in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-monitor-1-and-2-in-windows/"><u>How to Change Monitor 1 and 2 in Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unveiling-the-art-of-auditory-enhancement-on-youtube/"><u>[Updated] Unveiling the Art of Auditory Enhancement on YouTube</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/free-video-trimming-and-merging-tools-for-beginners-2023-update-for-2024/"><u>Free Video Trimming and Merging Tools for Beginners (2023 Update) for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-recording-winning-calls-a-complete-guide-free-vs-paid-for-windows-and-mac-users/"><u>[New] In 2024, Recording Winning Calls  A Complete Guide (Free vs Paid) for Windows & Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-best-of-the-best-top-5-online-stop-motion-creators/"><u>Updated 2024 Approved The Best of the Best Top 5 Online Stop Motion Creators</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-complete-analysis-breaking-down-the-google-podcast-app/"><u>In 2024, Complete Analysis  Breaking Down the Google Podcast App</u></a></li>
<li><a href="https://win11.techidaily.com/fix-cluttered-desktop-with-removal-of-win11s-focus-icons/"><u>Fix Cluttered Desktop with Removal of Win11's Focus Icons</u></a></li>
<li><a href="https://win11.techidaily.com/linking-legacy-and-modernity-initiating-windows-11-with-a-window-7-code/"><u>Linking Legacy and Modernity: Initiating Windows 11 with a Window 7 Code</u></a></li>
<li><a href="https://win11.techidaily.com/holiday-harmony-delightful-wrapped-apps-through-ms-store/"><u>Holiday Harmony: Delightful Wrapped Apps Through MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-error-4294967295-a-comprehensive-guide/"><u>Eliminating WSL Error 4294967295: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/revive-typical-windows-explore-view-configuration/"><u>Revive Typical Windows Explore View Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-photo-viewer-a-step-by-step-guide-for-11-users/"><u>Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-shooting-spectacle-top-9-strategies-for-panoramic-videos/"><u>2024 Approved  Shooting Spectacle  Top 9 Strategies for Panoramic Videos</u></a></li>
<li><a href="https://win11.techidaily.com/swift-pc-exploration-via-everythingapp/"><u>Swift PC Exploration via EverythingApp</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-non-playing-youtube-content-fixed-for-phonestablets/"><u>[New] 2024 Approved  Non-Playing YouTube Content  Fixed for Phones/Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-digital-gateway-easy-desktop-connectivity-with-win-11/"><u>Unlocking the Digital Gateway: Easy Desktop Connectivity with Win 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perfect-your-movie-watching-with-added-captions-on-windows-media-player/"><u>[Updated] Perfect Your Movie Watching with Added Captions on Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/explore-versatility-the-best-10-uses-for-windows-powertoys-tools/"><u>Explore Versatility: The Best 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://win11.techidaily.com/extracting-tabbed-files-windows-11-quick-guide/"><u>Extracting Tabbed Files: Windows 11 Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boost-safety-measures-include-trusted-sites-on-windows-11/"><u>Boost Safety Measures: Include Trusted Sites on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-top-10-memes-blending-hilarity-and-emotional-depth-on-insta/"><u>[New] In 2024, Top 10 Memes Blending Hilarity and Emotional Depth on Insta</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-linking-win-prefixes-and-ms-logins/"><u>Enhancing User Experience: Linking Win Prefixes & MS Logins</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-avoiding-mistakes-in-windows-11/"><u>The Beginner's Guide to Avoiding Mistakes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-10-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-gpu-capabilities-the-6-best-testers-in-windows/"><u>Navigate Through GPU Capabilities: The 6 Best Testers in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-get-the-best-deal-4-legit-ways-to-obtain-filmora-discount-codes-for-2024/"><u>Updated Get the Best Deal 4 Legit Ways to Obtain Filmora Discount Codes for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-win-over-product-sponsors-in-the-youtube-arena/"><u>[Updated] How to Win Over Product Sponsors in the YouTube Arena</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-high-cpu-usage-in-setups/"><u>Taming the Beast: High CPU Usage in Setups</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-windows-tools-for-superior-macos-experience/"><u>Utilizing Windows Tools for Superior macOS Experience</u></a></li>
</ul></div>
