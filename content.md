# Example Content Post

## Sources

This page's content is from **content.md** a plain text file written in markdown, while its
page headers, sidebars, etc are defined in **index.html**.

## Processing

The content, in markdown, is rendered and inserted into the page by [*marked.js*](https://marked.js.org)

![Image](marked-logo.svg "icon")

The browser always displays index.html; then Javascript in the index page:

1. Reads in the requested content
1. Converts it to html
1. Inserts it into index page in the 'content' div.

### Markdown

The markdown follows [this spec](https://daringfireball.net/projects/markdown/syntax).
Here's some examples [on wikipedia](https://en.wikipedia.org/wiki/Markdown#Examples)

---

## Development

### Run a server

If run locally the file read will fail with a CORs error.
So run a local server using

    python3 -m http.server

And browse http://0.0.0.0:8000
(lifted from [stackoverflow](https://stackoverflow.com/questions/10752055/cross-origin-requests-are-only-supported-for-http-error-when-loading-a-local))

### Resources

* Discover which page to display:
  * Get the desired content from the url: https://tutorialio.com/get-the-full-url-or-query-string-of-current-page-in-javascript/
  * Can I use: https://caniuse.com/?search=window.location.search
* Examine the resulting html:
  * Marked.js demo page: https://marked.js.org/demo/

