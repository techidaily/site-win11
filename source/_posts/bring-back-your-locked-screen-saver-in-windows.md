---
title: Bring Back Your Locked Screen Saver in Windows
date: 2024-07-29T15:53:40.199Z
updated: 2024-07-30T15:53:40.199Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bring Back Your Locked Screen Saver in Windows
excerpt: This Article Describes Bring Back Your Locked Screen Saver in Windows
keywords: Restore Screensaver,Unlock Desktop Image,Reset Wallpaper Snooze,Reopen SceenSaver,Fix Locked Screen Saver,Recover Image Display,Reactivate Windows SafeScreen
thumbnail: https://thmb.techidaily.com/eb645c13ee9dd9fbe7f99fc761b9dd81222823674663074f051eaef5c591591c.jpg
---

## Bring Back Your Locked Screen Saver in Windows

 Just when you’re about to change the screen saver on your Windows device, the system settings start malfunctioning. You realize that the screen saver settings are grayed out—making it hard for you to change your current screen saver.

 Fortunately, we’ve got all the solutions you need. So, let’s dive in and check out the four ways to resolve this issue.

## 1\. Use the Local Group Policy Editor

 The “grayed out screen saver settings” error might be caused by issues that stem from the Local Group Policy Editor (LGPE). So, the best way to tackle the problem is to make some changes in the LGPE.

 However, bear in mind that the LGE is only available on Windows Pro, Enterprise, and Education editions. If you’re using the Home edition, then check out tips on how to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Let’s now explore how to use the LGPE to resolve the issue at hand:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Enable screen saver** option on the right-hand side.

![Clicking the Enable screen saver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-enable-screen-saver-option.jpg)

 Check the **Enabled** box on the next screen. From there, click **Apply** and then click **OK**.

 But then how would enabling the “screen saver” option resolve the “grayed out screen saver settings” error?

 As per the description in the LGPE, enabling the “screen saver” option enables the “Screen Saver” section in the Screen Saver Settings window. Simply put, this means enabling this option will ensure that the "screen saver settings" section isn't grayed out.

 Now, let’s explore how to enable another LGPE feature to tackle the “grayed out screen saver settings” error:

1. Open the **LGPE** and navigate to the **Personalization** folder as per the previous steps.
2. Double-click on the **Force specific screen saver** option on the right-hand side.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Clicking the Force specific screen saver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-force-specific-screen-saver-option.jpg)

 Check the **Disabled** box, click **Apply**, and then click **OK**.

 So, how does disabling the “Force specific screen saver” option help?

 When the “Force specific screen saver” option is enabled, the drop-down list of screen savers in the "Windows Screen Saver" dialog will be grayed out. This means you won’t be able to change your screen saver, but you may still be able to configure other related settings

 So, by disabling the “Force specific screen saver” feature, the "screen saver" drop-down menu in the Screen Saver Settings window won't be grayed out.

## 2\. Use the Registry Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 Now, we’ll show you how to get rid of the “grayed out screen saver settings” error using the Registry Editor. But if you tweak the wrong Registry keys by mistake, your device might end up crashing. That’s why we always recommend that you [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before editing its keys.

 Let’s now check out how this tool can help you resolve the issue at hand:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows

 Next, click the **Control Panel** key (folder) from the options within the "Windows" key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
![Clicking the Control Panel key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-control-panel-key.jpg)

 If the "Control Panel" key is missing, here’s how you can create it:

1. Right-click on the **Windows** folder (key) in the LGPE and select **New > Key**.
2. Name the key **Control Panel** and press **Enter**.

 Once you’re inside the "Control Panel" key, navigate to the right-hand side and locate the **ScreenSaveActive** option.

![Clicking the ScreenSaveActive option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-screensaveactive-option.jpg)

 If this value is missing, create it through these steps:

1. Right-click on a blank space and select **New > DWORD (32-bit) Value**.
2. Name the value as **ScreenSaveActive** and press **Enter**.

 The “ScreenSaveActive” option in the Registry Editor performs the same function as the “Enable screen saver” option in the LGPE. Remember, enabling the “Enable screen saver option” in the LGPE ensures that the settings on the Screen Saver Settings window aren’t grayed out.

 To enable the “ScreenSaveActive” option in the Registry Editor, double-click on this option and then set the "Value data" as **1**. From there, press **OK** and then restart your device to save the changes.

## 3\. Change the Power Settings

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 You might not be aware of this, but configuring the power settings usually has an effect on the other system settings.

 For example, if you enable power-saving mode, then your device will pause some tasks in an effort to save power. But enabling some power-saving features might end up graying out some settings and tools.

 Now, let's check out how to configure a few power settings to tackle the “grayed out screen saver settings” issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
### Change the Power Settings Via the Screen Saver Settings Window

 Did you know that you can tweak the power settings directly from the Screen Saver Settings window? Here are the steps you need to follow:

1. Type **Change screen saver** in the Start menu search bar and select the **Best match**. This should open the Screen Saver Settings window.
2. Scroll down to the **Power management** section.
3. Click the **Change power settings** option.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
![Clicking the Change power settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-change-power-settings-option.jpg)

 Select the **Change plan settings** option on the "Power Options" screen. This will display the "Edit Plan Settings" screen.

 From there, follow these steps:

1. Locate the **Turn off the display** and **Put computer to sleep** options.
2. Click the drop-down menus next to these options and select **Never** for all the options.
3. Click the **Save Changes** button.

![Clicking the Save Changes button on the Edit plan settings screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-save-changes-button-on-the-edit-plan-settings-screen.jpg)

 Next, configure the advanced power settings through these steps:

1. Type **Change screen saver** in the Start menu search bar and select the **Best match**.
2. Click the **Change power settings** option.
3. Select the **Change advanced power settings** option in the "Edit Plan Settings" window. This will display the "Power Options" screen.

 Expand the contents in the "Display" section and select **Never** for both the "On battery" and "Plugged in" options.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![Selecting the Display option in the Power Options screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/selecting-the-display-option-in-the-power-options-screen.jpg)

 Next, expand the "Desktop background settings" option and select **Never** for all the options in this section. Finally, click **Apply** and then click **OK** to save these changes.

 Want to restore your power settings to their defaults at a later stage?

 Simply navigate to the "Power Options" screen as per the previous steps and then click the **Restore plan defaults** button. Finally, click **Apply** and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![Clicking the Restore plan defaults button in the Power Options screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-restore-plan-defaults-button-in-the-power-options-screen.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
### Change the Power Settings via the Control Panel

 In some rare instances, you might not be able to access the power settings via the Screen Saver Settings window. So, this means you’d have to configure the power settings directly via the Control Panel.

 Let's take you through the steps you should follow:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select **Small icons**.
3. Select **Power Options** from the menu items.
4. Click **Change plan settings** from the options. This will take you to the "Edit Plan Settings" screen.

![The Edit Plan Settings on the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-plan-settings-on-the-control-panel.jpg)

 From there, you can edit all the necessary power settings using the tips we covered in the previous section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Get Rid of System Corruption or Update Your PC

![Computer antivirus illustration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/08/Computer-antivirus-illustration.jpg)

 Still struggling to resolve the "grayed out screen saver settings" issue? If so, then maybe the error is caused by corrupted system files. In this case, you can [repair corrupt Windows files with built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) like DISM and SFC.

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

## You've Successfully Restored Your Screen Saver Settings

 There’s no denying that changing your screen saver regularly makes your PC look cool. But then being unable to change the screen saver settings is uncool.

 If your screen saver settings are grayed out, then check out any of the methods we’ve covered. And once the problem is out of the way, be sure to start exploring some of the coolest, free Windows screensavers.

 Fortunately, we’ve got all the solutions you need. So, let’s dive in and check out the four ways to resolve this issue.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unlock-image-potential-10plus-lut-samples-some-at-zero-cost/"><u>[New] 2024 Approved  Unlock Image Potential  10+ LUT Samples, Some at Zero Cost</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expanding-minds-virtualizing-classrooms/"><u>[New] Expanding Minds, Virtualizing Classrooms</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-discovering-the-essence-of-excellent-screen-capture-with-recmeister/"><u>[Updated] 2024 Approved  Discovering the Essence of Excellent Screen Capture with Recmeister</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-easing-high-encoding-issues-in-obs/"><u>[Updated] 2024 Approved  Easing High Encoding Issues in OBS</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-maximizing-online-exposure-on-youtube-by-keeping-up-creative-commons-usage/"><u>[Updated] In 2024, Maximizing Online Exposure on YouTube by Keeping Up Creative Commons Usage</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-expert-tips-on-selecting-the-ideal-video-aspect-ratio/"><u>2024 Approved  Expert Tips on Selecting the Ideal Video Aspect Ratio</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-uncovering-the-best-apps-to-transform-your-speech/"><u>2024 Approved  Uncovering the Best Apps to Transform Your Speech</u></a></li>
<li><a href="https://win11.techidaily.com/7-personal-touches-for-windows-11s-search-engine/"><u>7 Personal Touches for Windows 11'S Search Engine</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-windows-11-customization-techniques/"><u>A Detailed Guide to Windows 11 Customization Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/bios-tips-combatting-the-problem-of-grayed-out-secure-boot-on-windows/"><u>BIOS Tips: Combatting the Problem of Grayed-Out Secure Boot on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/cant-find-copilot-on-windows-11-heres-what-to-do/"><u>Can't Find Copilot on Windows 11? Here's What To Do</u></a></li>
<li><a href="https://win11.techidaily.com/craft-your-own-secure-windows-pin-with-custom-patterns/"><u>Craft Your Own Secure Windows PIN with Custom Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-odbc-configuration-basics/"><u>Delving Into Windows ODBC Configuration Basics</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-empty-directory-faux-pas-in-windows-a-guide-to-error-x80070091/"><u>Demystifying the 'Empty Directory' Faux Pas in Windows - A Guide to Error X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-way-to-relaunch-printer-service/"><u>Efficient Way to Relaunch Printer Service</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-art-with-top-win-11-sketch-tools/"><u>Elevate Your Art with Top Win 11 Sketch Tools</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-task-tracker-update-rate-in-windows-11/"><u>Enhancing Live Task Tracker Update Rate in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-interface-with-fn-key-modifications/"><u>Enhancing User Interface with FN Key Modifications</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-for-enabling-win11-on-5ghz-networks-effortlessly/"><u>Essentials for Enabling Win11 on 5GHz Networks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-screen-hurdle-sonic-frontiers-win-on-w11/"><u>Fixing the Screen Hurdle: Sonic Frontiers Win on W11</u></a></li>
<li><a href="https://win11.techidaily.com/game-resurrection-applying-retroarchs-shaders-to-vintage-games/"><u>Game Resurrection: Applying RetroArch's Shaders to Vintage Games</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-windows-11-taskbar-avoid-the-search/"><u>Hiding Windows 11 Taskbar: Avoid the Search</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-grant-permission-on-hidden-outlook-files-and-directories/"><u>How to Grant Permission on Hidden Outlook Files and Directories</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-essential-elements-error-on-win11win11/"><u>How to Rectify Essential Elements Error on Win11/Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-oneplus-nord-n30-se-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change OnePlus Nord N30 SE IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/key-practices-in-the-pursuit-of-a-pristine-windows-setup/"><u>Key Practices in the Pursuit of a Pristine Windows Setup</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/mac-video-editor-reviews-the-best-of/"><u>Mac Video Editor Reviews The Best Of</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-store-repair-techniques-error-0x80073d26/"><u>Mastering Microsoft Store Repair Techniques: Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-entering-windows-11s-authentication-screen/"><u>Methods for Entering Windows 11'S Authentication Screen</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-fix-directx-file-downloads/"><u>Methods to Fix DirectX File Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-ftdibussys-why-it-compromises-windows-memory/"><u>Navigating ftdibus.sys: Why It Compromises Windows Memory</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-restrictions-disabling-signatures-adding-unsigned-drivers/"><u>Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-chrome-for-smooth-youtube-streaming/"><u>Optimizing Chrome for Smooth YouTube Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-global-communication-hotkeys-for-windows-language-switch/"><u>Optimizing Global Communication: Hotkeys for Windows Language SwitcH</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-limited-use-of-chatgpt-in-pc/"><u>Optimizing Limited Use of ChatGPT in PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-alt-code-not-responding-on-windows-pc/"><u>Overcoming ALT Code Not Responding on Windows PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/parrot-powered-prowess-a-fresh-lens-on-bebop-2/"><u>Parrot-Powered Prowess – A Fresh Lens on Bebop 2</u></a></li>
<li><a href="https://win11.techidaily.com/quick-resolution-for-windows-dism-failure-code-0x800f082f/"><u>Quick Resolution for Windows' DISM Failure Code: 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-with-ms-store-a-stepwise-approach-to-windows-pcs/"><u>Re-Engaging with MS Store: A Stepwise Approach to Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-inactive-recycle-bin-icon-on-win11/"><u>Rejuvenating Inactive Recycle Bin Icon on Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/streaming-social-feeds-on-your-smart-tv-whats-next-for-2024/"><u>Streaming Social Feeds on Your Smart TV  What's Next for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-nokia-105-classic-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Nokia 105 Classic Device</u></a></li>
<li><a href="https://win11.techidaily.com/the-power-and-essence-of-wintoys-an-uncomplicated-yet-comprehensive-explanation/"><u>The Power & Essence of 'WinToys': An Uncomplicated, Yet Comprehensive Explanation</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-bar-evolution-story-1985present/"><u>The Windows Bar Evolution Story (1985–Present)</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-driver-verifier-on-windows-11-pc/"><u>Triggering Driver Verifier on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-overclocked-cpus-for-gaming-users/"><u>Troubleshooting Overclocked CPUs for Gaming Users</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-global-scripts-a-windows-font-guide/"><u>Unleashing Global Scripts: A Windows Font Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-top-9-changes-in-win11-february-2023/"><u>Unveiling the Top 9 Changes in Win11 February 2023</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>