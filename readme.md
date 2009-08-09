***mini***, a tiny selector engine
---

&copy; [James Padolsey](http://james.padolsey.com)

Dual licensed under the MIT and GPL licenses.

 * http://www.opensource.org/licenses/mit-license.php
 * http://www.gnu.org/copyleft/gpl.html

**Read more: [Introducing “mini”](http://james.padolsey.com/javascript/mini/)**

Usage:

    var pAnchors = mini('p > a'); // Returns an array.
    
    for (var i = 0, l = pAnchors.length; i < l; ++i) {
        // Do stuff...
    }
    
Supported Selectors:

 * `tag`
 * `tag > .className`
 * `tag > tag`
 * `#id > tag.className`
 * `.className tag`
 * `tag, tag, #id`
 * `tag#id.className`
 * `.className`
 * `span > * > b`
    
