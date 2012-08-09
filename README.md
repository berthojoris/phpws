# File Streamer (server & client) Sample

### Based on
based on code from [phpws](http://code.google.com/p/phpws/)

### Requirements
- apache & php
- ability to listen on port 12345
- a web browser
- on windows, make sure that the hosts file contains the line with _127.0.0.1 loalhost_

### Tested on
- Windows 7
- with latest [Xampp for Windows](http://www.apachefriends.org/en/xampp-windows.html), a bundled php/apache package for windows, with php 5.4
- Chrome 22, which is the latest

### Prepration
- You can put the php files under /var/www/html in linux or somewhere in htdocs if running on windows
- and create the text file to be streamed called *sendme.txt* in c:\tmp\sendme.txt or /tmp/sendme.txt with the correct read permissions


## Running the server
- go to the directory where the php files are and run php -q demo.php


## Running the client
- open up Chrome
- put [http://localhost/phpws/client1.html](http://localhost/phpws/client1.html) into the address
- follow the instructions on the page