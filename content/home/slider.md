---
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

active: true
 
# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 2000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 500px


item:
  - title: Nanolithography
    content: 'I am center aligned 😄'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: DTLdoublesize.png  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
#    cta_label: Download my app
#    cta_url: 'https://example.org'
#    cta_icon_pack: fas
#    cta_icon: graduation-cap
  - title: Nanofabrication
    content: 'I am left aligned 😄'
    align: center
    overlay_color: '#555'
	overlay_img: nanotubes.png
    overlay_filter: 0.5
  - title: Nanoengineered UV emitters
    content: 'I am right aligned 😄'
    align: center
    overlay_color: '#333'
    overlay_img: 'nanotubes.png'
    overlay_filter: 0.5
  - title: Core-shell visible emitters
    content: 'I am right aligned 😄'
    align: center
    overlay_color: '#333'
	overlay_img: NRs.png
    overlay_filter: 0.5
---
