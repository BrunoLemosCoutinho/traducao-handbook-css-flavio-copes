**CSS** (an abbreviation of **Cascading Style Sheets**) is the language that we use to style an HTML file, and tell the browser how should it render the elements on the page.

> In this book I talk exclusively about styling HTML documents, although CSS can be used to style other things too.

A CSS file contains several CSS rules.

Each rule is composed by 2 parts:

- the **selector**
- the **declaration block**

The selector is a string that identifies one or more elements on the page, following a special syntax that we'll soon talk about extensively.

The declaration block contains one or more **declarations**, in turn composed by a **property** and **value** pair.

Those are all the things we have in CSS.

Carefully organising properties, associating them values, and attaching those to specific elements of the page using a selector is the whole argument of this ebook.

## How does CSS look like

A CSS **rule set** has one part called **selector**, and the other part called **declaration**. The declaration contains various **rules**, each composed by a **property**, and a **value**.

In this example, `p` is the selector, and applies one rule which sets the value `20px` to the `font-size` property:

```css
p {
  font-size: 20px;
}
```

Multiple rules are stacked one after the other:

```css
p {
  font-size: 20px;
}

a {
  color: blue;
}
```

A selector can target one or more items:

```js
p, a {
  font-size: 20px;
}
```

and it can target HTML tags, like above, or HTML elements that contain a certain class attribute with `.my-class`, or HTML elements that have a specific `id` attribute with `#my-id`.

More advanced selectors allow you to choose items whose attribute matches a specific value, or also items which respond to pseudo-classes (more on that later)

## Semicolons

Every CSS rule terminates with a semicolon. Semicolons are **not** optional, except after the last rule, but I suggest to always use them for consistency and to avoid errors if you add another property and forget to add the semicolon on the previous line.

## Formatting and indentation

There is no fixed rule for formatting. This CSS is valid:

```css
      p
      {
  font-size:           20px   ;
                      }

a{color:blue;}
```

but a pain to see. Stick to some conventions, like the ones you see in the examples above: stick selectors and the closing brackets to the left, indent 2 spaces for each rule, have the opening bracket on the same line of the selector, separated by one space.

Correct and consistent use of spacing and indentation is a visual aid in understanding your code.
