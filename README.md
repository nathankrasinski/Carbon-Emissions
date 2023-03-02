# Carbon-Emissions
SQL Query to pull Carbon Emissions by Industry

Greenhouse gas emissions attributable to products—from food to sneakers to appliances—make up more than 75% of global emissions._ -The Carbon Catalogue

Our data, which is publicly availably on nature.com, contains product carbon footprints (PCFs) for various companies. PCFs are the greenhouse gas emissions attributable to a given product, measured in CO2 (carbon dioxide equivalent).

This data is stored in a PostgreSQL database containing one table, prouduct_emissions, which looks at PCFs by product as well as the stage of production these emissions occured in. Here's a snapshot of what product_emissions contains in each column:

product_emissions
field	data_type
id	VARCHAR
year	INT
product_name	VARCHAR
company	VARCHAR
country	VARCHAR
industry_group	VARCHAR
weight_kg	NUMERIC
carbon_footprint_pcf	NUMERIC
upstream_percent_total_pcf	VARCHAR
operations_percent_total_pcf	VARCHAR
downstream_percent_total_pcf	VARCHAR

Examine the carbon footprint of each industry in the dataset!
