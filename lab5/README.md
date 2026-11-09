## Study area and dates

I used [AccessAIS](https://marinecadastre.gov/accessais/) data for July 21, 2025 (UTC). I chose the Seattle–Eagle Harbor crossing to study passenger traffic on a summer weekday. Limiting the request to one day and 66 square miles kept the dataset manageable.

## Interpretation

The Passenger filter selected 27 of the 400 vessel paths. At 00:37 PDT on July 21, passenger trails showed an east–west crossing between the Seattle waterfront and Eagle Harbor. Another trail extended southwest from Seattle, so not all passenger traffic followed the same route.

## Feature proposal

A ferry rider could click a trail to see the vessel name and tell which ferry used that route. The [deck.gl interactivity guide](https://deck.gl/docs/developer-guide/interactivity) gave me this idea by showing how a click can identify a map object.