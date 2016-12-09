# Environment Setup

Backbone.js is very easy to setup and work. This chapter will discuss about download and setup of Backbone.js library. Backbone.js can be used in two ways:

* Downloading UI library from its official website.

* Downloading UI library from CDNs


## Downloading UI library from its official website

When you open the link [http://backbonejs.org/](http://backbonejs.org/), you will get to see a screen as below:

As you can see, there are three options for download of this library:

* Development Version - Right click on this button and save as and you get full source JavaScript library.

* Production Version - Right click on this button and save as and you get Backbone-min.js library file which is packed and gzipped.

* Edge Version - Right click on this button and save as and you get an unreleased version i.e development is going on, hence you need to use it at your own risk.


### Dependencies

Backbonejs depends on the following javascript files:

* Underscore.js : This is the only hard dependency which needs to be included. You can get it from here

* jQuery.js : Include this file for RESTful persistence, history support via Backbone.Router and DOM manipulation with Backbone.View. You can get it from here


* json2.js : Include this file for older Internet Explorer support. You can get it from here

## Download UI Library from CDNs

A CDN or Content Delivery Network is a network of servers designed to serve files to users. If you use a CDN link in your web page, it moves the responsibility of hosting files from your own servers to a series of external ones. This also offers an advantage that if the visitor to your webpage has already downloaded a copy of Backbone.js from the same CDN, it won't have to be re-downloaded.



As said above, Backbone.js has dependency of following javascript:

* jQuery

* Underscore


**CDN for all the above is as follows:**

```
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js"></script>
<script type="text/javascript" src="https://ajax.cdnjs.com/ajax/libs/underscore.js/1.1.4/underscore-min.js"></script>
<script type="text/javascript" src="https://ajax.cdnjs.com/ajax/libs/backbone.js/0.3.3/backbone-min.js"></script>
```

## Example









