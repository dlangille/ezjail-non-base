ezjail-non-base
===============

ezjail with the option of creating non-base jails

Based on http://erdgeist.org/arts/software/ezjail/

Tested once.  It worked.  Do not use this in production.  Test carefully.

Here is what I did to get a simple jail running:

ezjail-admin install -d newjailwithoutbase
ezjail-admin create -n newjailwithoutbase testing "em0|10.0.0.114"
ezjail-admin start testing
ezjail-admin console testing

