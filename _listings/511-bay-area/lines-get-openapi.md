---
swagger: "2.0"
x-collection-name: 511 Bay Area
x-complete: 0
info:
  title: Bay Area 511 Transit API Lines API
  description: San francisco 511 transit lines api.
  version: 1.0.0
host: api.511.org
basePath: /transit
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lines:
    get:
      summary: Lines API
      description: San francisco 511 transit lines api.
      operationId: LinesGet
      x-api-path-slug: lines-get
      parameters:
      - in: query
        name: api_key
      - in: query
        name: operator_id
      responses:
        200:
          description: OK
      tags:
      - "511"
      - Lines
      - API
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