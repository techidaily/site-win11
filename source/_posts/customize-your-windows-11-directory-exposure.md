---
title: Customize Your Window's 11 Directory Exposure
date: 2024-09-11T09:30:08.773Z
updated: 2024-09-12T09:30:08.773Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize Your Window's 11 Directory Exposure
excerpt: This Article Describes Customize Your Window's 11 Directory Exposure
keywords: Custom Window Display Adjustment,DirExpo Customization Guide,Windows View Settings,Personalized Directory View,Optimize Window Pane,Fixed Window Positioning,Tailored Screen Layout
thumbnail: https://thmb.techidaily.com/d64a92b374563fd7f8dd564ef2b564a68a3b72b9d9892ee74121db7b4e7f60bc.jpg
---

## Customize Your Window's 11 Directory Exposure

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115917/19272" target="_top" id="2115917">
  <img src="//a.impactradius-go.com/display-ad/19272-2115917" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115917/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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


