Select2
=======
[![Build Status][travis-ci-image]][travis-ci-status]

Select2 is a jQuery-based replacement for select boxes. It supports searching,
remote data sets, and pagination of results.

To get started, checkout examples and documentation at
https://select2.github.io/

Use cases
---------
* Enhancing native selects with search.
* Enhancing native selects with a better multi-select interface.
* Loading data from JavaScript: easily load items via AJAX and have them
  searchable.
* Nesting optgroups: native selects only support one level of nesting. Select2
  does not have this restriction.
* Tagging: ability to add new items on the fly.
* Working with large, remote datasets: ability to partially load a dataset based
  on the search term.
* Paging of large datasets: easy support for loading more pages when the results
  are scrolled to the end.
* Templating: support for custom rendering of results and selections.

Browser compatibility
---------------------
* IE 8+
* Chrome 8+
* Firefox 10+
* Safari 3+
* Opera 10.6+

Select2 is automatically tested on the following browsers.

[![Sauce Labs Test Status][saucelabs-matrix]][saucelabs-status]

Usage
-----
You can source Select2 directly from a CDN like [JSDliver][jsdelivr] or
[CDNJS][cdnjs], [download it from this GitHub repo][releases], or use one of
the integrations below.

Integrations
------------
Third party developers have create plugins for platforms which allow Select2 to be integrated more natively and quickly. For many platforms, additional plugins are not required because Select2 acts as a standard `<select>` box.

Plugins

* [Django]
  - [django-autocomplete-light]
  - [django-easy-select2]
  - [django-select2]
* [Meteor] - [meteor-select2]
* [Ruby on Rails][ruby-on-rails] - [select2-rails]
* [Wicket] - [wicketstuff-select2]
* [Yii 2][yii2] - [yii2-widget-select2]

Themes

- [Bootstrap 3][bootstrap3] - [select2-bootstrap-theme]
- [Flat UI][flat-ui] - [select2-flat-theme]
- [Metro UI][metro-ui] - [select2-metro]

Missing an integration? Modify this `README` and make a pull request back here to Select2 on GitHub.

Internationalization (i18n)
---------------------------
Select2 supports multiple languages by simply including the right language JS
file (`dist/js/i18n/it.js`, `dist/js/i18n/nl.js`, etc.) after
`dist/js/select2.js`.

Missing a language? Just copy `src/js/select2/i18n/en.js`, translate it, and
make a pull request back to Select2 here on GitHub.

Documentation
-------------
The documentation for Select2 is available
[through GitHub Pages][documentation] and is located within this repository
in the [`docs` folder][documentation-folder].

Community
---------
You can find out about the different ways to get in touch with the Select2
community at the [Select2 community page][community].

Copyright and license
---------------------
The license is available within the repository in the [LICENSE][license] file.
