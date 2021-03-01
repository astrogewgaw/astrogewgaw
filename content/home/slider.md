+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "tcal"
  content = "**T**he **C**omprehensive **A**strochemists' **L**ist <br/> <p>A maintained, updated and comprehensive list of astrochemists around the globe. Browse the list online [here](https://astrocommunique.netlify.app/tcal/list/) or get the app:</p>"
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#1d1135"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/media/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get tcal"
  cta_url = "https://github.com/astrogewgaw/tcal/"
  cta_icon_pack = "fas"
  cta_icon = "download"
  
[[item]]
  title = "who am i?"
  content = "I am an astrochemist and a pulsar astronomer. <br/> <p>I spend my days writing code that can help us look for space molecules and pulsars. Want to connect with me? Check out the [**About**](#about) section!</p>"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/media/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.  

[[item]]
  title = ""
  content = "How did we take the picture of a black hole? <br/><br/> We used radio telescopes! <br/> <p>Check out my thread on how we use them to take pictures like this, written for the Global Science Show, [here](https://twitter.com/astrogewgaw/status/1273900381190238210).</p>"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "blackhole.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
 
+++
