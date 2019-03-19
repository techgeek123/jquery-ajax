## Release 0 : Create a webpage lists data from XML files

We're going to pull data from ana XML file into our webpage just like in CoreBlock-01 but we're also going to work with the Gogole Maps API to list maps for each item we add to our webpage 

- Create an empty webpage.
- Use AJAX (via raw JS API or jQuery) to load the file `restaurants.xml` into your page.
- Create a `<ul>`. For each `<restaurant>`, create an `<li>` with the name and address of the restaurant. Change the color of the text depending on the type of the restaurant (“sitdown” or “bar”).
- Link each address to Google Maps.
- Use the [Google Static Maps API](https://developers.google.com/maps/documentation/static-maps/) to render a map for each restaurant.