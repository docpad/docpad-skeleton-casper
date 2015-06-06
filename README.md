# [Casper](https://github.com/TryGhost/Casper) skeleton for [DocPad](https://github.com/bevry/docpad)
The default personal blogging theme for Ghost.


## Getting Started

1. [Install DocPad](https://github.com/bevry/docpad)

1. Clone the project and run the server

``` bash
mkdir my-website
cd my-website
docpad run --skeleton casper
```

1. [Open http://localhost:9778/](http://localhost:9778/)

1. Start hacking away by modifying the `src` directory

## What's Different from Ghost - Casper?

1. This skeleton operates in a more "single author" mode.  Author details are used throughout the site, and can be edited in docpad.coffee.  Because of this there is no "author posts" pages.

2. Minor logic tweak to the masthead / cover images.  If it's not present on a post or page, the default site "cover" will be used instead.  This eliminates a display issue with the menu button (white) on a white background.

3. Site details are all managed in docpad.coffee, at the top.

4. Navigation links are manually managed in docpad.coffee.  This was the best way to ensure flexibility and make the navigation "generatable".

5. Paged posts are possible in this version.

6. Marking active links uses the url of the page, or 'sections'.  If a pages 'section' and a link's section match, the link will be marked active.  For the nav, this means the line in the link will be solid.


## License

Copyright (c) 2013-2015 Ghost Foundation

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.