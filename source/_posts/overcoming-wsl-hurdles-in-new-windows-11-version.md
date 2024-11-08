---
title: Overcoming WSL Hurdles in New Windows 11 Version
date: 2024-11-02T16:00:36.819Z
updated: 2024-11-07T21:31:28.798Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming WSL Hurdles in New Windows 11 Version
excerpt: This Article Describes Overcoming WSL Hurdles in New Windows 11 Version
keywords: Win11 Install Challenges,Overcoming Win11 Issues,Navigating Win11 Setup,Solving Win11 Errors,New Windows 11 Hurdles,Fixing Win11 Startups,Addressing Win11 Upgrade
thumbnail: https://thmb.techidaily.com/08c3aa17e0d4eaa82a6912035c2625c6aeb814a3c6b04915c834196ff8d149e8.jpg
---

## Overcoming WSL Hurdles in New Windows 11 Version

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049363/7443" target="_top" id="2049363">
  <img src="//a.impactradius-go.com/display-ad/7443-2049363" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049363/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://article-files.techidaily.com/new-2024-approved-laughter-legends-unwrapping-goofy-odyssey/"><u>[New] 2024 Approved 'Laughter Legends' - Unwrapping 'Goofy Odyssey'</u></a></li>
<li><a href="https://article-files.techidaily.com/new-slide-show-software-selection-from-ix-ios13-for-2024/"><u>[New] Slide Show Software Selection From IX-IOS13 for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-the-ultimate-guide-8-real-world-promotion-tools-for-videos/"><u>[Updated] 2024 Approved The Ultimate Guide 8 Real-World Promotion Tools for Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-iosandroid-techniques-extracting-twitters-gifs-for-2024/"><u>[Updated] IOS/Android Techniques Extracting Twitter's GIFs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1-mastering-multimedia-a-comprehensive-guide-on-leveraging-the-power-of-video-to-audio-conversion-with-factory-pro/"><u>1. Mastering Multimedia: A Comprehensive Guide on Leveraging the Power of Video-to-Audio Conversion with Factory Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-honor-magic-5-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Honor Magic 5 to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-and-mac4/"><u>動画画角トリミング: Windows & Macで実行可能な4手法</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/movavi-transforma-tus-videos-mkv-al-elegante-aac-por-internet-totalmente-gratuito/"><u>Movavi: Transforma Tus Videos MKV Al Elegante AAC Por Internet, Totalmente Gratuito</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-for-fixing-windows-grounded-issues-on-pc/"><u>Troubleshooting Guide for Fixing Windows 'Grounded' Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-on-transforming-vcd-audio-tracks-into-mp3-format/"><u>Ultimate Tutorial on Transforming VCD Audio Tracks Into MP3 Format</u></a></li>
<li><a href="https://win11.techidaily.com/uno-bindas-download-de-videos-de-aerobic-una-guia-completa-para-el-usuario-promedio/"><u>Uno Bindas Download De Vídeos De Aerobic: Una Guía Completa Para El Usuario Promedio</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/what-you-need-to-know-about-vanishing-shorts-thumbnails-on-youtube/"><u>What You Need to Know About Vanishing Shorts Thumbnails on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-dvd-8/"><u>Windows 11対応 DVD コピープロテクトを解除するための無料ツール、ベスト8推薦</u></a></li>
<li><a href="https://win11.techidaily.com/wmamp3-top3/"><u>WMAファイルからMP3への変換が簡単! ベストオンラインツールTOP3</u></a></li>
</ul></div>

