---
title: Steps to Mute Explore Tabs on Microsoft OS
date: 2024-10-10T21:26:15.816Z
updated: 2024-10-15T17:41:39.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Mute Explore Tabs on Microsoft OS
excerpt: This Article Describes Steps to Mute Explore Tabs on Microsoft OS
keywords: Muting Browser Tabs,MS Windows Tab Silence,MSIE Explore Mute,Windows Snooze Feature,Turn Off Explorer Browsing,OS X Tabs Suppression,Chrome Tab Muting Steps
thumbnail: https://thmb.techidaily.com/a15aaf86d9e6f286629da1a62d56aaff3df86baa99afaf09eec0439a28bfe3f5.jpg
---

## Steps to Mute Explore Tabs on Microsoft OS

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-deep-dive-into-youtube-writers-workshop-space/"><u>[New] In 2024, A Deep Dive Into YouTube’ Writers' Workshop Space</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhancing-your-youtube-content-basic-premiere-pro-edits/"><u>[Updated] Enhancing Your YouTube Content Basic Premiere Pro Edits</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-nostalgia-reimagined-transforming-your-vintage-photos-into-cutting-edge-videos/"><u>2024 Approved Nostalgia Reimagined Transforming Your Vintage Photos Into Cutting-Edge Videos</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-dragons-dogma-2-crash-on-pc-with-these-proven-fixes-a-step-by-step-walkthrough/"><u>Beat Dragon's Dogma 2 Crash on PC with These Proven Fixes: A Step-by-Step Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/direct-linking-of-onedrive-and-microsoft-live-id/"><u>Direct Linking of OneDrive and Microsoft Live ID</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-most-value-from-windows-11-product-codes/"><u>How to Get the Most Value From Windows 11 Product Codes</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-stopping-windows-11s-surveillance-systems/"><u>Mastery in Stopping Windows 11'S Surveillance Systems</u></a></li>
<li><a href="https://win11.techidaily.com/optimized-email-checking-securely-placement-of-gmail-bar/"><u>Optimized Email Checking: Securely Placement of Gmail Bar</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-supported-audio-problems-windowss/"><u>Overcoming Non-Supported Audio Problems Windowss</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-inactive-airflow-management-guidelines/"><u>Reviving Inactive Airflow Management Guidelines</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/tactics-for-using-gpt-3-in-openai-sandbox/"><u>Tactics for Using GPT-3 in OpenAI Sandbox</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/techniques-for-flawless-live-broadcasting-of-rl-games-for-2024/"><u>Techniques for Flawless Live Broadcasting of RL Games for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-art-and-science-of-crafting-a-captivating-trailer-for-youtube-for-2024/"><u>The Art and Science of Crafting a Captivating Trailer for YouTube for 2024</u></a></li>
</ul></div>

