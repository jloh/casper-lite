# Casper Lite

![Latest version](https://img.shields.io/github/tag/jloh/casper-lite.svg?style=flat)
![Ghost version](https://img.shields.io/badge/Ghost-%3E%3D0.9.0%20%3C1.0.0-brightgreen.svg?style=flat)

Casper Lite is a fork of the original Casper theme for Ghost focused on using as many external assets as possible and using system fonts for faster rendering.

## Features

 * Uses system fonts for faster rendering (No more Google fonts!)
 * Font Awesome for all social icons (No more custom font files!)
 * More social links for website and authors


## Install

Installation is a little different when compared to other themes since the idea is to be able to drop newer editions over the top of the current version *without* overriding current files.

1. Download a realse from the [releases page](https://github.com/jloh/casper-lite/releases)
1. Unzip the file locally
1. Copy `partials/author-social.hbs.dist` to `partials/author-social.hbs`
1. Copy `partials/social-links.hbs.dist` to `partials/social-links.hbs`
1. Edit both files to include additional social links if required  
   **Note:** these files *must* be present for the them to work
1. Zip up the file and upload it into Ghost!


## Roadmap

 * Redo side menu
 * Add more homepage icons/headings to page/posts
 * More to come!

## Credit

Credit of course goes to the [Ghost Team](https://github.com/TryGhost) for creating the original Casper theme.

## Copyright & License

Copyright (c) 2016 James Loh - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
