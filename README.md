perl-classes
============

UPDATE: Although `perl-classes` is alive and still kicking deep in bowels of large enterprise applications I can't recommend anyone start anything new with it these days. There's nothing wrong with except being written in Perl, which as a language in general has lost a lot of ground in the enterprise application space. I strongly recommend Go for small and enterprise-size behemouth applications of the type this module was created to build. ~ Rob

classes - Conventional Perl 5 classes

A simple, stable, fast, and flexible way to use Perl 5 classes. We're
talking *one file* with *no* dependencies. No other-object oriented Perl 5
solution offers this much power with this portability and stability.
Unlike others, `classes` does not depend on 50% of CPAN. In fact, it
depends on none of it, but has implemented the best within its ***one
file*** (I guess I don't get tired of typing that.)

Perl `classes` is the foundation for thousands of lines of enterprise
applications running on more than 50,000 Windows, Unix, and Linux machines
and has been used as the basis for complicated network protocol implementations
and brokering terabytes of enterprise data.

If you need OO in Perl, give `classes` a look.

Installation
============

To install this module, run the following commands:

``` bash
perl Makefile.PL
make
make test
make install
```

Requirements
============

While the `classes` pragma itself has no requirements nor dependencies
it does use the following for debugging and testing:

* Data::Dumper
* Scalar::Util
* Test::More

Support and Documentation
==========================

    * perldoc classes
        Syntax reference

    * perldoc classesoop

        Introductory primer of concepts, ideas and terms from object
        oriented programming without any particular implementation
        specifics in mind

    * perldoc classesfaq

        Questions and answers about support, design decisions,
        justification, motivation, and other hype.

Copyright and License
=======================

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>

