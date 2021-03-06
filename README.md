Rosetta
====

Tools for data science with a focus on text processing.

* Focuses on "medium data", i.e. data too big to fit into memory but too small to necessitate the use of a cluster.
* Integrates with existing scientific Python stack as well as select outside tools.

Packages
--------

See the `examples/` directory for more details.

### `cmd` 
* Unix-like command line utilities.  Filters (read from stdin/write to stdout) for files

### `parallel` 
* Wrappers for Python multiprocessing that add ease of use
* Memory-friendly multiprocessing

### `text`
* Stream text from disk to formats used in common ML processes
* Write processed text to sparse formats
* Helpers for ML tools (e.g. Vowpal Wabbit, Gensim, etc...)
* Other general utilities

### `workflow`
* High-level wrappers that have helped with our workflow and provide additional examples of code use

### `modeling`
* General ML modeling utilities

Install
-------
Check out the dev branch or a tagged release from the [rosettarepo][rosettarepo].  Then (so long as you have `pip`).

    make
    make test

Development
-----------

### Code

You can check the latest sources with

    git clone git://github.com/columbia-applied-data-science/rosetta

### Contributing

Feel free to contribute a bug report or a request by opening an [issue](https://github.com/columbia-applied-data-science/rosetta/issues)

Before contributing code, read `CONTRIBUTING.md`

Dependencies
------------

Testing
-------
From the base repo directory, `rosetta/`, you can run all tests with

    make test

History
-------
*Rosetta* refers to the [Rosetta Stone](http://en.wikipedia.org/wiki/Rosetta_Stone), the ancient Egyptian tablet discovered just over 200 years ago. The tablet contained fragmented text in three different languages and the uncovering of its meaning is considered an essential key to our understanding of Ancient Egyptian civilization. We would like this project to provide individuals the necessary tools to process and unearth insight in the ever-growing volumes of textual data of today.

[rosettarepo]: https://github.com/columbia-applied-data-science/rosetta
