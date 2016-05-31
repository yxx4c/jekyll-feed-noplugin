# jekyll-feed-noplugin
An xml file alternative for jekyll-feed plugin.
A complete Atom Feed, with no plugins and more contoll over the data.

####Extras:

Added <category/>

---------------------------------------------------------------
####Usage:

1.Copy this file (feed.xml) to the base of your Jekyll project.

2.Specify the feed location in _config.yml

---------------------
Config file example.

feed:

  path: feed.xml
  
---------------------

3.Add the data from head.html to your head part of the html file.

4.Your Feed is ready.

Try running Jekyll now.


PS: Do not use jekyll-feed with this alternative. Make sure you updated your _config.yml and head data in your html file(or head.html in _include folder).
