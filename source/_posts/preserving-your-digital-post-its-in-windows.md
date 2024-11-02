---
title: Preserving Your Digital Post-Its in Windows
date: 2024-10-26T23:41:00.655Z
updated: 2024-11-01T16:03:09.215Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preserving Your Digital Post-Its in Windows
excerpt: This Article Describes Preserving Your Digital Post-Its in Windows
keywords: Save Notes WInDS,Digital Note Storage,Keep ITEMS Windows,Secure Windows Notebooks,Save Digital Sticky Notes,Windows Sticky Info Safe,Store Windows Notes Easily
thumbnail: https://thmb.techidaily.com/d5d13fb577cc5620ebbaf2970abea56dace77d9e5a84a022ba162f616f0fcf69.png
---

## Preserving Your Digital Post-Its in Windows

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

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/nstant-thumbnails-for-fortnite-gameplay-for-2024/"><u>[New] Instant Thumbnails for Fortnite Gameplay for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-a-stepwise-approach-to-youtube-caption-addition/"><u>[Updated] 2024 Approved A Stepwise Approach to YouTube Caption Addition</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-worlds-premier-content-creators-ranked-by-subscriber-count/"><u>[Updated] 2024 Approved World's Premier Content Creators Ranked By Subscriber Count</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-pioneering-metaverse-brand-presence/"><u>[Updated] In 2024, Pioneering Metaverse Brand Presence</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-cuts-windows-11-shutdown-shortcuts/"><u>Efficient Cuts: Windows 11 Shutdown Shortcuts</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevating-brand-presence-a-guide-to-influencer-marketing-on-instagram/"><u>Elevating Brand Presence A Guide to Influencer Marketing on Instagram</u></a></li>
<li><a href="https://driver-error.techidaily.com/enabling-sound-device-in-windows-10-via-usb-connection/"><u>Enabling Sound Device in Windows 10 via USB Connection</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-guide-to-5-prime-slow-motion-cameras/"><u>Essential Guide to 5 Prime Slow Motion Cameras</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-secrets-to-successful-hash-tag-application-for-improved-campaigns-on-facebook/"><u>In 2024, Secrets to Successful Hash Tag Application for Improved Campaigns on Facebook</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/optimized-hard-drive-error-detection/"><u>Optimized Hard Drive Error Detection</u></a></li>
<li><a href="https://win11.techidaily.com/patching-the-black-screen-problem-in-window-8-pcs/"><u>Patching the Black Screen Problem in Window 8 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-disk-technology-using-windows-features/"><u>Pinpoint Disk Technology Using Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-streamlining-remote-desktop-on-win-11/"><u>Pro-Tips for Streamlining Remote Desktop on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-resource-in-use-status-on-windows-11-devices/"><u>Steps to Overcome Resource In-Use Status on Windows 11 Devices</u></a></li>
</ul></div>

