---
name: TradeStation
x-slug: tradestation
description: Whether you trade stocks, ETFs, options or futures, TradeStation???s
  award-winning tools and brokerage services can give you the confidence to achieve
  your goals.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
x-kinRank: "7"
x-alexaRank: "37688"
tags: Confirm
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/tradestation/apis.md
specificationVersion: "0.14"
apis:
- name: Tradestation API - Confirm Order
  x-api-slug: ordersconfirm-post
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/tradestation/ordersconfirm-post-openapi.md
- name: Tradestation API - Confirm Group Order
  x-api-slug: ordersgroupsconfirm-post
  description: |-
    Returns estimated cost and commission information for a group of orders (OCO, BRK) without the orders actually being placed

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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/tradestation/ordersgroupsconfirm-post-openapi.md
x-common:
- type: x-website
  url: http://www.tradestation.com
- type: x-api-gallery
  url: http://tigertext.api.gallery.streamdata.io
- type: x-api-stack
  url: http://tradestation.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/tradestation-technologies
- type: x-developer
  url: https://developer.tradestation.com/
- type: x-documentation
  url: https://tradestation.github.io/api-docs/
- type: x-faq
  url: https://www.tradestation.com/faq/
- type: x-github
  url: https://github.com/tradestation
- type: x-openapi
  url: https://tradestation.github.io/api-docs/swagger.json
- type: x-pricing
  url: https://www.tradestation.com/pricing/
- type: x-twitter
  url: https://twitter.com/TradeStation
- type: x-website
  url: https://www.tradestation.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---