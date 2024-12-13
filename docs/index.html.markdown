---
layout: default
title: CommonJS API
---

CommonJS
========

* JS
  * == powerful OO language /
    * one of the fastest dynamic language interpreters
  * official JS specification
    * defines APIs / 
      * uses
        * build browser-based applications 
    * ❌NOT define a standard library ❌
      * uses
        * build a broader range of applications

* CommonJS API
  * define APIs /
    * handle many common application needs
  * 💡define a standard library 💡
    * 's rich == Python, Ruby and Java's standard libraries rich 
  * goal
    * write an application -- via -- CommonJS APIs
    * run this application | DIFFERENT JS interpreters & host environments 
  * allows
    * writing
      * Server-side JS applications
      * CL tools
      * Desktop GUI-based applications
      * Hybrid applications (Titanium, Adobe AIR)

* see [additional introduction](http://arstechnica.com/web/news/2009/12/commonjs-effort-sets-javascript-on-path-for-world-domination.ars)
* versions
  * Current [0.1](specs/0.1.html)
  * development: [0.5](specs/0.5.html)
    
Implementations
---------------

<table id="implementations" class="tablesorter">
  <thead>
  <tr><th>Project</th><th>API Version</th><th>Interpreter</tr>
  </thead>
  <tbody>
  <tr><td><a href="impl/narwhal.html">Narwhal</a></td><td>0.1+</td><td><a href="interp/rhino.html">Rhino</a>, <a href="interp/mozilla.html">Mozilla</a></td></tr>
  <tr><td><a href="impl/v8cgi.html">v8cgi</a></td><td>0.1+</td><td><a href="interp/v8.html">v8</a></td></tr>
  <tr><td><a href="impl/helma.html">Helma</a></td><td>0.1+</td><td><a href="interp/rhino.html">Rhino</a></td></tr>
  <tr><td><a href="impl/persevere.html">Persevere</a></td><td>0.1+</td><td><a href="interp/rhino.html">Rhino</a></td></tr>
  <tr><td><a href="impl/gpsee.html">GPSEE</a></td><td>0.1+</td><td><a href="interp/spidermonkey.html">SpiderMonkey</a></td></tr>
  <tr><td><a href="impl/flusspferd.html">Flusspferd</a></td><td>0.1+</td><td><a href="interp/spidermonkey.html">SpiderMonkey</a></td></tr>
  <tr><td><a href="impl/monkeyscript.html">MonkeyScript</a></td><td>0.0</td><td><a href="interp/rhino.html">Rhino</a></td></tr>
  </tbody>
</table>
    
More information about CommonJS
-------------------------------

* [Group Process](process.html)
* [Project History](history.html)
