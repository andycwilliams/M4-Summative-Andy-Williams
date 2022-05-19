# Game-Store

Game store api that manages inventory and provides a means of purchasing products

# Generation of Invoice

In order to generate an invoice in our back-end, make a post request with the following body structure:

* Name
* Street
* City
* State
* Zipcode
* Item Type: User must input either T-Shirts/Consoles/Games written exactly as shown on this line
* Item Id: The id must match a t-shirt/console/game that exists within the database
* Quantity

By establishing a post request with this structure, our api will determine the appropriate invoice in relation to item type and id.
