# wotsdk-d3js-speedomete

## Technology

wotsdk-d3js-speedomete is a package of single-page application boilerplate for Web of Things application.

| Development | Frontend  |
| —————— | ——————— |
| Node.js       | Backbone      |
| Gulp          | AutomationJS    |
| Bower      | jQuery         |
| npm      | Underscore  |
| Browserify         | Virtual DOM   |
| EmailJS       | D3.js      |

## Prerequisites

1. [Node.js](https://nodejs.org). Note: Node should be with a version above 0.10.x.
2. [Gulp](http://gulpjs.com). Note: Run `$ nom install —global gulp` to install the latest version.
3. [Bower](http://bower.io). Note: Run `$ nom install —global bower` to install the latest versin.
4. Note: `git` command line interface is needed for Bower.

## Compile and Install

1. Run `$ git clone https://github.com/wot-sdk/d3js-speedomete`  to download SDK.
2. Run `$ cd d3js-speedomete` to change the directory.
3. Run `$ npm install --global gulp` to install Gulp globally if you don’t already have it.
4. Run `$ npm install --global bower` to install Bower globally if you don’t already have it.
5. Run `$ npm install` to install the dependencies if you don't already have them.
6. Run `$ bower install` to install the module dependencies if your don't already have them.
7. Run `$ gulp build` to build the application scripts.
8. Open `index.html` with your farovite browser. The web app page is empty now.
9. Append the device name in the URL as an frontend routing parameter. For example `index.html#5547870f4dd3e08d63000007`

### Getting the device name

1. Please visit [WoT.City Platform](http://wotcity.com).
2. Signup to create your account.
3. Login to your account.
4. Click *Device Manager* at the left side menu.
5. Click *Launch New Device* button to create a new device instance.
6. Copy your device name at *Device Name (Physical Object)* column.

## Discussion

There are various ways to get involved with WoT-SDK project. We're looking for help identifying bugs, writing documentation and contributing codes.
	
## How to Report Bugs

Bugs are reported via [https://github.com/wot-sdk/d3js-speedomete](https://github.com/wot-sdk/d3js-speedomete).

## Core Style Guide

WoT-SDK project follows [jQuery's Style Guides](http://contribute.jquery.org/style-guide/) except that:

* `forin` must be used in WoT-SDK project.
* `quotmark` must be `single`. Strings must use singlequote.

WoT-SDK project uses JSHint to validate code styles. The JSHint options are stored in the `.jshintrc` file. Run `$ gulp jshint` to detect errors.

## License

The MIT License (MIT)

Copyright (c) 2015 Jollen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
