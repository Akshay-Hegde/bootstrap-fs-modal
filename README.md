# Bootstrap Mobile FullScreen Modal
A simple way to improve UX of Bootstrap modals on mobile phones.

Regular Bootstrap modals (with a lot of content) on mobile devices can cause additional scrolling to get to the bottom buttons of modal.

Fullscreen modal provides more native user experience on mobile phones, here is side-by-side comparison of regular and fullscreen modals:

![Regular Bootstrap Modal on Phone](http://i.imgur.com/Calp2Rb.gif)
![Fullscreen Bootstrap Modal on Phone](http://i.imgur.com/uIWVS1Q.gif)

Fullscreen modal does not affect modals in large viewports, and applies these styles only on mobile devices.

Live demo page is here - https://keaukraine.github.io/bootstrap-fs-modal/

## How to Use

You can obtain plugin either from GitHub or from npm, package name is `bootstrap4-fs-modal`.

This plugin is implemented purely in CSS, so all you need is to include CSS from `dist` folder:

```html
<link href="dist/css/bootstrap-fs-modal.min.css" rel="stylesheet">
```

Then, you have two options to make modals use updated styles:
 * add `modal-fullscreen` CSS class to modals which you want to work full-screen.
 * add `bootstrap-fs-modal` CSS class to container element for all modals within this element to receive updated styles.

Examples:

```html
  <div class="modal fade modal-fullscreen" ...>
     ...
  </div>
```

```html
<body class="bootstrap-fs-modal">
    <div class="modal fade" ...>
       ...
    </div>
</body>
```


## Used Libraries
* Twitter Bootstrap used under the MIT License https://github.com/twbs/bootstrap/blob/master/LICENSE

## License

**The MIT License**

Copyright (c) 2017 Oleksandr Popov

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
