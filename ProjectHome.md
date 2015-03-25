## GravityScript, By [Joseph Paul Cohen](http://www.josephpcohen.com) ##


This is a general version of the Google Gravity code written by Mr. Doob as a Chrome Experiment.

Just Include this file somewhere inside the body or head tag

`<script src="http://gravityscript.googlecode.com/svn/trunk/gravityscript.js"></script>`

Or run the bookmarklet by setting this as the link in a bookmark and clicking it while on ANY page. NOTE:NOTE:NOTE some browsers will remove the javascript: when you paste this string in the url bar.  You can just add it back in after you paste it.

`javascript:var script = document.createElement("script"); script.src="http://gravityscript.googlecode.com/svn/trunk/gravityscript.js"; document.body.appendChild(script);void(0); `


If you include this script or eval this javascript after the body tag has loaded it will do it's awesome thing.

The standard version waits for a user to move their mouse. This version starts without the mouse moving:

`<script src="http://gravityscript.googlecode.com/svn/trunk/gravityscript-autorun.js"></script>`

or a shortened version

`<script src="http://tinyurl.com/grav-js"></script>`


---


<img src='http://gravityscript.googlecode.com/svn/trunk/gravityscript.png' />

-By Joseph Paul Cohen and others