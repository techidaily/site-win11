---
title: Preserve & Propagate Windows' Note Data
date: 2024-12-03T05:38:59.330Z
updated: 2024-12-06T22:11:37.251Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preserve & Propagate Windows' Note Data
excerpt: This Article Describes Preserve & Propagate Windows' Note Data
keywords: Save Notes Windows,Note Data Security,Windows Data Preservation,Protecting Windows Notes,Extend Note Lifespan,Backup Windows Notebooks,Secure Windows Note Files
thumbnail: https://thmb.techidaily.com/857cad2a82232e03f92aad9809b4a548e4964a8c9aa59aabf55be668d5e1078d.jpg
---

## Preserve & Propagate Windows' Note Data

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-analyzing-splitcams-place-among-best-recorders/"><u>[Updated] 2024 Approved Analyzing SplitCam's Place Among Best Recorders</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-top-8-4k-playback-powerhouses-unveiled/"><u>[Updated] 2024 Approved Top 8 4K Playback Powerhouses Unveiled</u></a></li>
<li><a href="https://solve-popular.techidaily.com/ai-europe-201/"><u>AI Europe 201</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-realme-c67-5g-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Realme C67 5G? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/expedite-finding-graphics-model-in-windows-11-haven/"><u>Expedite: Finding Graphics Model in Windows 11 Haven</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-steam-error-content-servers-not-reachable-in-windows/"><u>Fixing Steam Error: Content Servers Not Reachable in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-s23-fe-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy S23 FE Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-microsoft-store-error-code-0x80073cf3-in-windows/"><u>Mitigating Microsoft Store Error Code 0X80073CF3 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-ms-store-bugs-error-x80072f17-solution/"><u>Navigating MS Store Bugs: Error X80072F17 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/power-uninstalling-printers-on-windows-11-os/"><u>Power Uninstalling Printers on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-windows-error-image-id-0x80780119/"><u>Remedy for Windows Error: Image ID 0X80780119</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-vivo-y78t-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Vivo Y78t.</u></a></li>
<li><a href="https://win11.techidaily.com/transform-desktop-experience-with-smart-wmlayouts/"><u>Transform Desktop Experience with Smart WMLayouts</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-unresponsive-shift-key-a-comprehensive-guide/"><u>Troubleshoot & Fix Unresponsive Shift Key: A Comprehensive Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/visual-storytelling-and-auditory-art-converting-instagrams-to-songs-for-2024/"><u>Visual Storytelling & Auditory Art Converting Instagrams to Songs for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    