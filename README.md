# Classy CATE

CATE, without ~~the~~ as much hurt.

![Classy CATE](https://f.cloud.github.com/assets/510845/117032/1bde6e48-6c18-11e2-9452-0a37d6cd08d6.png "Classy CATE")


## Installation
Install `classy-cate.user.js` as a Userscript in [Chrome](https://www.google.com/intl/en/chrome/browser/) or use [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) in firefox.

- [Allow Third party Chrome Scripts](http://solidsprite.com/2012/08/how-to-install-third-party-userscripts-in-chrome-mac-os-x/)
- [Enabling 3rd Party Chrome user scripts](http://userscripts.org/topics/113176) (OSX)

## Rough TODO List (Please Help)

- **Timetable page**
- **Grades Page**
- Non-Undergrads may experience missing/broken links. I have no idea.
- Prevent CC from destroying non-targeted pages
- Refactor code in functions (couldn't until now)

## Summary of Improvements

- Implemented a Navbar for shortcuts
- Changelog + Version in Nav bar
- Put everything in one row
- Identity laid out better
- Simpler interface for class selection
- Simpler, nicer links for other CATE functionality

## Ideas

- Scrape Timetable page
  - Put below current interface
  - Notify of upcoming deadlines
  - Aggregate links to notes, exercises without jumping around a huge table

## Development

To develop and help improve classy-cate, do the following:

1. run the python HTTPS server with `python serve.py`
2. Modify `classy-cate.user.js` js/css references to refer to the local python server e.g. `https://raw.github.com/PeterHamilton/classy-cate/master/ -> https://localhost:8443/classy-cate.css`
3. Install your modified `classy-cate.user.js` as an Userscript/Greasemonkey extension in Chrome/Firefox.


## References

- [jQuery](http://api.jquery.com/jQuery/) as a Javascript Framework
- [Twitter Bootstrap](http://twitter.github.com/bootstrap/) for pretty CSS
- [Font Awesome](http://fortawesome.github.com/Font-Awesome/) for a breadth of nice scalable icons
