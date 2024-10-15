---
title: Tweaking the Visual Appearance of WinTerm
date: 2024-10-11T17:22:24.932Z
updated: 2024-10-15T22:37:16.747Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking the Visual Appearance of WinTerm
excerpt: This Article Describes Tweaking the Visual Appearance of WinTerm
keywords: WinTerm UI Tweaks,Terms WinStyle Enhance,WinTerm Design Tips,Enhance WinTerm Graphics,Customize WinTerm Look,WinTerm Aesthetics Change,Improve WinTerm Appearance
thumbnail: https://thmb.techidaily.com/f1e60caa3e6b666a54baaa6c3e17dd97a81f74bfc14a37bcb509db67f36be2c1.jpg
---

## Tweaking the Visual Appearance of WinTerm

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on[how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://vp-tips.techidaily.com/new-bending-words-altering-text-images-for-2024/"><u>[New] Bending Words Altering Text Images for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-archive-all-your-images-flawlessly-infinite-no-charge-and-elite-paid-storage/"><u>[Updated] 2024 Approved Archive All Your Images Flawlessly Infinite, No-Charge & Elite Paid Storage</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-the-best-bargains-in-drone-tech-for-under-100/"><u>[Updated] In 2024, The Best Bargains in Drone Tech for Under $100</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-sync-music-and-visuals-the-art-of-canva-editing/"><u>[Updated] Sync Music & Visuals The Art of Canva Editing</u></a></li>
<li><a href="https://win11.techidaily.com/44cm57ch5y2y44gr5a2m44g544kl77yb44ot44oh44kq44gu44k144og44on44kk44or5oq95ye644og44kv44ol44od44kv44cn/"><u>「簡単に学べる！ビデオのサムネイル抽出テクニック」</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44or44k944kz44oz5l244gj44gm5a625bqt55so44ot44oh44kq44kr44od44oi44gu5oml6acg44ks44kk44oj44cn/"><u>「パソコン使って家庭用ビデオカットの手順ガイド」</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-video-projects-using-intel-quick-sync-video-encoder/"><u>Accelerate Your Video Projects Using Intel Quick Sync Video Encoder</u></a></li>
<li><a href="https://win11.techidaily.com/complete-guide-to-dvd-extraction-on-windows-and-mac-a-step-by-step-tutorial/"><u>Complete Guide to DVD Extraction on Windows and Mac: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tutorial-installing-and-configuring-openmeta-and-openinfo-platforms/"><u>Comprehensive Tutorial: Installing and Configuring OpenMeta & OpenInfo Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-converting-m4a-audio-to-aiff-format/"><u>Easy Guide: Converting M4A Audio to AIFF Format</u></a></li>
<li><a href="https://win11.techidaily.com/easy-methods-for-converting-png-graphics-into-high-quality-mp4-movies-with-both-online-services-and-pc-applications/"><u>Easy Methods for Converting PNG Graphics Into High-Quality MP4 Movies with Both Online Services and PC Applications</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-the-foremost-techniques-for-transforming-seminars-into-videos/"><u>In 2024, The Foremost Techniques for Transforming Seminars Into Videos</u></a></li>
<li><a href="https://win-answers.techidaily.com/lunar-pc-client-continually-fails-resolved-issues-and-fixes/"><u>Lunar PC Client Continually Fails: Resolved Issues & Fixes</u></a></li>
<li><a href="https://article-posts.techidaily.com/perfecting-the-art-of-podcast-title-creation-essential-tips-and-inspirations/"><u>Perfecting the Art of Podcast Title Creation Essential Tips & Inspirations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seamlessly-transferring-youtube-content-onto-iphone-user-friendly-solutions-for-idevice-integration/"><u>Seamlessly Transferring YouTube Content Onto iPhone - User-Friendly Solutions for iDevice Integration</u></a></li>
<li><a href="https://extra-tips.techidaily.com/virtual-reality-humor-the-art-of-metaverse-memes/"><u>Virtual Reality Humor The Art of Metaverse Memes</u></a></li>
</ul></div>

