# Filez

Filez is a framework for naming static files in product design.

## Naming convention

Filez follows a two-tiered naming hierarchy, dividing file names into (1) general “categories” and “sub-categories,” as well as (2) descriptive “elements” and “modifiers.”

```
[category].[sub-category].[element]-[modifier].[extension]
```

### Categories

A “category” places a file into a general asset class. Commonly used categories include:

* Brand — files related to brand identity, such as logos, wordmarks, and app icons;
* Interface — files used to control the user interface, typically vector graphics or animated GIFs;
* Slice — files used as building blocks of the user interface, like geometric shapes or background patterns;
* Content — files used for decorative and informational purposes, such as illustrations and photographs; 
* Affiliate — files used on 3rd party services and platforms.

### Sub-categories

A “sub-category” aims to differentiate between multiple versions of a single file category. Typical sub-categories include `light` and `dark` interface color schemes or localized content variants.

### Elements and modifiers

An “element” identifies each functional file type within each category. For example, the “brand” category can contain “logo” or “wordmark” elements, whereas the “content” category can contain such elements like “avatar,” “photo” or “screenshot.”

A “modifier” appends a technical suffix to each element, such as information about file shape, dimensions, resolution, numerical order or date when it was created.

## Examples

### Brand

```
brand.favicon-filez.png

brand.apple-touch-icon-filez-60@2x.png
brand.apple-touch-icon-filez-60@3x.png
brand.apple-touch-icon-filez-76@1x.png
brand.apple-touch-icon-filez-76@2x.png

brand.app-icon-filez.png
brand.logo-filez.png

brand.wordmark-filez.svg
brand.wordmark-filez.svg
```

### Interface

```
interface.light.icon-cross-24.svg
interface.light.icon-check-24.svg

interface.dark.icon-chevron-left-24.svg
interface.dark.icon-chevron-right-24.svg
```

### Content

```
content.avatar-01@2x.png
content.avatar-02@2x.png

content.us.screenshot-filez-01@2x.png
content.jp.screenshot-filez-02@2x.png
```

### Affiliate

```
affiliate.medium-publication-avatar-filez.png
affiliate.medium-cover-filez.png
affiliate.medium-screenshot-filez-2020-02-20.png

affiliate.producthunt-thumbnail-filez.png
affiliate.producthunt-gallery-filez-01.png
```

## License

Filez is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
