Select2-to-Tree
=======

Select2-to-Tree is an extension to the popular select boxes library: Select2 (https://github.com/select2/select2).

Though Select2 is very versatile, it only supports a single level of nesting. See https://select2.github.io/options.html#how-many-levels-of-nesting-are-allowed
<blockquote>
How many levels of nesting are allowed?<br>
Because Select2 falls back to an <optgroup> when creating nested options, only a single level of nesting is supported. Any additional levels of nesting is not guarenteed to be displayed properly across all browsers and devices.</blockquote>

Select2-to-Tree aims to ...

Use cases
---------
* Enhancing native selects with search.
* Enhancing native selects with a better multi-select interface.
* Loading data from JavaScript: easily load items via AJAX and have them
  searchable.

Browser compatibility
---------------------
* IE 8+
* Chrome 8+
* Firefox 10+
* Safari 3+
* Opera 10.6+

Usage
-----
You can source Select2 directly from a CDN like [JSDliver][jsdelivr] or
[CDNJS][cdnjs], [download it from this GitHub repo][releases], or use one of
the integrations below.

Integrations
------------
Third party developers have create plugins for platforms which allow Select2 to be integrated more natively and quickly. For many platforms, additional plugins are not required because Select2 acts as a standard `<select>` box.


Missing an integration? Modify this `README` and make a pull request back here to Select2 on GitHub.

Internationalization (i18n)
---------------------------
Select2 supports multiple languages by simply including the right language JS
file (`dist/js/i18n/it.js`, `dist/js/i18n/nl.js`, etc.) after
`dist/js/select2.js`.

Missing a language? Just copy `src/js/select2/i18n/en.js`, translate it, and
make a pull request back to Select2 here on GitHub.

Community
---------
You can find out about the different ways to get in touch with the Select2
community at the [Select2 community page][community].

Copyright and license
---------------------
The license is available within the repository in the [LICENSE][license] file.
