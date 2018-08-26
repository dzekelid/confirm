---
name: AWS Cognito
x-slug: aws-cognito
description: Amazon Cognito lets you easily add user sign-up and sign-in to your mobile
  and web apps. With Amazon Cognito, you also have the options to authenticate users
  through social identity providers such as Facebook, Twitter, or Amazon, with SAML
  identity solutions, or by using your own identity system. In addition, Amazon Cognito
  enables you to save data locally on users devices, allowing your applications to
  work even when the devices are offline. You can then synchronize data across users
  devices so that their app experience remains consistent regardless of the device
  they use. With Amazon Cognito, you can focus on creating great app experiences instead
  of worrying about building, securing, and scaling a solution to handle user management,
  authentication, and sync across devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Confirm
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Cognito Merged API - Admin Confirm Sign Up
  x-api-slug: actionadminconfirmsignup-get
  description: Confirms user registration as an admin without using a confirmation
    code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionadminconfirmsignup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionadminconfirmsignup-get-openapi.md
- name: AWS Cognito Merged API - Confirm Device
  x-api-slug: actionconfirmdevice-get
  description: Confirms tracking of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionconfirmdevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionconfirmdevice-get-openapi.md
- name: AWS Cognito Merged API - Confirm Forgot Password
  x-api-slug: actionconfirmforgotpassword-get
  description: |-
    Allows a user to enter a code provided when they reset their password to update
                their password.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionconfirmforgotpassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionconfirmforgotpassword-get-openapi.md
- name: AWS Cognito Merged API - Confirm Sign Up
  x-api-slug: actionconfirmsignup-get
  description: |-
    Confirms registration of a user and handles the existing alias from a previous
                user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionconfirmsignup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionconfirmsignup-get-openapi.md
- name: AWS Cognito Merged API - Resend Confirmation Code
  x-api-slug: actionresendconfirmationcode-get
  description: |-
    Resends the confirmation (for confirmation of registration) to a specific user in
                the user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionresendconfirmationcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/confirm/master/_listings/aws-cognito/actionresendconfirmationcode-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.codedeploy.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.cognito.stack.network
- type: x-blog
  url: https://aws.amazon.com/cognito/dev-resources/#blogposts
- type: x-documentation
  url: http://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitosync/latest/APIReference/Welcome.html
- type: x-faq
  url: http://aws.amazon.com/cognito/faqs
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=173
- type: x-pricing
  url: http://aws.amazon.com/cognito/pricing
- type: x-sdk
  url: https://aws.amazon.com/cognito/dev-resources/#documentation
- type: x-slides
  url: https://aws.amazon.com/cognito/dev-resources/#slides
- type: x-videos
  url: https://aws.amazon.com/cognito/dev-resources/#videos
- type: x-website
  url: https://aws.amazon.com/cognito/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---