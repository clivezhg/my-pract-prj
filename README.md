Select2-to-Tree
=======

Select2-to-Tree is an extension to Select2, a popular select boxes library: https://github.com/select2/select2.

Though Select2 is very versatile, it only supports a single level of nesting. See https://select2.github.io/options.html#how-many-levels-of-nesting-are-allowed:
<blockquote style="font-size:smaller">
How many levels of nesting are allowed?<br>
Because Select2 falls back to an &lt;optgroup&gt; when creating nested options, only a single level of nesting is supported. Any additional levels of nesting is not guarenteed to be displayed properly across all browsers and devices.</blockquote>

Select2-to-Tree extends Select2 to support arbitrary level of nesting.

Browser compatibility
---------------------
* IE 8+
* Chrome 8+
* Firefox 10+
* Safari 3+
* Opera 10.6+

Usage
-----
Firstly, you need to know the usage of Select2: https://github.com/select2/select2
Then, you add the Select2 library (the *.js file & *.css file, currently the version should be 4.0+), and the Select2-to-Tree library (the *.js file & *.css file in the "src" folder) to your HTML document.

There are 2 ways to use Select2-to-Tree:

ot required because Select2 acts as a standard `<select>` box.


Copyright and license
---------------------
The license is available within the repository in the [LICENSE][license] file.
