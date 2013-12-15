jspwiki contributed plugins
===========================

Alpha - work in progress / use at your own risk


You can find all Plugins contributed to JSPWiki (pre-apache version) on this
archive:  http://www.ecyrd.com/JSPWiki/wiki/JSPWikiPlugins

Plugins converted to the Apache JSPWiki :

TablePlugin
===========

This plugin implements additional table support for JSPWiki pages, such as: 
- multi-line table editing to ease the entry of more complex tables
- markup to merge cells horizontally and/or vertically (aka colspan and rowspan) 
- auto-numbering to automatically insert the row-number
- CSS style for odd/even rows.

Installation Instructions:
- Copy Table.jar to the folder ``/WEB-INF/lib/``  of your web server
- Modify the plugin searchPath in your ``WEB-INF/jspwiki.properties` and 
  make sure there are no spaces between the different entries. Example:  
  
    jspwiki.plugin.searchPath = brushed.jspwiki.tableplugin
  
- Restart JSPWiki

