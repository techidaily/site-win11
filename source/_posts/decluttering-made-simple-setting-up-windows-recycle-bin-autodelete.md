---
title: "Decluttering Made Simple: Setting Up Windows Recycle Bin Autodelete"
date: 2024-09-16T10:09:22.676Z
updated: 2024-09-16T16:02:42.464Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decluttering Made Simple: Setting Up Windows Recycle Bin Autodelete"
excerpt: "This Article Describes Decluttering Made Simple: Setting Up Windows Recycle Bin Autodelete"
keywords: Simplify Decluttering,Windows Recycle Setup,Auto-Deletion Guide,Recycle Bin Management,Clutter Reduction Tips,Autodelete Feature Use,Easy Cleanup Techniques
thumbnail: https://thmb.techidaily.com/8f0b4518ce0df25393954ab31a3f7f9f5a628c2c9b34d40260095f1057a6321d.jpg
---

## Decluttering Made Simple: Setting Up Windows Recycle Bin Autodelete

 We all know how easy it is to delete files and send them to the Recycle Bin. But wouldn't it be great if Windows automatically emptied the bin for us? Fortunately, you can configure your system to do just that.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Automate the Recycle Bin Using the System Settings

 It's easy to configure Windows to empty the recycle bin automatically. All you need to do is open System settings, fiddle with a few things, and you're done.

 However, this feature applies only to the current user account. Other users on the same computer won't have their Recycle Bin emptied automatically until they adjust this setting. In other words, if you're using a shared computer, it won't affect anyone else.

 Here's how to do it:

1. [Open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left panel, select the **System** tab.
3. Scroll down and click on **Storage** on the right-hand side. Here, you will find various computer data storage and management options.  
![Stoage in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stoage-in-system-settings.jpg)
4. Now, you will see a toggle switch under **Storage Sense**. If it's turned off, click to switch it on. This feature enables Windows to delete no longer needed files automatically.  
![Turn on Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/turn-on-storage-sense.jpg)
5. Once Storage Sense is active, click the tiny arrow next to it to expand the options.
6. On the next screen, you'll find an option that says, **Delete files in my recycle bin if they have been there for over**. Click the drop-down menu beside this and select the duration, after which Windows should empty the recycle bin automatically.
7. Select **1 day** if you want Windows to delete these items daily. Or choose another option that suits your needs better.  
![Configure Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/configure-storage-sense.jpg)
8. You can also configure the system to delete downloaded files that haven't been used for several days. To do so, click the **Delete files in my Downloaded folder if they haven't been opened for more than** drop-down menu and select the desired option.

 Once you're done, close the Settings window. Windows will automatically empty your Recycle Bin from now on.

## 2\. How to Automate the Recycle Bin Using the Task Scheduler

 If you want more control over the process, you can use Windows Task Scheduler to empty your Recycle Bin. Here's how:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **taskschd.msc** and hit **Enter** or click **OK**. Doing this [opens the Task Scheduler program](https://www.makeuseof.com/windows-11-open-task-scheduler/).
3. On the left-hand side of the window, select **Task Scheduler Library**.
4. Now, click **Create Basic Task** from the right-hand panel. It will open another window where you can configure your task settings.  
![Create Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-basic-task.jpg)
5. Enter a name for your task (e.g., Empty Recycle Bin) and a brief description if you want. Then, click the **Next** button.

1. The following window will ask you to select the frequency when Windows should empty your Recycle Bin. You can choose Daily, Weekly, Monthly, or One time only. Once you've chosen your preferred frequency, click **Next**.  
![Create a Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-a-basic-task.jpg)
2. After that, set the start date and time for your task. Also, select **Recur every** to specify the total duration of each cleaning session. Then, click **Next**.  
![Start Date and Time in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-date-and-time-in-task-wizard.jpg)
3. You must specify what action Windows should perform when this task runs. Click on the **Start a program** option and click **Next** again.  
![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  
/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.
6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

## Automate the Recycling Process on Windows

 To keep your computer running smoothly, you must empty your Recycle Bin regularly. However, the process can be tedious and time-consuming. Fortunately, Windows provides some easy ways to automate this task, either through Windows Settings or Task Scheduler.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-celestial-vision-high-definition-touch-screens/"><u>[New] 2024 Approved Celestial Vision High Definition Touch Screens</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-make-a-thumbnail-for-your-youtube-free-easily-for-2024/"><u>[Updated] How to Make a Thumbnail for Your YouTube Free Easily for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/complete-examination-screenflow-full-features-for-mac/"><u>Complete Examination ScreenFlow Full Features for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-edit-audio-in-canva-videos-removing-and-adding-voiceovers-effortlessly/"><u>How to Edit Audio in Canva Videos: Removing and Adding Voiceovers Effortlessly</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-google-pixel-fold-lock-screen-password-by-drfone-android/"><u>How to Reset your Google Pixel Fold Lock Screen Password</u></a></li>
<li><a href="https://win11.techidaily.com/huge-savings-alert-check-out-the-amazing-black-friday-bargains-of-2eusier-in-2020/"><u>Huge Savings Alert! Check Out the Amazing Black Friday Bargains of 2Eusier in 2020</u></a></li>
<li><a href="https://win11.techidaily.com/imgburn-dvd-dvd/"><u>ImgBurn フリーウェアで簡単DVDバックアップ: DVDコピー機能をご案内し、コピーガード解除に最適なツールも紹介</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-recording-internet-radios-simplified-tips-and-tricks/"><u>In 2024, Recording Internet Radios Simplified Tips and Tricks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-spectral-savvy-applying-color-science/"><u>In 2024, Spectral Savvy Applying Color Science</u></a></li>
<li><a href="https://win11.techidaily.com/master-video-conversion-for-portable-gaming-systems-pspps3-compatible-solutions/"><u>Master Video Conversion for Portable Gaming Systems - PSP/PS3 Compatible Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-consistent-sound-quality-tips-for-balancing-mp4-audio/"><u>Mastering Consistent Sound Quality: Tips for Balancing MP4 Audio</u></a></li>
<li><a href="https://win11.techidaily.com/most-effective-windows-11-dvd-regions-bypass-tool-reviews-and-comparisons/"><u>Most Effective Windows 11 DVD Regions Bypass Tool: Reviews & Comparisons</u></a></li>
<li><a href="https://win11.techidaily.com/mp3-to-m4a/"><u>MP3 to M4A変換フリーツール比較ガイド - 使いやすくて正確なソフトウェア集めました!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/troubleshooting-obs-frame-loss/"><u>Troubleshooting OBS Frame Loss</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/tune-in-for-free-fb-music-archive-for-2024/"><u>Tune In for Free FB Music Archive for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

