rack-response-readme
====================

A HTTP Response is defined as three components.

 Status Code - A number representing the state of the response.
 
 When a web server responds to your browser, the first thing
 it tells you is how everything went. a 200 response means everything
 is good. A 500 response means the web server broke, sorry. A 400 response
 means that you made a mistake. A 300 response means we're confused.

 It's funny that the web is built on machines communicating their
 status to each other?

 Response Headers - Some metadata that describes the response.
 The web is multimedia. We deliver text, and hypertext, and 
 images, and sound, and video, and binary and lolcatz. Data comes 
 in many forms and we handle it all. To make things easy, we 
 describe the data we deliver. Generally, you have to at least
 specify the type of content your sending back. Sometimes, you have
 to say more.

 Response Body - The actual data we want to send.
 Content is king and it lives in the body of the response. For a web page
 it's a bunch of HTML. For lots of other stuff, it's a bunch of binary data.
 But you already know that all data is just bits and characters, so binary,
 text, images, it's really all the same.
