# SpringBoot-MongoDB-Mapping

Perform One to one , one to many mapping

Create database Flipkart then collection order_DB

Testing Perform in Postman

Post Method-http://localhost:8902/order-service/placedOrderNow

{
 "id":1,
 "name":"sharvan",
 "gender":"male",
 "products":[
     {
         "name":"mobile",
         "quantity":1,
         "price":5000
     },
     {
         "name":"cooler",
         "quantity":3,
         "price":9000
     }
 ],
 "address":{
"city":"smk",
"state":"hry",
"pincode":"132101"
 }   
}

Get Method by name- http://localhost:8902/order-service/getUserByName/ram

Get Method by city- http://localhost:8902/order-service/getUserByAddress/smk
