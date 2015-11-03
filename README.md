Bootstrap theme for unroole
===========================

Bootstrap theme point is a fully functional multipurpose website, with standard pages (homepage, blog, events, contact us, single blog post and event) and a [kitchensink page](http://startingpoint-bootstrap3.unroole.com/kitchen-sink) where all widgets and their various configurations are showcased. Kitchensink page will be very useful when you’re building your own custom pages as you can simply copy and paste particular widgets structure you would like to use and modify.


Widgets
-------
Below is the list of all widgets included in the theme and their configuration options

0. Article collection
---------------------
Displays collection of articles based on the category and/or type. Should be placed on pages that display article collections (ie. blog, news).
Configuration options:
* Width: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options: 
- _fluid_: will output `.container-fluid` class
- _fixed_: will output `.container` class
* Show Metadata: controls display of published date, author name and category of articles in the collection list. 
Options: 
- _yes_
- _no_
* Show Featured Image: controls display of featured images of articles in the collection list. 
Options: 
- _yes_
- _no_
* Pagination: controls display and type of pagination as per Bootstrap default types. 
Options: 
- _none_: pagination will not be outputed 
- _simple_: outputs Bootstraps simple pagiantion with only previous and next page links 
- _numbered_: outputs Bootstraps numbered pagination links
* Truncation Length In Chars: How many characters of each article to display before read more link. Default value is 300
* HTML Attributes: custom attributes that will be aplied to the container section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Article collection: default options for article collection
Options:
- _category_: select categories of articles to include
- _type_: select types of articles to include
- _per page_: number of articles to display per page
- _results page_: page which will be used to display single article when read more link is clicked
- _filter articles by tags_: coma-separated list of tags to filter the articles by

0. Article Result
-----------------
Displays article from collection on a single page. Should be placed on a page that will display single articles.
Configuration options:
* Width: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options: 
- _fluid_: will output `.container-fluid` class
- _fixed_: will output `.container` class
* Show Author: controls display of author name 
Options: 
- _yes_
- _no_
* Show Featured Image: controls display of articles featured image at the top of the article
Options: 
- _yes_
- _no_
* Show Category: controls display of articles category
Options: 
- _yes_
- _no_
* Published_Date: controls display and format of articles published date.
Options:
- _Do Not Show_: published date will not be displayed
- _Apr 22, 2014_
- _Tue Apr 22 11:16:09 2014_
- _2014-04-22_
* Show Related Articles: controls display of related articles collection below the article. Related articles are generated based on the category of the article displayed
Options: 
- _yes_
- _no_
* HTML Attributes: custom attributes that will be aplied to the container section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`