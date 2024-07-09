# Slidev Theme Neversink

An education/academia oriented [Slidev](https://sli.dev/) theme with some whimsical elements.

Documentation [here](https://gureckis.github.io/slidev-theme-neversink/)

## Installation

```bash
npm install slidev-theme-neversink
```

## Usage

Add the theme to the frontmatter of your first slide in `slides.md`:

```md
---
theme: neversink
---
```

## Features

## Todo list

### Code cleanup

- [x] refactor some of the layout stuff into layoutHelper.ts
  - [x] two-cols-header
  - [x] two-cols-footer
  - [x] top-title
  - [x] top-title-two-cols
  - [x] side-title
  - [x] quote
  - [x] intro
  - [x] cover
- [x] fix <code> bg colors on colored slides
- [x] add variables to configure things
- [x] make global-top be a feature of my talks not the theme
- [x] add a configuration option to global-bottom/slide-bottom for the date or whatever field
- [x] clean up css classes
- [ ] dark mode support
- [ ] publish as a theme
  - [ ] automate workflow for publishing to npm
- add docs
  - [x] vitepress setup published to github pages
  - [ ] slide types
  - [ ] add docs on how to customize variables/fonts

### Layouts

- [x] add a 100% full slide slide
- [x] color side bar left/right
- [x] two column footer
- [x] two column (configurable) header
- [x] four cell grid
- [x] Add a config way to drop some of the lab/nyu stuff
- [x] add a way to drop the page numbers
- [x] color bar top/bottom centering
- [x] color title page
- [x] one up with caption below
- [x] two up with caption below
- [x] three up across with content option above and below (e.g., three panels of data)
- [x] top title
- [x] top title two cols
- [x] two cols no header
- [x] credits layout
- [x] default (with color)
- [x] sort out the global-top/slide-top thing (waiting for new slidev release)
- [x] new section (with color)
- [x] full (with color)
- [x] quote (better style)
- [x] scrolling credits slide
  - [x] create as a layout also
  - [x] add links and icons
  - [ ] auto adjust height
  - [ ] looping is not working
  - [ ] use a animation library instead of raw request frame
  - [ ] if in export mode then don't start scrolled down
  - [ ] add keyboard commands to pause speed up and step forward/backwards in scrolling
  - [ ] center final page

<img src="/screenshots/credits-light.gif" alt="credits slide example" width="600" class="screenshot mb-10 mt-10"/>

<img src="/screenshots/credits-dark.gif" alt="full slide example" width="600" class="screenshot"/>

### components

- [x] markdown admonitions
- [x] draggable, custom admonition
  - [ ] adminition colors for dark/navy/etc...
- [x] speech bubble
  - [~x] corner tails (good enough)
  - [x] text-align
  - [x] animations
- [x] post-it note
  - [ ] prop to toggle if only visible in dev mode (waiting for new slidev release)

### Future ideas

- [ ] dynamic color themes
- [ ] thought bubble/comic style
- [ ] tooltip that appears on hover or with a click
- [ ] spoilers with clicks
- [ ] spring loaded word cloud
- [ ] quiz live polls
- [ ] map
- [ ] make admonition class be what the markdown processes uses
- [ ] animations/layouts
  - [ ] kawaii waving hands
  - [ ] kawaii raising hands
