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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/apis.md
specificationVersion: "0.14"
apis:
- name: Google Partners API Get Analytics
  x-api-slug: google-partners-api
  description: |-
    Lists analytics data for a user's associated company.
    Should only be called within the context of an authorized logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/analytics
  tags: Analytics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2analytics-get-openapi.md
- name: Google Partners API Get Generic Message Log
  x-api-slug: google-partners-api
  description: |-
    Logs a generic message from the client, such as
    `Failed to render component`, `Profile page is running slow`,
    `More than 500 users have accessed this result.`, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/clientMessages:log
  tags: Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2clientmessageslog-post-openapi.md
- name: Google Partners API Get Companies
  x-api-slug: google-partners-api
  description: Lists companies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/companies
  tags: Company
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companies-get-openapi.md
- name: Google Partners API Update Company
  x-api-slug: google-partners-api
  description: |-
    Update company.
    Should only be called within the context of an authorized logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/companies
  tags: Company
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companies-patch-openapi.md
- name: Google Partners API Get Company
  x-api-slug: google-partners-api
  description: Gets a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/companies/{companyId}
  tags: Company
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companiescompanyid-get-openapi.md
- name: Google Partners API Get Company Leads
  x-api-slug: google-partners-api
  description: Creates an advertiser lead for the given company ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/companies/{companyId}/leads
  tags: Lead
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2companiescompanyidleads-post-openapi.md
- name: Google Partners API Get Exam Token
  x-api-slug: google-partners-api
  description: Gets an Exam Token for a Partner's user to take an exam in the Exams
    System
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/exams/{examType}/token
  tags: Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2examsexamtypetoken-get-openapi.md
- name: Google Partners API Get Leads
  x-api-slug: google-partners-api
  description: |-
    Lists advertiser leads for a user's associated company.
    Should only be called within the context of an authorized logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/leads
  tags: Lead
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2leads-get-openapi.md
- name: Google Partners API Update Lead
  x-api-slug: google-partners-api
  description: Updates the specified lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/leads
  tags: Lead
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2leads-patch-openapi.md
- name: Google Partners API Get Offers
  x-api-slug: google-partners-api
  description: Lists the Offers available for the current user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/offers
  tags: Offer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2offers-get-openapi.md
- name: Google Partners API Get Historical Offers
  x-api-slug: google-partners-api
  description: Lists the Historical Offers for the current user (or user's entire
    company)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/offers/history
  tags: Lead
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2offershistory-get-openapi.md
- name: Google Partners API Get Partner Status
  x-api-slug: google-partners-api
  description: |-
    Gets Partners Status of the logged in user's agency.
    Should only be called if the logged in user is the admin of the agency.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/partnersstatus
  tags: Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2partnersstatus-get-openapi.md
- name: Google Partners API Log User Event
  x-api-slug: google-partners-api
  description: Logs a user event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/userEvents:log
  tags: Log
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usereventslog-post-openapi.md
- name: Google Partners API Get States For User
  x-api-slug: google-partners-api
  description: Lists states for current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/userStates
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2userstates-get-openapi.md
- name: Google Partners API Update User Profile
  x-api-slug: google-partners-api
  description: |-
    Updates a user's profile. A user can only update their own profile and
    should only be called within the context of a logged in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/users/profile
  tags: Profile
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersprofile-patch-openapi.md
- name: Google Partners API Get User
  x-api-slug: google-partners-api
  description: Gets a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/users/{userId}
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersuserid-get-openapi.md
- name: Google Partners API Delete user Company Relation
  x-api-slug: google-partners-api
  description: Deletes a user's company relation. Unaffiliaites the user from a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/users/{userId}/companyRelation
  tags: Relation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersuseridcompanyrelation-delete-openapi.md
- name: Google Partners API Create user Company Relation
  x-api-slug: google-partners-api
  description: Creates a user's company relation. Affiliates the user to a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com////v2/users/{userId}/companyRelation
  tags: Relation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/v2usersuseridcompanyrelation-put-openapi.md
- name: Google Partners API
  x-api-slug: google-partners-api
  description: Google Partners is Googles program for advertising agencies, digital
    marketing professionals, and other online consultants who manage AdWords accounts.
    The Google Partners API lets advertisers search certified companies and create
    contact leads with them, and also audits the usage of clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Partner.jpg
  humanURL: https://developers.google.com/partners/
  baseURL: ://partners.googleapis.com//
  tags: Google Partners
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-partners/master/_listings/google-partners/openapi.md
x-common:
- type: x-website
  url: https://developers.google.com/partners/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---