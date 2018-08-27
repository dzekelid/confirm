---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Admin Placereview Reviewid Confirm
  version: 1.0.0
  description: Post admin placereview reviewid confirm.
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