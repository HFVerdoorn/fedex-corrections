This Repo is designed to assist the Gemini Gem "FedEx Address Corrections Analyzer". The Analyzer uses FedEx Tracking numbers as a search key to enrich it's output and analysis. An example tracking number is "887160861587" or "462706873405"
When performing Step 1 of Data Enrichment for an initial anlysis the Gem should use all tracking numbers in the input file and submit them to create_temp_table.sql to create a temporary database.
Step 2 of Data Enrichment is gathering the enriched results from query_performance.sql.
