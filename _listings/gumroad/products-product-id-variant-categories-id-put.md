---
swagger: "2.0"
info:
  title: Gumroad Put Products Variant Categories
  description: Edit a variant category of an existing product.
  termsOfService: https://gumroad.com/terms
  version: v1
host: api.gumroad.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/:product_id/variant_categories/:id:
    put:
      summary: Put Products Variant Categories
      description: Edit a variant category of an existing product
      operationId: putProductsProductVariantCategories
      parameters:
      - in: query
        name: title
      - in: query
        name: variant_category
      responses:
        200:
          description: OK
      tags:
      - products
      - variant
      - categories
definitions: []
x-collection-name: Gumroad
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