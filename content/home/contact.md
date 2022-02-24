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
  autolink: false
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: tahmidhasan.3003@gmail.com
  phone: +880 1747 804726, +880 1521 440360
  address:
    street: Amar Ekushey Hall, KUET
    city: Khulna
    region: Khulna
    postcode: '9203'
    country: Bangladesh
    country_code: BAN
  coordinates:
    latitude: '22.8978182'
    longitude: '89.5014229'
  directions: Enter Amar Ekushey Hall and take the stairs to East PGR-4 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/thasan3003'
    - icon: skype       # video
      icon_pack: fab    # fas
      name: DM Me on Skype
      link: 'skype:tahmidhasan.3003?chat'
    

design:
  columns: '2'
---
