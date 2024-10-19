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

## 6. Write a MongoDB query to display the first 5 restaurant which is in the borough Bronx.
`db.restaurants.find({"borough": "Bronx"}).limit(5).pretty();`

## 7. Write a MongoDB query to display the next 5 restaurants after skipping first 5 which are in the borough Bronx.
`db.restaurants.find({"borough": "Bronx"}).skip(5).limit(5).pretty();`

## 8. Write a MongoDB query to find the restaurants who achieved a score more than 90.
`db.restaurants.find({"grade": {$elemMatch: {"score": {$gt: 90}}}}).pretty();`

## 9. Write a MongoDB query to find the restaurants that achieved a score is more than 80 but less than 100.
`db.restaurants.find({"grade": {$elemMatch: {"score": {$gt: 80, $lt: 100}}}}).pretty();`

## 10. Write a MongoDB query to find the restaurants which locate in a latitude value less than -95.754168.
`db.restaurants.find({"address.coord": {$lt: -95.754168}}).pretty();`

## 11. Write a MongoDB query to find the restaurants that do not prepare any cuisine of 'American' and their grade score more than 70 and lattitude less than -65.754168.
`db.restaurants.find(
    {$and: [
        {"cuisine": {$ne: "American"}},
        {"grade.score": {$gt: 70}},
        {"address.coord": {$lt: -95.754168}}
    ]
  ).pretty();`