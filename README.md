# Wiki
##HTML Design Principes
##Tables - For data rendering - Not for data structuring

##Explanation
Tables have been part of HTML almost since HTML began. The idea was to make it possible to display tabular data, equivalent to a spreadsheet. This purpose is still valid. Using tables for tabular data is perfectly standards-compliant and makes a lot of sense from an accessibility standpoint.HTML tables should only be used for rendering data that belongs naturally in a grid, in other words where the data describe a number of objects that have the same properties. 

As the internet progressed and as people started doing more things online, designers started using tables to create multi-column website layouts. This was never the intention of those who created HTML standards, but it quickly caught on and table-based layouts became the norm online. For several years, web designers used tables as the only way to structure web pages, but CSS now makes their use redundant.


##Recommended
Tables should be used for data rendering: Why? 
HTML tables should only be used for rendering data that belongs naturally in a grid, in other words where the data describe a number of objects that have the same properties.
Tables should be used whenever you have tabular data to display. This could include charts of data or statistics, as well as things like price charts, product lists, or similar data that is logically arranged into a table format.
Use CSS for layout, it has its own advantage over tables.


##Not Recommended
Tables should never be used for layout: Why?
Tables are semantically incorrect markup for layout.
Tables prevent certain layouts from working within them (like height:100% for child elements of <td>).
Tables make life hell for those using screen readers.
Tables lock you into the current design and make redesigns MUCH harder than semantic HTML+CSS.
Tables are less flexible than divs etc.
##Example 

It is possible to rearrange the order in which boxes are displayed on a page, even make them stack, just by changing a few CSS properties. This is impossible with tables, which are rigid and immovable.



#Further Readings

http://www.noupe.com/design/better-ui-design-proper-use-of-tables.html

http://phrogz.net/css/WhyTablesAreBadForLayout.html#incorrectsemantics

http://www.vanseodesign.com/css/css-divs-vs-tables/

http://www.chromaticsites.com/blog/13-reasons-why-css-is-superior-to-tables-in-website-design


