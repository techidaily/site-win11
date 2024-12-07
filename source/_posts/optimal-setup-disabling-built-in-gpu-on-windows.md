---
title: "Optimal Setup: Disabling Built-In GPU on Windows"
date: 2024-11-30T04:03:18.862Z
updated: 2024-12-07T09:32:00.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimal Setup: Disabling Built-In GPU on Windows"
excerpt: "This Article Describes Optimal Setup: Disabling Built-In GPU on Windows"
keywords: Turn Off Windows GPU,Disable GPU Setting,Optimize CPU Performance,GPU Shutdown Guide,Power Efficient PC,Bypass Built-In Graphics,Windows Graphics OFF
thumbnail: https://thmb.techidaily.com/e35b5be1f091e9309ed35244938c575401125e5d762e94ab1bade24154e68d3e.jpg
---

## Optimal Setup: Disabling Built-In GPU on Windows

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/arnings-on-youtube-the-crucial-number-of-video-views-for-money-for-2024/"><u>[New] Earnings on YouTube The Crucial Number of Video Views for Money for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/best-tools-to-create-stunning-igtv-video-edits-for-2024/"><u>Best Tools to Create Stunning IGTV Video Edits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-to-the-heart-of-recent-windows-use/"><u>Direct to the Heart of Recent Windows Use</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-black-ops-understanding-the-black-screen-and-error-code-0xc0000005/"><u>Fixing Black Ops: Understanding the 'Black Screen' And 'Error Code 0xC0000005'</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-honor-x8b-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Honor X8b to iPod | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-restart-stuck-windows-task-bar/"><u>Methods to Restart Stuck Windows Task Bar</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-a-device-not-valid-message-on-pc/"><u>Resolving a Device Not Valid Message on PC</u></a></li>
<li><a href="https://win11.techidaily.com/rewind-records-quick-applications-on-pc-to-change-file-dates/"><u>Rewind Records: Quick Applications on PC to Change File Dates</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-windows-11-interface-icon-sizing-up/"><u>Tailoring Windows 11 Interface: Icon Sizing Up</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/top-pick-ultimate-app-for-effortlessly-creating-a-see-through-canvas/"><u>Top Pick: Ultimate App for Effortlessly Creating a See-Through Canvas</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-xiaomi-redmi-12-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Xiaomi Redmi 12 Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>

