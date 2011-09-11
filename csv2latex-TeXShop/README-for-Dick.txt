This is the readme for csv2latex v. 1.1. 2010/01/31


This folder contains the following for inclusion of the csv2latex scripts into TeXShop.

1. csv2latex 

This is a ruby script that should go in ~/Library/TeXShop/bin

2. applescript-macro-plist-xml

This is the actual xml for the Latex_Macros.plist file.  It can be cut and pasted directly into the plist file.  I named the macro item  "Paste Spreadsheet Cells". (Better than Paste Excel cells, since it works with any spreadsheet application.)

A suitable place for it in the list of macros would be either right before or right after Will Robertson's Column Macros item.

3. csv2latex.plist

This is a full plist document of item 2 above, which can be loaded using TeXShop's built-in "Add Macros from File" function.

3. applescript-source

This is simply the text of the applescript.  (Not needed if you use the xml file).

4. help-snippet.html

This is the html file for inclusion into the TeXShop help panel.  It would make sense to add it in the same relative place as the actual menu item in the Macros menu.

5. css-style-snippet.css

Append this to the screen.css (just formats the description list styles nicely in the help; this would be useful for any other description styles within the help text anyway.)
