---
title: "Unlocking the Shutdown: 4 Steps for Windows' Firewall"
date: 2024-10-08T17:21:51.728Z
updated: 2024-10-15T20:27:27.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking the Shutdown: 4 Steps for Windows' Firewall"
excerpt: "This Article Describes Unlocking the Shutdown: 4 Steps for Windows' Firewall"
keywords: Windows Firewall Guide,Secure Firewall Settings,Enabling Windows Defender,Firewall Security Tips,Protecting PC with Firewall,Turn On Windows Firewall,Optimizing Firewall Settings
thumbnail: https://thmb.techidaily.com/58e5d972b07e7d47a47d775672521bb7b4d26dbdad2027a1e368bc81a0dd6f11.jpg
---

## Unlocking the Shutdown: 4 Steps for Windows' Firewall

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-vital-guide-to-cost-effective-video-and-photography-archives/"><u>[New] Vital Guide to Cost-Effective Video and Photography Archives</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44kk44oz44k44o844on44od44oi44gl44kj5yuv55s744ks44kt44oj44ox44ob44oj44gz44kl44gf44kb44gu44k544og44od44ox44oq44kk44k544og44od44ox44ks44kk44oj44cn/"><u>「インターネットから動画をキャプチャするためのステップバイステップガイド」</u></a></li>
<li><a href="https://win11.techidaily.com/1726030191811-mp4/"><u>「プロモーションビデオ作成後にMP4ファイルが正常に再生されない場合の解決法」</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-4-time-saving-ways-to-perfect-loops-in-your-instagram-videos/"><u>2024 Approved 4 Time-Saving Ways to Perfect Loops in Your Instagram Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-analysis-top-picks-of-the-best-5-slow-motion-cams/"><u>2024 Approved Expert Analysis Top Picks of the Best 5 Slow Motion Cams</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-improving-video-quality-during-iphone-shoots/"><u>2024 Approved Improving Video Quality During iPhone Shoots</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-three-ways-to-convert-youtube-music-tracks-safely-to-mp3-format/"><u>2024 Approved Three Ways to Convert YouTube Music Tracks Safely to MP3 Format</u></a></li>
<li><a href="https://win11.techidaily.com/2024-ps5/"><u>2024年版 PS5 ビデオ再生問題解決法：ステップバイステップガイド</u></a></li>
<li><a href="https://win11.techidaily.com/1726030205806-wav/"><u>高度WAV編集ガイド：効果的にトリミング・組み合わせ・ボリューム調整法</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-converting-stunning-hdr-videos-into-compatible-sdr-format/"><u>A Simple Guide: Converting Stunning HDR Videos Into Compatible SDR Format</u></a></li>
<li><a href="https://win11.techidaily.com/can-i-trust-online-video-conversion-services-understanding-their-security-risks-and-benefits/"><u>Can I Trust Online Video Conversion Services? Understanding Their Security Risks and Benefits</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/decrypting-your-usb-drive-recover-from-exe-file-conversion-and-eliminate-ransomware-threats/"><u>Decrypting Your USB Drive: Recover From EXE File Conversion & Eliminate Ransomware Threats</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/steps-to-save-youtube-videos/"><u>Easy Steps to Save YouTube Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-ensure-video-success-on-twitter-understand-the-aspect-ratio/"><u>In 2024, Ensure Video Success on Twitter Understand the Aspect Ratio</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leveraging-influencer-networks-for-video-game-success-for-2024/"><u>Leveraging Influencer Networks for Video Game Success for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-honor-x50-gt-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Honor X50 GT Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/1726030041701-youtube/"><u>YouTube ミュージックダウンロードガイド - 曲を正しく記録するための効果的な手法</u></a></li>
<li><a href="https://win11.techidaily.com/1726029971792-obs-studio/"><u>ぜひ体験！OBS Studioで美しくキレイに高精細化されたゲーム動画の作成法</u></a></li>
<li><a href="https://win11.techidaily.com/44oh44oh44kj44ki44ov44kh44kk44or566h55cg44gr54m55yyw44gx44gf44gv44gplus44gw44gplus44gq44k944ov44oi44km44kn44ki44o744oe44o844or44go44ki44ox44oq44kx44o844k34490/"><u>メディアファイル管理に特化したさまざまなソフトウェア・ツールとアプリケーションを紹介する</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    