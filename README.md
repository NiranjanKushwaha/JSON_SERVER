### Each key is route(End point).
### Suppose you are running you application at some port 4200 do localhost:4200/products it will show all the product list.
### If you do localhost:4200/products/1 it will show the object with id 1.
### To run your application on some port you can specify port number but some script is necessary to run the json server in your system.
"scripts": {
"serve-json": "json-server --watch db.json -a localhost -p 8000"
}
## ==========================================  db.json  ======================================================

{
  "products": [
    {
      "id": 1,
      "title": "Product1",
      "category": "Electronics",
      "price": 1000,
      "Description": "This is description about product 1"
    },
    {
      "id": 2,
      "title": "Product2",
      "category": "Electronics",
      "price": 1001,
      "Description": "This is description about product 2"
    },
  ],
  "reviewes": [
    {
      "id": 1,
      "rating": 3,
      "Comment": "Review 1 for product id 1",
      "productId": 1
    },
    {
      "id": 2,
      "rating": 3,
      "Comment": "Review 1 for product id 1",
      "productId": 1
    },
  ]
}
