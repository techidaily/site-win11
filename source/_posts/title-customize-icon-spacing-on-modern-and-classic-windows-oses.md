---
title: "Title: Customize Icon Spacing on Modern & Classic Windows OSes"
date: 2024-08-16T00:50:10.774Z
updated: 2024-08-17T00:50:10.774Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Title: Customize Icon Spacing on Modern & Classic Windows OSes"
excerpt: "This Article Describes Title: Customize Icon Spacing on Modern & Classic Windows OSes"
keywords: Win Icon Spacing Customization,Icon Layout Modern OS,Classic OS Icon Adjustment,Custom Icon Alignment,Windows Icon Settings,Modern OS Icon Spacing,Adjust Icons in Classic OS
thumbnail: https://thmb.techidaily.com/b60c76ffc589ae0e04ed8d9626d309109b105480cf9bd2a5898ac2cac1fa41f0.jpg
---

## Title: Customize Icon Spacing on Modern & Classic Windows OSes

 Windows 11 includes three desktop context menu options for changing icon size. However, those settings do nothing to change the spacing between icons. Nor does the Settings app or Control Panel offer any configuration settings with which to adjust icon spacing variables.

 As such, it might seem that you can’t change icon spacing on the desktop in Windows 11/10\. However, Windows 11 does have two hidden settings for changing the vertical and horizontal desktop icon spacing in the form of registry strings. Here is how you can change desktop icon spacing in Windows 11/10 in two different ways.

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
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
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
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
5. Then drag the slider for the**Vertical spacing** bar left or right to adjust the amount of vertical space for desktop icons.
6. Press the**Apply changes** button.
7. Click the**Sign out now** option to restart your PC and apply the icon spacing changes.

 That’s it. Now you can see the icon spacing change on the Windows 11 desktop.

 If you go a bit over the top with the space changes, you can easily readjust the values with Winaero Tweaker’s icon spacing slider bars. To restore the default spacing, click the**Reset this page to defaults** option for the Icon option.

 You might also notice that Winaero Tweaker’s Icon option has an additional**Change icons font** setting. That option enables you to choose a different font for your desktop icons. Press the**Change Font icon** button to bring up the window shown below.

![The Font window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/font-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

 There you can select a different icon font from a wide variety of alternatives in the**Font** menu. The**Font style** menu there includes 12 different styles for icon fonts to choose from. Input a higher or lower value in the**Size** box to increase or decrease the font size. You can also select**Strikeout** and**Underline** text effect options there.

 Click**OK** when you’ve customized the desktop icon font, and then select the**Apply Changes** and**Sign out** now options.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then drag the**Vertical Space** bar’s slider to adjust vertical icon spacing.

 You can also change desktop icon sizes from the Windows-Metrics window. Click the**Desktop icon size** drop-down menu to choose an alternative size from there. If you select the largest icon sizes, you’ll need to increase the spacing between them to prevent them overlapping.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-efficiently-extracting-twitters-visual-jokes-gifs/"><u>[New] 2024 Approved  Efficiently Extracting Twitter's Visual Jokes (GIFs)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-premium-list-live-streaming-with-local-channel-support-2024/"><u>[New] The Premium List  Live Streaming with Local Channel Support, 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-how-to-master-video-capture-using-adobe-presenter/"><u>[Updated] 2024 Approved  How to Master Video Capture Using Adobe Presenter</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-cinematic-wonders-with-hero5-black-a-filmmakers-companion/"><u>[Updated] Cinematic Wonders with Hero5 Black  A Filmmaker's Companion</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-screeneasew11-simplified-windows-11-recording-software-for-2024/"><u>[Updated] ScreenEaseW11  Simplified Windows 11 Recording Software for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-audible-allure-choosing-background-beats-for-videos/"><u>2024 Approved  Audible Allure  Choosing Background Beats for Videos</u></a></li>
<li><a href="https://win11.techidaily.com/delaying-microsoft-edge-tabs-a-win11-guide/"><u>Delaying Microsoft Edge Tabs: A Win11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-disk-identities-c-vs-d-a-review/"><u>Demystifying Disk Identities (C vs D): A Review</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/engaging-audiences-with-wirecast-hosted-facebook-streams/"><u>Engaging Audiences with Wirecast-Hosted Facebook Streams</u></a></li>
<li><a href="https://win11.techidaily.com/escape-key-troubles-discover-immediate-remedies-for-your-pc/"><u>Escape Key Troubles? Discover Immediate Remedies for Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-successful-windows-11-updates/"><u>Guaranteeing Successful Windows 11 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-swift-control-panel-navigation-in-windows/"><u>Guide to Swift Control Panel Navigation in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-oppo-a38-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Oppo A38</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-stalled-status-on-qbittorrent-for-windows/"><u>How to Fix the Stalled Status on qBittorrent for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-error-code-0xc0000005-a-techs-approach/"><u>How to Overcome Error Code 0XC0000005: A Tech's Approach</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-gionee-f3-pro-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Gionee F3 Pro without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-split-screen-errors-in-windows/"><u>How to Reset Split Screen Errors in WIndows</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-capturing-focus-with-leading-lines-in-iphone-images/"><u>In 2024, Capturing Focus with Leading Lines in iPhone Images</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, Methods to Change GPS Location On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-time-tamed-on-film-easy-steps-for-slow-mo-video-using-photo-apps/"><u>In 2024, Time Tamed on Film  Easy Steps for Slow-Mo Video Using Photo Apps</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-free-avi-video-rotation-tools-compare-the-best-options-for-windows-mac-mobile-and-online/"><u>New 2024 Approved Free AVI Video Rotation Tools Compare the Best Options for Windows, MAC, Mobile & Online</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-printer-service-not-running-issue-in-win/"><u>Overcoming Printer Service Not Running Issue in Win</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-image-failure-error-0x80780119/"><u>Overcoming Windows' Image Failure: Error 0X80780119</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-the-clicks-defeating-silent-spaces-on-pc/"><u>Reclaiming the Clicks: Defeating Silent Spaces on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-windows-operating-edition-epoch/"><u>Revealing Windows Operating Edition Epoch</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-strategies-for-definitions-in-win11/"><u>Speedy Strategies for Definitions in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-approach-to-configure-win11s-dns-client-service/"><u>Step-by-Step Approach to Configure Win11's DNS Client Service</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reinstate-the-mia-dxgidll-in-windows-11/"><u>Steps to Reinstate the MIA Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/taming-false-antivirus-alarms-a-windows-chrome-fix/"><u>Taming False Antivirus Alarms: A Windows Chrome Fix</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-rectifying-windows-msvcr110dll-gap/"><u>Tips for Rectifying Windows' msvcr110.dll Gap</u></a></li>
<li><a href="https://win11.techidaily.com/top-solutions-when-your-windows-security-is-down/"><u>Top Solutions When Your Windows Security Is Down</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-store-apps-in-windows-11/"><u>Troubleshooting Non-Functional Store Apps in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unstuck-apple-watch-discover-6-strategies-for-restoring-seamless-device-synchronization/"><u>Unstuck Apple Watch: Discover 6 Strategies for Restoring Seamless Device Synchronization</u></a></li>
<li><a href="https://win11.techidaily.com/win-centric-tips-for-switching-mkv-format-to-mp4/"><u>Win-Centric Tips for Switching MKV Format to MP4</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wizardry-six-routes-to-property-insight/"><u>Windows Wizardry: Six Routes to Property Insight</u></a></li>
</ul></div>
