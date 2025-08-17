[[Coalesce 2022]]

- Anomalies can be of several types (format, headings, spelling, null values, duplicate data, inaccurate)
- Solution: add an inspection layer
	- Define dbt models which enforce stakeholder expectations
	- Quarantine any anomalis
	- Reference the inspection models later to exclude bad data
	- Provide operational teams a method to retrieve quarantine data
- Make that based on expectations of stakeholders
- Make main inspection model by unioning a lot of inspection relations
- https://github.com/RedPillAnalytics/dbt_coalesce_workshop