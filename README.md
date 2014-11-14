meerkat_webservice_schema
=========================

This repository serves as document control for the Yodlee Meerkat Webservice API.

##JSend
Our API takes advantage of the [JSend] (http://labs.omniti.com/labs/jsend) standard.
This means that our response returns an object containing both:
** status -('success', 'fail', or 'error')
** data - everything else

That is the standard for JSON API responses. The Yodlee node.js framework as well as other JSON APIs throughout yodlee use the JSend format. 
