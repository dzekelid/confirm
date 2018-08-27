---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez To confirm or unconfirm a list of lots for the auction
  version: 1.0.0
  description: To confirm or unconfirm a list of lots for the auction.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/auction/{id}/confirmlots:
    post:
      summary: To confirm or unconfirm a list of lots for the auction
      description: To confirm or unconfirm a list of lots for the auction.
      operationId: Auction_ConfirmLotsByidByconfirmLotsDataContract
      x-api-path-slug: apiauctionidconfirmlots-post
      parameters:
      - in: body
        name: confirmLotsDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - To
      - Confirm
      - Unconfirm
      - List
      - Of
      - Lotsthe
      - Auction
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