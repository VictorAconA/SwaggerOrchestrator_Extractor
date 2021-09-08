# Swagger Orchestrator Extractor

Description: 

The workflow open a Chrome browser to extract 4 fields from a Swagger Orchestrator Endpoint API:
* Type of Request: GET,POST
* Endpoint: /api/FoldersNavigation/GetAllFoldersForCurrentUser
* OAuth: OAuth authentication is not supported.
* Required permissions: Users.View

Input:
* in_SwaggerUrl: Swagger URL
* in_ExcelOutput: Path to save the Excel file

Output: 
* Excel file in the target path
