---
title: Fixing the Shifting Default Printer on PCs
date: 2024-10-11T17:54:25.707Z
updated: 2024-10-15T18:59:35.308Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing the Shifting Default Printer on PCs
excerpt: This Article Describes Fixing the Shifting Default Printer on PCs
keywords: Print Default Fix PC,Reset Printer Pc,Change CPC Printer,Revert Default Printer,Restore Pc Printer,Unset Printer Pc Defaults,Edit Pc Printer Settings
thumbnail: https://thmb.techidaily.com/af63d40e10f4812d796851153ffe13a5133162342ccf375cf2e9337e968d99eb.jpg
---

## Fixing the Shifting Default Printer on PCs

 Setting a default printer on Windows saves you the hassle of manually selecting your preferred printer device across various apps and programs. But what if the default printer keeps changing on your Windows 10 or 11 PC?

 Here are some tips that will keep the default printer from changing on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Prevent Windows From Managing Your Default Printer

 If you have allowed Windows to manage your default printer, it may automatically change the printer depending on your current location. If you don't want that, use these steps to prevent Windows from changing the default printer.

1. Open the **Start menu** and click the **gear-shaped icon** to launch the Settings app.
2. Select **Bluetooth & devices** from the left sidebar.
3. Click on **Printers & scanners**.
4. Under the **Printer preferences** section, disable the toggle next to **Let Windows manage my default printer**.
5. Now select the printer you want to set as the default option.
6. Click the **Set as default** button at the top.  
![Stop Windows From Changing the Default Printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stop-windows-from-changing-the-default-printer.jpg)

 After you complete the above steps, Windows should not change the default printer on its own.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080317/19272" target="_top" id="2080317">
  <img src="//a.impactradius-go.com/display-ad/19272-2080317" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080317/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Edit the Relevant Registry Files

 If the default printer keeps changing even after you disable the **Let Windows manage my default printer** option, you will need to edit the registry files in order to fix the issue.

 Making incorrect changes to registry files can cause irreversible damage to your computer. Hence, it is important to follow the steps carefully and create a backup of all registry files before proceeding. If you need help with that, refer to our guide on how to [back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 Once you have done that, use these steps to edit the registry files:

1. Press **Win + S** to open the search menu.
2. Type **registry editor** in the search box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows NT > CurrentVersion > Windows**.
5. In the right pane, double-click the **LegacyDefaultPrinterMode** key to edit it.
6. Enter **1** in the **Value data** field and click **OK**.  
![Stop Windows From Changing the Default Printer via Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stop-windows-from-changing-the-default-printer-via-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857865/11832" target="_top" id="857865">
  <img src="//a.impactradius-go.com/display-ad/11832-857865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857865/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after completing the above steps, and then use one of [the many ways to set the default printer on your Windows PC](https://www.makeuseof.com/set-default-printer-windows-11/). After that, check if the issue occurs again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541">
  <img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Try Some Generic Windows Fixes

 In most cases, one of the above tips should solve your problem. Nonetheless, if the problem persists, you can try some generic solutions to address it.

* **Remove unused printers:**[Removing or uninstalling printers on Windows](https://www.makeuseof.com/windows-remove-printer/) that are no longer available can help resolve the issue of Windows constantly changing the default printer. While you’re at it, you should also delete any printer-related software to avoid potential conflicts.
* **Scan for malware:** The presence of malware or viruses on your PC can also impact system settings and lead to such irregularities. To check for this possibility, you can [use PowerShell to scan your Windows PC for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or other threats.
* **Install the latest Windows updates:** Windows updates not only bring new features to your PC but can also help resolve various issues like this one. Hence, it’s a good idea to [install any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) if you haven’t already.
* **Create a new user account:** Problems with your current user account can also cause the default printer to keep changing on Windows. This can happen if some of the user account files associated with your account have become corrupted. If that’s the case, your best option is to [create and switch to a new user account on Windows](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1883998/19272" target="_top" id="1883998">
  <img src="//a.impactradius-go.com/display-ad/19272-1883998" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1883998/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Setting the Default Printer Repeatedly on Windows

 It can be frustrating if the default printer on your Windows computer keeps changing without your input. Fortunately, it’s possible to stop that from happening with the solutions mentioned above.

 Here are some tips that will keep the default printer from changing on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-mastering-undersea-video-7-easy-to-follow-techniques/"><u>[New] Mastering Undersea Video 7 Easy-to-Follow Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/defying-conformity-a-journey-through-edges-microphonecamera-restrictions/"><u>Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-windows-photography-with-key-combinations/"><u>Effortless Windows Photography with Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/from-voice-to-words-a-guide-to-whisper-transcription/"><u>From Voice to Words: A Guide to Whisper Transcription</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-connectivity-hurdles-bluetooth-pin-problems-in-win11win10/"><u>How To Overcome Connectivity Hurdles: Bluetooth Pin Problems in Win11/Win10</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ffmpeg-analysis-maintaining-audio-format-integrity/"><u>In 2024, FFmpeg Analysis Maintaining Audio Format Integrity</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722968454777-nvidia-rtx-2080-latest-driver-version-available-now-for-multiple-windows-oses/"><u>NVIDIA RTX 2080 Latest Driver Version Available Now for Multiple Windows OSes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/streamlined-approach-to-validate-your-yt-identity/"><u>Streamlined Approach to Validate Your YT Identity</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-corruption-fixes-in-windows-1011/"><u>Streamlining Data Corruption Fixes in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-resolve-inkjet-and-laser-printer-conflicts/"><u>Tactics to Resolve Inkjet and Laser Printer Conflicts</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-surface-upgrade-compendium-for-improved-functionality/"><u>The Ultimate Surface Upgrade Compendium for Improved Functionality</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-20-uncommon-secrets-to-mastering-your-nintendo-switch/"><u>Top 20 Uncommon Secrets to Mastering Your Nintendo Switch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-access-is-forbidden-problem-on-your-site-403-error/"><u>Troubleshooting the 'Access Is Forbidden' Problem on Your Site (403 Error)</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/ultimate-guide-iphone-data-recovery-without-a-previous-backup-using-stellar/"><u>Ultimate Guide: IPhone Data Recovery Without a Previous Backup Using Stellar</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-potential-metaverse-marketing-secrets-for-2024/"><u>Unlocking Potential Metaverse Marketing Secrets for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/why-chatgpt-cannot-spot-its-own-writing/"><u>Why ChatGPT Cannot Spot Its Own Writing</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    