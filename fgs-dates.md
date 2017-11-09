## Usage ##

/search/*DATE-ID*/date/ 

selects objects that are associated with that date. 

Sometimes, it takes more than one date descriptor to select a date - in that case, you have to tell Graph Search how many parameters your date contains by an addendum stating the number of parameters: 

* /search/jun/2016**/date-2**
* /search/may/5/2017**/date-3**


Strangely enough, adding another number is interpreted as a year and is looking for a range. https://www.facebook.com/search/2011/10/date-2/stories/ actually finds stories from 2010 to 2011. 


## Date descriptors ##

These date descriptors are allowed: 
* year - /2017/date
* day - /21/date/
* This week/month/year - /this-month/date
* Last week/month/year - /last-year/date
* Next week/month/year - /next-year/date
* Last, this, next day - /yesterday/date, /today/date, /tomorrow/date
* In the past - /in-past/date
* In the future - /in-future/date
* Recently - /recent/date
* Month by name, 3-digit code: jan, feb, mar, apr...
## Selecting the right type of data ##

Data returned has no type yet; to process it further, you have to tell Unicorn what it has to select from these dates. If, for example, you try to select an event by date, you have to declare it as events - *see: [Looking for events](fgs-events.md)* and *[Looking for posts](fgs-posts.md)*

* /search/this-week/date/events 
* /search/this-week/date/stories

## Date ranges ##

Needs researching. 
