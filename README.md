JSPWiki contributed plugins
===========================

You can find all Plugins contributed to JSPWiki (pre-apache version) on this
archive:  http://www.ecyrd.com/JSPWiki/wiki/JSPWikiPlugins

Plugins on this repository have been converted to the Apache JSPWiki.


TablePlugin
===========

This plugin implements additional table support for JSPWiki : 
- multi-line table markup to ease the entry of more complex tables
- support for merging cells horizontally or vertically (aka colspan and rowspan) 
- auto-numbering to automatically insert row-numbers
- CSS styling for table-cells, odd/even row coloring, etc..

Installation Instructions:
- Copy `Table.jar` to the folder `/WEB-INF/lib/`  of your web server
- Modify the plugin search path in your `WEB-INF/jspwiki.properties` and 
  make sure there are no spaces between the different entries. Example:  
  
         jspwiki.plugin.searchPath = brushed.jspwiki.tableplugin
  
- Restart JSPWiki



