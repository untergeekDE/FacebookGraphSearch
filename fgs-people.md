## 

### Selecting for gender  ###

* /males
* /females

Expects a list of people, e.g. by searching for names first

### Selecting for age ###

* /X/users-age for users of a certain age [sample](https://facebook.com/search/594399277278367/likers/50/users-age/intersect)
* /X/Y/users-age-2 for users of an age range [sample](https://facebook.com/search/me/friends/19/29/users-age-2/intersect)
*	/X/users-younger/ for users below this age [sample](https://facebook.com/search/4/friends/friends/19/29/users-younger/intersect)
*	/X/users-older/ 

### Selecting for relationship status ###

*	/married/users
*	/engaged/users
*	/single/users
* /widowed/users
* /in-open-relationship/users
* /its-complicated/users
*	/seperated/users
*	/divorced/users
* /in-civil-union/users
*	/dating/users
* /in-any-relationship/users

And, of course:

* /*NAME-ID*/friends/
* /*NAME-ID*/friends/friends/
* /*NAME-ID*/spouses/

up to six levels deep. 

### Employees and employers ###

* /*PAGE-ID*/employees/past [sample]()
* /*PAGE-ID*/employees/present 
* /*PAGE-ID*/students/ (present, past, ever)

To research employers of a person, see [Looking for pages](fgs-pages.md)

String variant:

* /str/PAGE-NAME/pages-named/employees/intersect/ [sample](https://www.facebook.com/search/str/hessenschau/pages-named/employees/intersect/

### Residents ###

* /*PAGE-ID*/residents/present to find people living in X right now
* /*PAGE-ID*/residents/past
*	/*PAGE-ID*/home-residents

### Other ###

* /*PAGE-ID*/speakers/ to identify people who speak a language (C and other programming languages also qualify!)
* /*PAGE-ID*/likers/ to identify fans of a page

See: [Looking for places](fgs-places.md)

## Use an ID, not a string search ##

The search for a name may produce errors - whenever you have exact information on the target, use an ID rather than a string query. 

