
### About

This is the OpenGL counterpart to [4k][], a small framework intended for 4k
games or demos. It does the basics of creating a window, setting up an OpenGL
context and running a game loop at a fixed rate. It provides the bare minimum
but it's easy to extend.

Using [Crinkler][] it compiles to a 1kb executable.

### Compiling

There are batch files the [Source][] folder that compile the project
using MSVC (with the default linker or [Crinkler][]) and MinGW. It has been
tested using MSVC 2010/2012 and MinGW 4.8.1+ on Windows 7 and 8
(both x86 and x86-64).

### Alternatives

There is another 1k/4k framework done by [Iñigo Quilez][]. It's more mature
and has been used in more productions than this one. The main difference between
both is that iq's framework uses every known trick to keep the final size small.
This one tries to be clean and simple without ugly hacks.

### Status

This program is feature-complete and has no known bugs. Unless new issues
are reported or requests are made I plan no further development on it other
than maintenance.

### License

Like all my hobby projects, this is Free Software. See the [Documentation][]
folder for more information. No warranty though.


[4k]: https://github.com/Beluki/4k

[Crinkler]: http://www.crinkler.net
[Iñigo Quilez]: http://www.iquilezles.org/www/material/isystem1k4k/isystem1k4k.htm

[Documentation]: https://github.com/Beluki/4kGL/tree/master/Documentation
[Source]: https://github.com/Beluki/4kGL/tree/master/Source

