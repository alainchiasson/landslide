Landslide Docker builder
=========================

As we are starting to use site generators for some of our documentation and slide
presentations, a cleaner method is to simply use a container to process it. The
following creates a docker container which contains the
[landslide](https://github.com/adamzap/landslide) slide show generation script.

How to use
----------

See the following [presentation](https://rawgit.com/alainchiasson/landslide/master/presentation.html)
This was generated from : [slides.md](https://github.com/alainchiasson/landslide/blob/master/slides.md)

NOTE
----
I did find a
container, [ptisserand/landslide](https://hub.docker.com/r/ptisserand/landslide/)
but it was missing the watch. So as both a service and an
excercise I rebuilt a new one.

TODO
----

Slide themes to be integrated - install in specific location. print out help.


- https://github.com/akrabat/avalanche : https://akrabat.com/introducing-avalance-a-landslide-presentations-theme/

- https://github.com/Kaljurand/landslide-themes
- https://github.com/machinalis/slides/tree/master/landslide-theme
- http://readme-go.appspot.com/info/landslide
- https://pypi.python.org/pypi/darkslide (is there a theme to pull out of this?)

Also this is based on : https://code.google.com/archive/p/html5slides/
Original Author's site : http://adamzap.com/ He seems to be doing a full rewrite.

Would it make sense to integrate an ONBUILD directive ?
