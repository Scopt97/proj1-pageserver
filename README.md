## Author: Kyle Nielsen, kylen@uoregon.edu ##

### What? ###

A simple web server that displays the contents of a specified html or css file is the pages directory. Due to differences in path names, this server is designed to run on Unix based machines and may not work properly on Windows.

### Usage ###

In a terminal: `make run`

In a browser `http://ipaddr:port/path/to/file` 

By default, port is 5000 and path/to/file is relative to pages/ . These can be changed by copying credentials-skel.ini to pageserver/credentials.ini and editing the appropriate fields (port and DOCROOT), or by editing app.ini.



