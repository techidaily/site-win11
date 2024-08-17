---
title: Coding a Deity Command Into System Menu
date: 2024-08-16T00:08:43.598Z
updated: 2024-08-17T00:08:43.598Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Coding a Deity Command Into System Menu
excerpt: This Article Describes Coding a Deity Command Into System Menu
keywords: Coding DevCommand,Integrate DeityMenu,SystemDeityIntegration,UIDeitySystemUpdate,CodeMenubox,SystemDeityCoding,AddDeityToUI
thumbnail: https://thmb.techidaily.com/c11b89b923631ed5d512ccc32ee592a5fb46939b31266627ae16098d24a9cb49.jpg
---

## Coding a Deity Command Into System Menu

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-webcam-safety-starts-here-the-10-best-shields/"><u>[New] 2024 Approved  Webcam Safety Starts Here - The 10 Best Shields</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-investigating-authenticitys-role-in-social-media-selfie-presentation/"><u>[New] Investigating Authenticity’s Role in Social Media Selfie Presentation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-masterpieces-revealed-topping-20-anime-themes/"><u>[New] Masterpieces Revealed  Topping 20 Anime Themes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-mastery-guide-installing-snapchat-on-mac-os/"><u>[New] Mastery Guide  Installing Snapchat on Mac OS</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-ultimate-capture-assistant-az-audits-and-alternatives/"><u>[New] Ultimate Capture Assistant - AZ Audits & Alternatives</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nveiling-the-secrets-of-iphones-video-loops-for-2024/"><u>[New] Unveiling the Secrets of iPhone's Video Loops for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-ai-and-windows-with-vivetool-steps/"><u>Bridging AI and Windows with ViveTool Steps</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-with-telnet-3-easy-steps-for-wins-users/"><u>Bridging the Gap with Telnet: 3 Easy Steps for Wins Users</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-dull-extend-volume-buttons-in-diskmgmt/"><u>Brighten Dull Extend Volume Buttons in DiskMgmt</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-win-11-usb-fastest-and-simplest-methods-for-3-ways/"><u>Building a Win 11 USB: Fastest and Simplest Methods for 3 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-power-management-avoid-hibernation-of-usb-devices/"><u>Bypass Power Management: Avoid Hibernation of USB Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-windows-auto-lock-feature/"><u>Bypass Windows Auto-Lock Feature</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-local-lsa-deactivated-warning/"><u>Bypassing 'Local LSA Deactivated' Warning</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-common-steam-connectivity-issues/"><u>Bypassing Common Steam Connectivity Issues</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-initial-load-issues-in-lotr-lol-game/"><u>Bypassing Initial Load Issues in LOTR (LOL) Game</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-shop-error-code-x800704cf/"><u>Bypassing Windows 11 Shop Error: Code X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/cant-set-the-time-zone-automatically-in-windows-try-these-fixes/"><u>Can’t Set the Time Zone Automatically in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/capture-your-gameplay-utilizing-windows-and-intel-graphics-tools/"><u>Capture Your Gameplay: Utilizing Windows & Intel Graphics Tools</u></a></li>
<li><a href="https://win11.techidaily.com/cease-use-of-voice-recognition-ai-on-windows/"><u>Cease Use of Voice Recognition AI on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-11-registry-access-settings/"><u>Changing Windows 11 Registry Access Settings</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-win11s-security-rufus-techniques/"><u>Circumventing Win11's Security: Rufus Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computers-for-a-modern-world-running-windows-11-through-to-go-and-rufus/"><u>Classic Computers for a Modern World: Running Windows 11 Through To Go and Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/cleanse-your-pc-banishing-temporary-windows-files/"><u>Cleanse Your PC: Banishing Temporary Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-access-denied-errors-fixing-outlook-issues-in-windows-os/"><u>Clearing 'Access Denied' Errors: Fixing Outlook Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-access-issues-fixing-files-not-displayed-on-windows-pc/"><u>Clearing Up Access Issues: Fixing Files Not Displayed on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusion-how-to-fix-0x8007045d-blue-screen-in-win11/"><u>Clearing Up Confusion: How to Fix 0X8007045d Blue Screen in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-corruption-fix-your-win1011-recycle-error/"><u>Clearing up CORRUPTION! Fix Your WIN10/11 Recycle Error</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-windows-1011-xbox-game-pass-connection-glitch/"><u>Clearing Windows 10/11: Xbox Game Pass Connection Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/clone-without-cutting-corners-windows-edition/"><u>Clone Without Cutting Corners: Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/cmd-magic-show-unraveling-5-mesmerizing-maneuvers/"><u>CMD Magic Show: Unraveling 5 Mesmerizing Maneuvers</u></a></li>
<li><a href="https://win11.techidaily.com/coherent-windows-icons-for-productivity-boost/"><u>Coherent Windows Icons for Productivity Boost</u></a></li>
<li><a href="https://win11.techidaily.com/combat-reduced-desktop-icon-dimensions-on-windows-11/"><u>Combat Reduced Desktop Icon Dimensions on Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-video-files-on-infinix-zero-30-5g-by-fonelab-android-recover-video/"><u>Complete guide for recovering video files on Infinix Zero 30 5G</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-scripting-striking-film-epilogues/"><u>In 2024, Scripting Striking Film Epilogues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/language-model-showdown-discerning-the-divergences-between-gpt-vs-bert-technologies/"><u>Language Model Showdown: Discerning the Divergences Between GPT vs BERT Technologies</u></a></li>
<li><a href="https://extra-information.techidaily.com/yuneec-typhoon-q500-4k-review/"><u>Yuneec Typhoon Q500 4K Review</u></a></li>
</ul></div>
