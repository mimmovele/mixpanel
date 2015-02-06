February 2015
-------------

* Bump: 4.1.2 Feb 6, 2015

* Update Mailjet snippet to load new lib: //cdn.mxpnl.com/libs/mixpanel-2-latest.min.js

November 2013
--------------

* Bump: 4.1.0 Nov 14, 2013

* Fix XSS Vulnerability (bradleybuda)

Bump: 4.0.9 Nov 7, 2013

* URI namespace fix (Ahmed Belal)

September 2013
--------------

Bump: 4.0.7 Sep 6, 2013

* Fix request doing GET instead POST (Jan Berdajs)

Bump: 4.0.6 Sep 5, 2013

* Add append_track_charge method to person.rb (Matt Angriffel)
* Convert time property to timestamp (Francis Gulotta)

August 2013
-----------

Bump: 4.0.5 Aug 26, 2013

* Fix events sent async. (Eric Boehs)
* Fix crash with chunked response and turbolinks. (Roman Shterenzon)

July 2013
---------

* Ability to generate tracking links with redirect. (Francis Gulotta)
* Skip Middleware injection on All Redirect statuses. (Francis Gulotta)

May 2013
--------

* Allow to specify "test" when sending events using the HTTP interface(Roman Shterenzon)

Bump: 4.0.2 May 23, 2013

* Add alias helper method to event tracking (Chris Maddox)

Bump: 4.0.1 May 10, 2013

* Update documentation. (Paweł Gościcki)
* Add people.set_once to middleware script. (alvarezm50)

April 2013
----------

Bump: 4.0.0 Apr 18, 2013

* Delete a user from mixpanel (dennisvdvliet)
* Ability to set_once properties (Michael Glass)
* Use mixpanel script version 2.2. Replaced person.identify with unified identify. Added person.alias. (Milo Winningham)

Feb 2013
--------

Bump: 3.5.2 Feb 24, 2013

* Ability to skip middleware js snippet injection. (adimichele)
* Ability to unset a person property (Marko Vasiljevic)
* Update DelayedJob documentation (Joel)

Bump: 3.5.1 Jan 28, 2013

Jan 2013
--------

* Add option to not render mixpanel scripts (Murilo Pereira)
* Add support for Turbolinks (Jon Pospischil)
* Add track_charge and reset_charges to Mixpanel::Person (Tom Brown)

December 2012
-------------

* Fix: Github issue #59, When setting people properties, cannot set $ip for proper geolocation.
* FOPS: Removing Active Support dependency.

November 2012
-------------

* Pixel Based Event Tracking (Esteban Pastorino)

October 2012
--------------

* API Changes, please take a look at README file.
* Add support for mixpanel.people.identify (Ahmed Belal)
* Engage endpoint added. (GBH)
* Code revision (Chris Sturgill)

September 2012
--------------

* Added support for Import API (Sylvain Niles)
* Ability to skip Mixpanel Middleware through HTTP custom header
* Use mixpanel script version 2.1 (Travis Pew)

August 2012
-------------
* Added Javascript API 2 support (Jamie Quint)
* Add persistence feature (Ryan Schmukler)
* Deprecate: Mixpanel.new
* Use new JS CDN hosted (Alvaro Gil)

January 2012
-------------
* Ability to proxy Mixpanel calls (Mark Cheverton)

December 2011
-------------
* Add HTTP_X_FORWARDED_FOR to obtain ip addresses, Heroku thing. (Alvaro Gil)

November 2011
-------------

* Fix content length update, IE. Send file bug (Brad Wilson)

October 2011
--------------
* Ability to insert JS scripts at the bottom of Body element (James Ferguson)

September 2011
--------------

* Updated middleware with latest mixpanel javascript (eddiesiegel)
* Allow overriding of token, time, and ip address (Joe Van Dyk)
* Spelling correction (jellybob)

June 2011
---------

* Refactor Gem to live in Mixpanel::Tracker and avoid conflicts with other gems.

January 2011
------------

* Fix how the interpreter is called for asynchronous call support. (jakemack)
* Added optional asynchrony usage built in. (Logan Bowers)

Novemeber 2010
--------------

* Bug fixes. (Nathan Baxter)
* Allow api calls other than track through the javascript API. (Nathan Baxter)
* Added support for mixpanel's asynchronous javascript mechanism. (Nathan Baxter)
* Add support for large ajax responses in Rails. (Jake Mallory)
