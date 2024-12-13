https://wiki.commonjs.org/wiki/Introduction

* Server side JS
  * very fragmented 
  * script / accesses files can NOT be used WITHOUT modifying rhino & v8 
  * Spidermonkey & JavaScriptCore can NOT both load | additional modules & SAME way
  * see [this blog](https://www.blueskyonmars.com/2009/01/29/what-server-side-javascript-needs/)

* JS web framework
  * VERY tied to its interpreter
  * forced to create a bunch of APIs

* goal of this project
  * create a standard library / allow web developers to
    * choose
      * web frameworks
      * tools
    * run that code | MOST sense platform

* see
  * [other blog](https://bannister.us/weblog/2006/revisiting-server-side-javascript)
