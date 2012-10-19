[CFeather][homepage] is a package to provide C support for [Sublime Text 2]
[st2].

I created it because I'm not keen on Sublime's stock C package for the
following reasons:

* It's conflated with supporting C++ at the same time.
* Its scope taxonomy doesn't [KISS][kiss].

CFeather is targeted at [ISO C90 aka ANSI C89][lang] and its Standard Library.
For convenience, the following non-standard constructs are also recognised:

* `(i|u)(8|16|32|64)`, `f(32|64)`, `byte` and `bool` as presumed `typedef`
names.
* `//` as the beginning of a line comment.

For CFeather to be picked up by Sublime, you must first add the aforementioned
stock package ("C++") to the `ignored_packages` array in your settings file.

[homepage]: https://github.com/frou/CFeather
[st2]: http://www.sublimetext.com/
[kiss]: http://en.wikipedia.org/wiki/KISS_principle
[lang]: http://en.wikipedia.org/wiki/C_(programming_language)#ANSI_C_and_ISO_C
