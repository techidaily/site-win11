---
title: "Silent Restarts: A Windows 10/11 Guide to Going Dark"
date: 2024-08-16T00:08:13.770Z
updated: 2024-08-17T00:08:13.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Silent Restarts: A Windows 10/11 Guide to Going Dark"
excerpt: "This Article Describes Silent Restarts: A Windows 10/11 Guide to Going Dark"
keywords: Windows Offline Mode,Dark Mode Win10/11,GoDarkWin10/11,Disable Win10 Sound,Silent Restart Guide,Win10/11 Annoyance,Cutting Down Windows Noise
thumbnail: https://thmb.techidaily.com/2abff2026ed0f77bee3d5444a73ceb2a838092ecb3114e177d3896df7011b647.jpg
---

## Silent Restarts: A Windows 10/11 Guide to Going Dark

### Key Takeaways

* Schedule a shutdown in Windows 11 and 10 using Task Scheduler for daily, weekly, or monthly tasks. Customize the start date and time.
* Add a trigger condition to your shutdown task to run it after a specified period of inactivity using Task Scheduler.
* Use Command Prompt to schedule a system shutdown with a specific timer or define a shutdown time. Customize with shutdown parameters.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-capture-the-thrill-essential-recording-tips-for-overwatch/"><u>[New] 2024 Approved  Capture the Thrill  Essential Recording Tips for Overwatch</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-apex-top-youtube-videos-watch-count-heaven/"><u>[Updated] Apex Top YouTube Videos  Watch Count Heaven</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-prime-video-picks-most-watched-of-all-time/"><u>[Updated] In 2024, Prime Video Picks  Most Watched of All Time</u></a></li>
<li><a href="https://win11.techidaily.com/12-common-windows-11-aesthetic-oddities/"><u>12 Common Windows 11 Aesthetic Oddities</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-11-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-accessing-windows-web-services-manager/"><u>A Compreayer's Guide: Accessing Windows Web Services Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-iscsi-initiator/"><u>A Comprehensive Look at Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-the-negative-side-of-low-end-windows-licenses/"><u>A Deep Dive Into the Negative Side of Low-End Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-adding-secure-websites-in-windows-11/"><u>A Step-by-Step Guide to Adding Secure Websites in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-restart-utilizing-windows-11s-quick-start-function/"><u>Accelerating System Restart: Utilizing Windows 11'S Quick Start Function</u></a></li>
<li><a href="https://win11.techidaily.com/activation-verification-methods-for-windows-11/"><u>Activation Verification Methods for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adding-visual-disk-space-analyzer-to-windows-explorer-menu/"><u>Adding Visual Disk Space Analyzer to Windows Explorer Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pubg-setup-failures-a-windows-guide/"><u>Addressing PUBG Setup Failures: A Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-store-glitch-code-0x80073cf3/"><u>Addressing Windows Store Glitch: Code 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-cost-monitor-functionality-of-your-wifi-network/"><u>Adjusting the Cost Monitor Functionality of Your Wifi Network</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/an-intuitive-roadmap-for-installing-java-development-kit-on-windows-11/"><u>An Intuitive Roadmap for Installing Java Development Kit on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-key-differences-between-cloud-and-physical-windows-installations/"><u>Assessing Key Differences Between Cloud and Physical Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-oled-bape-edition-review-stealthy-stylish-and-practical/"><u>ASUS Vivobook S 15 OLED BAPE Edition Review: Stealthy, Stylish, and Practical</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-xbox-game-pass-0x00000001-troubleshooting-for-windows-11/"><u>Avoiding Xbox Game Pass 0X00000001: Troubleshooting for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-glitches-a-guide-to-fixing-error-code-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/big-bulky-minipcs-with-brainy-bare-performance/"><u>Big, Bulky Minipcs with Brainy Bare Performance</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computer-skills-keyboard-shortcuts-for-success/"><u>Boost Your Computer Skills: Keyboard Shortcuts for Success</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-black-backdrops-on-windows/"><u>Breaking Free From Black Backdrops on Windows</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/complete-data-purging-suite-stellar-file-wiped-out-on-mac/"><u>Complete Data Purging Suite - Stellar File Wiped Out on MAC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/curating-best-tiktok-scenes-as-pixel-art/"><u>Curating Best TikTok Scenes as Pixel Art</u></a></li>
<li><a href="https://facebook.techidaily.com/deciphering-the-user-exodus-from-the-worlds-largest-network/"><u>Deciphering the User Exodus From the World’s Largest Network</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-xiaomi-13t-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Xiaomi 13T FRP Bypass With Best Methods</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elite-software-selection-top-editors-for-webcams/"><u>Elite Software Selection  Top Editors for Webcams</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-oppo-reno-9a-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve  deleted photos on Oppo Reno 9A</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-pocket-playlist-portraits-actors-and-audio-art/"><u>In 2024, Pocket Playlist Portraits  Actors & Audio Art</u></a></li>
<li><a href="https://extra-resources.techidaily.com/launch-your-fortune-on-periscope-live-chats/"><u>Launch Your Fortune on Periscope Live Chats</u></a></li>
<li><a href="https://win11.techidaily.com/1719370883063-master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter.</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-top-10-budget-friendly-filmmaking-tools-for-indie-creators/"><u>New In 2024, Top 10 Budget-Friendly Filmmaking Tools for Indie Creators</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/trackcast-analysis/"><u>TrackCast Analysis</u></a></li>
</ul></div>
