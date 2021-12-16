# Basic data analysis using Spark

Exploring Craft Brewery data to perform basic data analysis using Spark. The data includes three files:
  - beers.csv
  - breweries.csv
  - dictionary.doc

Then, I used Spark and related language such as SQL to answer some questions:
1.	Determine the number of breweries in each state
2.	Determine the cities with the most breweries
3.	Determine the most brewed beer style

Code & results:

## 1. Determine the number of breweries in each state
  -	Import the package:

![.](https://user-images.githubusercontent.com/86505407/146413603-29a7bc43-f006-4014-aaea-6e3a8afd81fb.png)

  - Load the csv file into Spark:
![.](https://user-images.githubusercontent.com/86505407/146413750-2588ec81-c26b-4342-8e4d-ecda6c60a4ea.png)

  -	Remove the header:

![.](https://user-images.githubusercontent.com/86505407/146413766-20f84cb2-b67d-4a65-a436-dada67abca5a.png)
![.](https://user-images.githubusercontent.com/86505407/146413777-d1b0b555-462e-44de-9e33-e63e73ca6f0d.png)
![.](https://user-images.githubusercontent.com/86505407/146413795-b1d230ad-7653-4b16-96b3-8e5e3f83bbab.png)

  -	Define the column names, and put name for the table (breweries). Finally, get the result which shows the number of breweries in each state.  

![.](https://user-images.githubusercontent.com/86505407/146413827-a96dd2f5-ffb6-4443-aff6-3458a5d4818c.png)
![.](https://user-images.githubusercontent.com/86505407/146413863-c4e0c16d-1c8b-47cf-92e6-c82c4b19c80d.png)

  -	Result:

![.](https://user-images.githubusercontent.com/86505407/146413878-7812fb12-af5d-4115-a12b-fcc26c2faf2a.png)

## 2.	Determine the cities with the most breweries
  -	Determine the number of breweries in each city:
  
![.](https://user-images.githubusercontent.com/86505407/146414036-79e2da3d-2360-4a01-8efd-43cf56efb9ff.png)
![.](https://user-images.githubusercontent.com/86505407/146414070-d65231cf-97ff-4ee2-a3cc-a8f6f2d8c8d0.png)
  
  -	Find the max in column c1 of result above:
  
![.](https://user-images.githubusercontent.com/86505407/146414097-899c4def-e295-408a-8df7-95d33bbff25f.png)
![.](https://user-images.githubusercontent.com/86505407/146414131-473c77e9-5182-4564-94df-2c683a976541.png)

  -	Find the city with the max that is 17 I got from the previous code. 
  
![.](https://user-images.githubusercontent.com/86505407/146414156-ab24a303-9b71-4c03-9052-2dc895736db3.png)

  -	The city with the most breweries is Portland:
  
![.](https://user-images.githubusercontent.com/86505407/146414185-713e6de2-e443-4284-a38e-fe33ba1b012b.png)

## 3. Determine the most brewed beer style
  -	Load the csv file into Spark:

![.](https://user-images.githubusercontent.com/86505407/146414294-757c17b3-f8c0-4c16-9a59-994c5c0a0997.png)

  - Remove the header. Define the column names, and put name for the table (beers). Finally, get the result which shows the number of each brewed beer style.

![.](https://user-images.githubusercontent.com/86505407/146414310-7771805e-d2eb-4b71-8499-b719ee639f31.png)
![.](https://user-images.githubusercontent.com/86505407/146414344-d5e3434e-2d4c-4469-96a7-caf71e0efdc3.png)
![.](https://user-images.githubusercontent.com/86505407/146414356-2c9ad6b8-12f8-4263-a0d5-f6d0aa46f974.png)

  - Get the most brewed beer style:
  
![.](https://user-images.githubusercontent.com/86505407/146414370-354ec9e6-edf6-4987-b0b6-b6d19dcb0593.png)
![.](https://user-images.githubusercontent.com/86505407/146414392-837e7907-aeb3-428e-8b8a-dce648a3b085.png)

  -	The most brewed beer style is American IPA:
  
![.](https://user-images.githubusercontent.com/86505407/146414402-b3a9af68-cfd5-421a-ac5d-df0771c87a95.png)


