
-->
timezone:    Europe/Berlin
future:      false
# Set baseurl to the base path of the site eg "/mytalk"
# baseurl:     "/github-slideshow"
# The allowed values are 'rouge', 'pygments' or null.
highlighter: rouge
# markdown - Valid options are [ maruku | rdiscount | kramdown | redcarpet ]
markdown:    kramdown
lsi:         false
permalink:   "/:title"

kramdown:
  ## for german: "sbquo,lsquo,bdquo,ldquo"
  smart_quotes: lsquo,rsquo,ldquo,rdquo

plugins:
  - jemoji

## personalize your slide show
title:       github-slideshow
author:      GitHubTeacher
description: A fun activity for learning Git and GitHub.

sass:
  style:     :compressed

## solarized variant (dark/light)
solarized:
  theme:     dark

slideNumber:
  # Slide number formatting can be configured using these variables:
  #  "h.v":  horizontal . vertical slide number (default)
  #  "h/v":  horizontal / vertical slide number
  #    "c":  flattened slide number
  #  "c/t":  flattened slide number / total slides
  # "none":  dont't show slide numbers
  format:    "c/t"

## Reveal.initialize
## At the end of your page Jekyll initializes reveal by running the following code. Note that all config values are optional and will default as specified below.
## Note that the new default vertical centering option will break compatibility with slides that were using transitions with backgrounds ("cube" and "page"). To restore the previous behavior, set "center" to "false".
reveal:
  ## Display controls in the bottom right corner
  controls: false
  ## Display a presentation progress bar
  progress: true
  ## Display the page number of the current slide
  #slideNumber: false
  ## Push each slide change to the browser history
  history: true
  ## Enable keyboard shortcuts for navigation
  keyboard: true
  ## Enable the slide overview mode
  overview: true
  ## Vertical centering of slides
  center: true
  ## Enables touch navigation on devices with touch input
  touch: true
  ## Loop the presentation
  loop: false
  ## Change the presentation direction to be RTL
  #rtl: false
  ## Turns fragments on and off globally
  fragments: true
  ## Flags if the presentation is running in an embedded mode
  ## i.e. contained within a limited portion of the screen
  #embedded: false
  ## Number of milliseconds between automatically proceeding to the
  ## next slide, disabled when set to 0, this value can be overwritten
  ## by using a data-autoslide attribute on your slides
  #autoSlide: 0
  ## Stop auto-sliding after user input
  #autoSlideStoppable: true
  ## Enable slide navigation via mouse wheel
  #mouseWheel: false
  ## Hides the address bar on mobile devices
  #hideAddressBar: true
  ## Opens links in an iframe preview overlay
  #previewLinks: false
  ## Transition style (default/cube/page/concave/zoom/linear/fade/none)
  transition: linear
  ## Transition speed (default/fast/slow)
  #transitionSpeed: default
  ## Transition style for full page slide backgrounds (default/none/slide/concave/convex/zoom)
  backgroundTransition: slide
  ## Number of slides away from the current that are visible
  #viewDistance: 3
  ## Parallax background image (e.g. "'https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg'")
  #parallaxBackgroundImage: ''
  ## Parallax background size (CSS syntax, e.g. "2100px 900px")
  #parallaxBackgroundSize: ''
  ## The "normal" size of the presentation, aspect ratio will be preserved
  ## when the presentation is scaled to fit different resolutions. Can be
  ## specified using percentage units.
  width: 1000
  height: 920
  ## Factor of the display size that should remain empty around the content
  margin: 0.1
  ## Bounds for smallest/largest possible scale to apply to content
  minScale: 0.2
  maxScale: 1.5

exclude: [
  "Gemfile",
  "Gemfile.lock",
  "vendor",
  "reveal.js/test",
  "reveal.js/index.html",
  "reveal.js/README.md",
  "reveal.js/bower.json",
  "reveal.js/Gruntfile.js",
  "reveal.js/CONTRIBUTING.md",
  "reveal.js/LICENSE",
  "reveal.js/package.json"


