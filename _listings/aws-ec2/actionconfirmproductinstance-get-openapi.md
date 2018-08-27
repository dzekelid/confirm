---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Confirm Product Instance
  version: 1.0.0
  description: Determines whether a product code is associated with an instance.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ConfirmProductInstance:
    get:
      summary: Confirm Product Instance
      description: Determines whether a product code is associated with an instance.
      operationId: confirmproductinstance
      x-api-path-slug: actionconfirmproductinstance-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to bundle
        type: string
      - in: query
        name: Storage
        description: The bucket in which to store the AMI
        type: string
      responses:
        200:
          description: OK
      tags:
      - Product Instance
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