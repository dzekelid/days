---
swagger: "2.0"
x-collection-name: OnSched
x-complete: 0
info:
  title: OnSched Returns a list of available days.
  description: "This end point is used to show day level availability. For example
    if the business is closed, or there is a public holiday.\r\n\r\nDay level availability
    is a good way to restrict your choices of dates in your app and improve usability."
  termsOfService: None
  contact:
    name: OnSched.com
    url: https://onsched.com
    email: info@onsched.com
  version: 1.0.0
host: api.onsched.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /consumer/v1/availability/{serviceId}/{startDate}/{endDate}/days:
    get:
      summary: Returns a list of available days.
      description: "This end point is used to show day level availability. For example
        if the business is closed, or there is a public holiday.\r\n\r\nDay level
        availability is a good way to restrict your choices of dates in your app and
        improve usability."
      operationId: ConsumerV1AvailabilityByServiceIdByStartDateByEndDateDaysGet
      x-api-path-slug: consumerv1availabilityserviceidstartdateenddatedays-get
      parameters:
      - in: path
        name: endDate
        description: End Date for availability search
      - in: query
        name: locationId
        description: The id of the business location
      - in: query
        name: resourceId
        description: Resource Id to filter on
      - in: path
        name: serviceId
        description: Service Id for availability search
      - in: path
        name: startDate
        description: Start Date for availability search
      - in: query
        name: tzOffset
        description: Request timezone offset to view availability
      responses:
        200:
          description: OK
      tags:
      - Availability
      - ServiceId
      - StartDate
      - EndDate
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