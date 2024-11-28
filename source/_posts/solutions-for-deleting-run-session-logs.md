---
title: Solutions for Deleting Run Session Logs
date: 2024-11-26T22:00:13.574Z
updated: 2024-11-27T23:43:56.414Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Deleting Run Session Logs
excerpt: This Article Describes Solutions for Deleting Run Session Logs
keywords: Delete Session Logs,Clear Run Logs,Remove Activity Records,End Session Traces,Erase Running Sessions,Clear Session Data,Deletion of Run Logs
thumbnail: https://thmb.techidaily.com/37be59bd79492103146c553d037e355365677b2067dd8fea4392e3520b311142.jpg
---

## Solutions for Deleting Run Session Logs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-techniques-to-minimize-motion-blur-from-drones/"><u>[New] 2024 Approved Techniques to Minimize Motion Blur From Drones</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-next-gen-recording-nine-leading-webmicrone-recorders-23/"><u>[Updated] In 2024, Next-Gen Recording Nine Leading Webmicrone Recorders ('23)</u></a></li>
<li><a href="https://win-webster.techidaily.com/1-comprendre-la-suppression-automatique-des-fichiers-dans-votre-corbeille-resolu/"><u>1. Comprendre La Suppression Automatique Des Fichiers Dans Votre Corbeille [Résolu]</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-3d-lut-expertise-in-a-quick-learning-journey/"><u>2024 Approved 3D LUT Expertise in a Quick Learning Journey</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/4-camera-floodlight-bundle-for-only-80-exclusive-offer/"><u>4-Camera Floodlight Bundle for Only $80 - Exclusive Offer!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/atomi-alpha-electric-scooter-examined-a-blend-of-performance-and-panache/"><u>Atomi Alpha Electric Scooter Examined: A Blend of Performance and Panache</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-win-11-widget-features-efficiency-or-frivolous/"><u>Delving Into Win 11 Widget Features - Efficiency or Frivolous?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-roblox-fatal-app-failures-in-windows/"><u>Fixing Roblox Fatal App Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reinstating-deleted-windows-update-service/"><u>Guide to Reinstating Deleted Windows Update Service</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-malwarebytes-unable-to-connect-to-service-error-in-windows-11-and-11/"><u>How to Fix Malwarebytes’ “Unable to Connect to Service” Error in Windows 11 & 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-oppo-find-x6-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Oppo Find X6 to New Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-control-rgb-lighting-in-windows-11/"><u>Learn to Control RGB Lighting in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-ip-retrieval-via-command-line/"><u>Mastering: Windows IP Retrieval via Command Line</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/next-gen-law-practice-boost-how-microsoft-copilot-enhances-singapores-legal-tech-infrastructure-zdnet/"><u>Next-Gen Law Practice Boost: How Microsoft Copilot Enhances Singapore's Legal Tech Infrastructure | ZDNet</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/quiet-browsing-of-fb-narratives-for-2024/"><u>Quiet Browsing of FB Narratives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/take-your-windows-11-search-to-the-next-level-top-five-insights/"><u>Take Your Windows 11 Search to the Next Level: Top Five Insights</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-creative-potential-using-paint-cocreator-to-make-ai-images-on-windows-11/"><u>Unleashing Your Creative Potential: Using Paint Cocreator to Make AI Images on Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    