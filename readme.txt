﻿=== Posts By Tag ===
Contributors: sudar 
Tags: posts, sidebar, widget, tag, cache
Requires at least: 2.8
Tested up to: 2.8.2
Stable tag: 0.2
	
Provide sidebar widgets that cna be used to display posts from a set of tags in the sidebar.

== Description ==

Posts By Tag WordPress Plugin, provides sidebar widgets which can be used to display posts from a specific set of tags in the sidebar.

The Plugin caches the posts of each widget separately, and issues database queries only when needed. This will reduce the amount of database queries involved for each page load and will therefore be light on your server.

### Features

Posts By Tag Plugin provides a sidebar widget which can be configured to display posts from a set of tags in the sidebar. You can have multiple widgets with different set of tags configured for each one of them.

Each widget allows you to choose

*   The set of tags whose posts should be displayed 
*   The number of posts to be displayed. 
*   Option to enable post excerpts to be displayed with post titles. 
*   Option to display post thumbnail if present.

In addition to using the widget, you can also use the following template function to display posts from a set of tags, anywhere in the theme

posts_by_tag($tags, $num, $excerpt = false, $thumbnail = false);


*   $tags (string) - set of comma seperated tags
*   $num (number) - number of posts to display
*   $excerpt (bool) - To display post excerpts or not
*   $thumbnail (bool) - To display post thumbnails or not

### Translation

*   Swedish (Thanks Gunnar Lindberg Årneby)

The pot file is available with the Plugin. If you are willing to do translation for the Plugin, use the pot file to create the .po files for your language and let me know. I will add it to the Plugin after giving credit to you.

### Support

Support for the Plugin is available from the [Plugin's home page][1]. If you have any questions or suggestions, do leave a comment there.

 [1]: http://sudarmuthu.com/wordpress/posts-by-tag

### Vote for this Plugin

If you like this Plugin, please vote for it at [WordPress Plugin blog][1] and help me win the [WordPress Plugin Competition][2].

 [1]: http://weblogtoolscollection.com/pluginblog/2009/07/28/posts-by-tag-wordpress-plugin/
 [2]: http://sudarmuthu.com/blog/2009/05/23/wordpress-plugin-competition-2009.html
	
== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page. You should see a new widget called "Tag Posts" in the widgets pages, which you can drag and drop in the sidebar of your theme.
== Changelog ==
### Changelog

**v0.1 (2009-07-26)  

*   Initial Version

**v0.2 (2009-08-02)  

*   Added template functions
*   Added Swedish translation (Thanks Gunnar Lindberg Årneby)

==Readme Generator== 

This Readme file was generated using <a href = 'http://sudarmuthu.com/projects/wp-readme.php'>wp-readme</a>, which generates readme files for WordPress Plugins.