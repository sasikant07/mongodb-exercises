db.createCollection("restaurants");

db.restaurants.insertMany([
  {
    "_id": ObjectId("564c2d939eb21ad392f175c9"),
    "address": {
      "building": "351",
      "coord": [-73.98513559999999, 40.7676919],
      "street": "West 57 Street",
      "zipcode": "10019"
    },
    "borough": "Manhattan",
    "cuisine": "Irish",
    "grades": [
      { "date": ISODate("2014-09-06T00:00:00Z"), "grade": "A", "score": 2 },
      { "date": ISODate("2013-07-22T00:00:00Z"), "grade": "A", "score": 11 },
      { "date": ISODate("2012-07-31T00:00:00Z"), "grade": "A", "score": 12 },
      { "date": ISODate("2011-12-29T00:00:00Z"), "grade": "A", "score": 12 }
    ],
    "name": "Dj Reynolds Pub And Restaurant",
    "restaurant_id": "30191841"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175ca"),
    "address": {
      "building": "1007",
      "coord": [-73.856077, 40.848447],
      "street": "Morris Park Ave",
      "zipcode": "10462"
    },
    "borough": "Bronx",
    "cuisine": "Bakery",
    "grades": [
      { "date": ISODate("2014-03-03T00:00:00Z"), "grade": "A", "score": 2 },
      { "date": ISODate("2013-09-11T00:00:00Z"), "grade": "A", "score": 6 },
      { "date": ISODate("2013-01-24T00:00:00Z"), "grade": "A", "score": 10 },
      { "date": ISODate("2011-11-23T00:00:00Z"), "grade": "A", "score": 9 },
      { "date": ISODate("2011-03-10T00:00:00Z"), "grade": "B", "score": 14 }
    ],
    "name": "Morris Park Bake Shop",
    "restaurant_id": "30075445"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175cb"),
    "address": {
      "building": "2780",
      "coord": [-73.98241999999999, 40.579505],
      "street": "Stillwell Avenue",
      "zipcode": "11224"
    },
    "borough": "Brooklyn",
    "cuisine": "American",
    "grades": [
      { "date": ISODate("2014-06-10T00:00:00Z"), "grade": "A", "score": 5 },
      { "date": ISODate("2013-06-05T00:00:00Z"), "grade": "A", "score": 7 },
      { "date": ISODate("2012-04-13T00:00:00Z"), "grade": "A", "score": 12 },
      { "date": ISODate("2011-10-12T00:00:00Z"), "grade": "A", "score": 12 }
    ],
    "name": "Riviera Caterer",
    "restaurant_id": "40356018"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175cc"),
    "address": {
      "building": "469",
      "coord": [-73.961704, 40.662942],
      "street": "Flatbush Avenue",
      "zipcode": "11225"
    },
    "borough": "Brooklyn",
    "cuisine": "Hamburgers",
    "grades": [
      { "date": ISODate("2014-12-30T00:00:00Z"), "grade": "A", "score": 8 },
      { "date": ISODate("2014-07-01T00:00:00Z"), "grade": "B", "score": 23 },
      { "date": ISODate("2013-04-30T00:00:00Z"), "grade": "A", "score": 12 },
      { "date": ISODate("2012-05-08T00:00:00Z"), "grade": "A", "score": 12 }
    ],
    "name": "Wendy'S",
    "restaurant_id": "30112340"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175cd"),
    "address": {
      "building": "97-22",
      "coord": [-73.8601152, 40.7311739],
      "street": "63 Road",
      "zipcode": "11374"
    },
    "borough": "Queens",
    "cuisine": "Jewish/Kosher",
    "grades": [
      { "date": ISODate("2014-11-24T00:00:00Z"), "grade": "Z", "score": 20 },
      { "date": ISODate("2013-01-17T00:00:00Z"), "grade": "A", "score": 13 },
      { "date": ISODate("2012-08-02T00:00:00Z"), "grade": "A", "score": 13 },
      { "date": ISODate("2011-12-15T00:00:00Z"), "grade": "B", "score": 25 }
    ],
    "name": "Tov Kosher Kitchen",
    "restaurant_id": "40356068"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175ce"),
    "address": {
      "building": "8825",
      "coord": [-73.8803827, 40.7643124],
      "street": "Astoria Boulevard",
      "zipcode": "11369"
    },
    "borough": "Queens",
    "cuisine": "American",
    "grades": [
      { "date": ISODate("2014-11-15T00:00:00Z"), "grade": "Z", "score": 38 },
      { "date": ISODate("2014-05-02T00:00:00Z"), "grade": "A", "score": 10 },
      { "date": ISODate("2013-03-02T00:00:00Z"), "grade": "A", "score": 7 },
      { "date": ISODate("2012-02-10T00:00:00Z"), "grade": "A", "score": 13 }
    ],
    "name": "Brunos On The Boulevard",
    "restaurant_id": "40356151"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175cf"),
    "address": {
      "building": "6409",
      "coord": [-74.00528899999999, 40.628886],
      "street": "11 Avenue",
      "zipcode": "11219"
    },
    "borough": "Brooklyn",
    "cuisine": "American",
    "grades": [
      { "date": ISODate("2014-07-18T00:00:00Z"), "grade": "A", "score": 12 },
      { "date": ISODate("2013-07-30T00:00:00Z"), "grade": "A", "score": 12 },
      { "date": ISODate("2013-02-13T00:00:00Z"), "grade": "A", "score": 11 },
      { "date": ISODate("2012-08-16T00:00:00Z"), "grade": "A", "score": 2 },
      { "date": ISODate("2011-08-17T00:00:00Z"), "grade": "A", "score": 11 }
    ],
    "name": "Regina Caterers",
    "restaurant_id": "40356649"
  },
  {
    "_id": ObjectId("564c2d939eb21ad392f175d0"),
    "address": {
      "building": "7114",
      "coord": [-73.9068506, 40.6199034],
      "street": "Avenue U",
      "zipcode": "11234"
    },
    "borough": "Brooklyn",
    "cuisine": "Delicatessen",
    "grades": [
      { "date": ISODate("2014-07-18T00:00:00Z"), "grade": "A", "score": 10 },
      { "date": ISODate("2013-07-30T00:00:00Z"), "grade": "A", "score": 12 },
      { "date": ISODate("2013-02-13T00:00:00Z"), "grade": "A", "score": 11 },
      { "date": ISODate("2012-08-16T00:00:00Z"), "grade": "A", "score": 2 },
      { "date": ISODate("2011-08-17T00:00:00Z"), "grade": "A", "score": 11 }
    ],
    "name": "Sunster Caterers",
    "restaurant_id": "30075445"
  }
]);

db.restaurants.find();