swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/apply:
    post:
      summary: Filter Apply
      description: 'Filter: apply Apply the given filter criteria on the given column.'
      operationId: Filter:Apply
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtfilterapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/apply:
    post:
      summary: Filter Apply
      description: 'Filter: apply Apply the given filter criteria on the given column.'
      operationId: Filter:Apply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Apply
  /workbook/names(&lt;name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooknamesltnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbooktablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply