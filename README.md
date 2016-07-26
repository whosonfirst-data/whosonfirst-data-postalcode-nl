# whosonfirst-data-postalcode-nl

## About the data

![clustr](images/nl-oa-clustr.png)

This dataset is incomplete and approximate.

Specifically of the [3,782 records](data) included in this repository 1,035 of them lack any geographic data. They are ["visiting Null Island"](https://whosonfirst.mapzen.com/spelunker/nullisland/?iso=nl) so to speak.

_As of this writing this repository contains only 4-character postal codes. The Netherlands has upwards of 400,000 6-character codes (as found in OpenAddresses) that will be imported shortly._

The [remaining 3,750 records](https://whosonfirst.mapzen.com/spelunker/placetypes/postalcode/?iso=nl&exclude=nullisland) have geometries that were derived nlom the available address data for Netherlands [as provided by OpenAddresses](https://results.openaddresses.io/) on July 23, 2016 which was used to generate polygons using the [Clustr](https://github.com/whosonfirst/Clustr) tool.

All geometries generated using the Clustr tool should be considered approximate as denoted by the `mz:is_approximate` and `mz:is_clustr` properties. In time we expect (hope) that these records will be updated with current and authoritative data provided by the Dutch postal service.

Until then these geometries are [at least more accurate]() than "all of the Netherlands" and have been assigned [full hierarchies]() in Who's On First land.

![clustr](images/nl-oa-clustr-detail.png)

## See also

* https://github.com/whosonfirst-data/whosonfirst-data-postalcode
* https://en.wikipedia.org/wiki/Postal_codes_in_the_Netherlands