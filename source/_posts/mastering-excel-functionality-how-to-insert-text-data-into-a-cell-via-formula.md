---
title: "Mastering Excel Functionality: How To Insert Text Data Into A Cell Via Formula"
date: 2024-08-26 16:11:43
updated: 2024-08-29 11:23:44
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8e7f29503e1809da37fe391a31647712629490bb93b62275ef9ee0f83d862d33.jpg
---

## Mastering Excel Functionality: How To Insert Text Data Into A Cell Via Formula

### Quick Links

* [Add Text to the Beginning of a Cell](https://youtube-help.techidaily.com/in-2024-gain-profit-power-the-secret-of-successful-youtube-marketing-and-500plus/)
* [Add Text to the End of a Cell](https://techidaily.com/undelete-lost-photos-from-vivo-y27-5g-by-fonelab-android-recover-photos/)
* [Add Text After a Specific Number of Characters](https://win-dash.techidaily.com/update-your-razer-graphics-driver-on-windows-10-8-7-xp-and-vista-step-by-step-guide-to-downloading-new-versions/)
* [Add Text After a Specific Character](https://instagram-video-recordings.techidaily.com/2024-approved-transforming-raw-footage-into-stellar-instagram-content/)

### Key Takeaways

 To add text to the beginning or the end of your existing text, use the "&" operator or the CONCAT function. Using other functions, you can add text at the nth character or before or after a specific character.

 Do you want to [add some text](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) to the beginning, middle, or end of the existing text in your cells? Microsoft Excel has you covered. You can use a formula or function to append text to your cells, including finding a specific character and adding your text before or after it. Here's how.

##  Add Text to the Beginning of a Cell

[To add some text](https://instagram-clips.techidaily.com/updated-2024-approved-dual-dimensions-in-display-the-instagram-guide-to-effortless-image-turns/) before your existing text in a cell, simply use the `&` (ampersand) operator or the `CONCAT` function. Both work the same way.

 To use them, first, open your Excel spreadsheet and select the cell where you want to display your merged text.

![Select a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/1-excel-select-cell.png) 

 In the chosen cell, type the following formula and press Enter. In this formula, replace `Mr. ` (note the space after the text) with the text you want to add and `B2` with the reference of the cell where you want to append your text.

="Mr. "&B2

 Note that we've enclosed the text to add in double-quotes. You can add any text, spaces, numbers, or symbols within these quotes, and Excel will append them to your existing cell content.

![Add text before text using the & operator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/2-excel-add-text-before-text.png) 

 If you'd like to [use the CONCAT function](https://facebook-clips.techidaily.com/new-elevate-your-facebook-profile-with-these-11-superior-tools/), then in the cell where you want to display the result, enter the following function and press Enter. Here, replace `Mr. ` with the text to add and `B2` with the cell reference where your existing text is.

=CONCAT("Mr. ",C2)

 Your result will look like the following:

![Add text before text using CONCAT.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/3-excel-concat-before.png) 

Related: [How to Add Space Between Text and Cell Borders in Excel](https://instagram-clips.techidaily.com/updated-2024-approved-dual-dimensions-in-display-the-instagram-guide-to-effortless-image-turns/) 

##  Add Text to the End of a Cell

 To append your custom text at the end of your existing text, use the same `&` (ampersand) operator or the `CONCAT` function.

 If you'd like to use the `&` operator, then in your Excel spreadsheet, click the cell where you want to display the result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/4-excel-choose-cell.png) 

 In the selected cell, type the following formula and press Enter. Here, replace `B2` with the cell where your existing text is and ` (Journalist)`with the text you want to append.

=B2&" (Journalist)"

 There's a space before ` (Journalist)` so that this custom text adds a space right after your existing text ends.

![Add text after text using the & operator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/5-excel-add-text-after-text.png) 

 If you'd like to use the `CONCAT` function, then in your chosen cell, enter the following and press the Enter key. Once again, replace `B2` with the cell containing your existing text and ` (Journalist)` with the text you want to add.

=CONCAT(B2," (Journalist)")

 And here's what the result will look like:

![Add text after text using CONCAT.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/6-excel-concat-after.png) 

Related: [How to Add Alternative Text to an Object in Microsoft Excel](https://instagram-video-files.techidaily.com/new-2024-approved-how-to-upload-and-post-gifs-onto-instagram-4-steps/) 

##  Add Text After a Specific Number of Characters

 Excel allows you to add custom text after the specified number of characters in your existing text or after a specific character.

 To add your text after a specific number of characters, use the `LEFT` , `RIGHT` , and [LEN functions](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) in combination with the `&` operator.

 For example, to add a `-` (hyphen) after the second character in the `C2` cell's content, select the cell where you want to display the result.

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/7-excel-click-cell.png) 

 In the selected cell, type the following formula and press Enter. Here, replace all instances of `C2` with your cell reference, `-` (hyphen) with the text you want to add, and `2` with the number of characters after which you want your custom text to appear.

=LEFT(C2,2)&"-"&RIGHT(C2,LEN(C2)-2)

 Soon as you press Enter, Excel will add the specified text and display the result.

![Insert text after specific characters.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/8-excel-add-text-nth-character.png) 

##  Add Text After a Specific Character

 In case you want to add text after or before a specific character in a cell's text content, then use Excel's `LEFT` , `SEARCH` , `RIGHT` , and `LEN` functions.

 For instance, to add `212` (NYC's area code) after the `#` (hash) symbol, you'll use the following formula. Here, you'll replace `C2` with the cell where your existing text is, `#` with the character after which you want to append your text, and `212` with the text to add.

=LEFT(C2,SEARCH("#",C2))&"212"&RIGHT(C2,LEN(C2)-SEARCH("#",C2))

 You'll see the result in your selected cell.

![Append text after a specific character.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/9-excel-add-text-after-specific-character.png) 

 Once you've used a formula or function from the above sections, you can [automatically copy it for all your records](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) in the sheet. To do that, from the bottom-right corner of the cell where you've entered your function or formula, drag downwards until all your records are covered. And that's all.

 Is your concatenated text not fitting Excel's default cell size? There's a way to [shrink or expand your cells](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/).

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
