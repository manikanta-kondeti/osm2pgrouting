Openstreet Map Basics:
====================

#Basics Nodes and Tags:
* We call point as node. It is set of coordinates(a latitude and a longitude)
* Tags: The way we tell the computer what a node and point represent. They are basically keywords. 
	* Tags has two parts: Key, Value
		Key       |     Value 
		---------------------
		Natural   | 	tree
		Amenity   | 	Cafe 
		Highway   | 	Street_lamp
		
#Ways = Lines: 
* Collection of nodes. Ordering of the nodes as well. Ordering helps the computer to know what shape it is. 
* For computer geek: Way is an ordered list. Like we have tags for nodes, we have the same for ways.
	* Tags has two parts: Key, Value
		Key       |     Value 
		-----------------------
		Waterway  | 	River
		Highway   | 	Footway
		Highway   | 	Road 
#Closed Ways and Object ID's:
* Polygons = closed ways.
* Eg: If we have 4nodes polygon with their id starting from 500 with way id: 20. This will be the final order: 500, 501, 502, 503, 500.

#Routing: 
* Lets assume if have a map with streets. Lets take a way which is with name street. Name: MainStreet, Highway: Primary.  Consider another way with Name: Oah street, Highway: Secondary. Thid: Name: Elm street, Highway: residential. Fourth: Name: Ceder Lane, Highway: residential one_way= yes.
* In open street map, roads are said to be connected when they share a node.
* We need to draw new nodes whenever there is a chance of convergence.


