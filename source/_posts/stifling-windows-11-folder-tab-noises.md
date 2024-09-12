---
title: Stifling Windows 11 Folder Tab Noises
date: 2024-09-11T09:34:40.216Z
updated: 2024-09-12T09:34:40.216Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stifling Windows 11 Folder Tab Noises
excerpt: This Article Describes Stifling Windows 11 Folder Tab Noises
keywords: Stop Win11 Noise,Silent Tab Fix,Quiet Windows Folders,Hush Tab Glitch,Dampen WinTab Sound,Reduce Filetab Wrangling,Mute Tab Clicks Windows
thumbnail: https://thmb.techidaily.com/4f7878f35a5617dd30422b38a025795d7b590bfdd2ba7a274f89a9a6584223ab.jpg
---

## Stifling Windows 11 Folder Tab Noises

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-secure-and-enhance-slack-communications-with-top-10-free-audio-apps/"><u>[New] 2024 Approved Secure & Enhance Slack Communications with Top 10 Free Audio Apps</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-essential-drone-buyers-checklist-top-factors-to-ponder-for-2024/"><u>[New] Essential Drone Buyer's Checklist Top Factors to Ponder for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-culinary-craftsmanship-innovative-naming-for-food-shows/"><u>[Updated] 2024 Approved Culinary Craftsmanship Innovative Naming for Food Shows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-double-edged-sword-of-virtual-reality/"><u>[Updated] The Double-Edged Sword of Virtual Reality</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-videographers-guide-to-capturing-sports-competitions/"><u>[Updated] Videographer's Guide to Capturing Sports Competitions</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-breaking-down-sync-a-thorough-review-of-lgs-uhd68-display/"><u>2024 Approved Breaking Down Sync A Thorough Review of LG's UHD68 Display</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-color-techniques-for-professional-visual-narratives/"><u>2024 Approved Expert Color Techniques for Professional Visual Narratives</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-comprehensive-guide-to-capturing-perfect-instagram-covers/"><u>2024 Approved The Comprehensive Guide to Capturing Perfect Instagram Covers</u></a></li>
<li><a href="https://win11.techidaily.com/combating-valorant-communication-breakdowns-on-windows-78/"><u>Combating Valorant Communication Breakdowns on Windows 7/8</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-activities-deactivate-windows-eye-on-users/"><u>Concealing Activities: Deactivate Windows' Eye on Users</u></a></li>
<li><a href="https://win11.techidaily.com/discover-windows-11-taskbar-improvements/"><u>Discover Windows 11 Taskbar Improvements</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-obstacles-restoring-system-calls-on-win1111/"><u>Eliminating Obstacles: Restoring System Calls on Win11/11</u></a></li>
<li><a href="https://win11.techidaily.com/escalate-your-internet-speed-triumph-over-windows-100mbps-barrier/"><u>Escalate Your Internet Speed: Triumph Over Windows' 100Mbps Barrier</u></a></li>
<li><a href="https://win11.techidaily.com/essential-complaints-for-new-windows-11-users/"><u>Essential Complaints for New Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-for-configuring-dns-in-windows-11/"><u>Expert Strategies for Configuring DNS in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/from-amateur-to-pro-instagram-video-tutorials-for-2024/"><u>From Amateur to Pro Instagram Video Tutorials for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/guide-to-selecting-the-perfect-4k-camera-lens-for-2024/"><u>Guide to Selecting the Perfect 4K Camera Lens for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-system-errors-following-a-windows-update/"><u>How to Correct System Errors Following a Windows Update</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-asus-rog-phone-7-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Asus ROG Phone 7 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-infinix-note-30-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Infinix Note 30 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-audio-error-windows-11-0xc00d36b4/"><u>How to Mend Audio Error: Windows 11, 0XC00D36B4</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-oppo-k11x-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-spontaneous-command-window-flashes/"><u>How to Stop Spontaneous Command Window Flashes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-beginners-guide-to-windows-11-audible-recording/"><u>In 2024, Beginner's Guide to Windows 11 Audible Recording</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-navigating-through-vlc-features-settings-and-troubleshooting-mac/"><u>In 2024, Navigating Through VLC Features, Settings & Troubleshooting (Mac)</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-unrealcefsubprocess-impact-on-system-resources/"><u>Lowering UnrealCEFSubprocess Impact on System Resources</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-hiding-power-button-in-windows-11-settings/"><u>Masterclass: Hiding Power Button in Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-subnet-settings-windows-11-guide/"><u>Mastering Subnet Settings: Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-high-cpu-load-due-to-modules-installer-activity/"><u>Mitigating High CPU Load Due to Modules Installer Activity</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-cross-platform-video-editing-mastery-a-step-by-step-chromebook-guide/"><u>New In 2024, Cross-Platform Video Editing Mastery A Step-by-Step Chromebook Guide</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-11-a-quick-guide-to-stripping-junk/"><u>Optimize Windows 11: A Quick Guide to Stripping Junk</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrate-your-tasks-microsoft-to-do-plus-ifttt/"><u>Orchestrate Your Tasks: Microsoft To-Do + IFTTT</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-apple-image-failures-in-windows-1011/"><u>Overcoming Apple Image Failures in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-excessive-opening-of-file-explorer/"><u>Overcoming Excessive Opening of File Explorer</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-low-frames-per-second-in-valheim-expert-tips-and-tricks-for-gaming-nirvana/"><u>Overcoming Low Frames Per Second in Valheim: Expert Tips and Tricks for Gaming Nirvana</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-freeing-windows-11-space/"><u>Quick-Fix Guide to Freeing Windows 11 Space</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-absence-of-msvcr120dll-in-windows-environments/"><u>Resolving Absence of MSVCR120.DLL in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-windows-service-error-1053/"><u>Strategies for Overcoming Windows Service Error 1053</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/tailor-the-rhythm-of-youtube-videos-desktopmobile-way-for-2024/"><u>Tailor the Rhythm of YouTube Videos - Desktop/Mobile Way for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-enabling-external-security-solutions/"><u>Techniques for Enabling External Security Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-regedit-management-in-windows-11/"><u>Techniques for RegEdit Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-for-designing-custom-lock-patterns-in-windows-11/"><u>The Ultimate Technique for Designing Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-to-resolve-no-servers-found-navigating-apex-legends-windows-(156-chars/"><u>Top Tips to Resolve 'No Servers Found': Navigating Apex Legends Windows (<156 Chars)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/trouble-hearing-sound-in-your-presentation-expert-tips-to-resolve-powerpoint-audio-issues/"><u>Trouble Hearing Sound in Your Presentation? Expert Tips to Resolve PowerPoint Audio Issues</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-microsoft-store-on-windows-10-and-11-with-x800704cf-error/"><u>Unblocking Microsoft Store on Windows 10 & 11 with X800704CF Error</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-successful-device-connection-on-windows-11/"><u>Unlocking Successful Device Connection on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-disk-issues-avoiding-reading-problems/"><u>Unraveling Disk Issues: Avoiding Reading Problems</u></a></li>
<li><a href="https://win11.techidaily.com/what-hides-inside-ftdibussys-exploring-its-effects-on-windows-security/"><u>What Hides Inside ftdibus.sys? Exploring Its Effects on Windows Security</u></a></li>
<li><a href="https://win11.techidaily.com/winshift-fixes-guide-needed/"><u>WinShift Fixes Guide Needed</u></a></li>
</ul></div>

