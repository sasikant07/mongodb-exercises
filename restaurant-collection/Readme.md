# Restaurant Collection

## 1. Write a MongoDB query to display all the documents in the collection restaurant
`db.restaurants.find();`

## 2.Write a MongoDB query to display the fields restaurant_id, name, borough and cuisine for all the documents in the collection restaurant.
`db.restaurants.find({}, {"restaurant_id": 1, "name": 1, "borough": 1, "cuisine": 1});`

## 3. Write a MongoDB query to display the fields restaurant_id, name, borough and cuisine, but exclude the field _id for all the documents in the collection restaurant.
`db.restaurants.find({}, {"restaurant_id": 1, "name": 1, "borough": 1, "cuisine": 1, "_id": 0}).pretty();`

## 4.Write a MongoDB query to display the fields restaurant_id, name, borough and zip code, but exclude the field _id for all the documents in the collection restaurant.
`db.restaurants.find({}, {"restaurant_id": 1, "name": 1, "borough": 1, "address.zipcode": 1, "_id": 0}).pretty();`

## 5. Write a MongoDB query to display all the restaurant which is in the borough Bronx.
`db.restaurants.find({"borough": "Bronx"}).pretty();`
