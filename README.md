# flight-cancellations
Using python to analyze the reasons for flight cancellation.

My data is sourced from the Bureau of Transporation Statistics, a sub-agency of the Deportment of Transporation, at the following link:
https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr

This government website allows anyone to download statistics on flights by U.S. domestic carriers with dozens of selectable fields, include airport, aircraft tail number, whether or not the flight was cancelled and the reason if so, scheduled arrival and departures times, and more.

I downloaded data on flights in the year 2015. I chose this year as was affected neither by COVID nor by system outages like the ones recently experienced by Southwest. The original dataset contained about 5,813,554 flights (after dropping flights with invalid IATA airport codes). I also took a subset of the 89,828 that were cancelled. Using this data, I calculated total and proportional cancellations by airports, airlines, day of week, month, and the provided reason. I considered the relationships between factors that may compound difficulties and increase cancellations.
