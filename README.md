# Analytics regexp builder

Quickly create a pattern matching a list of page titles, with some scraping.

Basically, it
1. gets a list of URL and publication dates
2. scrapes each article's <title>
3. joins the strings as a regexp pattern: ^title 1$|^title 2$ etc.
