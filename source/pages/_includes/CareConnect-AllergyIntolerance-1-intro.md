
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	verificationStatus
2.	patient
3.	assertedDate

### Examples ###

- [CareConnect-AllergyIntolerance-1 Example](CareConnect-AllergyIntolerance-Example-1.html)
