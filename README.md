scotlandjs-2015
=============

"Getting started with three.js and WebGL"
WebGL shaders and GPU computing presentation for ScotlandJS 2015

About
-----

Shaders! Amazing little things: a few lines in a C-like language and we can get smooth colours pulsating on the screen or a first-person shooter. In WebGL that we have running on our browsers there are vertex and fragment shaders, we are going to take a closer look at the latter.

Fragment shaders are programs which perform a very specific task: to compute a colour. And each program is calculating a pixel, blissfully unaware of any other pixels or programs, so it can run all by himself in its own computer. Picture this: when we have thousands or millions of independent computers running in parallel we can compose an image thousands or millions of times faster.

But is that all we can do with shaders, drawing pictures? Not really! An image, in the end, is just a piece of memory that we choose to read as a picture. But a chunk of memory can be so much more, it can hold any data! And with fragment shaders we can perform many tasks on that data and speed them up incredibly.

Searching big sets of data, doing complex calculations, even synthesising music!

All in your browser!

Credits
-------

Coded using [three.js](http://www.threejs.org)

License
-------

MIT licensed

Copyright (C) 2015 Jaume Sanchez Elias http://twitter.com/thespite

http://www.clicktorelease.com