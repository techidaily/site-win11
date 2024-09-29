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


