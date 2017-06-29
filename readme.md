# JavaScript

## What is programming and how is that different than HTML and CSS (15 minutes / 0:15)

HTML is a **markup language**, a system in which tags are used to add meaning to the text of a document and describe non-text aspects of the document.
HTML doesn't operate on data, it is data.
As fancy as an HTML document can get, it is still ultimately describing itself not a program.

CSS is a **stylesheet language**, a language to describe the presentation of a structured document.
While there is a lot of depth to CSS it is ultimately focused on the document which is limiting.

A program is a collection of instructions that preforms a task when executed by a computer.
This task can be transfering money between bank accounts, operating a robot in a factory, mining data, firing nuclear weapons, or presenting a web application.
There are many programming languages and they could all do all of these things, but some better than others.

Programing languages generally share several features such as **data types**, **variables**, **logic**, **control flow**, and **functions** that allow them to express any conceivable procedure.
Every programming language has a specific **syntax** used to write these instructions.
Every programming language also has a set of built in features that let the instructions have external effects.

Developers choose to use different programming language for a variety of reasons.
It may have features that make a particular task easier or more efficient or it may have a clear syntax.
We use JavaScript when building web apps because it is the only language that runs in the browser.

## The Browser Wars (10 minutes / 0:25)

![Browser Market Share 1994-2009](https://upload.wikimedia.org/wikipedia/commons/5/55/Layout_engine_usage_share-2009-01-07.svg)
- **1993**: National Center for Supercomputing Applications (NCSA) of the University of Illinois at Ubrana-Champaign release [NCSA Mosaic](https://en.wikipedia.org/wiki/Mosaic_(web_browser)) popularizng the web.
- **early 1994**: Mosaic Communications founded and begins work on Mosaic Netscape (internally, Mozilla)
- **late 1994**: Mosaic Netscape released and quickly dominates web browser market
- **early 1995**: Mosaic Communications is renamed Netscape Communications and Mosaic Netscape is renamed Netscape Navigator.
  - Microsoft is making large investment in web browsers and is challenging Netscape.
  - As browser competition intensifies, Netscape founder, Marc Andreessen, beleives there is a need for a light weight language marketed to web designers that could be embedded directly in web pages.
    - Brennan Eich is hired to write "Scheme for the web".
    - Simultaneously, Netsape is working with Sun Microsystems to build Java extensibility into the browser leading to the decision that this new language should mimic Java to an extent.
    - Brennan Eich prototypes the language then called Mocha in ten days.
- **late 1995**: Mocha is released as a supported feature of the Netscape Browser under the name LiveScript
  - In the subsequent release of the Netscape Browser, LiveScript is regretably renamed JavaScript in an effort to ride the coat tails of the heavily marketed Java.
- **1996**: Microsoft reverse engineers JavaScript and releases JScript.
  - Netscape submits JavaScript to Ecma International to publish a standard (ECMAScript-262)
- **1998**: Netscape open-sources their browser and creates the Mozilla Project.
  - ECMAScript 2 Standard published.
- **1999**: ECMAScript 3 standard published.
- **2003**: ECMAScript 4 falls apart.
  - Apple releases Safari.
- **2005-2009**: Lots of excitement but things keep falling apart.
  - Open source community works to address failings of the standards comittees
  - ECMAScript 5 released
  - Node.js released
- **2015**: Change the naming convention to ECMAScript 2015 (commonly ES6)
- **2016**: ECMAScript 2017 released but not such a big deal because people had be using Babel.

![Browser Market Share 2009-2015](https://upload.wikimedia.org/wikipedia/commons/8/86/Usage_share_of_web_browsers_%28Source_StatCounter%29.svg)

Note: Check out [Can I Use..](https://caniuse.com/) for detailed info on browser support of JS features.

## Linking a JavaScript file (5 minutes / 0:30)

### Linking with a script tag

### Linking multiple scripts

**Bonus** async and defered attriutes


## Linter (10 minutes / 0:35)

- Install [Linter](https://github.com/steelbrain/linter)
- Install [linter-js-standard](https://github.com/ricardofbarros/linter-js-standard)
- Install [atom-standard-formatter](https://github.com/stephenkubovic/atom-standard-formatter)
- Install [standardjs-snippets](https://github.com/gaboesquivel/atom-standardjs-snippets)

## Developer Tools (10 minutes / 0:45)

### `console.log`

### `debugger`


## References

- [W3C: A Short History of JavaScript](https://www.w3.org/community/webed/wiki/A_Short_History_of_JavaScript)
- [Auth0: A Brief History of JavaScript](https://auth0.com/blog/a-brief-history-of-javascript/)
- [Wikipedia: JavaScript](https://en.wikipedia.org/wiki/JavaScript)
