# Task 2
*"When our parts are manufactured, individual design attributes are machined into each part as it goes down the assembly line. This results in a finished part. This is called an operation.*

*Think, a part can start out as a block of metal and through manufacturing operations, this block will become a useable part. After each operation, there is an expected nominal measurement of the design attribute that we record in manufacturing records. This is to ensure each part is made the same and will fit its required purpose.*

*There is also an acceptable tolerance (how far off the measurement is allowed) from that nominal value.*

*Your task is to report to our supply chain management team how our manufacturing process is performing. To do this, you need to will need to use data visualization to determine:*

* *If the parts manufactured fall within the specified range*
* *The pass / fail rate of each part against the dedicated KPIs"*

## Tableau:
### First Chart
*"We have supplied a table that is ready to be visualized. Your task is to create a run chart that will visualize the measurement of a given feature of each operation for a given part number."*

1. Visualized the measurement of a given feature of each operation for a given part number (pn); showed whether it is within specifications using the minimum (min) and maxiumum (max) measurements.

### Second Chart
*"Supply chain management wants to know what the pass/fail rate is for each operation of a given part."*

1.  Determined whether each part passed or failed (fell outside the specified measurements, either over or under) using a calculated column and if/then.

1. Visualized the pass/fail rate for each operation of a given part; identified failed parts during operation (over maximum or under minimum measurements), as well as passed parts.

### Third Chart (optional)
*"For fun - you can use the destination_latitude and destination_longitude for mapping."*

1. Joined av_airport_codes_t (airport codes with latitude and longitude) with combined engine data for the four airlines (contains departure and destination airports for flights tracked within the period monitored), resulting in coordinates for departure and destination flights.

1. Using the destination latitudes and longitudes, charted the flights on a map using size to reflect popularity and color to reflect the airline.

