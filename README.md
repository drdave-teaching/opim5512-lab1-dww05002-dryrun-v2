# opim5512-lab1-dww05002-dryrun-v2

## Data Dictionary

### data/clean/weather_hourly.csv  (Partner A)
| column       | meaning                                          | units |
|--------------|--------------------------------------------------|-------|
| hour         | timestamp — the hour that BEGINS                 | —     |
| tmpf       | air temperature                                  | °F    |
| dwpf   | dew point                                        | °F    |
| relh | relative humidity                                | %     |
| sknt      | wind speed                                        | knots |

**Convention:** `hour` is the hour that BEGINS. Weather is floored from the :51 observation.
**Missing hours:** ____ (drop the row, or keep it blank? — write which).

