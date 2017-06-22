## PSD to Sketch Design Converter (Beta)

PSD to Sketch Converter is a free online convertor of single Photoshop files into layered Sketch designs developed by Avocode.

 ## Purpose of this repository
 
The main purpose of this repository is for issue reporting. If you have used the PSD to Sketch Design Converter and found a bug or you have ideas for improvement, please create a new issue in its recommended format. 

- [Report an issue](https://github.com/avocode/psd-to-sketch-converter/issues/new)
- [Send us feedback or feature suggestions](http://r.avocode.com/feedback?utm_source=features&utm_medium=web&utm_campaign=psd-to-sketch-converter)

## Supported features

- Shape layers
- Combined shape layers
- Group layers
- Text layers
- Bitmap layers
- Smart objects
- Linear gradients
- Adjustment layers
    - Color fill
- Masks
    - Vector clipping masks
Layer styles
    - Stroke
    - Inner shadow, Drop shadow
    - Color overlay
    - Blend modes
    - Gradient overlay
    - Opacity

All converted Sketch designs can be opened only in Sketch app [Version 43](https://www.sketchapp.com/updates/#version-43) and later. In order to view the design correctly, make sure you have installed all of the fonts from the original PSD file.

## Known issues

- Sometimes boolean operations on shapes are not correct
- Color overlay is not working
- Text line height is still broken

## Features in development

- Text layers
    - Line height
    - Text decorations
- Masks
    - Bitmap clipping masks
    - Layer masks
- Circular gradient, Radial gradient
- Layer styles
    - Inner glow, Outer glow
- Additional features
    - Guides


## Future Roadmap

- Proper rounding 
- Convert adjustment layers to masks with effect

## Changelog

### v0.4.0 (June 22, 2017)

- added text decorations
- added support for fill opacity
- set artboard background color

### v0.3.0 (June 19, 2017)

- support for bitmap masks on layers

### v0.2.0 (June 15, 2017)

New features
- Text layers with applied scale and proper width
- Support color fill adjustment layers

Fixes
- Fixed several issues which lead to invalid Sketch document

### v0.1.0 (June 8, 2017)
- Initial Beta release
