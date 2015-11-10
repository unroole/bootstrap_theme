# Bootstrap theme for unroole


Bootstrap theme for unroole is a fully functional multipurpose website, with standard pages (homepage, blog, events, contact us, single blog post and event) and a [kitchensink page](http://startingpoint-bootstrap3.unroole.com/kitchen-sink) where all widgets and their various configurations are showcased. Kitchensink page will be very useful when you’re building your own custom pages as you can simply copy and paste particular widgets structure you would like to use and modify.


## Widgets
Below is the list of all widgets included in the theme and their configuration options

###1. Article collection
Displays collection of articles based on the category and/or type. Should be placed on pages that display article collections (ie. blog, news).
Configuration options:
- *Width*: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options: 
  - _fluid_: will output `.container-fluid` class
  - _fixed_: will output `.container` class
- *Show Metadata*: controls display of published date, author name and category of articles in the collection list. 
Options: 
  - _yes_
  - _no_
- *Show Featured Image*: controls display of featured images of articles in the collection list. 
Options: 
  - _yes_
  - _no_
- *Pagination*: controls display and type of pagination as per Bootstrap default types. 
Options: 
  - _none_: pagination will not be outputed 
  - _simple_: outputs Bootstraps simple pagiantion with only previous and next page links 
  - _numbered_: outputs Bootstraps numbered pagination links
- *Truncation Length In Chars*: How many characters of each article to display before read more link. Default value is 300
- *HTML Attributes*: custom attributes that will be aplied to the container section. 
Options: 
  - _tag_: id of the section 
  - _classes_: classes of the section 
  - _attributes_: custom attributes, ie. `data-foo="bar"`
- *Article collection*: default options for article collection
Options:
  - _category_: select categories of articles to include
  - _type_: select types of articles to include
  - _per page_: number of articles to display per page
  - _results page_: page which will be used to display single article when read more link is clicked
  - _filter articles by tags_: coma-separated list of tags to filter the articles by

0. Article Result
-----------------
Displays article from a collection on a single page. Should be placed on a _results page_ that will display single articles when read more links are clicked within the article collection.
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

0. Article
----------
Selects and displays single article content.
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
* Article: select article to display based on title
Options:
- _article_: article title
- _results page_: page which will be used to display single article when read more link is clicked

0. Biography
------------
Displays a single biography article. Should be placed inside _Component Section_ widget.
Configuration options: 
* Width: width of the article section. Corresponds to column numbers in Bootstrap.
Options:
- _1/1_ : full width. Renders `.col-md-12` class 
- _1/2_ : half width. Renders `.col-md-6` class
- _1/3_ : one third width. Renders `.col-md-4` class
- _1/4_: one fourth width. Renders `.col-md-3` class
* Show Image: controls display of featured image of an article.
Options: 
- _yes_
- _no_
* Image Shape: controls display shape of featured image
Options:
- _default_: no styling will be aplide
- _rounded_: image will have rounded corners. Renders `.img-rounded` class on image
- _circle_ : image will be rendered as a circle. Renders `.img-circle` class in image
* Icon size: size of the social media icons. These are based on FontAwesome sizes
Options:
- _1x_ : default font size
- _33%_ : large size. Renders `.fa-lg` class on the icon
- _2x_ : double the default size. Renders `.fa-2x` class on the icon
- _3x_: three times the original size. Renders `.fa-3x` class on the icon
- _4x_: four times the original size. Renders `.fa-4x` class on the icon
- _5x_: five times the original size. Renders `.fa-5x`
* Facebook URL: renders the url to the Facebook profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Twitter URL: renders the url to the Twitter profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* LinkedIn URL: renders the url to the LinkedIn profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Pinterest URL: renders the url to the Pinterest profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Behance URL: renders the url to the Behance profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Dribble URL: renders the url to the Dribble profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* GitHub URL: renders the url to the GitHub profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Website URL: renders the url to the Website behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Email: renders the email portion of the href atribute behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* HTML Attributes: custom attributes that will be aplied to the biography section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Article: select article to display based on title
Options:
- _article_: article title
- _results page_: will not be rendered

0. Body
-------
Renders the `body` tag and allows you to add custom attributes to it. Should be placed in layouts. This is a structured widget, which means that other widgets can be placed inside.
Configuration options:
* HTML Attributes: custom attributes that will be aplied to the biography section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`

0. Breadcrumbs
--------------
Displays breadcrumbs based on the selected navigation.
Configurable options:
* Navigation: name of the navigation to be used for breadcrumb links

0. Button
---------
Displays Bootstrap styled buttons. This is a structured widget, which means that other widgets can be placed inside. Most commonly you would place Font Awesome Icon widget
Configurable options:
* Button Type: controls which tag should be used to render the button.
Options:
- _default (a)_ : `a` tag
- _button_: `button` tag
- _input_: `input` tag

* Color: Applies bootstraps default color classes
Options:
- _default_: renders `.btn-default` class
- _primary_: renders `.btn-primary` class
- _success_: renders `.btn-success` class
- _info_: renders `.btn-info` class
- _warning_: renders `.btn-warning` class
- _danger_: renders `.btn-danger` class
- _link_: renders `.btn-link` class

* Size: Applies bootstraps default sizing classes
Options:
- _default_ : no size class will be applied
- _large_ : renders `.btn-lg` class
- _small_ : renders `.btn-sm` class
- _extra small_ : renders `.btn-xs` class

* Button width: Controlls the width of the button
- _auto_: width will be depending on the label length
- _full_: width will be full width of parent container. Renders `.btn-block` class on the button

* Disable: Adds `disabled` attribute to the button:
Options:
- _no_
- _yes_

* Link to page: Select one of the pages published on your website
* Link Override URL: add external url. If added, value of Link to page will be ignored
* Button Label: text label of the button
* HTML Attributes: custom attributes that will be aplied to the button section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Article: select article to display based on title
Options:
- _article_: article title
- _results page_: will not be rendered

0. Component - Column
---------------------
Renders single Bootstrap column. Should be placed inside the Componend Section widget. This is a structured widget, which means that other widgets can be placed inside.
Configurable options:
* Grid Colums on Devices Above 1200px: number for `.col-lg-` class
* Grid Colums on Devices Above 992px: number for `.col-md-` class
* Grid Colums on Devices Above 768px: number for `.col-sm-` class
* Grid Colums on Devices Below 768px: number for `.col-xs-` class
* HTML Attributes: custom attributes that will be aplied to the column div. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Article: select article to display based on title
Options:
- _article_: article title
- _results page_: will not be rendered

0. Component Form Field
-----------------------
Renders single input field. Should be placed inside Component - Form Wrapper widget.
Configurable options:
* Input Type: select type of input you would like to create.
Options:
- _text_ 
- _checkbox_
- _radio_
- _textarea_
- _password_
- _number_
- _email_
- _url_
- _datetime_
- _datetime-local_
- _date_
- _month_
- _time_
- _week_
- _search_
- _tel_
- _color_

* Show Label: shows or hides label of the field
Options: 
- _yes_
- _no_

* Inline radio or checkbox: if input type is radio or checkbox, you can set to display them inline or not
Options:
- _yes_: renders `-inline` after class name
- _no_: renders default class name

* Input Classes: space-separated class names that will be added to the `input` tag
* Input Id: `id` that will be added to the `input` tag
* Textarea Rows: number of rows for the textarea field
* Radio Group Name: if radio is selected as type, specify the name for the group of more than one radio input
* Checkbox Radio Value: if radio or checkbox are selected as type, add value of the `value` attribute
* Label text: String to be used as label. If Show label is set to `no`, label will have `.sr-only` class added
* Input Placeholder: text that will be used as a value for the `placeholder` attribute
* HTML Attributes: custom attributes that will be aplied to `.form-group` div. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`

0. Component - Form Wrapper
---------------------------
Wrapps several Component - Form Field widgets into one form.
Configurable options:
* Form Orientation: outputs bootstrap classes for form orientation
Options:
- _default_: no class will be added
- _inline_: `.form-inline` class will be added to the `form` tag
- _horizontal_: `.form-horizontal` class will be added to the `form` tag
* Action: form processing url. Will be rendered inside `action` attribute
* Method: form processing methid. Will be rendered inside `method` attribute
* Form title: Title of the form
* HTML Attributes: custom attributes that will be aplied to form div. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`

0. Component - Map Marker
-------------------------
Renders Google Maps marker on a map. Should be used inside Component - Map Wrapper widget. IMPORTANT NOTICE: in order to load Google Maps API you must add Google Maps API widget inside your layout, to load the API on each page or on a single page to load it only on that page.
Configurable options:
* Location Latitude - latitude of the location
* Location Longitude - longitude of the location
* Location Name - Name of the location that will be displayed on marker hover and as a title of the info window when marker is clicked
* Location Description - Description of the location that will be displayed in the infowindow body when marker is clicked

0. Component - Map Wrapper
--------------------------
Renders a Google map and markers that are placed inside the widget. IMPORTANT NOTICE: in order to load Google Maps API you must add Google Maps API widget inside your layout, to load the API on each page or on a single page to load it only on that page.
Configurable options:
* Zoom level: zoom level of the map. Correspods with the Google Maps API values
* Disable Default Google Maps Controls: controls display of Google Maps controls
Options: 
- _yes_
- _no_
* Zoom on scroll: controlls whether zoom level of the map can be changed with the mouse scroll.
Options:
- _yes_
- _no_

0. Component - Pricing Column
-----------------------------
Displays a single column of the Pricing table. Should be placed inside Component - Section widget.
Configurable options:
* Width: width of the article section. Corresponds to column numbers in Bootstrap.
Options:
- _1/1_ : full width. Renders `.col-md-12` class 
- _1/2_ : half width. Renders `.col-md-6` class
- _1/3_ : one third width. Renders `.col-md-4` class
- _1/4_: one fourth width. Renders `.col-md-3` class

* Featured plan: applies `.bg-primary` class on the column header inverting the colors and making the plan stand out.
Options:
- _regular_ : default
- _featured_ : applies `.bg-primary` class

* Text Alignment: sets the alignemnt of all the text
Options:
- _left_
- _right_
- _center_
- _justify_
* Button Color: Applies bootstraps default color classes
Options:
- _default_: renders `.btn-default` class
- _primary_: renders `.btn-primary` class
- _success_: renders `.btn-success` class
- _info_: renders `.btn-info` class
- _warning_: renders `.btn-warning` class
- _danger_: renders `.btn-danger` class
- _link_: renders `.btn-link` class
* Button Size: Applies bootstraps default sizing classes
Options:
- _default_ : no size class will be applied
- _large_ : renders `.btn-lg` class
- _small_ : renders `.btn-sm` class
- _extra small_ : renders `.btn-xs` class

* Button width: Controlls the width of the button
- _auto_: width will be depending on the label length
- _full_: width will be full width of parent container. Renders `.btn-block` class on the button

* Link to page: Creates link behind the button. Select one of the pages published on your website
* Link Override URL: add external url. If added, value of Link to page will be ignored
* Button Label: text label of the button
* HTML Attributes: custom attributes that will be aplied to the pricing column section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Plan Name: name of the plan
* Price: price of the plan
* Unit: Price unit name
* Features: list of features of the plan. Will be rendred in the column body

0. Component - Section
----------------------
Renders a wrapping element that has `.container` and `.row` elements. This is a structured widget which means that other widgets can be placed inside. Usually these will be Component - Column widgets.
Configurable options:
* Tag: html tag that will be rendered.
Options: 
- _section_
- _div_
- _main_
* Width: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options: 
- _fluid_: will output `.container-fluid` class
- _fixed_: will output `.container` class
* HTML Attributes: custom attributes that will be aplied to the container
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`

0. Component - Services Item
----------------------------
Services Item widget is designed to showcase blocks of content with an icon on top. 
Configurable options:
* Width: width of the Services Item section. Corresponds to column numbers in Bootstrap.
Options:
- _1/1_ : full width. Renders `.col-md-12` class 
- _1/2_ : half width. Renders `.col-md-6` class
- _1/3_ : one third width. Renders `.col-md-4` class
- _1/4_: one fourth width. Renders `.col-md-3` class
* Text Alignment: sets the alignemnt of all the text
Options:
- _left_
- _right_
- _center_
- _justify_
* Icon: select which Font Awesome icon to use at the top
* Icon size: size of the icon. These are based on FontAwesome sizes
Options:
- _1x_ : default font size
- _33%_ : large size. Renders `.fa-lg` class on the icon
- _2x_ : double the default size. Renders `.fa-2x` class on the icon
- _3x_: three times the original size. Renders `.fa-3x` class on the icon
- _4x_: four times the original size. Renders `.fa-4x` class on the icon
- _5x_: five times the original size. Renders `.fa-5x`
* Icon animation: applies Font Awesome animation classes to the icon
Options: 
- _none_
- _spin_
- _pulse_
* Icon Rotation: applies Font Awesome rotation classes to the icon
Options:
- _none_
- _90 degrees_
- _180 degrees_
- _270 degrees_
- _flip horizontal_
- _flip vertical_
* Display Read More Button: controls display of read more button
Options:
- _yes_
- _no_
* Button Color: Applies bootstraps default color classes. If Display Read More Button is set to no, this configuration will be ignored.
Options:
- _default_: renders `.btn-default` class
- _primary_: renders `.btn-primary` class
- _success_: renders `.btn-success` class
- _info_: renders `.btn-info` class
- _warning_: renders `.btn-warning` class
- _danger_: renders `.btn-danger` class
- _link_: renders `.btn-link` class
* Button Size: Applies bootstraps default sizing classes. If Display Read More Button is set to no, this configuration will be ignored.
Options:
- _default_ : no size class will be applied
- _large_ : renders `.btn-lg` class
- _small_ : renders `.btn-sm` class
- _extra small_ : renders `.btn-xs` class

* Button width: Controlls the width of the button. If Display Read More Button is set to no, this configuration will be ignored.
- _auto_: width will be depending on the label length
- _full_: width will be full width of parent container. Renders `.btn-block` class on the button

* Link to page: Creates link behind the button. Select one of the pages published on your website. If Display Read More Button is set to no, this configuration will be ignored.
* Link Override URL: add external url. If added, value of Link to page will be ignored. If Display Read More Button is set to no, this configuration will be ignored.
* Button Label: text label of the button. If Display Read More Button is set to no, this configuration will be ignored.
* HTML Attributes: custom attributes that will be aplied to the pricing column section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Article: select article to display based on title

0. Component - Social Media Links
---------------------------------
Displays row of social media links and corresponding icons
Configurable options:
* Icon size: size of the social media icons. These are based on FontAwesome sizes
Options:
- _1x_ : default font size
- _33%_ : large size. Renders `.fa-lg` class on the icon
- _2x_ : double the default size. Renders `.fa-2x` class on the icon
- _3x_: three times the original size. Renders `.fa-3x` class on the icon
- _4x_: four times the original size. Renders `.fa-4x` class on the icon
- _5x_: five times the original size. Renders `.fa-5x`
* Facebook URL: renders the url to the Facebook profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Twitter URL: renders the url to the Twitter profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* LinkedIn URL: renders the url to the LinkedIn profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Pinterest URL: renders the url to the Pinterest profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Behance URL: renders the url to the Behance profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Dribble URL: renders the url to the Dribble profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* GitHub URL: renders the url to the GitHub profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Website URL: renders the url to the Website behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Email: renders the email portion of the href atribute behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty

0. Event collection
---------------------
Displays collection of events based on the category and/or location. Should be placed on pages that display events collections.
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
* Event collection: default options for event collection
Options:
- _category_: select categories of articles to include
- _location_: select types of articles to include
- _per page_: number of articles to display per page
- _results page_: page which will be used to display single article when read more link is clicked

0. Event Result
-----------------
Displays event from a collection on a single page. Should be placed on a _results page_ that will display single events when read more links are clicked within the event collection. Besides the event content this widget also renders Google Map with marker placed at the location of the event. When clicked, marker will display infowindow with locations name and description. IMPORTANT NOTICE: in order to load Google Maps API you must add Google Maps API widget inside your layout, to load the API on each page or on a single page to load it only on that page.
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
* Date and Time format: controls format of events start and end date and time
Options:
- _dd/mm/yy HH:MM am/pm_
- _dd/mm/yy HH:MM_
- _Tmm/dd/yy HH:MM am/pm_
- _mm/dd/yy HH:MM_
* Related Events: controls display of related events collection below the event. Related events are generated based on the category or location of the article displayed
Options: 
- _none_ 
- _By Category_
- _By Location_
* HTML Attributes: custom attributes that will be aplied to the container section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Zoom level: zoom level of the map. Correspods with the Google Maps API values
* Disable Default Google Maps Controls: controls display of Google Maps controls
Options: 
- _yes_
- _no_
* Zoom on scroll: controlls whether zoom level of the map can be changed with the mouse scroll.
Options:
- _yes_
- _no_

0. Event
--------
Selects and displays a single event content and renders the Google Map with marker pointing to events location. IMPORTANT NOTICE: in order to load Google Maps API you must add Google Maps API widget inside your layout, to load the API on each page or on a single page to load it only on that page.
Configuration options:
* Width: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options: 
- _fluid_: will output `.container-fluid` class
- _fixed_: will output `.container` class
* Show Featured Image: controls display of events featured image at the top of the event
Options: 
- _yes_
- _no_
* Show Category: controls display of articles category
Options: 
- _yes_
- _no_
* Date and Time format: controls format of events start and end date and time
Options:
- _dd/mm/yy HH:MM am/pm_
- _dd/mm/yy HH:MM_
- _Tmm/dd/yy HH:MM am/pm_
- _mm/dd/yy HH:MM_
* Related Events: controls display of related events collection below the event. Related events are generated based on the category or location of the article displayed
Options: 
- _none_ 
- _By Category_
- _By Location_
* HTML Attributes: custom attributes that will be aplied to the container section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`
* Event: select an event to display based on title
Options:
- _event_: event title
- _results page_: page which will be used to display single event when read more link is clicked
* Zoom level: zoom level of the map. Correspods with the Google Maps API values
* Disable Default Google Maps Controls: controls display of Google Maps controls
Options: 
- _yes_
- _no_
* Zoom on scroll: controlls whether zoom level of the map can be changed with the mouse scroll.
Options:
- _yes_
- _no_

0. FontAwesome Icon
-------------------
Displays single FontAwesome icon.
Configurable options:
* _Icon_: select the icon by name

0. Footer
---------
Displays footer bar with navigation and social media links.
Configurable options:
* _Navbar Color_: Bootstraps default navigation color variations
Options:
- _default_: renders `.navbar-default` class
- _inverse_: renders `.navbar-inverse` class
* Container width: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options:
- _fluid_: will output `.container-fluid` class
- _fixed_: will output `.container` class
* Navbar Position: position of the navigation
- _default_: no class will be applied
- _fixed to top_: navigation will be fixed to top. Renders `.navbar-fixed-top` class
- _fixed to bottom_ : navigation will be fixed to bottom. Renders `.navbar-fixed-bottom` class
* Navigation Links Float: float of the navigation links
Options:
- _left_: links will float left. Renders `.navbar-left` class
- _right_: links will float right. Renders `.navbar-right` class
* Icon size: size of the social media icons. These are based on FontAwesome sizes
Options:
- _1x_ : default font size
- _33%_ : large size. Renders `.fa-lg` class on the icon
- _2x_ : double the default size. Renders `.fa-2x` class on the icon
- _3x_: three times the original size. Renders `.fa-3x` class on the icon
- _4x_: four times the original size. Renders `.fa-4x` class on the icon
- _5x_: five times the original size. Renders `.fa-5x`
* Facebook URL: renders the url to the Facebook profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Twitter URL: renders the url to the Twitter profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* LinkedIn URL: renders the url to the LinkedIn profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Pinterest URL: renders the url to the Pinterest profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Behance URL: renders the url to the Behance profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Dribble URL: renders the url to the Dribble profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* GitHub URL: renders the url to the GitHub profile behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Website URL: renders the url to the Website behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Email: renders the email portion of the href atribute behind the corresponding FontAwesome icon. Icon and link will not be rendered if the field is empty
* Copyright Text: text that will be rendered as a copyright text

0. Gallery
----------
Displays unroole galleries.
Configurable options:
* Container width: width of the container. Correspodns with Bootstraps fluid and fixed containers. 
Options: 
- _fluid_: will output `.container-fluid` class
- _fixed_: will output `.container` class
* Display Caption: controlls display of the caption for each image
Options:
- _yes_
- _no_
* Grid Colums on Devices Above 1200px: number for `.col-lg-` class that will be applied to each image in the gallery
* Grid Colums on Devices Above 992px: number for `.col-md-` class that will be applied to each image in the gallery
* Grid Colums on Devices Above 768px: number for `.col-sm-` class that will be applied to each image in the gallery
* Grid Colums on Devices Below 768px: number for `.col-xs-` class that will be applied to each image in the gallery
* Gallery: select which unroole galery to display by gallery title

0. Glyphicon
------------
Displays single Glyphicon icon
Configurable options:
* _Icon Name_: select the icon by name

0. Google Maps API
------------------
Loads Google Maps API. Should be placed in Layout, to load the API on each page or on a single page to load it only on that page.
Configurable options:
* Google Maps API Key: your Google Maps API key

0. Hero Section
---------------
Displays Bootstraps Jumpotron with additional elements. This is a structured widget which means that other widgets can be placed inside and they will be rendered below the button
Configurable options:
* Choose a Background Image: select an image already uploaded to unroole assets as a background of the Hero Section
* Title Caption: text that will be outputted in the title
* Body Caption: text that will be outputted in the body
* Content position: text alignemnt of all content
Options:
- _Center_
- _Left_
- _Right_
* Text Color: color of the captions text
Options:
- _Default_ : default theme text color
- _White_
* Button Color: Applies bootstraps default color classes
Options:
- _default_: renders `.btn-default` class
- _primary_: renders `.btn-primary` class
- _link_: renders `.btn-link` class
* Link to page: Creates link behind the button. Select one of the pages published on your website
* Link Override URL: add external url. If added, value of Link to page will be ignored
* Button Label: text label of the button
* HTML Attributes: custom attributes that will be aplied to the Hero section. 
Options: 
- _tag_: id of the section 
- _classes_: classes of the section 
- _attributes_: custom attributes, ie. `data-foo="bar"`

0. HTML Layout Header
---------------------
Renders `<head>` portion of the page. This widget will output page meta description, title and keywords in appropriate meta tags. Also it will output the code that is placed in HTML Page Header widget. This widget doesn't accept any configurations.

0. HTML Page Header 
-------------------
Used to output custom code to the `<head>` tag of the page it was used in. This is a structured widget which means that it accepts child widgets. Usually you would place Code system widget with the code you would like to be appended to the `<head>` tag of that page.

0. Image
--------
Dsiplays single image uploaded to assets
Configurable options:
* Image Shape: controls display shape of featured image
Options:
- _default_: no styling will be aplide
- _rounded_: image will have rounded corners. Renders `.img-rounded` class on image
- _circle_ : image will be rendered as a circle. Renders `.img-circle` class in image
* Is a link: outputs `<a>` tag around image
Options:
- _yes_
- _no_

0. Lead Text
------------
Displays text as Bootstraps lead paragrpah.
Configurable options:
* Text Alignment: sets the alignemnt of all the text
Options:
- _left_
- _right_
- _center_
- _justify_
* Lead text: text to output
