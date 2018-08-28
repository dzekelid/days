swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 1
info:
  title: Entertainment Express
  description: your-gateway-to-building-incredible-movie-tv-and-game-content-discovery-experiences-
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Analytics/Viewers/:
    get:
      summary: Get viewers by Day.
      description: Optional DateValue for length of report.
      operationId: GetAnalyticsViewers
      x-api-path-slug: analyticsviewers-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: ReportTag
        description: Report Tag filter
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - Viewers
  /Analytics/Views/:
    get:
      summary: Get views by Day.
      description: Optional DateValue for length of report.
      operationId: GetAnalyticsViews
      x-api-path-slug: analyticsviews-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: ReportTag
        description: Report Tag filter
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - Views