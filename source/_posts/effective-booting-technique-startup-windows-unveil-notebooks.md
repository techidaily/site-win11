---
title: "Effective Booting Technique: Startup Windows, Unveil Notebooks"
date: 2024-11-30T02:07:00.942Z
updated: 2024-12-07T00:00:45.266Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Effective Booting Technique: Startup Windows, Unveil Notebooks"
excerpt: "This Article Describes Effective Booting Technique: Startup Windows, Unveil Notebooks"
keywords: Boot Windows Quickly,Launch PC Efficiently,Fast Startup Method,Optimal Device Activation,Proper System Initiate,Swift Notebook Opening,Accelerated Power On
thumbnail: https://thmb.techidaily.com/4be59755ae7994bb626513b3614a3ec947be3b56430323187fb64d462d24a601.jpg
---

## Effective Booting Technique: Startup Windows, Unveil Notebooks

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-snap-with-a-single-purpose-remove-bg-using-affinity/"><u>[New] Snap with a Single Purpose - Remove Bg Using Affinity</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-the-art-of-crafting-excellent-zoom-conferences/"><u>[Updated] 2024 Approved The Art of Crafting Excellent Zoom Conferences</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-seamless-srt-and-mp4-fusion-the-ultimate-guide-for-2024/"><u>[Updated] Seamless SRT & MP4 Fusion – The Ultimate Guide for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-yield-strategies-for-successful-money-making-on-mobile-youtube/"><u>Boosting Yield Strategies for Successful Money-Making on Mobile YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/disable-met-not-achieved-indicator-on-windows-11/"><u>Disable Met Not Achieved Indicator on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/get-to-know-the-samsung-galaxy-ring-price-points-release-schedule-and-in-depth-specs-analysis/"><u>Get to Know the Samsung Galaxy Ring: Price Points, Release Schedule & In-Depth Specs Analysis</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-xiaomi-14-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-seamless-guide-to-saving-gifs-on-iphonesandroids/"><u>In 2024, The Seamless Guide to Saving GIFs on iPhones/Androids</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-apex-legends-freezescrashes/"><u>Mastering Fixes for Apex Legends Freezes/Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-unauthorized-sign-in-bypassing-in-windows/"><u>Mastering the Art of Unauthorized Sign-In Bypassing in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mending-connections-addressing-windows-and-ea-server-linkage/"><u>Mending Connections: Addressing Windows and EA Server Linkage</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-windows-ssd-with-ssd-fresh-tips/"><u>Optimize Your Windows' SSD with SSD Fresh Tips</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-display-disruptions-on-windows-11/"><u>Preventing Display Disruptions on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-your-windows-11-taskbar-placement/"><u>Tailor Your Windows 11 Taskbar Placement</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-key-to-a-secure-ride-learn-how-to-find-and-enter-your-car-radio-password-successfully/"><u>The Key to a Secure Ride: Learn How to Find and Enter Your Car Radio Password Successfully</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-of-5-mobile-apps-to-expand-your-circle-of-friends/"><u>The Ultimate List of 5 Mobile Apps to Expand Your Circle of Friends</u></a></li>
<li><a href="https://win11.techidaily.com/windows-authentication-breakdown-standard-vs-microsoft-user-access-explored/"><u>Windows Authentication Breakdown: Standard vs Microsoft User Access Explored</u></a></li>
</ul></div>

