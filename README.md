oca-housing-mobility-map
====================

Connecticut Open Communities Alliance housing mobility tools

# Demos

## Mobility App for housing mobility counselors and clients
http://jackdougherty.github.io/oca-housing-mobility-map/index.html

TO DO:
- if possible, display transportation options between new address and 2nd address (work, school, etc.) and integrate Google Directions API as another map layer. See Google Routes sample code (https://github.com/JackDougherty/Google_Routes) and live demo (http://jackdougherty.github.io/Google_Routes/) See also NON-FUNCTIONAL MOCKUP for desired placement of 2nd address (http://jackdougherty.github.io/oca-housing-mobility-map/index-2-addresses.html)
- Erin to decide about Places of Worship data
- Erin/Jack to discuss whether or not she wishes the end product to appear as an iframe inside another web page, and if so, switch to Derek Eder's new iframe template (https://github.com/JackDougherty/FusionTable-Map-polygons-legend#fusiontable-map-polygons-legend)
- Erin/Jack to modify initial appearance (which looks a bit cluttered) by selecting layers/points to display by default
- Erin/Jack to decide whether to keep existing shading legend (http://magic.lib.uconn.edu/test/n/images/oppIndex_legend.png) which is a static image that cannot be modified, or to switch the template to a dynamic coded shading (similar to http://jackdougherty.github.io/FusionTable-Map-polygons-legend/iframe_test.html). In either case, modify polygon colors and saturation levels to match.
- Erin/Jack to add explanatory text and links to source data (preferably point to Google Fusion Tables for public download)
- Erin/Jack to explore options for embedding tool within her website

## Opportunity and Race Map
http://jackdougherty.github.io/oca-housing-mobility-map/index_minorityMap.html

TO DO:
- if possible, display town labels on this interactive map. Natalia says not possible to do so as a separate KML layer. Displaying labels on interactive maps is very different from static maps, where labels remain same size without zooming. There are other ways to display labels on other interactive map platforms, such as this Leaflet.js "hover to see labels & data" template by Alvin Chang at CT Mirror (http://ctmirror.org/malloy-vs-foley-in-maps-what-changed-from-2010-to-2014/#graphic). But alternative solutions all require some coding skills and storing data in a different way, which will not allow Erin to easily make changes in the future.

## Overall
- make sure that Erin has access and skills to modify Google Fusion Table data points; access to GitHub code to embed on her website

#Credits
- originally created at CT Mirror Hackathon April 2014
- based on Searchable Map Template for Google Fusion Tables by @derekeder
- data contributions by Scott @sgaul https://github.com/sgaul/opportunity
- contributions by Christopher @cbrechlin
- code contributions by NataliaV @nav10003
