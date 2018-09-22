# css-helper-classes
Css helpers for easier and quicker layout building. Maded as extra classes to work with bootstrap 4.*. 

## Installation
You can download zip file with project or install via NPM:
```bash
$ npm install css-helper-classes --save
```
## Basic usage
1. Include the stylesheet on your document's `<head>`

```html
<head>
  ...
  <link rel="stylesheet" href="./dist/css-helper-classes.min.css">
</head>
```
2. Choose from prepared classes what css property you want to change. Maybe some block in html code needs more "margin" at the bottom. Or you decided to enlarge "padding" from all 4 sides. Or your text should be bigger and bolder. 
```html
<div class="m_bottom_20 p_15 fs_20 fw_strong">Text</div>
```
![alt text](https://web-citrus.com/img/ex1.png)
## Class prefixes
| margin | padding | font-size | line-height | font-weight |
| :---: | :---: | :---: | :---: | :---: |
| ```m_``` | ```p_``` | ```fs_``` | ```lh_``` | ```fw_``` |

## Responsive styles
As I said above, these css classes better works with bootstrap 4. Thats why was added similar classes which depends on bootstrap grid breakpoints.

|  | Extra small | Small | Medium | Large | Extra large |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Viewport width** | <576px | ≥576px | ≥768px | ≥992px | ≥1200px |
| **Class suffix** |  | ```_sm_``` | ```_md_``` | ```_lg_``` | ```_xl_``` |
```html
<div class="m_bottom_sm_20 p_md_15 fs_lg_20 fw_strong">Responsive text</div>
```
## Couple examples

```html
<!-- Margin -->
<div class="m_0 m_bottom_15 m_bottom_sm_20 m_bottom_md_30 m_bottom_lg_45 m_bottom_xl_60">Margin text</div>

<!-- Padding -->
<div class="p_10 p_top_20 p_bottom_30 p_top_md_30 p_bottom_lg_45 p_top_xl_90">Padding text</div>

<!-- Font -->
<div class="fs_14 lh_16 fs_sm_18 lh_sm_20 fs_md_20 lh_md_22 fs_lg_24 lh_lg_26">Font text</div>

<!-- Combined -->
<div class="fs_14_combo fs_20_lg_combo p_15 p_lg_30 m_bottom_30 m_bottom_lg_45 fw_light">Combined text</div>
```
## License

(The MIT License)

Copyright (c) 2018 Sergii Bolinchuk

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**[⬆ back to top](#css-helper-classes)**