---
title: Quieting File Explorer Tab Activity on Win11
date: 2024-11-05T20:15:47.641Z
updated: 2024-11-07T20:58:22.670Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quieting File Explorer Tab Activity on Win11
excerpt: This Article Describes Quieting File Explorer Tab Activity on Win11
keywords: Quiet Windows Explorer,Silent Explorer Close,Hush File Manager,Mute Explore Activities,Dampen Explorer Lights,Tune Out Folder Views,Subdue File Dialog Sounds
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Quieting File Explorer Tab Activity on Win11

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134239/18498" target="_top" id="2134239">
  <img src="//a.impactradius-go.com/display-ad/18498-2134239" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134239/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-boosting-viewership-with-animated-subscribe-buttons-in-filmora-easy-guide/"><u>[New] 2024 Approved Boosting Viewership with Animated Subscribe Buttons in Filmora (Easy Guide)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-strategic-steps-for-sky-high-insta-video-view-counts-for-2024/"><u>[New] Strategic Steps for Sky-High Insta Video View Counts for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exploring-the-best-value-routers-an-in-depth-look-at-the-tp-link-archer-c9-model-review/"><u>Exploring the Best Value Routers: An In-Depth Look at the TP-Link Archer C9 Model Review</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-best-screen-recorder-no-ads-for-android/"><u>In 2024, Best Screen Recorder No Ads for Android</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-tips-labeling-footage-with-text-via-photos-app-win-11/"><u>In 2024, Tips Labeling Footage with Text via Photos App (Win 11)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/leverage-complete-movie-files-for-ai-training-using-google-gemini-v15/"><u>Leverage Complete Movie Files for AI Training Using Google Gemini V1.5</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-keyboardmouse-inactivity-after-sleep-win11/"><u>Overcoming Keyboard/Mouse Inactivity After Sleep, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-update-failures-windows-11s-error-0x30017/"><u>Tackling Update Failures: Windows 11'S Error 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-app-error-0x80131500/"><u>Tackling Windows App Error 0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-guide-to-devhome-and-w11-integration/"><u>The Comprehensive Guide to DevHome and W11 Integration</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-text-editor-to-dark-mode-windows-11/"><u>Transitioning Text Editor to Dark Mode (Windows 11)</u></a></li>
</ul></div>

