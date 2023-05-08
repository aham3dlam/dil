swagger: '2.0'
info:
  version: '1.0'
  title: april_poc
  x-lastModified: '2023-05-08T07:08:00.000Z'
paths:
  /get/day:
    post:
      produces:
        - application/json
      responses:
        '200':
          description: Success response
      parameters:
        - name: q
          in: query
          description: ''
          required: false
          type: string
          format: ''
        - name: hi
          in: header
          description: ''
          required: false
          type: string
          format: ''
      operationId: postGetDay
      description: hihi
      summary: hihi
