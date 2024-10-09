---
title: Eliminate Unwanted Updates with 4 Tactics
date: 2024-10-01T17:50:31.318Z
updated: 2024-10-09T00:27:28.935Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Unwanted Updates with 4 Tactics
excerpt: This Article Describes Eliminate Unwanted Updates with 4 Tactics
keywords: Eliminate Unwanted Ups,Update Removal Tricks,Stop Pesky Updates,Strategies for No Update,Tactics Against Auto-Updates,Preventing Automatic Fixes,Stopping Undesired Updates
thumbnail: https://thmb.techidaily.com/a50a3cec0521fa6fb800284717c9122c07291a0277fd1f77229ad231586b5b14.jpg
---

## Eliminate Unwanted Updates with 4 Tactics

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

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

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

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
<li><a href="https://screen-capture.techidaily.com/new-precision-in-screen-recording-a-comprehensively-reviewed-list-for-2024/"><u>[New] Precision in Screen Recording A Comprehensively Reviewed List for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-skillful-stylization-efficiently-tap-into-windows-paints-features/"><u>[New] Skillful Stylization Efficiently Tap Into Windows Paint's Features</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-vlc-screen-recorder-review-and-using-guide/"><u>[Updated] 2024 Approved VLC Screen Recorder Review and Using Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-musical-mosaics-15-video-tutorials-on-collaborative-projects/"><u>[Updated] Musical Mosaics 15 Video Tutorials on Collaborative Projects</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/compiling-the-finest-ios-psp-game-tools-1-5-for-2024/"><u>Compiling the Finest iOS PSP Game Tools #1-5 for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-review-top-cable-modem-and-wireless-routers-for-enhanced-connectivity-best-picks-2024/"><u>Comprehensive Review: Top Cable Modem & Wireless Routers for Enhanced Connectivity (Best Picks, 2024)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disjointed-sticky-note-behavior-on-w11-system/"><u>Fixing Disjointed Sticky Note Behavior on W11 System</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-become-a-broadcast-pro-screen-sharing-101-for-facebookers/"><u>In 2024, Become a Broadcast Pro Screen Sharing 101 for Facebookers</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/next-gen-health-revenue-strategies-unleashed-explore-the-power-of-abbyys-digital-transformation-techniques-in-managing-patient-payments/"><u>Next-Gen Health Revenue Strategies Unleashed - Explore the Power of ABBYY's Digital Transformation Techniques in Managing Patient Payments</u></a></li>
<li><a href="https://win11.techidaily.com/onedrives-new-home-a-guide-for-windows-11-users/"><u>OneDrive's New Home: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-copypaste-failures-in-windows-11/"><u>Preventing Copy/Paste Failures in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-programs-with-context-menu-additions/"><u>Streamlining Programs with Context Menu Additions</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-overcoming-server-issues-hindering-win-1111-store-functionality/"><u>Swift Solutions: Overcoming Server Issues Hindering Win 11/11 Store Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-artistic-potential-of-windows-11-comics/"><u>Unlock the Artistic Potential of Windows 11 Comics</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11s-hidden-treasures-with-our-6-secrets-to-success/"><u>Unlock Windows 11'S Hidden Treasures with Our 6 Secrets to Success</u></a></li>
<li><a href="https://win11.techidaily.com/which-out-of-intel-unison-or-phone-link-is-superior/"><u>Which Out of Intel Unison or Phone Link Is Superior?</u></a></li>
</ul></div>

