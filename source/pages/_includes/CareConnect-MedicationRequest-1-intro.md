
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	intent
2.	medicationReference
3.	subject

### Examples ###

- [CareConnect-MedicationRequest-1 Example](CareConnect-MedicationRequest-Example-1.html)
