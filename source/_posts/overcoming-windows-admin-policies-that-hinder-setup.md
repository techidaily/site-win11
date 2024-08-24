---
title: Overcoming Windows Admin Policies That Hinder Setup
date: 2024-08-23T06:09:29.583Z
updated: 2024-08-24T06:09:29.583Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Admin Policies That Hinder Setup
excerpt: This Article Describes Overcoming Windows Admin Policies That Hinder Setup
keywords: WinAdminSetupPolicies,PolicyHindersWindowsSetup,OvercomeWindowsPolicy,DisableWindowsPolicies,WindowsSetupObstacles,ClearWinAdmPolicies,EliminatePolicyBarriers
thumbnail: https://thmb.techidaily.com/a7b063e2c5f1e938dc6e32e2ce85c52239dfc8e7739a5c0ead2c07ab91e735b6.png
---

## Overcoming Windows Admin Policies That Hinder Setup

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
6. Select **OK** to set the **DisableMSI** value.
7. Close Registry Editor and restart your PC.

## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-dancing-to-the-tune-youtubes-hottest-music-video-responses-23/"><u>[New] 2024 Approved  Dancing to the Tune  YouTube's Hottest Music Video Responses, '23</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-9-swift-solutions-for-boosting-your-tiktok-community-for-2024/"><u>[New] 9 Swift Solutions for Boosting Your TikTok Community for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-image-play-with-altering-tools/"><u>[New] Image Play with Altering Tools</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-expertise-guide-for-effective-text-overlays-on-images/"><u>[New] In 2024, Expertise Guide for Effective Text Overlays on Images</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-screenflow-demystified-essential-tools-for-your-mac-creation/"><u>[New] In 2024, ScreenFlow Demystified  Essential Tools for Your Mac Creation</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-step-by-step-creation-of-gamers-channel-graphics/"><u>[New] In 2024, Step-By-Step Creation of Gamers' Channel Graphics</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-triumph-through-film-the-top-10-motivating-titles/"><u>[New] Triumph Through Film  The Top 10 Motivating Titles</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-ultimate-scene-seizing-exploration/"><u>[Updated] 2024 Approved  Ultimate Scene Seizing Exploration</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-master-the-art-of-snaps-15-pro-tips-for-2024/"><u>[Updated] Master the Art of Snaps  15 Pro Tips for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-quick-guide-to-mp3-from-instagram-videos/"><u>[Updated] Quick Guide to MP3 From Instagram Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-quick-guide-to-instagrams-magnification-magic-for-2024/"><u>[Updated] The Quick Guide to Instagram's Magnification Magic for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-unleashing-instagram-success-through-precision-metrics-monitoring/"><u>[Updated] Unleashing Instagram Success Through Precision Metrics Monitoring</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unleashing-creativity-with-mobile-melodies-on-iphone/"><u>2024 Approved  Unleashing Creativity with Mobile Melodies on iPhone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/crafting-your-perfect-minecraft-shelter-for-2024/"><u>Crafting Your Perfect Minecraft Shelter for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-iphone-13-pro-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-uninstall-process-away-with-wsl-on-windows-11/"><u>Detailed Uninstall Process: Away with WSL on Windows 11</u></a></li>
<li><a href="https://media-tips.techidaily.com/easy-tips-and-tricks-transforming-flv-video-into-iphone-friendly-formats/"><u>Easy Tips & Tricks: Transforming FLV Video Into iPhone-Friendly Formats</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-woe-of-windows-11-and-geforce-nows-xc0f1103f/"><u>Eliminating the Woe of Windows 11 & GeForce Now’s Xc0f1103f</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-1011-search-visibility-and-functionality/"><u>Enhancing Windows 10/11 Search Visibility & Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-windows-11-with-dolby-atmos-experience/"><u>Enriching Windows 11 with Dolby Atmos Experience</u></a></li>
<li><a href="https://win11.techidaily.com/fourfold-path-to-program-peace-in-windows/"><u>Fourfold Path to Program Peace in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-separate-to-linked-coordinating-files-between-two-computers-with-aoemi/"><u>From Separate to Linked: Coordinating Files Between Two Computers with AOEMi</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-free-up-iphone-xr-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up iPhone XR Space | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-windows-media-player-for-easy-access/"><u>How to Open Windows Media Player for Easy Access</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-windows-11s-isdonedll-complications/"><u>How to Repair Windows 11'S ISDone.dll Complications</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-xiaomi-redmi-k70e-easily-by-drfone-android/"><u>How To Unlock a Xiaomi Redmi K70E Easily?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-windows-hello-biometric-lock-in-windows-11/"><u>How to Utilize Windows Hello Biometric Lock in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-masterclass-in-visual-updates-igtv-cover-photos/"><u>In 2024, Masterclass in Visual Updates  IGTV Cover Photos</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-skyrim-script-extender-not-working-on-windows-how-to-fix-it/"><u>Is the Skyrim Script Extender Not Working on Windows? How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-system-efficiency-through-cpu-settings/"><u>Maximizing System Efficiency Through CPU Settings</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-android-latest-tips-for-immersive-360-content/"><u>Navigating Android  Latest Tips for Immersive 360 Content</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-windows-10-black-screen-with-simple-fixes/"><u>Overcome Windows 10 Black Screen with Simple Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-access-denied-on-windows-11-essential-fixes-listed/"><u>Overcoming Access Denied On Windows 11: Essential Fixes Listed</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-access-issues-with-roblox-for-windows-users/"><u>Overcoming Access Issues with Roblox for WINDOWS Users</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-failure-windows-error-0x8007045d/"><u>Overcoming System Failure - Windows Error 0X8007045D</u></a></li>
<li><a href="https://win11.techidaily.com/project-proficiency-through-keyboard-kudos/"><u>Project Proficiency Through Keyboard Kudos</u></a></li>
<li><a href="https://win11.techidaily.com/quick-free-note-taking-tricks-for-windows-users/"><u>Quick, Free Note Taking Tricks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-chrome-download-issues-in-the-windows-environment/"><u>Remedying Chrome Download Issues in the Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-path-errors-on-windows-810-systems/"><u>Remedying PATH Errors on Windows 8/10 Systems</u></a></li>
<li><a href="https://data-wizards.techidaily.com/resolve-movie-irregularities-a-simple-self-help-article-on-fixing-unstable-videos/"><u>Resolve Movie Irregularities: A Simple Self-Help Article on Fixing Unstable Videos</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-login-adjusting-the-reset-lockout-frequency-post-attempts-win-11-edition/"><u>Securing Your Login: Adjusting the Reset Lockout Frequency Post-Attempts, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-selecthighlight-problems-in-windows-pdfs/"><u>Solutions for Select/Highlight Problems in Windows PDFs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-keyboard-malfunctions-a-guide-for-windows-11-7-and-8-users/"><u>Solving Keyboard Malfunctions: A Guide for Windows 11, 7, and 8 Users</u></a></li>
<li><a href="https://win11.techidaily.com/solving-proc-call-not-successful-issues-with-malwarebytes-in-windows-1110/"><u>Solving Proc Call Not Successful Issues with Malwarebytes in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-prevent-csgo-launch-issues-on-windows-11/"><u>Strategies to Prevent CS:GO Launch Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-online-journey-with-gesture-controls-in-ms-edge-win-11-edition/"><u>Streamline Your Online Journey with Gesture Controls in MS Edge, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-upgrade-malfunction-fixing-windows-update-error-0x80246007/"><u>Swift Solution to Upgrade Malfunction: Fixing Windows Update Error 0X80246007</u></a></li>
<li><a href="https://screen-capture.techidaily.com/top-strategies-capturing-saving-and-sharing-ps4-experiences/"><u>Top Strategies  Capturing, Saving & Sharing PS4 Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharging-android-dev-tools-speed-boost-for-windows-users/"><u>Turbocharging Android Dev Tools: Speed Boost for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-guide-steps-to-successfully-install-the-asus-wireless-network-drivers/"><u>Ultimate Guide: Steps to Successfully Install the ASUS Wireless Network Drivers</u></a></li>
<li><a href="https://program-issues.techidaily.com/untangling-the-mystery-of-freezing-falls-in-fallout-3-for-windows-users/"><u>Untangling the Mystery of Freezing Falls in Fallout 3 for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-netstat-function-for-network-surveillance/"><u>Unveiling Windows 11'S Netstat Function for Network Surveillance</u></a></li>
<li><a href="https://win11.techidaily.com/windows-networks-decoded-arp-cache-understanding/"><u>Windows Networks Decoded: ARP Cache Understanding</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-for-rectifying-fall-guys-connection-woes-in-windows/"><u>Winning Strategies for Rectifying Fall Guys Connection Woes in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>