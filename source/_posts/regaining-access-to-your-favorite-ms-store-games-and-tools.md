---
title: Regaining Access to Your Favorite MS Store Games & Tools
date: 2024-06-25T11:41:18.123Z
updated: 2024-06-26T11:41:18.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Access to Your Favorite MS Store Games & Tools
excerpt: This Article Describes Regaining Access to Your Favorite MS Store Games & Tools
keywords: Gain Game MS Access,Restore Mighty Store,Re-Enter Game MS,Retrieve MS Store Tools,Unlock Favorite MG Games,Reclaim MG Toolset,Open MG Store Games
thumbnail: https://thmb.techidaily.com/b0d6f56b3e6efb0ac5881b741c9c12ef541c2aef549de1d2cc8ab07a2bd3f133.jpg
---

## Regaining Access to Your Favorite MS Store Games & Tools

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-icon-diminution-issues-on-windows-11/"><u>Reverse Icon Diminution Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/facilitating-regular-updates-toolbar-integration-in-the-windows-ui/"><u>Facilitating Regular Updates: Toolbar Integration in the Windows UI</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-full-potential-of-windows-customizations-via-winbubble/"><u>Unleash the Full Potential of Windows Customizations via WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-100mbps-wired-internet-limit-in-windows/"><u>Break Free From 100Mbps Wired Internet Limit in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/modify-mouse-indicator-for-personalized-windows-experience/"><u>Modify Mouse Indicator for Personalized Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-erratic-mouse-movement-in-windows/"><u>Ceasing Erratic Mouse Movement in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-display-order-easy-windows-method/"><u>Reversing Display Order: Easy Windows Method</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-retain-calculator-top-status-on-win-os/"><u>Methods to Retain Calculator Top Status on Win OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exclusive-list-the-top-10-camcorders-for-2ranking/"><u>2024 Approved  Exclusive List  The Top 10 Camcorders for 2Ranking</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-industrial-giants-taking-flight-heavy-duty-drones/"><u>[Updated] Industrial Giants Taking Flight  Heavy-Duty Drones</u></a></li>
<li><a href="https://extra-tips.techidaily.com/behind-the-screen-samsung-ue590-4k-freesync-analysis-for-2024/"><u>Behind the Screen  Samsung UE590 4K, FreeSync Analysis for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-mobile-media-mastery-best-mp4-to-mp3-converter-apps/"><u>New 2024 Approved Mobile Media Mastery Best MP4 to MP3 Converter Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-auditory-excellence-pinpointing-the-best-songs-to-accompany-your-montage-narrative/"><u>New Auditory Excellence Pinpointing the Best Songs to Accompany Your Montage Narrative</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-secrets-of-excellence-in-xbox-gameplay-screenshots/"><u>[New] Secrets of Excellence in Xbox Gameplay Screenshots</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-efficient-screen-recording-on-xbox-explained/"><u>2024 Approved  Efficient Screen Recording on Xbox Explained</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-making-your-voice-heard-in-the-podcast-realm/"><u>[Updated] In 2024, Making Your Voice Heard in the Podcast Realm</u></a></li>
<li><a href="https://youtube-data.techidaily.com/r-your-first-impressions-best-free-intro-makers-for-2024/"><u>Master Your First Impressions  Best Free Intro Makers for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/freeframe-studio-gameplay-capture-made-simple-in-24/"><u>FreeFrame Studio  Gameplay Capture Made Simple in '24</u></a></li>
</ul></div>
