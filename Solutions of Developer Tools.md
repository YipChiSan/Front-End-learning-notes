# Solutions of Developer Tools
This file contains my attempt to the Knowledge Check section on this [page](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/developer-tools#knowledge-check)

> How do you open developer tools in your browser?
* When you want to work with the DOM or CSS, right-click an element on the page and select Inspect to jump into the Elements panel. Or press Command+Option+C (Mac) or Control+Shift+C (Windows, Linux, Chrome OS).
* When you want to see logged messages or run JavaScript, press Command+Option+J (Mac) or Control+Shift+J (Windows, Linux, Chrome OS) to jump straight into the Console panel.

> How do you select a specific element on your page with your browser’s developer tools?

Right-click an element and select Inspect. The Elements panel of DevTools opens. The selected element is highlighted in the DOM Tree.

> How do you change CSS in real time on specific elements of a web page with your browser’s developer tools?

The **Styles** tab on the **Elements** panel lists the CSS rules being applied to whatever element is currently selected in the DOM Tree. Then we can simply add or change CSS of an element under Style tab.

> What does a strikethrough in a CSS element mean in your browser’s developer tools?

When a CSS property shows as struck-through, it means that the crossed-out style was applied, but then overridden by a more specific selector, a more local rule, or by a later property within the same rule.

> How do you check every inherited style for an element in your browser’s developer tools?

It is simply displayed on the **Styles** tab.

> How do you edit HTML in real time in your browser’s developer tools?

You can edit the HTML — tags, attributes, and content — directly in the HTML pane: double-click the text you want to edit, change it, and press Enter to see the changes reflected immediately. To edit an element's outerHTML, activate the element's popup menu and select "Edit As HTML". You'll see a text box in the HTML pane and then you can add any HTML codes you need.
