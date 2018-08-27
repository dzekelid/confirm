---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Request Requestid Condition Condition Confirm
  version: 1.0.0
  description: Post request requestid condition condition confirm.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/place/{placeId}/confirm:
    put:
      summary: Put Admin Place Placeid Confirm
      description: Put admin place placeid confirm.
      operationId: putApiV1AdminPlacePlaceConfirm
      x-api-path-slug: apiv1adminplaceplaceidconfirm-put
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
      - Confirm
  /api/v1/admin/placeReview/{reviewId}/confirm:
    post:
      summary: Post Admin Placereview Reviewid Confirm
      description: Post admin placereview reviewid confirm.
      operationId: postApiV1AdminPlacereviewReviewConfirm
      x-api-path-slug: apiv1adminplacereviewreviewidconfirm-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Reviewid
      - Confirm
  /api/v1/email/confirm:
    post:
      summary: Post Email Confirm
      description: Post email confirm.
      operationId: postApiV1EmailConfirm
      x-api-path-slug: apiv1emailconfirm-post
      parameters:
      - in: body
        name: request
        description: email
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Confirm
  /api/v1/gigme/email/confirm:
    post:
      summary: Post Gigme Email Confirm
      description: Post gigme email confirm.
      operationId: postApiV1GigmeEmailConfirm
      x-api-path-slug: apiv1gigmeemailconfirm-post
      parameters:
      - in: body
        name: request
        description: email
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Email
      - Confirm
  /api/v1/gigme/phone/confirm:
    post:
      summary: Post Gigme Phone Confirm
      description: Post gigme phone confirm.
      operationId: postApiV1GigmePhoneConfirm
      x-api-path-slug: apiv1gigmephoneconfirm-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Phone
      - Confirm
  /api/v1/phone/confirm:
    post:
      summary: Post Phone Confirm
      description: Post phone confirm.
      operationId: postApiV1PhoneConfirm
      x-api-path-slug: apiv1phoneconfirm-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Phone
      - Confirm
  /api/v1/request/{requestId}/condition/{condition}/confirm:
    post:
      summary: Post Request Requestid Condition Condition Confirm
      description: Post request requestid condition condition confirm.
      operationId: postApiV1RequestRequestConditionConditionConfirm
      x-api-path-slug: apiv1requestrequestidconditionconditionconfirm-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: condition
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Condition
      - Confirm
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