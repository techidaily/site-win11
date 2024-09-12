---
title: Troubleshooting Admin Command Failures on PCs
date: 2024-09-11T09:44:19.852Z
updated: 2024-09-12T09:44:19.852Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Admin Command Failures on PCs
excerpt: This Article Describes Troubleshooting Admin Command Failures on PCs
keywords: Admin Commands Troubleshoot,Resolve Command Errors PC,Fixing Admin Command Issues,Admin Command Fix Guide,Stop Admin Commands Fail,PC Admin Command Halt,Debugging Command Errors
thumbnail: https://thmb.techidaily.com/d24334e679d3e178a2e8d9f5b333fac2b20b9134a044e30e2240a2331d8bec84.jpg
---

## Troubleshooting Admin Command Failures on PCs

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118304/7443" target="_top" id="2118304">
  <img src="//a.impactradius-go.com/display-ad/7443-2118304" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118304/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
6. Now exit the Registry Editor and restart your computer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-the-perfect-way-to-add-linktree-to-tiktok-bio/"><u>[New] 2024 Approved The Perfect Way to Add Linktree to TikTok Bio</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-chuckling-and-crying-on-the-same-ig-feed-top-memetic-pages/"><u>[New] Chuckling and Crying on the Same IG Feed Top Memetic Pages</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-pace-your-panorama-learning-time-lapses-on-samsung-phones-for-2024/"><u>[New] Pace Your Panorama Learning Time-Lapses on Samsung Phones for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-from-noob-to-pro-making-the-list-of-popular-fb-songs-and-videos/"><u>[Updated] 2024 Approved From Noob to Pro Making the List of Popular FB Songs and Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-a-rundown-top-8-exceptional-free-online-translation-platforms/"><u>[Updated] In 2024, A Rundown Top 8 Exceptional Free Online Translation Platforms</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-photoshop-sway-decrease-pivotal-or-superfluous-in-2024/"><u>[Updated] Photoshop Sway Decrease Pivotal or Superfluous, In 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-unlocking-the-value-in-twitters-archives-for-2024/"><u>[Updated] Unlocking the Value in Twitters Archives for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-visualize-success-free-templates-to-elevate-your-youtube-presence-for-2024/"><u>[Updated] Visualize Success Free Templates to Elevate Your YouTube Presence for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-chromeos-top-free-screen-capture-software/"><u>2024 Approved ChromeOS Top Free Screen Capture Software</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-iphone-techniques-for-full-sphere-videography/"><u>2024 Approved IPhone Techniques for Full-Sphere Videography</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-masterclass-top-10-recorder-options-on-spotify/"><u>2024 Approved Masterclass Top 10 Recorder Options on Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tips-for-dealing-with-system-calls-in-windows/"><u>Comprehensive Tips for Dealing With System Calls in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/1716465391257-creative-video-ends-top-6-budget-friendly-options/"><u>Creative Video Ends Top 6 Budget-Friendly Options!</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Infinix Zero 5G 2023 Turbo? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-how-to-make-uwp-app-shortcuts/"><u>Enhancing Windows 11: How to Make UWP App Shortcuts</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On OnePlus 11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-vac-was-unable-to-verify-your-game-session-error-on-steam-for-windows/"><u>How to Fix the “VAC Was Unable to Verify Your Game Session” Error on Steam for Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-tecno-phantom-v-fold-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Tecno Phantom V Fold Safely | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevate-your-content-uploading-numerous-photos-and-videos-to-instagram/"><u>In 2024, Elevate Your Content Uploading Numerous Photos and Videos to Instagram</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sound-in-sight-mixing-music-into-microsofts-presentation-tool/"><u>In 2024, Sound in Sight Mixing Music Into Microsoft's Presentation Tool</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-graphics-enhancement-in-windows-11s-shielded-browsing/"><u>Innovative Graphics Enhancement in Windows 11'S Shielded Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-correction-windows-11-wow-mishaps/"><u>Mastering Error Correction: Windows 11 WoW Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-speech-to-text-the-whisper-desktop-way/"><u>Mastering Speech-to-Text: The Whisper Desktop Way</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-without-microsofts-core-tools-for-win-11/"><u>Mastery Without Microsoft's Core Tools for Win 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/y-makers-manual-youtube-track-transfers-for-2024/"><u>Melody Makers' Manual YouTube Track Transfers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-ai-hub-revolutionizing-retail-shopping/"><u>Microsoft AI Hub: Revolutionizing Retail Shopping</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-settings-hyper-v-onoff-tutorial/"><u>Navigating Windows 11'S Settings: Hyper-V On/Off Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-epic-launcher-errors-a-windows-fix-guide/"><u>Overcoming Epic Launcher Errors: A Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-store-error-code-x00000000/"><u>Overcoming Windows 11 Store Error Code X00000000</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-synapse-for-smooth-operation/"><u>Quick Guide: Resetting Synapse for Smooth Operation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-stalled-asana-functionality-in-windows-environment/"><u>Quick Remedies for Stalled Asana Functionality in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cmd-prompt-lack-of-admin-privileges/"><u>Resolving Cmd Prompt Lack of Admin Privileges</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-read-error-on-windows-os/"><u>Resolving Disk Read Error on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-windows-11-defender-trail-easy-steps-to-take/"><u>Revamp Your Windows 11 Defender Trail: Easy Steps to Take</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-microsoft-meeting-screen/"><u>Reviving Your Microsoft Meeting Screen</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-win11-screensaver-exceptions-easily/"><u>Sidestep WIN11 Screensaver Exceptions Easily</u></a></li>
<li><a href="https://win11.techidaily.com/steam-game-achievement-reboot-guide/"><u>Steam Game Achievement Reboot Guide</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-installing-kali-into-your-windows-ecosystem/"><u>Step by Step: Installing Kali Into Your Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-dns-flushing-in-modern-windows/"><u>Step-by-Step DNS Flushing in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-and-using-microsofts-code-assistant/"><u>Step-by-Step: Setting Up and Using Microsoft's Code Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-lost-network-access-on-windows-pc/"><u>Steps to Regain Lost Network Access on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-re-associate-file-applications-in-win108/"><u>Strategies to Re-Associate File Applications in Win10/8</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-non-storage-feedback/"><u>Tackling Windows Camera Non-Storage Feedback</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-companion-for-new-diablo-players/"><u>The Essential Companion for New Diablo Players</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-altering-nat-settings-on-modern-windows-systems/"><u>The Essential Guide to Altering NAT Settings on Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/transform-workflow-efficiency-mastering-flow-launcher-basics/"><u>Transform Workflow Efficiency: Mastering Flow Launcher Basics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-persistent-windows-volume-mixer/"><u>Troubleshooting Non-Persistent Windows Volume Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x800f082f-with-dism/"><u>Troubleshooting Windows Error 0X800F082F with DISM</u></a></li>
<li><a href="https://win11.techidaily.com/unearthing-the-hidden-potential-of-windows-monitoring-systems/"><u>Unearthing the Hidden Potential of Windows Monitoring Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-security-tool-canary-channel/"><u>Unveiling Windows' Security Tool: Canary Channel</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    