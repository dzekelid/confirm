swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/documentgeneration/confirmepcappointment:
    post:
      summary: Generates a confirm an epc appointment letter correspondence
      description: Generates a confirm an epc appointment letter correspondence.
      operationId: DocumentGeneration_ConfirmEpcAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationconfirmepcappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Confirm
      - Epc
      - Appointment
      - Letter
      - Correspondence
  /api/documentgeneration/confirmmeeting:
    post:
      summary: Generates a confirm a meeting letter correspondence
      description: Generates a confirm a meeting letter correspondence.
      operationId: DocumentGeneration_ConfirmMeetingLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationconfirmmeeting-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Confirm
      - Meeting
      - Letter
      - Correspondence
  /api/documentgeneration/confirmgeneralappointment:
    post:
      summary: Generates a confirm general appointment letter correspondence
      description: Generates a confirm general appointment letter correspondence.
      operationId: DocumentGeneration_ConfirmGeneralAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationconfirmgeneralappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Confirm
      - General
      - Appointment
      - Letter
      - Correspondence
  /api/role/{id}/confirmcompliancechecks:
    put:
      summary: Confirms the compliance checks have been carried out on a marketing
        role
      description: Confirms the compliance checks have been carried out on a marketing
        role.
      operationId: Role_ConfirmComplianceChecksByidBynegotiatorId
      x-api-path-slug: apiroleidconfirmcompliancechecks-put
      parameters:
      - in: path
        name: id
        description: The id of the role
      - in: query
        name: negotiatorId
        description: The negotiator id who confirmed the checks
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Confirms
      - Compliance
      - Checks
      - Have
      - Been
      - Carried
      - Out
      - "On"
      - Marketing
      - Role