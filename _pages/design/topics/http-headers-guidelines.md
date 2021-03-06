---
layout: topic
title: HTTP Headers
permalink: /design/topics/http-headers
sort: HTTP Protocol_HTTP Headers
topic_id: http-headers
topic_category: HTTP Protocol
topic_name: HTTP Headers
topic_description: How to use standard or custom HTTP headers
guidelines:
  - guideline_id: atlassian-rest-api-design-guidelines-version-1
    guideline_title: Atlassian REST API Design Guidelines version 1
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_screenshotUrl: /media/screenshots/atlassian-rest-api-design-guidelines-version-1.png
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1/topics
    references:
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Entities SHOULD be served with an ETag header.
      - name: Caching
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Caching'
        quote: 'ETag, If-None-Match'
  - guideline_id: atlassian-rest-api-policy
    guideline_title: Atlassian REST API Policy
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_screenshotUrl: /media/screenshots/atlassian-rest-api-policy.png
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-policy
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-policy/topics
    references:
      - name: Detectability (Deprecation Policy)
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Detectability'
  - guideline_id: cisco-api-design-guide
    guideline_title: API Design Guide
    guideline_type: github
    guideline_url: 'https://github.com/CiscoDevNet/api-design-guide'
    guideline_company: Cisco
    guideline_companyLogoUrl: /media/logos/cisco.png
    guideline_companyUrl: 'http://developer.cisco.com/'
    guideline_screenshotUrl: /media/screenshots/cisco-api-design-guide.png
    guideline_date: 2015-08-21T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/cisco-api-design-guide
      guidelineTopics:
        href: /design/guidelines/cisco-api-design-guide/topics
    references:
      - name: 3.5 HTTP Headers
        url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
      - name: 3.6.1 POST
        quote: Location header
        url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
  - guideline_id: haufe-api-styleguide
    guideline_title: Haufe API style guide
    guideline_type: github
    guideline_url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
    guideline_company: Haufe
    guideline_companyLogoUrl: /media/logos/haufe.png
    guideline_companyUrl: 'http://dev.haufe.com/'
    guideline_screenshotUrl: /media/screenshots/haufe-api-styleguide.png
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/haufe-api-styleguide
      guidelineTopics:
        href: /design/guidelines/haufe-api-styleguide/topics
    references:
      - name: Expires HTTP Header
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#expires-http-header'
      - name: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
      - name: ETag
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#etag'
  - guideline_id: heroku-http-api-design-guide
    guideline_title: HTTP API Design Guide
    guideline_type: gitbook
    guideline_url: 'https://geemus.gitbooks.io/http-api-design/content/en/'
    guideline_company: Heroku
    guideline_companyLogoUrl: /media/logos/heroku.png
    guideline_companyUrl: 'https://devcenter.heroku.com/articles/platform-api-reference'
    guideline_screenshotUrl: /media/screenshots/heroku-http-api-design-guide.png
    guideline_date: 2016-07-05T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/heroku-http-api-design-guide
      guidelineTopics:
        href: /design/guidelines/heroku-http-api-design-guide/topics
    references:
      - name: Require Versioning in the Accepts Header
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-versioning-in-the-accepts-header.html'
      - name: Support ETags for Caching
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/support-etags-for-caching.html'
      - name: Provide Request-Ids for Introspection
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/provide-request-ids-for-introspection.html'
      - name: Divide Large Responses Across Requests with Ranges
        description: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/divide-large-responses-across-requests-with-ranges.html'
  - guideline_id: microsoft-rest-api-guidelines
    guideline_title: Microsoft REST API Guidelines
    guideline_type: github
    guideline_url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md'
    guideline_company: Microsoft
    guideline_companyLogoUrl: /media/logos/microsoft.png
    guideline_companyUrl: 'https://opensource.microsoft.com/'
    guideline_screenshotUrl: /media/screenshots/microsoft-rest-api-guidelines.png
    guideline_date: 2016-07-19T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/microsoft-rest-api-guidelines
      guidelineTopics:
        href: /design/guidelines/microsoft-rest-api-guidelines/topics
    references:
      - name: POST
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
        quote: POST operations SHOULD support the Location response header
      - name: Options and link headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
      - name: Standard request headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
      - name: Standard response headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
      - name: Custom Headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#77-custom-headers'
      - name: Specifying headers as query parameters
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#78-specifying-headers-as-query-parameters'
  - guideline_id: redhat-thoughts-on-restful-api-design
    guideline_title: Thoughts on RESTful API Design
    guideline_type: website
    guideline_url: 'http://restful-api-design.readthedocs.io/en/latest/'
    guideline_company: Red Hat
    guideline_companyLogoUrl: /media/logos/redhat.png
    guideline_companyUrl: 'https://www.redhat.com/'
    guideline_screenshotUrl: /media/screenshots/redhat-thoughts-on-restful-api-design.png
    guideline_authors:
      - name: Geert Jansen
        twitter: 1geertj
    guideline_date: 2012-11-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/redhat-thoughts-on-restful-api-design
      guidelineTopics:
        href: /design/guidelines/redhat-thoughts-on-restful-api-design/topics
    references:
      - name: Link Headers
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
  - guideline_id: white-house-web-api-standards
    guideline_title: White House Web API Standards
    guideline_type: github
    guideline_url: 'https://github.com/WhiteHouse/api-standards'
    guideline_company: White House
    guideline_companyLogoUrl: /media/logos/whitehouse.png
    guideline_companyUrl: 'https://www.whitehouse.gov/developers'
    guideline_screenshotUrl: /media/screenshots/white-house-web-api-standards.png
    guideline_date: 2015-02-24T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/white-house-web-api-standards
      guidelineTopics:
        href: /design/guidelines/white-house-web-api-standards/topics
    references:
      - name: General guidelines for RESTful URLs
        quote: URL v. header
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - guideline_id: zalando-restful-api-guidelines
    guideline_title: RESTFul API Guidelines
    guideline_type: website
    guideline_url: 'http://zalando.github.io/restful-api-guidelines/'
    guideline_company: Zalando
    guideline_companyLogoUrl: /media/logos/zalando.png
    guideline_companyUrl: 'https://tech.zalando.de/'
    guideline_screenshotUrl: /media/screenshots/zalando-restful-api-guidelines.png
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-08-28T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/zalando-restful-api-guidelines
      guidelineTopics:
        href: /design/guidelines/zalando-restful-api-guidelines/topics
    references:
      - name: You Must Hyphenate HTTP Headers
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-you-must-hyphenate-http-headers'
      - name: Prefer Hyphenated-Pascal-Case for HTTP header Fields
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#should-prefer-hyphenatedpascalcase-for-http-header-fields'
      - name: Use Standardized Headers
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-standardized-headers'
      - name: Use 429 with Headers for Rate Limits
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
      - name: Do Not Use Link Headers with JSON entities
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
      - name: HTTP headers
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#http-headers'
        quote: Use the HTTP date format defined in RFC 7231
      - name: Common Headers
        url: 'http://zalando.github.io/restful-api-guidelines/headers/CommonHeaders.html'
      - name: Proprietary Headers
        url: 'http://zalando.github.io/restful-api-guidelines/headers/ProprietaryHeaders.html'
      - name: Add a Warning Header to Responses
        url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html#should-add-a-warning-header-to-responses'
---