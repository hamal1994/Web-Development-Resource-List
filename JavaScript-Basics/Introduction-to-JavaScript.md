# JavaSript Basics 💥

## An introduction to JavaSript

Let’s see what’s so special about JavaScript, what we can achieve with it, and which other technologies play well with it.

### What is JavaScript?

JavaScript was initially created to “make web pages alive”.

The programs in this language are called scripts. They can be written right in a web page’s HTML and run automatically as the page loads.

Scripts are provided and executed as plain text. They don’t need special preparation or compilation to run.

In this aspect, JavaScript is very different from another language called Java.

## Why JavaScript? ℹ️

When JavaScript was created, it initially had another name: “LiveScript”. But Java was very popular at that time, so it was decided that positioning a new language as a “younger brother” of Java would help.

But as it evolved, JavaScript became a fully independent language with its own specification called ECMAScript, and now it has no relation to Java at all.

*************************************************************************

Today, JavaScript can execute not only in the browser, but also on the server, or actually on any device that has a special program called the JavaScript engine.

The browser has an embedded engine sometimes called a “JavaScript virtual machine”.

Different engines have different “codenames”. For example:

* V8 – in Chrome and Opera.
* SpiderMonkey – in Firefox.
* …There are other codenames like “Trident” and “Chakra” for different versions of IE, “ChakraCore” for Microsoft Edge, “Nitro” and “SquirrelFish” for Safari, etc.
The terms above are good to remember because they are used in developer articles on the internet. We’ll use them too. For instance, if “a feature X is supported by V8”, then it probably works in Chrome and Opera.

The terms above are good to remember because they are used in developer articles on the internet. We’ll use them too. For instance, if “a feature X is supported by V8”, then it probably works in Chrome and Opera.

*************************************************************************

## How do engines work? ℹ️

Engines are complicated. But the basics are easy.

* The engine (embedded if it’s a browser) reads (“parses”) the script.
* Then it converts (“compiles”) the script to the machine language.
* And then the machine code runs, pretty fast.
The engine applies optimizations at each step of the process. It even watches the compiled script as it runs, analyzes the data that flows through it, and applies optimizations to the machine code based on that knowledge. When it’s done, scripts run quite fast.

*************************************************************************

## What makes JavaScript unique?

There are at least three great things about JavaScript:

* Full integration with HTML/CSS.
* Simple things are done simply.
* Support by all major browsers and enabled by default.

*************************************************************************

## Author

* **Luke Ashton-Johnson** - *Initial work* - [KODN.IO](http://kodn.io/)