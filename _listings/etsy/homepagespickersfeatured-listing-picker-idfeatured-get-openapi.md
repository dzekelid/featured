---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 0
info:
  title: Etsy Get Homepages Pickers Featured Listing Picker Featured
  description: Retrieves a set of FeaturedListing objects associated to a FeaturedListingPicker.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /homepages/pickers/{featured_listing_picker_id}:
    get:
      summary: Get Homepages Pickers Featured Listing Picker
      description: Retrieves a FeaturedListingPicker by id.
      operationId: getHomepagesPickersFeaturedListingPicker
      x-api-path-slug: homepagespickersfeatured-listing-picker-id-get
      parameters:
      - in: path
        name: featured_listing_picker_id
      responses:
        200:
          description: OK
      tags:
      - Home Pages
      - Pickers
      - Featured
      - Listing
      - Picker
  /homepages/pickers/{featured_listing_picker_id}/featured:
    get:
      summary: Get Homepages Pickers Featured Listing Picker Featured
      description: Retrieves a set of FeaturedListing objects associated to a FeaturedListingPicker.
      operationId: getHomepagesPickersFeaturedListingPickerFeatured
      x-api-path-slug: homepagespickersfeatured-listing-picker-idfeatured-get
      parameters:
      - in: path
        name: featured_listing_picker_id
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      responses:
        200:
          description: OK
      tags:
      - Home Pages
      - Pickers
      - Featured
      - Listing
      - Picker
      - Featured
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