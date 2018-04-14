### Fullstack Node.js

#### Node.js in the wild

---
@title[Introduction]

### State of affaires

In the last few years Node.js matured and became the "goto" platform Fromm startups to enterprises everyone want to use and adopt this new(?) technology.

+++

Open source and the [the unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) - do one thing and do it well, are the pillars of Node.js and its ecosystem.

+++

The amount and availability of free and open source code, frameworks, tools and addon for Node.js ecosystem is unparalleled to any development platform that came before.

+++

A good Node.js developer knows how to choose the right solution from the wide array of existing solutions, a smart developer knows how to write his own solution from scratch, and the wise knows when to not to use Node.js at all...

+++

<a href="http://www.azquotes.com/quote/267248" title="William Shakespeare quote"><img src="http://www.azquotes.com/picture-quotes/quote-a-fool-thinks-himself-to-be-wise-but-a-wise-man-knows-himself-to-be-a-fool-william-shakespeare-26-72-48.jpg" alt="A fool thinks himself to be wise, but a wise man knows himself to be a fool. - William Shakespeare"></a>

Always keep on learning.

---

@title[TOC]

### Fullstack Skills

@ul

- Large scale code design
- High level system architecture
- Knowledge of leading JS libraries and frameworks
- SaaS solutions - pros and cons
- Devops tools and workflows

@ulend

---

@title[Code design]

### Code design

Javascript was developed in 1995 by Netscape under two week to serve as a "glue language" embedded inside HTML pages. It had many engines and conflicting standards in its early days, the missing parts were filled by polyfills or other intermediate languages, the best ones found there way back to the language (Promises, coffeescript, async/await, etc').

+++

As a multi-paradigm language, JavaScript supports event-driven, functional, and imperative (including object-oriented and prototype-based) programming styles [*](https://en.wikipedia.org/wiki/JavaScript).

+++

The true power of javascript is the ability to write multi-paradigm code effortlessly, taking the best part of each paradigm would lead to better code, ALWAYS choose the simpler solution NOT the "correct" one!

+++

Code styles/paradigms comes and goes, in the long run it is better to try out new approaches some will stick.

And remember even if you don't like code style/paradigm you still need to know how to read and use it.

+++

<a href="http://www.azquotes.com/quote/765126" title="Alan Perlis quote"><img src="http://www.azquotes.com/picture-quotes/quote-a-language-that-doesn-t-affect-the-way-you-think-about-programming-is-not-worth-knowing-alan-perlis-76-51-26.jpg" alt="A language that doesn't affect the way you think about programming is not worth knowing. - Alan Perlis"></a>

---

### Large scale design

General tips:

- Centralize dependencies - it would make for easier updates.
- Domain driven design - works grate with event-driven system.
- Automation - build, test, deploy from day one - it force proper dependencies management.
- Good practices - pick code style guide, linter, tests, git branches from day one.

+++

### Code maintenance 

<a href="http://www.azquotes.com/quote/803741" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-javascript-is-the-only-language-that-i-m-aware-of-that-people-feel-they-don-t-need-to-douglas-crockford-80-37-41.jpg" alt="JavaScript is the only language that I'm aware of that people feel they don't need to learn before they start using it. - Douglas Crockford"></a> 

---

### Architecture


---

<a href="http://www.azquotes.com/quote/680861" title="Alan Perlis quote"><img src="http://www.azquotes.com/picture-quotes/quote-simplicity-does-not-precede-complexity-but-follows-it-alan-perlis-68-8-0861.jpg" alt="Simplicity does not precede complexity, but follows it. - Alan Perlis"></a>

<a href="http://www.azquotes.com/quote/229021" title="Alan Perlis quote"><img src="http://www.azquotes.com/picture-quotes/quote-fools-ignore-complexity-pragmatists-suffer-it-some-can-avoid-it-geniuses-remove-it-alan-perlis-22-90-21.jpg" alt="Fools ignore complexity. Pragmatists suffer it. Some can avoid it. Geniuses remove it. - Alan Perlis"></a>

<a href="http://www.azquotes.com/quote/765126" title="Alan Perlis quote"><img src="http://www.azquotes.com/picture-quotes/quote-a-language-that-doesn-t-affect-the-way-you-think-about-programming-is-not-worth-knowing-alan-perlis-76-51-26.jpg" alt="A language that doesn't affect the way you think about programming is not worth knowing. - Alan Perlis"></a>

<a href="http://www.azquotes.com/quote/1346177" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-most-programming-languages-contain-good-parts-and-bad-parts-i-discovered-that-i-could-douglas-crockford-134-61-77.jpg" alt="Most programming languages contain good parts and bad parts. I discovered that I could be better programmer by using only the good parts and avoiding the bad parts. - Douglas Crockford"></a>

<a href="http://www.azquotes.com/quote/803741" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-javascript-is-the-only-language-that-i-m-aware-of-that-people-feel-they-don-t-need-to-douglas-crockford-80-37-41.jpg" alt="JavaScript is the only language that I'm aware of that people feel they don't need to learn before they start using it. - Douglas Crockford"></a>

<a href="http://www.azquotes.com/quote/1346180" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-software-is-usually-expected-to-be-modified-over-the-course-of-its-productive-life-the-douglas-crockford-134-61-80.jpg" alt="Software is usually expected to be modified over the course of its productive life. The process of converting one correct program into a different correct program is extremely challenging. - Douglas Crockford"></a>

<a href="http://www.azquotes.com/quote/1371236" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-good-architecture-is-necessary-to-give-programs-enough-structure-to-be-able-to-grow-douglas-crockford-137-12-36.jpg" alt="Good architecture is necessary to give programs enough structure to be able to grow large without collapsing into a puddle of confusion. - Douglas Crockford"></a>

<a href="http://www.azquotes.com/quote/1119104" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-progress-comes-from-finding-better-ways-to-do-things-don-t-be-afraid-of-innovation-don-douglas-crockford-111-91-04.jpg" alt="Progress comes from finding better ways to do things. Don't be afraid of innovation. Don't be afraid of ideas that are not your own. - Douglas Crockford"></a>

<a href="http://www.azquotes.com/quote/803748" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-javascript-is-the-world-s-most-misunderstood-programming-language-douglas-crockford-80-37-48.jpg" alt="JavaScript is the world's most misunderstood programming language. - Douglas Crockford"></a>

<a href="http://www.azquotes.com/quote/669649" title="Brian Kernighan quote"><img src="http://www.azquotes.com/picture-quotes/quote-controlling-complexity-is-the-essence-of-computer-programming-brian-kernighan-66-96-49.jpg" alt="Controlling complexity is the essence of computer programming. - Brian Kernighan"></a>

<a href="http://www.azquotes.com/quote/596303" title="Dennis Ritchie quote"><img src="http://www.azquotes.com/picture-quotes/quote-a-language-that-doesn-t-have-everything-is-actually-easier-to-program-in-than-some-that-dennis-ritchie-59-63-03.jpg" alt="A language that doesn't have everything is actually easier to program in than some that do - Dennis Ritchie"></a>

<a href="http://www.azquotes.com/quote/154158" title="Alan Kay quote"><img src="http://www.azquotes.com/picture-quotes/quote-most-software-today-is-very-much-like-an-egyptian-pyramid-with-millions-of-bricks-piled-alan-kay-15-41-58.jpg" alt="Most software today is very much like an Egyptian pyramid with millions of bricks piled on top of each other, with no structural integrity, but just done by brute force and thousands of slaves. - Alan Kay"></a>

---

### Large scale code design

Javascript

---


@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting) [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents) [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

## Go GitPitch Pro!

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details here.</a>
</div>
<div class="right">
    <ul>
        <li>Private Repos</li>
        <li>Private URLs</li>
        <li>Password-Protection</li>
        <li>Image Opacity</li>
        <li>SVG Image Support</li>
    </ul>
</div>

---

### Questions?

<br>

@fa[twitter gp-contact](@gitpitch)

@fa[github gp-contact](gitpitch)

@fa[medium gp-contact](@gitpitch)

---?image=assets/image/gitpitch-audience.jpg&opacity=100

@title[Download this Template!]

### Get your presentation started!
### [Download this template @fa[external-link gp-download]](https://gitpitch.com/template/download/black)

