# Church Center Form Embedder
Adds the Planning Center Online Church Center Modal javascript to a WordPress site.

To make any Church Center form work as a modal popup rather than a URL to a seperate webpage there are two options.

## First Method
The first method is to add the approrpiate field to the HTML URL tag:
````
<a href="church-center-form-URL" data-open-in-church-center-modal="true">Link to form</a>
````
## Second Method
Alternatively you can add the modal option as a parameter to the URL of the link itself:
````
<a href="church-center-form-url?open-in-church-center-modal=true">Link to form</a>
````
