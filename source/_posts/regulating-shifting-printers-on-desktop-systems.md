---
title: Regulating Shifting Printers on Desktop Systems
date: 2024-12-10T05:45:44.280Z
updated: 2024-12-12T18:24:54.060Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regulating Shifting Printers on Desktop Systems
excerpt: This Article Describes Regulating Shifting Printers on Desktop Systems
keywords: Print Cost Control,Printer Price Regulation,Desk Printer Management,Quality Print Settings,Efficient Printer Use,Printer Performance Optimization,Desktop Printer Maintenance
thumbnail: https://thmb.techidaily.com/0be5a94dd3d4589909d5a9db46fde9f5e7dc17aa86b034cba9990542387160cd.jpg
---

## Regulating Shifting Printers on Desktop Systems

 Setting a default printer on Windows saves you the hassle of manually selecting your preferred printer device across various apps and programs. But what if the default printer keeps changing on your Windows 10 or 11 PC?

 Here are some tips that will keep the default printer from changing on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after completing the above steps, and then use one of [the many ways to set the default printer on your Windows PC](https://www.makeuseof.com/set-default-printer-windows-11/). After that, check if the issue occurs again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Some Generic Windows Fixes

 In most cases, one of the above tips should solve your problem. Nonetheless, if the problem persists, you can try some generic solutions to address it.

* **Remove unused printers:**[Removing or uninstalling printers on Windows](https://www.makeuseof.com/windows-remove-printer/) that are no longer available can help resolve the issue of Windows constantly changing the default printer. While you’re at it, you should also delete any printer-related software to avoid potential conflicts.
* **Scan for malware:** The presence of malware or viruses on your PC can also impact system settings and lead to such irregularities. To check for this possibility, you can [use PowerShell to scan your Windows PC for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or other threats.
* **Install the latest Windows updates:** Windows updates not only bring new features to your PC but can also help resolve various issues like this one. Hence, it’s a good idea to [install any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) if you haven’t already.
* **Create a new user account:** Problems with your current user account can also cause the default printer to keep changing on Windows. This can happen if some of the user account files associated with your account have become corrupted. If that’s the case, your best option is to [create and switch to a new user account on Windows](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Setting the Default Printer Repeatedly on Windows

 It can be frustrating if the default printer on your Windows computer keeps changing without your input. Fortunately, it’s possible to stop that from happening with the solutions mentioned above.

 Here are some tips that will keep the default printer from changing on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/approved-does-immediate-subscribing-affect-content-recommendations/"><u>2024 Approved Does Immediate Subscribing Affect Content Recommendations?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-inshot-analysis-video-edition-showdown/"><u>2024 Approved InShot Analysis Video Edition Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-techniques-to-run-task-manager-admin-style-on-windows-11/"><u>Command Prompt Techniques to Run Task Manager Admin-Style on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1723005468576-cyberpunk-2077-black-screen-dilemma-top-solutions-revealed/"><u>Cyberpunk 2077 Black Screen Dilemma: Top Solutions Revealed</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-bargains-with-oodles-complimentary-community-ads/"><u>Discover Bargains with Oodle's Complimentary Community Ads</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-ultimate-2022-mobile-gaming-experience-with-zdnets-top-phones-for-gamers/"><u>Discover the Ultimate 2022 Mobile Gaming Experience with ZDNet's Top Phones for Gamers</u></a></li>
<li><a href="https://fox-info.techidaily.com/essential-steps-for-diminishing-audio-intensity-in-lumafusion/"><u>Essential Steps for Diminishing Audio Intensity in Lumafusion</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-nearby-networking-solutions-googles-vs-microsofts-method/"><u>Evaluating Nearby Networking Solutions: Google's Vs. Microsoft's Method</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-management-app-snafus-quickly/"><u>Fix Windows Management App Snafus Quickly</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-assessing-ffmpegs-prowess-in-original-audio-extraction/"><u>In 2024, Assessing FFmpeg’s Prowess in Original Audio Extraction</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-adobe-illustrator-adding-smooth-motion-blurs-for-2024/"><u>Mastering Adobe Illustrator Adding Smooth Motion Blurs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-widget-alerts-management/"><u>Mastering Windows 11 Widget Alerts Management</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-latest-in-computing-at-toms-hardware-corner/"><u>Navigating the Latest in Computing at Tom's Hardware Corner</u></a></li>
<li><a href="https://win11.techidaily.com/scaling-windows-11-taskbar-icons-effectively/"><u>Scaling Windows 11 Taskbar Icons Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/seven-strategies-for-eternally-deactivating-windows-defender/"><u>Seven Strategies for Eternally Deactivating Windows Defender</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-task-execution-fast-track-windows-outlook/"><u>Streamline Task Execution: Fast-Track Windows Outlook</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/teslas-latest-automaton-stay-updated-on-news-gossip-speculated-cost-and-launch-details/"><u>Tesla's Latest Automaton: Stay Updated on News, Gossip, Speculated Cost & Launch Details</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    