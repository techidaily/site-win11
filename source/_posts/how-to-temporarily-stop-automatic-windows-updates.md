---
title: How to Temporarily Stop Automatic Windows Updates
date: 2024-09-05T08:41:02.813Z
updated: 2024-09-06T08:41:02.813Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Temporarily Stop Automatic Windows Updates
excerpt: This Article Describes How to Temporarily Stop Automatic Windows Updates
keywords: Pause Windows Update,Stop Auto Updates,Windows Update Hold,Delay Windows Updates,Halt Windows Patches,Postpone Windows Updates,Suspend Windows Installs
thumbnail: https://thmb.techidaily.com/246a59716ccd46798f84896d6b6802f3ff638286b1b806ed68510f39b79036cf.jpg
---

## How to Temporarily Stop Automatic Windows Updates

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123481/16836" target="_top" id="2123481">
  <img src="//a.impactradius-go.com/display-ad/16836-2123481" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123481/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to[download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.


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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-beginner-friendly-steps-to-record-your-mac-display/"><u>[New] 2024 Approved  Beginner-Friendly Steps to Record Your Mac Display</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-10-iconic-beauty-personalities-to-follow-on-youtube/"><u>[Updated] 2024 Approved  10 Iconic Beauty Personalities to Follow on YouTube</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-audio-conversion-made-simple-youtube-to-mp3-mac-edition/"><u>[Updated] In 2024, Audio Conversion Made Simple  YouTube to MP3, Mac Edition</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-windows-color-rich-video-landscape/"><u>2024 Approved  Navigating Windows' Color-Rich Video Landscape</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/clip-perfection-achieved-through-blended-methodologies-for-2024/"><u>Clip Perfection Achieved Through Blended Methodologies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cure-your-consoles-crashing-wow-problems-quickly/"><u>Cure Your Console's Crashing WoW Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-search-experience-in-windows-11/"><u>Elevate Your Search Experience in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhance-onboarding-process-and-cultivate-customer-loyalty-in-financial-services/"><u>Enhance Onboarding Process and Cultivate Customer Loyalty in Financial Services</u></a></li>
<li><a href="https://win11.techidaily.com/from-vintage-to-virtual-realm-activate-windows-11-using-a-windows-7-key/"><u>From Vintage to Virtual Realm: Activate Windows 11 Using a Windows 7 Key</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-honor-90-lite-by-drfone-android/"><u>Full Guide to Unlock Your Honor 90 Lite</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-edit-like-a-pro-64-bit-video-editor-for-windows-8-and-up/"><u>In 2024, Edit Like a Pro 64-Bit Video Editor for Windows 8 and Up</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-dj-tools-for-windows/"><u>In 2024, Expert DJ Tools for Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-proven-6-best-video-grabbers-for-your-mac/"><u>In 2024, Proven 6 Best Video Grabbers for Your Mac</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-windows-data-safe-a-must-do-habit/"><u>Keeping Windows Data Safe: A Must-Do Habit</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-youtube-videos-your-comprehensive-tutorial-for-2024/"><u>Mastering YouTube Videos  Your Comprehensive Tutorial for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-chromes-inaccurate-virus-alert-and-resolving-it/"><u>Navigating Chrome's Inaccurate Virus Alert and Resolving It</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/navigating-the-web-easier-the-secret-behind-cookiebot/"><u>Navigating the Web Easier: The Secret Behind Cookiebot</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-blue-screen-error-0xc0000142/"><u>Overcoming Blue Screen Error 0XC0000142</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-windows-11-taskbar-icons-layout/"><u>Perfecting Windows 11 Taskbar Icons Layout</u></a></li>
<li><a href="https://win11.techidaily.com/power-play-four-strategies-for-removing-user-entries-from-win11/"><u>Power Play: Four Strategies for Removing User Entries From Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-tap-your-way-through-win11s-print-settings-max-48-chars/"><u>Quick Guide: Tap Your Way Through Win11's Print Settings (Max 48 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-non-selectable-text-within-windows-pdf-files/"><u>Rectify Non-Selectable Text Within Windows PDF Files</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-non-operational-display-driver-on-windows-11-os/"><u>Remedy for Non-Operational Display Driver on Windows 11 OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/revamp-your-google-group-chats-with-4-tips/"><u>Revamp Your Google Group Chats with 4 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-for-batch-installing-windows-11-apps-via-winstall/"><u>Simplified Techniques for Batch Installing Windows 11 Apps via Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-unsupported-device-error/"><u>Strategies to Address 'Unsupported Device' Error</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-handle-source-file-error-in-windows-1110/"><u>Strategies to Handle Source File Error in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-fps-and-reduce-lag-in-roblox-windows-edition/"><u>Strategies to Improve FPS & Reduce Lag in Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-call-journals-on-windows-pcs/"><u>Streamlining Call Journals on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/switching-on-windows-11s-updated-widget-chooser/"><u>Switching On Windows 11'S Updated Widget Chooser</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-nonresponsive-diagnostics-in-win10win11/"><u>Tackling Nonresponsive Diagnostics in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-plan-for-your-epic-games-files/"><u>The Ultimate Plan for Your Epic Games Files</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-gripes-windows-11-user-experience/"><u>Top 5 Gripes: Windows 11 User Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-of-windows-screen-hangouts/"><u>Unlocking Secrets of Windows Screen Hangouts</u></a></li>
<li><a href="https://techidaily.com/update-your-drivers-with-device-manager-in-windows-1110-by-drivereasy-guide/"><u>Update your drivers with Device Manager in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/use-accessibility-features-utilize-features-like-narrator-magnifier-and-text-size-adjustment-for-better-visibility-without-altering-display-settings-drastic29/"><u>Use Accessibility Features: Utilize Features Like Narrator, Magnifier, and Text Size Adjustment for Better Visibility without Altering Display Settings Drastically</u></a></li>
<li><a href="https://win11.techidaily.com/win11-wizardry-invisible-archiving-techniques-in-photos/"><u>Win11 Wizardry: Invisible Archiving Techniques in Photos</u></a></li>
<li><a href="https://win11.techidaily.com/windows-command-line-expertise-the-top-20-must-know-commands/"><u>Windows Command Line Expertise: The Top 20 Must-Know Commands</u></a></li>
<li><a href="https://win11.techidaily.com/windows-screen-grabs-snip-tool-versus-print-screen-efficacy/"><u>Windows Screen Grabs: Snip Tool Versus Print Screen Efficacy</u></a></li>
<li><a href="https://win11.techidaily.com/windows-steps-to-purge-unnecessary-steam-dns-data/"><u>Windows Steps to Purge Unnecessary Steam DNS Data</u></a></li>
</ul></div>
