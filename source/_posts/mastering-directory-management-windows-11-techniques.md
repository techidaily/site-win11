---
title: "Mastering Directory Management: Windows 11 Techniques"
date: 2025-01-12T19:07:03.763Z
updated: 2025-01-18T22:06:30.032Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Directory Management: Windows 11 Techniques"
excerpt: "This Article Describes Mastering Directory Management: Windows 11 Techniques"
keywords: Win11 DirMgmt Skills,Windows 11 Organizational Tactics,Advanced Windows 11 DIR,Proficient Windows 11 Directory Management,Efficient Windows 11 Directory Strategies,Mastering 11-Dir Techniques,Optimizing Win11 Dir Usage
thumbnail: https://thmb.techidaily.com/0994f11e3b98aa050445b83a923c27f3f286a1f5302c7ff78d5008912b4d02f9.jpg
---

## Mastering Directory Management: Windows 11 Techniques

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-analyzing-view-count-to-cash-out-on-youtube/"><u>[Updated] In 2024, Analyzing View Count to Cash Out on YouTube</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-aural-tapestry-weaving-sounds-into-cinematic-threads/"><u>[Updated] In 2024, Aural Tapestry Weaving Sounds Into Cinematic Threads</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-efficient-audio-documentation-in-academia-using-macs/"><u>2024 Approved Efficient Audio Documentation in Academia Using Macs</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-how-win11-monitors-and-records-activities/"><u>Discovering How Win11 Monitors and Records Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-fixes-for-the-frozen-search-in-windows-11-settings-app/"><u>Efficient Fixes for the Frozen Search in Windows 11 Settings App</u></a></li>
<li><a href="https://article-tips.techidaily.com/enhancing-memory-retention-organized-photo-albums-and-icloud-coordination-for-2024/"><u>Enhancing Memory Retention Organized Photo Albums and iCloud Coordination for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-windows-11s-missing-search-items/"><u>How to Address Windows 11'S Missing Search Items</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-an-app-on-windows-11-and-11/"><u>How to Reset an App on Windows 11 and 11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-prime-youtube-personalities-and-their-stellar-subscriber-tally/"><u>In 2024, Prime YouTube Personalities and Their Stellar Subscriber Tally</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-assistants-windows-11s-best-free-aid-compendium/"><u>Innovative Assistants: Windows 11'S Best Free Aid Compendium</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/is-the-fitbit-charge-3-still-a-top-contender-in-wearables-technology/"><u>Is the Fitbit Charge 3 Still a Top Contender in Wearables Technology?</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-watch-time-free-windows-media-center-list/"><u>Maximize Your Watch Time: Free Windows Media Center List</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-wp-app-showdown-introducing-unison-and-phone-link/"><u>Microsoft WP App Showdown: Introducing Unison & Phone Link</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-your-desktop-the-essentials-of-adding-widgets-to-window-11/"><u>Revamping Your Desktop: The Essentials of Adding Widgets to Window 11</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-pc-download-rates-on-battlenet/"><u>Skyrocket PC Download Rates on Battle.net</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-future-of-apple-macos-15-sequoias-arrival-insider-info-on-launch-schedule-cutting-edge-features-and-news-updates/"><u>The Future of Apple: MacOS 15 Sequoia's Arrival - Insider Info on Launch Schedule, Cutting-Edge Features & News Updates</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-nokia-c22-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Nokia C22 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
</ul></div>

