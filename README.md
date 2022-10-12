# Mac U.S. keyboard layout with German Umlauts
This layout is designed for German speakers using U.S. English mac keyboards. The layout is a modified U.S. English keyboard layout with German Umlauts using `⌥ option` key bindings:
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

```bash
curl -sL https://api.github.com/repos/patrick-zippenfenig/us-with-german-umlauts/tarball/master | sudo tar xz --exclude=README.md --strip=1 -C /Library/Keyboard\ Layouts/
```

2. Enter your password. This is required because the keyboard layout is installed for all users on your mac.
3. Open `System Preferences` -> `Keyboard` -> `Input Sources`
4. Click `+` and add `U.S. with German Umlauts` (category `English`)
5. Check `☑ Show Input menu in menu bar`
6. In the menu bar (top right) select `U.S. with German Umlauts`

# Uninstall #
1. Delete directory `/Library/Keyboard\ Layouts/US-with-German-Umlauts.bundle` with

```bash
sudo rm -R /Library/Keyboard\ Layouts/US-with-German-Umlauts.bundle
```

# Credits #
Generated with [Ukelele 3.2.7](http://software.sil.org/ukelele/) and tested on macOS 10.13 High Sierra, 10.14 Mojave, 10.15 Catalina and 11 Big Sur.

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
