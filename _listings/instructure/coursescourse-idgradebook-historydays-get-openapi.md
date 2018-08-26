---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Days in gradebook history for this course
  description: Days in gradebook history for this course.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/gradebook_history/days:
    get:
      summary: Days in gradebook history for this course
      description: Days in gradebook history for this course.
      operationId: days-in-gradebook-history-for-this-course
      x-api-path-slug: coursescourse-idgradebook-historydays-get
      parameters:
      - in: query
        name: course_id
        description: The id of the contextual course for this API call
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Gradebook
      - History
      - Days
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