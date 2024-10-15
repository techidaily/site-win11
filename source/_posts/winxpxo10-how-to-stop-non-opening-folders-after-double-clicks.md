---
title: WinXP/XO10 - How to Stop Non-Opening Folders After Double-Clicks
date: 2024-10-09T17:07:39.992Z
updated: 2024-10-15T19:34:23.031Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes WinXP/XO10 - How to Stop Non-Opening Folders After Double-Clicks
excerpt: This Article Describes WinXP/XO10 - How to Stop Non-Opening Folders After Double-Clicks
keywords: XP Windows Security Fix,Fix Folder Not Open,Stop Double Click Error,XO10 Safe Browsing,Non-Opening Folders Guide,Secure XP for XO10,XP Explorer Safety Tips
thumbnail: https://thmb.techidaily.com/6cebc56dc292975b98a5a871193af627ed43dff4753b2894db168c37d5d2f38f.png
---

## WinXP/XO10 - How to Stop Non-Opening Folders After Double-Clicks

 Some users have posted on help chat forums about folders not opening when they double-click them in Windows File Explorer. This means users can’t access folders by double-clicking on directories. There isn’t a specific error message associated with this issue.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Adjust File Explorer Options

 File Explorer has alternative single-click and double-click options for opening items. If single-click is set, double-clicking folders won’t open them. Try single-clicking a folder to see if that works. If it does, then you probably need to select the **Double-click to open an item** option like this:

1. Right-click on your taskbar’s **Start** button to select a **Search** shortcut.
2. Type "File Explorer options" to find a matching search result.
3. Click **File Explorer Options** to bring up the window with that title.
4. Select the **Double-click to open an item** radio button.  
![The Double-click to open an item option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-to-open-an-item-option.jpg)
5. Click the **Apply** button for saving settings.
6. Select **OK** to close the File Explorer Options window.

 If you find the **Double-click to open item** option is already selected, you could try selecting the single-click setting instead. That way, you might at least be able to access your folders by single-clicking them. Or, proceed with applying the other resolutions below.

## 2\. Adjust the Double-Click Mouse Speed

 The mouse **Double-click speed** setting can feasibly cause this issue if it’s set too fast. So, you might need to lower that setting a little bit. This is how you can adjust the mouse double-click speed:

1. First, bring up the tool for finding files with the **Windows** key + **S** hotkey that opens it.
2. Type the "mouse settings" keyword phrase.
3. Click **Mouse settings** to open a Settings window.
4. Next, click the **Additional mouse** options in Settings.  
![The Additional mouse settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/additional-mouse-settings.jpg)
5. Drag the **Double-click speed** bar’s slider left to slow it down.  
![The Double-click speed setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-speed-setting.jpg)
6. Select **Apply** and click **OK** to set the new double-click speed.

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The required double-click speed for opening folders will now be slower than before. So, you won’t need to double-click so quickly.

## 3\. Scan and Repair Windows System Files

 Microsoft advises users to run system file scans when Windows functions aren’t working right. In this case, there’s an issue with the folders’ double-click functionality.

 So, [run a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to see if Windows Resource Protection detects any corrupted system files. If so, Windows Resource Protection will probably also repair the files detected, which could fix the double-clicking of folders not opening.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Edit the Shell Registry Key

 Quite a few users have confirmed editing the **shell** registry key can fix the double-clicking of folders not working in Windows 11/10\. Those users changed that key’s **(Default)** string value to fix the issue. These are the steps for editing the **shell** key:

1. Press the **Windows** logo keyboard key + **R** to start Run.
2. Input a **regedit** (Registry Editor) Run command inside the **Open** box and select **OK**.
3. Bring up the shell key by inputting this path inside the registry address box:  
`Computer\HKEY_CLASSES_ROOT\Directory\shell`
4. Double-click **(Default)** inside the **shell** key.  
![The shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-shell-key.jpg)
5. If the **Value data** box is empty, or set differently, input **none** there as in the snapshot directly below.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The (Default) string value for the shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-default-string-value.jpg)
6. Click **OK** to save the new **(Default)** string value.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You might need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for this registry tweak to take effect. Alternatively, restart Windows and then try double-clicking a folder to see if it opens.

## 5\. Edit the Mouse Registry Key

 Double-click issues can arise when string values for the **Mouse** registry key have been altered from their default settings (typically by third-party apps). To be more specific, **MouseHoverWidth**, **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** are four **Mouse** key strings you might need to restore to default values for to fix this issue.

 To do so, edit the **Mouse** registry key like this:

1. Bring up Registry Editor as instructed for the first two steps of the previous potential solution.
2. Next, go to the **Mouse** key by entering this path within Registry Editor’s address bar:  
`Computer\HKEY_CURRENT_USER\Control Panel\Mouse`
3. Double-click the **MouseHoverWidth** string.  
![The Mouse key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/mouse-key.jpg)
4. If set any differently, input **4** inside the **Value data** box and select **OK**.  
![The MouseHoverWidth string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-mousehoverwidth-string-value.jpg)
5. Repeat the previous two steps for the **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** strings in the **Mouse** key. Set their values to **4**, just like you did for the **MouseHoverWidth**string.

 When you’ve finished adjusting those string values, exit the Registry Editor and restart your PC. If you find all those strings are already set to four, you don’t need to change them.

## 6\. Turn Off Controlled Folder Access

 Some users have said they fixed the double-clicking of folders not working by turning off controlled folder access. Controlled folder access is the Windows Security feature that blocks unauthorized apps from modifying contents inside protected directories. Thus, enabling that feature restricts folder access.

 So, try turning off controlled folder access like this:

1. Open Windows Security by double-clicking the small shield icon inside the system tray area of your taskbar.
2. Click **Virus & threat protection** in Windows Security’s left navigation sidebar.  
![The tab sidebar in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-security-s-tab-sidebar.jpg)
3. Scroll down a little and click on **Manage ransomware protection**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/manage-ransomware-protection.jpg)
4. Click the **Controlled folder access** toggle switch to turn off that setting.  
![The Controlled folder access setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/controlled-folder-access-setting.jpg)

 Then, go into File Explorer and try opening some folders again to see if disabling that security feature makes a difference. If it does, then it’s probably best to leave controlled folder access off.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Revert Windows to a Restore Point

 Rolling Windows back to a saved restoration point is one of the last things to try if no other potential fixes for this issue work. Applying this potential fix will undo system changes made and remove software installed after your chosen restore point date.

 However, it’s only worth reverting Windows if you can select a restore point that will roll back the OS to a time when you could open folders by double-clicking them.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-system-restore-tool.jpg)

 To apply this potential fix, check out our guide on [utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/). The System Restore tool will need to be enabled for you to select a restoration point. Be prepared to reinstall software packages a selected restore point deletes, which you can check by clicking **Scan for affected programs** in System Restore.

## Make Double-Clicking Open Folders on Windows Again

 Those potential fixes for double-clicking folders not working will probably resolve that Windows 11/10 issue in most cases. We can’t promise they’re guaranteed, but lots of users have confirmed some of them work.

 Beyond those possible resolutions, you might have to try something more drastic, like a full system reset or in-place Windows upgrade.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-ace-the-art-of-altering-and-amplifying-vhs-photos-on-computers/"><u>[New] 2024 Approved Ace the Art of Altering and Amplifying VHS Photos on Computers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-crafting-visual-narratives-with-the-leading-frames/"><u>[New] Crafting Visual Narratives with the Leading Frames</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-comprehensive-guide-to-io-screen-capture-capabilities/"><u>[Updated] Comprehensive Guide to IO Screen Capture Capabilities</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-advice-on-acquiring-royalty-free-high-quality-graphics/"><u>[Updated] Expert Advice on Acquiring Royalty-Free, High-Quality Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/1726028360556-7/"><u>「最適なビデオ寸法変更サイト・上位7推奨」</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44km44kn44ow44ox44os44k844oz44og44o844k344on44oz44gu44gf44kb44gr44k544op44kk44oj44k344on44o844ot44oh44kq44ks5yq55p6c55qe44gr57eo6zug44gz44kl5oqa6kgt44cn1/"><u>「ウェブプレゼンテーションのためにスライドショービデオを効果的に編集する技術」</u></a></li>
<li><a href="https://win11.techidaily.com/1726026337234-dvd/"><u>最適なレンタルDVDコピーツール選び - 使い勝手とセキュリティの両立!</u></a></li>
<li><a href="https://win11.techidaily.com/1726028106781-dvd/"><u>DVDの正常再生を保証する!理解しやすく簡単に修復する方法</u></a></li>
<li><a href="https://win11.techidaily.com/1726026382879-gif/"><u>GIFアニメ画質向上:高解像度への改良手順</u></a></li>
<li><a href="https://techtrends.techidaily.com/gpu-beschleunigte-videokonvertierung-mit-winxvideo-ai-schnelle-und-zuverlassige-audiovideo-konvertierungssoftware/"><u>GPU-Beschleunigte Videokonvertierung Mit Winxvideo AI: Schnelle Und Zuverlässige Audio/Video-Konvertierungssoftware</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-8-plus-drfone-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-vivo-s17e-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Vivo S17e? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-proven-pathways-to-peeling-away-pesky-backdrops-with-affinity-photo-tools/"><u>In 2024, Proven Pathways to Peeling Away Pesky Backdrops with Affinity Photo Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/intermittent-video-playback-fix-and-resolve-issues/"><u>Intermittent Video Playback - Fix & Resolve Issues</u></a></li>
<li><a href="https://win11.techidaily.com/1726029205926-iphone/"><u>IPhoneにおける「読み込めない動画エラー」を克服する方法</u></a></li>
<li><a href="https://win11.techidaily.com/1726028985392-mp3/"><u>MP3音量比率変更ツールをご利用いただける場所と使い方ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/1726027369163-pcdvd/"><u>PCで安全にDVDのデータをバックアップする手順ガイド</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/revamp-your-display-a-tutorial-on-how-to-install-the-latest-ati-drivers-for-windows-pcs/"><u>Revamp Your Display: A Tutorial on How to Install the Latest ATI Drivers for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/1726026492605-gif/"><u>ダイナミックなGIFウェルカムバナー作成の基礎知識</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    