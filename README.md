# Color Thief

Finds the color palette used in an image.

## How to use

### Get the dominant color from an image

```js
var colorThief = new ColorThief();
colorThief.getColor(sourceImage);
```

```js
getColor(sourceImage[, quality])
returns [num, num, num]
```

### Build a color palette from an image

In this example, we build an 8 color palette.

```js
var colorThief = new ColorThief();
colorThief.getPalette(sourceImage, 8);
```

```js
getPalette(sourceImage[, colorCount, quality])
returns [ [num, num, num], [num, num, num], ... ]
```

## Development

### Deploy

Make sure you have [parcel](https://github.com/parcel-bundler/parcel) installed:

- Run `yarn run build`
- Push to Github repo
- Create a new Github release along with tag. Naming convention for both ```v2.8.1```
