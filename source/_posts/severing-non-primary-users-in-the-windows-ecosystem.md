---
title: Severing Non-Primary Users in the Windows Ecosystem
date: 2024-08-16T00:29:33.506Z
updated: 2024-08-17T00:29:33.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Severing Non-Primary Users in the Windows Ecosystem
excerpt: This Article Describes Severing Non-Primary Users in the Windows Ecosystem
keywords: Non-Windows Users Separation,Primary Windows Users First,Windows Primaries Priority,Eliminate Non-Users,Windows Core User Focus,Exclude External OS Users,Windows Ecosystem Maintenance
thumbnail: https://thmb.techidaily.com/8a48baa92cdc76a86f454f4bf37afbb0816527695359221f913b5285fa5c2939.jpg
---

## Severing Non-Primary Users in the Windows Ecosystem

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-iphone-and-ipad-best-screen-recording-software/"><u>[New] 2024 Approved  IPhone & iPad  Best Screen Recording Software</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-skyrocketing-youtube-traffic-11-seo-insights-unveiled/"><u>[New] 2024 Approved  Skyrocketing YouTube Traffic  11 SEO Insights Unveiled</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-extract-youtube-soundtracks-for-free-with-this-list-of-25-rippers-for-2024/"><u>[New] Extract YouTube Soundtracks for Free With This List of 25 Rippers for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-five-superior-timelapse-filmmakers/"><u>[New] In 2024, Five Superior Timelapse Filmmakers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-visualtwitter-quickly-download-and-share-videos-on-mobile/"><u>[New] In 2024, VisualTwitter  Quickly Download and Share Videos on Mobile</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-unlock-high-res-video-leading-4k-conversion-tools/"><u>[Updated] 2024 Approved  Unlock High-Res Video  Leading 4K Conversion Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-enhance-youtubes-conversations-with-emojis-for-2024/"><u>[Updated] Enhance Youtubes' Conversations with Emojis for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-seamlessly-posting-online-content-to-ig-storypost/"><u>2024 Approved  Seamlessly Posting Online Content to IG Story/Post</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtubes-best-gamers-audio-selection-guide/"><u>2024 Approved  YouTube's Best Gamers' Audio Selection Guide</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/augment-communication-skills-expertly-selected-languages-apps/"><u>Augment Communication Skills: Expertly Selected Languages Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/avoiding-mistakes-the-freelancers-guide-to-chatgpt-use/"><u>Avoiding Mistakes: The Freelancer's Guide to ChatGPT Use</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-back-into-your-stuck-windows-11-search-bar/"><u>Breathe Life Back Into Your Stuck Windows 11 Search Bar</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-your-xbox-application/"><u>Breathe Life Into Your Xbox Application</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-windows-11s-diagnostic-features/"><u>Breathe New Life Into Windows 11'S Diagnostic Features</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technical-gaps-fixing-faulty-win11-ccleaner/"><u>Bridging Technical Gaps: Fixing Faulty Win11 CCleaner</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-windows-11-and-google-play-store/"><u>Bridging Windows 11 and Google Play Store</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-invisible-expert-techniques-to-revive-off-screen-applications-in-win-1011-6-ways/"><u>Bring Back the Invisible: Expert Techniques to Revive Off-Screen Applications in Win 10/11 (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-peace-5-corrections-for-family-safety-woes/"><u>Bring Back the Peace: 5 Corrections for Family Safety Woes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/broadcast-battlegrounds-where-does-streaming-technology-stand-strongest/"><u>Broadcast Battlegrounds  Where Does Streaming Technology Stand Strongest?</u></a></li>
<li><a href="https://win11.techidaily.com/broken-bitwall-dont-hurry-evaluate-existing-safeguards/"><u>Broken BitWall: Don't Hurry, Evaluate Existing Safeguards</u></a></li>
<li><a href="https://win11.techidaily.com/browser-ram-test-showdown-top-7-lightweight-contenders/"><u>Browser RAM Test Showdown: Top 7 Lightweight Contenders</u></a></li>
<li><a href="https://win11.techidaily.com/build-an-autohotkey-powered-whisper-enhanced-window-text-converter/"><u>Build an AutoHotkey-Powered, Whisper-Enhanced Window Text Converter</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-safe-web-environment-with-trustable-sites-in-windows-11/"><u>Building a Safe Web Environment with Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/building-your-language-repertoire-downloading-windows-fonts/"><u>Building Your Language Repertoire: Downloading Windows Fonts</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-access-denied-window-issues-steps-and-tips/"><u>Bypass 'Access Denied' Window Issues: Steps and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-quick-access-initiate-file-explorer-via-onedrive-link/"><u>Bypass Quick Access: Initiate File Explorer via OneDrive Link</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-service-failed-errors-on-disk-management/"><u>Bypassing 'Service Failed' Errors on Disk Management</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-rdp-authentication-a-windows-11-guide/"><u>Bypassing RDP Authentication: A Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-spec-limitations-for-successful-game-capturing/"><u>Bypassing Spec Limitations for Successful Game Capturing</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-audible-hurdle-code-0xc00d36b4/"><u>Bypassing Windows' Audible Hurdle: Code 0Xc00d36b4</u></a></li>
<li><a href="https://win11.techidaily.com/cant-use-your-microphone-on-google-meet-for-windows-heres-why/"><u>Can’t Use Your Microphone on Google Meet for Windows? Here's Why</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-others-use-of-your-camera-windows-error-code-0xa00f4243/"><u>Ceasing Others' Use of Your Camera: Windows Error Code 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/changing-nat-settings-on-windows-tips-for-win1110-users/"><u>Changing NAT Settings on Windows: Tips for Win11/10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/charting-the-course-for-user-sid-discovery-on-windows-11/"><u>Charting the Course for User SID Discovery on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/choco-vs-wm-a-comparative-look-at-windows-package-tools/"><u>Choco vs WM: A Comparative Look at Window's Package Tools</u></a></li>
<li><a href="https://win11.techidaily.com/christmas-in-coding-revamping-your-windows-11/"><u>Christmas in Coding: Revamping Your Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-lockdown-resolving-windows-11-error-code-22/"><u>Circumventing Lockdown: Resolving Windows 11 Error Code 22</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-hardware-reserved-space-in-windows/"><u>Clarifying Hardware Reserved Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-diablo-playbook-step-by-step-guide/"><u>Classic Diablo Playbook: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/classic-explorer-features-revival-guide/"><u>Classic Explorer Features Revival Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-clutter-prioritizing-and-positioning-tasks-on-your-window-desktop/"><u>Clear the Clutter: Prioritizing and Positioning Tasks on Your Window Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-to-chatting-ease-on-your-pc/"><u>Clear the Path to Chatting Ease on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-cloud-of-past-accomplishments-in-steam/"><u>Clearing the Cloud of Past Accomplishments in Steam</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-fixing-office-activation-errors/"><u>Clearing the Path: Fixing Office Activation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-chromes-profile-conflicts-in-windows/"><u>Clearing Up Chrome's Profile Conflicts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-closed-captioning-confusion-in-win-10-systems/"><u>Clearing Up Closed Captioning Confusion in Win 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/combat-disappearing-steam-app-graphics/"><u>Combat Disappearing Steam App Graphics</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/comprehensive-review-of-screen-recording-tools-for-2024/"><u>Comprehensive Review of Screen Recording Tools for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/efficient-file-transfers-5-methods-for-pc/"><u>Efficient File Transfers  5 Methods for PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhance-your-storytelling-discover-how-chatgpt-aids-in-crafting-unique-novels/"><u>Enhance Your Storytelling: Discover How ChatGPT Aids in Crafting Unique Novels</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/youtube-subtitled-content-download-without-paying/"><u>Free YouTube Subtitled Content  Download Without Paying</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-mistral-ais-le-chat-stack-up-against-chatgpt-find-out-in-this-comparative-analysis/"><u>How Does Mistral AI's Le Chat Stack Up Against ChatGPT? Find Out in This Comparative Analysis</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-f34-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy F34 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-call-logs-from-phantom-v-flip-by-fonelab-android-recover-call-logs/"><u>How to retrieve erased call logs from Phantom V Flip?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From iPhone 13 Pro Max</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-oppo-a58-4g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Oppo A58 4G Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-asus-rog-phone-7-ultimate-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Asus ROG Phone 7 Ultimate to Mac? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/no-more-interruptions-how-to-stabilize-your-phoenix-point-game-and-prevent-future-crashes/"><u>No More Interruptions: How to Stabilize Your Phoenix Point Game & Prevent Future Crashes</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175727926-nvme-ssd-uphere-m201-heatsink-review-exceptional-cooling-performance-at-an-unbeatable-5-price/"><u>NVMe SSD UpHere M201 Heatsink Review - Exceptional Cooling Performance at an Unbeatable $5 Price!</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/remove-cluttered-backgrounds-using-picarts-features-for-2024/"><u>Remove Cluttered Backgrounds Using PicArt's Features for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-itel-s23plus-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Itel S23+</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/stop-your-macs-auto-sleep-feature-with-these-simple-steps/"><u>Stop Your Mac's Auto-Sleep Feature with These Simple Steps</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-guide-to-resolving-frame-drops-and-stutters-in-naraka-the-beating/"><u>Ultimate Guide to Resolving Frame Drops & Stutters in Naraka: The Beating</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-mp4-video-tag-management-made-easy-best-editors-for-windows-and-mac-for-2024/"><u>Updated MP4 Video Tag Management Made Easy Best Editors for Windows and Mac for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/vloggers-guide-to-choosing-camera-essentials-the-top-9-accessories-for-2024/"><u>Vloggers' Guide to Choosing Camera Essentials - The Top 9 Accessories for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/x-3/"><u>X=-3</u></a></li>
</ul></div>
