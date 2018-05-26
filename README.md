<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. jojo-wiki-network</a></li>
<li><a href="#sec-2">2. details</a>
<ul>
<li><a href="#sec-2-1">2.1. language</a></li>
<li><a href="#sec-2-2">2.2. packages</a></li>
</ul>
</li>
</ul>
</div>
</div>

# jojo-wiki-network<a id="sec-1" name="sec-1"></a>

I've written some code to scrape specific pages on the [JoJo's Bizarre Adventure Wiki](http://jojo.wikia.com) for characters and the episodes or chapters they appear in.
I then merge the list with itself to generate a new list of characters who are connected by appearing in the same episode or chapter.
Lastly I draw network diagrams for all parts and for each part individually.

# details<a id="sec-2" name="sec-2"></a>

## language<a id="sec-2-1" name="sec-2-1"></a>

Python

## packages<a id="sec-2-2" name="sec-2-2"></a>

-   requests
-   beautifulsoup 4
-   pandas
-   networkx