---
title: Changing NAT Types Effortlessly with Our Step-by-Step Tutorials
date: 2024-07-29T15:54:52.775Z
updated: 2024-07-30T15:54:52.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing NAT Types Effortlessly with Our Step-by-Step Tutorials
excerpt: This Article Describes Changing NAT Types Effortlessly with Our Step-by-Step Tutorials
keywords: Changing NAT Types,NAT Effortless Change,NAT Steps Guide,NAT Type Alteration,NAT Migration Easy,Step-by-Step NAT,NAT Tutorial Quickly
thumbnail: https://thmb.techidaily.com/6cd087da3f927fb5541ee18a5c4f27fd477ab52940ff719d4e3de086cc546e4e.jpg
---

## Changing NAT Types Effortlessly with Our Step-by-Step Tutorials

### Key Takeaways

* Changing the NAT type from strict to open can improve network connectivity and reduce network-related issues when playing multiplayer games online.
* You can change your NAT type on Windows by enabling Discovery Mode, UPnP, or port forwarding.
* Port forwarding provides greater control over open ports and enhances security compared to UPnP, but it requires knowing the specific TCP and UDP ports used by your game.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unleash-creative-potential-with-top-tips-for-gopro-timelapses/"><u>[New] 2024 Approved  Unleash Creative Potential with Top Tips for GoPro Timelapses</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-5-essentials-for-mac-users-on-the-tiktok-web-for-2024/"><u>[New] Top 5 Essentials for Mac Users on the TikTok Web for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-game-day-to-hollywood-sports-video-success-story-for-2024/"><u>[Updated] From Game Day to Hollywood  Sports Video Success Story for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-win10s-best-bet-for-screen-snaps-and-recordings/"><u>[Updated] Win10's Best Bet for Screen Snaps and Recordings</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-shorts-a-comprehensive-marketing-tool/"><u>2024 Approved  YouTube Shorts  A Comprehensive Marketing Tool</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-infinix-smart-8-pro-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Infinix Smart 8 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-cryptography-tools-for-windows-users-146-chars/"><u>7 Essential Cryptography Tools for Windows Users (146 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-preserving-your-win-11-push-notification-functionality/"><u>A Guide to Preserving Your Win 11 Push Notification Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-windows-11-the-essentials-of-its-registry-data/"><u>A Window Into Windows 11: The Essentials of Its Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-mixer-for-clear-windows-sounds/"><u>Activating the Action Center Mixer for Clear Windows Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functional-gadget-alert-in-windows-11/"><u>Addressing Non-Functional Gadget Alert in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-nvidia-opengl-failure-code-3-on-win11/"><u>Addressing NVIDIA OpenGL Failure Code 3 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-error-unauthorized-file-reading-in-win11/"><u>Addressing Steam Error: Unauthorized File Reading in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unreadable-folder-in-microsoft-office-for-desktop-users/"><u>Addressing Unreadable Folder In Microsoft Office for Desktop Users</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-converting-heic-images-to-jpeg-in-windows-11/"><u>Advanced Tips for Converting HEIC Images to JPEG in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/altering-monitors-order-in-windows/"><u>Altering Monitors' Order in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-non-working-cut-and-paste-in-win-11/"><u>Ameliorating Non-Working Cut and Paste in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-unsatisfied-system-demands-sign-in-win11/"><u>Avoid Unsatisfied System Demands Sign in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overloaded-capacity-alerts-on-pcsupremum/"><u>Avoiding Overloaded Capacity Alerts on PC'supremum</u></a></li>
<li><a href="https://win11.techidaily.com/bare-bones-pc-boasts-bulky-but-lackluster-loops/"><u>Bare-Bones PC Boasts Bulky, but Lackluster Loops</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-competition-with-fc-managed-for-no-charge/"><u>Beat the Competition with FC Managed for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-digital-discourse-with-windows-11/"><u>Begin Your Digital Discourse with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/best-way-to-wrap-windows-store-games-for-yule/"><u>Best Way to Wrap Windows Store Games for Yule</u></a></li>
<li><a href="https://win11.techidaily.com/bluetooth-woes-try-these-9-fixes-for-a-seamless-link-in-windows-11/"><u>Bluetooth Woes? Try These 9 Fixes for a Seamless Link in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-performance-with-these-six-simple-steps/"><u>Boost Your VM Performance with These Six Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-microsoft-edge-performance-in-win10win11/"><u>Boosting Microsoft Edge Performance in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-user-interface-with-scroll-lock-icon-on-windows-11-systray/"><u>Boosting User Interface with Scroll Lock Icon on Windows 11 SysTray</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-to-accessing-steam-files/"><u>Breaking Down Barriers to Accessing Steam Files</u></a></li>
<li><a href="https://fox-access.techidaily.com/chic-and-stylish-beauty-videos-for-2024/"><u>Chic and Stylish Beauty Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719329356847-chrome-freezing-woes-on-win11-try-these-swift-solutions/"><u>Chrome Freezing Woes on Win11? Try These Swift Solutions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/gaming-with-style-perfecting-your-steam-footage-for-2024/"><u>Gaming with Style - Perfecting Your Steam Footage for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-apple-iphone-xs-max-online-without-jailbreak-by-drfone-ios/"><u>How to Unlock SIM Card on Apple iPhone XS Max online without jailbreak</u></a></li>
<li><a href="https://some-techniques.techidaily.com/imprint-clipart-with-inner-circle-light-defocus-method-ps-for-2024/"><u>Imprint Clipart with Inner Circle Light Defocus Method PS for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-samsung-galaxy-m34-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Samsung Galaxy M34</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Apple iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-xiaomi-redmi-13c-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Xiaomi Redmi 13C Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/key-players-in-top-6-4k-youtube-to-mp3-conversion-software-for-2024/"><u>Key Players in Top 6 4K YouTube-to-MP3 Conversion Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719374553725-new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/"><u>New Era of Connectivity: Windows for iPhones, iPads and PCs Just Dropped</u></a></li>
<li><a href="https://win11.techidaily.com/1719319756779-revive-your-frozen-shift-key-on-pc/"><u>Revive Your Frozen Shift Key on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/1719338015239-team-share-dilemma-heres-the-solution/"><u>Team Share Dilemma? Here's the Solution</u></a></li>
<li><a href="https://win11.techidaily.com/1719231593414-unveiling-the-impact-of-eradicating-windows-11s-taskbar-chatting-functionality/"><u>Unveiling the Impact of Eradicating Windows 11'S Taskbar Chatting Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/1719371064101-windows-11-ready-embrace-google-chrome-now/"><u>Windows 11 Ready? Embrace Google Chrome Now</u></a></li>
</ul></div>
