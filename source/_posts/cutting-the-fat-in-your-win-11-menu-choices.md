---
title: Cutting the Fat in Your Win 11 Menu Choices
date: 2024-10-19T20:21:47.616Z
updated: 2024-10-26T20:24:20.798Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cutting the Fat in Your Win 11 Menu Choices
excerpt: This Article Describes Cutting the Fat in Your Win 11 Menu Choices
keywords: Win 11 Healthy Options,Reduce Win 11 Weight,Clean Win 11 Menu,Slender Win 11 Diet,Win 11 Low Fat Foods,Optimal Win 11 Eating,Balanced Win 11 Selection
thumbnail: https://thmb.techidaily.com/5648c434c12cbf88b15506d6d23b8724252689511d16fa18d7a28833e2a6d9c5.jpg
---

## Cutting the Fat in Your Win 11 Menu Choices

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105870/7443" target="_top" id="2105870">
  <img src="//a.impactradius-go.com/display-ad/7443-2105870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925565/19272" target="_top" id="1925565">
  <img src="//a.impactradius-go.com/display-ad/19272-1925565" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925565/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://some-knowledge.techidaily.com/new-how-to-infuse-prayerful-melodies-on-your-phone/"><u>[New] How to Infuse Prayerful Melodies on Your Phone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-effortless-communication-unveil-the-three-step-method-for-snapchat-calls/"><u>[Updated] 2024 Approved Effortless Communication Unveil the Three-Step Method for Snapchat Calls</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-sprightly-spirits-top-kid-approved-games/"><u>[Updated] In 2024, Sprightly Spirits Top Kid-Approved Games</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-tackling-not-empty-directive-error-in-windows/"><u>Expert Guide to Tackling Not Empty Directive Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/faster-updates-no-frustration-9-fixes-for-verifying-installer-speed/"><u>Faster Updates, No Frustration: 9 Fixes for Verifying Installer Speed</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-the-art-of-stress-free-computing-with-essential-linux-tips/"><u>Master the Art of Stress-Free Computing with Essential Linux Tips</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-muted-microphone-recordings-with-obs-in-windows-11/"><u>Rectifying Muted Microphone Recordings with OBS in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/running-windows-11-in-mac-a-parallels-guide/"><u>Running Windows 11 in Mac: A Parallels Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reinitiate-windows-print-spooler-processing/"><u>Steps to Reinitiate Windows Print Spooler Processing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-power-of-hashtags-in-growing-your-instagram-reel-presence-for-2024/"><u>The Power of Hashtags in Growing Your Instagram Reel Presence for 2024</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-10-free-online-sticker-makers-to-make-your-own-stickers-for-2024/"><u>Updated 10 Free Online Sticker Makers to Make Your Own Stickers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-n-flavors-explained-advantages-examined/"><u>Windows N Flavors Explained: Advantages Examined</u></a></li>
</ul></div>

