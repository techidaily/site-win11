---
title: "Personalizing Your Windows Environment: Adding to the Desktop Menu"
date: 2024-08-16T00:33:37.012Z
updated: 2024-08-17T00:33:37.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalizing Your Windows Environment: Adding to the Desktop Menu"
excerpt: "This Article Describes Personalizing Your Windows Environment: Adding to the Desktop Menu"
keywords: Customize Desktop Menu,Windows Personalization,Add To Menu Windows,Widgets On Desktop,Theme Changes Window,Icon Placement Windows,Aesthetic Settings PC
thumbnail: https://thmb.techidaily.com/56e9a63f6cd0da6aa662fe6ddfb8ba418b2232ba03eb8e75fedd97f8000b9ecc.jpg
---

## Personalizing Your Windows Environment: Adding to the Desktop Menu

 Windows 11’s desktop context menu is a place where you can add many software shortcuts even though the platform doesn’t include built-in customization settings for that menu. Many users add shortcuts to that menu with third-party software, but you can manually customize it with Registry Editor.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

## How to Add a Submenu to the Context Menu by Manually Editing the Registry

 You can manually create a context menu submenu that includes any number of software shortcuts with the Registry Editor. For the sake of example, here we’ll create a submenu that includes shortcuts for opening the Notepad and Remote Desktop Connection apps. Then you can add more shortcuts for software on your PC. First, you’ll need to lay the foundation for the submenu as follows:

1. To access the registry app, check out this guide about [how to open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Go to a **shell** key by inputting the following location into the Registry Editor’s address bar:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell`
3. Right-click the **shell** key in the left sidebar and select the **New** \> **Key** options for adding a new registry entry.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/new-key-options.jpg)
4. Enter **Menu1** to be the new key’s name.
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

 You can add more software shortcuts to that submenu. Note that the values you input for the **SubCommands** string must match the names of the registry keys created for the software shortcuts. In the example above, the **Notepad** and **Remote Desktop Connection** registry keys matched values input for the **SubCommands** string.

 You must also input the exact and full paths for whatever software you want the shortcuts to open within the **(Default)** strings of the command subkeys. In the example above, the **(Default)** strings of the **command** subkeys within the **Remote Desktop Connection** and **Notepad** keys include the paths for opening those apps.

 If you ever want to remove the submenu from the context menu, delete the key that created it. To do so, return to the registry location that includes the **Menu1** key. Right-click the **Menu1** key to select **Delete** and **Yes** for confirmation.

![The Delete option for the Menu1 key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## How to Add a Submenu to the Context Menu With Easy Context Menu

 Easy Context Menu is a freely available context menu customization desktop app. That software enables you to add custom software shortcut submenus to the right-click menu without [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/).

 You can create a custom software shortcuts submenu with Easy Context Menu like this:

1. Navigate to the [Easy Context Menu](https://www.sordum.org/downloads/?easy-context-menu) download page.
2. Click **Direct Download** on that page to save the ZIP archive for Easy Context Menu.
3. Extract the **ec\_menu** ZIP with a method in this [guide for unzipping ZIP archives](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/) within Windows.  
![The Extract All option for ZIP archives](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/extract-all-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Open the extracted folder for Easy Context Menu and double-click the EXE file that runs the software from there.
5. Click the **List Editor** button in Easy Context Menu.

1. Select **Desktop Context Menu** and press the **Add Sub Menu** button.
2. Input **Software Shortcuts** in the **Title** box for the new submenu.  
![The List Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click the **Add New** button with the **Software Shortcuts** submenu selected.
4. Select a program you want to include in the submenu and click **Open**.
5. Repeat the previous two steps to add more programs to the submenu.  
![A program shortcut added to the Software Shortcuts submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/program-shortcuts.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the checkboxes for the new **Software Shortcuts** submenu and the programs added to it in the List Editor window.
7. Press the **Save Changes** button and close the List Editor window.
8. Select the checkboxes for the **Software Shortcuts** submenu and the program options it includes within the Easy Context Menu window.  
![The Easy Context Menu window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/easy-context-menu-window.jpg)
9. Click **Apply Changes** to add the new submenu.

 Now check out the new **Software Shortcuts** submenu on Windows 11’s classic desktop context menu. That cascading menu will include all the programs you selected to add to it. It will also include program icons, so long as you leave the **Show icon in the Context Menu** checkboxes selected.

![software-shortcuts-submenu2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu2.jpg)

 Another advantage of utilizing Easy Context Menu is that it includes options for positing the submenu. You can configure the approximate position of that submenu by selecting one of the three **Show at** options for it within the List Editor window. You can also reposition the submenu or items in it by selecting them and clicking the **Move Up** or **Move Down** buttons.

 Easy Context Menu also includes **Tools**, **System Tools**, and **Turn Off Options** submenus for you to add to the right-click menu. To add those submenus, select the **System Tools**, **Turn Off Options**, and **Tools** checkboxes for the desktop context menu and click **Apply Changes**. You can also deselect some of the checkboxes for those submenus to remove certain shortcuts from them.

![A Tools submenu added with Easy Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-tools-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Organize Your Windows Desktop Context Menu Shortcuts With Submenus

 Adding one or more submenus to Windows 11’s desktop context menu will enable you to organize the software shortcuts added to it.

 You could create multiple submenus on the context menu that include shortcuts for opening different software categories, such as web browsers, media players, productivity apps, etc. Or you can add a new desktop context menu submenu for accessing Windows tools and turn off options with Easy Context Menu.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-pc-playback-protocol-for-consoles-an-instructive-path-for-2024/"><u>[New] PC Playback Protocol for Consoles  An Instructive Path for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-novice-to-pro-simplified-youtube-live-streaming-with-obs/"><u>[Updated] In 2024, From Novice to Pro  Simplified YouTube Live Streaming with OBS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y100-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y100 5G</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-honor-100-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Honor 100</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audiovisual-harmony-perfecting-voiceover-in-videos-for-2024/"><u>Audiovisual Harmony  Perfecting Voiceover in Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-winupdate-failure-x8019-error/"><u>Correcting WinUpdate Failure: X8019 Error</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-execution-descriptors-in-software-life-cycles/"><u>Deciphering Execution Descriptors in Software Life Cycles</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-the-windows-update-file-absence-issue-error-0x80070003/"><u>Decoding and Fixing the Windows Update File Absence Issue (Error 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/detecting-authenticated-access-vs-unauthorized-hurdles-in-windows/"><u>Detecting Authenticated Access vs Unauthorized Hurdles in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-techniques-for-engaging-conversations-in-mozilla-thunderbird/"><u>Effective Techniques for Engaging Conversations in Mozilla Thunderbird</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/effortlessly-record-high-quality-mac-audio-using-audacity-for-2024/"><u>Effortlessly Record High-Quality Mac Audio Using Audacity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-address-unresponsive-spotify-windows/"><u>Essential Steps to Address Unresponsive Spotify Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exclude-non-critical-windows-suggestions-and-tips/"><u>Exclude Non-Critical Windows Suggestions and Tips</u></a></li>
<li><a href="https://article-helps.techidaily.com/expanding-photography-quality-for-2024/"><u>Expanding Photography Quality for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/experience-the-mighty-radpower-radcity-5plus-bike-balancing-capability-with-weight-considerations/"><u>Experience the Mighty RadPower RadCity 5+ Bike – Balancing Capability with Weight Considerations</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-iphone-15-pro-max-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your iPhone 15 Pro Max Apple ID and Apple Pay</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-apple-iphone-14-by-drfone-ios/"><u>How To Change Your Apple ID Password On your Apple iPhone 14</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-manage-virtual-machines-tpm-and-secure-boot-on-vbox-70/"><u>How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-non-accelerated-workflows-on-windows-systems/"><u>How to Optimize Non-Accelerated Workflows on Windows Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/hush-play-relax-with-idling-titles/"><u>Hush, Play: Relax with Idling Titles</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solutions-for-non-functional-xbox-in-windows/"><u>Immediate Solutions for Non-Functional Xbox in Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-samsung-galaxy-a54-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Samsung Galaxy A54 5G Devices | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leverage-windows-11-activating-hyper-v/"><u>Leverage Windows 11: Activating Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-intrusive-minimize-feature/"><u>Overcoming Windows' Intrusive Minimize Feature</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-cant-access-mail-error-in-windows-11-email-service/"><u>Rectifying Can't Access Mail Error in Windows 11 Email Service</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-excessive-ram-use-solutions-for-service-platforms-on-pcs/"><u>Reducing Excessive RAM Use: Solutions for Service Platforms on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-printing-service-on-pc-post-error-alert-in-windows/"><u>Restoring Printing Service on PC, Post Error Alert in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-non-working-filesystem-consolidator/"><u>Reversing Non-Working Filesystem Consolidator</u></a></li>
<li><a href="https://win-answers.techidaily.com/sea-of-thieves-stability-restored-say-goodbye-to-unexpected-shutdowns/"><u>Sea of Thieves Stability Restored: Say Goodbye to Unexpected Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-security-4-efficient-actions-to-banish-users-from-win11-systems/"><u>Simplified Security: 4 Efficient Actions to Banish Users From Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/sound-superchargers-select-tools-that-elevate-pc-volume-past-100-limit/"><u>Sound Superchargers: Select Tools That Elevate PC Volume Past 100%% Limit</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-launching-sticky-notes-in-win11/"><u>Step-by-Step: Launching Sticky Notes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-device-not-found-error-when-connecting-usb-to-virtualbox/"><u>Steps to Rectify 'Device Not Found' Error When Connecting USB to VirtualBox</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721461992906-struggling-to-link-your-iphone-with-your-computer-discover-the-solutions/"><u>Struggling to Link Your iPhone With Your Computer? Discover the Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tesla-robotaxi-revealed-speculations-surrounding-price-point-expected-launch-and-technical-details/"><u>Tesla Robotaxi Revealed - Speculations Surrounding Price Point, Expected Launch, and Technical Details</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-apps-and-online-tools-to-track-oppo-a58-4g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Oppo A58 4G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win11.techidaily.com/top-review-the-ultimate-guide-to-garmin-forerunner-745-for-multisports-enthusiasts/"><u>Top Review: The Ultimate Guide to Garmin Forerunner 745 for Multisports Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-email-alerts-in-windows/"><u>Troubleshooting Non-Responsive Email Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-dxvks-role-in-linuxwindows-gameplay/"><u>Understanding DXVK's Role in Linux/Windows Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-windows-system-craft-a-distributed-transcoding-powerhouse-with-tdarr/"><u>Upgrade Windows System: Craft a Distributed Transcoding Powerhouse with Tdarr</u></a></li>
</ul></div>
