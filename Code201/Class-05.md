# Images, Color, and Text

[Home](../index.md)

## HTML and CSS

### Chapter 5 Images

If your building a site from scratch it is good practice to put all of your images into their own folder.

The `<img>` tag allows you to add images into your pages and has the properties `src`, `alt`, and `title`. It is an empty (self-closing tag). Additional it has a height and width image like most elements in HTML.

> Images created for the web shoud be saved at a resolution of 72 ppi. The higher the resolution of the image. the larger the size of the file.

In order to support transparency your need to use a Transparent .gif or a .png file.

### Chapter 11 Color

The most common ways to express color in programming are RGB, RGBA, HSL, HSLA, hex codes, and color names. When picking a color and a background it is important to ensure there is sufficient contrast, especially for those who are color defecient.

### Chapter 12 Text

The primary kinds of typeface (fonts) are:

- serif
- sans-serif
- cursive
- fantasy
- monospace

Other font properties include:

- weight
- style
- stretch
- text-decoration
- line-height
- letter-spacing
- word spacing
- text-alignment
- text-indent
- text-shadow

Pseduo classes include

- :first-letter
- :first-line
- :link
- :visited

It is important to specify alternate fonts becuase the client's browser needs to have the requested font downloaded in order to use the font. For this reason it is good to end you list of alternates with a generic catch-all.

@font-face is a technique (albeit possibly dated) for enabling additional fonts on computers/browsers that do not have the font natively installed. You can place a URL reference to a file that describes your font and then reference it in your code. The most common file formats for this are `eot`, `.woff`, `.ttf / .otf`, and `.svg`. You can save these files local in your website, or you can reference an external URL for these.

Nowadays it is common to use Google Fonts and place a link in your HTML that references and external stylesheet that enables this font in your code.

## JPEG vs PNG vs GIF (Online Reading)

> Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.

This is because different file types offer differenet compressions methods. JPG is lossy and PNG is lossless. Distortion upon lossy compression is known as compression artefact. Since JPG uses the average of nearby pixels to approximate their pictures, the compression algorithm works well with photos with smooth transitions in color.

> JPEG images can support around 16 million colours. This is what makes them suitable for storing images of natural scenes.
> PNG images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image. Use PNG8 for simple shapes with fewer colours and PNG24 for high quality, complex logos and shapes with rounded corners on a transparent background.
> GIF images are limited to 256 colours. If index transparency is used, then one of these 256 colours is assigned as transparent and the remaining 255 are used for other colours.
