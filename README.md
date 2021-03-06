# react-image-blur

A React component to blur image by canvas

[DEMO](http://lingyucoder.github.io/react-image-blur/demo/demo.html)

## Install

```bash
$ npm install --save react-image-blur
```

## Usage

```javascript
import React from 'react';
import BlurImage from 'react-image-blur';

React.render(
  <BlurImage radius={5} alphaChannel={false} src="http://lingyucoder-demo.qiniudn.com/imgsliders_1.jpg"></BlurImage>,
  document.getElementById('container')
);
```

## Properties

All properties of `<img>` are supported, and two more:

```javascript
radius: React.PropTypes.number, //blur radius, the default value is 5
alphaChannel: React.PropTypes.bool //blur alpha channel or not, the default value is false
```

## Development

```bash
$ npm start
$ open http://127.0.0.1:3000/demo/demo.html
```

## License
The MIT License (MIT)

Copyright (c) 2015 天镶

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
