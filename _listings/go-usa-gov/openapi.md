---
swagger: "2.0"
x-collection-name: Go.USA.Gov
x-complete: 1
info:
  title: Go.USA.gov API
  description: the-go-usa-gov-api-can-shorten-a-url--preview-the-destination-of-a-short-url--get-the-number-of-clicks-on-a-short-url--export-short-urls-from-an-account-
  termsOfService: http://www.usa.gov/About/developer-resources/terms-of-service.shtml
  version: 1.0.0
host: go.usa.gov
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  shorten.json:
    get:
      summary: Shortening a URL
      description: Shortening a URL
      operationId: shortenURL
      x-api-path-slug: shorten-json-get
      parameters:
      - in: query
        name: longURL
        description: The encoded long URL that you wish to shorten
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - URL
  expand.json:
    get:
      summary: Expand URL
      description: Expand URL
      operationId: expandURL
      x-api-path-slug: expand-json-get
      parameters:
      - in: query
        name: shortUrl
        description: The encoded shortened URL
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - URL
  clicks.json:
    get:
      summary: URL Clicks
      description: Get the Number of Clicks on a Short URL
      operationId: urlClicks
      x-api-path-slug: clicks-json-get
      parameters:
      - in: query
        name: shortUrl
        description: The encoded shortened URL
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - URL
  export.json:
    get:
      summary: Export URLs
      description: Get a List of All Short URLs
      operationId: exportURLs
      x-api-path-slug: export-json-get
      responses:
        200:
          description: OK
      tags:
      - URL
---