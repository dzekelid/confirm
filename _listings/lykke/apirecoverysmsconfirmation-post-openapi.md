---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Recoverysmsconfirmation
  version: 1.0.0
  description: Add api recoverysmsconfirmation.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/RecoverySmsConfirmation:
    post:
      summary: Add API Recoverysmsconfirmation
      description: Add api recoverysmsconfirmation.
      operationId: ApiRecoverySmsConfirmationPost
      x-api-path-slug: apirecoverysmsconfirmation-post
      parameters:
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Recoverysmsconfirmation
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