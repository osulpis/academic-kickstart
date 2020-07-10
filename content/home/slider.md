+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = '4000'

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Pieces of the seafloor are dissolving, here is why"
  content = "Climate change does not just hit our atmosphere, it is also making parts of our ocean floor disappear."
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = 'sweel.jpg'  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "See the video"
  cta_url = "https://www.youtube.com/watch?v=c_svWhCBG_k"
  cta_icon_pack = "fab"
  cta_icon = "youtube"

[[item]]
  title = "We're going to sea!"
  content = "Funding received from a NWO-XS Grant to sample and explore deep-sea sediments and microbial fauna in an upcoming cruise."
  align = "left"  # Choose `center`, `left`, or `right`.

  overlay_color = "#666"  # An HTML color value.
  overlay_img = 'sallyride.jpg'  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Read about the project"
  cta_url = "https://deep-c.xyz/project/deep-sea-sediment-microbial-fauna/"
  cta_icon_pack = "fas"
  cta_icon = "ship"

[[item]]
  title = "Oeuf ou poule ?"
  content = "I was invited to this podcast to talk (in French) about ocean acidification and ways to reduce it, with a pinch of optimism!"
  align = "right"  # Choose `center`, `left`, or `right`.

  overlay_color = "#666"  # An HTML color value.
  overlay_img = 'oeufpoule.jpg'  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Ecouter le podcast"
  cta_url = "https://www.choq.ca/episodes/loeuf-ou-la-poule/emission-du-1-avril-2019/"
  cta_icon_pack = "fas"
  cta_icon = "microphone-alt"


+++
