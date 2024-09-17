---
title: Upgrade Your Terminal Visual Element
date: 2024-09-12T20:55:04.481Z
updated: 2024-09-16T18:29:37.007Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Upgrade Your Terminal Visual Element
excerpt: This Article Describes Upgrade Your Terminal Visual Element
keywords: Terminal UI Enhancement,Terminal Graphics Improvement,Visually Upgraded Terminal,Advanced Terminal Display,Better Terminal Aesthetics,Updated Terminal Visuals,Modernized Terminal Screen
thumbnail: https://thmb.techidaily.com/60c0536f1fc5d6831a20d36d45e0ac93bc7d119ca6b31c73ad5af370fee6c60a.jpg
---

## Upgrade Your Terminal Visual Element

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

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

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

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-thriving-in-the-world-of-youtube-broadcasting-master-class/"><u>[New] 2024 Approved Thriving in the World of YouTube Broadcasting Master Class</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/astering-youtube-the-ultimate-guide-to-earning-for-2024/"><u>[New] Mastering YouTube The Ultimate Guide to Earning for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-from-basic-to-breathtaking-crafting-top-tier-tiktok-videos-using-templates-for-2024/"><u>[Updated] From Basic to Breathtaking Crafting Top-Tier TikTok Videos Using Templates for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-prime-flight-tech-ready-to-buy/"><u>[Updated] Prime Flight Tech Ready to Buy</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-system-reactivated-post-failure/"><u>Display System Reactivated Post-Failure</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-to-upgrading-from-hevc-to-av1-video-codec-without-hitches/"><u>Easy Guide to Upgrading From HEVC to AV1 Video Codec Without Hitches</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-methods-for-iphone-users-to-enjoy-ogg-files/"><u>Effortless Methods for iPhone Users to Enjoy OGG Files</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-transformation-mastering-the-switch-from-wmv-to-webm-files/"><u>Effortless Transformation: Mastering the Switch From WMV to WebM Files</u></a></li>
<li><a href="https://win11.techidaily.com/full-circle-video-spin-mastering-the-art-of-180-degree-video-rotations/"><u>Full-Circle Video Spin: Mastering the Art of 180 Degree Video Rotations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effortlessly-view-mts-videos-a-comprehensive-tutorial-for-your-pc-or-mac/"><u>How To Effortlessly View MTS Videos: A Comprehensive Tutorial for Your PC or Mac</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 to other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
</ul></div>

