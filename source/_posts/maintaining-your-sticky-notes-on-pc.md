---
title: Maintaining Your Sticky Notes on PC
date: 2024-12-05T23:31:13.357Z
updated: 2024-12-13T05:32:22.270Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Maintaining Your Sticky Notes on PC
excerpt: This Article Describes Maintaining Your Sticky Notes on PC
keywords: Note Management PC,PC Sticky Reminder,Digital Note Holder,PC Sticky Save,PC Sticky Organizer,Virtual Post-It Pad,Keep Notes PC
thumbnail: https://thmb.techidaily.com/a6f140ff4ddda64bd14cec3cab639274aa642e4bb60e8fa6d0c6031cee3c6ed0.jpg
---

## Maintaining Your Sticky Notes on PC

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-holiday-memories-revisited-summertimes-best-vacation-flicks/"><u>[New] Holiday Memories Revisited Summertime’s Best Vacation Flicks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-a-look-into-the-future-of-camera-multicam-systems/"><u>[New] In 2024, A Look Into the Future of Camera Multicam Systems</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-no-expense-required-remove-coffee-stains-from-iphone-photos/"><u>[New] No Expense Required Remove Coffee Stains From iPhone Photos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-monitoring-friends-lost-in-instagram-world/"><u>[Updated] In 2024, Monitoring Friends Lost in Instagram World</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mold-personal-memes-that-resonate/"><u>[Updated] Mold Personal Memes That Resonate</u></a></li>
<li><a href="https://media-tips.techidaily.com/best-top-5-dvd-ripper-tools-convert-your-movies-from-dvd-to-flv-on-windows-and-macos/"><u>Best Top 5 DVD Ripper Tools: Convert Your Movies From DVD to FLV on Windows and macOS</u></a></li>
<li><a href="https://win11.techidaily.com/effective-integration-of-ethernet-and-wi-fi-in-a-windows-environment/"><u>Effective Integration of Ethernet & Wi-Fi in a Windows Environment</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-xiaomi-14-ultra-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Xiaomi 14 Ultra?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-access-denial-by-correcting-keys-in-windows-11/"><u>Overcoming Network Access Denial by Correcting Keys in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-revealing-the-invisible-registry-editor/"><u>Techniques for Revealing the Invisible 'Registry Editor'</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-system32-win11/"><u>The Ultimate Guide to System32 (Win11)</u></a></li>
<li><a href="https://fox-http.techidaily.com/transforming-virtual-worlds-enhancing-spark-ar-with-custom-luts-for-2024/"><u>Transforming Virtual Worlds Enhancing Spark AR with Custom LUTs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-explorer-not-recognizing-sd-remedy-tips/"><u>Windows Explorer Not Recognizing SD: Remedy Tips</u></a></li>
<li><a href="https://youtube-data.techidaily.com/be-shorts-monetization-how-to-make-money-on-youtube-shorts-for-2024/"><u>YouTube Shorts Monetization How to Make Money on YouTube Shorts for 2024</u></a></li>
</ul></div>

