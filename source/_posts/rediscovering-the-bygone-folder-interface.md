---
title: Rediscovering the Bygone Folder Interface
date: 2024-09-05T08:29:19.643Z
updated: 2024-09-06T08:29:19.643Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rediscovering the Bygone Folder Interface
excerpt: This Article Describes Rediscovering the Bygone Folder Interface
keywords: Old File Explorer,Classic Folders,Retro UI Design,Vintage File Management,Nostalgic Filespace,Historical Folder View,Antique System Interface
thumbnail: https://thmb.techidaily.com/3c65f68799b4050edde66f042974df77982abdb35ad2689534997125a364839c.jpg
---

## Rediscovering the Bygone Folder Interface

 Microsoft redesigned File Explorer’s user interface for Windows 11\. Windows 11’s File Explorer has a command bar on which you can select options. That bar replaces the tabbed ribbon interface from Windows 10’s File Explorer.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Press the Up Button in the Control Panel

 File Explorer is accessible from the Control Panel. Furthermore, Explorer will still have the old, ribbon interface from Windows 10 when you open it from there. You can access the classic File Explorer in Windows 11 by clicking the up button in the Control Panel as follows:

1. Press the **Windows + S** key combination to access Windows 11’s search box.
2. Input **Control Panel** and select to open the matching search result.
3. If the Control Panel opens in an icon view, click the **View by** drop-down menu and select **Category**.  
![The View by menu in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/view-by-menu.jpg)
4. Then click the **Up to “Desktop”** button (up arrow) button on the Control Panel’s navigation bar. Alternatively, press the **Alt + Up arrow key** keyboard shortcut.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Up to Desktop button in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/up-button.jpg)

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now you’ll see the classic File Explorer from Windows 10 that incorporates a tab bar. You’ll always need to open the Control Panel first to access classic File Explorer through it. So, consider [setting up a Control Panel shortcut](https://www.makeuseof.com/windows-11-set-up-control-panel-shortcuts/) in Windows 11 to give you more direct access.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Manually Edit the Registry

 Users utilizing Windows 11 21H2 or earlier versions can restore the classic File Explorer ribbon by manually tweaking the registry. However, the same registry tweak will not work in Windows 11 22H2 or later builds. This is how you can restore the classic File Explorer ribbon interface by manually editing the registry:

1. Open Windows 11’s Registry Editor app. Our guide to [opening Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods for launching that app.
2. Go to the **ShellExtensions** key by inputting this location in the Registry Editor’s address bar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\`
3. If you can’t see a **Blocked** subkey, right-click ShellExtensions and select New and Key. You can skip through to step five if you can already see a Blocked key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-option.jpg)
4. Input **Blocked** to create that key.
5. Right-click the **Blocked** key and select **New** \> **String Value**.
6. Input **{e2bf9676-5f8f-435c-97eb-11607a5bedf7**} in the new string’s text box. You can copy and paste that string name in by selecting its text, pressing **Ctrl** \+ **C**, and then pressing **Ctrl** \+ **V**.  
![The string value for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-string-value.jpg)
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
3. You can bring back the command bar by executing this command:  
`reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f`

 This method is somewhat more straightforward than manually editing the registry. The first command adds the **{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}** string value. Entering the second command deletes that string, which restores Explorer’s default command bar.

 If the command for restoring classic File Explorer doesn’t work when you execute it, there might be spaces at the end of it. Make sure there aren’t any extra spaces included at the end of the command before executing.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Restore Explorer’s Classic Ribbon UI With ExplorerPatcher

 You can still restore Explorer’s ribbon interface in Windows 11 22H2 and all other build versions with ExplorerPatcher. ExplorerPatcher is freeware software that enables you to customize Windows 11’s Start menu, taskbar, File Explorer, and system tray. It includes many options for [making Windows 11 look more like Windows 10](https://www.makeuseof.com/windows-11-look-like-windows-10-explorerpatcher/).

 This is how you can restore tabs in Windows 11’s File Explorer with ExplorerPatcher.

1. Open this [ExplorerPatcher Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Explorer-Patcher-for-Windows-11.shtml) and download the file.
2. Double-click the **ep\_setup** file to install Explorer Patcher.
3. Activate the Power User menu by right-clicking the **Start** taskbar button to select **Search**.
4. Enter **ExplorerPatcher** in the Windows 11 search box and click **Properties (ExplorerPatcher)**.
5. Click the **File Explorer** tab in ExplorerPatcher.
6. Next, click the **Control interface** option to select **Windows 10 Ribbon**.  
![The Windows 10 Ribbon option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-10-ribbon.jpg)
7. Click **Restart File Explorer** on the Properties window.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-choosing-the-right-recorder-top-4-full-screen-picks-for-pcmac-for-2024/"><u>[New] Choosing the Right Recorder  Top 4 Full-Screen Picks for PC/Mac for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-capturing-discords-magic-3-steps-for-ensuring-your-live-stream-stays-alive/"><u>[New] In 2024, Capturing Discord's Magic  3 Steps for Ensuring Your Live Stream Stays Alive</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-igtv-gurus-you-cant-miss/"><u>[New] Top IGTV Gurus You Can't Miss</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-clear-up-fb-message-misrepresentation/"><u>[Updated] Clear Up FB Message Misrepresentation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-recruitment-powerhouses-top-ten-shorts/"><u>[Updated] Recruitment Powerhouses - Top Ten Shorts</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-peak-performance-cameras-for-athleticism/"><u>2024 Approved  Peak Performance Cameras for Athleticism</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-the-art-of-audible-alteration-a-journey-through-cost-free-audio-effects-software/"><u>2024 Approved  The Art of Audible Alteration  A Journey Through Cost-Free Audio Effects Software</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/9-reasons-you-should-upgrade-to-chatgpt-plus/"><u>9 Reasons You Should Upgrade to ChatGPT Plus</u></a></li>
<li><a href="https://win11.techidaily.com/cut-the-cost-boost-quality-wins-finest-players/"><u>Cut the Cost, Boost Quality: Win's Finest Players</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-common-issues-in-windows-camera/"><u>Decoding and Fixing Common Issues in Windows Camera</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-intricacies-of-windows-automated-repair/"><u>Decoding the Intricacies of Windows’ Automated Repair</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-no-more-files-notifications-on-win-11/"><u>Disabling 'No More Files' Notifications on Win 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/diy-tech-how-to-get-and-setup-llama-2-for-personal-use-at-home/"><u>DIY Tech: How to Get and Setup Llama 2 for Personal Use at Home</u></a></li>
<li><a href="https://win11.techidaily.com/double-the-fun-with-a-swifter-mouse-click-process/"><u>Double the Fun with a Swifter Mouse Click Process</u></a></li>
<li><a href="https://win11.techidaily.com/five-superior-tools-excluding-the-standard-windows-snipper/"><u>Five Superior Tools Excluding the Standard Windows Snipper</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-application-couldnt-start-0xc000003e-hexadecimal-error/"><u>Fixing The Application Couldn't Start 0xC000003E Hexadecimal Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-the-windows-11-login-method-from-pin-to-password/"><u>How to Change the Windows 11 Login Method From PIN to Password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-obs-studio-error-windows-edition-strategy/"><u>How to Eliminate OBS Studio Error: Windows Edition Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-not-enough-usb-controller-resources-error-on-a-windows-computer/"><u>How to Fix “Not Enough USB Controller Resources” Error on a Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-msstore-crash-with-error-code-0x0-on-windows-1011/"><u>How to Overcome MsStore Crash with Error Code 0X0 on Windows 10/11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-magic-6-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor Magic 6 Pro to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-drawers-for-win-11-a-comprerancial-guide-to-best-apps/"><u>Ideal Drawers for Win 11: A Comprerancial Guide to Best Apps</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-countermeasures-to-address-winoffice-operational-failure/"><u>Immediate Countermeasures to Address WinOffice Operational Failure</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-adding-frames-to-instagram-videos-3-procedures/"><u>In 2024, Adding Frames to Instagram Videos - 3 Procedures</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-poco-m6-pro-5g-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your Poco M6 Pro 5G Device</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-revolutionary-ai-for-artistic-photography/"><u>In 2024, Revolutionary AI for Artistic Photography</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/increasing-click-rates-and-revenue-the-power-of-engaging-fb-animation-ads/"><u>Increasing Click Rates & Revenue  The Power of Engaging FB Animation Ads</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/lexical-limits-earths-extended-expressions/"><u>Lexical Limits: Earth's Extended Expressions</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-conquer-windows-os-errors/"><u>Master Plan to Conquer Windows OS Errors</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-adjusting-windows-11-device-usage/"><u>Maximizing Efficiency: Adjusting Windows 11 Device Usage</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-your-drive-space-a-disc-usage-command-breakdown/"><u>Navigating Through Your Drive Space: A Disc Usage Command Breakdown</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-beam-local-content-to-chromecast-easy-setup-for-windows-mac-android-and-ios-users/"><u>New In 2024, Beam Local Content to Chromecast Easy Setup for Windows, Mac, Android, and iOS Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/next-morning-analysis-fresh-insights/"><u>Next Morning Analysis  Fresh Insights</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-retro-clips-using-madvr-software-for-pcs/"><u>Optimize Retro Clips Using MadVR Software for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unsuccessful-share-attempts-in-nvidias-experience/"><u>Overcoming Unsuccessful Share Attempts in NVIDIA's Experience</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insight-are-you-ready-for-windows-11/"><u>Quick Insight: Are You Ready for Windows 11?</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-nvidia-connectivity-flaws/"><u>Resolving Windows 10/11 NVIDIA Connectivity Flaws</u></a></li>
<li><a href="https://win11.techidaily.com/shielding-windows-default-screen-display-from-user-changes/"><u>Shielding Windows Default Screen Display From User Changes</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-approach-to-fix-windows-charmap-woes/"><u>Streamlining Your Approach to Fix Windows CharMap Woes</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-for-winerror-0x80072746-in-microsoft-mail/"><u>Swift Solution for WinError 0X80072746 in Microsoft Mail</u></a></li>
<li><a href="https://win11.techidaily.com/switch-your-windows-11-preferred-apps/"><u>Switch Your Windows 11 Preferred Apps</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-technology-today-a-new-windows-era/"><u>Tomorrow's Technology Today: A New Windows Era</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-4-tools-for-sharing-and-exporting-your-conversations-with-chatgpt/"><u>Top 4 Tools for Sharing & Exporting Your Conversations with ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/total-methodology-for-disabling-windows-subsystem-for-linux/"><u>Total Methodology for Disabling Windows Subsystem for Linux</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-unwanted-background-workers-windows-pc/"><u>Trimming Unwanted Background Workers Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-file-share-problems-with-geforce-experience/"><u>Troubleshooting File-Share Problems with GeForce Experience</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-11-interface-elements/"><u>Understanding Windows 11 Interface Elements</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unveiling-ipads-full-potential-a-timelapse-journey-begins-here-for-2024/"><u>Unveiling iPad's Full Potential  A Timelapse Journey Begins Here for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>