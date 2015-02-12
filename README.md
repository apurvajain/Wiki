# Wiki
##HTML Design Principes
##Tables - For data rendering - Not for data structuring

##Explanation

<h3>Tables for data renedering</h3>
<ol> 
<li>Tables have been part of HTML almost since HTML began. The idea was to make it possible to display tabular data, equivalent to a spreadsheet. </li>
<li>This purpose is still valid. Using tables for tabular data is perfectly standards-compliant and makes a lot of sense from an accessibility standpoint.</li> 
<li>HTML tables should only be used for rendering data that belongs naturally in a grid, in other words where the data describe a number of objects that have the same properties. </li>
</ol>

<h3>Tables for data layout</h3>
<ol>
<li>As the internet progressed and as people started doing more things online, designers started using tables to create multi-column website layouts.</li>
<li>This was never the intention of those who created HTML standards, but it quickly caught on and table-based layouts became the norm online.</li>
<li>Tables are less flexible than divs - Table contains different tags: the table tag being the wrapper, tr for each row and td for each cell. For readability, each tag is normally given its own line of code, with indention. Any developer maintaining that page in future has to go through a lot of code to understand its structure.</li>
<li>Nested tables are code smell that a website is stuck in table hell. The number of lines of code is endless, and the complexity is overwhelming. Tables are far from clean code and don’t bring anything semantic to the content unless you’re dealing with actual tabular data.
</li>
<li>Excess code slows down development and raises maintenance costs.
More lines of code mean larger file sizes, which mean longer download times. Because tables increase the code base, such structures likely contain more bugs than layouts with less code lines.</li>
</ol>


##Recommended

<h3>Tables should be used for data rendering: Why? </h3>
<ol>
<li>HTML tables should only be used for rendering data that belongs naturally in a grid, in other words where the data describe a number of objects that have the same properties.</li>
<li>Tables should be used whenever you have tabular data to display.This could include charts of data or statistics, as well as things like price charts, product lists etc.</li>
<li>Use CSS for layout, it has its own advantage over tables as explained in the following example.</li>
</ol>

##Not Recommended
<h3>Tables should never be used for layout: Why?</h3>
<ol><li>Tables are semantically incorrect markup for layout.</li>
<li>Tables prevent certain layouts from working within them (like height:100% for child elements of <td>).</li>
<li>Tables make life difficult for those using screen readers.</li>
<li>Tables lock you into the current design and make redesigns much harder.</li>
</ol>

##Example 

To make html tables : <br> 
index.html
```html 
<table cellpadding="0" cellspacing="0" border="0">
  <tr>
    <td colspan="3" height="120px">....</td>
  </tr>
  <tr>
    <td class="menu" valign="top">...</td>
    <td class="content" valign="top">...</td>
    <td class="aSide" valign="top">...</td>
  </tr>
  <tr>
    <td colspan="3">...</td>
  </tr>
</table>
</table>
```

To make css work like tables :<br>
index.html
```html 
<div id="header">...</div>
<div id="menu">...</div>
<div id="content">...</div>
<div id="aSide">...</div>
<div id="footer">...</div>
```



##Further Readings
<ol>
<li>http://www.noupe.com/design/better-ui-design-proper-use-of-tables.html</li>

<li>http://phrogz.net/css/WhyTablesAreBadForLayout.html#incorrectsemantics</li>

<li>http://www.vanseodesign.com/css/css-divs-vs-tables/</li>

<li>http://www.chromaticsites.com/blog/13-reasons-why-css-is-superior-to-tables-in-website-design</li>
</ol>

