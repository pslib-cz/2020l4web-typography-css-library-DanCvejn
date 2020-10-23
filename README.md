# Typography CSS library
**Author:** *Daniel Cvejn*
## Demo site

**Example of the typography [here](https://pslib-cz.github.io/2020l4web-typography-css-library-DanCvejn/).**

## Dependecies

The usage of the css is on you.

## Implementation
Just download css file and link it to your html.
```
    <link rel="stylesheet" href="./*/typography.css">
```
"*" = folder where you have css files.

If you have it in the same folder as the html file then use this: 
```
    <link rel="stylesheet" href="./typography.css"> 
```
Next download these two **fonts**:
* [Merriweather](https://fonts.google.com/specimen/Merriweather?query=mer)
    - Just regular will be enough
* [Work Sans](https://fonts.google.com/specimen/Work+Sans?query=work)
    - Just regular and bold
    
Put fonts in the folder that is called *font* and this folder has to be in the same folder as the css file.

## Usage

Whole content put in **div** that has class *content* just like this:
```
<body>
    <div class="content">
        <section>...</section>
    </div>
</body>
```
First **section** have to has class *first* like this:
```
<body>
    <div class="content">
        <section class="first">...</section>
        <section>...</section>
        <section>...</section>
    </div>
</body>
```
Every image put in **div** with class *img* and if you want some description for it, put **p** with class *description* behind it:
```
    <div class="img">
        <img src="./your-image.jpg" alt="description">
        <p class="description">Description of the picture...</p>
    </div>
```
For every button use class *btn*, you can use it for **a** or **button**:
```
    <a href=".yourlink" class="btn">Link</a>
```
## Components

I changed:
- [x] Headings 1-6
- [x] Sections
- [x] Lists styles
- [ ] Table
- [x] Buttons
