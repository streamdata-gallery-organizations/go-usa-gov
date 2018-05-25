---
swagger: "2.0"
x-collection-name: Go.USA.Gov
x-complete: 0
info:
  title: Go.USA.gov API Shortening a URL
  description: Shortening a URL
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---