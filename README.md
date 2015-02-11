# Wiki
##HTML Design Principes
##Tables - For data rendering - Not for data structuring

##Explanation

<h3>Tables for data renedering</h2>
<ol> 
<li>Tables have been part of HTML almost since HTML began. The idea was to make it possible to display tabular data, equivalent to a spreadsheet. </li>
 <li>This purpose is still valid. Using tables for tabular data is perfectly standards-compliant and makes a lot of sense from an accessibility standpoint.</li> 
 <li>HTML tables should only be used for rendering data that belongs naturally in a grid, in other words where the data describe a number of objects that have the same properties. </li>
</ol>

<h3>Tables for data layout</h3>
<ol>
<li>As the internet progressed and as people started doing more things online, designers started using tables to create multi-column website layouts.</li>
<li>This was never the intention of those who created HTML standards, but it quickly caught on and table-based layouts became the norm online.</li>
<li>For several years, web designers used tables as the only way to structure web pages, but CSS now makes their use redundant.</li>
</ol>

##Recommended

<h3>Tables should be used for data rendering: Why? </h3>
<ol>
<li>HTML tables should only be used for rendering data that belongs naturally in a grid, in other words where the data describe a number of objects that have the same properties.</li>
<li>Tables should be used whenever you have tabular data to display.This could include charts of data or statistics, as well as things like price charts, product lists etc.</li>
<li>Use CSS for layout, it has its own advantage over tables.</li>
</ol>

##Not Recommended
<h3>Tables should never be used for layout: Why?</h3>
<ol><li>Tables are semantically incorrect markup for layout.</li>
<li>Tables prevent certain layouts from working within them (like height:100% for child elements of <td>).</li>
<li>Tables make life hell for those using screen readers.</li>
<li>Tables lock you into the current design and make redesigns MUCH harder than semantic HTML+CSS.</li>
<li>Tables are less flexible than divs etc.</li>
</ol>

##Example 
<p>It is possible to rearrange the order in which boxes are displayed on a page, even make them stack, just by changing a few CSS properties. This is impossible with tables, which are rigid and immovable.</p>



##Further Readings
<ol>
<li>http://www.noupe.com/design/better-ui-design-proper-use-of-tables.html</li>

<li>http://phrogz.net/css/WhyTablesAreBadForLayout.html#incorrectsemantics</li>

<li>http://www.vanseodesign.com/css/css-divs-vs-tables/</li>

<li>http://www.chromaticsites.com/blog/13-reasons-why-css-is-superior-to-tables-in-website-design</li>
</ol>

