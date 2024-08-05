# Fvursor v0.0.3

[![Preview](https://cdn.jsdelivr.net/gh/ahmetcanisik/fvursor/media/preview.gif)]

It wouldn't be bad to use a few custom cursors, like [figma](https://figma.com) does.

## How to use?

To use it, it is enough to have basic CSS knowledge. here is a usage example:

### Install with NPM

```bash
npm install fvursor@latest
```

#### Usage

```jsx
import 'fvursor';

#or commonjs

require("fvursor");
```

### Or use with CDN

To use it, you can place it between the head tags in your site's HTML file.
```html
<link href="https://cdn.jsdelivr.net/npm/fvursor@latest/min/index.css" rel="stylesheet" />
```

#### Usage

```
<!DOCTYPE html>
<html>
    <head>
        <!-- ... -->
        <link href="https://cdn.jsdelivr.net/npm/fvursor@latest/min/index.css" rel="stylesheet" />
    </head>
    <body>
        <!-- ... -->

        Try it <div class="cursor-default"> Cursor Default </div>
        Try it <div class="cursor-pointer"> Cursor Pointer </div>
        Try it <div class="cursor-not-allowed"> Cursor Not Allowed </div>
        Try it <div class="cursor-progress"> Cursor Progress </div>
        Try it <div class="cursor-text"> Cursor Text </div>
        Try it <div class="cursor-wait"> Cursor Wait </div>

        <!-- ... -->
    </body>
</html>
```

Or you can include it in your project with css.
```css

/* You can also include it in your project via cdn. */
@import url("https://cdn.jsdelivr.net/npm/fvursor@latest/min/index.css")

body {
    cursor: var(--cursor-default), default;
}

.pointer {
    cursor: var(--cursor-pointer), pointer;
}
```