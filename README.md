# Sip First (Project 01)
___

### Design

Our front-end design was meant to spark user interest and interactivity. The design highlights binary user choice, limiting user options, and providing a smaller scope allowing for quicker, more conscise decisions. Our intent for this design choice was to prevent the user from being indundated from too many choices and to aid those in our generation who suffer from "analysis-paralysis".


### Logic

The basic logic flow of this web-based application begins with the user-input. The user inputs their parameters for their search, thus dynamically generating their final search query. That search query, once its parameters are completed, is used to perform an Ajax call to the Yelp API to return a JSON object with data to leveraged for rendering on the page. But before all of our information is rendered onto the page, we take location data from the Ajax call and send a requeste to the Google Maps API to dynamically generate a Javascript map w/ markers according to the location of the businesses received from the Yelp API.

tl;dr...
` [ WEB-CLIENT(input) ==> YELP API ==> GOOGLE API ==> WEB-CLIENT(render) ]`



## Built With

___

* [HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
* [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
* [Google Fonts](https://developers.google.com/fonts/)
* [Animista](http://animista.net/)
* [Codepen](https://blog.codepen.io/documentation/)
* [JQuery](https://api.jquery.com/)
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/tutorial)
* [Yelp API](https://www.yelp.com/developers/documentation/v3/business)
* [cors-axsnywhere](https://cors-anywhere.herokuapp.com/)
* [AJAX](https://api.jquery.com/category/ajax/)
* [Firebase](https://firebase.google.com/docs)

![Graph](graph.png)
___

![Drink Selection Page](screenshot.png)
![Priority Selection Page](screenshot.png)
![Results Page](screenshot.png)
![Google Maps Page](screenshot.png)

[Sip First deployed page](https://djgoldstone.github.io/Sip/)

___

## Authors

* Joanne Badua - [UC Berkeley Extension](https://github.com/joannebadua)
* Christopher Celestino - [UC Berkeley Extension](https://github.com/BAANG)
* Derek Goldstone - [UC Berkeley Extension](https://www.linkedin.com/in/derek-goldstone-482884a3/)
* Minori Hashimoto - [UC Berkeley Extension](https://github.com/minori-fh)



___