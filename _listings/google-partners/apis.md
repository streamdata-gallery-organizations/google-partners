---
name: Google Partners
x-slug: google-partners
description: Google Partners is Googles program for advertising agencies, digital
  marketing professionals, and other online consultants who manage AdWords accounts.
  The Google Partners API lets advertisers search certified companies and create contact
  leads with them, and also audits the usage of clients.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Partners
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/apis.md
specificationVersion: "0.14"
apis:
- name: Google Partners - Get Analytics
  x-api-slug: v2analytics-get
  description: |-
    Lists analytics data for a user's associated company.
    Should only be called within the context of an authorized logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2analytics-get-openapi.md
- name: Google Partners - Get Generic Message Log
  x-api-slug: v2clientmessageslog-post
  description: |-
    Logs a generic message from the client, such as
    `Failed to render component`, `Profile page is running slow`,
    `More than 500 users have accessed this result.`, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2clientmessageslog-post-openapi.md
- name: Google Partners - Get Companies
  x-api-slug: v2companies-get
  description: Lists companies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companies-get-openapi.md
- name: Google Partners - Update Company
  x-api-slug: v2companies-patch
  description: |-
    Update company.
    Should only be called within the context of an authorized logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companies-patch-openapi.md
- name: Google Partners - Get Company
  x-api-slug: v2companiescompanyid-get
  description: Gets a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companiescompanyid-get-openapi.md
- name: Google Partners - Get Company Leads
  x-api-slug: v2companiescompanyidleads-post
  description: Creates an advertiser lead for the given company ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companiescompanyidleads-post-openapi.md
- name: Google Partners - Get Exam Token
  x-api-slug: v2examsexamtypetoken-get
  description: Gets an Exam Token for a Partner's user to take an exam in the Exams
    System
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2examsexamtypetoken-get-openapi.md
- name: Google Partners - Get Leads
  x-api-slug: v2leads-get
  description: |-
    Lists advertiser leads for a user's associated company.
    Should only be called within the context of an authorized logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2leads-get-openapi.md
- name: Google Partners - Update Lead
  x-api-slug: v2leads-patch
  description: Updates the specified lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2leads-patch-openapi.md
- name: Google Partners - Get Offers
  x-api-slug: v2offers-get
  description: Lists the Offers available for the current user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2offers-get-openapi.md
- name: Google Partners - Get Historical Offers
  x-api-slug: v2offershistory-get
  description: Lists the Historical Offers for the current user (or user's entire
    company)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2offershistory-get-openapi.md
- name: Google Partners - Get Partner Status
  x-api-slug: v2partnersstatus-get
  description: |-
    Gets Partners Status of the logged in user's agency.
    Should only be called if the logged in user is the admin of the agency.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2partnersstatus-get-openapi.md
- name: Google Partners - Log User Event
  x-api-slug: v2usereventslog-post
  description: Logs a user event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usereventslog-post-openapi.md
- name: Google Partners - Get States For User
  x-api-slug: v2userstates-get
  description: Lists states for current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2userstates-get-openapi.md
- name: Google Partners - Update User Profile
  x-api-slug: v2usersprofile-patch
  description: |-
    Updates a user's profile. A user can only update their own profile and
    should only be called within the context of a logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersprofile-patch-openapi.md
- name: Google Partners - Get User
  x-api-slug: v2usersuserid-get
  description: Gets a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersuserid-get-openapi.md
- name: Google Partners - Delete user Company Relation
  x-api-slug: v2usersuseridcompanyrelation-delete
  description: Deletes a user's company relation. Unaffiliaites the user from a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersuseridcompanyrelation-delete-openapi.md
- name: Google Partners - Create user Company Relation
  x-api-slug: v2usersuseridcompanyrelation-put
  description: Creates a user's company relation. Affiliates the user to a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersuseridcompanyrelation-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.pagespeed.insights.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.partners.stack.network
- type: x-website
  url: https://developers.google.com/partners/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---