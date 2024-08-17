---
title: A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11
date: 2024-08-16T00:03:29.596Z
updated: 2024-08-17T00:03:29.596Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11
excerpt: This Article Describes A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11
keywords: Win11 Login Halt,Windows 11 Unregister,Session Lockout WIn11,End Non-Registered Sessions,Disable Unauthorized Access,Stop Unlogged Users WIn11,User Account Termination Win11
thumbnail: https://thmb.techidaily.com/698acf9899d7549d0c21beb422c9a4efb393d0c106634028a5e9ccbf41fc2d01.jpg
---

## A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
7. Once done, type **exit** and press Enter to close the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/xcellent-10-tech-choices-for-livestream-monitoring-for-2024/"><u>[New] Excellent 10 Tech Choices for Livestream Monitoring for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-invisible-scrutiny-unlocking-ig-selfie-verification-secrets/"><u>[New] The Invisible Scrutiny  Unlocking IG Selfie Verification Secrets</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-5-best-mid-range-gaming-keyboards-for-enthusiasts/"><u>[Updated] 5 Best Mid-Range Gaming Keyboards for Enthusiasts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-collaborate-for-success-video-strategies-for-2024/"><u>[Updated] Collaborate for Success  Video Strategies for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-scratch-to-screen-video-editing-with-youtube-and-others-for-2024/"><u>[Updated] From Scratch to Screen  Video Editing with YouTube & Others for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-leading-edge-facebook-film-archives-for-2024/"><u>[Updated] Leading Edge  Facebook Film Archives for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-navigating-and-mastering-instagram-filters-a-2023-guide/"><u>[Updated] Navigating and Mastering Instagram Filters  A 2023 Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-streamlined-techniques-for-recording-gotomeetings-for-2024/"><u>[Updated] Streamlined Techniques for Recording GoToMeetings for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-ignite-interest-with-your-own-solo-podcast-series/"><u>2024 Approved  Ignite Interest with Your Own Solo Podcast Series</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfect-package-presentation-transformative-openings/"><u>2024 Approved  Perfect Package Presentation  Transformative Openings</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-ultimate-fix-for-instagram-video-problems/"><u>2024 Approved  The Ultimate Fix for Instagram Video Problems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tying-the-story-together-expert-techniques-for-inshots-seamless-segments/"><u>2024 Approved  Tying the Story Together  Expert Techniques for Inshot's Seamless Segments</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clumped-up-windows-11-icon-grouping/"><u>Adjusting Clumped-Up Windows 11 Icon Grouping</u></a></li>
<li><a href="https://win11.techidaily.com/bring-home-the-fun-smartphone-games-to-desktop-with-win-11-and-google-play/"><u>Bring Home the Fun: Smartphone Games to Desktop with Win 11 & Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-a-bricked-windows-update-fix/"><u>Bypassing a Bricked Windows Update Fix</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-winning-strategy-running-windows-11-on-mac-via-parallels/"><u>Craft a Winning Strategy: Running Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-refusal-to-execute-exe-files/"><u>Decoding Windows' Refusal to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-z-fold-5-has-native-mkv-support-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Samsung Galaxy Z Fold 5 has native MKV support?</u></a></li>
<li><a href="https://facebook.techidaily.com/embracing-the-online-world-9-ways-social-media-enhances-life/"><u>Embracing the Online World: 9 Ways Social Media Enhances Life</u></a></li>
<li><a href="https://win11.techidaily.com/end-session-of-unknown-windows-users-effectively/"><u>End Session of Unknown Windows Users Effectively</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-picks-for-the-ultimate-smart-speaker-comparison-of-2024/"><u>Expert Picks for the Ultimate Smart Speaker Comparison of 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-effective-batch-conversion-of-heic-to-jpeg-in-windows/"><u>Expert Tips for Effective Batch Conversion of HEIC to JPEG in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fast-tracking-yuzu-gameplay-on-windows/"><u>Fast-Tracking Yuzu Gameplay on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-identifiable-usb-port-error-on-windows-11/"><u>Fixing Non-Identifiable USB Port Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-open-issues-windows-11s-mail-and-calendar-hiccup/"><u>Fixing Open Issues: Windows 11'S Mail & Calendar Hiccup</u></a></li>
<li><a href="https://win11.techidaily.com/forward-into-futures-ai-driven-windows-transformation/"><u>Forward Into Futures: AI-Driven Windows Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-enable-widgets-on-windows-11-system/"><u>Harness the Power: Enable Widgets on Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-desktop-trash-bin-for-permanently-deleting-files-on-windows-11-and-11/"><u>How to Add a Desktop Trash Bin for Permanently Deleting Files on Windows 11 & 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-breakneck-speed-photo-display-on-your-pc/"><u>In 2024, Breakneck Speed Photo Display on Your PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harnessing-the-power-of-photoshops-3d-lut-filters/"><u>In 2024, Harnessing the Power of Photoshop's 3D LUT Filters</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-heads-up-on-high-tech-the-best-motorcycle-cam-gear-guide-in-23/"><u>In 2024, Heads Up on High-Tech - The Best Motorcycle Cam Gear Guide in '23</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-13-with-7-methods-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 13 With 7 Methods</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-skyrocketing-your-tiktok-content-speed/"><u>In 2024, Skyrocketing Your TikTok Content Speed</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-fixes-in-windows-10-and-11/"><u>Mastering DirectDraw Fixes in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-pc-graphics-fix-in-windows-1011/"><u>Mastering PC Graphics Fix in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-visual-impact-with-auto-color-settings-in-windows-11/"><u>Maximize Visual Impact with Auto Color Settings in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-12-pro-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 12 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/no-plug-just-play-connect-dualshock-3-to-pc/"><u>No Plug, Just Play: Connect DualShock 3 to PC</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tutorial-opening-the-windows-info-panel/"><u>Quick Tutorial: Opening the Windows Info Panel</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-the-windows-firewall-with-precision/"><u>Resetting the Windows Firewall with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vmware-freeze-up-in-windows-11/"><u>Resolving VMware Freeze-Up in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-microsofts-speech-recognition-in-windows-11/"><u>Restoring Microsoft's Speech Recognition in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-memory-shortage-error-in-windows-based-vms/"><u>Solutions for 'Memory Shortage' Error in Windows-Based VMs</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-stop-laptops-internal-keystrokes/"><u>Step-by-Step: Stop Laptop's Internal Keystrokes</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-reversing-rdp-monochrome/"><u>Strategies for Reversing RDP Monochrome</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-domain-users-biometric-use-on-w11/"><u>Strategizing Domain Users' Biometric Use on W11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-data-handling-mastering-windows-11s-disk-access-methods/"><u>Streamline Data Handling: Mastering Windows 11'S Disk Access Methods</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-home-admin-with-ease-of-use/"><u>Streamline Windows Home Admin with Ease of Use</u></a></li>
<li><a href="https://video-capture.techidaily.com/streamline-your-workflow-essential-tips-to-record-on-hp-laptop/"><u>Streamline Your Workflow  Essential Tips to Record on HP Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-faulty-microsoft-store-eradicate-0x80072efd/"><u>Tackling Faulty Microsoft Store: Eradicate 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-overcoming-failed-rpc-in-windows/"><u>The Ultimate Guide to Overcoming Failed RPC in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-pre-buying-your-ideal-win-pc/"><u>The Ultimate Guide to Pre-Buying Your Ideal Win PC</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-guide-how-to-fix-when-zoom-doesnt-play-your-video/"><u>Ultimate Guide: How To Fix When Zoom Doesn't Play Your Video</u></a></li>
<li><a href="https://extra-information.techidaily.com/unraveling-the-expertise-within-polarrs-photography-suite/"><u>Unraveling the Expertise Within Polarr’s Photography Suite</u></a></li>
<li><a href="https://change-location.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/wi-fi-6ax201-issues-solution-found/"><u>Wi-Fi 6Ax201 Issues - Solution Found</u></a></li>
<li><a href="https://common-error.techidaily.com/win11-system-spontaneously-shuts-down/"><u>Win11 System Spontaneously Shuts Down</u></a></li>
</ul></div>
