## CLI

These settings don't need to apply `--cli` on the command line.

``` yaml
cli:
  cli-name: digitaltwins
  package-name: azure-mgmt-digitaltwins
  namespace: azure.mgmt.digitaltwins
  test-scenario:
    - name: /DigitalTwins/put/Put a DigitalTwinsInstance resource
    - name: /DigitalTwinsEndpoint/put/Put a DigitalTwinsInstance resource
    - name: /DigitalTwinsEndpoint/get/Get a DigitalTwinsInstance endpoint
    - name: /DigitalTwinsEndpoint/get/Get a DigitalTwinsInstance endpoints
    - name: /DigitalTwins/get/Get a DigitalTwinsInstance resource
    - name: /DigitalTwins/get/Get DigitalTwinsInstance resources by resource group
    - name: /DigitalTwins/get/Get DigitalTwinsInstance resources by subscription
    - name: /Operations/get/Get available operations
    - name: /DigitalTwins/patch/Patch a DigitalTwinsInstance resource
    - name: /DigitalTwins/post/Check name Availability
    - name: /DigitalTwinsEndpoint/delete/Delete a DigitalTwinsInstance endpoint
    - name: /DigitalTwins/delete/Delete a DigitalTwinsInstance resource
```