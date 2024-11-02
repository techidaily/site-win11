---
title: Solving Unspecified OBS Studio Error on New Windows
date: 2024-10-26T01:53:47.693Z
updated: 2024-11-02T01:41:39.385Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Unspecified OBS Studio Error on New Windows
excerpt: This Article Describes Solving Unspecified OBS Studio Error on New Windows
keywords: Fix OBS Mistake Windows,Resolve OBS Error Windows,Stop OBS Glitches Windows,Correct OBS Failures Windows,End OBS Crashes New OS,Cease OBS Issues Windows,Eradicate OBS Problems Win
thumbnail: https://thmb.techidaily.com/93c58d18d4169d1b8be3151f6e561548c6b0c37eb736f1516830c78d9ab2d4d1.jpg
---

## Solving Unspecified OBS Studio Error on New Windows

 OBS Studio is a great program to record and stream online. However, some users can't utilize OBS Studio because of a recording error that occurs when they try to record their screens. Instead of recording, OBS Studio throws up this message: "An unspecified error occurred while recording."

 The error usually appears when an important DLL file is missing, or there's corruption in the OBS Studio installation directory. As such, if you also see the same error, then try the below solutions to eliminate the problem for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart OBS Studio

![Closing the OBS Studio Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/end-task.jpg)

 Whether you're[seeing a black screen](https://www.makeuseof.com/windows-11-obs-black-screen-fix/) or getting the "An unspecified error occurred while recording" error, the best way to fix any OBS Studio issue is to restart it. Restarting OBS Studio will clear the system resources and kill any temporary bugs or glitches that might be causing the error.

 To restart OBS Studio, open the**Task Manager** (see how to[open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on OBS Studio, and choose**End Task.** Then, search for OBS Studio in the**Start Menu** and choose**Open** from the right pane.

## 2\. Temporarily Disable Your Graphics Driver

 The error is likely to occur if there's corruption in the GPU log file that is used by the OBS Studio. To remove the corruption, you'll have to disable the graphics driver before launching the OBS Studio. Doing this will force the program to create a new GPU log.

Here's what you need to do:

1. Open the**Power User Menu** by pressing the**Win + X** hotkey and choose**Device Manager** from the context menu.
2. In the Device Manager, double-click on the**Display adapters** node to expand it.
3. Right-click on the dedicated graphics driver and choose**Disable device.**  
![Disable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-option-1.jpg)
4. Click**Yes** to the prompt that appears.

 Your screen might flicker after disabling the dedicated graphics driver. But worry not; it'll become normal after the generic driver is started.

 Now, launch the OBS Studio and open your project. Then, open the Device Manager again > access the Display adapters node > right-click on the dedicated graphics driver and choose**Enable device.**

![Enable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-device.jpg)

 That's it! Return to OBS Studio and check if you are able to record.

## 3\. Allow OBS Studio Through Your Firewall

 OBS Studio might fail to record and throw the error at hand if it's blocked under Windows Firewall. To fix this, you'll have to whitelist OBS Studio from the Windows Firewall blocked app list. Here's how to do that:

1. Press the**Win** key to open the**Start Menu.**
2. Type**Windows Firewall** in the search bar and press Enter.
3. Choose **Allow an app or feature through Windows Defender Firewall** option from the left sidebar.  
![Allow an app or feature through Windows Defender Firewall option in Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/allow-an-app-or-feature-through-windows-defender-firewall-option.jpg)
4. Click the**Change settings** button.
5. Click on**Allow another app** and then choose**Browse** from the**Add an app** prompt.  
![Add an app prompt in the Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-app.jpg)
6. Navigate to the location where you have installed the OBS Studio.
7. Select the**obs-ffmpeg-mux** executable file and click**Open.**  
![obs-ffmpeg-mux file in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/obs-ffmpeg-mux-file.jpg)
8. Click**Add.**

9. Check both the**Private** and**Public** boxes for**obs-ffmpeg-mux** and click**OK** to save the settings.  
![Private and Public boxes for OBS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/private-and-public-boxes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Restart your computer and check if the problem continues.

## 4\. Fix the Missing DLL Files

[Dynamic Link Libraries](https://www.makeuseof.com/what-are-dll-files-on-windows/) , aka DLL files, are special implementations of system libraries that contain various functions and variables that programs use when needed. If an important DLL file required by OBS Studio goes missing, you will see the "An unspecified error occurred while recording" error.

 To fix that, you will have to re-acquire the required DLL file. Here's how:

1. Navigate to the place where you have installed the OBS Studio.
2. Double-click on the obs-ffmpeg-mux file, and note down which of the following DLL file is missing.  
`avcodec-57.dll  
avformat-57.dll  
avutil-55.dll  
swresample-2.dll`
3. Follow our guide on[how to fix DLL files missing on Windows](https://www.makeuseof.com/tag/dll-files-missing-errors/) to repair the missing file.

Restart your computer and check for the issue.

## 5\. Edit the OBS-Ffmpeg-Mux Installation Folder

 If you're still facing the issue even after downloading the missing DLL file, then it indicates that OBS Studio is unable to find the required DLL. The solution, in this case, is to edit the Path environment so that OBS Studio finds the required DLL files.

You can do that by following the below instructions:

1. Press the**Win + I** key to open the**Settings** **app.**
2. In the System tab, choose the**About** option in the left pane.
3. Click the**Advanced system settings** option.  
![Advanced system settings option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-system-settings.jpg)
4. Click the**Environment Variables** button.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Environment Variables option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enviroment-variables.jpg)
5. Select**Path** under the**System Variables** section, and click the**Edit** button.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Paste the following path in the**Variable value** text box and click**OK.**  
`C:\Program Files (x86)\obs-studio\bin\32bit;`  
![Edit Variable in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-variable.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it! Now, start recording in OBS Studio and check if the problem persists.

## 6\. Check for Corrupted or Missing Files

 Sometimes, OBS Studio might fail to record due to corruption in its installation folder. The problem can also occur if an important file is missing.

 In either case, you can use the "Check File Integrity" feature to scan the OBS installation for corruption and redownload broken/ missing files. Here's how to use that feature:

1. Launch OBS Studio, click the**Help** option at the top, and choose the**Check File Integrity** option from the context menu.  
![Check File Integrity option in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-file-integrity-option.jpg)
2. Click**Yes** to confirm your selection.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 OBS Studio will compare the available files with those on its server and download any missing or broken files.

 While you're at the OBS Studio home screen, check for and download any available updates. To do that, click**Help** and choose**Check for Updates** .

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Reinstall OBS Studio

 If you're still getting the error message, you're left with no option other than reinstalling OBS Studio. To do that, first[uninstall OBS Studio from Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) .

 Then, visit the[OBS Studio official website](https://obsproject.com/) , and download and install the latest version on your computer.

## Enjoy Seamless Recording With OBS Studio

 OBS Studio makes it a cakewalk to record anything and upload it online. However, due to corruption in its installation folder or missing DLL files, it might throw the "An unspecified error occurred while recording" error. Fortunately, you can quickly get rid of this error by applying the above fixes.

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-unlocking-the-potential-of-your-mobile-content-for-youtube-wealth/"><u>[New] 2024 Approved Unlocking the Potential of Your Mobile Content for YouTube Wealth</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-digital-detox-ignoring-negativity-on-youtube/"><u>[New] Digital Detox Ignoring Negativity on YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-pinnacle-partnership-portrayal-picking-an-ideal-mcn/"><u>[Updated] Pinnacle Partnership Portrayal Picking an Ideal MCN</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-efficiency-counteracting-zero-speed/"><u>Boosting Windows Steam Efficiency: Counteracting Zero-Speed</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-chromes-profiles-issues/"><u>Comprehensive Guide to Fixing Chrome's Profiles Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/curated-list-top-discovery-plus-series-to-watch-in-july-2024/"><u>Curated List: Top Discovery Plus Series to Watch in July 2024</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-faulty-m365-functionality-code-30015-26/"><u>Disabling Faulty M365 Functionality: Code 30015-26</u></a></li>
<li><a href="https://blog-min.techidaily.com/discover-the-stealthy-way-a-guide-to-clandestine-screen-capture-on-pc-and-mac/"><u>Discover the Stealthy Way: A Guide to Clandestine Screen Capture on PC and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/facilitating-regular-updates-toolbar-integration-in-the-windows-ui/"><u>Facilitating Regular Updates: Toolbar Integration in the Windows UI</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-infinix-zero-30-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Infinix Zero 30 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-novice-evolving-skills-in-the-realm-of-google-photos/"><u>In 2024, From Novice Evolving Skills in the Realm of Google Photos</u></a></li>
<li><a href="https://win11.techidaily.com/measuring-electrical-use-for-windows-pcs-effectively/"><u>Measuring Electrical Use for Windows PCs Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-shift-away-from-windows-xp-7-and-81-support/"><u>Navigating the Shift Away From Windows XP, 7 & 8.1 Support</u></a></li>
<li><a href="https://extra-skills.techidaily.com/reviewing-the-newest-2023-samsung-bd-j5900-model-for-2024/"><u>Reviewing the Newest 2023 Samsung BD-J5900 Model for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-travel-planning-apple-maps-and-windows/"><u>Streamlining Travel Planning: Apple Maps & Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-tricks-for-mass-folder-creation-at-a-click-in-windows-oses/"><u>The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/olds-sway-over-youtube-subscribers-in-2024/"><u>Who Holds Sway Over YouTube Subscribers, In 2024</u></a></li>
</ul></div>

