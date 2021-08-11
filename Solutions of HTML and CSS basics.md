# Solutions of HTML and CSS basics
This file contains my attempt to the Knowledge Check section on [this page.](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/html-and-css-basics#knowledge-check)

> What is the difference between HTML and CSS?

HTML provides the structure of the page, CSS the (visual and aural) layout, for a variety of devices

> For accessibility in HTML, what is the attribute used to describe an image (on screen readers or if it fails to load)?

`alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.

> What is the difference between CSS Grid and Flexbox?

For me, an absolute beginner on web development, I would say the most significant difference is that Flexbox is one dimensional layout while Grid is two dimensional. This [link](https://css-tricks.com/quick-whats-the-difference-between-flexbox-and-grid/) contains more information about the difference. 

> For a responsive website, should it be designed mobile-first or desktop-first?

Mobile-first based on lots of information from Google. I will summarise some ideas from this [post](https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/).
  * Websites are naturally responsive before we even write a single line of CSS.
  * Mobile layouts tend to be very simple, making it very easy to start there. (Desktop-first can lead to redundant code) 

> Describe the components of the CSS Box Model.

This [link](https://www.w3schools.com/css/css_boxmodel.asp) is a very good reference for this.

> In CSS, what is a breakpoint?

In short, CSS breakpoints are points where the website content responds according to the device width, allowing you to show the best possible layout to the user. CSS breakpoints are also called media query breakpoints, as they are used with [media query](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries).

> What is a div and how are they used?

To my understanding, `div` is a container that can contain any HTML elments as you want. [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div) is a more comprehensive explanation.

> What are the two main groups of CSS properties that control typography style?

`font` and `text`. More detailed information are [about font](https://developer.mozilla.org/en-US/docs/Web/CSS/font) and [about text](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Text).

> What is the “query string” in a URL and what does it do?

A query string is a part of a URL and it can assign values to specific parameters. It is always in the form of `something=other` after a question mark `?` in a URL.

> What is the difference between “pixels” and “em”?

Pixel(px) is a static measurement while em are relative measurements. em is relative to the font-size of the element (2em means 2 times the size of the current font).

> How does inheritance work for CSS styles, i.e. how does an element get its “default” styles?

There are two ways for inheritance:
 * Inherited property: When no value for an inherited property has been specified on an element, the element gets the computed value of that property on its parent element. Only the root element of the document gets the initial value given in the property's summary.
 * The [inherit](https://developer.mozilla.org/en-US/docs/Web/CSS/inherit) keyword allows authors to explicitly specify inheritance. It works on both inherited and non-inherited properties.

> What are two CSS attributes you can change to push an element around on the page?

* `float`: While float defaults to none, setting this property to left or right ‘floats’ an element to the left or right of a container respectively, wrapping the rest of the content around it.
* `position`: The position property determines in what manner an item is positioned on the page or relative to one another.

> What are the three different ways to include a CSS stylesheet in your project or use CSS to style a particular element?
* Inline: To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
* Internal: The internal style is defined inside the `<style>` element, inside the head section.
* External: Each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section.

> What is the “default stylesheet” or “user agent stylesheet”?
* Default stylesheet: Every CSS property has a Formal Definition section. These Formal Definitions are a part of the W3C’s standardization of CSS, the organization that is in charge of the web’s standards.
* User agent stylesheet: The “User-Agent-Stylesheet” is the default CSS file that the browser companies implement in their browsers.
