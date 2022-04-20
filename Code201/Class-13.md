# Local Storage for Web Applications

[Home](../index.md)

## Web Application limitations

Web application as opposed to native programs are historically severly limited in the amount of local storage infrastructure provided to them. Cookies were one of the first ways to store data locally within a browser but are slow create needless transfer of data via HTTP requests, and have a very small maximum amount of data that can be stored. Thankfully HTML5 provided a solution, but before we get there lets examine some previous methods used to remedy this issue.

userData, FlashCookies, Gears were attempts to do this, however all of them were either browswer specific or relied on third-party plugins.

## HTML5 Storage

HTML5 provided a standardized Web Storage API for web pages to store key value pairs locally, within the browser. The data continues to exist even after you navigate away from the webpage, and even exit the browser! However unlike cookies it is never transmitted to the web server unless explicitly told to do so. All data retrieved from local storage is represented by strings. You can use `getItem()`/`setItem()` or simply use JavaScript bracket notation. You can also us the storage event to interact with the code.

Now with local storage the browser gets 5 MB by default. As of February 2011 you could not ask the user for more data in your application.

## Future Visions (As of Feb 2011)

Google has been working on an open source browser plugin based on SQL which then influenced the advent of the Web SQL Database specification.

> This specification has reached an impasse: all interested implementors have used the same SQL backend (Sqlite), but we need multiple independent implementations to proceed along a standardisation path. Until another implementor is interested in implementing this spec, the description of the SQL dialect has been left as simply a reference to Sqlite, which isn't acceptable for a standard.

Also the Indexed Database API is a vision for local storage on Websites of the Future.
