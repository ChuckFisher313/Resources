# Javascript basics #

## Referencing javascript ##

There are two ways to reference javascript.

>1. Inline

Syntax ` <script> let firstName = 'Chuck'; </script> `

>2. Separate file

Syntax ` <script src='index.js> `

## Placement of script tag ##

Best practice for where to put javascript references is at the bottom of the body tag. This allows the browser to load the HTML first, before loading the javascript. This can potentially help for speed. Sometimes javascript is included inside the header tag as well if the javascript must load before the HTML for some reason.
