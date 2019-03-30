# Ticket #44360 Spreadsheet
This spreadsheet contains the .patch, and .diff files contributed for Ticket # 44360. I created this spreadsheet to make it easier to search for duplicates, revisions, and files still in need of a patch.

This spreadsheet is created with numbers and converted with SheetJS Community Edition
-- Spreadsheet Parser and Writer (https://sheetjs.com/) (https://github.com/SheetJS/js-xlsx).
The file may not render with the entire correct format but you should be able to make edits in your spreadsheet application.

##Column Titles

###.patch/.diff
The name of the .patch or .diff files.

###Index
The path to the file.

###Contributor
The name of the .patch/.diff contributor.

###Review/Reply
The name and reply # of a contributor review.

###Issues File Line#
I created this column to include a reference to the specific line in the issues file to search for duplicates and place holders in need of translations.
Follow the link to view the most recent line itemized issues:
(https://gist.github.com/swissspidy/006e26b7ba53cdb68a5d10763d8fcc31)
Using the issues file as an example, the warning statement, "Warning: The string "Thank you for creating with <a href="%s">WordPress</a>."
contains placeholders but has no "translators:" comment to clarify their meaning.
(wp-admin/admin-footer.php:34), is located on line 13.    

(https://core.trac.wordpress.org/attachment/ticket/44360/44360.admin-footer.diff)   

###Warning Ref Line #
I created this column to include a reference to the file line itemized in the warning statement. A reference to a specific line increases the ability to search the document for duplicates or to verify that a translator statement is still necessary.   

###Translators Line #
This column is to input the line number where you can find the translation. This helps to search the ticket for duplicates and files that need translations.
