---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "fhirrest_fhir_resource Data Source - fhirrest"
subcategory: ""
description: |-
  This data source is able to read a fhir resource and return it as a json
---

# fhirrest_fhir_resource (Data Source)

This data source is able to read a fhir resource and return it as a json



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `resource_id` (String) The id of the fhir resource, example Medication/08146022-932a-4001-9fe4-928382855ddf

### Read-Only

- `resource` (String) The fhir json as string