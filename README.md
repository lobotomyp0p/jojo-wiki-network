# This repository is no longer being maintained.

I am leaving it up because it is an instructive, simple example for Beautiful Soup and NetworkX. However Fandom Wiki has changed the format of their pages at some point, so the ipython notebook will no longer work "out of the box". I have no plans to fix it.

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
<li><a href="#sec-3">3. to do</a></li>
</ul>
</div>
</div>

# jojo-wiki-network<a id="sec-1" name="sec-1"></a>

I've written some code to scrape specific pages on the [JoJo's Bizarre Adventure Wiki](http://jojo.wikia.com) for characters and the episodes or chapters they appear in.
I then merge the list with itself to generate a new list of characters who are connected by appearing in the same episode or chapter.
Lastly I draw network diagrams for all parts and for each part individually.

Check out the [notebook](https://github.com/lobotomyp0p/jojo-wiki-network/blob/master/jojo_scrape_bs4.ipynb) to see how it works.

# details<a id="sec-2" name="sec-2"></a>

## language<a id="sec-2-1" name="sec-2-1"></a>

Python

## packages<a id="sec-2-2" name="sec-2-2"></a>

-   requests
-   beautifulsoup 4
-   pandas
-   networkx

# to do<a id="sec-3" name="sec-3"></a>

-   Weight edges by the number of appearances characters make together
-   Color edges by the first part in which characters make an appearance together
-   Color nodes by pagerank
-   Hide node labels except for major characters
-   Interactive features: (in notebook? in HTML?)
    -   mouse-over an edge to see what appearance it corresponds to
    -   mouse-over a node to see some data about the character
        -   a picture? wiki categories?
