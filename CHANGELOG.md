# Changelog

## 1.7.1

* Fix bug with REST endpoints in Multisite (props justnorris)
* Fix for some failing unit tests due to core changes (props jasonagnew)
* Fix for bug where shortcodes would be removed completely (props jasonagnew)
* Fixed some pagination issues in relatively unique circumstances (props liam-defty)
* Fixed a bug that failed to correctly handle avatars (props liam-defty)
* Made sure we handle timezones in entries properly (props liam-defty)

## 1.7

* New: Mobile-friendly React-based frontend UI for a better editing experience across devices. (props jagnew jrmd liam-defty)
* Various UI bugfixes thanks to the new frontend.
* Fix for incorrect use of `defined()` (props kevinfodness)

## 1.6.1

* Remove support for Flash + Silverlight which are no longer supported in WP 4.9, see https://core.trac.wordpress.org/ticket/41755#no0
* Bugfix for WPCOM: Don't force an AJAX URL if we're using the REST API.
* Bugfix WPCOM: Retain SA access for A12s

## 1.6

* REST API support
* Performance improvements to lazy loading
* Auto-archiving of Liveblogs
* Removed copied core functions
* Improved test coverage
* Bugfix for edited comments appearing on archived Liveblogs
* Bugfix for multiple edits issue
* Bugfix for deleted key events appearing after edits
* Bugfix for shortcodes within key events
* Bugfix to allow editing entries more than once

Thanks to Mo Jangda, Jason Agnew, Max Katz, Olly Warren, Rebecca Hum, Travis W

## 1.5

* New "Key Events" feature
* New "Lazyloading" feature
* Improved escaping

People who helped make this happen: Jason Agnew, Josh Betz, Sarah Blackstock, Stephane Boisvert, Ian Dunn, Scott Evans, Thorsten Frommen, Mark Goodyear, Chris Hardie, Philip John, Paul Kevan, Connor Parks

## 1.4.1

* Bump tested tag to 4.2.2.
* Added Composer support!

## 1.4

* Rich-text editing!
* Archived liveblogs now display in chronological order (live ones show reverse chron)
* New and udpated translations
* Bump to fix SVN sync issues (thanks @kevinlisota)

## 1.3.1

* Fixed a bug where liveblog would show up in secondary loops

## 1.3

**The liveblog plugin now requires WordPress 3.5.**

New functionality:

* Liveblog archiving
* Shows automatically new entries, with a slick notification bar if we have scrolled out of view. With the help of [@borkweb](https://github.com/borkweb) and [@zbtirrell](https://github.com/zbtirrell)
* Front-end editing
* Pasting an image URL embeds the image

Translations:

* German by [@cfoellmann](https://github.com/cfoellmann)
* Spanish by [@elarequi](http://profiles.wordpress.org/elarequi)

Also a lot of internal improvements and bug fixes. See the [full list of
closed issues](https://github.com/Automattic/liveblog/issues?milestone=3&state=closed).

## 1.2

New functionality:

* Introduce many new hooks and filters, which help customization without changing the plugin code.
* Allow shortcodes and OEmbed in liveblog entries
* Translations:
	- Spanish by [@elarequi](http://profiles.wordpress.org/elarequi)
	- Dutch by [@defries](https://github.com/defries)
	- Catalan by [@gasparappa](https://github.com/gasparappa)
	- German by [@cfoellmann](https://github.com/cfoellmann)
* Add github-friendly version of `readme.txt`
* Optimize PNG files

Fixed problems:

* Fix JavaScript errors on IE8, props [@pippercameron](https://github.com/pippercameron)
* Fix preview tab
* Compatibility with plupload 1.5.4, props [@borkweb](https://github.com/borkweb)

## 1.1

* Backwards compatibility for 3.4
* Support for non-pretty permalinks
* Support for permalinks without trailing slashes
* Fix preview tab

## 1.0

* Initial release
