---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

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
      captcha: false

  # Contact details (edit or remove options as required)
  email: jonathan.cook.18@ucl.ac.uk
  phone: +44 7825 292720
  address:
    street: 32 Campdale Road
    city: London
    postcode: N7 0ED
    country: United Kingdom
    country_code: UK

design:
  columns: '2'
---
