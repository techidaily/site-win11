---
title: "Organize Your Data with Excel: Mastering Alphabetical Tab Arrangement Techniques"
date: 2024-08-26 14:15:56
updated: 2024-08-29 11:35:37
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fd60f16bf20dda981eb260766dc085349ba6360b3659bdf5766d705fbc85be65.jpg
---

## Organize Your Data with Excel: Mastering Alphabetical Tab Arrangement Techniques

If you have a large number of worksheets in your Excel workbook, it may be hard to find a specific worksheet. Sorting your worksheet tabs alphabetically would make it easier to find what your looking for.

Related: [How to Change the Color of the Worksheet Tabs in Excel](https://hardware-help.techidaily.com/get-the-latest-hp-scanjet-software-for-windows-operating-systems-quick-guide-and-downloads/) 

 In addition to organizing your worksheet tabs by [applying colors to them](https://eaxpv-info.techidaily.com/updated-harness-your-view-count-cross-platform-studio-methods-for-2024/), you can also sort them alphabetically or alphanumerically, as long as you've [applied custom names to your worksheets](https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-xiaomi-14-ultra-phone-unlock-it-now-by-drfone-android/). Unfortunately, sorting worksheet tabs alphabetically is not built in to Excel, but you can add a macro to your workbook that will allow you to sort your tabs in ascending or descending order. We’ll show you how to add a macro available on Microsoft’s support site to your Excel workbook that will sort your worksheet tabs.

![01_unsorted_tabs](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/01_unsorted_tabs.png) 

 To begin, press Alt+F11 to open the Microsoft Visual Basic for Applications (VBA) editor. Then, go to Insert > Module.

![02_selecting_insert_module](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/02_selecting_insert_module.png) 

 Copy and paste the following macro [from Microsoft](https://support.microsoft.com/en-us/kb/812386) into the module window that displays.

Sub Sort_Active_Book()

    
                    Dim i As Integer

    
                    Dim j As Integer

    
                    Dim iAnswer As VbMsgBoxResult

    
                    '

    
                    ' Prompt the user as which direction they wish to

    
                    ' sort the worksheets.

    
                    '

    
                     iAnswer = MsgBox("Sort Sheets in Ascending Order?" & Chr(10) _

    
                     & "Clicking No will sort in Descending Order", _

    
                     vbYesNoCancel + vbQuestion + vbDefaultButton1, "Sort Worksheets")

    
                     For i = 1 To Sheets.Count

    
                     For j = 1 To Sheets.Count - 1

    
                    '

    
                    ' If the answer is Yes, then sort in ascending order.

    
                    '

    
                     If iAnswer = vbYes Then

    
                     If UCase$(Sheets(j).Name) > UCase$(Sheets(j + 1).Name) Then

    
                     Sheets(j).Move After:=Sheets(j + 1)

    
                     End If

    
                    '

    
                    ' If the answer is No, then sort in descending order.

    
                    '

    
                     ElseIf iAnswer = vbNo Then

    
                     If UCase$(Sheets(j).Name) < UCase$(Sheets(j + 1).Name) Then

    
                     Sheets(j).Move After:=Sheets(j + 1)

    
                     End If

    
                     End If

    
                     Next j

    
                     Next i

    
                    End Sub

 The VBA editor automatically names each module with a number on the end, such as Module1, Module2, etc. You can simply accept the default name of the module. However, if you plan to add other macros to your workbook, it’s a good idea to rename each module so you know what they are. We’ll rename our module to show you how.

![04_module1_in_modules_list](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/04_module1_in_modules_list.png) 

 To rename the module, select the text in the Name box for the module under Properties in the left pane.

![05_changing_module_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/05_changing_module_name.png) 

 Type a name for the module in the Name box and press Enter. Note that the module name cannot contain spaces.

![06_typing_new_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/06_typing_new_name.png) 

 The name of the module changes in the Modules list under Project in the left pane.

![07_name_changed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/07_name_changed.png) 

 Close the VBA editor by going to File > Close and Return to Microsoft Excel.

![08_file_close_and_return_to_excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/08_file_close_and_return_to_excel.png) 

 Now, we’re going to run the macro to sort our tabs. Press Alt+F8 to access the list of macros on the Macro dialog box. Select the macro in the list (in our case there is only one macro), and click “Run”.

![09_running_macro](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/09_running_macro.png) 

 The following dialog box displays, allowing you to choose whether you want to sort your worksheets in ascending or descending order. We want to sort them in ascending order, so we click “Yes”.

![10_sort_worksheets_dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/10_sort_worksheets_dialog.png) 

 The worksheet tabs are now arranged in alphabetical order.

![11_sorted_tabs](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/11_sorted_tabs.png) 

 The macro you added is part of your workbook now, but when you save it, you’ll probably see the following dialog box. That’s because you saved your workbook as an .xlsx file, which is a normal Excel workbook format that does not include macros. To include macros in your workbook, and be able to run them, you must save your workbook as a macro-enabled workbook, or an .xlsm file. To do this, click “No” on this dialog box.

![12_warning_about_saving_macro_enabled_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/12_warning_about_saving_macro_enabled_file.png) 

 The Save As dialog box displays. Navigate to where you want to save the macro-enabled workbook, if you’re not already in that folder. Select “Excel Macro-Enabled Workbook (\*.xlsm)” from the “Save as type” drop-down list.

![13_selecting_excel_macro_enabled_workbook](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/13_selecting_excel_macro_enabled_workbook.png) 

 Click “Save”.

![14_clicking_save](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/14_clicking_save.png) 

 If you don’t save the workbook as a macro-enabled workbook (.xlsm file), the macro you added will be deleted. You might want to delete the .xlsx version of your workbook so you don’t forget to use the .xlsm version of your workbook if you want to add more worksheet tabs and sort them again using the macro. You can always save the workbook as an .xlsx file again if you don’t want to use macros anymore.

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
