# om-next-02

Simple [om-next](https://github.com/omcljs/om/wiki/Quick-Start-%28om.next%29) example to tv shows.
 
Load "state" into "reconciler" using ":remote" xhr data.
 
Expand to use queries.
 
[1.0.0-alpha28](https://clojars.org/org.omcljs/om)

## Overview

## Setup

Intellij - Cursive - REPL

![Figwheel Idea Cursive](https://raw.githubusercontent.com/griffio/griffio.github.io/master/public/figwheel-idea.png)

Open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

## License

Copyright © 2015 

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
