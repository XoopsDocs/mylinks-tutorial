# 7.0 Templates

This module uses 
•	two templates for About and Help screens in the Administration, and 
•	three templates for its four blocks  

You can customize the layout of the module by modifying the templates, which are available in Administration menu => System Module => Templates => MyLinks. Note that you cannot modify the default templates – you must make a copy first (clone them). This ensures you can always fall back to the original templates. See the Operations Guide for more details about templates. The MyLinks templates are:
mylinks_brokenlink.html
Displays the user-side form for reporting broken links.

mylinks_link.html
This is the template for displaying each individual link description. It is included within other templates that display the link descriptions, such as the index page etc.

mylinks_index.html
Displays the main (index) page for the MyLinks module.This is the template for the Partners block.

mylinks_modlink.html
Displays the user-side form to request amendment of a link description.

mylinks_ratelink.html
Displays the user-side form to ‘Rate this site’.

mylinks_singlelink.html
Displays a page with a single link description (for example, when a link is selected from the ‘recent links’ block).

mylinks_submit.html
Displays the user-side form to enter / submit new link descriptions.

mylinks_topten.html
Displays the ‘Top ten’ links in each category. It is called by the ‘Popular’ and ‘Top Rated’ sublinks in the main menu. The contents are ordered according to hits or user ratings, depending on which sublink was selected.

mylinks_viewcat.html
This template displays the contents of a category (links and subcategories).

mylinks_block_new.html
Displays the Recent Links block.

mylinks_block_top.html
Displays the ‘Top Links’ block.


