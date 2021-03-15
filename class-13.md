# local storage
![img](https://elzero.org/wp-content/uploads/2020/05/lab-local-storage.png)
 * is one of the areas where native client applications have held an advantage over web applications.
 * the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.
 * Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data.
 * they have three potentially dealbreaking downsides:
   * Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
   * Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
   * Cookies are limited to about 4 KB of data — enough to slow down your application.

# LOCAL STORAGE HACKS

## Internet Explorer. 
 * Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer.
 * One of these things was called DHTML Behaviors, and one of these behaviors was called userData.
 * userData: allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
 
## Flash cookies
 * the feature is properly known as Local Shared Objects.
 * it allows Flash objects to store up to 100 KB of data per domain.
 * prototype of a Flash-to-JavaScript bridge called AMASS (AJAX Massive Storage System)
   * it was limited by some of Flash’s design quirks.

## ExternalInterface in Flash 8
 * JavaScript became an order of magnitude easier and faster.
 * Flash gives each domain 100 KB of storage “for free.”
 * it prompts the user for each order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).

##  Gears
 * an open source browser plugin aimed at providing additional capabilities in browsers.
 * provides an API to an embedded SQL database based on SQLite. 
 * Gears can store unlimited amounts of data per domain in SQL database tables.

# HTML5 STORAGE
 * is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification.
 * it’s a way for web pages to store named key/value pairs locally, within the client web browser.
 * this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.
 * From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.

## USING HTML5 STORAGE
 * You store data based on a named key, then you can retrieve that data with the same key.
 * The named key is a string.
 * the data is actually stored as a string.
 * If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() 
   to coerce your retrieved data into the expected JavaScript datatype.
 
 ## LIMITATIONS IN CURRENT BROWSERS
  1) 5 megabytes.
   * is how much storage space each origin gets by default.
   * you’re storing strings, not data in its original format.
   * Each digit in that float is being stored as a character, not in the usual representation of a floating point number.
 
 2) QUOTA_EXCEEDED_ERR
  * is the exception that will get thrown if you exceed your storage quota of 5 megabytes.
  * Some browsers (like Opera) allow the user to control each site’s storage quota, but it is purely a user-initiated action, 
    not something that you as a web developer can build into your web application.

## COMPETING VISIONS
* A new API has been standardized and implemented across all major browsers, platforms, and devices.
* The Web SQL Database specification has been implemented by four browsers and platforms.
  * “SQL” is more of a marketing term than a hard-and-fast standard. 
  * There’s Oracle’s SQL, Microsoft’s SQL, MySQL’s SQL, PostgreSQL’s SQL, and SQLite’s SQL.
  * the object store has no structured query language.


