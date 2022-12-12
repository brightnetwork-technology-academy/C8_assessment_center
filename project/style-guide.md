# Front-End Style Guide

This document will outline many of the CSS properties you may use in the coming days while also providing links to useful resources to help kick-start your web-development learning. Alongside this document there will also be a Figma board provided which houses many example components which you may consider using in your site. The end of the document then details some of the design properties of the example (Doritos) site.

[Figma Example Design Board](https://www.figma.com/file/Fs56TNlz7KIIxW9s7JoKKA/BNTA-Foundation-Days?node-id=0%3A1)

If you have any trouble accessing the Figma board above then please reach out to one of the BNTA Team.

Many of the design elements involve CSS properties which you may not have covered in the initial teaching, however there are many great online resources which we hope to point you towards. Googling the names of the properties below should bring up some resources. If not, chuck "mdn" or "css" at the front and they should appear. Take initiative, search online if you are stuck and talk things through with your teammates!



## Picking Colours & Images

When choosing a design, it's a great idea to choose a colour palette and some placeholder images to really make your website pop. The websites listed below should help with these choices:

**Images**

- [https://unsplash.com/](https://unsplash.com/)
- [https://placebear.com/](https://placebear.com/)

**Colours & Palettes**  

- [https://coolors.co/](https://coolors.co/)
- [https://paletton.com/](https://paletton.com/)
- [https://www.color-hex.com/](https://www.color-hex.com/)
          
          
                    
## Developer Tools

Regardless of what browser you are using, developer tools will be provided. They can be opened by right-clicking a webpage and clicking "Inspect" or through the relevant key-binds. You will find a lot of useful information there including the DOM tree (effectively the list of HTML elements for the site) and a list of the CSS applied to the selected element (under "Elements" > "Styles" & "Computed"). Using these tools can help give you a great idea for how your website is coming together and is great for debugging problems.

Windows / Linux     - `[F12]` or `[Ctrl]` + `[Shift]` + `[I]`

Mac                 - `[Command]` + `[Option]` + `[I]`



## The Box Model
[MDN - Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)

Items on a webpage all use the Box Model to define their spacing. It works in stages radiating outward first with the Content, followed by the Padding, then Border and lastly the Margin. Proper understanding of the Box Model is a key part to building a website. Within the "Computed" tab of the DevTools, you can inspect the Model of a selected element and even visualise each layer on the page (hover over the box).



## CSS: Property - Effect

**Colours and Fonts**

| Attribute | Description |
| :--- | :--- |
|Color               | Changes the text colour (NOTE: American spelling)|
|Background-color    | Changes the background colour (NOTE: American spelling)|
|Font-size           | Changes the font size|
|Font-family         | Changes the font family. Many fonts are included by default (Free fonts can be found at https://fonts.google.com/)|
|Font-weight         | Changes the weighting of the text ("boldness")|
|Font-style          | Changes the styling of the font. Can be used for italics|

**Spatial organisation**

| Attribute | Description |
| :--- | :--- |
|Padding             | Changes the spacing surrounding the content|
|Border              | Changes the border style, colour and width|
|Margin              | Changes the outermost spacing property|
|Border-radius       | Changes how round a box's corners are. Setting border-radius: 50% on a square element makes it circular|

**Sizing**

| Attribute | Description |
| :--- | :--- |
|Height              | Sets the height of the element|
|Width               | Sets the width of the element|
|Max-/min-Height     | Sets the extreme height bounds of the element|
|Max-/min-Width      | Sets the extreme width bounds of the element|

**Images**

| Attribute | Description |
| :--- | :--- |
|Object-fit          | Changes the way an image sits within their container (eg. whether it stretches or crops parts to fit)|

**Display & Flexbox**

| Attribute | Description |
| :--- | :--- |
|Position            | Sets how an element is positioned in a document (default is "position: static". See "absolute" for stacking elements)|
|Display             | Sets how an element is displayed, whether inline or as a block. Also changes layout of children|
|Display: flex       | Used to create a FlexBox, arranging the child elements according to Flex (1D display type, can give 2D effect)|
|Justify-content     | Sets how children are positioned relative to the main axis of a FlexBox|
|Align-items         | Sets how children are positioned relative to the cross-axis of a FlexBox|
|Display: grid       | Used to create a CSS Grid, arranging the child elements in a grid (2D display type)|



## Colour Value Types
[MDN - Applying Colour](https://developer.mozilla.org/en-US/docs/Web/HTML/Applying_color)

| Type | Description |
| :--- | :--- |
|Names               | Values such as "blue", "yellow" or "rebeccapurple"|
|HexCodes            | Hexadecimal codes of the form: #ABC123. Each value can be 1-9 or A-F. Each two values defines an intensity of Red, Green & Blue|
|RGBA                | Of the form: rgba(red, green, blue, alpha) where the first three vary 0-255, and the final 0-1. Alpha is the transparency channel|
|HSL                 | Of the form: hsl(hue, saturation, luminosity). Sometimes includes an alpha channel also. Hue: 0-360 deg, sat. & lum. 0-100%|

## Unit Types
[Medium - Unit Types](https://medium.com/@dixita0607/css-units-for-font-size-px-em-rem-79f7e592bb97)

| Type | Description |
| :--- | :--- |
|px                  | Absolute values of pixels|
|rem                 | A value relative to the sizing of font set on the HTML root element. Default is 16px|
|em                  | A value relative to the sizing of font set on the parent HTML element|
|%                   | A value relative to the size of the parent element|


## Doritos Example Site
Below are some of the CSS values to give you an idea of:

### Layout

The designs were created to the following widths:

- Desktop: 1280px

### Colours

**Primary**

- Light Grey: rgb(196, 196, 196)
- Slightly Transparent Black: rgba(0, 0, 0, .9)
- Tangy Cheese Orange: #f56e08
- Pink: hsl(322, 100%, 66%)
- Light Pink: hsl(321, 100%, 78%)
- Light Red: hsl(0, 100%, 63%)

**Neutral**

- Very Dark Cyan: hsl(192, 100%, 9%)
- Very Pale Blue: hsl(207, 100%, 98%)

### Typography

**Headings**

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 700

**Body**

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400, 600, 700

### Icons

For icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)