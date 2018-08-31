---
swagger: "2.0"
x-collection-name: Google Partners
x-complete: 0
info:
  title: Google Partners API Get Companies
  description: Lists companies.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: partners.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/analytics:
    get:
      summary: Get Analytics
      description: |-
        Lists analytics data for a user's associated company.
        Should only be called within the context of an authorized logged in user.
      operationId: partners.analytics.list
      x-api-path-slug: v2analytics-get
      parameters:
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results that the server returns
      - in: query
        name: requestMetadata.experimentIds
        description: Experiment IDs the current request belongs to
      - in: query
        name: requestMetadata.locale
        description: Locale to use for the current request
      - in: query
        name: requestMetadata.partnersSessionId
        description: Google Partners session ID
      - in: query
        name: requestMetadata.trafficSource.trafficSourceId
        description: Identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.trafficSource.trafficSubId
        description: Second level identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.userOverrides.ipAddress
        description: IP address to use instead of the users geo-located IP address
      - in: query
        name: requestMetadata.userOverrides.userId
        description: Logged-in user ID to impersonate instead of the users ID
      responses:
        200:
          description: OK
      tags:
      - Analytics
  /v2/clientMessages:log:
    post:
      summary: Get Generic Message Log
      description: |-
        Logs a generic message from the client, such as
        `Failed to render component`, `Profile page is running slow`,
        `More than 500 users have accessed this result.`, etc.
      operationId: partners.clientMessages.log
      x-api-path-slug: v2clientmessageslog-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Message
  /v2/companies:
    get:
      summary: Get Companies
      description: Lists companies.
      operationId: partners.companies.list
      x-api-path-slug: v2companies-get
      parameters:
      - in: query
        name: address
        description: The address to use when searching for companies
      - in: query
        name: companyName
        description: Company name to search for
      - in: query
        name: gpsMotivations
        description: List of reasons for using Google Partner Search to get companies
      - in: query
        name: industries
        description: List of industries the company can help with
      - in: query
        name: languageCodes
        description: List of language codes that company can support
      - in: query
        name: maxMonthlyBudget.currencyCode
        description: The 3-letter currency code defined in ISO 4217
      - in: query
        name: maxMonthlyBudget.nanos
        description: Number of nano (10^-9) units of the amount
      - in: query
        name: maxMonthlyBudget.units
        description: The whole units of the amount
      - in: query
        name: minMonthlyBudget.currencyCode
        description: The 3-letter currency code defined in ISO 4217
      - in: query
        name: minMonthlyBudget.nanos
        description: Number of nano (10^-9) units of the amount
      - in: query
        name: minMonthlyBudget.units
        description: The whole units of the amount
      - in: query
        name: orderBy
        description: How to order addresses within the returned companies
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results that the server returns
      - in: query
        name: requestMetadata.experimentIds
        description: Experiment IDs the current request belongs to
      - in: query
        name: requestMetadata.locale
        description: Locale to use for the current request
      - in: query
        name: requestMetadata.partnersSessionId
        description: Google Partners session ID
      - in: query
        name: requestMetadata.trafficSource.trafficSourceId
        description: Identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.trafficSource.trafficSubId
        description: Second level identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.userOverrides.ipAddress
        description: IP address to use instead of the users geo-located IP address
      - in: query
        name: requestMetadata.userOverrides.userId
        description: Logged-in user ID to impersonate instead of the users ID
      - in: query
        name: services
        description: List of services that the returned agencies should provide
      - in: query
        name: specializations
        description: List of specializations that the returned agencies should provide
      - in: query
        name: view
        description: The view of the `Company` resource to be returned
      - in: query
        name: websiteUrl
        description: Website URL that will help to find a better matched company
      responses:
        200:
          description: OK
      tags:
      - Company
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