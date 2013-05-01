==== Category Post Shortcode ====

Contributors: ibnuyahya
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R9WS2KA3ZJLCS
Tags: text, php, plugin, shortcode, post list
Requires at least: 2.8
Tested up to: 3.3
Stable tag: 2.4

This plugin is to display post by category in your page/post

== Description ==
This plugin allow you to display post list in your page or post by using shortcode.

* Author: ibnuyahya
* Author URI: [http://www.ibnuyahya.com](http://www.ibnuyahya.com "developers note")
* Copyright: Released under GNU GENERAL PUBLIC LICENSE


== Installation ==

**Install like any other basic plugin:**

1.	Copy the category-post-shortcode folder to your /wp-content/plugins/ folder

2.	Activate the Category Post Shortcode on your plugin-page.


== How to use ==
just put this shortcode in your post or pages

 [cat totalposts="3" category="1,3" thumbnail="true" excerpt="true" ]

* totalposts - your total number of post to display. default is -1
* category   - category id. use comma , for multiple id
* thumbnail_type - set to 'meta' to use custom thumbnail-url meta field, set to 'featured_image' to use the featured image. default is 'meta'
* thumbnail  - set true if you want to display thumbnail. default is false
* thumbnail_height - image size for the thumbnail. default is 130
* thumbnail_width - image size for the thumbnail. default is 130
* date       - set true if you want to display post date. default is false. Uses format set in WordPress Settings > General > Date Format
* excerpt    - set true if you want to display excertp. default is true
* orderby    - your post will order by . default post_date . check http://codex.wordpress.org/Template_Tags/get_posts for detail
* order      - asc | desc

**thumbnail**
* create custom field key as thumbnail-url and put your thumbnail url in the value area or set thumbnail_type to 'featured_image' and set a featured image

**style at your own**
* you need to style your category-post-shortcode plugin in your style.css example

.cat-post{
    width:100%;
}
.cat-post-list{
    display: block;
    margin-bottom: 20px;
    position: relative;

}
.cat-post-images{
    float:left;
    width:140px;
    display:block;
}

.cat-content{
    width:350px;
    float:right;
}
.cat-post-title{
    display: block;
    width:100%;
}
.cat-post-date{
    display: block;
    width:100%;
}
.cat-clear{
    clear:both;
}


4.	more info or sample, please visit http://ibnuyahya.com/wordpress-plugins/category-post-shortcode

== Changelog ==

= 1.0 =
* Initial release

= 2.0 =
* Fixed some bug

= 2.1 =
* Add order parameter

= 2.2 =
* Corrected comment id

= 2.3 =
* add thumbnail size
* get image from post as a thumbnail if no thumbnail-url custom field created.

= 2.4 =
* add option to display the post date


