July, 2018 update: proxify-umd now uses the Rebrandly API rather than the Bitly API.

This is a JavaScript version of [proxify-umd](https://github.com/spurioso/proxify-umd) and as such is more useful in CMSes, LibGuides, or wherever you don't have access to a PHP server.

The script adds a proxy prefix to a URL, shortens the result using Rebrandly, and returns a shortened link.
The resulting link will route the user through the University of Maryland's proxy server for user authentication.

Take a look at a [working example](http://lib.guides.umd.edu/c.php?g=326844&p=2194244)

To adapt to your own library you need to make three changes to proxify-umd.html:

1. Change ```var proxyprefix``` to your own institution's proxy prefix
2. In the $.ajax methond in the rebrandly function, change ```headers.apikey``` to your own Rebrandly API key.
