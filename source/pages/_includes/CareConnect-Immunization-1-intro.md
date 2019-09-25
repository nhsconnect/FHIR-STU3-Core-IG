
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	status
2.	notGiven
3.	vaccineCode
4.	patient
5.	primarySource

### Examples ###

- [CareConnect-Immunization-1 Example](CareConnect-Immunization-Example-1.html)
