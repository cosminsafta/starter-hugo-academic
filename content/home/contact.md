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
  email: csafta@sandia.gov
  phone: 925-294-1292
  address:
    street: 7011 East Avenue
    city: Livermore
    region: CA
    postcode: '94588'
    country: United States
    country_code: US

design:
  columns: '2'
---
