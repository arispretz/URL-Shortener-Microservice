# URL-Shortener-Microservice
This is one of my projects in the way to achieve "Back End Development and APIs" certification at freeCodeCamp.org. It was designed using Nodejs and Express. 
In this project, when opening the live view, you must enter a URL to shorten it, simplifying and optimizing the management and sharing of links online.
Tests:
You can POST a URL to /api/shorturl and get a JSON response with original_url and short_url properties. Here's an example: { original_url : 'https://freeCodeCamp.org', short_url : 1}
Waiting:When you visit /api/shorturl/<short_url>, you will be redirected to the original URL.
Waiting:If you pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain { error: 'invalid url' }
HINT: Do not forget to use a body parsing middleware to handle the POST requests. Also, you can use the function dns.lookup(host, cb) from the dns core module to verify a submitted URL.
