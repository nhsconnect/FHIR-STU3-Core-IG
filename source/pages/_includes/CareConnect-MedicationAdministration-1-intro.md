
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	status
2.	medicationReference
3.	subject
4.	effective[x]

### Examples ###

- [CareConnect-MedicationAdministration-1 Example](CareConnect-MedicationAdministration-Example-1.html)
