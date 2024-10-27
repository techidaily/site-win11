---
title: How to Securely Store and Recover Notes
date: 2024-10-19T17:12:03.930Z
updated: 2024-10-26T21:28:01.533Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Securely Store and Recover Notes
excerpt: This Article Describes How to Securely Store and Recover Notes
keywords: Note Storage Security,Safe Note Keeping,Data Backup for Notes,Protect Stored Notes,Secure Note Recovery,Encrypted Notebooks,Digital Note Preservation
thumbnail: https://thmb.techidaily.com/cbd55a60b36d243580c486b7896cd6baf0fe5a1c6ab330fc24fdad62a19d7e96.jpeg
---

## How to Securely Store and Recover Notes

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
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1521325/16446" target="_top" id="1521325">
  <img src="//a.impactradius-go.com/display-ad/16446-1521325" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1521325/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-twitsnap-secure-effortless-methods-for-downloading-tweets-videos/"><u>[Updated] In 2024, TwitSnap Secure Effortless Methods for Downloading Tweets' Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-masterful-color-grading-explore-these-7-methods/"><u>2024 Approved Masterful Color Grading Explore These 7 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/consolidation-of-data-on-windows-platforms/"><u>Consolidation of Data on Windows Platforms</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-driver-downloads-for-lenovo-x1-carbon-perfect-for-windows-10-and-7-users/"><u>Effortless Driver Downloads for Lenovo X1 Carbon - Perfect for Windows 10 & 7 Users</u></a></li>
<li><a href="https://win11.techidaily.com/excellence-in-portability-best-windows-laptops-unveiled/"><u>Excellence in Portability: Best Windows Laptops Unveiled</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/expert-roundup-comprehensive-camstudio-guide/"><u>Expert Roundup Comprehensive CamStudio Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Lava Blaze Curve 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/1716465516496-jumpstart-to-partner-elevation-secure-10k-views-in-minutes/"><u>Jumpstart to Partner Elevation Secure 10K Views in Minutes!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/live-streaming-made-easy-explore-manycam-top-notch-video-editing-and-virtual-cam-solutions/"><u>Live Streaming Made Easy: Explore ManyCam - Top Notch Video Editing & Virtual Cam Solutions</u></a></li>
<li><a href="https://facebook.techidaily.com/mastering-non-facebook-direct-message-apps/"><u>Mastering Non-Facebook Direct Message Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permission-blocks-in-windows-11/"><u>Overcoming Permission Blocks in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-enter-button-failures/"><u>Overcoming Windows Enter Button Failures</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-unintended-hotkey-activation-by-windows-keys/"><u>Remedying Unintended Hotkey Activation by Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/swift-switching-setup-arranging-windows-in-cascade-mode-win1110/"><u>Swift Switching Setup: Arranging Windows in Cascade Mode (Win11/10)</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-diverse-wallpapers-on-windows-11/"><u>The Ultimate Guide to Diverse Wallpapers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/title-enhance-icon-layout-in-winxi10-for-better-views/"><u>Title: Enhance Icon Layout in WinXI/10 for Better Views</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-your-steam-experience-halting-abrupt-downloads/"><u>Turbocharge Your Steam Experience: Halting Abrupt Downloads</u></a></li>
<li><a href="https://sound-issues.techidaily.com/unlocking-crystal-clear-audio-performance-fix-stutter-and-distortion-problems-in-win-107/"><u>Unlocking Crystal-Clear Audio Performance: Fix Stutter and Distortion Problems in Win 10/7</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/wolcen-launch-issues-an-in-depth-look-at-why-gamers-are-waiting-longer-than-expected/"><u>Wolcen Launch Issues – An In-Depth Look at Why Gamers Are Waiting Longer Than Expected</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    