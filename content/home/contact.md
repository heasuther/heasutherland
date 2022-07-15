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
  email: h.e.a.sutherland@sms.ed.ac.uk
  address:
    street: Kennedy Tower, Morningside Place
    city: Edinburgh
    postcode: '94305'
    country: Scotland
    country_code: UK
  office_hours:
    - 'Monday to Friday
    - 09:00 to 17:00'
    - (These hours are flexible.)
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/heasutherland'

design:
  columns: '2'
---
