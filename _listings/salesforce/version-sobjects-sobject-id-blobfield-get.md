---
swagger: "2.0"
info:
  title: SalesForce Get Version Sobjects Sobject  Blobfield
  description: Retrieves the specified blob field from an individual record. Because
    blob fields contain binary data, you can't use JSON or XML to retrieve this data.
  version: 1.0.0
host: na14.salesforce.com
basePath: /services/data
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{version}/sobjects/{sobject}/{id}/{blobField}:
    get:
      summary: Get Version Sobjects Sobject  Blobfield
      description: Retrieves the specified blob field from an individual record
      operationId: version.sobjects.sobject.id.blobField.get
      parameters:
      - in: query
        name: fields
        description: Optional list of fields used to return values for
      responses:
        200:
          description: OK
      tags:
      - version
      - sobjects
      - sobject
      - ""
      - blobfield
definitions: []
x-collection-name: Salesforce
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