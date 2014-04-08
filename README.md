heartbleed-detect.js
====================

Scans your servers to see if they are vulnerable to heartbleed. 

See http://heartbleed.com/ for the scary details. 

**This is not a robust scan!** It simply connects to your web server, checks to see what version of OpenSSL your web server says it is using, and reports whether or not it is vulnerable. Security-conscious individuals will have already configured their web servers to omit information about the OpenSSL version from their web server headers, which will make this script useless.
