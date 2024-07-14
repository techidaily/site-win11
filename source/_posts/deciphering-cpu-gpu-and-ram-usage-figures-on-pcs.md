---
title: Deciphering CPU, GPU, & RAM Usage Figures on PCs
date: 2024-07-13T09:55:09.511Z
updated: 2024-07-14T09:55:09.511Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering CPU, GPU, & RAM Usage Figures on PCs
excerpt: This Article Describes Deciphering CPU, GPU, & RAM Usage Figures on PCs
keywords: PC Usage Analysis,CPU Performance Insight,GPU Load Monitoring,RAM Efficiency Tracking,Tech Hardware Metrics,Compute Component Usage,System Resource Management
thumbnail: https://thmb.techidaily.com/ece65a7774f151025dd995777d6ba1908931a5fce5214e3cee86728ea78d0703.jpg
---

## Deciphering CPU, GPU, & RAM Usage Figures on PCs

### Key Takeaways

* Use Task Manager to monitor RAM, CPU, and GPU usage. End unnecessary processes to improve system performance quickly.
* Resource Monitor offers more detailed metrics than Task Manager. Windows 11 users can benefit from its real-time monitoring features.
* For advanced users, Performance Monitor is the most comprehensive tool to analyze system performance and resource usage on Windows 11\.

 Keeping an eye on system resources can be vital, especially when experiencing glitches or slowdowns. If you're on Windows, there are tools baked into the operating system that let you quickly look up just how much of your RAM, CPU, and GPU are being used by a specific process.

## How to Check Windows 11's System Resource Usage With Task Manager

 The Task Manager is one of Windows 11’s primary system resource monitoring utilities. The tool is the easiest way to see which programs and processes are running and how many resources each takes up.

Related: [How to Access the Task Manager on Windows 11](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/)

 Here's how you can check your PC’s system resource usage with Task Manager.

1. Press **CTRL + Shift + Esc** to open Task Manager.
2. Click the **Performance** tab. This tab displays your system's RAM, CPU, GPU, and disk usage, along with network info.
3. To view RAM usage, select the **Memory** section. This section will show you how much memory the system is currently using, how much memory you have, and its specifications among other things.  
![task-manager-memory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/task-manager-memory.jpg)
4. You can check your computer's processor usage by clicking the **CPU** section. The processor box shows you a variable CPU percentage utilization figure, current clock speed, base clock speed, system uptime, and more.
5. Click the **GPU** section to see how much GPU memory is in use. You can choose which one you want to see if your PC has two GPUs (as with laptops with one integrated and one dedicated GPU).

 Task Manager also has a neat summary view that displays only the system resource usage boxes. To switch to that viewing mode, right-click within Task Manager and select **Summary View**. Then the Task Manager window will shrink as shown below.

![task-manager-cpu-summary-view-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/task-manager-cpu-summary-view-1.jpg)

 To check which programs consume the most resources, click the **Processes** tab. This tab displays all running apps and background processes, their memory, CPU, disk, network, and GPU usage. You can also free up system resources by selecting unnecessary third-party background programs (or processes and services) you don’t need and clicking the **End task** button.

![task-manager-processes-tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/task-manager-processes-tab.jpg)

Read also: [How to Free Up RAM and Reduce RAM Usage on Windows](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/)

## How to Check Windows 11's System Resource Usage With the Resource Monitor

 The Resource Monitor is a slightly more detailed monitoring utility than Task Manager in Windows 11\. It first appeared in Windows Vista and has since been a part of every subsequent Windows release. In addition to CPU, network, disk, and memory usage, the resource monitor also shows real-time metrics such as response time, throughput, and active time among others.

 Here's how you can check system resource consumption with Resource Monitor.

1. Open the Start menu by pressing the Windows key, type **Resource Monitor**, and hit enter.
2. Select the **Memory** tab to view its resource usage graphs. That tab includes a physical memory graph that shows how much memory is currently in use, how much is available, and how much is on standby, along with percentage utilization details.
3. Click the **CPU** tab to view its processor utilization percentage graphs.  
![resource-monitor-CPU-page-2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/resource-monitor-cpu-page-2.jpg)
4. Select the **Network** tab to view processes with network (internet) activity.
5. Click **Overview** to view memory, CPU, network, and disk usage details within a single tab.

## How to Check Windows 11's System Resource Usage With the Performance Monitor

 The Performance Monitor is the most advanced monitoring tool available in Windows 11\. It's designed to help analyze system performance and resource usage while also providing system summaries, performance reports, and real-time performance graphs.

 Here is how you can view performance and system resource details with Performance Monitor on Windows 11:

1. Open the Start menu by pressing the Windows key, type **Performance Monitor**, and hit enter.
2. Select **Performance** on the left side of the window to view the system summary resource usage data.  
![performance-monitor-main-screen-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/performance-monitor-main-screen-1.jpg)
3. Click **Performance Monitor** to view real-time performance data. By default, the graph shows the processor performance counter.  
![performance-monitor-real-time-graph-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/performance-monitor-real-time-graph-1.jpg)
4. To add other counters to the graph, click the **\+ Add** button.
5. Then select a counter, such as Memory, on the window shown directly below. The committed bytes line for the Memory counter highlights the average RAM usage over time.  
![performance-monitor-add-counter-screen-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/performance-monitor-add-counter-screen-1.jpg)
6. Press the **Add** button.
7. Click **OK** to view performance data for your selected counter on the graph.

 You can better analyze this data by creating data collector sets. To do that, select **Data Collector sets** in Performance Monitor. Right-click **User Defined** and select **New** \> **Data Collector**. Then you can set up the new data collector with the wizard that opens.

 Information from data collection sets becomes available with reports. You can view information from data collector sets you’ve run by clicking **Reports** in Performance Manager. Then select **User Defined** to view your data reports.

## Checking System Resources With Third-Party Tools

 If the built-in tools in Windows aren't to your liking, there's a plethora of third-party tools that you can use to monitor system resources. You can try out something simple and lightweight such as [OpenHardwareMonitor](https://openhardwaremonitor.org/downloads/), a free and open-source tool, which shows you CPU, GPU, memory, and disk usage at a glance. It also lets you monitor minimum and maximum temperatures as well as fan speeds for various PC components.

![Openhardware UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/openhardwaremonitor-ui-1.jpg)

 Using the tool is also quite simple, all you have to do is head over to the [OpenHardwareMonitor website](http://openhardwaremonitor.org/downloads/) and download the tool. Once downloaded, simply double-click the executable file to run it and you'll see all the metrics you need.

 Alternatives to OpenHardwareMonitor include [HWiNFO](https://www.hwinfo.com/), [Libre Hardware Monitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor), and [MSI Afterburner](https://www.msi.com/Landing/afterburner/graphics-cards), [which can also be used for overclocking](https://www.makeuseof.com/the-complete-guide-to-using-msi-afterburner/). That said, while Windows has since discontinued desktop widgets, you can use [8GadgetPack](https://8gadgetpack.net/) to add system resource monitoring widgets to your desktop. Do keep in mind that the program hasn't been updated in a while though, so there's a chance it might not work as expected.

![The gadget selection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/gadget-selection-window.png)

## Windows 11 will become slower and less responsive to your actions when system resource utilization is high (especially for RAM and CPU). Whenever it feels like you need to speed up Windows, check your PC’s resource utilization with the tools and gadgets above

 Once done, you can identify what programs or background processes are hogging the most resources and close them. And once they're close, you’ll notice an improved system performance overall.

 Keeping an eye on system resources can be vital, especially when experiencing glitches or slowdowns. If you're on Windows, there are tools baked into the operating system that let you quickly look up just how much of your RAM, CPU, and GPU are being used by a specific process.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/efficient-navigation-of-files-with-gallery-on-pc/"><u>Efficient Navigation of Files with Gallery on PC</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-productivity-top-30-mouse-control-wizards/"><u>Elevate Productivity: Top 30 Mouse Control Wizards</u></a></li>
<li><a href="https://win11.techidaily.com/guide-disabling-laptops-hardware-keys-on-windows-pc/"><u>Guide: Disabling Laptop's Hardware Keys on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-firewall-defenses-in-5-easy-steps/"><u>Customizing Firewall Defenses in 5 Easy Steps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/video-virtuosity-expertly-attaching-audio-to-youtube-videos-for-2024/"><u>Video Virtuosity  Expertly Attaching Audio to YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-live-speech-to-text-whisper-desktop-tips/"><u>Mastering Live Speech-to-Text: Whisper Desktop Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-photographers-route-to-perfectly-trimmed-web-pics/"><u>2024 Approved  The Photographer's Route to Perfectly Trimmed Web Pics</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-boosting-productivity-in-project-management-tools/"><u>Expert Tips for Boosting Productivity in Project Management Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality.</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-create-benime-whiteboard-animation-on-android-for-2024/"><u>How to Create Benime Whiteboard Animation on Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-underrated-realm-of-windows-monitoring-systems/"><u>Navigating the Underrated Realm of Windows Monitoring Systems</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-10-youtube-to-mp3-transformation-tools-for-2024/"><u>Top 10 YouTube-to-MP3 Transformation Tools for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/aried-and-eye-catching-vlog-discussion-points-for-2024/"><u>[New] Varied and Eye-Catching Vlog Discussion Points for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pc-non-compliance-intel-hd-graphics-setback/"><u>Addressing PC Non-Compliance: Intel HD Graphics Setback</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-update-failure-code-0x80246007-windows-guide/"><u>Disabling Update Failure Code 0X80246007: Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-how-win11-collects-your-personal-data/"><u>A Closer Look: How Win11 Collects Your Personal Data</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-clipcutter-plus/"><u>In 2024, ClipCutter Plus</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-apple-maps-on-windows/"><u>Navigating the World: Apple Maps on Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-best-intro-creator-software-for-windows-and-mac/"><u>New 2024 Approved Best Intro Creator Software for Windows and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-repairs-how-to-tackle-post-windows-update-glitches/"><u>Immediate Repairs: How to Tackle Post-Windows Update Glitches</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unveiling-the-best-vr-game-engines-of-2023/"><u>In 2024, Unveiling the Best VR Game Engines of 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-kinemasters-gs-complete-guide/"><u>Mastering KineMaster's GS  Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-update-notifier-into-the-windows-ui-context-of-win11/"><u>Integrating Update Notifier Into the Windows UI Context of Win11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-how-to-add-3d-effects-to-video-in-windows-computer-for-2024/"><u>Updated How to Add 3D Effects to Video in Windows Computer for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-highest-quality-images-in-4k-with-these-cameras/"><u>[New] Highest Quality Images in 4K with These Cameras</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-easy-audio-capturing-on-non-rooted-android-devices/"><u>2024 Approved  Easy Audio Capturing on Non-Rooted Android Devices</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-banishing-unwanted-green-in-mac-recorded-youtube-content/"><u>[New] 2024 Approved  Banishing Unwanted Green in Mac-Recorded YouTube Content</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-apple-iphone-11-pro-max-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing Apple iPhone 11 Pro Max iCloud Activation Lock</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-overlooked-window-11-styles/"><u>In-Depth Look at Overlooked Window 11 Styles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-mobile-screening-guide-gogooglemeetrecorder-tips/"><u>2024 Approved  Mobile Screening Guide  GoGoogleMeetRecorder Tips</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-blank-windows-11-logins/"><u>Guide to Fixing Blank Windows 11 Logins</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-social-narrative-this-years-twittale-highlights-for-2024/"><u>[New] The Social Narrative  This Year's TwitTale Highlights for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-harnessing-light-and-motion-for-gopro-time-lapse-magic/"><u>[New] Harnessing Light and Motion for GoPro Time-Lapse Magic</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/from-airwaves-to-archives-online-recording-strategies-for-tv-shows/"><u>From Airwaves to Archives  Online Recording Strategies for TV Shows</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-open-a-games-directory-on-windows/"><u>3 Ways to Open a Game's Directory on Windows</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-wealth-kid-star-earnings-surpass-major-celebrities/"><u>Kaji’s Wealth  Kid Star Earnings Surpass Major Celebrities</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-screen-unresponsive-message-in-windows-1111/"><u>Fixing Screen Unresponsive Message in Windows 11/11</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-pick-the-premier-mac-for-gif-capturing/"><u>[Updated] 2024 Approved  Pick the Premier Mac for GIF Capturing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/data-retrieval-tool-restore-lost-data-from-agni-2-5g-by-fonelab-android-recover-data/"><u>Data Retrieval tool – restore lost data from Agni 2 5G</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-tecno-spark-20-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Tecno Spark 20</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/top-4-free-3d-intro-maker-to-use/"><u>Top 4 Free 3D Intro Maker to Use</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Motorola Edge 2023? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-easy-steps-to-personalize-your-snapchat-pin/"><u>[New] Easy Steps to Personalize Your Snapchat Pin</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedy-restore-registry-management-functions/"><u>Quick Remedy: Restore Registry Management Functions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-error-0x800704b3/"><u>How to Bypass Windows Error 0X800704B3</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-superior-selection-androids-leading-video-call-for-large-groups-for-2024/"><u>[New] Superior Selection  Android's Leading Video Call for Large Groups for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-non-operational-ccleaner-on-win11/"><u>Overhauling Non-Operational CCleaner on Win11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unbox-the-secrets-of-10-song-success-on-facebook-for-2024/"><u>Unbox the Secrets of #10 Song Success on Facebook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-in-linux-sphere/"><u>Exploiting Windows Software in Linux Sphere</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-the-ultimate-student-friendly-laptop/"><u>ASUS Vivobook S 15: The Ultimate Student-Friendly Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/pro-animation-studio-top-8-software-picks-for-mac-and-windows-for-2024/"><u>Pro Animation Studio Top 8 Software Picks for Mac and Windows for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-impact-on-performance-the-unseen-effect-of-disguised-software/"><u>Hidden Impact on Performance: The Unseen Effect of Disguised Software</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-reframing-your-content-the-impact-of-aspect-ratio-on-video-style-for-2024/"><u>New Reframing Your Content The Impact of Aspect Ratio on Video Style for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>How to Share/Fake Location on WhatsApp for Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-quantum-hdrs-impact-on-photography/"><u>In 2024, Exploring Quantum HDR's Impact on Photography</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-in-use-device-names-on-your-windows-system/"><u>Overcoming In-Use Device Names on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-microsoft-powerpoint-not-printing-correctly-on-windows/"><u>9 Ways to Fix Microsoft PowerPoint Not Printing Correctly on Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-precision-and-perfection-leading-discord-emoji-makers-of-today/"><u>[New] In 2024, Precision and Perfection  Leading Discord Emoji Makers of Today</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-print-saturation-with-windows-11/"><u>Avoiding Print Saturation with Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-experts-pathway-navigating-fullscreen-realms-in-premiere-pro/"><u>In 2024, Expert's Pathway  Navigating Fullscreen Realms in Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-touchscreen-experience-on-a-windows-11-machine/"><u>Maximize Your Touchscreen Experience on a Windows 11 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-distant-devices-a-guide-for-windows-users/"><u>Reconciling Distant Devices: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-your-laptop-or-desktop-a-portable-network-hub-on-windows-11/"><u>How to Make Your Laptop or Desktop a Portable Network Hub on Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-sensational-tale-tiler-system/"><u>2024 Approved  Sensational Tale Tiler System</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-windows-11-performance-with-these-adjustments/"><u>Achieve Peak Windows 11 Performance with These Adjustments</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-personalizing-your-ig-experience-blocking-tactics-for-2024/"><u>[New] Personalizing Your IG Experience  Blocking Tactics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-world-google-map-powerhouse/"><u>Microsoft World, Google Map Powerhouse</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-ms-store-problem-fix-code-0x0-error-on-pcs/"><u>Eradicating MS Store Problem - Fix Code 0X0 Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-storage-potential-with-windows-iscsi-initiator/"><u>Unlocking Storage Potential with Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-link-ups-phones-and-windows-11-synergy/"><u>Innovative Link-Ups: Phones and Windows 11 Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-avoiding-endless-xbox-app-cycle/"><u>Quick Cure: Avoiding Endless Xbox App Cycle</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-roblox-gaming-with-higher-frames-per-second/"><u>Elevating Roblox Gaming with Higher Frames per Second</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-iphone-11-drfone-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-to-remove-restrictions-on-blocked-windows-files/"><u>Advanced Methods to Remove Restrictions on Blocked Windows Files</u></a></li>
</ul></div>
