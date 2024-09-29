---
title: Step-by-Step Tutorial on Controlling Information Input in Microsoft Excel Through Data Validation Rules
date: 2024-08-28T00:49:37.773Z
updated: 2024-08-29T00:49:37.773Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/you-dun-goofed.png
---

## Step-by-Step Tutorial on Controlling Information Input in Microsoft Excel Through Data Validation Rules

If you use Excel spreadsheets to collect data from other people, but find that they often fill your carefully-planned cells with the wrong kind of information, data validation can help.

 This tool lets you restrict specific cells to only allow properly-formatted data. If someone enters anything that’s not supposed to be there---like “lunch at airport” instead of “$15.68” on an expense report---Excel rejects the input until they get it right. Think of it as a passive-aggressive way to make sure people don’t waste your time.

 As an example, here’s the basic expense report worksheet for How-To Geek. Let's say we want to make sure that people only enter numerical values that are formatted as currency (i.e., some digits, followed by a decimal point, followed by two more digits) into certain cells.

 First, select all the cells you want to restrict.

![expense report](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/expense-report.png) 

 Switch over to the "Data" tab on the Ribbon, and then click the “Data Validation” button. If your window isn't full size and you can’t see the labels, it’s the icon with two horizontal boxes, a green check mark, and a red crossed circle.

![arrow](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/arrow.png) 

 In the Data Validation window, on the "Settings" tab, click the “Allow” dropdown menu. Here, you can set a specific type of input to allow for your selected cells. For our expense report, we’re going to insist that users put in a number with two decimal values, so we would select the “Decimal” option. You can also select other criteria, like making sure a cell contains text, a time or date, text of a specific length, or even your own custom validation.

![decimal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/decimal.png) 

 Whatever type of data you select on the “Allow” dropdown changes the options available to you on the rest of the "Settings" tab. Since we want a numerical value corresponding to currency, we're setting the "Data" dropdown to the “between” setting. Then, we're configuring a minimum value of 0.00 and a maximum value of 10000.00, which is way more than enough to cover our needs.

![data range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/data-range.png) 

 To test it our, click “OK” to apply the validation settings, and then try putting in an improper value. For example, if we type “pancakes” for the Breakfast value instead of the cost of the meal, we'll get an error message.

![value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/value.png) 

 While that does restrict people to entering only the correct type of data, it doesn't give them any feedback on what type of data is required. So, let's set that up, too.

 Head back to the Data Validation window (Data > Data Validation on the Ribbon). You've got two options here (and you can use both of them if you want). You can use the "Input Message" tab to have a pop-up tool tip show people the type of data you want whenever they select a cell for which data validation is turned on. You can also use the "Error Alert" tab to customize the error they see when they enter the wrong type of data.

 Let's switch over to the "Input Message" tab first. Here, make sure the "Show input message when cell is selected" option is turned on. Then, give your input tooltip a title and some text. As you can see below, just clicking in one of the cells pops up the message letting people know what's expected.

![input message](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/input-message.png) 

 On the "Error Alert" tab, you can customize the error message people see when they enter the wrong type of data. Make sure the "Show error alert after invalid data is entered" option is turned on. Pick a style for your error message from the "Style" dropdown. You can go with a Stop (the red circle with the X), Warning (yellow triangle with an exclamation point), or Information (blue circle with a lowercase "i"), depending on how strong you want the message to come across.

 Type a title for your message, the text of the message itself, and then hit "OK" to finish up.

![error alert](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/error-alert.png) 

 Now, if someone tries to enter improper data, that error message is a little more helpful (or sarcastic, if you prefer).

![excel_1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/excel_1.png) 

 It's a bit of extra legwork setting up data validation, but it can save you a lot of time later on if you use spreadsheets for collecting data from other people. It's even useful for preventing your own mistakes. And this is doubly true if you’ve set up formulas or any kind of automation tasks that rely on that data.

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



<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->