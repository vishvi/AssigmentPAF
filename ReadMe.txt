#Order Service#
1.GET All Orders
Url- http://localhost:8080/orders/order/
Method- GET

2.Get Specific Order
Url- http://localhost:8080/orders/order/1
Method- GET	

3.Create New Order
Url- http://localhost:8080/orders/order/
Method- POST
Body- {
"oid": 5,
"odate": "2019-05-05",
"qty": 10,
"total": 2450,
"fid": 456,
"cid": 257,
"sid": 457
}


4.Update Order
Url- http://localhost:8080/orders/order/
Method- PUT
Body- {
"oid": 5,
"odate": "2019-05-05",
"qty": 5,
"total": 2200,
"fid": 456,
"cid": 257,
"sid": 457
}



5.Delete Order
Url- http://localhost:8080/orders/order/1
Method- DELETE
