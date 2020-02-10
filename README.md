# TYPEN

You can check the example [here](https://crasty01.github.io/typen/).

## DESCRIPTION

Typen is a typographic library created with SCSS (.scss), created as a school project.
It includes styles for headlines (h1 - h6), special text markups (links, code, strong, q ...), images (with figcaption), lists (ul, ol, dl), basic tables, forms, buttons, and more.
Roboto is used by default.

## TABLE OF CONTENT

1. [Installation](#Installation)
2. [Usage](#Usage)
3. [Docs](#Docs)
    1. [Typography](#Typography)
    2. [Quotes and blockquotes](##quotes-and-blockquotes)
    3. [Buttons](#Buttons)
    4. [Lists](#Lists)
    5. [Forms](#Forms)
    6. [Tables](#Tables)
    7. [Codes](#Codes)
    8. [Images](#Images)
4. [Plan](#Plan)
4. [End](#End)

## INSTALLATION

1. Download, fork, clone library
2. Link **typen.css** to your HTML page (or somethng else)
3. You're done!

Optionally you can either edit main.css or (if you have sass/scss compiler) .scss files.

## USAGE

Theoretically, you don't have to do anything - just link the file and that's it. Practically, you have to do the whole rest of your project 🙃

## DOCS

### TYPOGRAPHY

#### Usable headlines and their sizes
`<h1>` is 46px, `<h2>` is 36px, `<h3>` is 28px, `<h4>` is 22px, `<h5>` is 18px, `<h6>` is 16px

#### Usable markdown tags
`<u>`, `<s>`, `<i>`, `<b>`, `<time>`, `<mark>`, `<small>`, `<strong>`, `<em>`, `<a>`

### QUOTES AND BLOCKQUOTES

#### Quotes

standard quote tag `<q>` is „quote“

#### Blockquotes

standard blockquote syntax is:

![blockquote](https://github.com/pslib-cz/2019l4web-typography-css-library-crasty01/blob/master/example-images/blockquote.jpg)

### BUTTONS

#### Works for

`<a class="button">`
`<button>`
`<input type="submit">`
`<input type="reset">`
`<input type="button">`
`<div class="button">`

#### Types

Buttons are either enabled or disabled.

Buttons can be default (filled), outlined or clear.

### LISTS

Typen can formate unordered list, ordered list or description list

### FORMS

Typen can format all fields (Text, Email, Number, Password, Select, Search, Tel, URL, Radio, Checkbox, Textarea), legend, label, and buttons reset and submit.

### TABLES

standard table syntax is:

![blockquote](https://github.com/pslib-cz/2019l4web-typography-css-library-crasty01/blob/master/example-images/table.jpg)

### CODES

Typen can format your code. The best way is use in combination with `<pre>` tag (preserves spaces and line breaks).

![blockquote](https://github.com/pslib-cz/2019l4web-typography-css-library-crasty01/blob/master/example-images/code.jpg)

### IMAGES

Typen formates your images just elementally. The best way is use in combination in `<figure>` and `<figcaption>` tags

![blockquote](https://github.com/pslib-cz/2019l4web-typography-css-library-crasty01/blob/master/example-images/img.jpg)

### FLOAT

For fast way to float just use `class="float-right"` or `class="float-left"`.


## PLAN

- [x] Headings + deffrent types of text (strong, marked...)
- [x] Blockquotes
- [x] Buttons (disabled, outlined, clear ...)
- [x] Lists (ul, ol, dl)
- [x] Forms (fields, radio, checkbox, text area ...)
- [x] Tables
- [x] Codes
- [x] Floats
- [x] Images
- [x] Documentation
- [ ] Print css

## THE END

Live long and prosper 🖖

Created by [Daniel Vondra](https://danielvondra.tk)