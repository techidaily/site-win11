---
title: How to Handle Windows' Error Code 1053 for Non-Responsive Services
date: 2024-12-31T19:04:16.840Z
updated: 2025-01-06T21:01:20.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Handle Windows' Error Code 1053 for Non-Responsive Services
excerpt: This Article Describes How to Handle Windows' Error Code 1053 for Non-Responsive Services
keywords: Fixing Windows 1033 Error,Troubleshoot Code 1053,Service Management in WinError,Resolve Non-Responsive Services,Remedy Windows 10 Error,Managing WinService Disruption,Overcome Code 1053 in Windows
thumbnail: https://thmb.techidaily.com/a018e8a9f0d428a05e6f8e5f431115fbc243ce5256805ecd4c390c919b578ebe.jpg
---

## How to Handle Windows' Error Code 1053 for Non-Responsive Services

 Windows has many services that it needs for the running of OS features and task operation. Error 1053 is an issue some users report occurring when they try to manually start required services via the Services app. It can also happen when users start programs. The error 1053 message says, “The service did not respond to the start or control request in a timely fashion.”

 Windows can’t start whatever service for which error 1053 occurs. Consequently, Windows features, software packages, and tasks that need affected services won’t work. This is how you can fix error 1053 on a Windows PC.

## 1\. Repair Corrupted System Files With SFC and DISM Scans

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command.jpg)

 It could be the case that some corrupted system files required for a service operation are causing error 1053\. To address such a possibility, run System File Checker and Deployment Image Service Management command scans.

 Our guide to [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) gives you the full lowdown on how to run both the SFC and DISM tools via the Command Prompt.

## 2\. Check for and Install Any Pending Windows Updates

 Microsoft often rolls out patch updates to fix Windows 11/10 bugs and issues. Although there isn’t a specific Microsoft hotfix for error 1053, installing available Windows cumulative or patch updates might still resolve this issue for some users.

 Our guide to [manually installing Windows updates](https://www.makeuseof.com/update-windows-manually/) includes instructions for how you can apply this potential solution.

![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/check-for-updates-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Tweak the Control Registry Key

 Tweaking the **Control** registry key is one of the most widely user-confirmed potential fixes for error 1053\. Applying this potential fix sets a new timeout value for services, which extends the response time frame. This gives services more time to respond. So, try editing the **Control** registry key as follows:

1. To open Registry Editor, press the **Windows** logo + **R** keys simultaneously, input a **regedit** command into Run, and click **OK**.
2. Click within the Registry Editor’s address bar and erase the current path.
3. Bring up the **Control** key by inputting this path in the address bar and pressing **Enter**:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\`
4. Skip to step six if you can see a **ServicesPipeTimeout** DWORD in the **Control** key. If that DWORD isn't there, click the **Control** key with your right mouse button and select **New** \> **DWORD** **(32-bit) Value**.  
![The New and DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-value-option.jpg)
5. Next, enter **ServicesPipeTimeout** in the DWORD text box.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The ServicesPipeTimeout DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/servicespipetimeout-dword.jpg)
6. Double-click **ServicesPipeTimeout** to bring up a window for editing that DWORD value.
7. Then input **180000** into the **Value** box and select **OK**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window.jpg)
8. Click **X** at the top right of the Registry Editor window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Select **Power** and **Restart** on your Windows Start menu.

## 4\. Run Network Reset Commands

 This potential resolution could work when error 1053 occurs for network-related services. Clearing the DNS cache and resetting the Winsock catalog can address network configuration issues causing error 1053\.

 Fortunately, it's very easy to [reset the Winsock catalog](https://www.makeuseof.com/reset-winsock-catalog-windows/) and [flush the DNS cache](https://www.makeuseof.com/flush-dns-cache-windows-11/) on a Windows PC.

## 5\. Take Ownership of Affected Software’s Installation Directory

 If error 1053 occurs when utilizing or starting software, the affected program might not be able to execute a service because you don’t have ownership of it. To remedy that, try taking ownership of the software’s EXE (application) file.

 To do so, check out this article about [taking ownership of a folder](https://www.makeuseof.com/windows-10-11-own-folder/) in Windows 11/10\. The steps for taking ownership of a software package’s EXE file are the same as for a folder.

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-security-settings-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reinstall the Affected Software Packages

 Reinstalling affected software is another potential fix for error 1053 when it occurs when you try to start a desktop app. Applying this possible solution will likely address any issues with the software that could be causing the error. Uninstall the affected desktop app with a suitable method in this article about [removing software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/uninstall-option.jpg)

 Restart Windows before reinstalling the software. Download the newest version of the same software from the publisher’s website. Then open the folder that includes your file downloads and double-click on the downloaded installer pack to reinstall the desktop app.

## Get Error 1053 Sorted on Your Windows PC

 Error 1053 is an annoying service issue that can hinder feature and software utilization on Windows PCs. Many users have been able to resolve error 1053 by applying the possible solutions covered here. Resolution three often works, but you might have to try some of the alternative potential fixes to address other possible causes.

 Windows can’t start whatever service for which error 1053 occurs. Consequently, Windows features, software packages, and tasks that need affected services won’t work. This is how you can fix error 1053 on a Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-quick-guide-iphones-easiest-screen-recording-method/"><u>[New] 2024 Approved Quick Guide IPhone's Easiest Screen Recording Method</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-simplifying-the-art-of-mac-screen-recording-a-keyboard-gurus-insight/"><u>[New] 2024 Approved Simplifying the Art of Mac Screen Recording A Keyboard Guru's Insight</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-20-quick-video-concepts-for-aspiring-vloggers/"><u>[New] In 2024, 20 Quick Video Concepts for Aspiring Vloggers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-expert-advice-capturing-and-storing-twitter-vids-on-phones/"><u>[New] In 2024, Expert Advice Capturing and Storing Twitter Vids on Phones</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-discover-the-depths-of-funimate/"><u>2024 Approved Discover the Depths of Funimate</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/an-authentic-evaluation-of-recordcast-services/"><u>An Authentic Evaluation of RecordCast Services</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-user-profiles-with-precise-gpo-settings-in-win-oses/"><u>Customizing User Profiles with Precise GPO Settings in Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-platform-user-service-stability-on-windows/"><u>Enhancing Platform User Service Stability on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unauthorized-file-access-in-windows-os/"><u>How to Clear Unauthorized File Access in Windows OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-nubia-red-magic-9-pro-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Nubia Red Magic 9 Pro Phone Now with These Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-pixelpilots-pathway-navigating-screen-recorder-landscapes/"><u>In 2024, PixelPilot's Pathway Navigating Screen Recorder Landscapes</u></a></li>
<li><a href="https://win11.techidaily.com/scribble-to-screen-top-8-notetaking-alternatives-for-windows-pcs/"><u>Scribble to Screen: Top 8 Notetaking Alternatives for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-viewing-best-free-windows-media-players/"><u>Streamline Your Viewing: Best Free Windows Media Players</u></a></li>
</ul></div>

