0.3.3 / 2014-10-01
==================

* updating analytics-events

0.3.2 / 2014-09-04
==================

* updating analytics-events and the makefile

0.3.1 / 2014-07-11
==================

 * emit ready on next frame

0.3.0 / 2014-07-11
==================

 * ready on initialize by default
 * duo creds
 * use duo-test
 * make: remove server
 * bump node version to 0.11
 * make new `load` method load tags (script/img/iframe). so, you don't need to implement `.load` when building a new integration.
 * add `.tag` to the DSL, where you define script/img/iframe tags, instead of loading them manually. they use mustache-like templates, getting the options and whatever other "locals" you send to the `.load` method
 * remove old `load` method

0.2.4 / 2014-07-08
==================

 * port to duo
 * swap callback and ready event

0.2.3 / 2014-07-02
==================

 * reset window defaults
 * update readme
 * version component

0.2.2 / 2014-05-16 
==================

 * allow camelCase and snake_case names

0.2.1 / 2014-04-29 
==================

 * .mapping(): make sure it returns the integration for chaining
 * make: move rm node_modules to distclean target, for speed
 * add .mapping(name)

0.2.0 / 2014-04-26 
==================

 * add #events method to find events.
 * component: add githubusercontent to remotes

0.1.9 / 2014-04-16 
==================

 * make sure initialize is called with page

0.1.8 / 2014-04-15 
==================

 * make sure all methods return the real values

0.1.7 / 2014-01-30
==================

 * pass all arguments to track()
 * dont wait until "ready" event to call track() directly

0.1.6 / 2014-01-30
==================

 * add eCommerce api

0.1.5 - November 26, 2013
-------------------------
* adding `readyOnLoad` fix to still call `load` callback

0.1.4 - November 12, 2013
-------------------------
* debug: upgrade to 0.7.3

0.1.2 - November 11, 2013
-------------------------
* rename `section` argument to `category`

0.1.1 - November 11, 2013
-------------------------
* add `section` argument to `page` method signature

0.1.0 - November 10, 2013
-------------------------
* change `exists` to `loaded` and check in `load`

0.0.7 - November 10, 2013
-------------------------
* add `construct` event to integration

0.0.6 - November 6, 2013
------------------------
* fix `ready` to always be emitted asynchronously

0.0.5 - November 6, 2013
------------------------
* add `exists` check for globals

0.0.4 - November 5, 2013
------------------------
* move `initialize` on `page` logic into `page`
* move `initialized` state into `initialize`
* remove handling of `initialPageview` option

0.0.3 - October 29, 2013
------------------------
* change initialize to be called with `page` args

0.0.2 - October 29, 2013
------------------------
* change globals to be an array of keys

0.0.1 - October 29, 2013
------------------------
:sparkles:
