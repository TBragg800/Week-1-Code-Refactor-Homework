# Week-1-Code-Refactor-Homework
<h2>VU Bootcamp week 1 homework summary:</h2>
The purpose of this refactor is to improve the codebase, ensure that all the links are functioning properly and to condense the CSS in an effort to make it more efficient. Additionally, the CSS has been organized to follow the semantic structure of the HTML elements. You will find a list below of all of the specific changes that have been made. 

<h3>Html changes:</h3>
<ul>
  <li>Added id tag “search-engine-optimization” so the “search-engine-optimization" link will direct to the appropriate location.</li>
  <li>Changed div element to a header element.</li>
  <li>Changed div element to a nav element for major block of navigation links.</li> 
  <li>Changed multiple div elements to figure elements to wrap images with captions.</li> 
  <li>Changed multiple div elements nested in figure elements to figcaption elements.</li> 
  <li>Changed div element to a footer element.</li> 
  <li>Removed the “header” class.</li>
  <li>Removed the “footer” class.</li>
  <li>Removed the “benefit-lead”, “benefit-brand” and “benefit-cost” classes.</li>
  <li>Removed “search-engine-optimization”, “online-reputation-management” and “social-media-marketing” classes.       </li> 
  <li>Removed unnecessary img closing tag from “cost-management.png”.</li> 
  <li>Removed unnecessary backslash from the end of all img tags.</li> 
  <li>Removed “float-left” and “float-right” classes.</li>
  <li>Removed “sea” class.</li>
  <li>Removed “header” class.</li>
  <li>Added additional “meta” element attributes.</li>
  <li>Changed the “div class=”content”” and div class=“benefits”” elements to section elements.</li>
  <li>Changed the “div class=“hero”” element to a figure element.</li>
  <li>Changed the “title” to briefly describe the page.</li>
  <li>Added alt attributes to all images.</li>
</ul>

<h3>Css changes:</h3>
<ul>
  <li>Changed the “header” class selector to attach to the header element.</li>
  <li>Changed the “footer” class selector to attach to the footer element.</li>
  <li>Condensed the benefit-lead, benefit-brand and benefit-cost selectors into one h3 selector.</li>
  <li>Condensed the benefit-lead, benefit-brand and benefit-cost  with image selectors into one “.benefits img” selector.</li>
  <li>Condensed “.search-engine-optimization”, “.online-reputation-management” and “.social-media-marketing” class selectors into one selector “.content figure”.</li>
  <li>Condensed “.search-engine-optimization img”, “.online-reputation-management img” and “.social-media-marketing img” class selectors into one selector “.content img”.</li> 
  <li>Condensed “.search-engine-optimization h2”, “.online-reputation-management h2” and “.social-media-marketing h2” class selectors into one selector “.content h2”.</li> 
  <li>Removed “.float-left” selector.</li>
  <li>Added “float: left;” and “margin-left: 25px;” to “.content img” selector.</li>
  <li>Changed “.float-right” selector to “#online-reputataion-management img” selector.</li>
  <li>Changed “.header h1 .seo” selector to “span” selector.</li>
  <li>Changed all “.header” and “div” selectors to reference “header” and “nav” elements.</li>
  <li>Added “float: inherit;” to the “.content figure” selector.</li>
