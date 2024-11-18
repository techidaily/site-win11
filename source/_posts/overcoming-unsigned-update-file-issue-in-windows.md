---
title: Overcoming Unsigned Update File Issue in Windows
date: 2024-11-15T22:00:32.032Z
updated: 2024-11-18T00:47:08.101Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Unsigned Update File Issue in Windows
excerpt: This Article Describes Overcoming Unsigned Update File Issue in Windows
keywords: Fixing Update Files in Win,Troubleshoot Update Errors,Resolve Win Updates Failure,Remedy Unsigned File Woes,Correct Update Install Issue,Windows Update Correction Tips,Address Windows Updater Glitch
thumbnail: https://thmb.techidaily.com/1f277a1e71fd10df1b01699e57758c33c523b120ed3c32dedf0e24f515c80068.png
---

## Overcoming Unsigned Update File Issue in Windows

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484940/16446" target="_top" id="1484940">
  <img src="//a.impactradius-go.com/display-ad/16446-1484940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484940/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-how-to-make-money-from-youtube-shorts-requirements-and-earning-potential/"><u>[Updated] In 2024, How to Make Money From YouTube Shorts Requirements and Earning Potential</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-secret-sound-scribes-hidden-audio-logging-for-mobile-devices/"><u>2024 Approved Secret Sound Scribes Hidden Audio Logging for Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://win-web.techidaily.com/comment-sauvegardez-votre-systeme-windows-10-avec-une-cle-usb-a-laide-du-plus-puissant-logiciel-de-securite-economique/"><u>Comment Sauvegardez Votre Système Windows 10 Avec Une Clé USB À L'aide Du Plus Puissant Logiciel De Sécurité Économique</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-windows-control-with-administrator-rights/"><u>Conquering Windows Control with Administrator Rights</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-windows-alt-key-errors-48-characters/"><u>Diagnosing Windows Alt Key Errors (48 Characters)</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-samsung-galaxy-f15-5g-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Samsung Galaxy F15 5G Phone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-elevating-tiktok-bio-by-merging-it-with-linktree/"><u>In 2024, Elevating TikTok Bio by Merging It With Linktree</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-guide-for-efficient-note-placement-in-win11win10/"><u>Quick-Start Guide for Efficient Note Placement in Win11/Win10</u></a></li>
<li><a href="https://screen-capture.techidaily.com/skype-capture-methods-seamless-transition-between-oses/"><u>Skype Capture Methods Seamless Transition Between OSes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Motorola Edge 40? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-tutorial-on-how-to-unlink-gadgets-from-your-google-nest-hub/"><u>The Ultimate Tutorial on How to Unlink Gadgets From Your Google Nest Hub</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    