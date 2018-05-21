---
name: Go.USA.Gov
x-slug: gousagov
description: The Go.USA.gov API can Shorten a URL. Preview the destination of a short
  URL. Get the number of clicks on a short URL. Export short URLs from an account.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags: Go.USA.Gov
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/apis.md
specificationVersion: "0.14"
apis:
- name: Go.USA.gov API Shortening a URL
  x-api-slug: gousagov-api
  description: Shortening a URL
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://go.usa.gov
  baseURL: https://go.usa.gov//api//shorten.json
  tags: URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/shortenjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/shortenjson-get-openapi.md
- name: Go.USA.gov API Expand URL
  x-api-slug: gousagov-api
  description: Expand URL
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://go.usa.gov
  baseURL: https://go.usa.gov//api//expand.json
  tags: URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/expandjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/expandjson-get-openapi.md
- name: Go.USA.gov API URL Clicks
  x-api-slug: gousagov-api
  description: Get the Number of Clicks on a Short URL
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://go.usa.gov
  baseURL: https://go.usa.gov//api//clicks.json
  tags: URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/clicksjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/clicksjson-get-openapi.md
- name: Go.USA.gov API Export URLs
  x-api-slug: gousagov-api
  description: Get a List of All Short URLs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://go.usa.gov
  baseURL: https://go.usa.gov//api//export.json
  tags: URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/exportjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/exportjson-get-openapi.md
- name: Go.USA.gov API
  x-api-slug: gousagov-api
  description: The Go.USA.gov API can Shorten a URL. Preview the destination of a
    short URL. Get the number of clicks on a short URL. Export short URLs from an
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://go.usa.gov
  baseURL: https://go.usa.gov//api/
  tags: Go.USA.Gov
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/go.usa.gov/master/_listings/gousagov/openapi.md
x-common:
- type: x-blog
  url: https://go.usa.gov/blog
- type: x-terms-of-service
  url: http://www.usa.gov/About/developer-resources/terms-of-service.shtml
- type: x-twitter
  url: https://twitter.com/gousagov
- type: x-website
  url: https://go.usa.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---