## The Good: ##

Any place on Facebook will be immediately recognizable by the "Things to do in..." page - and it will tell you its object ID in the URL. 

_Example: _ `https://www.facebook.com/places/Sachen-die-du-in-Munchen-unternehmen-kannst/116045151742857/`

## The Bad ##

As of 2017, you can no longer search for countries. 

Hint by research trainer and Graph Search specialist [Henk van Ess](https://twitter.com/henkvaness): 

``Find the biggest place of each country. For Montenegro it's the capital, which is 109429795749542. For Belgium it's Brussels, which is 108429795855423. Now replace the countries in the formula with the cities, as shown here https://www.facebook.com/…/1084…/residents/present/intersect and your are fine.

## The Ugly ## 

It is not easy to find Munich on Facebook. Try these: 

* Looking for "München" in the search bar, and then clicking on places, won't work.
* [Looking for the str "Munich" in a "places-named" search does not work well](https://www.facebook.com/search/str/munich/places-named/). 
* Looking for the keyword works - but for some reason, [you have to use the selector "keyword_places"](https://www.facebook.com/search/str/munich/keywords_places/). 

## Finding people and content from places ##

You'd normally need a PLACE-ID as an input - see above. Try /str/.../keywords_places/ if you have no exact ID. 

## People living or born there ##

* /*PLACE-ID*/users-birth-place returns users born there
* /*PLACE-ID*/residents (/past or /present) returns users living there (now or in the past)

### Returning content: photos, videos ###

* /*PLACE-ID*/photos-in/
* /*PLACE-ID*/videos-in/
