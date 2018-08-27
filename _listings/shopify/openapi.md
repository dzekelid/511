swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/discounts/2951196163.json:
    delete:
      summary: Delete a discount
      description: Delete a discount.
      operationId: deleteAdminDiscounts2951196163.json
      x-api-path-slug: admindiscounts2951196163-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Discount
  /admin/discounts/2951196163/disable.json:
    post:
      summary: Disable a discount
      description: Disable a discount.
      operationId: postAdminDiscounts2951196163Disable.json
      x-api-path-slug: admindiscounts2951196163disable-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Disable
      - Discount