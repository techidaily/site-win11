---
title: Optimize PC Power for Distributed Video Conversion by Tdarr
date: 2024-08-15T23:34:20.594Z
updated: 2024-08-16T23:34:20.594Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimize PC Power for Distributed Video Conversion by Tdarr
excerpt: This Article Describes Optimize PC Power for Distributed Video Conversion by Tdarr
keywords: Pc Power Optimization,Video Distributed Conversion,Tdarr Video Tech,PC Efficiency Enhancement,Low-Latency Transmission,High-Performance PCs,Streaming Device Upgrade
thumbnail: https://thmb.techidaily.com/5f19d12263b1224bd46b49560f2a184a0c0f8c0d56bb43f9e5c26e9a6768a6cd.jpg
---

## Optimize PC Power for Distributed Video Conversion by Tdarr

 Transcoding is one of the most demanding tasks for your PC, translating to a time-consuming process for the end user. Encoding a single video can take days, depending on the PC's specifications, the codec used, and the source video's characteristics. That's where multiple PCs and an app like Tdarr can be a lifesaver.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.

## What Is Tdarr?

 Sonarr, Radarr, and their "siblings" were created to assist with media piracy. However, unlike the other apps in the pirate-y "...arr" family, Tdarr differs in two crucial ways, justifying why we've decided to use it for this guide:

* It doesn't specialize in "granting access to illegal content" like (most of) its siblings, but in modifying the media files you already own.
* It trivializes the creation of mass-video-encoding networks. In the past, few, apart from professionals in the field, like Netflix, could pull this off successfully.

 After setting it up, Tdarr can help you "unify" your media collection, whose files are spread on various devices. You can always [compress videos to reduce their file size](https://www.makeuseof.com/compress-video-file/) yourself, but why not completely delegate the task to Tdarr?

1. You can configure Tdarr to "pull" your media files from all your devices.
2. It can then re-encode them to formats appropriate for each of them.
3. Finally, it can store the results in a shared folder or "push" them to each device on your local network.

 Best of all, after you set it up, it works automatically while taking advantage of the hardware capabilities of the "nodes" in your network: Windows desktop PCs, Linux servers, ARM-based Chromebooks, or your shiny new Mac.

 For this article, we'll see how you can set it up and use it on two Windows-based PCs on the same home network.

## How to Install Tdarr

 Despite being a relatively complicated collection of separate scripts and tools, Tdarr's installation is straightforward.

1. Start by downloading the appropriate version of the application for your platform from [Tdarr's official GitHub page](https://GitHub.com/HaveAGitGat/Tdarr).
2. Extract the downloaded zip archive and run the Tdarr **updater** app.
3. Windows protection might warn you that you are trying to run an unrecognized application. Click on **More info** to allow the app to run.
4. Click on **Run anyway** to acknowledge that you want to run an application created "by an unknown publisher".  
![Tdarr Install App Run Anyway](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-install-app-run-anyway.jpg)
5. Allow the Tdarr updater to download everything needed by the application. If you see any mention that a connection failed, grant the Tdarr updater access to the Internet through your firewall.  
![Tdarr Downloading Necessary Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-downloading-necessary-data.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tdarr's Hardware Requirements

 You can run the Tdarr server and the node software on any PC and access its interface through almost any browser. However, your hardware's performance and features can significantly affect encoding speeds.

 For example, a node running on a modern AMD Ryzen CPU will encode the same video in a blink compared to a ten-year-old Intel Celeron.

 Another node, using Nvidia's **NVEnc** hardware encoder for transcoding, will, in turn, be much faster than the AMD Ryzen CPU, but will also produce lower quality or larger files.

 So, if you find Tdarr's encoding too slow, you have two options:

* Try a less demanding codec or one that's "hardware accelerated" by your hardware.
* Upgrade to better hardware.

 Apart from that, you can run Tdarr even on a ten-year-old laptop if you can tolerate slow encoding speeds.

### What About Tdarr's Codecs?

 We won't go into detail about what codecs are and how they work. However, we must mention that the codecs and encoders you choose are the most important factor for Tdarr's encoding performance and quality of produced results.

* Newer Codecs come with better quality-to-bitrate ratios but also higher hardware requirements.
* Hardware encoders can dramatically boost performance but also produce lower quality/larger files than software encoders (when using similar settings).

 With the above in mind, here's a list of the codecs worth using with Tdarr for re-encoding your media files. The closer a codec is to the top, the better the output quality, the higher its requirements, and the slower the encoding time.

1. AV1
2. H.265/HEVC
3. VP9
4. H.264/AVC
5. AV1/H.265 GPU-assisted Encoding
6. H.264 GPU-Assisted Encoding
7. MPEG4, DivX, Xvid
8. MPEG2

## How to Configure Tdarr

 Tdarr's core is its server, which provides a browser-accessible interface for the app, manages media, and orchestrates encoding among various nodes. The server doesn't do any encoding on its own. For that, it needs at least one node.

 Each node can have its own configuration and run locally on your PC or another computer on the same network. Nodes are responsible for media analysis, health checks, re-encoding, etc.

 The server controls all nodes, how they act on media, and manages files.

 Tdarr's nodes come pre-configured for running on the "local" PC without requiring a network. Thus, if you only plan to use Tdarr on a single PC, you only have to configure its server (apart from minor node tweaks).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
### Configuring Your Tdarr Server

 For this article, we'll see how you can configure Tdarr Server from scratch without importing an existing media collection. Have you got a media library set up? You can modify the paths we'll use to point to your existing folders to have Tdarr process and re-encode them.

1. To configure Tdarr for a single computer, enter the **Tdarr Server** folder created by Tdarr's updater and run the **Tdarr Server app**.
2. As with the updater, you will probably have to allow it access through your firewall.
3. Tdarr's page didn't open automatically in your default browser? Enter the following in your browser's address bar: "localhost:8265/", and press **Enter** to visit Tdarr's web-based GUI. We suggest you **bookmark** it for easier access in the future.  
![Tdarr Change Log](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-change-log.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
4. If you don't like how Tdarr's page looks, you can change its theme from the **Options** page.
5. Scrolling down on the same page, you'll find a series of **Resolution boundaries** fields. Those allow you to set custom resolutions for your media.  
![Tdarr Options Define Resolution Boundary Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-options-define-resolution-boundary-crop.jpg)

1. For example, since I only have access to **Full HD** screens, I've set "**1920**" as the width in the **Width Max** field of all resolutions above 1080p and their height as "**1188**" in their respective **Height Max** fields. This way, Tdarr will never re-encode media at a higher resolution than the native Full HD (1920 x 1080) of my monitors, producing much smaller files more quickly than if it had to deal with higher resolutions.  
![Tdarr Options Custom Resolution Boundary Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-options-custom-resolution-boundary-crop.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
2. You need at least one library for your media, so visit the **Libraries** page and click the **Library +** button to create one.
3. Type any name you wish in the field stating "**Library Name**".
4. Fire up your favorite file explorer. Choose where you want to keep your media and create a folder. For this article, we used a folder named "**Videos**" at the root of the system "C" drive.
5. Create three subfolders inside that folder. For ease of use, we've named them "**Incoming**", "**Ready**", and "**Temporary**". "Incoming" is where we will drop any unprocessed files for Tdarr to check out. "Temporary" is the folder Tdarr will use while processing files. "Ready" is where Tdarr will output processed files.  
![Tdarr Incoming Ready Temporary Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-incoming-ready-temporary-folders.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
6. Go back to Tdarr's interface, move to the **Libraries** page, select your library, and if not visible on your screen, scroll down to find the **Source** tab. Click on it and enter the full path to your Incoming folder in the **Source** field below.  
![Tdarr Define Library Source Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-define-library-source-crop.jpg)
7. Move to the **Transcode cache** tab and enter the full path to your "Temporary" folder in the **Cache** field.  
![Tdarr Set Transcode Cache to Temporary Folder Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-set-transcode-cache-to-temporary-folder-crop.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
8. Finally, move to the **Output folder**, and as you might have guessed, enter the full path to your "Ready" folder in the **Output** field.  
![Tdarr Point Output Folder to Ready Folder Path Copy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-point-output-folder-to-ready-folder-path-copy.jpg)
9. Click the switch next to **Output Folder** on that tab to have Tdarr use the Incoming and Ready folders as Input and Output. If you don't do that, Tdarr will store everything in the Incoming folder. If you've got many media files, that can quickly get messy.

 If you wish, you can control the rate at which Tdarr scans the Incoming folder for new files. To do that, move to your library's **Source** tab, scroll down a bit, and change the number in the **Folder watch scan interval** field under **Folder watch settings**.

 Similarly, right below, you can tell it to run an hourly scan and define how many **File scanner threads** that will use. If you store your media on NVMe or SSD drives, increasing the number of File scanner threads can boost performance.

 Older mechanical HDDs, though, take a significant hit in performance when trying to access files in parallel, so it's best not to exceed the default value of "**2**" for those. You can also enable the option to **Hold files after scanning** and define how long (in seconds) those files will remain locked to ensure other apps won't interfere with them.

 Your library's **Filters** tab lets you define resolutions and codecs you'd prefer to skip. If, for example, you want Tdarr only to **downscale** videos, you can enter all the popular lower resolutions up to your monitor's native resolution (like "360p", "720p", and "1080p"), separated by commas in the **Resolutions to skip field**.

![Tdarr Library Filters Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filters-crop.jpg)

 The **Codecs to skip** field works similarly. For example, if you type "**AV1, HEVC**" in that field, Tdarr won't try re-encoding video files already compressed with those codecs.

![Tdarr Library Filter Skip Code Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filter-skip-code-crop.jpg)

 To have Tdarr process your files, it will have to watch the incoming folder to detect changes (AKA: new files). For that, visit your library's **Source** tab and flick the switch next to **Folder watch** to the right.

![Tdarr Library Source Enable Folder Watch Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-source-enable-folder-watch-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Customizing Tdarr's Nodes & Encoding

 Tdarr requires at least one active node to act on your media, so it's time to turn our attention to them.

1. With your Tdarr server still active, to add a node to it, enter the **Tdarr node** folder created by the Tdarr updater and run the **Tdarr node app** you'll find within it.
2. You will see a notification on Tdarr's interface web interface page that a node was **registered**.  
![Tdarr Node Connected to Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-connected-to-server.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. To test things out, place a media file in your incoming folder.  
![Tdarr Place Video into Incoming Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-place-video-into-incoming-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
4. Move to Tdarr's main page (named "Tdarr") and scroll to the bottom, under **Status**, to find your library. Soon you will see the file you added to your Incoming folder appear there.  
![Tdarr Media Added to Library Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-media-added-to-library-crop.jpg)
5. Nothing will happen because your node needs to be configured to act on it. For that, scroll up to find the **Nodes** panel and click on your node name.  
![Tdarr Node Selection Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-selection-crop.jpg)

1. You will see more details about the selected node, and you can use the **plus** and **minus** buttons next to **Transcode** and **Health Check** to assign to the node CPU and GPU threads for each task. This way, you control which node does what, which is especially useful in a multi-computer environment.  
![Tdarr Node Transcode and Health Check Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-transcode-and-health-check-crop.jpg)
2. Click on your node's **Options** button to access its more advanced options.
3. You can manually edit the node's configuration from here. Still, it's best to leave it as is and only manipulate it using external applications like Notepad.  
![Tdarr Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-1.jpg)
4. Scroll down and use the drop-down menu to select which type of GPU acceleration you want the node to use (if available on your hardware).  
![Tdarr Node Hardware Encoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-hardware-encoding-crop.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. If you want to use the PC on which the node runs for other tasks while encoding, flick the switch under **Low FFMPEG/HandBrake Process Priority** to have the node consume fewer resources and avoid choking your PC. Alternatively, [use an app like Process Lasso to take control of your CPU threads](https://www.makeuseof.com/process-lasso-take-control-of-cpu-threads/) and ensure it won't start crawling while encoding.
6. For even more control, you can scroll down further and create a **Node schedule**, stating which hours of the day a node will be allowed to perform health-checking or transcoding tasks using the CPU or GPU.
7. When you return to the **Nodes** panel with at least one CPU or GPU assigned for transcoding and health checks, you will see that your node has started working on your incoming file.  
![Tdarr Node Scanning Media File Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-scanning-media-file-crop.jpg)
8. After an initial check and if the incoming file doesn't match your filter, Tdarr will start transcoding it.

 You can see the result when it's done if you scroll to the **Staging** section where, in our case, the status of our file was "**Transcode Success**", and its size was down to around 49 MB. The **Handling** field on the right offers three buttons for controlling the entries of this list.

 Using those, you can requeue, skip, or accept an encode. You can find the re-encoded version of your file inside the "Ready" folder.

![Tdarr Re encoded File in Ready Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-re-encoded-file-in-ready-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Network & Hardware-Accelerated Encoding

 Tdarr is best when using all the CPU and GPU power of all PCs on your local network for re-encoding your files. However, that's a bit more complicated to set up.

 For this part of our guide, we take for granted that you have more than one PC, and they can "see" each other through your local network. You've got the PCs but haven't "networked them" yet? Choose a networking approach from our collection of [diagrams on which to base your home network for full connectivity](https://www.makeuseof.com/home-network-setup-diagrams/), and then follow our guide on [how to set up a secure home network](https://www.makeuseof.com/home-network-setup/).

1. Since all the PCs that will become nodes in Tdarr's network will require access to the same media files, you should keep them in a network-accessible shared folder. It's better to use a dedicated network drive for that. Still, we shared the same "Videos" folder we created earlier, but with "**shared**" as its network alias.  
![Tdarr Shared Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-shared-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
2. Update the **Source**, **Transcode cache**, and **Output folder** paths of your library to point to the respective subfolders within your "Shared" folder.
3. Install Tdarr on the other PCs in your local network. Use your file manager to enter the "**configs**" folder in Tdarr's installation directory.  
![Tdarr Config Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-config-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Make a copy of the "**Tdarr\_Node\_Config.json**" file, then open the original with a text editor (like Notepad).  
![Tdarr Node Config in Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-in-explorer-1.jpg)
5. You can change the value next to "**nodeName**" to assign the node any name you wish, like "my\_laptop", to make it easier to recognize and manage what runs where. Next to "**serverIP**", enter the IP of the PC on which you run the Tdarr server. As the "**serverPort**", enter "**8266**".  
![Tdarr Editing Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-editing-node-config.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->

1. Next, you have to configure the "**pathTranslators**". This section is the most complicated to grasp since it needs you to define **pairs of paths**. Next to "**server**", you must enter the path from which the Tdarr server can access a particular folder.
2. Next to "**node**", you must enter the equivalent path from which a node can access the same folder through the network. So, the actual path to our incoming folder on the Tdarr server PC was **//vmware-host/Shared Folders/Shared/Incoming**, but the path to the same folder on our node PC was through the mapped network drive "D:" and the folders **/Shared/Incoming**.
3. You have to define a path translator for each of the folders you've specified in Tdarr's interface for your "Incoming", "Temporary", and "Output" folders. The goal is to have both the Tdarr server and its nodes able to find the same files through their respective paths.  
![Tdarr Node Config Path Translators](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-path-translators.jpg)
4. Run the node software on your second PC and ensure both its firewall and the one on your main Tdarr server PC allow connections between them. Our guide on [how to allow apps through Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) can help with that. You should see the remote node popup in your Tdarr server interface if everything works correctly.  
![Tdarr Network Node Connected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-network-node-connected.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
5. Next to its address, you will see its IP address and be able to control its CPU and GPU threads and options as if it were a local node.
6. If GPU encoding doesn't work for you, it's probably because the appropriate plugin is disabled. For that, move back to the **Libraries** page, scroll down to find its tabs, and click on **Transcode options**.
7. There, enable the "**Migz-Transcode Using Nvidia GPU & FFMPEG**" plugin. You must also prioritize it over CPU encoding by left-clicking, dragging, and dropping it above the "**Migz-Transcode Using CPU & FFMPEG**" plugin.  
![Tdarr Libraries Enable Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-enable-hardware-transcoding-crop.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. From the same spot, if you click on a plugin, you can configure some options about how it will work. However, we won't dive into those, for they're outside the scope of this article.  
![Tdarr Libraries Customize Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-customize-hardware-transcoding-crop.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
9. When you return to the **Nodes** panel, your nodes (for which you've enabled that) should be using their GPUs for transcoding.

## Set Up Your Auto-Multi-Hyper-Encoder With Tdarr

 Setting up complicated automation software like Tdarr can take a while and occasionally make you wonder why something doesn't work as intended. When you set it up, though, Tdarr feels like magic.

 Add its server and nodes to your computers' auto-startup sequences, and hey presto, your media will always be re-encoded to high-quality, smaller files, using the optimal resolutions and formats for every single "machine" in your network. All while taking advantage of all available CPUs and GPUs in your PCs without you having to lift a finger.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-selection-for-top-tier-hdr-cameras/"><u>[New] Ultimate Selection for Top-Tier HDR Cameras</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-instant-sharing-to-long-term-storage-snapshots-journey/"><u>[Updated] From Instant Sharing to Long-Term Storage  Snapshots' Journey</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-your-potential-with-outstanding-android-time-lapse-videos/"><u>[Updated] Unleash Your Potential with Outstanding Android Time-Lapse Videos</u></a></li>
<li><a href="https://win11.techidaily.com/10-solutions-for-stuck-pin-locks-on-windows/"><u>10 Solutions for Stuck PIN Locks on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-best-free-android-capture-app-zero-ads/"><u>2024 Approved  Best Free Android Capture App, Zero Ads</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-unlocking-successful-srt-shipping-out-of-premiere/"><u>2024 Approved  Unlocking Successful SRT Shipping Out of Premiere</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-void-recovering-startups-on-windows/"><u>Bridging the Void: Recovering Startups on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-way-for-printer-use-by-one-pc-only/"><u>Clearing the Way for Printer Use by One PC Only</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-gpu-usage-in-windows-desktop-window/"><u>Decreasing Excessive GPU Usage in Windows Desktop Window</u></a></li>
<li><a href="https://win11.techidaily.com/dont-overlook-the-side-effects-of-bargain-windows-keys/"><u>Don't Overlook: The Side Effects of Bargain Windows Keys</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhanced-personalization-with-the-help-of-cookiebot-technology/"><u>Enhanced Personalization with the Help of Cookiebot Technology</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-activate-black-background-on-wincalc/"><u>Guide to Activate Black Background on WinCalc</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-windows-11s-security-settings/"><u>Guide: Accessing Windows 11'S Security Settings</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oneplus-nord-n30-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my OnePlus Nord N30 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-combat-frozen-wireless-mice-on-windows-desktops/"><u>How to Combat Frozen Wireless Mice on Windows Desktops</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/how-to-mute-google-meet-in-2024/"><u>How to Mute Google Meet, In 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-pro-max-without-passcode-4-easy-methods-drfone-by-drfone-ios/"><u>How To Unlock iPhone 12 Pro Max Without Passcode? 4 Easy Methods | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-x90s-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo X90S</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone 14 Plus</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirror-your-apple-iphone-6s-plus-display-drfone-by-drfone-ios/"><u>In 2024, How to Screen Mirror your Apple iPhone 6s Plus Display? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-windows-bar-make-it-transparent-on-win11/"><u>Invisible Windows Bar: Make It Transparent on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/low-memory-high-performance-comparing-best-windows-browsers/"><u>Low-Memory, High Performance: Comparing Best Windows Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-system-restore-a-windows-11-perspective/"><u>Mastery Over System Restore: A Windows 11 Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-white-screens-and-blank-logins-on-windows-1011/"><u>Navigating Through White Screens and Blank Logins on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-file-properties-and-date-adjustments/"><u>Navigating Windows File Properties and Date Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-powershell-experience-execution-policies-demystified/"><u>Optimize Your PowerShell Experience: Execution Policies Demystified</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-update-failure-code-0x80246007/"><u>Overcoming Windows 11'S Update Failure: Code 0X80246007</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>Pokemon Go Error 12 Failed to Detect Location On Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/searching-for-a-slender-browser-footprint-on-your-desktop/"><u>Searching For a Slender Browser Footprint on Your Desktop</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-repair-addressing-recurrerence-of-bsod-linked-with-multiple-irp-completion-tasks/"><u>Step-by-Step Repair: Addressing Recurrerence of BSOD Linked with Multiple IRP Completion Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-systems-replacing-aged-windows-drivers-efficiently/"><u>Streamlining Systems: Replacing Aged Windows Drivers Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-organized-print-setup-in-windows-systems/"><u>The Key to Organized Print Setup in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-preventing-random-keyboard-hotkeys-at-work/"><u>Tips for Preventing Random Keyboard Hotkeys at Work</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11-drive-map-techniques/"><u>Unlocking Win11 Drive Map Techniques</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-unleash-your-creativity-best-free-video-editors-for-32-bit-windows/"><u>Updated Unleash Your Creativity Best Free Video Editors for 32-Bit Windows</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-xiaomi-redmi-12-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Xiaomi Redmi 12 5G Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wizardry-entering-control-panel-quickly/"><u>Windows Wizardry: Entering Control Panel Quickly</u></a></li>
</ul></div>
