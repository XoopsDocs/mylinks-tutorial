# Templates

This module uses

* two templates for About and Help screens in the Administration, and 
* three templates for its four blocks  

You can customize the layout of the module by modifying the templates, which are available in Administration menu =&gt; System Module =&gt; Templates =&gt; MyLinks. Note that you cannot modify the default templates – you must make a copy first \(clone them\). This ensures you can always fall back to the original templates. See the Operations Guide for more details about templates. The MyLinks templates are:

| Template | Features |
| --- | --- |
| mylinks\_brokenlink.html | Displays the user-side form for reporting broken links. |
| mylinks\_link.html | This is the template for displaying each individual link description. It is included within other templates that display the link descriptions, such as the index page etc. |
| mylinks\_index.html | Displays the main \(index\) page for the MyLinks module.This is the template for the Partners block. |
| mylinks\_modlink.html | Displays the user-side form to request amendment of a link description. |
| mylinks\_ratelink.html | Displays the user-side form to ‘Rate this site’. |
| mylinks\_singlelink.html | Displays a page with a single link description \(for example, when a link is selected from the ‘recent links’ block\). |
| mylinks\_submit.html | Displays the user-side form to enter / submit new link descriptions. |
| mylinks\_topten.html | Displays the ‘Top ten’ links in each category. It is called by the ‘Popular’ and ‘Top Rated’ sublinks in the main menu. The contents are ordered according to hits or user ratings, depending on which sublink was selected. |
| mylinks\_viewcat.html | This template displays the contents of a category \(links and subcategories\). |
| mylinks\_block\_new.html | Displays the Recent Links block. |
| mylinks\_block\_top.html | Displays the ‘Top Links’ block. |

