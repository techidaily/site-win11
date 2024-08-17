---
title: Reinstating Windows 11 Default Search Options
date: 2024-08-16T00:50:14.067Z
updated: 2024-08-17T00:50:14.067Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Windows 11 Default Search Options
excerpt: This Article Describes Reinstating Windows 11 Default Search Options
keywords: Restore Win11 SearCH,Win11 SEARCH RESET,Enable Win11 Default SERCH,Set Win11 as DEFAULT SEARCH,Windows 11 SETTINGS RESTORE,Win11 INITIAL SEARCH RECUP,Win11 Search RETURN TO STD
thumbnail: https://thmb.techidaily.com/e0a34c7a81fb8279e0e4f8e61ff399b11932a0b059873f4809f00d7b660fc375.jpg
---

## Reinstating Windows 11 Default Search Options

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-command-and-conquer-the-pinnacle-of-strategic-sagas-in-7-total-war-games/"><u>[New] Command & Conquer  The Pinnacle of Strategic Sagas in 7 Total War Games</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-missing-icon-reclaim-your-facebook-watch-icon/"><u>[New] In 2024, Missing Icon? Reclaim Your Facebook Watch Icon</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleash-creativity-with-these-top-free-slideshow-templates/"><u>[New] Unleash Creativity with These Top Free Slideshow Templates</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-capturing-your-gaming-adventures-best-practices-reviewed/"><u>[Updated] Capturing Your Gaming Adventures  Best Practices Reviewed</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-exclusive-play-on-apex-how-to-turn-off-cross-platform-mode/"><u>[Updated] Exclusive Play on Apex  How to Turn Off Cross-Platform Mode</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-step-by-step-setting-up-your-first-xbox-record-session-for-2024/"><u>[Updated] Step-by-Step  Setting Up Your First Xbox Record Session for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-the-new-short-form-fb-story-for-2024/"><u>[Updated] The New Short-Form FB Story for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-defective-battery-meter-on-windows-11-devices/"><u>Correcting Defective Battery Meter on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/devising-schemes-to-skirt-sign-in-requests-in-windows/"><u>Devising Schemes to Skirt Sign-In Requests in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-accelerated-inputs-for-a-smooth-click-journey/"><u>Eliminating Accelerated Inputs for a Smooth Click Journey</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-file-security-routine-with-powertoys/"><u>Enhancing Your File Security Routine with PowerToys</u></a></li>
<li><a href="https://fox-http.techidaily.com/essential-submarine-cinematography-tools-for-gopro-for-2024/"><u>Essential Submarine Cinematography Tools for Gopro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-of-windows-glass-hangout-guide/"><u>Essentials of Windows Glass Hangout Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-severe-discord-js-error-on-pc-windows-10-and-11-guide/"><u>Fixing Severe Discord JS Error on PC: Windows 10 & 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-setting-up-a-taskbar-on-windows-11-tablets/"><u>Guide to Setting Up a Taskbar on Windows 11 Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-users-through-windows-search-failure-issues/"><u>Guiding Users Through Windows Search Failure Issues</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-honor-90-gt-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Honor 90 GT Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-microsoft-edge-in-w11-os/"><u>How to Delete Microsoft Edge in W11 OS</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-find-and-download-the-correct-samsung-android-debug-bridge-adb-support-file/"><u>How to Find and Download the Correct Samsung Android Debug Bridge (ADB) Support File</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-lava-yuva-3-pro-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Lava Yuva 3 Pro.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-onedrive-unsuccessful-cloud-issues/"><u>How to Rectify OneDrive Unsuccessful Cloud Issues</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-passcode-from-iphone-14-plus-complete-guide-drfone-by-drfone-ios/"><u>How To Remove Passcode From iPhone 14 Plus? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-infinix-hot-40-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Infinix Hot 40</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-start-windows-media-player-in-windows/"><u>How to Start Windows Media Player in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-watch-hulu-outside-us-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-honor-x50iplus-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Honor X50i+ FRP Bypass Instantly</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-master-the-art-of-audible-social-media-posts-without/"><u>In 2024, Master the Art of Audible Social Media Posts (Without)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snapchat-savvy-mastering-screen-recordings-on-your-phone/"><u>In 2024, Snapchat Savvy  Mastering Screen Recordings on Your Phone</u></a></li>
<li><a href="https://win11.techidaily.com/installation-woes-microsoft-pc-manager-on-windows-xp/"><u>Installation Woes: Microsoft PC Manager on Windows XP</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/integrating-microsofts-azure-transcription-service-in-code-for-2024/"><u>Integrating Microsoft's Azure Transcription Service in Code for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/learn-to-cropping-and-composition-the-audio-visual-balance-in-canvas-for-2024/"><u>Learn to Cropping & Composition  The Audio-Visual Balance in Canvas for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-window-settings-for-optimal-space-in-win11/"><u>Master the Window Settings for Optimal Space in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/method-reinstate-windows-base-power-plan/"><u>Method: Reinstate Windows Base Power Plan</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-display-hiccup-error-code-x0001-geforce/"><u>Overcoming Display Hiccup: Error Code X0001, GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-disconnect-restarting-your-hotspot-in-windows-11/"><u>Overcoming the Disconnect: Restarting Your Hotspot in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unpreviewed-documents-error-in-office-outlook/"><u>Quick Fixes for Unpreviewed Documents Error in Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-cannot-create-errors-for-files-in-windows/"><u>Remedying 'Cannot Create' Errors for Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-directories-not-empty-error-on-win11-with-0x80070091/"><u>Remedying Directories Not Empty Error on Win11 with #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cloud-sync-failures-windows-10-and-11/"><u>Resolving Cloud Sync Failures: Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-cloud-connection-problems/"><u>Resolving Steam Cloud Connection Problems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gameplay-mastery-fixing-frames-drops-in-valorant/"><u>Seamless Gameplay Mastery: Fixing Frames Drops in Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/secure-file-management-windows-folders-restricted-mode-setup/"><u>Secure File Management: Windows Folders Restricted Mode Setup</u></a></li>
<li><a href="https://win11.techidaily.com/skip-the-haste-disabling-early-edge-tab-activation-in-win11/"><u>Skip the Haste: Disabling Early Edge Tab Activation in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-resurrect-winget-in-windows-os/"><u>Solutions to Resurrect Winget in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-method-to-create-an-automatic-text-transcription-program/"><u>Step-by-Step Method to Create an Automatic Text Transcription Program</u></a></li>
<li><a href="https://win11.techidaily.com/stop-zooming-start-scrolling-essential-mouse-repairs/"><u>Stop Zooming, Start Scrolling: Essential Mouse Repairs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-first-browser-view-in-windows-11/"><u>Tailoring Your First Browser View in Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-art-of-eliminating-backgrounds-in-photography/"><u>The Art of Eliminating Backgrounds in Photography</u></a></li>
<li><a href="https://win11.techidaily.com/the-voice-of-efficiency-unleashing-the-full-potential-of-windows-accessibility-tools/"><u>The Voice of Efficiency: Unleashing the Full Potential of Windows Accessibility Tools</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-11-themes-missed-by-many/"><u>Top Windows 11 Themes Missed by Many</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-computer-embracing-the-power-of-16gb/"><u>Upgrading Your Computer: Embracing the Power of 16GB</u></a></li>
<li><a href="https://win11.techidaily.com/where-are-win11-control-panel-settings-locate-missing-keys/"><u>Where Are Win11 Control Panel Settings? Locate Missing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-might-prefer-windows-11-to-apples-macos/"><u>Why You Might Prefer Windows 11 to Apple's macOS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-storage-strategies-from-chaos-to-clarity/"><u>Windows Storage Strategies: From Chaos to Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-on-pause-four-simple-steps/"><u>Windows Update on Pause: Four Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/winx-backdrop-blues-solutions-for-a-colorful-ui/"><u>WinX Backdrop Blues: Solutions for a Colorful UI</u></a></li>
</ul></div>
