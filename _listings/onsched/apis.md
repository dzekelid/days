---
name: OnSched
x-slug: onsched
description: Build secure and scalable custom apps for Online Booking. Our flexible
  API provides many options for availability and booking. OnSched is an API first
  booking software that allows you to bring your design to life by creating your own
  booking flow. Using our robust API you can customize the interaction between your
  consumers and vendors while we do all the leg work behind the scenes. Want to offer
  online booking to your vendors? Ask about our white labelling solutions and rebrand
  our software as your own.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
x-kinRank: "7"
x-alexaRank: ""
tags: Days
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/days/master/_listings/onsched/apis.md
specificationVersion: "0.14"
apis:
- name: OnSched API - Returns a list of available days.
  x-api-slug: consumerv1availabilityserviceidstartdateenddatedays-get
  description: "This end point is used to show day level availability. For example
    if the business is closed, or there is a public holiday.\r\n\r\nDay level availability
    is a good way to restrict your choices of dates in your app and improve usability."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/days/master/_listings/onsched/consumerv1availabilityserviceidstartdateenddatedays-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/days/master/_listings/onsched/consumerv1availabilityserviceidstartdateenddatedays-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://onenote.api.gallery.streamdata.io
- type: x-api-stack
  url: http://onsched.stack.network
- type: x-documentation
  url: https://www.onsched.com/api/docs/
- type: x-pricing
  url: https://www.onsched.com/index.html#self-service
- type: x-website
  url: http://www.onsched.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---