# Pages and Attachments Comments Report #

The plugin allows to display the comments (simple and inline) of the current page (and, and its descendents' comments, if selected) in a form of a table and also page attachments' comments (simple and inline) as a table.

It has 2 macros:

* Pages Comments
* Attachments comments

The icons in the top right of the page show the count of the comments on current page:

* grey - number of simple comments 
* yellow - number of inline Unresolved comments
* green - number of inline Resolved comments

Icons are clickable - by clicking you will go to the first comment of relevant type on current page.

## Pages Comments ##

By default the macro shows simple comments, but you can control the table comments displaying.

The macro has the following options:

* <b>Show INLINE comments</b> - if switched on, the inline comments will be displayed instead of simple
* <b>Inline comments type</b> - If <b>Show INLINE comments</b> is selected, you can set here if you want to see all, just Resolved or just Unresolved inline comments
* <b>Space Key</b> - select the space where the page to display the comments from, is located
* <b>Page Title</b> - select the page from which to display comments
* <b>Author name</b> - checkbox to display the name of the comment's author
* <b>Commented content</b> - checkbox to display the commented content of inline comment (for INLINE comments only)
* <b>Display page title</b> - display the Page Title column with pages from which the comments will be collected
* <b>Creation date</b> - checkbox to show the date when the comment was created
* <b>Date format</b> - specify the format in which the date should be displayed
* <b>Descendents</b> - checkbox to display the comments from descendent pages

In the following fields you can specify the width of the corresponding column:

You can specify the width in pixels or percentage for these columns:

* <b>Commented content column width</b>
* <b>Author column width</b>
* <b>Comment column width</b>
* <b>Is Resolved column width</b>
* <b>Page title column width</b>
* <b>Date column width</b>

Example : "120", "120px", "24%"

## Attachments Comments ##

* <b>Show Inline comments</b> - Display Inline comments of attachments, not simple ones

* <b>Space</b> - select the space with necessary page
* <b>Page Title</b> - select the necessary page from the correct space

* <b>Author</b> - checkbox to display the name of the comment's author
* <b>Page name</b> - checkbox to display the name of the page with attachments' comments
* <b>Date</b> - checkbox to show the date when the comment was created
* <b>Date format</b> - specify the format in which the date should be displayed

You can specify the width in pixels or percentage for these columns:

* <b>Comment column width</b>
* <b>Attachment column width</b>
* <b>Author column width</b>
* <b>Date column width</b>
* <b>Page Name column width</b>

Example : "120", "120px", "24%"
