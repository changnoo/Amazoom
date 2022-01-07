## Amazoom

This is the final project that my team and I worked on for CPEN 333. Amazoom, an Amazon clone, simulates a warehouse with items, robots, and trucks in real-time. A user can place an order throuhgh our web interface, and restocking trucks will be called to restock items that are low in stock, and robots will begin physically moving around the warehouse to execute various tasks. The robots then ship the products from the warehouse into the delivery trucks, and the customer receives their order. This project was built with multithreading in C#, with an ASP.NET MVC webpage, MongoDB database and WPF as a graphical user inteface for the warehouse status.<br>

### Features 
* __Order Placement through __Amazoom__ website__
  * Beautiful clien-interface
  * Order sent to database
* __Order fulfillment__ 📦
  * Automatic detection of new orders 
  * Robots gather items around warehouse
  * Drop off items into truck
  * Truck (_if carrying sufficient weight_) leaves warehouse
* __Restocking__ 🚛
  * Truck with new items arrives
  * Robots unload truck, place new items into warehouse
* __Database updated to reflect live status of orders and items__
  * e.g. Available, Purchases, Loaded, Shipped for items

## Demo 


https://user-images.githubusercontent.com/71570400/147901336-a1b36cf9-9526-4697-a71f-630c49163f35.mp4

