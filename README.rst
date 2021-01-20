===============
ckanext-pdfview
===============

This extension provides a view plugin for PDF files using `PDF.js <https://mozilla.github.io/pdf.js/>`_.

Beyond viewing PDFs, this version takes advantage of the latest PDF.js features that were not available in the bundled pre 2.3 viewer, namely:

* Localization. Uses CKAN's language settings when possible.
* Tools Menu. Go to first/last page. Rotate clockwise/counter-clockwise. Hand tool. Document Properties.
* Fullscreen support.
* PDF attachment support.
* Performance. Renders PDFs much faster in browsers with `WebGL <http://caniuse.com/#feat=webgl>`_ and `Web Worker <http://caniuse.com/#feat=webworkers>`_ support.
* Implements `hundreds of PDF.js bug fixes <https://github.com/mozilla/pdf.js/compare/b996e1b...72cfa36b06f15ce12c6c210c68465a1e4d48c36e>`_
* Updated from `ckanext-pdfview` to work with CKAN 2.9

-----------------
Running the Tests
-----------------

To run the tests, do::

    nosetests --nologcapture --ckan --with-pylons=test.ini

