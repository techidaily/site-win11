---
title: The Efficient User's Guide to Self-Cleansing Files on Windows 10/11
date: 2024-10-13T21:01:05.492Z
updated: 2024-10-15T16:04:04.599Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Efficient User's Guide to Self-Cleansing Files on Windows 10/11
excerpt: This Article Describes The Efficient User's Guide to Self-Cleansing Files on Windows 10/11
keywords: Self-Cleaning Windows Files Guide,Windows Self-Clean Tips,Efficient File Management Windows,Optimize Windows Data Cleanup,Windows 10/11 File Organization,Streamlining Windows Files,Quick Windows Data Cleanse
thumbnail: https://thmb.techidaily.com/9dde14122d86332e2939d12b71c8c112849e5b475313180be25192ee619462eb.jpg
---

## The Efficient User's Guide to Self-Cleansing Files on Windows 10/11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-best-of-breed-pages-for-sparkling-3d-text/"><u>[New] Best of Breed Pages for Sparkling 3D Text</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-effortless-tips-for-storing-vimeo-videos/"><u>[New] In 2024, Effortless Tips for Storing Vimeo Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-expert-strategies-for-engaging-live-audiences-on-facebook/"><u>[Updated] Expert Strategies for Engaging Live Audiences on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/1726027145566-iso/"><u>「細切りのISOファイルをひも解ける完全ガイド - ビデオチュートリアル」</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-what-phone-is-compatible-with-gear-vr/"><u>2024 Approved What Phone Is Compatible With Gear VR?</u></a></li>
<li><a href="https://win11.techidaily.com/2024-flv-windows-10/"><u>2024年版 FLV ビデオプレイヤーの復活！Windows 10用トップテクニックリスト公開</u></a></li>
<li><a href="https://win11.techidaily.com/5oiq5lq65zcr44gr44ot44oh44kq44ks44kt44oj44ox44ob44oj44gz44kl5yq55p6c55qe44gq44og44kv44ol44od44kv/"><u>成人向けビデオをキャプチャする効果的なテクニック</u></a></li>
<li><a href="https://win11.techidaily.com/aacm4a/"><u>音声ファイルの変換:AACとM4Aを比べて、最適な無劣化方法は何ですか？</u></a></li>
<li><a href="https://win11.techidaily.com/6zw35oyb44gh44gz44kl5pa55rov77ya44ov44oq44od44ox44ot44oh44kq44gu5pya6ygp44gq5lplusd5a2y5oml5q61/"><u>長持ちする方法：フリップビデオの最適な保存手段</u></a></li>
<li><a href="https://win11.techidaily.com/best-split-screen-video-software-discover-the-5-most-user-friendly-options-for-making-split-videos-with-ease/"><u>Best Split Screen Video Software: Discover the 5 Most User-Friendly Options for Making Split Videos with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/1726026610963-bilibili/"><u>Bilibiliビューワで再生問題に見舞われたら、ダウンロード・セーブ不可を解決するポイント</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-htc-u23-drfone-by-drfone-android/"><u>How to Screen Mirroring HTC U23? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-itel-p55-5g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Itel P55 5G PC | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-14-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock on Apple iPhone 14</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/the-essentials-of-writing-amazing-end-of-episode-scripts-for-2024/"><u>The Essentials of Writing Amazing End-of-Episode Scripts for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-openais-ceo-is-calling-for-more-ai-regulation-and-what-that-means/"><u>Why OpenAI's CEO Is Calling for More AI Regulation (and What That Means)</u></a></li>
<li><a href="https://win11.techidaily.com/44kz44o844oh44od44kv5lin6laz44gr44ki44kl5yuv55s75yan55sf6zqc5a6z44ks5zue6yg44gz44kl5pa55rov/"><u>コーデック不足による動画再生障害を回避する方法</u></a></li>
<li><a href="https://win11.techidaily.com/44ot44oh44kq44gu5lit44gr44og44kt44k544oi44k144ow44k44kk44oi44or6lplus95yqg5oml6acg6zug/"><u>ビデオの中にテキストサブタイトル追加手順集</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    