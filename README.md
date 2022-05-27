## Babel 3.75.2750

*(Development)*

This package manages culturally-determined typographical (and other)
rules, and hyphenation patterns for a wide range of languages. Many
language styles work with pdflatex, as well as with xelatex and
lualatex out of the box. A few even work with plain formats. Included
is a set of ini files for about 250 languages.

The latest stable version is available on <https://ctan.org/pkg/babel>.

Changes in version 3.76 are described in:

https://latex3.github.io/babel/news/whats-new-in-babel-3.76.html

Apart from the manual, you can find information on some aspects of babel at:

https://latex3.github.io/babel/

The best way to install and/or update it is with the help of package
managers.

### Reporting bugs

If you wish to report a problem or bug in any of these packages please
use the
[Issue Tracker for LaTeX2e on GitHub](https://github.com/latex3/babel/issues)
and follow the guidelines that pop up if you press the `New issue`
button.

In particular, to check that you are really seeing a bug, please write
a short, self-contained document that shows the problem. This should
include the `latexbug` package, which will warn if your test file is
not suitable for one or the other reason. See the
[CONTRIBUTING guide](https://github.com/latex3/latex2e/blob/master/CONTRIBUTING.md)
for further details, or if you need to obtain the `latexbug` package.

If the bug turns out to be with third-party software then please
contact the developer, and not us!

You may also report them to the current maintainer more informally on:

   http://www.texnia.com/contact.html

Bugs related to specific languages are best reported to their
respective authors.

### Summary of latest changes
```
3.75   (dev)
       * Calendar conversion: islamic-civil, islamic-umalqura.

3.75   2022-05-22
       * `\BabelEnsureInfo` is active by default, to make sure the BCP 47
         codes are always available, as they may be required by the
         LaTeX kernel.
       * `\localeinfo*` is like `\localeinfo` but expands to empty if
         unknown (fully expandable).
       * The key `character`/`ranges` in `ini` files now sets the
         corresponding Unicode script ranges (as used by `onchar`).
       * Fixes:
         - Misplaced rule un diagbox (#43)
         - Caption names of 'chapter' and 'part' swapped in Chinese (#180).
         - Captions after numbers in Lithuanian.
         - `hyphenrules` in the `ini` files for `en-AU` and
           `en-NZ` where set to `english` instead of `ukenglish`.
```

### Previous changes

See https://latex3.github.io/babel/#whats-new
