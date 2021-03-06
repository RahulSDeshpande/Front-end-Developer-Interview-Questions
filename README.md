#Front-end Job Interview Questions

This repo contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

[Rebecca Murphey](http://rmurphey.com/)'s [Baseline For Front-End Developers](http://rmurphey.com/blog/2012/04/12/a-baseline-for-front-end-developers/) is also a great resource to read up on before you head into an interview.

**Note:** Keep in mind that many of these questions are open ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## <a name='toc'>Table of Contents</a>

  1. [Original Contributors](#contributors)
  1. [General Questions](#general)
  1. [HTML Questions](#html)
  1. [CSS Questions](#css)
  1. [JS Questions](#js)
  1. [jQuery Questions](#jquery)
  1. [Coding Questions](#jscode)
  1. [Fun Questions](#fun)
  1. [Other Great References](#references)

####[[⬆]](#toc) <a name='contributors'>Original Contributors:</a>

The majority of the questions were plucked from an [oksoclap](http://oksoclap.com/) thread created originally by [Paul Irish](http://paulirish.com) ([@paul_irish](http://twitter.com/paul_irish)) and contributed to by the following individuals:

* [@bentruyman](http://twitter.com/bentruyman) - http://bentruyman.com
* [@cowboy](http://twitter.com/cowboy) - http://benalman.com
* [@ajpiano](http://ajpiano) - http://ajpiano.com
* [@SlexAxton](http://twitter.com/slexaxton) - http://alexsexton.com
* [@boazsender](http://twitter.com/boazsender) - http://boazsender.com
* [@miketaylr](http://twitter.com/miketaylr) - http://miketaylr.com
* [@vladikoff](http://twitter.com/vladikoff) - http://vladfilippov.com
* [@gf3](http://twitter.com/gf3) - http://gf3.ca
* [@jon_neal](http://twitter.com/jon_neal) - http://twitter.com/jon_neal
* [@wookiehangover](http://twitter.com/wookiehangover) - http://wookiehangover.com
* [@iansym](http://twitter.com/iansym) - http://twitter.com/iansym

####[[⬆]](#toc) <a name='general'>General Questions:</a>

* What did you learn yesterday/this week?
* What excites or interests you about coding?
* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
* Talk about your preferred development environment. (OS, Editor, Browsers, Tools etc.)
* Which version control systems are you familiar with?
* Can you describe your workflow when you create a web page?
* If you have 5 different stylesheets, how would you best integrate them into the site?
  * Points off for `@import` directives.
  * File concatenation
* Can you describe the difference between progressive enhancement and graceful degradation?
  * Bonus points for describing feature detection
* Explain what "Semantic HTML" means.
* How would you optimize a websites assets/resources?
  * Looking for a number of solutions which can include:
    * File concatenation
    * File minification
    * CDN Hosted
    * Caching
    * etc.
* Traditionally, why has it been better to serve site assets from multiple domains?
  * How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
    * Bonus points for identifying mobile as a possible downside (http://www.mobify.com/blog/domain-sharding-bad-news-mobile-performance/)
    * Bonus points for identifying SDPY as an exception
* Name 3 ways to decrease page load. (perceived or actual load time)
* If you jumped on a project and they used tabs and you used spaces, what would you do?
  * Suggest the project utilize something like EditorConfig (http://editorconfig.org)
  * Conform to the conventions (stay consistent)
  * `issue :retab! command`
* Write a simple slideshow page
  * Bonus points if it does not use JS.
* What tools do you use to test your code's performance?
  * Profiler, JSPerf, Dromaeo
* If you could master one technology this year, what would it be?
* What are the differences between Long-Polling, Websockets and SSE?
* Explain the importance of standards and standards bodies.
* What is FOUC? How do you avoid FOUC?
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.

####[[⬆]](#toc) <a name='html'>HTML Questions:</a>

* What's a `doctype` do?
* What's the difference between standards mode and quirks mode?
* What are the limitations when serving XHTML pages?
  * Are there any problems with serving pages as `application/xhtml+xml`?
* How do you serve a page with content in multiple languages?
  * What kind of things must you be wary of when design or developing for multilingual sites?
* What are `data-` attributes good for?
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
* Describe the difference between cookies, sessionStorage and localStorage.
* Can you explain the difference between `GET` and `POST`?

####[[⬆]](#toc) <a name='css'>CSS Questions:</a>

* Describe what a "reset" CSS file does and how it's useful.
* Describe Floats and how they work.
* Describe z-index and how stacking context is formed.
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when?
* CSS property hacks, conditionally included .css files, or... something else?
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* What are the different ways to visually hide content (and make it available only for screen readers)?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* Any familiarity with styling SVG?
* How do you optimize your webpages for print?
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors? (SASS, Compass, Stylus, LESS)
  * If so, describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
  * Webfonts (font services like: Google Webfonts, Typekit etc.)
* Explain how a browser determines what elements match a CSS selector?
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
* What does ```* { box-sizing: border-box; }``` do? What are its advantages? 
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?
* What's the difference between a relative, fixed, absolute and statically positioned element?
* What existing CSS frameworks have you used locally, or in production? (Bootstrap, PureCSS, Foundation etc.)
  * If so, which ones? If you could, how would you change/improve them? 
* Have you played around with the new CSS Flexbox or Grid specs?
  * If so, what do you think of them from a performance standpoint? 

####[[⬆]](#toc) <a name='js'>JS Questions:</a>

* Explain event delegation
* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* How do you go about testing your JavaScript?
* AMD vs. CommonJS?
* What's a hashtable?
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`. 
  * What needs to be changed to properly make it an IIFE?
* What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  * How would you go about checking for any of these states?
* What is a closure, and how/why would you use one?
* What's a typical use case for anonymous functions?
* Explain the "JavaScript module pattern" and when you'd use it.
  * Bonus points for mentioning clean namespacing.
  * What if your modules are namespace-less?
* How do you organize your code? (module pattern, classical inheritance?)
* What's the difference between host objects and native objects?
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
* What's the difference between `.call` and `.apply`?
* explain `Function.prototype.bind`?
* When do you optimize your code?
* Can you explain how inheritance works in JavaScript?
* When would you use `document.write()`?
  * Most generated ads still utilize `document.write()` although its use is frowned upon
* What's the difference between feature detection, feature inference, and using the UA string
* Explain AJAX in as much detail as possible
* Explain how JSONP works (and how it's not really AJAX)
* Have you ever used JavaScript templating?
  * If so, what libraries have you used? (Mustache.js, Handlebars etc.)
* Explain "hoisting".
* Describe event bubbling.
* What's the difference between an "attribute" and a "property"?
* Why is extending built in JavaScript objects not a good idea?
* Why is extending built ins a good idea?
* Difference between document load event and document ready event?
* What is the difference between `==` and `===`?
* Explain how you would get a query string parameter from the browser window's URL.
* Explain the same-origin policy with regards to JavaScript.
* Describe inheritance patterns in JavaScript.
* Make this work:
```javascript
[1,2,3,4,5].duplicate(); // [1,2,3,4,5,1,2,3,4,5]
```
* Describe a strategy for memoization (avoiding calculation repetition) in JavaScript.
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
* What is the arity of a function?
* What is `"use strict";`? what are the advantages and disadvantages to using it?

####[[⬆]](#toc) <a name='jquery'>jQuery Questions:</a>

* Explain "chaining".
* Explain "deferreds".
* What are some jQuery specific optimizations you can implement?
* What does `.end()` do?
* How, and why, would you namespace a bound event handler?
* Name 4 different values you can pass to the jQuery method.
  * Selector (string), HTML (string), Callback (function), HTMLElement, object, array, element array, jQuery Object etc.
* What is the effects (or fx) queue?
* What is the difference between `.get()`, `[]`, and `.eq()`?
* What is the difference between `.bind()`, `.live()`, and `.delegate()`?
* What is the difference between `$` and `$.fn`? Or just what is `$.fn`.
* Optimize this selector:
```javascript
$(".foo div#bar:eq(0)")
```

####[[⬆]](#toc) <a name='jscode'>Code Questions:</a>


```javascript
modulo(12, 5) // 2
```
*Question: Implement a modulo function that satisfies the above*


```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
*Question: What value is returned from the above statement?*

**Answer: "goh angasal a m'i"**

```javascript
( window.foo || ( window.foo = "bar" ) );
```
*Question: What is the value of `window.foo`?*

**Answer: "bar"** *(only if `window.foo` was falsey otherwise it will retain its value)*

```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
*Question: What is the outcome of the two alerts above?*

**Answer: "Hello World" & ReferenceError: bar is not defined**

```javascript
var foo = [];
foo.push(1);
foo.push(2);
```
*Question: What is the value of `foo.length`?*

**Answer: `2`**

####[[⬆]](#toc) <a name='fun'>Fun Questions:</a>

* What's a cool thing you've coded recently? What's something you've built that you're proud of?
* What are some things you like about the developer tools you use?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?

####[[⬆]](#toc) <a name='references'>Other Great References:</a>

* http://programmers.stackexchange.com/questions/46716/what-technical-details-should-a-programmer-of-a-web-application-consider-before
* http://www.nczonline.net/blog/2010/01/05/interviewing-the-front-end-engineer/
* http://css-tricks.com/interview-questions-css/
* http://davidshariff.com/quiz/
* http://blog.sourcing.io/interview-questions
