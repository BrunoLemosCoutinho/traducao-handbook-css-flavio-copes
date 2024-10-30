CSS is attached to an HTML page in different ways.

## 1: Using the `link` tag

The `link` tag is the way to include a CSS file. This is the preferred way to use CSS as it's intended to be used: one CSS file is included by all the pages of your site, and changing one line on that file affects the presentation of all the pages in the site.

To use this method, you add a `link` tag with the `href` attribute pointing to the CSS file you want to include. You add it inside the `head` tag of the site (not inside the `body` tag):

```html
<link rel="stylesheet" type="text/css" href="myfile.css">
```

The `rel` and `type` attributes are required too, as they tell the browser which kind of file we are linking to.

## 2: using the `style` tag

Instead of using the `link` tag to point to separate stylesheet containing our CSS, we can add the CSS directly inside a `style` tag. This is the syntax:

```html
<style>
...our CSS...
</style>
```

Using this method we can avoid creating a separate CSS file. I find this is a good way to experiment before "formalising" CSS to a separate file, or to add a special line of CSS just to a file.

## 3: inline styles

Inline styles are the third way to add CSS to a page. We can add a `style` attribute to any HTML tag, and add CSS into it.

```html
<div style="">...</div>
```

Example:

```html
<div style="background-color: yellow">...</div>
```

