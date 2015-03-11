# openhab2-bindings
This repository contains (or rather will) certain bindings for openhab2. They are basically tailored to my needs, 
but maybe it helps someone too.

Currently it contains
- Port of the 1.x `RRD4jService` due to not yet supported `ItemRegistry`in the compat1x API. It contains 
only the required changes to get the `default chart provider`and the contained `RRD4JChartProvierServlet` running
(see https://github.com/openhab/openhab2/issues/146 for details)

In the near future
- JeeLink binding supporting discovery for LaCrosse IT+ sensors
- Dimplex NWPM binding for Dimplex/Buderus heat pumps
