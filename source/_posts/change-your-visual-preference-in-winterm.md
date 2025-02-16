---
title: Change Your Visual Preference in WinTerm
date: 2025-02-12T04:31:05.175Z
updated: 2025-02-15T20:12:31.696Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Change Your Visual Preference in WinTerm
excerpt: This Article Describes Change Your Visual Preference in WinTerm
keywords: Change View Settings,Update WinTerm Display,Adjust WinTerm Graphics,Modify Visual WinTerm,Customize WinTerm Appearance,Tweak Window Settings in WinTerm,Alter WinTerm Display Mode
thumbnail: https://thmb.techidaily.com/b7025f879b7f69fff163ff4565fc3f42cd715d8a0e343c5b6d69fd8b7007ad8a.jpg
---

## Change Your Visual Preference in WinTerm

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-information.techidaily.com/new-advanced-pip-setup-elevating-your-visual-presentations-on-macos/"><u>[New] Advanced PIP Setup Elevating Your Visual Presentations on macOS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-dslr-or-mirrorless-for-high-quality-video-recording/"><u>[Updated] 2024 Approved DSLR or Mirrorless for High-Quality Video Recording?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-step-by-step-approach-to-capturing-and-editing-in-adobe-connect/"><u>[Updated] 2024 Approved Step-by-Step Approach to Capturing and Editing in Adobe Connect</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-capture-breathtaking-scenes-on-iphone-with-ease-for-2024/"><u>[Updated] Capture Breathtaking Scenes on iPhone with Ease for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/advanced-steps-a-compre-point-of-view-on-screen-record-with-adobe-captivate/"><u>Advanced Steps A Compre Point of View on Screen Record with Adobe Captivate</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-tackle-windows-activation-fault-0x803f700f/"><u>Guidelines to Tackle Windows Activation Fault 0X803F700f</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-ai-powered-name-ideas-for-standout-podcast-titles/"><u>In 2024, AI-Powered Name Ideas for Standout Podcast Titles</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-win11-personalized-sound-triggers/"><u>Mastering Win11: Personalized Sound Triggers</u></a></li>
<li><a href="https://win11.techidaily.com/offscreen-wonderland-revive-windows-on-your-1011-device/"><u>Offscreen Wonderland: Revive Windows on Your 10/11 Device</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-restoring-volume-mixer-defaults/"><u>Regain Control: Restoring Volume Mixer Defaults</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revitalize-your-visuals-expertly-curated-list-of-the-best-10-editors-for-2024/"><u>Revitalize Your Visuals Expertly Curated List of the Best 10 Editors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-method-for-cr2-image-jpg-transformation/"><u>Step-by-Step Windows Method for CR2 Image JPG Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-temp-directory-errors-in-win11/"><u>Steps to Correct Temp Directory Errors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-removing-absence-of-display-during-win-remoting/"><u>Strategies for Removing Absence of Display During Win Remoting</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-tips-resolving-code-800-on-clientserver-vpns/"><u>Troubleshooting Tips: Resolving Code 800 on Client/Server VPNs</u></a></li>
</ul></div>

