---
title: Enhancing Windows 11 Context Menu with Submenus
date: 2024-09-05T08:38:57.802Z
updated: 2024-09-06T08:38:57.802Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Windows 11 Context Menu with Submenus
excerpt: This Article Describes Enhancing Windows 11 Context Menu with Submenus
keywords: Win11 Menu Enhance,Windows Submenu Add,Context Menu Update,Windows UI Improve,Submenu for Windows,Context Menu Extend,Windows Menu Expansion
thumbnail: https://thmb.techidaily.com/3119c4d644ca38982b7a0f68d251b6e048a299751591496c468d996da741d28a.jpg
---

## Enhancing Windows 11 Context Menu with Submenus

 Windows 11’s desktop context menu is a place where you can add many software shortcuts even though the platform doesn’t include built-in customization settings for that menu. Many users add shortcuts to that menu with third-party software, but you can manually customize it with Registry Editor.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add a Submenu to the Context Menu by Manually Editing the Registry

 You can manually create a context menu submenu that includes any number of software shortcuts with the Registry Editor. For the sake of example, here we’ll create a submenu that includes shortcuts for opening the Notepad and Remote Desktop Connection apps. Then you can add more shortcuts for software on your PC. First, you’ll need to lay the foundation for the submenu as follows:

1. To access the registry app, check out this guide about [how to open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Go to a **shell** key by inputting the following location into the Registry Editor’s address bar:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell`
3. Right-click the **shell** key in the left sidebar and select the **New** \> **Key** options for adding a new registry entry.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/new-key-options.jpg)
4. Enter **Menu1** to be the new key’s name.
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right-click **Menu1** to select the **New** \> **String Value** options.

1. Input **MUIVerb** for the new string’s name.
2. Repeat step five to add another new string to the **Menu1** key. However, enter **SubCommands** to be this new string’s name.  
![The Menu1 registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-menu1-key.jpg)
3. Double-click the **MUIVerb** string added to the **Menu1** key.
4. Enter **Apps** in the **Value** box for the **MUIVerb** string, which will be the heading for your new context menu submenu. Or you can input a different submenu heading in the **Value data** box if preferred.  
![The MUIVerb string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/muiverb-string.jpg)
5. Click **OK** to exit the Edit String window for **MUIVerb**.
6. Next, double-click on the **SubCommand** string inside the **Menu1** key.
7. Input **Notepad; Remote Desktop Connection** inside the **Value** box for the **SubCommands** string and click **OK**.  
![subcommands-string-value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/subcommands-string-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now a new **App** submenu will be visible on Windows 11’s classic context menu. However, it won’t include any shortcuts. So, you will need to do some further editing of a different **shell** key to add functionality to the submenu. Edit the registry like this to complete the submenu:

1. Return to the Registry Editor and input this location into its address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\Shell`
2. Right-click **shell** to select **Key** on the **New** submenu.
3. Input **Notepad** to be the title for this new registry key.
4. Right-click on **Notepad** in Registry Editor’s left sidebar to select **New** \> **Key**.
5. Enter **command** to be the name of the subkey.
6. Double-click **(Default)** in the **Notepad** key.
7. Input **Notepad** into the **Value** box and click **OK**.
8. Double-click the **(Default)** string in the **command** subkey.
9. Enter this Notepad location into the **Value** box and select **OK**:  
`C:\Windows\System32\notepad.exe`  
![The Notepad path value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-notepad-path-value.jpg)
10. Repeat steps two to five to create a **Remote Desktop Connection** key with a **command** subkey, as shown in the snapshot directly below. Instead of naming the key Notepad, input **Remote Desktop Connection** for the new key’s title.  
![The Remote Desktop Connection and Notepad keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/notepad-and-remote-desktop-connection-keys.jpg)
11. Double-click the **(Default)** string for the **Remote Desktop Connection** key you created.
12. Input **Remote Desktop Connection** into the **Value** box and select **OK**.
13. Select the **command** subkey for the **Remote Desktop Connection** key and double-click its **(Default)** string.
14. Enter the following Remote Desktop Connection app path in the **Value** box and click **OK**:  
`"C:\Windows\System32\mstsc"`

 Now the new context menu submenu is complete. Right-click within an area of the Windows 11 desktop and select **Show more options** to view the secondary classic context menu. Move the cursor over the new **Apps** submenu from which you can select to open Notepad and Remote Desktop Connection.

![The Apps submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-apps-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can add more software shortcuts to that submenu. Note that the values you input for the **SubCommands** string must match the names of the registry keys created for the software shortcuts. In the example above, the **Notepad** and **Remote Desktop Connection** registry keys matched values input for the **SubCommands** string.

 You must also input the exact and full paths for whatever software you want the shortcuts to open within the **(Default)** strings of the command subkeys. In the example above, the **(Default)** strings of the **command** subkeys within the **Remote Desktop Connection** and **Notepad** keys include the paths for opening those apps.

 If you ever want to remove the submenu from the context menu, delete the key that created it. To do so, return to the registry location that includes the **Menu1** key. Right-click the **Menu1** key to select **Delete** and **Yes** for confirmation.

![The Delete option for the Menu1 key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/delete-option.jpg)

## How to Add a Submenu to the Context Menu With Easy Context Menu

 Easy Context Menu is a freely available context menu customization desktop app. That software enables you to add custom software shortcut submenus to the right-click menu without [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/).

 You can create a custom software shortcuts submenu with Easy Context Menu like this:

1. Navigate to the [Easy Context Menu](https://www.sordum.org/downloads/?easy-context-menu) download page.
2. Click **Direct Download** on that page to save the ZIP archive for Easy Context Menu.
3. Extract the **ec\_menu** ZIP with a method in this [guide for unzipping ZIP archives](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/) within Windows.  
![The Extract All option for ZIP archives](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/extract-all-option.jpg)
4. Open the extracted folder for Easy Context Menu and double-click the EXE file that runs the software from there.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134230/18498" target="_top" id="2134230">
  <img src="//a.impactradius-go.com/display-ad/18498-2134230" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134230/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click the **List Editor** button in Easy Context Menu.

1. Select **Desktop Context Menu** and press the **Add Sub Menu** button.
2. Input **Software Shortcuts** in the **Title** box for the new submenu.  
![The List Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu.jpg)
3. Click the **Add New** button with the **Software Shortcuts** submenu selected.
4. Select a program you want to include in the submenu and click **Open**.
5. Repeat the previous two steps to add more programs to the submenu.  
![A program shortcut added to the Software Shortcuts submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/program-shortcuts.jpg)
6. Select the checkboxes for the new **Software Shortcuts** submenu and the programs added to it in the List Editor window.
7. Press the **Save Changes** button and close the List Editor window.
8. Select the checkboxes for the **Software Shortcuts** submenu and the program options it includes within the Easy Context Menu window.  
![The Easy Context Menu window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/easy-context-menu-window.jpg)
9. Click **Apply Changes** to add the new submenu.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now check out the new **Software Shortcuts** submenu on Windows 11’s classic desktop context menu. That cascading menu will include all the programs you selected to add to it. It will also include program icons, so long as you leave the **Show icon in the Context Menu** checkboxes selected.

![software-shortcuts-submenu2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu2.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Another advantage of utilizing Easy Context Menu is that it includes options for positing the submenu. You can configure the approximate position of that submenu by selecting one of the three **Show at** options for it within the List Editor window. You can also reposition the submenu or items in it by selecting them and clicking the **Move Up** or **Move Down** buttons.

 Easy Context Menu also includes **Tools**, **System Tools**, and **Turn Off Options** submenus for you to add to the right-click menu. To add those submenus, select the **System Tools**, **Turn Off Options**, and **Tools** checkboxes for the desktop context menu and click **Apply Changes**. You can also deselect some of the checkboxes for those submenus to remove certain shortcuts from them.

![A Tools submenu added with Easy Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-tools-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115943/19272" target="_top" id="2115943">
  <img src="//a.impactradius-go.com/display-ad/19272-2115943" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Organize Your Windows Desktop Context Menu Shortcuts With Submenus

 Adding one or more submenus to Windows 11’s desktop context menu will enable you to organize the software shortcuts added to it.

 You could create multiple submenus on the context menu that include shortcuts for opening different software categories, such as web browsers, media players, productivity apps, etc. Or you can add a new desktop context menu submenu for accessing Windows tools and turn off options with Easy Context Menu.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-channeling-creativity-get-green-screen-tips-from-youtube/"><u>[New] 2024 Approved  Channeling Creativity  Get Green Screen Tips From YouTube</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-unite-gamers-and-followers-xboxfb-livestream-guide/"><u>[New] 2024 Approved  Unite Gamers & Followers  Xbox/FB Livestream Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-shooting-for-beginners-best-cams-reviewed-2024-edition/"><u>[New] Shooting for Beginners  Best Cams Reviewed 2024 Edition</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-seamless-search-for-your-youtube-comments-across-platforms/"><u>[Updated] In 2024, Seamless Search for Your YouTube Comments Across Platforms</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-mastering-magic-essential-filters-to-make-your-videos-pop/"><u>[Updated] Mastering Magic  Essential Filters to Make Your Videos Pop</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unleashing-classic-ps3-games-on-your-pc-for-2024/"><u>[Updated] Unleashing Classic PS3 Games on Your PC for 2024</u></a></li>
<li><a href="https://solve-latest.techidaily.com/1-macavchdmkvwmvmp4/"><u>1. Mac電腦支援多種格式快速轉檔軟體，AVCHD、MKV、WMV、MP4</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015570878-astro-a50-speaker-mic-not-working-heres-how-to-fix-it/"><u>Astro A50 Speaker-Mic Not Working? Here's How to Fix It!</u></a></li>
<li><a href="https://win11.techidaily.com/comparative-study-how-microsoft-and-default-windows-user-accounts-diverge/"><u>Comparative Study: How Microsoft and Default Windows User Accounts Diverge</u></a></li>
<li><a href="https://some-tips.techidaily.com/cookiebot-driven-marketing-unleashing-the-full-potential-of-your-digital-strategy/"><u>Cookiebot-Driven Marketing: Unleashing the Full Potential of Your Digital Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-webcam-written-as-how-to-fix-your-webcam-showing-a-black-screen-on-windows/"><u>Correcting Windows Webcam' Written as How to FIX Your WebCam Showing a BLACK SCREEN on WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/direct-routes-to-windows-11s-safe-mode-for-it-professionals/"><u>Direct Routes to Windows 11'S Safe Mode for IT Professionals</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diy-techniques-how-to-access-your-iphones-sim-tray-without-an-ejector-pin/"><u>DIY Techniques: How to Access Your iPhone's SIM Tray Without an Ejector Pin</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-galaxy-a14-4g-support-mov-videos-by-aiseesoft-video-converter-play-mov-on-android/"><u>Does Galaxy A14 4G support MOV videos ?</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-unwanted-quit-alerts-from-roblox-installations/"><u>Eliminating Unwanted 'Quit' Alerts From Roblox Installations</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-explorer-photo-functionality/"><u>Enhancing Windows Explorer Photo Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/exciting-laptop-releases-at-ifa-2023/"><u>Exciting Laptop Releases at IFA 2023</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-messaging-disclose-whereabouts-easily/"><u>Facebook Messaging: Disclose Whereabouts Easily</u></a></li>
<li><a href="https://driver-install.techidaily.com/fast-driver-update-new-gaming-mouse/"><u>Fast Driver Update: New Gaming Mouse</u></a></li>
<li><a href="https://win11.techidaily.com/first-timers-guide-to-navigating-windows-tools/"><u>First Timer's Guide to Navigating Windows Tools</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-lava-agni-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-users-from-changing-the-screensaver-on-windows/"><u>How to Stop Users From Changing the Screensaver on Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-icloud-separation-how-to-disconnect-iphone-6-and-ipad-by-drfone-ios/"><u>In 2024, iCloud Separation How To Disconnect iPhone 6 and iPad</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-printer-support-into-application-guard/"><u>Integrating Printer Support Into Application Guard</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/is-paying-up-for-vision-pro-worth-it-heres-why/"><u>Is Paying Up For Vision Pro Worth It? Here’s Why</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-advanced-visuals-within-edges-security/"><u>Mastering Advanced Visuals Within Edge's Security</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-warhammers-precision-gameplay-end-stuttering-on-windows/"><u>Mastering Warhammer's Precision Gameplay - End Stuttering on Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-decoding-the-best-music-arrangement-apps-iphone-and-android-guide-for-2024/"><u>New Decoding the Best Music Arrangement Apps IPhone & Android Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-gameplay-in-win-11-navigating-the-leading-fps-apps-and-monitors/"><u>Optimal Gameplay in Win 11: Navigating the Leading FPS Apps & Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-with-high-dynamic-range-on-windows-11-systems/"><u>Pushing Boundaries with High Dynamic Range on Windows 11 Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/quash-unwanted-youtube-suggested-videos-for-2024/"><u>Quash Unwanted YouTube Suggested Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/re-enabling-disabled-recycle-bin-on-win11/"><u>Re-Enabling Disabled Recycle Bin on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-not-found-entry-point-errors/"><u>Rectifying Windows 'Not Found' Entry Point Errors</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-your-system-replacing-outdated-windows-cards/"><u>Rejuvenating Your System: Replacing Outdated Windows Cards</u></a></li>
<li><a href="https://win11.techidaily.com/removing-restrictions-for-microsoft-store-in-windows-11/"><u>Removing Restrictions for Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-copypaste-errors-on-windows-11-pcs/"><u>Resolving Copy/Paste Errors on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-errors-in-windows/"><u>Resolving Disk Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solving-microsoft-11s-input-lag-8-effective-steps/"><u>Solving Microsoft 11'S Input Lag: 8 Effective Steps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-zoom-livestream-setup-guide-for-youtube-enthusiasts-for-2024/"><u>Step-by-Step Zoom Livestream Setup Guide for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/streamlining-virtual-collaborations-a-comprehensive-scheduling-and-recording-manual-for-slack-plus-filmora-for-2024/"><u>Streamlining Virtual Collaborations  A Comprehensive Scheduling & Recording Manual for Slack + Filmora for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-windows-update-eliminating-error-0x800736cc/"><u>Swift Solutions for Windows Update: Eliminating Error 0X800736CC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-most-debated-apple-innovations-of-all-time-from-scorn-to-stardom/"><u>The Most Debated Apple Innovations of All Time - From Scorn to Stardom</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-guide-to-free-sound-effects-for-final-cut-pro-editors/"><u>The Ultimate Guide to Free Sound Effects for Final Cut Pro Editors</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-setup-effortless-installation-of-legacy-applications/"><u>Windows 11 Setup: Effortless Installation of Legacy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/windows-arp-cache-explained-and-guide-to-clear-it-out/"><u>Windows ARP Cache Explained & Guide to Clear It Out</u></a></li>
<li><a href="https://win11.techidaily.com/winrush-securing-past-command-actions/"><u>WinRush: Securing Past Command Actions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>