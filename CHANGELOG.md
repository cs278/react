CHANGELOG
=========

* 0.2.2 (2012-10-28)

 * Major: Dropped Espresso as a core component now available as `react/espresso` only
 * Feature: DNS executor timeout handling (@arnaud-lb)
 * Feature: DNS retry executor (@arnaud-lb)
 * Feature: HTTP client (@arnaud-lb)
 * Bug fix: Forward drain events from HTTP response (@cs278)

* 0.2.1 (2012-10-14)

 * Feature: Support HTTP 1.1 continue
 * Bug fix: Check for EOF in `Buffer::write()`
 * Bug fix: Make `Espresso\Stack` work with invokables (such as `Espresso\Application`)
 * Minor adjustments to DNS parser

* 0.2.0 (2012-09-10)

 * Feature: DNS resolver

* 0.1.1 (2012-07-12)

 * Bug fix: Testing and functional against PHP >= 5.3.3 and <= 5.3.8

* 0.1.0 (2012-07-11)

 * First tagged release
