HTML Links - Syntax
The HTML <a>tag defines a hyperlink. It has the following syntax:

<a href="url">link text</a>
The most important attribute of the <a>element is the hrefattribute, .

The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.

HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The targetattribute specifies where to open the linked document.

The targetattribute can have one of the following values:

_self- Default. Opens the document in the same window/tab as it was clicked
_blank- Opens the document in a new window or tab
_parent- Opens the document in the parent frame
_top- Opens the document in the full body of the window
Absolute URLs vs. Relative URLs
Both examples above are using an absolute URL(a full web address) in the hrefattribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

 

CSS layout
At this point we've already looked at CSS fundamentals, how to style text, and how to style and manipulate the boxes that your content sits inside. Now it's time to look at how to place your boxes in the right place in relation to the viewport, and one another. We have covered the necessary prerequisites so we can now dive deep into CSS layout, looking at different display settings, modern layout tools like flexbox, CSS grid, and positioning, and some of the legacy techniques you might still want to know about.

Introduction to CSS layout (Links to an external site.)This article will recap some of the CSS layout features we've already touched upon in previous modules — such as different display (Links to an external site.) values — and introduce some of the concepts we'll be covering throughout this module.Normal flow (Links to an external site.)Elements on webpages lay themselves out according to normal flow - until we do something to change that. This article explains the basics of normal flow as a grounding for learning how to change it.Flexbox (Links to an external site.)Flexbox (Links to an external site.) is a one-dimensional layout method for laying out items in rows or columns. Items flex to fill additional space and shrink to fit into smaller spaces. This article explains all the fundamentals. After studying this guide you can test your flexbox skills (Links to an external site.) to check your understanding before moving on.Grids (Links to an external site.)CSS Grid Layout is a two-dimensional layout system for the web. It lets you lay content out in rows and columns, and has many features that make building complex layouts straightforward. This article will give you all you need to know to get started with page layout, then test your grid skills (Links to an external site.) before moving on.Floats (Links to an external site.)Originally for floating images inside blocks of text, the float (Links to an external site.) property became one of the most commonly used tools for creating multiple column layouts on webpages. With the advent of Flexbox and Grid it has now returned to its original purpose, as this article explains.Positioning (Links to an external site.)Positioning allows you to take elements out of the normal document layout flow, and make them behave differently, for example sitting on top of one another, or always remaining in the same place inside the browser viewport. This article explains the different position (Links to an external site.) values, and how to use them.Multiple-column layout (Links to an external site.)The multiple-column layout specification gives you a method of laying content out in columns, as you might see in a newspaper. This article explains how to use this feature.Responsive design (Links to an external site.)As more diverse screen sizes have appeared on web-enabled devices, the concept of responsive web design (RWD) has appeared: a set of practices that allows web pages to alter their layout and appearance to suit different screen widths, resolutions, etc. It is an idea that changed the way we design for a multi-device web, and in this article we'll help you understand the main techniques you need to know to master it.Beginner's guide to media queries (Links to an external site.)The CSS Media Query gives you a way to apply CSS only when the browser and device environment matches a rule that you specify, for example "viewport is wider than 480 pixels". Media queries are a key part of responsive web design, as they allow you to create different layouts depending on the size of the viewport, but they can also be used to detect other things about the environment your site is running on, for example whether the user is using a touchscreen rather than a mouse. In this lesson you will first learn about the syntax used in media queries, and then move on to use them in a worked example showing how a simple design might be made responsive.Legacy layout methods (Links to an external site.)Grid systems are a very common feature used in CSS layouts, and before CSS Grid Layout they tended to be implemented using floats or other layout features. You imagine your layout as a set number of columns (e.g. 4, 6, or 12), and then fit your content columns inside these imaginary columns. In this article we'll explore how these older methods work, in order that you understand how they were used if you work on an older project.Supporting older browsers (Links to an external site.)

In this module we recommend using Flexbox and Grid as the main layout methods for your designs. However there will be visitors to your site who use older browsers, or browsers which do not support the methods you have used. This will always be the case on the web — as new features are developed, different browsers will prioritise different things. This article explains how to use modern web techniques without locking out users of older technology.

Assessment: Fundamental layout comprehension (Links to an external site.)An assessment to test your knowledge of different layout methods by laying out a webpage.

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

JavaScript Function Syntax
A JavaScript function is defined with the functionkeyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

 

Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

 
