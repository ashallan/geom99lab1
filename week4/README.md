There are many addition tools available in the Developers website to manage and create data, applications, 
and other components that cannot be found in the main user-focused AGOL interface. 

In particular there are a few tools to create and import layers: https://developers.arcgis.com/layers/

Create  Use the Create Data / New Hosted Layer to generate an empty layer in ArcGIS Online's Data Store (sometimes tables are referred 
to as a Schemas since you are designing the database structure). Use the specifications from the Fall Geom65 tree collection database 
description (below) to create this new schema as a single table (or if you have your own idea you can create a layer to capture that too 
as a single table--just ask during your lab before you start).

Once created, use the ArcGIS Online web map website to add a few records of fictitious data using a web map to see how it works with the 
web interfaces. Be sure to enable editing on the items settings page (see the different links below) before trying to edit it! Use one of the 
many methods documented to edit the features and attributes https://doc.arcgis.com/en/arcgis-online/manage-data/use-hosted-layers.htm. 



URL 1: Developers Details Item Page
The ArcGIS Developers site has its own UX for interacting specifically with Hosted Feature Layers in ArcGIS Online. This page should be shown 
after you create your new layer. The link will look similar to https://developers.arcgis.com/layers/3226b7ae87cf4f1a8bb3b36cac8108fb/. Can you 
find the Item id in the url? Note only the owner of the hosted feature layer will be able to open this developers URL. 

URL 2: ArcGIS Online Items Page
ArcGIS Online's main UX has a generic AGOL Item viewer that is found in the main interface for ArcGIS Online. The URL will look similar to this: 
https://fleming.maps.arcgis.com/home/item.html?id=3226b7ae87cf4f1a8bb3b36cac8108fb. Anyone with the rights to see this item will be able to open this URL.

Tip: You can "paste" any item id in the place of the parameter id= to open it directly! It's like a URL shortcut. 

URL 3: REST API
The final link is different and references access to the actual data store (AKA the database and tables themselves). In the case of the item above, 
this URL provides access to the REST Services Directory. 

https://services1.arcgis.com/pMeXRvgWClLJZr3s/arcgis/rest/services/Geocommunity_Project_Listings/FeatureServer

Opening this URL above you can actually see the REST API endpoint has an entry to link back to the item ID! Use the Tip in URL 2 to open the ArcGIS 
Online Item associated with this dataset (this displays the item metadata). 

Service ItemId: 3226b7ae87cf4f1a8bb3b36cac8108fb

Update June 2022: If opening a service URL from ArcGIS Online Esri now embeds this into an iframe (which hides the power of seeing the services 
URL directly!). So your URL will not look like above and instead like this URL (notice how the domain part is very different):

https://fleming.maps.arcgis.com/home/item.html?id=3226b7ae87cf4f1a8bb3b36cac8108fb&view=service (pretty much the same as URL 2, with view=service added). 

It is best to open the REST API Endpoint URL directly. One of many ways to open the iframe in a new tab using Chrome is to right click on the framed part 
of the window, then select View Frame Source. It will open the code section but you can just remove the view-source: portion of the URL and it will open 
exposing the desired URL.

Submit Create a document with all three different link types from above to your hosted feature layer item and its data (Be sure to not include the token). 
Store these (again, without a security token) in a web page or MarkDown document on your GitHub for this weeks' activities (name this whatever you wish, 
just know how to find it for the practical lab!). 
