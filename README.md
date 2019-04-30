# Mac U.S. keyboard layout with German Umlauts
Modified U.S. Keyboard layout with German Umlauts with `option` key:
* `option` + `a` => `ä`
* `option` + `o` => `ö`
* `option` + `u` => `ü`
* `option` + `s` => `ß`
* `option` + `shift` + `a` => `Ä`
* `option` + `shift` + `o` => `Ö`
* `option` + `shift` + `u` => `Ü`
* `option` + `shift` + `s` => `ẞ`

# Installation #
1. To install the keyboard layout open `Terminal` on your mac and execute the command below.

```
curl -sL https://api.github.com/repos/patrick-zippenfenig/us-with-german-umlauts/tarball/master | tar xz --strip=1 -C ~/Library/Keyboard\ Layouts/
```

2. Open `System Preferences` -> `Keyboard` -> `Input Sources`
3. Click `+` and add `U.S. with German Umlauts`
4. In the menu bar (top right) select `U.S with German Umlauts`

# Uninstall #

1. Delete directory `~/Library/Keyboard Layouts/US-with-German-Umlauts.bundle`

# Credits #
Generated with [Ukelele 3.2.7](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) and tested on macOS 10.13 High Sierra and 10.14 Mojave.

# License #
MIT License

Copyright (c) 2017 Patrick Zippenfenig

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
