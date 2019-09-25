
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	status
2.	code
3.	effective[x]
4.	value[x]

### Examples ###

- [CareConnect-Subscore-Observation-1 Example](CareConnect-Subscore-Observation-Example-1.html)
