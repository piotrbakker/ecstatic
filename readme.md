# Ecstatic

Ecstatic is a framework for naming static files in product design.

## Formatting

Ecstatic divides file names into (1) general “categories” and “sub-categories,” as well as (2) descriptive “elements” and “modifiers.”

```
[category].[sub-category].[element]-[modifier].[extension]
```
Dot notation (`.`) is used to separate hierarchical levels, such as categories and sub-categories, whereas hyphens (`-`) are used to separate descriptive elements and technical modifiers.

### Categories

A “category” places a file into a general asset class. Commonly used categories include:

* Brand — files related to brand identity, such as logos, wordmarks, or app icons;
* Interface — files used to control the user interface, typically vector graphics or animated GIFs;
* Slice — files used as building blocks of the user interface, like geometric shapes or background patterns;
* Content — files used for decorative or informational purposes, such as illustrations and photographs; 
* Affiliate — files used on 3rd party services and platforms, such as avatars or screenshots.

### Sub-categories

A “sub-category” aims to differentiate between multiple versions of a single file category. Typical sub-categories include `light` and `dark` interface color schemes or localized content variants.

### Elements and Modifiers

An “element” identifies each functional file type within each category. For example, the “brand” category can contain “logo” or “wordmark” elements, whereas the “content” category can contain such elements like “avatar,” “photo” or “screenshot.”

A “modifier” appends a technical suffix to each element, such as information about file shape, dimensions, resolution, numerical order or date when it was created.

### Dimensions

File dimensions are formatted as `wWWhHH`. [WW] is the width of the file, prefixed by the letter _w_, and [HH] is its height, prefixed with the letter _h_. 

The framework also allows for dimensions to be written with reduced precision. For example, one may simply write `60@2x` to refer to the width and/or the height of the file.

### Dates

To enhance human readability and reduce ambiguity dates should be expressed according to the [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) notation: [YYYY]-[MM]-[DD].

## Examples

### Brand

```
brand.favicon-ecstatic.png

brand.apple-touch-icon-ecstatic-60@2x.png
brand.apple-touch-icon-ecstatic-60@3x.png
brand.apple-touch-icon-ecstatic-76@1x.png
brand.apple-touch-icon-ecstatic-76@2x.png

brand.app-icon-ecstatic.png
brand.logo-ecstatic.png

brand.wordmark-ecstatic.svg
brand.wordmark-ecstatic.svg
```

### Interface

```
interface.light.icon-cross-24.svg
interface.light.icon-check-24.svg

interface.dark.icon-chevron-left-24.svg
interface.dark.icon-chevron-right-24.svg
```

### Slice

```
slice.rectangle-contained-w24h24-#333333.png
slice.rectangle-contained-w24h24-#F1C100.png

slice.rectangle-outlined-w24h24-#333333.png
slice.rectangle-outlined-w24h24-#F1C100.png
```

### Content

```
content.photo-product-ecstatic-01.png
content.photo-product-ecstatic-02.png

content.hero-image-ecstatic-mobile.png
content.hero-image-ecstatic-desktop.png
```

### Affiliate

```
affiliate.medium-publication-avatar-ecstatic.png
affiliate.medium-cover-ecstatic.png
affiliate.medium-screenshot-ecstatic-2020-02-20.png

affiliate.producthunt-thumbnail-ecstatic.png
affiliate.producthunt-gallery-ecstatic-01.png
```

## License

Ecstatic is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
