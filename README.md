# Light Swtich

Decoration for standart html input checkbox by pure CSS without any JS.

![](docs/demo.png)

# Demo

https://codepen.io/exsmund/pen/YzyeKpG


# Install

Install with npm: `npm install light-switch`.

Or install with yarn: `yarn add light-switch`.


# Usage

In SCSS:

```scss
@import "node_modules/checkbox-light-switch/scss/";
```

Or just copy CSS from `node_modules/checkbox-light-switch/dist/index.css` to your own code.


```html
<div>
    <input class="light-switch" type="checkbox" id="some_checkbox" />
    <label for="some_checkbox">Light</label>
</div>
```