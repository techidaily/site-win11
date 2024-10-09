---
title: "Title: Enhancing Window Organization by Icon Adjustment"
date: 2024-10-06T19:00:48.229Z
updated: 2024-10-08T22:10:16.443Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Title: Enhancing Window Organization by Icon Adjustment"
excerpt: "This Article Describes Title: Enhancing Window Organization by Icon Adjustment"
keywords: Window Arrangement Tips,Icon Editing for Order,Space Optimization Windows,Icons Boosting Layouts,Effective Window Organizing,Enhanced Window Display,Efficient Icon Usage
thumbnail: https://thmb.techidaily.com/94567bf4df3b715033d93123bd31d8eb4bb0ab79d545d1676a1f32d06cb990c5.jpg
---

## Title: Enhancing Window Organization by Icon Adjustment

 Windows 11 includes three desktop context menu options for changing icon size. However, those settings do nothing to change the spacing between icons. Nor does the Settings app or Control Panel offer any configuration settings with which to adjust icon spacing variables.

 As such, it might seem that you can’t change icon spacing on the desktop in Windows 11/10\. However, Windows 11 does have two hidden settings for changing the vertical and horizontal desktop icon spacing in the form of registry strings. Here is how you can change desktop icon spacing in Windows 11/10 in two different ways.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change Desktop Icon Spacing By Manually Editing the Registry

 The registry is one big database of configuration settings that you can edit to customize Windows. It includes a WindowsMetrics key that incorporates IconSpacing and IconVerticalSpacing strings.

 You can tweak these hidden options and create the desktop icon spacing you want as follows:

1. Click the**Start** button on the taskbar with the right mouse button to select the**Run** shortcut.
2. To[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) , enter**regedit** in the Run and select**OK** .
3. Go to the **Computer\\HKEY\_CURRENT\_USER\\Control Panel\\Desktop\\WindowMetrics** registry key. You can copy and paste that registry location in the address bar or click the keys for it on the left sidebar.
4. Select the**WindowMetrics** key.  
![The WindowMetrics key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windowsmetrics-key.jpg)
5. Double-click the**WindowMetrics** key's**IconSpacing** string, which changes the horizontal spacing for desktop icons.

1. Then erase the current**\-1125** number from the Value data box.
2. Enter a replacement value with a minus (-) sign in front of it. For example, entering**\-1180** will slightly increase the horizontal spacing.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-string-window.jpg)
3. Press the**OK** button to close IconString’s Edit String window.
4. Next, double-click the**IconVerticalSpacing** string setting, with which you can modify vertical icon spacing.
5. Clear the current value, and then input another number with a minus sign in front of it. If you want the vertical spacing to be the same as the horizontal, enter a number there that matches the IconSpacing value.
6. Click the Edit String window’s**OK** button.
7. Exit the Registry Editor.
8. You’ll need to restart Windows to apply this[registry tweak](https://www.makeuseof.com/tag/5-windows-10-registry-tweaks-improve-unlock-features/) .

 After the restart, the icon spacing on your desktop will have changed according to the new**IconString** and**IconVerticalSpacing** values you entered. You’ll notice the difference if you entered notably higher or lower values. Don’t get too carried away by entering values that are far too low or high. The shortcuts’ labels will overlap with too little spacing and some icons might disappear from the desktop if you expand the space between them too much.

![New desktop icon spacing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/new-icon-spacing.jpg)

 Now you might wonder how you can restore the default desktop icon spacing. The default spacing value for both the strings is**\-1125** , which amounts to 75 pixels. So, return to the WindowMetric registry key and enter**\-1125** for both the**IconString** and**IconVerticalSpacing** string values. Thereafter, restart your PC to restore the default spacing.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Desktop Icon Spacing With Winaero Tweaker

 Some third-party customization software packages for Windows 11/10 include options for changing desktop icon spacing. Among them is the freeware Winaero Tweaker, which has two slider bars with which you can increase or decrease horizontal and vertical icon spacing. As that software also specifies space values in pixels, some users might prefer to change icon spacing with it. This is how to change the spacing for desktop icons with Winaero Tweaker.

1. Open a browser and visit the[Winaero Tweaker](https://winaero.com/winaero-tweaker/#download) download page.
2. Scroll down the page to select a**Download Winaero Tweaker** option.
3. Next, launch File Explorer to open the folder that includes Winaero’s ZIP archive.
4. Right-click the winaerotweaker.zip file and select its**Extract All** option.  
![The Extract All button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/extract-all-button4.jpg)
5. Select the checkbox for the**Show extracted files when complete** setting on the Extract Compressed (Zipped) Folders window.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/the-extract-compressed-window3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. To unzip the archive, click**Extract** .
2. Double-click the installer file for Winaero Tweaker to bring up the software’s setup wizard.
3. Select the**Next** option a few times, and click the**I accept the radio agreement** button.
4. Click**Next** to proceed to the folder selection. Although not essential to do so, you can click**Browse** to choose a different folder.  
![The Winaero Tweaker setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/setup-winaero-tweaker-window2.jpg)
5. All the other default installation options selected are fine. Keep clicking**Next** and then Install to finish.

1. Select the**Run Winaero Tweaker** checkbox after installing, and then click**Finish** .
2. Double-click the**Advanced Appearance Settings** category in Winaero.
3. Click the**Icons** option shown directly below.
4. Drag the**Horizontal spacing** bar’s slider right or left to increase or decrease the space width between icons.  
![The Icons option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/icons-option.jpg)
5. Then drag the slider for the**Vertical spacing** bar left or right to adjust the amount of vertical space for desktop icons.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Press the**Apply changes** button.
7. Click the**Sign out now** option to restart your PC and apply the icon spacing changes.

 That’s it. Now you can see the icon spacing change on the Windows 11 desktop.

 If you go a bit over the top with the space changes, you can easily readjust the values with Winaero Tweaker’s icon spacing slider bars. To restore the default spacing, click the**Reset this page to defaults** option for the Icon option.

 You might also notice that Winaero Tweaker’s Icon option has an additional**Change icons font** setting. That option enables you to choose a different font for your desktop icons. Press the**Change Font icon** button to bring up the window shown below.

![The Font window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/font-window.jpg)

 There you can select a different icon font from a wide variety of alternatives in the**Font** menu. The**Font style** menu there includes 12 different styles for icon fonts to choose from. Input a higher or lower value in the**Size** box to increase or decrease the font size. You can also select**Strikeout** and**Underline** text effect options there.

 Click**OK** when you’ve customized the desktop icon font, and then select the**Apply Changes** and**Sign out** now options.

## How to Change Desktop Icon Spacing With DesktopOK

 DesktopOK is another third-party app with which you can adjust the vertical and horizontal spacing between desktop icons. That software also enables you to save desktop icon layouts and packs in other useful tools and features. You can change desktop icon spacing with DesktopOK like this:

1. Open[this DesktopOK](https://www.softwareok.com/?Download=DesktopOK&goto=../Download/DesktopOK%5Fx64.zip) download page.
2. Click the**DesktopOK\_x64.zip** (for the portable app version) to save the archive.
3. Simultaneously press the**Windows** logo +**E** keys on your keyboard to activate File Explorer.
4. Go to the folder containing the DesktopOK ZIP archive.
5. Follow the instructions in this[how-to unzip archives in Windows guide](https://www.makeuseof.com/unzip-files-windows-10/) to extract the ZIP file.

1. Then double-click the**DesktopOK\_x64.exe** file.
2. Click**Tools** on the DesktopOK window.  
![The Windows-Metrics option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-metrics-option.jpg)
3. Select**Windows-Metrics** on the**Tools** menu.
4. Click**Yes** on the confirmation dialog prompt.
5. Drag the**Horizontal Space** bar’s slider to change horizontal desktop icon spacing.  
![The spacing bars](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/spacing-bars.jpg)
6. Then drag the**Vertical Space** bar’s slider to adjust vertical icon spacing.

 You can also change desktop icon sizes from the Windows-Metrics window. Click the**Desktop icon size** drop-down menu to choose an alternative size from there. If you select the largest icon sizes, you’ll need to increase the spacing between them to prevent them overlapping.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Much Icon Space Do You Want on Your Desktop?

 So, would you prefer the desktop icons in Windows 11/10 to have more or less space between them? Reducing desktop icon space will free up space for more shortcuts. However, some Microsoft Surface touchscreen PC users might prefer to widen the spaces between icons a little bit. You can choose either way by manually editing the registry or adjusting spacing with Winaero Tweaker’s**Icon** option or the Windows-Metrics utility in DesktopOK.

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
<li><a href="https://screen-recording.techidaily.com/new-how-to-do-voiceover-on-powerpoint/"><u>[New] How to Do Voiceover on PowerPoint</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-capturing-the-essence-including-dates-in-image-files/"><u>[Updated] Capturing the Essence Including Dates in Image Files</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/crafting-an-uninterrupted-viewing-experience-set-up-youtube-autoplay-on-fb/"><u>Crafting an Uninterrupted Viewing Experience Set Up Youtube Autoplay on FB</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-browsing-post-windows-installation/"><u>Effortless Browsing Post-Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-user-biometric-use-by-domains/"><u>Enabling/Disabling User Biometric Use by Domains</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-superiorly-crafted-radio-scripts/"><u>In 2024, Superiorly Crafted Radio Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-windows-0x80242016-update-fails/"><u>Navigating Past Windows' 0X80242016 Update Fails</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsofts-safe-mode-only-constraint/"><u>Navigating Through Microsoft's Safe Mode Only Constraint</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Oppo A79 5G | Dr.fone</u></a></li>
</ul></div>

