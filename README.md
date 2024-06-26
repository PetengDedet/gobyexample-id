[Readme in Indonesian (Bahasa Indonesia)](https://github.com/PetengDedet/gobyexample-id/blob/master/README-id.md)

## Go by Example - ID (gobyexample.id)

Indonesian translation for [Go by Example](https://gobyexample.com),
a site that teaches Go via annotated example programs.

The indonesian version of Go by Example can be reached at 
[http://gobyexample.id](http://gobyexample.id).

### Translation

The Indonesian localization is up to [golang-id](http://golangid.github.io).
Feel free to [open a bug](https://github.com/PetengDedet/gobyexample-id/issues) or [open a pull request](https://github.com/PetengDedet/gobyexample-id/pulls) to report bugs and typos.

### Overview

The Go by Example site is built by extracting code and
comments from source files in `examples` and rendering
them via the `templates` into a static `public`
directory. The programs implementing this build process
are in `tools`, along with some vendor'd dependencies
in `vendor`.

The built `public` directory can be served by any
static content system. <del>The production site uses S3 and
CloudFront, for example</del>.

### Building

To build the site you'll need Go and Python installed. Run:

```console
$ go get github.com/russross/blackfriday
$ tools/build
$ open public/index.html
```

To build continuously in a loop:

```console
$ tools/build-loop
```

### License

The indonesian translation is copyright PetengDedet and licensed under a
[Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

The original work is copyright Mark McGranaghan and licensed under a
[Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

The Go Gopher is copyright [Renée French](http://reneefrench.blogspot.com/) and licensed under a
[Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).
