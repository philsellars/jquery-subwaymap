jQuery Subway Map Plugin
========================

Based on http://www.kalyani.com/2010/10/subway-map-visualization-jquery-plugin/



##Updated syntax

*(LI) data-markerInfo:* For data-marker type "interchange" or "@interchange," this attribute now defines the pipe-separated coordinates where other station points should be drawn

Example:
    <li data-marker="interchange" data-coords="1,2" data-markerInfo="2,2|1,4"></li>

    This entry will draw an interchange starting at (1,2) to the points (2,2) then (1,4)



