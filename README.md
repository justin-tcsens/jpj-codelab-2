# Vehicle Service
Vehicle service endpoint.

## Tasks
- Clone the project to your local workspace.
- Modify '/vehicle' endpoint, on GET request type.
    - Change operationId to 'getVehicleByCriteria' 
    - Add query parameters:-
        | # | Properties | Mandatory | Variable Type | 
        | --- | --- | --- | --- |
        | 1 | carPlateNumber | false | string |
        | 2 | manufacturerYear | false | string |
        | 3 | pageNo | true | integer |
        | 4 | pageSize | true | integer |
- Modify '/summon' endpoint, remove existing carPlateNumber query parameter.
- Reference carPlateNumber to externalize carPlateNumber schema.

### Notes:
- Right click at Visual Studio Code.
- Click on Command Palette -> OpenAPI: Show Preview Using Swagger UI, to preview your Open API specification.
