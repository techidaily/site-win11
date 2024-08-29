---
title: "Easy Steps to Define Excel Cell Value Constraints: Min and Max Techniques"
date: 2024-08-28T00:47:46.627Z
updated: 2024-08-29T00:47:46.627Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/82e91f7db84fddd0d0cd74fd53de4decc4bc8c46a25aa2285ca573b91b9719e8.jpg
---

## Easy Steps to Define Excel Cell Value Constraints: Min and Max Techniques

### Quick Links

* [Finding Minimum and Maximum Values in Excel](https://facebook-video-footage.techidaily.com/updated-deciphering-user-insights-in-youtube-comments-for-2024/)
* [How to Produce a Result With a Minimum Value in Excel](https://remote-screen-capture.techidaily.com/updated-in-2024-the-7-best-stardew-valley-mods/)
* [How to Produce a Result With a Maximum Value in Excel](https://unlock-android.techidaily.com/lock-your-vivo-y100-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/)
* [How to Produce Maximum or Minimum Results With Other Formulas in Excel](https://facebook.techidaily.com/unveiling-the-truth-7-pivotal-facebook-revelations/)

 When using Excel, you can create formulas that produce a minimum value or maximum value in a calculation. In this article, we will show you the potential uses of this simple Excel formula and how to implement it in your spreadsheet.

##  Finding Minimum and Maximum Values in Excel

 A more well-known function of Excel lets you [find the highest and/or lowest values](https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-xs-max-to-others-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) within a range of numbers, handy if you are keeping track of bills in your budget. You can also combine these formulas to [find the range](https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-vivo-y77t-drfone-by-drfone-virtual-android/) (the largest minus the smallest) within that list of numbers if you're looking to produce statistical data. Both of these make use of the MIN and MAX functions in Excel.

 However, a less-known use of the MIN and MAX functions in Excel lets you cap numbers in a spreadsheet, or set a minimum value. Let's see how we can do this.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
##  How to Produce a Result With a Minimum Value in Excel

 To produce a result with a minimum value in Excel, use the following formula:

=MAX(X,Y)

 where X is the numerical value or cell reference that determines the minimum value, and Y is the cell reference of the number you are looking to affect. Let's look at how to actually use it. 

 Let's say we own a grocery store, and we take pre-orders from our customers. Now that we have compiled the total number of orders for each fruit, we need to place the order with our wholesaler. However, the wholesaler insists that we order a minimum of 1500 for each fruit.

![Excel sheet containing a table with three columns. The first column contains fruit products, the second column contains customer orders, and the third column (blank) contains orders to make with the wholesaler (minimum 1500).](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/wholesale-orders-blank.png) 

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
 Therefore, we want Excel to tell us how many pieces of each fruit we need to order from the wholesale to both satisfy our customers' orders and meet the minimum requirement of the wholesaler. Begin by clicking the cell where you want the first calculation to be made (in this case, we're starting with bananas).

 Start to type the following formula:

=MAX(

 This might seem contradictory, as your intention is to provide a minimum result of 1500 in the final column, not a maximum result. However, the reason we type MAX is that we are telling Excel to find the maximum possible value in the calculation, with no upper limit.

 Next, inside the parentheses, we need to type the criterion (in this case, it's 1500):

=MAX(1500

 Finally, we need to add a comma, click or type the cell reference we are looking to affect (in our example, it's cell K20), and then press Enter:

=MAX(1500,J20)

 You can now see the number of bananas we need to order from the wholesaler.

![Excel sheet showing the use of the MAX formula to produce a minimum result of 1500 in the final column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/min-bananas.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 If the minimum criterion is likely to change, instead of typing the minimum number into the formula above, we would type the minimum value into another cell and [use an absolute reference](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/) to tell Excel where to find the criterion:

=MAX($K$28,J20)

![Excel sheet showing the minimum value in cell K28 and the correct formula to use to produce a minimum result in the final column of the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/abs-ref-minimum-1.png) 

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you were to change "1500" to another number in cell K28, the minimum criterion would automatically change within your calculations in your table.

 We can now apply the same formula to the other cells in the table by [using Excel's AutoFill function](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/).

![Excel sheet showing the total orders in the rightmost column after having applied the minimum value and used AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/min-autofilled-1.png) 

 We have now fulfilled our customers' orders while also meeting the wholesaler's minimum requirements for each fruit.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Produce a Result With a Maximum Value in Excel

 To produce a result with a minimum value in Excel, use the following formula:

=MIN(X,Y)

 where X is the numerical value or cell reference that determines the maximum value, and Y is the cell reference of the number you are looking to affect. Let's look at this in more detail.

 Let's assume we own a business and offer bonus incentives to our employees. However, we want to cap the bonuses they can receive every two months to $5000.

![Excel sheet containing a table with five columns. The first column contains employee names, the second and third columns contain the respective bonuses to be paid for January and February, the fourth column contains the total bonuses, and the fifth column is headed 'Maximum bonus: 5000' with no values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/bonus-payments-blank.png) 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Firstly, type the following formula in the cell where you want the result to show:

=MIN(

 Again, this might seem confusing, as we are aiming to produce a capped value in the final column, not a minimum value. However, we type MIN because we are telling Excel to find the smallest possible value, with no lower limit.

 Next, inside the parentheses, type the criterion (in this example, it's 5000):

=MIN(5000

 Finally, add a comma, click or type the cell reference to be affected (in this case, we would click on cell M20), and press Enter.

=MIN(5000,L20)

 We can now see the maximum result for the first calculation we want to make:

![Excel sheet showing the use of the MIN formula to produce a maximum result of 5000 in the final column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/max-employee-1.png) 

 If you are likely to change the value of the capped number, type the maximum value in another cell and [reference this cell using an absolute reference](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/), instead of typing the maximum value directly into the formula:

=MIN($M$28,L20)

![Excel sheet showing the maximum value in cell M28 and the correct formula to use to produce a minimum result in the final column of the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/abs-ref-maximum-1.png) 

 As a result, if you were to amend the cap of 5000 in cell M28, the calculations in your table would automatically adjust to your new figure.

 Then, use AutoFill to apply the formula to the remaining cells.

![Excel sheet showing the total bonus in the rightmost column after having applied the maximum value and used AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/max-autofilled-1.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Produce Maximum or Minimum Results With Other Formulas in Excel

 Using a formula within your MIN or MAX calculation can help you to present your spreadsheet more succinctly. Let's say we want to remove the total bonus column altogether in the following table, and get Excel to work out the payment at the same time as considering the maximum value.

![Excel sheet containing a table with five columns. The first column contains employee names, the second and third columns contain the respective bonuses to be paid for January and February, the fourth column contains the total bonuses, and the fifth column is headed 'Maximum bonus: 5000' with no values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/bonus-payments-blank.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 Therefore, our table would initially look like this, and we need to tell Excel to add the totals together for each employee to work out what will go in the final column:

![Excel sheet containing a table with four columns. The first column contains employee names, the second and third columns contain the respective bonuses to be paid for January and February, and the fourth column is headed 'Max 5000' with no values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/combined-blank-2.png) 

 To work out how much we're paying Tom, in the cell where you want the total to show (L20 in this example), type the following formula and press Enter:

=MIN(5000,(SUM(J20+K20)))

 See the previous sections for further information on how this formula works.

![Excel sheet showing the first result for a calculation where the values in two columns have been added together and a maximum has been applied.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/combined-first-result.png) 

 You can also type the criterion in another cell and [use absolute referencing](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/) to link to that cell, rather than the value itself, within your formula, and press Enter:

=MIN($L$28,(SUM(J20+K20)))

![Excel sheet showing the maximum value in cell L28 and the correct formula to use to produce a maximum result in the final column of the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/abs-ref-combined.png) 

 Now, if you were to amend your cap of 5000 in cell L28, your formula would automatically pick up the newly inserted number.

 Finally, use AutoFill to complete your table.

![Excel sheet showing the totals in the rightmost column after having performed a calculation, applied the maximum value, and used AutoFill in that column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/combined-autofilled.png) 

 The same method can be used for calculating a maximum number or a minimum number.

---

 Now you know how to cap results or set a minimum value in your Excel spreadsheet!

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
<li><a href="https://screen-capture.techidaily.com/new-active-presenter-8-review-is-it-the-best-screen-recorder/"><u>[New] Active Presenter 8 Review  Is It The Best Screen Recorder?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-essential-8-tools-linux-based-edits-software-for-2024/"><u>[New] Essential 8 Tools  Linux-Based Edits Software for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-simplifying-age-verification-on-tiktok-accounts/"><u>[New] Simplifying Age Verification on TikTok Accounts</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-reposition-mac-picture-cache-destination/"><u>[Updated] Reposition Mac Picture Cache Destination</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-poco-m6-5g-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Poco M6 5G</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-demystified-guiding-you-through-win11-upgrades/"><u>DevHome Demystified: Guiding You Through Win11 Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/digital-dots-top-8-window-friendly-note-apps/"><u>Digital Dots: Top 8 Window-Friendly Note Apps</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-web-interaction-enable-mouse-gestures-in-microsofts-edge-browser/"><u>Elevate Your Web Interaction: Enable Mouse Gestures in Microsoft's Edge Browser</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-ms-resouce-text-error-on-windows-11/"><u>Eliminating Ms-Resouce Text Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-unsupported-windows-hello-scanner-mismatch/"><u>Eliminating the Unsupported Windows Hello Scanner Mismatch</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-isdonedll-problem-steps/"><u>Eliminating Windows 11'S ISDone.dll Problem Steps</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-fixing-failed-windows-mmc-creations/"><u>Expert Guide to Fixing Failed Windows MMC Creations</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-startup-functionality-for-a-smooth-windows-11-launch/"><u>Fine-Tuning Startup Functionality for a Smooth Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-iphoneipad-photo-import-error-a-compreayers-approach-on-w11/"><u>Fixing iPhone/iPad Photo Import Error: A Compreayer’s Approach on W11</u></a></li>
<li><a href="https://win11.techidaily.com/halt-unprompted-gaming-suggestions-on-windows-11/"><u>Halt Unprompted Gaming Suggestions on Windows 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/o-download-part-of-youtube-video/"><u>How to Download Part of YouTube Video?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-vmware-bsod-error-on-windows-11/"><u>How to Fix VMware BSOD Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revert-windows-11s-search-bar-to-a-search-icon/"><u>How to Revert Windows 11'S Search Bar to a Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/improve-visual-identification-displaying-this-pc-icon/"><u>Improve Visual Identification: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-mastering-instagram-the-ultimate-video-cropping-techniques/"><u>In 2024, Mastering Instagram  The Ultimate Video Cropping Techniques</u></a></li>
<li><a href="https://driver-download.techidaily.com/installing-the-latest-windows-11-drivers-intel-iris-plus-gfx-655-support/"><u>Installing the Latest Windows 11 Drivers: Intel Iris Plus GFx 655 Support</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-ed-inspired-visuals-to-windows/"><u>Introducing Ed-Inspired Visuals to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-books-unlocking-potential-with-7-top-study-methods-on-a-windowed-computer/"><u>Master the Books: Unlocking Potential with 7 Top Study Methods on a Windowed Computer</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-new-window-11-the-best-modifications-for-an-optimized-experience/"><u>Master Your New Window 11: The Best Modifications for an Optimized Experience</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-remedies-for-windows-app-issues-7-steps-to-success/"><u>Masterful Remedies for Windows App Issues, 7 Steps to Success</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-game-capture-fbx-filming-techniques-for-2024/"><u>Mastering Game Capture  FBX Filming Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-powertoys-in-win11-setup/"><u>Mastering Microsoft PowerToys in Win11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-with-sticky-notes-in-w11w10/"><u>Maximize Productivity with Sticky Notes in W11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-back-to-your-copilot-in-ws11-spacecraft/"><u>Navigate Back to Your Copilot in WS11 Spacecraft</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-new-era-of-interactive-technology-between-pc-and-galaxy/"><u>Navigating a New Era of Interactive Technology Between PC & Galaxy</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-clipboard-utility-in-windows-11-pcs/"><u>Optimizing Clipboard Utility in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-desk-view-including-this-pc-on-the-screen/"><u>Personalize Desk View: Including 'This PC' On the Screen</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-your-desktop-icon-order/"><u>Reclaiming Your Desktop Icon Order</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-access-fixing-frozen-windows-terminals-quickly/"><u>Regaining Access: Fixing Frozen Windows Terminals Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-a-unresponsive-discord-overlay-in-windows/"><u>Solving the Puzzle of a Unresponsive Discord Overlay in Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/sony-x1000d-vivid-full-action-cam-test-for-2024/"><u>Sony X1000D Vivid - Full Action Cam Test for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-indexer-in-windows/"><u>Steps to Tweak Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-workflows-with-windows-11-multitasking-tips/"><u>Streamline Workflows with Windows 11 Multitasking Tips</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sound-system-upgrade-with-atmos-on-win-1011/"><u>Streamlined Sound System Upgrade with Atmos on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sign-in-with-windows-hello-biometrics/"><u>Streamlining Sign-In with Windows Hello Biometrics</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-hidden-taskbar-explorer-of-windows-11/"><u>Tapping Into Hidden Taskbar Explorer of Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/the-actors-art-and-craft/"><u>The Actor's Art and Craft</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-review-ultimate-guide-to-computer-hardware/"><u>Tom's Tech Review: Ultimate Guide to Computer Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/top-factors-for-choosing-windows-10-over-the-latest-operating-system-win11/"><u>Top Factors for Choosing Windows 10 over the Latest Operating System - Win11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-silent-mode-a-guide-to-fixing-conexant-smartaudio-in-windows-10/"><u>Troubleshooting Silent Mode: A Guide to Fixing Conexant SmartAudio in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-selecthighlight-capabilities-in-windows-pdf-viewer/"><u>Unblock Select/Highlight Capabilities in Windows' PDF Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-app-execution-variants-and-usage/"><u>Understanding App Execution Variants & Usage</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-vanishing-printmanagement-in-windows/"><u>Unraveling the Mystery of Vanishing 'Printmanagement' In Windows</u></a></li>
</ul></div>
