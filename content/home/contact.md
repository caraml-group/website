---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 150

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  # email: test@example.org
  # phone: 888 888 88 88
  address:
    street: 15 JJ Thomson Ave
    city: Cambridge
    region: Cambridgeshire
    postcode: 'CB3 0FD'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '52.21078723113385'
    longitude: '0.0922959785002502'
  directions: William Gates Building, Computer Laboratory, University of Cambridge
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
  - icon: twitter
    icon_pack: fab
    name: Follow us on Twitter
    link: 'https://twitter.com/'
  - icon: github
    icon_pack: fab
    name: Code on GitHub
    link: 'https://github.com/'
  - icon: envelope
    icon_pack: fas
    name: Email individually for appointments
    link: '#people'

  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  # form:
  #   provider: netlify
  #   formspree:
  #     id:
  #   netlify:
  #     # Enable CAPTCHA challenge to reduce spam?
  #     captcha: false

design:
  columns: '2'
---
