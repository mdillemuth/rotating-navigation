# Rotating Navigation

Project 3 of 50 from BradTraversy's "50 Projects in 50 Days" course on Udemy.

Interact with the project yourself by [viewing the live demonstration online!](https://mdillemuth.github.io/rotating-navigation/)

## Demo

![demo](demo.gif)

## Description

This is a simple web component that takes a creative take on a hamburger-icon navigation menu. Instead of sliding-in from the side of the page, this navigation menu _rotates-in_ from outside of the page. The visible content on the page rotates with it to make room for the navigation menu. It is quite a unique way to accomplish such an everyday task.

The JS logic is not anything complex or beyond what you would expect for a traditional pop-out mobile navigation menu. The CSS is where the magic happens and the _transform_ and _transition_ properties are responsible for the bulk of the animating behavior.

## Technology

- HTML
  - Semantic HTML5
  - Accessibilty compliant
- CSS
  - Animation
- JavaScript
  - ES6 Syntax

## Modifications from the Original

I made a few small stylistic and personal changes.

Using Chrome developer tool's Lighthouse, I generated reports to measure the performance, accessibility, and use of best practices in the project. I then made corrections in the project in order to reach 100% in all of those categories. Some of the changes to improve accessibility include the following:

- Added _aria-label_ attributes to the button elements that use icons
- Replace the h3 used in the tutorial with an h2

## Credit

This is project #3 of 50 from Brad Traversy's [50 Projects in 50 Days: HTML, CSS, & JavaScript](https://www.udemy.com/couse/50-projects-50-days/)
