[CFeather][homepage] is a package to provide C support for [Sublime Text 2][st2].

I created it because I'm not keen on Sublime's stock C package for the following reasons:

* It's conflated with supporting C++ at the same time.
* Its scope taxonomy doesn't [KISS][kiss].

CFeather is targeted at [ISO C90 aka ANSI C89][lang]. For convenience, the following non-standard constructs are also recognised:

* `(i|u)(8|16|32|64)`, `f(32|64)`, `byte` and `bool` as presumed type names.
* `//` as the beginning of a line comment.

For CFeather to be picked up by Sublime, you must first add the aforementioned stock package ("C++") to the `ignored_packages` array in your settings file.

This package is available direct from its GitHub homepage, and also via [Sublime Package Control][spc]. If you wish to distribute it otherwise, please contact me first.

---

The following screenshot shows C source code as classified by this package and coloured by my [Sundried][sd] colour scheme.

![Screenshot](https://github.com/frou/Sundried/raw/master/screenshot.png)

[homepage]: https://github.com/frou/CFeather
[st2]: http://www.sublimetext.com/
[kiss]: http://en.wikipedia.org/wiki/KISS_principle
[lang]: http://en.wikipedia.org/wiki/C_(programming_language)#ANSI_C_and_ISO_C
[spc]: http://wbond.net/sublime_packages/package_control
[sd]: https://github.com/frou/Sundried
