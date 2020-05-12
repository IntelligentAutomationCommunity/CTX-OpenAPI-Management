# CTX-OpenAPI-Management
Flow to upload OpenAPI specification files and or point to url where OpenAPI specification can be found. It will be uploaded and processed by this flow.

After import you will find this flow under Cortex-Library > CTX-OpenAPI-UPLOAD.
You can access this from the Cortex LivePortal. For ease of use, no Access Control has be been applied.
You can set this manually after you imported the package.

### Usage
The flow allows you to upload multiple OpenAPI specification files (with json extension).
It also supports at the same time to point to a url where the specification can be found.
When the Submit button is clicked both the uploaded files and the url specification will be uploaded to the Cortex server and processed.
After the process is finished a confirmation message is displayed.
The process will validate if the OpenAPI specification meets version 2 specifications.
If a version 1 or 3 specification is used it will not be processed.

# Installation Instructions
Download the Studio Package file and Import it into your Cortex Environment.
Don't forget to apply rights using the Studio Authorization module.

### Note
This flow works for Cortex version 7 only at the moment.

:thumbsup: Success! :wink:

