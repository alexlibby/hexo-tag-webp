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
