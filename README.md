# hi.js

> Hi JavaScript/HTML/CSS.

## Purpose

Re-learning JavaScript/HTML/CSS and make a simple demo `hi.js`. JavaScript's syntax almost same with TypeScript/C, so don't worry about that.

## Features

- play video planet
- [WIP]show your profile page
- ...

## Structure

- example
- nodecourse
- hi.js
- hi.css
- hi.scss
- hi.html

## Install & Run

This demo need follows package to run:

- node/npm: run the JavaScript code
    - `brew install node` 
- sass: convert .scss to .css
    - `brew install sass/sass/sass` // install sass for macOS
    - use command `sass hi.scss [save_to_new_name.css]` to convert 

And then if you want to see the effect of this demo, please run follows command:

- `./hi hi.html`

## hi.js Sample

![page.png](https://github.com/i0Ek3/hi.js/blob/master/media/page.png)

## YSK

> JavaScript
- `let` same with `var`
- Number/String/Symbol/Undefined/Null/Object/Array/Boolean
- comma is optional
- JS have 4 methods to output content
    - console.log()
    - document.write()
    - document.getElementById(id).innerHTML = str
    - window.alert()
- declare method like this: `methodName function() {}`
- JavaScript event
- `==` different with `===`, the last one means abosulte euqal which required same type and value 
- `typeof`
- regex: `var p = /test/i`
- `try {} catch(e) {} finally {}`
- use keyword `debugger` and `console.log()` to debug code or F12 on Chrome browser
- becareful `hoisting(声明提升)`
- you cannot use undefined var in "strict mode" which declared on the top of code or function with "use strict"

> [CSS: Cascading Style Sheets](https://drafts.csswg.org/css-display/)
- selector {attr:value; ...;}
    - p {color:red; text-align:center;}
- `#` represents id on CSS
    - #para1 {color:red; text-align:center;}
- `.` represents class selector in CSS
    - .center {text-align:center;}
- style sheet
    - external style sheet: <link rel="stylesheet" type="text/css" href="hi.css">
    - internal style sheet: <style>css code</style>
    - inline style: `<p style="color:red;text-align:center">hi.js</p>`
- Sass
    - represent by .scss, it is a pre-processor of CSS
    - to support scss, we need install sass with command: `npm install -g sass`

> HTML
- just see example hi.html


## Standard

This repo support JavaScript ES6, HTML5 and CSS3.

## Credit

- [runoob.com](https://www.runoob.com)
- [HTML/CSS/JavaScript online](https://c.runoob.com/front-end/61)
