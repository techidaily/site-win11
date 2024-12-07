---
title: "Efficiency Tips: Starting Windows and Immediately Unlocking Notebooks"
date: 2024-12-02T03:23:58.408Z
updated: 2024-12-07T09:31:17.418Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficiency Tips: Starting Windows and Immediately Unlocking Notebooks"
excerpt: "This Article Describes Efficiency Tips: Starting Windows and Immediately Unlocking Notebooks"
keywords: Window Start Efficiency,Lock Notebook Quickly,Laptop Security Hacks,Fast System Boot PC,Secure Devices Instantly,Optimize PC Shutdown,Accelerate Device Unlock
thumbnail: https://thmb.techidaily.com/d68b2c77d9bc6992a97b4d45a79ba7275bc346cfc58c9a3e57e1e4c2f555ef0b.jpg
---

## Efficiency Tips: Starting Windows and Immediately Unlocking Notebooks

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-exclusive-reveal-top-downloading-tools-for-fans-of-apples-ios-and-facebook/"><u>[New] Exclusive Reveal Top Downloading Tools for Fans of Apple's iOS and Facebook</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-simplifying-the-process-of-enabling-virtual-screen-on-meet/"><u>[New] In 2024, Simplifying the Process of Enabling Virtual Screen on Meet</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/onetary-spectrum-a-glimpse-into-mr-beasts-world/"><u>[New] Monetary Spectrum A Glimpse Into Mr. Beast’s World</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-a-newcomers-primer-to-av1-codecs-for-2024/"><u>[Updated] A Newcomer’s Primer to AV1 Codecs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-widget-integration-in-windows-11/"><u>Cutting-Edge Widget Integration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effective-solutions-to-bypass-disallowed-logins-on-windows/"><u>Effective Solutions to Bypass Disallowed Logins on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-troubleshooting-tips-for-a-non-operational-wsreset/"><u>Essential Troubleshooting Tips for a Non-Operational WSReset</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-dev-drive-essential-setup-for-windows-11-programmers/"><u>Exploring Dev Drive: Essential Setup for Windows 11 Programmers</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-realme-12-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-and-windows-the-integrity-disruption-scenario/"><u>Ftdibus.sys & Windows: The Integrity Disruption Scenario</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-windows-11-users-on-restarting-mobile-hotspots/"><u>Guiding Windows 11 Users on Restarting Mobile Hotspots</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-samsung-galaxy-a23-5g-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Samsung Galaxy A23 5G FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-tackle-error-code-0x0000004e/"><u>Quick Fixes to Tackle Error Code 0X0000004E</u></a></li>
<li><a href="https://win-blog.techidaily.com/red-dead-redemption-2-stuck-here-are-proven-fixes-for-incessant-loading-screens/"><u>Red Dead Redemption 2 Stuck? Here Are Proven Fixes for Incessant Loading Screens</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-productivity-select-7-innovative-window-11-widgets/"><u>Reimagine Productivity: Select 7 Innovative Window 11 Widgets</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-graphics-card-info-windows-11-edition/"><u>Unlocking Graphics Card Info: Windows 11 Edition</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-enhancing-video-experience-the-role-of-background-music-integration/"><u>Updated 2024 Approved Enhancing Video Experience The Role of Background Music Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-unlocking-the-dialer/"><u>Win 11: Unlocking the Dialer</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    