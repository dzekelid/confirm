---
swagger: "2.0"
x-collection-name: TradeStation
x-complete: 0
info:
  title: TradeStation Confirm Order
  description: |-
    Returns estimated cost and commission information for an order without the order actually being placed. The fields that are returned in the response depend on the order type.
    The following shows the different fields that will be returned.

    **Base Confirmation**  (All confirmations will have these fields)
    * Route
    * Duration
    * Account
    * SummaryMessage
    * OrderConfirmId

    **Equity Confirmation** (Base Confirmation fields + the following)
    * EstimatedPrice
    * EstimatedPriceDisplay
    * EstimatedCost
    * EstimatedCostDisplay
    * EstimatedCommission
    * EstimatedCommissionDisplay
    * DebitCreditEstimatedCost
    * DebitCreditEstimatedCostDisplay

    **Forex Confirmation** (Base Confirmation fields + the following)
    * BaseCurrency
    * CounterCurrency
    * InitialMarginDisplay

    **Futures Confirmation** (Base Confirmation fields + the following)
    * ProductCurrency
    * AccountCurrency
    * EstimatedCost
    * EstimatedPrice
    * EstimatedPriceDisplay
    * InitialMarginDisplay
    * EstimatedCommission
    * EstimatedCommissionDisplay
  termsOfService: http://elasticbeanstalk-us-east-1-525856068889.s3.amazonaws.com/wp-content/uploads/2014/03/Guidelines_For_Acceptance.pdf
  contact:
    name: TradeStation API Team
    url: https://developer.tradestation.com/webapi
    email: webapi@tradestation.com
  version: 1.0.0
host: api.tradestation.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /orders/confirm:
    post:
      summary: Confirm Order
      description: |-
        Returns estimated cost and commission information for an order without the order actually being placed. The fields that are returned in the response depend on the order type.
        The following shows the different fields that will be returned.

        **Base Confirmation**  (All confirmations will have these fields)
        * Route
        * Duration
        * Account
        * SummaryMessage
        * OrderConfirmId

        **Equity Confirmation** (Base Confirmation fields + the following)
        * EstimatedPrice
        * EstimatedPriceDisplay
        * EstimatedCost
        * EstimatedCostDisplay
        * EstimatedCommission
        * EstimatedCommissionDisplay
        * DebitCreditEstimatedCost
        * DebitCreditEstimatedCostDisplay

        **Forex Confirmation** (Base Confirmation fields + the following)
        * BaseCurrency
        * CounterCurrency
        * InitialMarginDisplay

        **Futures Confirmation** (Base Confirmation fields + the following)
        * ProductCurrency
        * AccountCurrency
        * EstimatedCost
        * EstimatedPrice
        * EstimatedPriceDisplay
        * InitialMarginDisplay
        * EstimatedCommission
        * EstimatedCommissionDisplay
      operationId: postOrderConfirm
      x-api-path-slug: ordersconfirm-post
      parameters:
      - in: query
        name: access_token
        description: A valid OAuth2 token used to authorize access to the resource
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Confirm
      - Order
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