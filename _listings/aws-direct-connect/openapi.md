swagger: "2.0"
x-collection-name: AWS Direct Connect
x-complete: 1
info:
  title: AWS Direct Connect API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ConfirmConnection:
    get:
      summary: Confirm Connection
      description: Confirm the creation of a hosted connection on an interconnect.
      operationId: confirmConnection
      x-api-path-slug: actionconfirmconnection-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=ConfirmPrivateVirtualInterface:
    get:
      summary: Confirm Private Virtual Interface
      description: Accept ownership of a private virtual interface created by another
        customer.
      operationId: confirmPrivateVirtualInterface
      x-api-path-slug: actionconfirmprivatevirtualinterface-get
      parameters:
      - in: query
        name: virtualGatewayId
        description: ID of the virtual private gateway that will be attached to the
          virtual interface
        type: string
      - in: query
        name: virtualInterfaceId
        description: ID of the virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces
  /?Action=ConfirmPublicVirtualInterface:
    get:
      summary: Confirm Public Virtual Interface
      description: Accept ownership of a public virtual interface created by another
        customer.
      operationId: confirmPublicVirtualInterface
      x-api-path-slug: actionconfirmpublicvirtualinterface-get
      parameters:
      - in: query
        name: virtualInterfaceId
        description: ID of the virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces