---
title: "Windows 11 Trick: Show/Hide User-Defined Directories"
date: 2024-08-23T06:10:16.595Z
updated: 2024-08-24T06:10:16.595Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Trick: Show/Hide User-Defined Directories"
excerpt: "This Article Describes Windows 11 Trick: Show/Hide User-Defined Directories"
keywords: Windows 11 Hidden Folders,Show Hidden Windows 11,Uncover System Directories,Display UDs in Win11,User-Defined Trick Win11,Hide/Show Windows Files,Directories Visibility Tech
thumbnail: https://thmb.techidaily.com/6e2f3010b64553c858c441b2aa0463f3e8a124b61c9d02d5a4f78ba177103c47.png
---

## Windows 11 Trick: Show/Hide User-Defined Directories

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-duplicate-screen-output-tracking-for-2024/"><u>[New] Duplicate Screen Output Tracking for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-leveraging-user-feedback-with-instagram-story-questions/"><u>[New] Leveraging User Feedback with Instagram Story Questions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-definitive-guide-to-capturing-your-streams-netflix-mac-edition/"><u>[New] The Definitive Guide to Capturing Your Streams  Netflix Mac Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-simple-steps-to-coordinate-consistent-productive-google-collaboration-times/"><u>[Updated] 2024 Approved  Simple Steps to Coordinate Consistent, Productive Google Collaboration Times</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-9-best-online-mic-recorders-2023/"><u>[Updated] 9 Best Online Mic Recorders 2023</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-best-5-camera-apps-to-shoot-and-record-videos-on-iphone-and-andriod/"><u>[Updated] Best 5 Camera Apps to Shoot and Record Videos on iPhone and Andriod</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-eyeview-assessment-surpassing-manycams-standards/"><u>[Updated] In 2024, EyeView Assessment  Surpassing ManyCam's Standards</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-polaroid-camplus-cube-analysis-when-life-is-on-screen/"><u>[Updated] Polaroid Cam+ Cube Analysis  When Life Is on Screen</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pivotal-ideas-behind-digital-tale-weaving/"><u>2024 Approved  Pivotal Ideas Behind Digital Tale Weaving</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sony-blu-ray-player-s6700-new-insights/"><u>2024 Approved  Sony Blu-Ray Player S6700  New Insights</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-samsung-galaxy-s24-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/determine-your-windows-10-powershell-edition-with-ease/"><u>Determine Your Windows 10 PowerShell Edition with Ease</u></a></li>
<li><a href="https://data-wizards.techidaily.com/digital-recovery-renewing-video-files/"><u>Digital Recovery: Renewing Video Files</u></a></li>
<li><a href="https://win11.techidaily.com/does-pressing-prtscr-start-snipping-tool-on-win-11-trick-to-block-it/"><u>Does Pressing PrtScr Start Snipping Tool on Win 11? Trick to Block It</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-ide-speed-and-productivity-for-developers-on-windows/"><u>Enhancing IDE Speed & Productivity for Developers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-top-8-win11-choices-for-professional-videoscripting/"><u>Explore the Top 8 Win11 Choices for Professional Videoscripting</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-zero-x-error-in-windows-11s-mail-application/"><u>Fixing Zero X Error in Windows 11'S Mail Application</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Samsung Galaxy A15 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-successful-or-failed-login-attempts-on-your-windows-computer/"><u>How to Check Successful or Failed Login Attempts on Your Windows Computer</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-clear-computer-cache-windows-10-revo-uninstaller/"><u>How to Clear Computer Cache Windows 10? - Revo Uninstaller</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-discords-cannot-resize-gif-error-on-windows-11/"><u>How to Fix Discord's Cannot Resize GIF Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-merge-adjacent-and-non-adjacent-partitions-in-windows/"><u>How to Merge Adjacent and Non-Adjacent Partitions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reconnect-disconnected-file-apps-in-windows/"><u>How to Reconnect Disconnected File Apps in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Vivo S17 Pro? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-11-ranked-audio-recorders-of-the-year/"><u>In 2024, 11 Ranked Audio Recorders of the Year</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-tecno-spark-20-propluswithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Tecno Spark 20 Pro+with/without a PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-perfecting-your-presentations-youtube-and-google-slides/"><u>In 2024, Perfecting Your Presentations  YouTube and Google Slides</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-revolutionize-your-farm-life-stardews-best-7-game-updates/"><u>In 2024, Revolutionize Your Farm Life  Stardew's Best 7 Game Updates</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-bloatware-removal-in-windows-11/"><u>Mastering Bloatware Removal in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-connectivity-microsofts-phone-link-app-explained/"><u>Mastering Connectivity: Microsoft’s Phone Link App Explained</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-transparency-on-windows-11-machines/"><u>Maximizing Window Transparency on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-game-pass-issues-on-windows-os/"><u>Methods to Rectify Game Pass Issues on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-modifying-network-address-translation-in-wins-oses/"><u>Navigating and Modifying Network Address Translation in Wins OSes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-restore-on-windows-for-past-fixes/"><u>Navigating System Restore on Windows for Past Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-flawed-menu-navigation-in-windows-desktops/"><u>Overcoming Flawed Menu Navigation in Windows Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-overcoming-xbox-game-pass-warzones-directx-issues/"><u>Quick Fixes for Overcoming Xbox Game Pass Warzone's DirectX Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solution-conquer-camera-fails-in-windows-os/"><u>Quick Solution: Conquer Camera Fails in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-reconnecting-distant-devices-in-windows/"><u>Regaining Control: Reconnecting Distant Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-cyber-travel-mastering-connections-on-windows-pc/"><u>Seamless Cyber Travel: Mastering Connections on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/six-proven-techniques-for-pinpointing-your-pcs-brand-and-version/"><u>Six Proven Techniques for Pinpointing Your PC's Brand & Version</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-performance-with-expert-tips-on-wintoys-usage/"><u>Skyrocket Performance with Expert Tips on Wintoys Usage</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-unexpected-command-prompt-displays/"><u>Stopping Unexpected Command Prompt Displays</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-digital-life-using-windows-11s-taskbar-search/"><u>Streamline Your Digital Life: Using Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/switching-windows-11-logon-from-pin-to-password-a-step-by-step-guide/"><u>Switching Windows 11 Logon From PIN to Password: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-operation-failed-problem-on-pcs/"><u>Tackling the Operation Failed Problem on PCs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/tech-chronicles-by-tom-unraveling-secrets-of-modern-computer-systems/"><u>Tech Chronicles by Tom: Unraveling Secrets of Modern Computer Systems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-vivo-s17-pro-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Vivo S17 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-integrity-in-the-windows-registry/"><u>The Ultimate Guide to Restoring Integrity in the Windows Registry</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-compatible-hardware-alerts-for-idt-systems/"><u>Troubleshooting Non-Compatible Hardware Alerts for IDT Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/unique-identity-creation-accessible-logo-base-and-personal-customization-for-no-cost-for-2024/"><u>Unique Identity Creation  Accessible Logo Base & Personal Customization for No-Cost for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-top-8-interactive-gloves-in-vr-for-2024/"><u>Unveiling Top 8 Interactive Gloves in VR for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-animation-enthusiasts-choice-top-8-downloaded-sound-effects-for-your-projects/"><u>Updated 2024 Approved Animation Enthusiasts Choice Top 8 Downloaded Sound Effects for Your Projects</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-level-up-your-video-editing-with-20-free-adobe-premiere-intro-templates/"><u>Updated In 2024, Level Up Your Video Editing with 20 Free Adobe Premiere Intro Templates</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-comprehensive-navshortcut-compendium/"><u>Win11's Comprehensive NavShortcut Compendium</u></a></li>
<li><a href="https://win11.techidaily.com/windows-as-the-base-crafting-a-linux-vm-environment-via-hyper-v/"><u>Windows as the Base: Crafting a Linux VM Environment via Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-diverse-monitor-decorations-1011-edition/"><u>Windows Wonders: Diverse Monitor Decorations, 10/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-adoption-and-linux-market-dynamics/"><u>WSL Adoption and Linux Market Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/zero-internet-window-upgrades-strategy/"><u>Zero Internet Window Upgrades Strategy</u></a></li>
</ul></div>
