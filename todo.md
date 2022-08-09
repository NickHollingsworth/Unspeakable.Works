# Things ToDo To Blogi

### Seperating blog engine from content
* Move to new project called Blogi

### Allow Multiple Sub-Sites Easily
* Can I use subdomains without needing different github projects?

### normal navigation ###
* click on heading to go to (subdomain) home
* make headings have anchors. click on heading to show anchor which you can click on to go there (which you can then bookmark or share). see [tauri](http://github.com/tauri-apps/awesome-tauri)

### Allow html to be generated in the browser and pushed to git ###
* Work out how to push a (dummy text) file to git as a new version
  * **isomorphic-git**? see [this](https://isomorphic-git.org/?utm_source=pocket_mylist) and [this](https://news.ycombinator.com/item?id=22420231&utm_source=pocket_mylist)
  * git http api?
  * github.js [see](https://getpocket.com/read/1074857487) and [this](https://getpocket.com/read/2750385341)

  Is it possible to do this so user can pick git provider?
  * github
  * gitlab
  * own git
  * bit bucket?

### Find a richer markdown syntax converter ###
One thats easy to extend.
And does more out the box.
* marked.js ? my first version uses this) - very extendable but seems really hard (though have not tried looking at source and copying it)
* kramdown - look like it has better syntax. Is it extendable? - but its ruby so wont run in browser.
* Gitlab's markdown is rather nice. See [this](https://about.gitlab.com/handbook/markdown-guide/) I think its kramdown.
* **markdown-it** is js and available via cdn.

### Allow side by side markdown edit and preview ###
* see marked.js example Its probably stealable as it.

### Making Pages Trivial To Edit
* Allow user to edit current page on github (currently hard coded to edit index. MD)
* ~~Allow user to create missing pages on github~~

### Follow Good Blogging Standards
* Put published date on page. Can I work this out from the file system automatically?
* ~~Show a Last Updated date on page~~

### Being search engine friendly
* __Handle the problem of search engines not crawlimg the site because they aren't running the javascript. Is it possible to change the workflow to static site generation by loading and rendering the markdown and then saving that to github as final html from the browser using GitHub.js__
* ~~Add ability to put summary in markdown to populate Meta Description tags for search engines~~
* Get google to index the pages on demand
* Set up google analytics https://neilpatel.com/blog/google-index/
* Do I need a Sitemap for search engines to encourage indexing?. How do I submit it to google etc.
* Do I need a robots.txt for search engines?
* Make page work with facebook and social media. https://www.youtube.com/watch?v=u-tdYTNJUnU
* Use https://search.google.com/search-console?resource_id=sc-domain%3Amusings.uk

### Further out
* What are the benefits of cloudflare over github?
* Add a comments system despite having nothing running on the server!? See [giscus](https://giscus.app/) for examples
* Add an rss feed. Do I need atom too? What else is useful for people to subscribe.
* Add social media sharing links.

### On Android ###
* Check it's easy to: create and edit pages and save with a comment
* think about the merge issues with other machines. Is it practical and simple.
* consider dropping the .md from url. So its easier to edit on a phone.

### Project infrastructure ###
* js.org provide free project page hosting eg blogi.js.free

