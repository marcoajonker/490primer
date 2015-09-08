# poptags
Basic website for COMP 490 to show use of CGI

To access the page on my csun site go to
# www.csun.edu/~mj47069/cgi-bin/simple.cgi
you can also add ~mj47069/cgi-bin/simple.cgi?{query} at the end to see what page you get with that request.

all files are in cgi-bin
------
simple.cgi -- cgi script
------
baseindex.html -- landing page
------
queryindex.html -- when you make a query
-------
404.html -- when you make a request with any verb other than 'GET'
-------
490.css -- styling
-------

at first i started with just getting the html going. i slowly updated the cgi script and added styling. I didnt redirect from the root because I didnt understand what exactly was required. I asked the professor, but never got a response to clarify. I was also asked to use the script as a proxy for a remote webserver, but python in the csun bin is not updated so i couldnt use the http req libraries that would be required to do that. I embedded a youtube video and a widget, which gets its info from another server so that will have to do for now. no js for now because i didn't feel like it... The project is complete to my understanding.
