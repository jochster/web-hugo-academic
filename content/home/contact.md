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
  email: suj@ife.uni-hannover.de
  phone: +49 511 762 4542
  address:
    street: Schneiderberg 50
    city: Hannover
    #region: NI
    postcode: '30167'
    country: Germany
    country_code: DE
  coordinates:
    latitude: '52.3860'
    longitude: '9.7130'
  directions: Leibniz Universität Hannover, Institut für Erdmessung (IfE) | Building 3109 Room 402B
  #office_hours:
    #- 'Monday 10:00 to 13:00'
    #- 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  #contact_links:
    #- icon: twitter
      #icon_pack: fab
      #name: DM Me
      #link: 'https://twitter.com/Twitter'
    #- icon: video
      #icon_pack: fas
      #name: Zoom Me
      #link: 'https://zoom.com'

# map
features:
  map:
    provider: 'mapnik'
    api_key: ''
    zoom: 15
content:
  coordinates:
    latitude: '52.3860'
    longitude: '9.7130'
design:
  columns: '2'
---
