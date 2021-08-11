*"You have been asked by GE Aviation leadership to create a single data set that combines all the data listed above into a single table.*

*The data you have been given has sheets related to Flight data (so data relating to the health of the mechanical engine of a plane), Location Data for airports, Manufacturing Data (which relate to various airplane parts), and a manufacturing bill of material (which tells you what engines have been used).*

*In this final form, we can then use this table to either create a prediction of RUL or visualize the data for easy user consumption. This will be done in task two."*

**Excel:**
1. Cleanup: AIC stored their t24 column in Rankine, the other airlines kept their temps in a standard format. Adjusted the column accordingly.

1. Merged all four "av_engine_data" datasets into one sheet.

1. Using INDEXMATCH, found the relationships between the "av_manufacturing_supply_chain_psql" sheet and the "av_bom_manufacturing_psql" and combine them into a seperate sheet called "manufacturing_combined."

**Tableau:**
1. Cleanup: AIC stored their t24 column in Rankine, the other airlines kept their temps in a standard format. Adjusted the column accordingly using a calculated field.

1. Joined all flight tables to consilidate data with a union.
