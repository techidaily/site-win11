---
title: "Mastering Window Customization: Adding Contextual Options in Win 11"
date: 2024-08-15T23:35:17.893Z
updated: 2024-08-16T23:35:17.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Window Customization: Adding Contextual Options in Win 11"
excerpt: "This Article Describes Mastering Window Customization: Adding Contextual Options in Win 11"
keywords: Win 11 UI Tweaks,Windows 11 Customize,Win11 Widgets,Windows Personalization,Enhance Win11 UI,Window Themes in Win11,Contextual UI Options Win11
thumbnail: https://thmb.techidaily.com/e03e7f36869e1845d154715bfdea777a291cb2eaca41f020a72559cf27e30f77.jpg
---

## Mastering Window Customization: Adding Contextual Options in Win 11

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

## How to Add a Submenu to the Context Menu With Easy Context Menu

 Easy Context Menu is a freely available context menu customization desktop app. That software enables you to add custom software shortcut submenus to the right-click menu without [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/).

 You can create a custom software shortcuts submenu with Easy Context Menu like this:

1. Navigate to the [Easy Context Menu](https://www.sordum.org/downloads/?easy-context-menu) download page.
2. Click **Direct Download** on that page to save the ZIP archive for Easy Context Menu.
3. Extract the **ec\_menu** ZIP with a method in this [guide for unzipping ZIP archives](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/) within Windows.  
![The Extract All option for ZIP archives](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/extract-all-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
4. Open the extracted folder for Easy Context Menu and double-click the EXE file that runs the software from there.
5. Click the **List Editor** button in Easy Context Menu.

1. Select **Desktop Context Menu** and press the **Add Sub Menu** button.
2. Input **Software Shortcuts** in the **Title** box for the new submenu.  
![The List Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Click the **Add New** button with the **Software Shortcuts** submenu selected.
4. Select a program you want to include in the submenu and click **Open**.
5. Repeat the previous two steps to add more programs to the submenu.  
![A program shortcut added to the Software Shortcuts submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/program-shortcuts.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the checkboxes for the new **Software Shortcuts** submenu and the programs added to it in the List Editor window.
7. Press the **Save Changes** button and close the List Editor window.
8. Select the checkboxes for the **Software Shortcuts** submenu and the program options it includes within the Easy Context Menu window.  
![The Easy Context Menu window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/easy-context-menu-window.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Click **Apply Changes** to add the new submenu.

 Now check out the new **Software Shortcuts** submenu on Windows 11’s classic desktop context menu. That cascading menu will include all the programs you selected to add to it. It will also include program icons, so long as you leave the **Show icon in the Context Menu** checkboxes selected.

![software-shortcuts-submenu2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu2.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Another advantage of utilizing Easy Context Menu is that it includes options for positing the submenu. You can configure the approximate position of that submenu by selecting one of the three **Show at** options for it within the List Editor window. You can also reposition the submenu or items in it by selecting them and clicking the **Move Up** or **Move Down** buttons.

 Easy Context Menu also includes **Tools**, **System Tools**, and **Turn Off Options** submenus for you to add to the right-click menu. To add those submenus, select the **System Tools**, **Turn Off Options**, and **Tools** checkboxes for the desktop context menu and click **Apply Changes**. You can also deselect some of the checkboxes for those submenus to remove certain shortcuts from them.

![A Tools submenu added with Easy Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-tools-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-basic-obs-setup-tips-for-budget-machines/"><u>[New] 2024 Approved  Basic OBS Setup Tips for Budget Machines</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-frame-perfect-our-top-10-photo-lenses-list/"><u>[New] 2024 Approved  Frame Perfect  Our Top 10 Photo Lenses List</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-discoveries-10-facebook-meme-pages-that-surprise-you/"><u>[New] Discoveries  10 Facebook Meme Pages That Surprise You</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-is-inshot-leading-video-editing-an-examination-review/"><u>[New] In 2024, Is InShot Leading Video Editing? An Examination Review</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-rise-to-prominence-6-game-changing-approaches-for-instagram-verification-and-fan-increase/"><u>[New] In 2024, Rise to Prominence  6 Game-Changing Approaches for Instagram Verification & Fan Increase</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-virtual-realitys-creativity-quandary-a-2023-outlook/"><u>[Updated] In 2024, Virtual Reality's Creativity Quandary - A 2023 Outlook</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-securing-your-speech-on-the-ipad/"><u>[Updated] Securing Your Speech on the iPad</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-stop-the-background-from-automatically-changing-on-windows-11/"><u>6 Ways to Stop the Background From Automatically Changing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-resolve-virtual-machines-on-windows-11-vmware/"><u>7 Key Steps to Resolve Virtual Machines on Windows 11-VMware</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-vivo-y78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-windows-11s-speedy-startup/"><u>A Beginner's Guide to Windows 11'S Speedy Startup</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-look-at-triggering-system-restore-in-windows-11/"><u>A Detailed Look at Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-the-new-era-of-laptops-at-ifa-2023/"><u>A Journey Into the New Era of Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-guide-to-infusing-personality-into-your-calendar/"><u>A Window's Guide to Infusing Personality Into Your Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-type-speed-cutting-down-lag-on-windows-11/"><u>Accelerating Type Speed: Cutting Down Lag on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/acceleration-at-fingertips-3-ways-to-enhance-mouse-double-click-speed/"><u>Acceleration at Fingertips: 3 Ways to Enhance Mouse Double-Click Speed</u></a></li>
<li><a href="https://win11.techidaily.com/1719347210677-access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings.</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/activating-local-administrator-tools-in-windows-1110-home/"><u>Activating Local Administrator Tools in Windows 11/10 Home</u></a></li>
<li><a href="https://win11.techidaily.com/adapt-window-placement-for-windows-os/"><u>Adapt Window Placement for Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-to-new-horizons-migrating-apps-for-a-windows-11-laptop/"><u>Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-command-prompt-authorization-problems/"><u>Addressing Command Prompt Authorization Problems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-system-breakdown-windows-c0000022-fixes/"><u>Addressing Critical System Breakdown: Windows C0000022 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-empty-folder-warning-windows/"><u>Addressing Empty Folder Warning Windows</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-pc-energy-utilization-efficiency/"><u>Assessing Windows PC Energy Utilization Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-mastering-the-deletion-of-drive-partitions-in-win-os/"><u>Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unending-enter-password-interruptions-in-windows/"><u>Avoiding Unending Enter Password Interruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/black-out-bliss-with-microsofts-basic-brush/"><u>Black-Out Bliss with Microsoft's Basic Brush</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-game-loading-times-for-epic-universe/"><u>Boosting Game Loading Times for Epic Universe</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-win1011-graphics-power-the-ultimate-guide-to-vram/"><u>Boosting Win10/11 Graphics Power: The Ultimate Guide to VRAM</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-the-benefits-of-hulu-vs-the-added-perks-of-hulu-plus/"><u>Decoding the Benefits of Hulu Vs. The Added Perks of Hulu Plus</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>Does Airplane Mode Turn off GPS Location On Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/effortless-tips-for-storing-vimeo-videos-for-2024/"><u>Effortless Tips for Storing Vimeo Videos for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/grasping-the-full-potential-of-animoji-on-iphone-x/"><u>Grasping the Full Potential of Animoji on iPhone X</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-download-and-install-a-comprehensive-walkthrough-of-the-newest-radeon-hd-graphics-card-drivers-by-amd/"><u>Hassle-Free Download & Install: A Comprehensive Walkthrough of the Newest Radeon HD Graphics Card Drivers by AMD</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-iphone-13-pro-face-id-by-drfone-ios-unlock-ios-unlock/"><u>How to Bypass iPhone 13 Pro Face ID?</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-overcome-cod-black-ops-cold-war-glitch-error-code-887a0005/"><u>How To Overcome COD Black Ops Cold War Glitch 'Error Code: 887A0005'</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-cinematic-clarity-premium-handheld-stabilizers-selection/"><u>In 2024, Cinematic Clarity  Premium Handheld Stabilizers Selection</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-devising-visual-temporal-anomalies-effects/"><u>In 2024, Devising Visual Temporal Anomalies Effects</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-enhance-tiktok-authenticity-changing-your-digital-vocal-trail/"><u>In 2024, Enhance TikTok Authenticity  Changing Your Digital Vocal Trail</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-vivo-x-flip-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Vivo X Flip Phones with/without a PC</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-scrutinizing-software-for-video-editing-the-bandicam-camtasia-comparison/"><u>In 2024, Scrutinizing Software for Video Editing  The Bandicam-Camtasia Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/1719307817163-keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now!</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-tips-incorporating-video-from-youtube-into-google-presentations-for-2024/"><u>Quick Tips  Incorporating Video From YouTube Into Google Presentations for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/secrets-to-successful-twitpicingvideos-included/"><u>Secrets to Successful Twitpicing—Videos Included</u></a></li>
</ul></div>
