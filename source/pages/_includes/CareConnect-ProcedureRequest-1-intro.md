
{% assign id = {{page.id}} %}

{{site.data.structuredefinitions.[id].description}}

### Profile Minimum Viable Content (MVC) ###

The following elements are mandatory in the FHIR profile (i.e. MUST be present):

1.	status
2.	intent
3.	code
4.	subject
5.	performer

### Examples ###

- [CareConnect-ProcedureRequest-1 Example](CareConnect-ProcedureRequest-Example-1.html)
