Before moving on, I want to give you a brief recap of the history of CSS.

CSS was grown out of the necessity of styling web pages. Before CSS was introduced, people wanted a way to style their web pages, which looked all very similar and "academic" back in the day. You couldn't do much in terms of personalisation.

HTML 3.2 introduced the option of defining colors inline as HTML element attributes, and presentational tags like `center` and `font`, but that escalated quickly into a far from ideal situation.

CSS let us move everything presentation-related from the HTML to the CSS, so that HTML could get back being the format that defines the structure of the document, rather than how things should look in the browser.

CSS is continuously evolving, and CSS you used 5 years ago might just be outdated, as new idiomatic CSS techniques emerged and browsers changed.

It's hard to imagine the times when CSS was born and how different the web was.

At the time, we had several competing browsers, the main ones being Internet Explorer or Netscape Navigator.

Pages were styled by using HTML, with special presentational tags like `bold` and special attributes, most of which are now deprecated.

This meant you had a limited amount of customisation opportunities.

The bulk of the styling decisions were left to the browser.

Also, you built a site specifically for one of them, because each one introduced different non-standard tags to give more power and opportunities.

Soon people realised the need for a way to style pages, in a way that would work across all browsers.

After the initial idea proposed in 1994, CSS got its first release in 1996, when the CSS Level 1 ("CSS 1") recommendation was published.

CSS Level 2 ("CSS 2") got published in 1998.

Since then, work began on CSS Level 3. The CSS Working Group decided to split every feature and work on it separately, in modules.

Browsers weren't especially fast at implementing CSS. We had to wait until 2002 to have the first browser implement the full CSS specification: IE for Mac, as nicely described in this CSS Tricks post: https://css-tricks.com/look-back-history-css/

Internet Explorer implemented the box model incorrectly right from the start, which led to years of pain trying to have the same style applied consistently across browsers. We had to use various tricks and hacks to make browsers render things as we wanted.

Today things are much, much better. We can just use the CSS standards without thinking about quirks, most of the time, and CSS has never been more powerful.

We don't have official release numbers for CSS any more now, but the CSS Working Group releases a "snapshot" of the modules that are currently considered stable and ready to be included in browsers. This is the latest snapshot, from 2018: https://www.w3.org/TR/css-2018/

CSS Level 2 is still the base for the CSS we write today, and we have many more features built on top of it.