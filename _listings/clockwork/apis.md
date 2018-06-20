---
name: Clockwork
x-slug: clockwork
description: Clockwork is an Easy Text Message API. An SMS API for Developers. Build
  powerful apps and include SMS. Signup is free, Try it now.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1373-clockwork.jpg
x-kinRank: "8"
x-alexaRank: "643753"
tags: Clockwork
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/clockwork/master/_listings/clockwork/apis.md
specificationVersion: "0.14"
apis:
- name: Clockwork SMS Check Balance
  x-api-slug: clockwork-sms
  description: Check how much credit you have left on your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1373-clockwork.jpg
  humanURL: http://clockworksms.com
  baseURL: http://api.clockworksms.com/http///balance
  tags: Check,Balance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/clockwork/master/_listings/clockwork/balance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/clockwork/master/_listings/clockwork/balance-get-openapi.md
- name: Clockwork SMS Send SMS Via HTTP
  x-api-slug: clockwork-sms
  description: The HTTP interface to send text messages can be accessed using GET
    or POST. All parameters must be URL Encoded and sent as UTF-8 text.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1373-clockwork.jpg
  humanURL: http://clockworksms.com
  baseURL: http://api.clockworksms.com/http//send.aspx
  tags: Send,SMS,Via,HTTP
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/clockwork/master/_listings/clockwork/send-aspx-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/clockwork/master/_listings/clockwork/send-aspx-get-openapi.md
- name: Clockwork SMS
  x-api-slug: clockwork-sms
  description: The Clockwork SMS API access to an SMS gateway allowing users to send
    messages through an application. Clockwork is a service that allows for the sending
    of bulk SMS. The API uses RESTful, SOAP and SMPP protocol. Responses are formatted
    in XML.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1373-clockwork.jpg
  humanURL: http://clockworksms.com
  baseURL: http://api.clockworksms.com/http/
  tags: Clockwork
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/clockwork/master/_listings/clockwork/openapi.md
x-common:
- type: x-base
  url: http://api.clockworksms.com
- type: x-blog
  url: http://www.clockworksms.com/blog/
- type: x-blog-rss
  url: http://www.clockworksms.com/feed/
- type: x-contact-form
  url: http://www.clockworksms.com/support/
- type: x-crunchbase
  url: https://crunchbase.com/organization/product/clockwork
- type: x-developer
  url: http://www.clockworksms.com/doc/
- type: x-documentation
  url: http://www.clockworksms.com/doc/easy-stuff/http-interface/send-sms/
- type: x-email
  url: 441234567980@YOURAPIKEY.clockworksms.com
- type: x-email
  url: hello@clockworksms.com
- type: x-faq
  url: http://www.clockworksms.com/faqs/
- type: x-pricing
  url: http://www.clockworksms.com/pricing/
- type: x-selfservice-registration
  url: https://app3.clockworksms.com/signup
- type: x-terms-of-service
  url: http://www.clockworksms.com/terms-and-conditions/
- type: x-twitter
  url: https://twitter.com/ClockworkSMS
- type: x-website
  url: http://clockworksms.com
- type: x-website
  url: http://www.clockworksms.com
- type: x-wordpress-plugin
  url: http://wordpress.org/extend/plugins/contact-form-7-sms-addon/
- type: x-wordpress-plugin
  url: http://wordpress.org/extend/plugins/booking-sms/
- type: x-zendesk
  url: http://www.clockworksms.com/blog/sending-sms-from-zendesk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---