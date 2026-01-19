GeoMap
Created by: Etienne de Klerk at Salesforce


What is It?

A LWC that displays a google map

Why use it?
While salesforcre publishes a LWC Map specification , there is not a standard component in the box.
Additionally, none of the components I found provided flexibility for coord data source.

How does it work?

Drop onto any record page and configure the LWC properties to specifiy the data source for the coordinates  

You set the following properties:
- custom field:  Geolocation (compound) field, e.g. myFavouriteLocation (Geolocation) and populate it using decimal geo notation  
- Address: standard address fields, Google will do the geocoding
- Lat/Lon, these exisit as hidden fields and are auto populated on some objects, e.g. Contact, Account, Service Appointment.  You can also specify custom lat/lon fields 
- Icon (standard SLDS icon names) 
- Map title
- Zoom level


