---
title: Toggle Visibility for Folder in Windows Explorer, Version 11
date: 2024-11-02T20:30:37.217Z
updated: 2024-11-07T17:44:03.766Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Toggle Visibility for Folder in Windows Explorer, Version 11
excerpt: This Article Describes Toggle Visibility for Folder in Windows Explorer, Version 11
keywords: Folder Visibility Control,Window Explorer View Change,Windows Explorer Settings Adjustment,Explore Folder Toggle Visibility,Manage Explorer Display Option,Windows Explorer Show/Hide Feature,Access Folder Visibility Switch in Explorer
thumbnail: https://thmb.techidaily.com/a9744aafdac80a7e4f169749236f6a9a3444533f48662a5ae5f051ec41bdae27.jpg
---

## Toggle Visibility for Folder in Windows Explorer, Version 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

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
<li><a href="https://screen-capture.techidaily.com/updated-easy-steps-for-enhanced-productivity-keyboard-based-screen-recordings-in-os-x-for-2024/"><u>[Updated] Easy Steps for Enhanced Productivity Keyboard-Based Screen Recordings in OS X for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-top-100-virtual-bicycle-escapades-to-experience/"><u>[Updated] In 2024, Top 100 Virtual Bicycle Escapades to Experience</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-streamline-events-with-obs-crafting-a-time-based-feature/"><u>[Updated] Streamline Events with OBS Crafting a Time-Based Feature</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-mastering-the-art-of-digital-distortion-in-minutes/"><u>2024 Approved Mastering the Art of Digital Distortion in Minutes</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-review-of-the-samsung-galaxy-a71-5g-the-smart-choice-beyond-premium-phones/"><u>Comprehensive Review of the Samsung Galaxy A71 5G - The Smart Choice Beyond Premium Phones</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elite-equipment-showcasing-gameplay-innovations/"><u>Elite Equipment Showcasing Gameplay Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/fundamental-insights-into-windows-snoozer-functionality/"><u>Fundamental Insights Into Window's Snoozer Functionality</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-best-obs-settings-for-low-end-pcs/"><u>In 2024, Best OBS Settings for Low-End PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-devices-name-conflicts-with-ease-windows-guide/"><u>Navigate Through Devices Name Conflicts with Ease (Windows Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-dropbox-performance-lessening-cpu-overuse-in-windows/"><u>Optimizing Dropbox Performance: Lessening CPU Overuse in Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-launch-difficulties-in-evil-genius-2-effective-solutions-for-a-smooth-start/"><u>Overcoming Launch Difficulties in Evil Genius 2 - Effective Solutions for a Smooth Start</u></a></li>
<li><a href="https://win11.techidaily.com/power-up-windows-top-5-essential-wintoys/"><u>Power Up Windows: Top 5 Essential WinToys</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-windows-11-app-opening/"><u>Turbocharge Windows 11 App Opening</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-capabilities-a-detailed-review-of-linksys-velop-networking-solutions/"><u>Unveiling the Capabilities: A Detailed Review of Linksys Velop Networking Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-examining-their-unique-traits/"><u>Windows Terminal and PowerShell: Examining Their Unique Traits</u></a></li>
</ul></div>

