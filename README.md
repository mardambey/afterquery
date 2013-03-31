afterquery
==========

The fun begins after the serious analysts have gone home.

Afterquery is a pure-client-side javascript tool that downloads jsonp-formatted data from a given URL, applies a configurable series of transformations, and then renders the result as either a data table or a Google Visualizations (gviz) chart.

Although the javascript file happens to be hosted on a server, your data never gets uploaded; your browser handles all the processing steps internally. Also, the permissions to download the jsonp data depends on the cookies in your browser, so you can safely retrieve protected content without granting authorization to an external server.
