# Mobile Angular UI

Fast mobile boilerplate integrates with the following:

* Mobile Angular UI v1.1.0-beta.22: http://mobileangularui.com/
* Phonegap v3.4.0: http://phonegap.com/
* Fireshell v1.1.0: http://getfireshell.com/

## Jump start

1. Install [NodeJS](http://nodejs.org/)
2. If you're a Windows user you'll also need to install [Ruby](http://rubyinstaller.org/downloads).
3. Install Grunt `npm install -g grunt-cli`
4. Install Phonegap `npm install -g phonegap`
5. Excute `grunt-dev` file to install the necessary `node_modules`
6. [Build apps](https://build.phonegap.com)

## Document

Mobile Angular UI - http://mobileangularui.com/docs/

Phonegap - http://docs.phonegap.com/en/3.4.0/index.html

Fireshell - https://github.com/toddmotto/fireshell/blob/master/docs/DOCS.md

## Debug

weinre - http://localhost:8080/

Chrome ADB Plugin (Android 24+ is required) - https://chrome.google.com/webstore/detail/adb/dpngiggdglpdnjdoaefidgiigpemgage/details

## Scaffolding

````
├── www
│   ├── apple-touch-icon-precomposed.png
│   ├── assets
│   │   ├── css
│   │   ├── fonts
│   │   ├── img
│   │   ├── js
│   │   └── template
│   ├── config.xml
│   ├── favicon.ico
│   └── index.html
├── src
│   ├── js
│   │   └── scripts.js
│   └── scss
│       ├── mixins
│       ├── modules
│       ├── partials
│       ├── vendor
│       └── style.scss
├── docs
├── hooks
├── merges
├── platforms
├── plugins
├── grunt-build.command
├── grunt-build.bat
├── grunt-dev.command
├── grunt-dev.bat
├── Gruntfile.js
├── package.json
├── README.md
├── .cordova
│   └── config.json
├── .editorconfig
├── .gitignore
├── .jshintrc
└── .travis.yml
````

## License

#### The MIT License (MIT)

Copyright (c) ayming

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
