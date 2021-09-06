---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

design:
  columns: '1'
  background:
    gradient_start: '#4bb4e3'
    gradient_end: '#2b94c3'
    gradient_angle: 180
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
---

