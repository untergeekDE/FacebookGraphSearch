Posts are, for some archaic reasons, named **stories** in Unicorn parlance.

## Show posts connected to a user or a list of users ##

See [Looking for people](fgs-people.md).

* /stories-by
* /stories-commented
* /stories-tagged

## Show posts by a page ##

* /*PAGE-ID*/stories-by/

### Looking for a keyword in posts from one page: ###

* /*PAGE-ID*/stories-by/str/keywords_posts/intersect [sample](https://www.facebook.com/search/122816404437089/stories-by/str/bouffier/keywords_posts/intersect)

Don't try this with double str search, e.g. searching for keywords in /str/*KEYWORD*/pages-named/ - only the last str query will work.

## Show posts connected to a place or a list of places ##

* /stories-in

## Selecting by keyword ##

In connection with the string selection method - [See the section on selecting objects by name.](../../wiki/The-basic-Graph-Search-grammar#selecting-by-name)

These should be identical but they are not: 

* /str/*KEYWORD*/stories-keyword
* /str/*KEYWORD*/keywords_posts seems to return more. 

## Other ##

* /stories-topic  
* /stories-live
* /stories-public
* /stories-recent
