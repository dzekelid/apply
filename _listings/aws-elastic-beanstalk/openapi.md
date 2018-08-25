---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ApplyEnvironmentManagedAction:
    get:
      summary: Apply Environment Managed Action
      description: Applies a scheduled managed action immediately.
      operationId: applyEnvironmentManagedAction
      x-api-path-slug: actionapplyenvironmentmanagedaction-get
      parameters:
      - in: query
        name: ActionId
        description: The action ID of the scheduled managed action to execute
        type: string
      - in: query
        name: EnvironmentId
        description: The environment ID of the target environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the target environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
---