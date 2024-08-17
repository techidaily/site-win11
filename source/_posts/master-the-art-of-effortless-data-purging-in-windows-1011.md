---
title: Master the Art of Effortless Data Purging in Windows 10/11
date: 2024-08-16T00:25:19.019Z
updated: 2024-08-17T00:25:19.019Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master the Art of Effortless Data Purging in Windows 10/11
excerpt: This Article Describes Master the Art of Effortless Data Purging in Windows 10/11
keywords: Data Purge Mastery,Effortless Data Delete,Windows Easy Cleanup,Zero-Trouble Deletion,Purging Guide W10/W11,Simplified System Cleaning,No Hassle File Removal
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
---

## Master the Art of Effortless Data Purging in Windows 10/11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-10-best-apps-for-editing-igtv-vertical-videos/"><u>[New] 10 Best Apps for Editing IGTV Vertical Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-navigating-ig-videos-successfully-building-an-efficient-marketing-blueprint/"><u>[New] 2024 Approved  Navigating IG Videos Successfully  Building an Efficient Marketing Blueprint</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-turning-off-igtv-on-your-account/"><u>[New] 2024 Approved  Turning Off IGTV on Your Account</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-5-quick-filming-diy-hacks-to-try-at-home/"><u>[New] Top 5 Quick Filming DIY Hacks to Try at Home</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-unlocking-facebooks-secrets-an-introductory-guide/"><u>[New] Unlocking Facebook's Secrets  An Introductory Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-dive-deeper-into-life-advanced-strategies-for-capturing-the-essence-of-your-sims-adventures-in-sims-4/"><u>[Updated] 2024 Approved  Dive Deeper Into Life  Advanced Strategies for Capturing the Essence of Your Sim's Adventures in Sims 4</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-swipe-right-on-creativity-youtubes-top-techniques-for-greenscreens/"><u>[Updated] 2024 Approved  Swipe Right on Creativity  YouTube’s Top Techniques for Greenscreens</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tech-trend-analysis-vlls-evaluations/"><u>[Updated] Tech Trend Analysis  VLL's Evaluations</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-and-science-of-periscope-streaming/"><u>[Updated] The Art and Science of Periscope Streaming</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-storyline-secret-to-youtube-triumph-for-2024/"><u>[Updated] The Storyline Secret to YouTube Triumph for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-comprehensiveness-in-film-capture-vs-dimensionality-in-visuals/"><u>2024 Approved  Comprehensiveness in Film Capture vs Dimensionality in Visuals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-metaversal-journey-versus-omniverse-quest/"><u>2024 Approved  Metaversal Journey Versus Omniverse Quest</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-vivo-x-flip-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-tecno-spark-10c-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Tecno Spark 10C</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/boost-viewers-interaction-via-youtube-cards/"><u>Boost Viewers Interaction via YouTube Cards</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-window-taskbar-lockup-a-guide/"><u>Breaking the Window Taskbar Lockup: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-the-barrier-of-windows-errors/"><u>Breaking Through the Barrier of Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-back-into-your-stuck-windows-11-search-bar/"><u>Breathe Life Back Into Your Stuck Windows 11 Search Bar</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-a-non-operational-itunes-windows-app/"><u>Breathing Life Into a Non-Operational iTunes Windows App</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-new-life-into-windows-outdated-driver-removal/"><u>Breathing New Life Into Windows: Outdated Driver Removal</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-windows-resolution-problems-quickly/"><u>Breeze Through Windows Resolution Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gap-to-windows-11-concealed-searchlight/"><u>Bridging Gap to Windows 11 Concealed Searchlight</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-languages-font-downloads-for-windows-enthusiasts/"><u>Bridging Languages: Font Downloads for Windows Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-invisible-expert-techniques-to-revive-off-screen-applications-in-win-1011-6-ways/"><u>Bring Back the Invisible: Expert Techniques to Revive Off-Screen Applications in Win 10/11 (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-printer-accessibility-to-microsofts-security-shield/"><u>Bringing Printer Accessibility to Microsoft's Security Shield</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-context-menu-update-functionality-in-windows-11plus11-interface/"><u>Building a Context Menu Update Functionality in Windows 11+11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/bumping-basslines-top-4-software-to-overshoot-windows-maxed-volume/"><u>Bumping Basslines: Top 4 Software to Overshoot Window's Maxed Volume</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-login-obstacles-in-microsoft-store-quickly/"><u>Bypass Login Obstacles in Microsoft Store Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-a00f4289-for-seamless-webcams-on-w1011/"><u>Bypassing Error A00F4289 for Seamless Webcams on W10/11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-maxed-out-status-of-gpt-on-pc/"><u>Bypassing Maxed Out Status of GPT on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-network-troubles-unlocking-secrets-of-error-0x800704b3/"><u>Bypassing Network Troubles: Unlocking Secrets of Error 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-guard-unavailable-warning-on-pc/"><u>Bypassing Security Guard Unavailable Warning on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-in-use-message-for-windows-11-files/"><u>Bypassing the 'In-Use' Message for Windows 11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unresponsive-programs-in-windows-systems/"><u>Bypassing Unresponsive Programs in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/calm-down-your-zooming-mouse-with-7-fixes/"><u>Calm Down Your Zooming Mouse with 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/cascading-chaos-conquered-multitask-management-for-win1110/"><u>Cascading Chaos Conquered: Multitask Management for Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/cease-unwanted-windows-update-restarts/"><u>Cease Unwanted Windows Update Restarts</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-others-use-of-your-camera-windows-error-code-0xa00f4243/"><u>Ceasing Others' Use of Your Camera: Windows Error Code 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-voice-activated-ai-on-windows-11/"><u>Ceasing Voice-Activated AI on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/changing-nat-settings-on-windows-tips-for-win1110-users/"><u>Changing NAT Settings on Windows: Tips for Win11/10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/changing-nat-types-effortlessly-with-our-step-by-step-tutorials/"><u>Changing NAT Types Effortlessly with Our Step-by-Step Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/charting-your-course-with-the-insiders-of-windows-11/"><u>Charting Your Course with the Insiders of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-nvidia-drivers-game-vs-studio-edition/"><u>Choosing Nvidia Drivers: Game vs Studio Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-hardware-reserved-space-in-windows/"><u>Clarifying Hardware Reserved Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-legacy-restoration-for-modern-users/"><u>Classic Legacy Restoration for Modern Users</u></a></li>
<li><a href="https://win11.techidaily.com/clean-up-your-computer-top-12-windows-extras-for-removal/"><u>Clean Up Your Computer: Top 12 Windows Extras for Removal</u></a></li>
<li><a href="https://win11.techidaily.com/cleanse-your-pcs-security-records-with-win-11-tips/"><u>Cleanse Your PC's Security Records with Win 11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-for-team-success-resolving-80080300-errors-on-w11/"><u>Clearing the Path for Team Success: Resolving 80080300 Errors on W11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-pathway-for-smooth-windows-discord-installation/"><u>Clearing the Pathway for Smooth Windows Discord Installation</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-out-of-storage-error-on-win-1011/"><u>Clearing Up Out of Storage Error on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-windows-10-tracking-step-by-step-tutorial/"><u>Clearing Windows 10 Tracking: Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-windows-11-update-error-code-0x30017/"><u>Clearing Windows 11 Update Error Code 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/clever-consumers-can-confront-fakeware-feints/"><u>Clever Consumers Can Confront Fakeware Feints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-reset-failure-count-for-incorrect-login-attempts-on-windows-11/"><u>Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-iphone-15-pro-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your iPhone 15 Pro Apple ID and Apple Pay</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-vivo-y200-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Vivo Y200 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-deciphering-youtubes-monetary-mechanisms/"><u>In 2024, Deciphering YouTube's Monetary Mechanisms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-the-art-of-tiktok-visual-enhancements/"><u>In 2024, Mastering the Art of TikTok Visual Enhancements</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-social-gaming-galore-the-ultimate-metaverse-list/"><u>In 2024, Social Gaming Galore  The Ultimate Metaverse List</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-most-effective-ways-to-bypass-iphone-se-2022-activation-lock-by-drfone-ios/"><u>In 2024, The Most Effective Ways to Bypass iPhone SE (2022) Activation Lock</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-role-of-look-up-tables-in-cinematic-coloring/"><u>In 2024, The Role of Look-Up Tables in Cinematic Coloring</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-trouble-with-apple-iphone-12-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>In 2024, Trouble with Apple iPhone 12 Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-unpacking-manycams-revolutionary-recording-features/"><u>In 2024, Unpacking ManyCam's Revolutionary Recording Features</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-mastering-video-editing-on-mac-a-step-by-step-guide-for-yosemite-users/"><u>New Mastering Video Editing on Mac A Step-by-Step Guide for Yosemite Users</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-samsung-galaxy-z-fold-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-lava-blaze-2-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Lava Blaze 2 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-for-correcting-gtfo-crash-issues/"><u>Troubleshooting Tips for Correcting GTFO Crash Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-cross-platform-communication-how-to-enable-android-users-access-to-imessages/"><u>Unlocking Cross-Platform Communication: How to Enable Android Users Access to iMessages</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unrivaled-script-authority-place/"><u>Unrivaled Script Authority Place</u></a></li>
</ul></div>
