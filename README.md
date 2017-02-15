This is a JavaScript version of [proxify-umd](https://github.com/spurioso/proxify-umd) and as such is more useful in CMSes, LibGuides, or wherever you don't have access to a PHP server. 

The script adds a proxy prefix to a URL, shortens the result using Bitly, and returns a bitly link.
The resulting link will route the user through the University of Maryland's proxy server for user authentication.

Take a look at a [working example](http://lib.guides.umd.edu/c.php?g=326844&p=2194244)

To adapt to your own library you need to make two changes:

1. Change ```var proxyprefix``` to your own institution's proxy prefix
2. Change ```var key``` to your own Bitly API key.
3. Change ```var login``` to your own Bitly user name
