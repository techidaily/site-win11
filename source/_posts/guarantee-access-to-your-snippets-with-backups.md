---
title: Guarantee Access to Your Snippets with Backups
date: 2024-11-21T17:53:45.243Z
updated: 2024-11-28T01:44:58.420Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guarantee Access to Your Snippets with Backups
excerpt: This Article Describes Guarantee Access to Your Snippets with Backups
keywords: Snippet Backup,Access Guaranteed,Secure Code Copies,Snip Safeguard,Uninterrupted Edits,Copy Protection,Data Redundancy
thumbnail: https://thmb.techidaily.com/de25cad762d1b1da1023e95cc7ce6ed0cc716ab658bda48c421a9e8a9c4e4418.png
---

## Guarantee Access to Your Snippets with Backups

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-memorable-moments-quick-and-clean-xbox-screenshots/"><u>[New] 2024 Approved Memorable Moments, Quick & Clean Xbox Screenshots</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-critical-examination-of-lg-bp350-screen-size-and-viewing-distance/"><u>[Updated] 2024 Approved Critical Examination of LG BP350 Screen Size & Viewing Distance</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-accolades-across-platforms-for-video-creators-for-2024/"><u>[Updated] Accolades Across Platforms for Video Creators for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-incorporating-vimeo-videos-seamlessly-in-microsoft-slides/"><u>[Updated] Incorporating Vimeo Videos Seamlessly in Microsoft Slides</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-little-gamers-treasure-trove-of-joy-for-2024/"><u>[Updated] Little Gamers' Treasure Trove of Joy for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-photo-edits-skewed-caption-creation-for-2024/"><u>[Updated] Photo Edits Skewed Caption Creation for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-quickened-cinema-of-corporate-presentations/"><u>2024 Approved Quickened Cinema of Corporate Presentations</u></a></li>
<li><a href="https://apple-account.techidaily.com/detailed-guide-on-removing-iphone-6s-activation-lock-without-previous-owner-by-drfone-ios/"><u>Detailed Guide on Removing iPhone 6s Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-graphics-enhancement-in-windows-11s-shielded-browsing/"><u>Innovative Graphics Enhancement in Windows 11'S Shielded Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-correction-windows-11-wow-mishaps/"><u>Mastering Error Correction: Windows 11 WoW Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-speech-to-text-the-whisper-desktop-way/"><u>Mastering Speech-to-Text: The Whisper Desktop Way</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-store-error-code-x00000000/"><u>Overcoming Windows 11 Store Error Code X00000000</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cmd-prompt-lack-of-admin-privileges/"><u>Resolving Cmd Prompt Lack of Admin Privileges</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-installing-kali-into-your-windows-ecosystem/"><u>Step by Step: Installing Kali Into Your Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-and-using-microsofts-code-assistant/"><u>Step-by-Step: Setting Up and Using Microsoft's Code Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-non-storage-feedback/"><u>Tackling Windows Camera Non-Storage Feedback</u></a></li>
<li><a href="https://win11.techidaily.com/transform-workflow-efficiency-mastering-flow-launcher-basics/"><u>Transform Workflow Efficiency: Mastering Flow Launcher Basics</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-powerful-video-cutting-function-allows-you-to-easily-cut-video-files-into-various-fragments/"><u>Updated In 2024, The Powerful Video Cutting Function Allows You to Easily Cut Video Files Into Various Fragments</u></a></li>
<li><a href="https://screen-capture.techidaily.com/virtual-realms-on-screen-comprehensive-techniques-for-gameplay-recording-for-2024/"><u>Virtual Realms on Screen Comprehensive Techniques for Gameplay Recording for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    