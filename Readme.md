*This repository is a mirror of the [component](http://component.io) module [code42day/plumper](http://github.com/code42day/plumper). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/code42day-plumper`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
[![Build Status](https://secure.travis-ci.org/code42day/plumper.png)](http://travis-ci.org/code42day/plumper)
[![NPM version](https://badge.fury.io/js/plumper.png)](http://badge.fury.io/js/plumper)

# plumper

Makes your polyline look fat using [routeboxer][1] algorithm.
Check out [the live demo][2].

## API

```javascript
// polyline is a set of points
var polyline = [[0,2], [3,4], [7,8]];
// fat is a factor corresponding to the width of the polyline
var fat = 5;
// polygon is an array of points outlining a polygon that completely encompasses a line
var polygon = plumper(polyline, fat);
```

# License

The MIT License (MIT)

Copyright (c) 2013 [code42day.com](http://code42day.com)

[1]: http://google-maps-utility-library-v3.googlecode.com/svn/trunk/routeboxer/docs/examples.html
[2]: http://code42day.github.io/plumper/