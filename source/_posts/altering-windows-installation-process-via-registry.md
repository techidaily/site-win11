---
title: Altering Windows Installation Process via Registry
date: 2024-07-13T11:18:56.034Z
updated: 2024-07-14T11:18:56.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows Installation Process via Registry
excerpt: This Article Describes Altering Windows Installation Process via Registry
keywords: WinInstallRegChange,RegEditForWindows,WindowSetupKeyEdit,ModifyWinRegistry,AlteredWinInstReg,EditWinOSReg,WindowsSetupCustomization
thumbnail: https://thmb.techidaily.com/6afde60cdf2c4ed08818a0c3bb279e1893a9ceb4675945a4f5d57ab92e9d6ef9.jpg
---

## Altering Windows Installation Process via Registry

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first [activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to [launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-pro-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 11 Pro 3 Ways To Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/max-1-antivirus-for-windows-optimize-system-performance/"><u>Max 1 Antivirus for WIndows: Optimize System Performance</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-the-power-of-two-networks-a-window-guide-to-dual-connectivity/"><u>Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-vrecorder-basics-seamless-installation/"><u>[New] In 2024, VRecorder Basics  Seamless Installation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-recovery-methods-for-frozen-mouse-clicks/"><u>Quick Recovery Methods for Frozen Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-change-file-formats-on-pc/"><u>Expert Strategies to Change File Formats on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-cannot-open-file-problems-in-win1110/"><u>Mastering the Art of Fixing 'Cannot Open File' Problems in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-inability-to-link-with-nvidia-experience-on-pcs/"><u>Overcoming the Inability to Link with NVIDIA Experience on PCs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-seamlessly-reorganize-video-playlists-on-yt/"><u>[New] 2024 Approved  How to Seamlessly Reorganize Video Playlists on YT</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-network-shield-controls-on-windows/"><u>Mastering Network Shield Controls on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-optimal-screen-capture-chromeos-enhanced-for-2024/"><u>[Updated] Optimal Screen Capture  ChromeOS Enhanced for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-nokia-c110-to-mac-drfone-by-drfone-android/"><u>How to Mirror Nokia C110 to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-see-what-is-taking-up-too-much-disk-space-on-your-windows-pc/"><u>How to See What Is Taking Up Too Much Disk Space on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-windows-safescreen-state-against-user-tweaks/"><u>Protecting Windows SafeScreen State Against User Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-halted-wow-installation/"><u>Reactivating a Halted WoW Installation</u></a></li>
<li><a href="https://extra-information.techidaily.com/coordinated-audio-visual-grouping-space/"><u>Coordinated Audio-Visual Grouping Space</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-windows-model-chronology/"><u>Pinpointing Windows Model Chronology</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-your-windows-stylus-device/"><u>Mastering the Art of Fixing Your Windows Stylus Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-game-on-with-premium-screens-for-your-xbox-series-x-console/"><u>[New] Game on with Premium Screens for Your Xbox Series X Console</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-honor-70-lite-5g-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Honor 70 Lite 5G without backup.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-iphone-images-problem-in-windows-environments/"><u>How to Rectify iPhone Images Problem in Windows Environments</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-a24-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy A24 Lock Screen Password?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-xbox-play-network-errors-on-windows-1011-systems/"><u>Fixing Xbox Play Network Errors on Windows 10/11 Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/achieve-professional-results-access-to-10-basic-free-and-paid-luts-for-canon-cams/"><u>Achieve Professional Results  Access to 10 Basic Free and Paid LUTs for Canon Cams</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-leveraging-libraries-improving-efficiency-in-your-javascript-projects/"><u>[New] 2024 Approved  Leveraging Libraries  Improving Efficiency in Your JavaScript Projects</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-elevate-your-content-game-on-youtube-top-11-video-seo-insights/"><u>[New] 2024 Approved  Elevate Your Content Game on YouTube  Top 11 Video SEO Insights</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-flow-optimize-your-windows-11-hdd/"><u>Mastering Data Flow: Optimize Your Windows 11 HDD</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-install-failed-messages-on-discord/"><u>Navigating Through Install Failed Messages on Discord</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlock-growth-potential-with-savvy-analysis-of-youtube-data/"><u>[Updated] Unlock Growth Potential with Savvy Analysis of YouTube Data</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Infinix Note 30i? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-collect-premium-audio-for-video-editors/"><u>[New] Collect Premium Audio for Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-computers-small-smart-and-windows/"><u>Innovative Computers: Small, Smart, and Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-android-studio-on-windows-for-faster-compilation/"><u>Optimizing Android Studio on Windows for Faster Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-missing-battery-time-estimate-in-windows-11/"><u>How to Fix a Missing Battery Time Estimate in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-downloading-with-diligence-how-to-securely-save-imagesvideos-on-iphone-for-2024/"><u>[New] Downloading with Diligence  How to Securely Save Images/Videos on iPhone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-windows-speech-to-text-app-using-whisper-and-ahk/"><u>Creating a Personalized Windows Speech-to-Text App Using Whisper & AHK</u></a></li>
<li><a href="https://win11.techidaily.com/managing-disk-space-wisely-recognizing-huge-file-and-folder-use/"><u>Managing Disk Space Wisely: Recognizing Huge File & Folder Use</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-nailing-the-technique-for-snapchat-screen-time-lapses/"><u>2024 Approved  Nailing the Technique for Snapchat Screen Time-Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-null-associated-app-error-on-windows-systems/"><u>Fixing Null Associated App Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-typing-efficiency-with-w11-bespo-points/"><u>Elevate Typing Efficiency with W11, Bespo Points</u></a></li>
<li><a href="https://win11.techidaily.com/prime-weather-software-for-w10w11-pcs/"><u>Prime Weather Software for W10/W11 PCs</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtubes-earnings-strategy-explored-for-2024/"><u>[Updated] YouTube's Earnings Strategy Explored for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-apple-iphone-13-mini-and-ipad-screen-mirroring-app-drfone-by-drfone-ios/"><u>Best Apple iPhone 13 mini & iPad Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transform-your-shots-into-dynamic-works-of-art-with-motion-blur-techniques/"><u>[Updated] Transform Your Shots Into Dynamic Works of Art with Motion Blur Techniques</u></a></li>
</ul></div>
