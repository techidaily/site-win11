---
title: The Essential Guide to Altering NAT Settings on Modern Windows Systems
date: 2024-09-05T08:28:05.393Z
updated: 2024-09-06T08:28:05.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Guide to Altering NAT Settings on Modern Windows Systems
excerpt: This Article Describes The Essential Guide to Altering NAT Settings on Modern Windows Systems
keywords: Win NAT Adjustment Tutorial,Windows NAT Modification Guide,NAT Changes in Windows Update,NAT Configure for PCs,Modern OS NAT Tweaks,Optimizing Windows NAT Settings,Navigating Windows NAT Configurations
thumbnail: https://thmb.techidaily.com/035705869a176d12c457c62dcd5ac8433382a242da2e6ee8d5c9aeccc24af52d.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115943/19272" target="_top" id="2115943">
  <img src="//a.impactradius-go.com/display-ad/19272-2115943" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## The Essential Guide to Altering NAT Settings on Modern Windows Systems

### Key Takeaways

* Changing the NAT type from strict to open can improve network connectivity and reduce network-related issues when playing multiplayer games online.
* You can change your NAT type on Windows by enabling Discovery Mode, UPnP, or port forwarding.
* Port forwarding provides greater control over open ports and enhances security compared to UPnP, but it requires knowing the specific TCP and UDP ports used by your game.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115944/19272" target="_top" id="2115944">
  <img src="//a.impactradius-go.com/display-ad/19272-2115944" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115935/19272" target="_top" id="2115935">
  <img src="//a.impactradius-go.com/display-ad/19272-2115935" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115935/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123479/16836" target="_top" id="2123479">
  <img src="//a.impactradius-go.com/display-ad/16836-2123479" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123479/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123470/16836" target="_top" id="2123470">
  <img src="//a.impactradius-go.com/display-ad/16836-2123470" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123470/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
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
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123481/16836" target="_top" id="2123481">
  <img src="//a.impactradius-go.com/display-ad/16836-2123481" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123481/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134239/18498" target="_top" id="2134239">
  <img src="//a.impactradius-go.com/display-ad/18498-2134239" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134239/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115915/19272" target="_top" id="2115915">
  <img src="//a.impactradius-go.com/display-ad/19272-2115915" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115915/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123468/16836" target="_top" id="2123468">
  <img src="//a.impactradius-go.com/display-ad/16836-2123468" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123468/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115908/19272" target="_top" id="2115908">
  <img src="//a.impactradius-go.com/display-ad/19272-2115908" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115908/19272" style="position:absolute;visibility:hidden;" border="0" />
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
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118321/7443" target="_top" id="2118321">
  <img src="//a.impactradius-go.com/display-ad/7443-2118321" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118321/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115930/19272" target="_top" id="2115930">
  <img src="//a.impactradius-go.com/display-ad/19272-2115930" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115930/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128843/7443" target="_top" id="2128843">
  <img src="//a.impactradius-go.com/display-ad/7443-2128843" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128843/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
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
<li><a href="https://screen-recording.techidaily.com/new-reimagining-home-security-the-rise-of-multi-camera-recorders-for-2024/"><u>[New] Reimagining Home Security  The Rise of Multi-Camera Recorders for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-essential-15-ideas-to-boost-your-snap-score/"><u>[Updated] 2024 Approved  Essential 15 Ideas to Boost Your Snap Score</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-snap-and-save-your-android-no-price-tag/"><u>[Updated] 2024 Approved  Snap & Save Your Android - No Price Tag</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-secrets-of-screen-grabs-exposed/"><u>[Updated] In 2024, Secrets of Screen Grabs Exposed</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-experts-guide-to-instagrams-licensed-music-posting-policies/"><u>2024 Approved  The Expert’s Guide to Instagram's Licensed Music Posting Policies</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-reno-8t-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Reno 8T 5G</u></a></li>
<li><a href="https://some-approaches.techidaily.com/adopting-effective-mobile-hygiene-with-advanced-intelligence-and-efficient-note-taking-via-abbyy-solutions/"><u>Adopting Effective Mobile Hygiene with Advanced Intelligence and Efficient Note-Taking via ABBYY Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-disabled-powershell-script-policy-4-efficient-solutions/"><u>Confronting Disabled PowerShell Script Policy: 4 Efficient Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-directdraw-errors-effective-remedies-for-modern-microsoft-oses/"><u>Decoding DirectDraw Errors: Effective Remedies for Modern Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-path-to-exceptional-windows-wallpapers/"><u>Decoding the Path to Exceptional Windows Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/defining-fresh-default-for-windows-pdf-files/"><u>Defining Fresh Default for Windows PDF Files</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-power-within-wintoys-an-in-depth-user-friendly-guide-for-windows-os-users/"><u>Discover the Power Within WinToys: An In-Depth, User-Friendly Guide for Windows OS Users</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-slide-show-creation-in-windows-seven-ways-to-go/"><u>Effortless Slide Show Creation in Windows – Seven Ways to Go</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-itel-p55t-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Itel P55T Quickly | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-notifications-from-phone-link-app-in-windows-environment/"><u>Fixing Inactive Notifications From Phone Link App in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-obstructed-video-feed-from-webcam/"><u>Fixing Obstructed Video Feed From Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/future-on-display-the-premium-laptops-at-ifa-2023/"><u>Future on Display: The Premium Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-roblox-error-code-403-on-pc/"><u>Guide to Fixing Roblox Error Code 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-handling-java-vm-creation-failure/"><u>Guidelines for Handling Java VM Creation Failure</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-itel-p40-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Itel P40 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delay-windows-10-shutdown-with-running-software-applications/"><u>How to Delay Windows 10 Shutdown with Running Software Applications</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-steams-missing-file-privileges-error-in-windows-11/"><u>How to Fix Steam's Missing File Privileges Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-1011/"><u>How to Install Dolby Atmos in Windows 10/11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-reno-9a-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Oppo Reno 9A Phone with Broken Screen</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-iphone-12-mini-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock iPhone 12 mini After Forgetting the Passcode?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-guffaw-generator-cyborg-comic-coders/"><u>In 2024, Guffaw Generator  Cyborg Comic Coders</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-official-method-to-unlock-your-iphone-14-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 14 Official Method to Unlock Your iPhone 14</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-oppo-a2-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/leading-11-ios-and-android-tools-for-professional-sound-engineering/"><u>Leading 11 iOS and Android Tools for Professional Sound Engineering</u></a></li>
<li><a href="https://win11.techidaily.com/leading-edge-in-sharing-files-windows-finest-apps-ranked/"><u>Leading Edge in Sharing Files: Windows' Finest Apps Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/live-microphone-input-addressing-recording-issues-with-obs-w11-edition/"><u>Live Microphone Input: Addressing Recording Issues with OBS, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/master-rdc-start-ups-with-these-10-tips/"><u>Master RDC Start-Ups with These 10 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-apexs-windows-server-issues-(156-chars/"><u>Mastering Apex's Windows Server Issues (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-device-control-in-windows-11-updates/"><u>Mastering Device Control in Windows 11 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-transitioning-your-workspace-from-concentration-to-normal-on-terminal/"><u>Mastery over Transitioning Your Workspace: From Concentration to Normal on Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/mouse-double-click-mastery-3-easy-steps-for-speed-enhancement/"><u>Mouse Double-Click Mastery: 3 Easy Steps for Speed Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-without-installation-in-windows-11/"><u>Notetaking Without Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-win-11-experience-with-added-movecopy-context-menu/"><u>Optimize Your Win 11 Experience with Added 'Move'/'Copy' Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-upgrade-obstacles-windows-11-update-error-0x80246007/"><u>Overcoming Upgrade Obstacles: Windows 11 Update Error 0X80246007</u></a></li>
<li><a href="https://win11.techidaily.com/precision-tactics-to-handle-win1011-recycle-bin-crashes/"><u>Precision Tactics to Handle Win10/11 Recycle Bin Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-inactive-conditional-filters-in-outlook-email/"><u>Reactivating Inactive Conditional Filters in Outlook Email</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-non-functional-outlook-push-notifications/"><u>Reviving Non-Functional Outlook Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-multitasking-the-art-of-shifting-windows-by-90-degrees/"><u>Simplify Multitasking: The Art of Shifting Windows by 90 Degrees</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reinstate-disappearing-registry-management-tool/"><u>Steps to Reinstate Disappearing Registry Management Tool</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-look-of-your-windows-cursor/"><u>Transforming the Look of Your Windows Cursor</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshoot-and-start-your-play-of-days-gone-on-pc-a-step-by-step-solution/"><u>Troubleshoot and Start Your Play of 'Days Gone' On PC - A Step-by-Step Solution</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-the-power-of-window-tabbing-for-streamlined-productivity/"><u>Uncover the Power of Window Tabbing for Streamlined Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-complex-registry-edits-with-command-prompt-scripts/"><u>Unlocking Complex Registry Edits with Command Prompt Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11s-narrator-command-efficiency/"><u>Unlocking Win11's Narrator Command Efficiency</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveiling-filmora-its-10-most-attractive-features/"><u>Unveiling Filmora  Its 10 Most Attractive Features</u></a></li>
<li><a href="https://win11.techidaily.com/win11-icons-how-to-ditch-the-focused-wallpaper-symbol/"><u>Win11 Icons: How to Ditch the Focused Wallpaper Symbol</u></a></li>
</ul></div>
