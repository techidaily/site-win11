---
title: "Purging Power Users: The Guide to Default Settings"
date: 2024-08-15T23:59:53.424Z
updated: 2024-08-16T23:59:53.424Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Purging Power Users: The Guide to Default Settings"
excerpt: "This Article Describes Purging Power Users: The Guide to Default Settings"
keywords: Power User Tips,Setting Basics,Default Configs,Admin Guidelines,Security Updates,System Optimization,Default Tweaks
thumbnail: https://thmb.techidaily.com/c097990fd37784ce6293a6224fb832fd4d9a7841c40f79ad9e48ab602a74cd56.jpg
---

## Purging Power Users: The Guide to Default Settings

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-clearer-horizons-the-ultimate-tweet-video-viewing-guide/"><u>[New] 2024 Approved  Clearer Horizons  The Ultimate Tweet Video Viewing Guide</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-optimizing-video-exposure-on-youtube-with-high-impact-channels/"><u>[New] 2024 Approved  Optimizing Video Exposure on YouTube with High-Impact Channels</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-the-ultimate-list-youtube-alternatives-for-video-creators/"><u>[New] 2024 Approved  The Ultimate List  YouTube Alternatives for Video Creators</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-from-recordings-to-live-streams-instagram-via-obs-explained-for-2024/"><u>[New] From Recordings to Live Streams  Instagram via OBS Explained for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-tiktoks-enduring-melodies-top-10-of-the-year-2024/"><u>[New] TikTok's Enduring Melodies  Top 10 of the Year 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-audio-archive-collect-and-examine-music-files/"><u>[Updated] Audio Archive  Collect & Examine Music Files</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-beneath-the-oceans-veil-tips-for-recording-top-notch-underwater-gopro-videos/"><u>[Updated] Beneath the Ocean’s Veil  Tips for Recording Top-Notch Underwater GoPro Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-discerning-t-series-profit-mechanisms-from-youtube-views/"><u>[Updated] Discerning T-Series' Profit Mechanisms From Youtube Views</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-effortless-digital-preservation-how-to-record-live-tv-shows-for-2024/"><u>[Updated] Effortless Digital Preservation  How To Record Live TV Shows for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-cutting-the-chaff-skilled-techniques-for-cropping-videos-for-instagram/"><u>[Updated] In 2024, Cutting the Chaff  Skilled Techniques for Cropping Videos for Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-tailoring-mac-videos-to-fit-snapchat-dimensions/"><u>[Updated] In 2024, Tailoring Mac Videos to Fit Snapchat Dimensions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-unleash-the-power-of-your-lost-iphone-x/"><u>[Updated] In 2024, Unleash the Power of Your Lost iPhone X</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-interactive-inspection-kits-facebook-live-for-2024/"><u>[Updated] Interactive Inspection Kits  Facebook Live for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-nightly-narratives-video-guide-and-critiques/"><u>2024 Approved  Nightly Narratives  Video Guide & Critiques</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-repair-the-net-framework-on-windows/"><u>5 Ways to Repair the .NET Framework on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-things-to-remember-before-you-clean-install-windows/"><u>8 Things to Remember Before You Clean Install Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-on-using-w11s-automated-hdr-feature/"><u>A Complete Guide on Using W11's Automated HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-step-by-step-approach-to-chatgpt-with-iphones-siri/"><u>A Step-by-Step Approach to ChatGPT with iPhone's Siri</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-roadmap-to-your-computers-heart-mouse-prop/"><u>A Step-by-Step Roadmap to Your Computer's Heart - Mouse Prop</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-typing-mastering-windows-powertoys/"><u>Accelerate Typing: Mastering Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-keystrokes-mastery-via-typingaid/"><u>Accelerating Keystrokes: Mastery via TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/access-banishment-4-streamlined-steps-for-stripping-win11-of-users/"><u>Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-phone-dialer-in-windows-11/"><u>Accessing Phone Dialer in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activatedeactivate-fingerwriting-in-windows-system/"><u>Activate/Deactivate Fingerwriting in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-files-in-steam-library/"><u>Addressing Disconnected Files in Steam Library</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-30015-26-in-m365-software-for-pcs/"><u>Addressing Error Code 30015-26 in M365 Software for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-nvidia-software-connection-failure-in-os-x/"><u>Addressing NVIDIA Software Connection Failure in OS X</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-unsuccessful-java-vm-startup/"><u>Addressing the Unsuccessful Java VM Startup</u></a></li>
<li><a href="https://win11.techidaily.com/adept-methods-for-switching-file-types-in-windows/"><u>Adept Methods for Switching File Types in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-desktop-date-and-time-a-win-1011-guide/"><u>Adjusting Desktop Date & Time: A Win 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-isolating-subjects-in-photography/"><u>Advanced Tips for Isolating Subjects in Photography</u></a></li>
<li><a href="https://win11.techidaily.com/automatic-empty-recycle-bin-in-windows-step-by-step/"><u>Automatic Empty Recycle Bin in Windows Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unauthorized-user-error-on-windows-11-and-11/"><u>Avoiding Unauthorized User Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-update-failure-code-0x800f0845/"><u>Avoiding Update Failure - Code 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/bargain-bonanza-black-friday-612-for-lifelong-win10-life/"><u>Bargain Bonanza: Black Friday - $6.12 for Lifelong Win10 Life</u></a></li>
<li><a href="https://win11.techidaily.com/battle-the-bake-off-effective-tactics-to-reduce-gaming-laptops-temperature/"><u>Battle the Bake-Off: Effective Tactics to Reduce Gaming Laptop’s Temperature</u></a></li>
<li><a href="https://win11.techidaily.com/boot-security-errors-squashed-in-5-easy-steps-for-windows-users/"><u>Boot Security Errors Squashed in 5 Easy Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bound-windows-login-with-ms-account-essentials/"><u>Bound Windows Login with MS Account Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-essential-steps-to-game-folder-opening/"><u>Break the Code: Essential Steps to Game Folder Opening</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-setup-barriers-filling-action-voids-on-pc/"><u>Breaking Down Wi-Fi Setup Barriers: Filling Action Voids on PC</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-exepe-file-formats/"><u>Breaking Down Windows EXE/PE File Formats</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-adjusting-immovable-gif-sizes-for-windows-users-of-discord/"><u>Breaking Free: Adjusting Immovable GIF Sizes for Windows Users of Discord</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/chart-a-new-course-windows-7-to-10-upgrade-map/"><u>Chart a New Course: Windows 7 to 10 Upgrade Map</u></a></li>
<li><a href="https://win11.techidaily.com/1719362389609-determining-cpu-version-on-windows-here-are-8-ways/"><u>Determining CPU Version on Windows – Here Are 8 Ways</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-infinix-note-30-5g-device-sim-by-drfone-android/"><u>Easily Unlock Your Infinix Note 30 5G Device SIM</u></a></li>
<li><a href="https://vp-tips.techidaily.com/hololens-review-pioneering-virtual-spacecraft/"><u>HoloLens Review  Pioneering Virtual Spacecraft</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-galaxy-a15-4g-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Galaxy A15 4G Pictures  An Easy Method Explained.</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-stop-frostpunk-crashes-expert-tips-and-solutions-inside/"><u>How To Stop Frostpunk Crashes: Expert Tips and Solutions Inside!</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-engaging-stories-expanding-audiences-top-three-methods/"><u>In 2024, Engaging Stories, Expanding Audiences  Top Three Methods</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-silence-the-algorithmic-intrusions-on-ig/"><u>In 2024, Silence the Algorithmic Intrusions on IG</u></a></li>
<li><a href="https://win11.techidaily.com/1719224494525-revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/l-media-video-trends-for-smbs-for-2024/"><u>Social Media Video Trends for SMBs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719369059725-streamline-facebook-messenger-on-your-pc-now/"><u>Streamline Facebook Messenger On Your PC Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1719350686194-unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues</u></a></li>
<li><a href="https://change-location.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Samsung Galaxy A14 4G | Dr.fone</u></a></li>
</ul></div>
