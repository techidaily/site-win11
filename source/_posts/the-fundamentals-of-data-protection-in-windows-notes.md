---
title: The Fundamentals of Data Protection in Windows Notes
date: 2024-11-24T02:52:05.921Z
updated: 2024-11-27T19:01:53.882Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Fundamentals of Data Protection in Windows Notes
excerpt: This Article Describes The Fundamentals of Data Protection in Windows Notes
keywords: Data Safety Windows Notebooks,Windows Note Protection Basics,Secure Windows Takeout Tips,Essential Privacy Windows Notes,Core Data Security in Windows,Fundamentals of Windows Note Shielding,Windows Notes Privacy Guidelines
thumbnail: https://thmb.techidaily.com/6afde60cdf2c4ed08818a0c3bb279e1893a9ceb4675945a4f5d57ab92e9d6ef9.jpg
---

## The Fundamentals of Data Protection in Windows Notes

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevating-your-channels-profits-with-impactful-and-effective-trailers/"><u>[New] In 2024, Elevating Your Channels' Profits with Impactful and Effective Trailers</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-ensuring-flawless-sending-of-large-videos-from-iphone-to-mac-pc/"><u>[Updated] 2024 Approved Ensuring Flawless Sending of Large Videos From iPhone to Mac PC</u></a></li>
<li><a href="https://solve-latest.techidaily.com/5oplusq5y2h5zob54mm6io96yep77ya5aqs6auu5oqa6kgt6iih5oiq5yqf5qgi5l6l/"><u>提升品牌能量：媒體技術與成功案例</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-color-dynamics-rgb-on-windows-11/"><u>Configuring Color Dynamics: RGB on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/declutter-minds-notes-organized-with-obsidian-canvas-techniques/"><u>Declutter Minds: Notes Organized with Obsidian Canvas Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-dismantle-persistent-0x800f0831-issues/"><u>Expert Guide to Dismantle Persistent 0X800F0831 Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-game-on-pioneer-top-choices-in-windows-10s-new-games-and-apps/"><u>In 2024, Game On, Pioneer Top Choices in Windows 10’S New Games and Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-saving-gifs-from-twitter-ios-and-android-guide/"><u>In 2024, Saving GIFs From Twitter IOS & Android Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-error-code-0x8007045d-in-windows-11/"><u>Overcoming the Error Code 0X8007045d in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/precision-power-and-aesthetics-note-taking-with-obsidian-canvas/"><u>Precision, Power & Aesthetics - Note-Taking with Obsidian Canvas</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/proven-film-edits-that-enhance-visual-storytelling-for-2024/"><u>Proven Film Edits That Enhance Visual Storytelling for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restore-lost-speaker-settings-with-ease-on-windows-pc/"><u>Restore Lost Speaker Settings with Ease on Windows PC</u></a></li>
<li><a href="https://facebook.techidaily.com/scoping-out-social-network-supporters/"><u>Scoping Out Social Network Supporters</u></a></li>
<li><a href="https://win11.techidaily.com/secure-data-access-on-windows-pc-without-online-network/"><u>Secure Data Access on Windows PC without Online Network</u></a></li>
<li><a href="https://games-able.techidaily.com/the-top-ten-terrors-of-trial-and-tribulation-in-games/"><u>The Top Ten Terrors of Trial and Tribulation in Games</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-for-libgdkwin32-20-missing-dll-files/"><u>Troubleshooting Tips for 'Libgdk_win32-2.0' Missing DLL Files</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-systems-lost-dragging-feature-in-win11/"><u>Unlock Your System's Lost Dragging Feature in Win11</u></a></li>
</ul></div>

