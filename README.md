# Good Practices for build Web Components

**Note:** The best practices presented here are about [polymer](polymer-project.org), but you can follow these recommendations for any [Web Components](https://www.webcomponents.org/introduction) or other type of component based on Libraries or frameworks (like [React](https://facebook.github.io/react/) or any other).

**Tip:** For open source projects [see the Open Source Checklist](https://afonsopacifer.github.io/open-source-checklist/).

## Table of contents

  - [ ] [Make reusable and composable](#make-reusable-and-composable)
  - [ ] [Cover the basics](#cover-the-basics)
  - [ ] [Make maintainable](#make-maintainable)
  - [ ] [Improve performance](#improve-performance)
  - [ ] [A11y](#a11y)
  - [ ] [Make customizable](#make-customizable)
  - [ ] [Document all](#document-all)
  - [ ] [Publish to the world](#publish-to-the-world)
  - [ ] [Resources for learning](#resources-for-learning)

## Make reusable and composable

  - [ ] Learn the 17 Rules of [Unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy).
  - [ ] Learn about [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/).

## Cover the basics

  - [ ] Make [Responsive](https://en.wikipedia.org/wiki/Responsive_web_design).
  - [ ] When necessary, think in [Progressive enhancement](https://en.wikipedia.org/wiki/Progressive_enhancement).

## Make maintainable

  - [ ] Follow the [Semantic Versioning](http://semver.org/).
  - [ ] Use `_` as a prefix convention for private methods.
  - [ ] Lint with [eslint](http://eslint.org/).
  - [ ] Lint with [polylint](https://github.com/PolymerLabs/polylint).
  - [ ] Write unit tests with [Web Component Tester WCT](https://github.com/Polymer/web-component-tester).
  - [ ] Write the [UI regression test](https://github.com/Huddle/PhantomCSS) with whatever you want.
  - [ ] Run the tests in all browser with [Selenium](http://www.seleniumhq.org/) and [Source Labs](https://saucelabs.com/).
  - [ ] Integrate all tests with [CI](https://travis-ci.org/).

## Improve performance

  - [ ] Optimize [first paint](https://www.smashingmagazine.com/2016/12/front-end-performance-checklist-2017-pdf-pages/).
  - [ ] Write a [test for first paint](https://youtu.be/zfQoleQEa4w?t=1307) performance.
  - [ ] Implement [do less & be lazy](https://youtu.be/zfQoleQEa4w?t=1386) concepts.

## A11y

  - [ ] Add [Aria](https://www.youtube.com/watch?v=g9Qff0b-lHk&index=4&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g) labels.
  - [ ] Use the [focus](https://www.youtube.com/watch?v=EFv9ubbZLKw&index=14&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g) event.
  - [ ] Think in [tab index](https://www.youtube.com/watch?v=Pe0Ce1WtnUM&index=13&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g) order.
  - [ ] Test all with [Accessibility Developer Tools](https://github.com/GoogleChrome/accessibility-developer-tools).

## Make [customizable](https://www.youtube.com/watch?v=IbOaJwqLgog)

  - [ ] Use [custom properties](https://www.w3.org/TR/css-variables/) and expose the API for users with docs.
  - [ ] Use [@apply rule](https://tabatkins.github.io/specs/css-apply-rule/) for most generic style and expose the API for users with docs.

## Document all

  - [ ] Provide a quick demo (like [webcomponents.org inline demo](https://www.webcomponents.org/publish)).
  - [ ] Provide a full demo (Polymer [iron-demo-helpers](https://github.com/PolymerElements/iron-demo-helpers) is recommended).
  - [ ] Describe how to download and use the component.
  - [ ] Describe how to style the component.
  - [ ] Specify the component support.
  - [ ] Describe your API. ([example](https://www.webcomponents.org/element/PolymerElements/paper-button/paper-button))
  - [ ] Describe how to run the development environment.
  - [ ] Describe how to run all the tests.

## Publish to the world

  - [ ] Publish in [bower](https://bower.io/).
  - [ ] Publish in [webcomponents.org](https://www.webcomponents.org/) following the [requirements](https://www.webcomponents.org/publish).

## Resources for learning
- [Practical lessons from a year of building web components - Google I/O 2016](https://www.youtube.com/watch?v=zfQoleQEa4w&feature=youtu.be) - [@notwaldorf](https://twitter.com/notwaldorf)
- [Production-Ready Polymer Elements - A How-To-Guide (Polymer Summit 2016)](https://www.youtube.com/watch?v=T35IgjN9IwY&index=22&list=PLNYkxOF6rcICc687SxHQRuo9TVNOJelSZ) - [@danfreedman](https://twitter.com/danfreedman)
- [Polymer's Styling System (The Polymer Summit 2015)](https://www.youtube.com/watch?v=IbOaJwqLgog) - [@notwaldorf](https://twitter.com/notwaldorf)
- [A11ycasts](https://www.youtube.com/watch?v=HtTyRajRuyY&index=16&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g) - [@rob_dodson](https://twitter.com/rob_dodson)
