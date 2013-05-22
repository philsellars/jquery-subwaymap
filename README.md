jQuery Subway Map Plugin
========================

Based on http://www.kalyani.com/2010/10/subway-map-visualization-jquery-plugin/



##Updated syntax

*(LI) data-markerInfo:* For data-marker type "interchange" or "@interchange," this attribute now defines the pipe-separated coordinates where other station points should be drawn

Example:

    <li data-marker="interchange" data-coords="1,2" data-markerInfo="2,2|1,4"></li>

    This entry will draw an interchange starting at (1,2) to the points (2,2) then (1,4)


* Plugin now supports individual colours for stations using the 'data-color' attribute
of a <li> item. 

Example 
		<li data-coords='{0},{1}' data-marker='interchange' data-labelPos='{3}' data-color='red'></li>

## Other updates

* Add new global constant _NODESIZE to make sizing the station nodes a little easier

* Adjusted ratio of z-index calculation from 2000:1000 to 20:10

* Adjusted the position of the "W" label position to accomodate the new default node size



