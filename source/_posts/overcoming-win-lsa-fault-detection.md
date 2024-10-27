---
title: Overcoming Win LSA Fault Detection
date: 2024-10-26T03:23:38.887Z
updated: 2024-10-27T05:27:44.513Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Win LSA Fault Detection
excerpt: This Article Describes Overcoming Win LSA Fault Detection
keywords: Fixing LSA Errors,Win-LSA Troubleshooting,Detecting LSA Issues,Resolve LSA Faults,Overcoming LSA Failures,Addressing LSA Problems,Tackling LSA Errors
thumbnail: https://thmb.techidaily.com/f3ddbfc1319d06192a1f603baf76c1f6dea1578ed46bf0e0e3227f2988d719a1.jpg
---

## Overcoming Win LSA Fault Detection

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/updated-audacitys-annotated-guide-for-amplifying-transitions/"><u>[Updated] Audacity's Annotated Guide for Amplifying Transitions</u></a></li>
<li><a href="https://win11.techidaily.com/1-ultimate-guide-downloading-youtube-content-onto-your-ipad/"><u>1. Ultimate Guide: Downloading YouTube Content Onto Your iPad</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-crafting-a-superior-fpv-drone-setup-choosing-right-propellers/"><u>2024 Approved Crafting a Superior FPV Drone Setup Choosing Right Propellers</u></a></li>
<li><a href="https://win11.techidaily.com/1726027881327-youtube/"><u>効果的な方法でYoutube映像ダウンロード術</u></a></li>
<li><a href="https://games-able.techidaily.com/enable-remote-play-and-game-share-on-ps5/"><u>Enable Remote Play & Game Share on PS5</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/expert-evaluation-of-vsdc-features-and-best-competitor-software/"><u>Expert Evaluation of VSDC Features and Best Competitor Software</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/huion-inspiroy-g10t-drawing-pad-an-authoritative-review-on-its-elite-performance-and-sturdy-construction/"><u>Huion Inspiroy G10T Drawing Pad - An Authoritative Review on Its Elite Performance & Sturdy Construction</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-discover-the-best-3d-video-production-tools-for-stunning-visuals/"><u>In 2024, Discover the Best 3D Video Production Tools for Stunning Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/1726027705515-pc-and-smartphone/"><u>PC & Smartphoneで組み合わせ編集:ビデオ・オーディオの最適化</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/syncing-soundtracks-seamlessly-with-iphone-videos-discover-3-tricks/"><u>Syncing Soundtracks Seamlessly with iPhone Videos [Discover 3 Tricks]</u></a></li>
<li><a href="https://some-approaches.techidaily.com/vrij-converten-ik-van-m2p-naar-mpeg-uit-ons-login-free-movavi-service/"><u>VRIJ CONVERTEN IK VAN M2P NAAR MPEG UIT ONS LOGIN - FREE MOVAVI SERVICE</u></a></li>
<li><a href="https://win11.techidaily.com/1726027640655-wav/"><u>WAV形式のメタデータ管理 - 最適な編集ソフトと使用手順</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfox-navigation-error-why-you-cant-find-the-content-anymore-new-link-text/"><u>WonderFox Navigation Error: Why You Can’t Find the Content Anymore – New Link Text</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfoxs-limited-time-deal-earn-high-value-ripper-pro-licenses-discounted-3995-7990-during-this-months-movie-campaign-join-now/"><u>WonderFox's Limited-Time Deal: Earn High-Value Ripper Pro Licenses (Discounted @$3995-$7990) During This Month’s Movie Campaign – Join Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1726026812283-tiktok/"><u>パーフェクトなTikTok動画の縦横サイズ及び製作技術</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    