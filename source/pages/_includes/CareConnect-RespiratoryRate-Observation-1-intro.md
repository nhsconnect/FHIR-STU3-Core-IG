
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	status
2.	category
3.	code
4.	subject
5.	effective[x]

### Examples ###

- [CareConnect-RespiratoryRate-Observation-1 Example](CareConnect-RespiratoryRate-Observation-Example-1.html)
