# hexo-tag-webp 
> A [Hexo](https://hexo.io) tag plugin to generate WebP format images from PNG files 

## Install
```bash
$ npm install hexo-tag-webp --save
```

## Options
You can configure this plugin in `_config.yml`:

```yaml
webpconfig:
  quality: 90
  height: 260
  width: 0
```

- **quality** - Sets the quality of the image from 0 to 100
- **height** - Specify the height of the new WebP image
- **width** - Specify the width of the new WebP image

Specifying 0 for height or width will scale the image's height or width automatically, based on whether a non-zero value has been set for height or width.

## License
    The MIT License (MIT)

    Copyright (c) 2020 Alex Libby

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
