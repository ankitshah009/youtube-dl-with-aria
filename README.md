Youtube-dl-with-aria
===============
A wrapper that speeds up youtube-dl downloads by utilising aria2's
capability of opening multiple connections per server. This uses a lot of bandwidth so be careful.

Please refer the following post for initial setup http://ankitshah009.blogspot.in/2015/04/download-youtube-videos-faster-in-linux.html

Dependencies
============
 * youtube-dl (http://rg3.github.io/youtube-dl/)
 * aria2 (http://aria2.sourceforge.net/)
Installation of both these utility is pretty standard. Google to find out the installation

Usage
=====

The below will work if youtube-dl is correctly setup

bash youtube-dl-with-aria.sh URL


