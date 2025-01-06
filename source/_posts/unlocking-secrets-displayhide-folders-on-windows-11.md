---
title: "Unlocking Secrets: Display/Hide Folders on Windows 11"
date: 2024-12-31T17:50:38.432Z
updated: 2025-01-06T18:42:10.241Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Secrets: Display/Hide Folders on Windows 11"
excerpt: "This Article Describes Unlocking Secrets: Display/Hide Folders on Windows 11"
keywords: Win11 Folder Management,Hide Windows Files,Show Hidden Content,XP/Vista Comparison,Secure File Hiding,Windows Privacy Settings,Advanced Explorer Tweaks
thumbnail: https://thmb.techidaily.com/3da56b4dd62c9d29faa422fa86eb533c5fdaa7995cd6fe5de9f6ecf749c3b6f7.jpg
---

## Unlocking Secrets: Display/Hide Folders on Windows 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-building-an-affluent-future-with-instagram-know-how/"><u>[New] In 2024, Building an Affluent Future with Instagram Know-How</u></a></li>
<li><a href="https://youtube-web.techidaily.com/op-17-light-and-gear-perfect-for-vloggers-for-2024/"><u>[New] Top 17 Light & Gear Perfect for Vloggers for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-brand-battlegrounds-mastery-of-marketing-metrics-on-youtube/"><u>[Updated] In 2024, Brand Battlegrounds Mastery of Marketing Metrics on YouTube</u></a></li>
<li><a href="https://discover-community.techidaily.com/codec-h265-video-le-plus-performant-encodeur-pour-windows-et-mac-convertisseur/"><u>Codec H.265 Vidéo - Le Plus Performant Encodeur Pour Windows Et Mac Convertisseur</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-to-monitor-kids-internet-use/"><u>Configuring Windows 11 to Monitor Kids' Internet Use</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/expert-advice-on-the-newest-iphone-15-unmatched-performance-that-attracts-both-novices-and-pro-enthusiasts-zdnet-review/"><u>Expert Advice on the Newest iPhone 15: Unmatched Performance That Attracts Both Novices and 'Pro' Enthusiasts | ZDNET Review</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-eliminating-wow-crashes-on-pc/"><u>Expert Tips for Eliminating WoW Crashes on PC</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-dodge-windows-11s-protective-shield/"><u>Expert Tips: Dodge Windows 11'S Protective Shield</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restarting-unresponsive-spotify-windows-11/"><u>Guidelines for Restarting Unresponsive Spotify Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-camon-30-pro-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Camon 30 Pro 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-short-form-media-exploration/"><u>In 2024, Short Form Media Exploration</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-list-of-leading-real-time-tv-streamers-compared/"><u>In 2024, Ultimate List of Leading Real-Time TV Streamers Compared</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-5-replacements-for-windows-snipping-capability-in-other-oses/"><u>The Top 5 Replacements for Windows' Snipping Capability in Other OSes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-protectors-for-the-newest-iphones-iphone-16-and-pro-your-ultimate-buying-guide-featuring-extensive-reviews-by-tech-experts-zdnet/"><u>Top-Rated Protectors for the Newest iPhones (iPhone 16 & Pro) - Your Ultimate Buying Guide, Featuring Extensive Reviews by Tech Experts | ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-potential-via-admin-terminal-immediate-launch/"><u>Unleash Full Potential via Admin Terminal Immediate Launch</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-exepe-formats/"><u>Unveiling the Secrets of Windows EXE/PE Formats</u></a></li>
</ul></div>

