# Mendeley Vanilla JS Implicit authorization flow example

Loads `doi` from the url query parameters. After logging into Mendeley, fetches catalog record for the doi and displays title

e.g. https://josephguillaume.github.io/mendeley-api-vanilla-js-example/?doi=10.1016/j.molcel.2009.09.013

To use locally, register at https://dev.mendeley.com/ and edit `client_id` and `redirect_uri` - which should be the URL at which `index.html` is hosted.
