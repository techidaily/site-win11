---
title: The Simple Way to Self-Empty the Recycle Bin on Windows
date: 2024-07-13T09:52:49.445Z
updated: 2024-07-14T09:52:49.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Simple Way to Self-Empty the Recycle Bin on Windows
excerpt: This Article Describes The Simple Way to Self-Empty the Recycle Bin on Windows
keywords: Empty Recycle Bin Quickly,Clear Waste Folder Easy,Windows Trash Purge Method,Fast Delete Windows Files,Simplify Deleting Data,Recycle Bin Cleanup Guide,Effective File Removal Tip
thumbnail: https://thmb.techidaily.com/962100c4bb1cf841eba9a73f110c7891af5a14d4cf3e7d146e6c0272a50f3335.jpg
---

## The Simple Way to Self-Empty the Recycle Bin on Windows

 We all know how easy it is to delete files and send them to the Recycle Bin. But wouldn't it be great if Windows automatically emptied the bin for us? Fortunately, you can configure your system to do just that.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

## 1\. How to Automate the Recycle Bin Using the System Settings

 It's easy to configure Windows to empty the recycle bin automatically. All you need to do is open System settings, fiddle with a few things, and you're done.

 However, this feature applies only to the current user account. Other users on the same computer won't have their Recycle Bin emptied automatically until they adjust this setting. In other words, if you're using a shared computer, it won't affect anyone else.

 Here's how to do it:

1. [Open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left panel, select the **System** tab.
3. Scroll down and click on **Storage** on the right-hand side. Here, you will find various computer data storage and management options.  
![Stoage in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stoage-in-system-settings.jpg)
4. Now, you will see a toggle switch under **Storage Sense**. If it's turned off, click to switch it on. This feature enables Windows to delete no longer needed files automatically.  
![Turn on Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/turn-on-storage-sense.jpg)
5. Once Storage Sense is active, click the tiny arrow next to it to expand the options.
6. On the next screen, you'll find an option that says, **Delete files in my recycle bin if they have been there for over**. Click the drop-down menu beside this and select the duration, after which Windows should empty the recycle bin automatically.
7. Select **1 day** if you want Windows to delete these items daily. Or choose another option that suits your needs better.  
![Configure Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/configure-storage-sense.jpg)
8. You can also configure the system to delete downloaded files that haven't been used for several days. To do so, click the **Delete files in my Downloaded folder if they haven't been opened for more than** drop-down menu and select the desired option.

 Once you're done, close the Settings window. Windows will automatically empty your Recycle Bin from now on.

## 2\. How to Automate the Recycle Bin Using the Task Scheduler

 If you want more control over the process, you can use Windows Task Scheduler to empty your Recycle Bin. Here's how:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **taskschd.msc** and hit **Enter** or click **OK**. Doing this [opens the Task Scheduler program](https://www.makeuseof.com/windows-11-open-task-scheduler/).
3. On the left-hand side of the window, select **Task Scheduler Library**.
4. Now, click **Create Basic Task** from the right-hand panel. It will open another window where you can configure your task settings.  
![Create Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-basic-task.jpg)
5. Enter a name for your task (e.g., Empty Recycle Bin) and a brief description if you want. Then, click the **Next** button.

1. The following window will ask you to select the frequency when Windows should empty your Recycle Bin. You can choose Daily, Weekly, Monthly, or One time only. Once you've chosen your preferred frequency, click **Next**.  
![Create a Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-a-basic-task.jpg)
2. After that, set the start date and time for your task. Also, select **Recur every** to specify the total duration of each cleaning session. Then, click **Next**.  
![Start Date and Time in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-date-and-time-in-task-wizard.jpg)
3. You must specify what action Windows should perform when this task runs. Click on the **Start a program** option and click **Next** again.  
![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  
/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.
6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

## Automate the Recycling Process on Windows

 To keep your computer running smoothly, you must empty your Recycle Bin regularly. However, the process can be tedious and time-consuming. Fortunately, Windows provides some easy ways to automate this task, either through Windows Settings or Task Scheduler.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-help.techidaily.com/2024-approved-harness-the-power-of-youtubes-movie-maker-for-professionals/"><u>2024 Approved  Harness the Power of YouTube's Movie Maker for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-resolve-virtual-machines-on-windows-11-vmware/"><u>7 Key Steps to Resolve Virtual Machines on Windows 11-VMware</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-disappointed-that-cant-use-pinnacle-studio-on-mac-weve-got-you-covered-check-out-our-list-below-for-some-great-alternatives-to-pinnacle-stud/"><u>Updated In 2024, Disappointed that Cant Use Pinnacle Studio on Mac? Weve Got You Covered! Check Out Our List Below for some Great Alternatives to Pinnacle Studio for Mac Users</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-the-quiet-edge-achieving-crystal-clear-video-through-smart-sound-editing-in-premiere-pro/"><u>New 2024 Approved The Quiet Edge Achieving Crystal-Clear Video Through Smart Sound Editing in Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-stop-automatic-office-updates-on-windows/"><u>4 Ways to Stop Automatic Office Updates on Windows</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-how-to-make-a-fortune-on-reddit-without-experience-top-13-methods/"><u>2024 Approved  How to Make a Fortune on Reddit Without Experience - Top 13 Methods</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/prime-selections-securing-entry-level-channel-monetization-sites-for-2024/"><u>Prime Selections  Securing Entry-Level Channel Monetization Sites for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-12-pro-max-complete-guide-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone 12 Pro Max? Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-approach-to-podcast-naming-and-50plus-dynamic-name-options/"><u>2024 Approved  Step-by-Step Approach to Podcast Naming & 50+ Dynamic Name Options</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-pcs-are-better-than-macs/"><u>9 Reasons PCs Are Better Than Macs</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-to-revamping-group-policy-settings/"><u>A Practical Approach to Revamping Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/1719359813770-cloud-connected-computers-integrating-files-with-dropboxgoogledrive-in-c/"><u>Cloud-Connected Computers: Integrating Files with Dropbox/GoogleDrive in C</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://win11.techidaily.com/1719368088856-troubleshooting-stuck-chrome-on-win11-easy-methods-here/"><u>Troubleshooting Stuck Chrome on Win11 – Easy Methods Here!</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-bridging-audio-gaps-the-complete-guide-to-smooth-blending-in-audacity/"><u>2024 Approved  Bridging Audio Gaps  The Complete Guide to Smooth Blending in Audacity</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-zero-cost-strategies-for-engaging-youtube-intros/"><u>[Updated] 2024 Approved  Zero-Cost Strategies for Engaging YouTube Intros</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719362389609-determining-cpu-version-on-windows-here-are-8-ways/"><u>Determining CPU Version on Windows – Here Are 8 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-clear-the-tpm-on-windows-11/"><u>4 Ways to Clear the TPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-11-software-removal-primer-top-11-approaches-114-chars/"><u>A Windows 11 Software Removal Primer: Top 11 Approaches (114 Chars)</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-immaculate-window-display-on-w11/"><u>A Guide to Immaculate Window Display on W11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-advanced-hd-screen-capture-gadgets/"><u>[New] 2024 Approved  Advanced HD Screen Capture Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-windows-processes-that-could-be-hiding-a-virus/"><u>7 Essential Windows Processes That Could Be Hiding a Virus</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-accurate-money-forecasting-apps-for-tiktok-users/"><u>[New] Accurate Money Forecasting Apps for TikTok Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://win11.techidaily.com/5-apps-that-elevate-your-desktop-writing-game/"><u>5 Apps That Elevate Your Desktop Writing Game</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-top-5-best-live-streaming-webcamscameras-for-twitch/"><u>In 2024, Top 5 Best Live Streaming Webcams/Cameras for Twitch</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-assessing-enterprise-chat-apps-for-unmatched-collaboration-which-holds-the-high-ground-slack-or-discord/"><u>[Updated] 2024 Approved  Assessing Enterprise Chat Apps for Unmatched Collaboration  Which Holds the High Ground, Slack or Discord?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/adobe-lightroom-color-grading-tutorial/"><u>Adobe Lightroom Color Grading Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/a-comparative-study-of-cloud-and-physical-methods-for-windows-setup/"><u>A Comparative Study of Cloud & Physical Methods for Windows Setup</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-ultimate-key-to-exploring-without-boundaries-through-vr/"><u>[New] The Ultimate Key to Exploring Without Boundaries Through VR</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-file-sharing-apps-on-a-windows-pc/"><u>5 Best File Sharing Apps on a Windows PC</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-splitting-video-in-vsdc-step-by-step/"><u>New Splitting Video in VSDC Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-review-whats-top-10-software-to-make-ai-upscaling-video/"><u>Updated 2024 Approved REVIEW Whats Top 10 Software to Make AI Upscaling Video</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-dual-lens-approach-gaining-audience-insight-with-3-pov-strategies-for-youtube-reactions-for-2024/"><u>The Dual Lens Approach  Gaining Audience Insight with 3 POV Strategies for YouTube Reactions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-resolving-upgrade-error-in-windows-os/"><u>A Step-By-Step Guide to Resolving Upgrade Error in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-reasons-users-prefer-older-windows-versions/"><u>7 Key Reasons Users Prefer Older Windows Versions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-visualvoyage-mastering-the-art-of-image-and-video-size-on-instagram/"><u>[Updated] VisualVoyage  Mastering the Art of Image and Video Size on Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-conquer-snapchats-boomerang-challenges-easily/"><u>In 2024, Conquer Snapchat's Boomerang Challenges Easily</u></a></li>
<li><a href="https://screen-recording.techidaily.com/simplifying-the-process-how-to-guide-for-booking-meets-for-2024/"><u>Simplifying the Process  How-To Guide for Booking Meets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-must-have-windows-software-for-mac-refugees/"><u>5 Must-Have Windows Software for Mac Refugees</u></a></li>
<li><a href="https://win11.techidaily.com/1719348018496-skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-best-online-video-spinners-rotate-your-clips-with-ease/"><u>New 2024 Approved Best Online Video Spinners Rotate Your Clips with Ease</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/o-monetize-your-youtube-shorts-simple-steps-for-2024/"><u>How to Monetize Your YouTube Shorts  Simple Steps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-finding-out-what-model-you-run-on-windows/"><u>A Simple Guide to Finding Out What Model You Run on Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-ultimate-guide-to-choosing-top-audio-reversing-applications-for-your-pc-phone-and-tablet-for-2024/"><u>New The Ultimate Guide to Choosing Top Audio Reversing Applications For Your PC, Phone, and Tablet for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-change-taskbar-history-19852023/"><u>A Window Into Change: Taskbar History (1985–2023)</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-youtube-outro-complete-guide-plusbest-makers-and-templates/"><u>[Updated] 2024 Approved  YouTube Outro Complete Guide [+Best Makers & Templates]</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleashing-creativity-new-font-addition-strategies-for-ae/"><u>In 2024, Unleashing Creativity  New Font Addition Strategies for AE</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719580912312-slovak-in-a-flash-online-learning-for-busy-lives/"><u>Slovak in a Flash - Online Learning for Busy Lives!</u></a></li>
<li><a href="https://win11.techidaily.com/1719339382074-unlock-frozen-shift-on-windows-pcs/"><u>Unlock Frozen Shift on Windows PCs.</u></a></li>
</ul></div>
