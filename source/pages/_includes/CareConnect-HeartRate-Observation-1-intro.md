
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	basedOn
2.	status
3.	category
4.	code
5.	subject
6.	effective[x]

### Examples ###

- [CareConnect-HeartRate-Observation-1 Example](CareConnect-HeartRate-Observation-Example-1.html)
