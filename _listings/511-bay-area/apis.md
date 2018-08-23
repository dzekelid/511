---
name: 511 Bay Area
x-slug: 511-bay-area
description: 511 is your free one-stop phone and web source for up-to-the minute Bay
  Area traffic, transit, rideshare, bicycling, and parking information.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_511_128x128_400x400.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: "511"
created: "2018-08-22"
modified: "2018-08-22"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/511/master/_listings/511-bay-area/apis.md
specificationVersion: "0.14"
apis:
- name: 511 Driving Times
  x-api-slug: 511-driving-times
  description: The 511 Driving Times API provides 511s current and typical driving
    times between a starting and ending point, including incidents along the route.
    The API consists of a collection of individual services implemented using simple
    web pages that accept query string parameters and return plain XML documents.
    If youd like a complete traffic data set (incidents, speed, and travel time data)
    by individual links, please check out the 511 Traffic Data Feed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_511_128x128_400x400.jpg
  humanURL: http://www.511.org/
  baseURL: https:///
  tags: "511"
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/511/master/_listings/511-bay-area/openapi.md
- name: '511 Real-time Transit Departures '
  x-api-slug: 511-realtime-transit-departures-
  description: The 511 Real-time Transit Departures API provides real-time departure
    predictions for several regional transit agencies, including BART, Muni, and AC
    Transit. The API consists of a collection of individual services implemented using
    simple web pages that accept query string parameters and return plain XML documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_511_128x128_400x400.jpg
  humanURL: http://www.511.org/
  baseURL: https:///
  tags: "511"
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/511/master/_listings/511-bay-area/openapi.md
x-common:
- type: x-twitter
  url: https://twitter.com/511SFBay
- type: x-website
  url: http://www.511.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---