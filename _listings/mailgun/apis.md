---
name: Mailgun
x-slug: mailgun
description: Mailgun provides a web service for integrating email inboxes into apps.
  Providing APIs for sending, receiving, and storing APis, including tools for managing
  delivery, real-time integration, organizing, routing, and tracking on emails. Malign
  provides a free trial to learn about services, and pay as you go, unit based pricing
  to continue from there, including volume pricing for increased usage.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
x-kinRank: "8"
x-alexaRank: "24750"
tags: Bounces
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/apis.md
specificationVersion: "0.14"
apis:
- name: Mailgun API - Bounces
  x-api-slug: bounces-get
  description: Fetches the list of bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-get-openapi.md
- name: Mailgun API - Add Bounce
  x-api-slug: bounces-post
  description: Adds a permanent bounce to the bounces table. Updates the existing
    record if already here.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-post-openapi.md
- name: Mailgun API - Delete Bounce
  x-api-slug: bouncesaddress-delete
  description: Clears a bounce event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-delete-openapi.md
- name: Mailgun API - Bounce
  x-api-slug: bouncesaddress-get
  description: Fetches a single bounce event by a given email address. This is useful
    to check if a given email address has bounced before.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-get-openapi.md
- name: Mailgun API - Add Bounce
  x-api-slug: bounces-post
  description: Adds a permanent bounce to the bounces table. Updates the existing
    record if already here.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-post-openapi.md
- name: Mailgun API - Delete Bounce
  x-api-slug: bouncesaddress-delete
  description: Clears a bounce event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-delete-openapi.md
- name: Mailgun API - Bounce
  x-api-slug: bouncesaddress-get
  description: Fetches a single bounce event by a given email address. This is useful
    to check if a given email address has bounced before.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-get-openapi.md
- name: Mailgun API - Bounce
  x-api-slug: bouncesaddress-get
  description: Fetches a single bounce event by a given email address. This is useful
    to check if a given email address has bounced before.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-get-openapi.md
- name: Mailgun API - Delete Bounce
  x-api-slug: bouncesaddress-delete
  description: Clears a bounce event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bouncesaddress-delete-openapi.md
- name: Mailgun API - Add Bounce
  x-api-slug: bounces-post
  description: Adds a permanent bounce to the bounces table. Updates the existing
    record if already here.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Stack Network, SaaS, Technology, API Provider, API Provider, Emails, Messages,
    Profiles, Emails, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/mailgun/bounces-post-openapi.md
x-common:
- type: x--net-library
  url: http://documentation.mailgun.com/libraries.html#c
- type: x-api-gallery
  url: http://lykke.api.gallery.streamdata.io
- type: x-api-stack
  url: http://mailgun.stack.network
- type: x-base
  url: https://api.mailgun.net
- type: x-blog
  url: http://blog.mailgun.net
- type: x-blog-rss
  url: https://twitter.com/unbounce
- type: x-crunchbase
  url: http://www.crunchbase.com/company/mailgun
- type: x-crunchbase
  url: https://crunchbase.com/organization/mailgun
- type: x-developer
  url: http://documentation.mailgun.com/
- type: x-email
  url: privacy@mailgun.com
- type: x-faq
  url: http://documentation.mailgun.com/faqs.html
- type: x-github
  url: https://github.com/mailgun
- type: x-heroku-addon
  url: https://addons.heroku.com/mailgun
- type: x-java-library
  url: http://documentation.mailgun.com/libraries.html#java
- type: x-node-js-library
  url: http://documentation.mailgun.com/libraries.html#node-js
- type: x-php-library
  url: http://documentation.mailgun.com/libraries.html#php
- type: x-pricing
  url: http://www.mailgun.com/pricing
- type: x-privacy
  url: http://www.mailgun.com/privacy
- type: x-python-library
  url: http://documentation.mailgun.com/libraries.html#python
- type: x-ruby-library
  url: http://documentation.mailgun.com/libraries.html#ruby
- type: x-selfservice-registration
  url: https://www.mailgun.com/signup
- type: x-stack-overflow
  url: https://stackoverflow.com/questions/tagged/mailgun
- type: x-terms-of-service
  url: http://www.mailgun.com/terms
- type: x-twitter
  url: https://twitter.com/#!/mail_gun
- type: x-website
  url: http://mailgun.net
- type: x-wordpress-plugin
  url: https://wordpress.org/plugins/mailgun/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---