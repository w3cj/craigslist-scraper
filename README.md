# Craigslist Pro

* [ ] Scrape craigslist results
  * [ ] /search/:location/:search_term
    * e.g:
      * https://columbus.craigslist.org/search/sss?sort=date&query=korg
        * /search/columbus/korg
      * https://columbus.craigslist.org/search/sss?sort=date&query=synth
        * /search/columbus/synth
* [ ] Dashboard view
  * [x] Add search terms (tags)
  * [x] View all results in a list
    * [x] Title
    * [x] Image
    * [x] Price
    * [x] Location
  * [x] Show loading image/progress bar
  * [x] Click a result to go to the craigslist page
    * [x] API send back the craigslist id or url
  * [x] Hide a result
  * [ ] Mark a result as favorite
