# IntervalMap [![Hackage](https://img.shields.io/hackage/v/IntervalMap.svg)](https://hackage.haskell.org/package/IntervalMap) [![Build Status](https://travis-ci.org/bokesan/IntervalMap.svg?branch=master)](https://travis-ci.org/bokesan/IntervalMap)

Containers for intervals. Like `Data.Set` and `Data.Map` with
Intervals as keys and functions for efficiently getting the subset
of all intervals containing a point, intersecting an interval, and more.

Home page and documentation: [http://www.chr-breitkopf.de/comp/IntervalMap/index.html](http://www.chr-breitkopf.de/comp/IntervalMap/index.html)

Install from hackage with cabal install.

To run the tests, extract the archive, and do

    $ cabal configure --enable-tests
    $ cabal build
    $ cabal test
