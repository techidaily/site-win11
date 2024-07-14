---
title: "Security Simplified: Defaults in Windows 11 Setup"
date: 2024-07-13T10:49:50.889Z
updated: 2024-07-14T10:49:50.889Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Simplified: Defaults in Windows 11 Setup"
excerpt: "This Article Describes Security Simplified: Defaults in Windows 11 Setup"
keywords: Win11SecureDefault,SecureWinSetup,Windows11Basics,SafeWindows11,DefSecConfigWin11,DefaultsWin11Security,EnhanceWindows11Secure
thumbnail: https://thmb.techidaily.com/a65a2d3fb958e05df694286812a1e2454a9d6c6ff463421241eb49561be7ce4c.jpg
---

## Security Simplified: Defaults in Windows 11 Setup

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://win11.techidaily.com/resolving-picturesaveerror-in-windows-11/"><u>Resolving PictureSaveError in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-exporting-your-creativity-imovie-videos-for-youtube-audiences/"><u>[New] In 2024, Exporting Your Creativity  IMovie Videos for YouTube Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-phone-link-microsofts-bluetooth-connectivity-app/"><u>Unveiling 'Phone Link': Microsoft’s Bluetooth Connectivity App</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-distractions-mastering-wins-on-windows-11/"><u>Avoiding Distractions: Mastering Wins on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/20-must-haves-free-copyright-compliant-relaxation-tracks-for-2024/"><u>20 Must-Haves  Free, Copyright-Compliant Relaxation Tracks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-experience-new-pcs-ultimate-tools/"><u>Elevate Your Experience: New PC's Ultimate Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-performance-with-vm-cache-clear/"><u>Boost PC Performance with VM Cache Clear</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-best-31-video-trimmers-for-computer-phone-and-online-for-2024/"><u>Updated Best 31 Video Trimmers for Computer, Phone and Online for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-animation-studios-for-pc-and-mac-top-picks-for-pros/"><u>In 2024, Best Animation Studios for PC and Mac Top Picks for Pros</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-peer-into-the-future-with-apeaksofts-screen-capture-trends-2023-for-2024/"><u>[New] Peer Into the Future with Apeaksoft’s Screen Capture Trends 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-high-performance-navigate-valorant-lag-reduction/"><u>Unlock High Performance: Navigate Valorant Lag Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-tech-titans-android-and-microsoft-pc/"><u>Uniting Two Tech Titans: Android and Microsoft PC</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-file-management-altering-timestamps-in-windows/"><u>Cutting-Edge File Management: Altering Timestamps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-software-to-functionality-ms-workspace-on-windows-1011/"><u>From Software to Functionality: MS Workspace on Windows 10/11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-clear-picture-perfection-the-best-online-image-enhancers-for-2024/"><u>[New] Clear Picture Perfection  The Best Online Image Enhancers for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/essential-tactics-for-youtube-success-in-25-ways-for-2024/"><u>Essential Tactics for YouTube Success in 25 Ways for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-mastering-the-art-of-locating-fb-lately-seen-videos/"><u>[Updated] In 2024, Mastering the Art of Locating Fb Lately Seen Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-raw-to-refined-youtube-thumbnail-creation-for-mobile-users/"><u>[New] In 2024, From Raw to Refined  YouTube Thumbnail Creation for Mobile Users</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/first-day-with-windows-11-heres-what-not-to-do-top-7-mistakes/"><u>First Day with Windows 11? Here's What Not to Do! - Top 7 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-hues-overcoming-color-issues-on-windows/"><u>Harmonizing Hues: Overcoming Color Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-persistent-boot-related-windows-audio-failures/"><u>Eliminate Persistent Boot-Related Windows Audio Failures</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/strategies-for-time-loop-visual-tricks/"><u>Strategies for Time-Loop Visual Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-with-personal-touches/"><u>Enhancing Windows 11 with Personal Touches</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-future-of-photography-top-frames/"><u>[New] The Future of Photography  Top Frames</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-transform-your-photos-into-videos-with-these-10-online-tools/"><u>New Transform Your Photos Into Videos with These 10 Online Tools</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolving-error-x800704cf-on-windows-devices/"><u>Guide to Resolving Error X800704CF on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-lifelong-deletion-functions-on-windows-1011-desktop/"><u>Configuring Lifelong Deletion Functions on Windows 10/11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/stop-auto-changing-visuals-on-win11-pcs/"><u>Stop Auto-Changing Visuals on Win11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-advanced-backup-capabilities/"><u>Unlock Advanced Backup Capabilities</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-mp4-file-editor-for-pc-quickly-trim-cut-and-merge-videos/"><u>New MP4 File Editor for PC Quickly Trim, Cut, and Merge Videos</u></a></li>
<li><a href="https://win11.techidaily.com/verifying-your-version-three-ways-for-windows-11/"><u>Verifying Your Version: Three Ways for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-comic-file-access-in-modern-windows/"><u>Streamlining Comic File Access in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-the-electrical-footprint-of-your-personal-windows-pc/"><u>Analyzing the Electrical Footprint of Your Personal Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-innovation-new-pcs-best-tools-from-msistore/"><u>Accelerated Innovation: New PC's Best Tools From MSIStore</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-twitter-elite-moments-live-on-snapchat/"><u>[New] 2024 Approved  Twitter Elite Moments Live on Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-clutter-eliminate-onedrive-symbol-from-explorer/"><u>Confronting Clutter: Eliminate OneDrive Symbol From Explorer</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-explore-instagrams-per-video-limit-explained/"><u>[New] In 2024, Explore Instagram's Per-Video Limit Explained</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-take-control-of-your-instagram-content/"><u>[Updated] In 2024, Take Control of Your Instagram Content</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-reviving-your-windows-system/"><u>The Blueprint for Reviving Your Windows System</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-stories-in-simplicity/"><u>[New] Stories in Simplicity</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-download-youtube-videos-on-android-9-powerful-apps-compared/"><u>[Updated] Download YouTube Videos on Android  9 Powerful Apps Compared</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/incognito-observer-of-online-chronicles/"><u>Incognito Observer of Online Chronicles</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unable-to-access-your-windows-start-icon/"><u>Troubleshooting: Unable to Access Your Windows Start Icon</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-indulge-in-9-holiday-blockbusters-free-online-christmas-viewing/"><u>[Updated] In 2024, Indulge in 9 Holiday Blockbusters  Free Online Christmas Viewing</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-top-10-best-photo-to-animation-converters/"><u>Updated 2024 Approved Top 10 Best Photo to Animation Converters</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-to-counteract-accelerated-mice/"><u>Adjusting Windows to Counteract Accelerated Mice</u></a></li>
<li><a href="https://some-tips.techidaily.com/moto-cams-best-top-5-hats-for-riders-for-2024/"><u>Moto Cam's Best  Top 5 Hats for Riders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-installs-time-mastering-grouped-deployments-with-winstall-on-windows-11/"><u>Cutting Down Installs Time: Mastering Grouped Deployments with Winstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/turning-oculus-quest-into-a-windows-based-vr-device/"><u>Turning Oculus Quest Into a Windows-Based VR Device</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-video-editing-face-off-premiere-pro-vs-after-effects-whats-the-best-choice-in-2024/"><u>Updated Video Editing Face-Off Premiere Pro vs After Effects - Whats the Best Choice, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-wizardry-unmasking-your-ip/"><u>Command Prompt Wizardry: Unmasking Your IP</u></a></li>
<li><a href="https://win11.techidaily.com/creating-digital-wonders-on-win11-with-paint-cocreator-the-ultimate-guide-for-ai-image-creation/"><u>Creating Digital Wonders on Win11 With Paint Cocreator: The Ultimate Guide for AI Image Creation</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-rewind-designers-toolkit/"><u>In 2024, Rewind Designer's Toolkit</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-redmi-12-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi Redmi 12 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-procedure-to-independently-update-windows/"><u>Stepwise Procedure to Independently Update Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-distant-devices-a-guide-for-windows-users/"><u>Reconciling Distant Devices: A Guide for Windows Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-revealing-the-truth-behind-instagrams-video-pauses/"><u>[New] Revealing the Truth Behind Instagram’s Video Pauses</u></a></li>
<li><a href="https://win11.techidaily.com/relish-in-unmatched-windows-software-sweepstakes/"><u>Relish In Unmatched Windows Software Sweepstakes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lag-on-extended-screens/"><u>Addressing Windows Lag on Extended Screens</u></a></li>
<li><a href="https://win11.techidaily.com/revive-muted-slack-on-windows-easy-steps-to-resuscitate-alerts/"><u>Revive Muted Slack on Windows: Easy Steps to Resuscitate Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-window-resolutions/"><u>Enhancing Your Visual Experience with Window Resolutions</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/izing-profits-the-ultimate-guide-to-youtube-revenue/"><u>Maximizing Profits   The Ultimate Guide to YouTube Revenue</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/reimagining-your-tiktok-visage-complete-profile-update-manual/"><u>Reimagining Your TikTok Visage  Complete Profile Update Manual</u></a></li>
<li><a href="https://win11.techidaily.com/solving-failed-volume-shadow-copy-in-windows-os/"><u>Solving Failed Volume Shadow Copy in Windows OS</u></a></li>
</ul></div>
