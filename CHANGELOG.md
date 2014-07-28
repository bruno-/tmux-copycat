# Changelog

### master
- update video script
- update readme and invite for code contributions
- update dockerfile with it's purpose
- add test suite `README` file
- add screencast original document to git
- add video directory `README` file
- update readme to reflect github organization change

### v0.0.5, Jul 24, 2014
- improve stored file matching search
- fix wrong result highlighting for lines that have \r, \n chars
- another improvement to file matching search: changed regex strategy to be
  "inclusive"
- add test suite
- update readme to show how test suite is started

### v0.0.4, Jul 9, 2014
- bugfix for incorrect result highlighting
- optimize and improve the function that centers the result vertically on the
  screen
- fix OS X awk bug: awk variable content can't start with `=` char
- fix a bug with wrong result highlighting caused by using `printf`
- fix a bug with wrong result highlighting caused by a bug in OSX `grep`
- improve URL matching regex. Matches don't include quotes anymore.

### v0.0.3, Jun 29, 2014
- add notifications about the first and last match
- improve "jump correction" handling by fetching the precise window height
- improve result vertical centering & fix a related bug

### v0.0.2, Jun 26, 2014
- search results are always at the bottom of the page. If possible center the
  result, or provide maximum possible padding.
- refactoring in `copycat_jump.sh` - extract 2 constants to file global variables
- improve file matching regex. `master...origin/master` is not detected as a
  string.

### v0.0.1, Jun 25, 2014
- first version, plugin working
