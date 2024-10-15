---
title: Uncover Concealed Files and Folders in Windows 11 UI
date: 2024-10-10T22:38:12.262Z
updated: 2024-10-15T21:13:37.167Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uncover Concealed Files and Folders in Windows 11 UI
excerpt: This Article Describes Uncover Concealed Files and Folders in Windows 11 UI
keywords: Hide Files Finder,Windows File Exposure,XPesy Utility Search,Folder Reveal Tool,Secret File Locator,UI Hidden Content Discoverer,Windows 11 Files Uncovered
thumbnail: https://thmb.techidaily.com/280ddac45a43e26292eec3f07f23cb423510585b526fcae65189b9637edf5522.jpg
---

## Uncover Concealed Files and Folders in Windows 11 UI

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-create-fantastic-youtube-description-with-templates-to-get-more-viewers/"><u>[New] In 2024, Create Fantastic YouTube Description With Templates To Get More Viewers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/iberate-content-consumption-with-these-leading-free-and-on-demand-tools-for-2024/"><u>[New] Liberate Content Consumption with These Leading Free & On-Demand Tools for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-saving-skies-best-price-for-data-keepers-2024/"><u>[New] Saving Skies Best Price for Data Keepers 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-professional-looking-shots-at-home-top-5-must-try-tips/"><u>[Updated] 2024 Approved Professional-Looking Shots at Home – Top 5 Must-Try Tips</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-streamlining-video-conferencing-on-chrome-os/"><u>[Updated] In 2024, Streamlining Video Conferencing on Chrome OS</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-savefromnet-safety-and-key-insights-for-secure-downloading/"><u>Evaluating SaveFrom.Net: Safety and Key Insights for Secure Downloading</u></a></li>
<li><a href="https://win11.techidaily.com/free-methods-to-transfer-your-dvd-collection-onto-your-huawei-device-a-comprehensive-guide/"><u>Free Methods to Transfer Your DVD Collection Onto Your Huawei Device: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-converting-your-media-files-for-optimal-playback-on-sony-bravia-televisions/"><u>Guide to Converting Your Media Files for Optimal Playback on Sony Bravia Televisions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-any-song-you-love-as-a-personalized-ringtone-free-tutorial/"><u>How to Get Any Song You Love as a Personalized Ringtone - Free Tutorial!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-securely-get-your-favorite-worldstarhiphop-content-online/"><u>How to Securely Get Your Favorite WorldStarHipHop Content Online</u></a></li>
<li><a href="https://win11.techidaily.com/itunesyoutube/"><u>ITunes上で動画サイトからYouTube音楽を取り込む手順</u></a></li>
<li><a href="https://win11.techidaily.com/pcmp4/"><u>PC画面収録をMP4形式でどうやってキャプチャするか解説</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/snag-a-bargain-premium-apple-watch-offers-for-month-limited-time/"><u>Snag a Bargain: Premium Apple Watch Offers for [Month] – Limited Time</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/universal-unlock-pattern-for-oneplus-nord-n30-5g-by-drfone-android/"><u>Universal Unlock Pattern for OnePlus Nord N30 5G</u></a></li>
<li><a href="https://fox-helps.techidaily.com/xsplit-exclusive-direct-split-insight-for-2024/"><u>XSplit Exclusive Direct Split Insight for 2024</u></a></li>
</ul></div>

