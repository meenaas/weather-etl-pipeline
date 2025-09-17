# weather-etl-pipeline
Ingest weather API  data, transform and oad into Postgres
blueprint -- CSV
target column	JSON path	note
city	name	str
country	sys.country	str
datetime_utc	dt	unix → UTC ISO
