---
title: Stifling Windows 11 Folder Tab Noises
date: 2024-10-26T22:58:05.579Z
updated: 2024-11-01T19:21:12.031Z
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

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-simply-screen-recording-apowersofts-cost-free-software-review/"><u>[New] 2024 Approved Simply Screen Recording Apowersoft's Cost-Free Software Review</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-checklist-for-constructing-your-youtube-musical-assortment/"><u>[New] The Ultimate Checklist for Constructing Your YouTube Musical Assortment</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-crafting-clear-and-consistent-slug-lines/"><u>[Updated] Crafting Clear and Consistent Slug Lines</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-optimizing-your-periscope-stream-experience/"><u>[Updated] In 2024, Optimizing Your Periscope Stream Experience</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fierce-competition-gopro-vs-sonys-dslr-for-adventure-films-for-2024/"><u>Fierce Competition GoPro Vs. Sony's DSLR for Adventure Films for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-cut-and-paste-feature/"><u>Fixing Non-Operational Cut and Paste Feature</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-art-of-disguising-reality-learn-free-green-screen-techniques-via-vfx-leaders-on-4-video-platforms/"><u>In 2024, The Art of Disguising Reality Learn Free Green Screen Techniques via VFX Leaders on 4 Video Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/installers-manual-setting-up-win11-in-vmware-17/"><u>Installer's Manual: Setting Up Win11 in VMware 17</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ter-lane-navigating-to-the-top-15-funny-youtubers-for-2024/"><u>Laughter Lane Navigating to the Top 15 Funny YouTubers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-spotify-link-errors-on-modern-windows-devices/"><u>Reconciling Spotify Link Errors on Modern Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-keyboard-operations-restoring-enter-functionality/"><u>Recovering Keyboard Operations: Restoring 'Enter' Functionality</u></a></li>
<li><a href="https://win-able.techidaily.com/resolving-the-last-round-mishap-a-guide-to-overcoming-error-code-tfla0002/"><u>Resolving the Last Round Mishap: A Guide to Overcoming Error Code TFLA0002</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-workflows-master-win-command-shortcut-techniques/"><u>Simplify Workflows: Master Win Command Shortcut Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-windows-11-app-engagement-techniques/"><u>Speedy Windows 11 App Engagement Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-write-file-access-problem-on-pcs/"><u>Steps to Correct Write File Access Problem on PCs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-asus-rog-phone-8-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Asus ROG Phone 8? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://extra-hints.techidaily.com/threefold-stabilization-to-shine-your-iphone-videos/"><u>Threefold Stabilization to Shine Your iPhone Videos</u></a></li>
<li><a href="https://win11.techidaily.com/top-9-new-features-in-the-latest-win11-update/"><u>Top 9 New Features in the Latest Win11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-upgrade-incorporate-disk-space-analysis-into-menu/"><u>Windows UI Upgrade: Incorporate Disk Space Analysis Into Menu</u></a></li>
</ul></div>

