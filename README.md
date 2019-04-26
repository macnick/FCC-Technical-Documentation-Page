# freeCodeCamp Technical Documentation Page

This is my Technical Documentation page for freeCodeCamp's fourth [basic front end project](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page) inspired by the (then) new Ducati Panigale V4. Demo is also available [on codepen.io](https://codepen.io/macnick/full/WYpKrr). This is not the complete manual of the Panigale. There is a link at the bottom of the page for the full manual.

![Technical Documentation Page](/screenshot.jpg)

## User Stories

- [x] I can see a `main` element with a corresponding `id="main-doc"`, which contains the page's main content (technical documentation).
- [x] Within the `#main-doc` element, I can see several `section` elements, each with a class of `main-section`. There should be a minimum of 5.
- [x] The first element within each `.main-section` should be a `header` element which contains text that describes the topic of that section.
- [x] Each `section` element with the class of `main-section` should also have an id that corresponds with the text of each `header` contained within it. Any spaces should be replaced with underscores (e.g. The `section` that contains the header "Javascript and Java" should have a corresponding `id="Javascript_and_Java"`).
- [x] The `.main-section` elements should contain at least 10 `p` elements total (not each).
- [x] The `.main-section` elements should contain at least 5 `code` elements total (not each).
- [x] The `.main-section` elements should contain at least 5 `li` items total (not each).
- [x] I can see a `nav` element with a corresponding `id="navbar"`.
- [x] The `navbar` element should contain one header element which contains text that describes the topic of the technical documentation.
- [x] Additionally, the navbar should contain link (`a`) elements with the class of `nav-link`. There should be one for every element with the class `main-section`.
- [x] The `header` element in the navbar must come before any link (`a`) elements in the navbar.
- [x] Each element with the class of `nav-link` should contain text that corresponds to the `header` text within each `section` (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
- [x]
- [x]
- [x]
- [x] When I click the `#submit` element, the email is submitted to a static page (use this mock URL: [https://www.freecodecamp.com/email-submit](https://www.freecodecamp.com/email-submit)) that confirms the email address was entered and that it posted successfully.
- [x] The navbar should always be at the top of the viewport.
- [x] My product landing page should have at least one media query.
- [x] My product landing page should utilize CSS flexbox at least once.

## Tools Used

- [HTML5] Markup Language
- [CSS 3 Flex Box](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)

## Install and Build

Nothing to install, just clone this repo and you are good to go.

#### Clone this repo

```bash
git clone https://github.com/macnick/FCC-Landing-Page.git
cd FCC-Landing-Page
```
