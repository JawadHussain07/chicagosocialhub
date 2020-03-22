Chicago Social hub - Real Time Web-APP

 <img width="826" alt="Screen Shot 2020-03-22 at 5 46 28 PM" src="https://user-images.githubusercontent.com/57274566/77263018-13542600-6c65-11ea-922e-316191ce1703.png">

![Screen Shot 2020-03-22 at 5 30 07 PM](https://user-images.githubusercontent.com/57274566/77263028-26ff8c80-6c65-11ea-908e-faf3fb86c414.png)



Designed and implemented a web-based real-time application for Divvy bikers that will allow them to search and chart Yelp reviewed Chicago social places (restaurants, bars, coffee shops, etc) and plot real-time available docks in near-by Divvy docking stations on Chicago downtown area map.

#Requirements: 
1. Angular 7 or higher
2. Node.js/Express
3. D3.js
4. Google Maps (AGM)
5. PostgreSQL – to store Divvy stations real-time status
6. ElasticSearch – to store Yelp reviews for Chicago Businesses
7. ElasticSearch – to create and store Divvy real-time logs and store Divvy trips anonymized data

Node.js/Express to create the back-end application server
PostgreSQL and ElasticSearch for SQL and NoSQL databases to retrieve data
Use Google Maps to plot data for the Geospatial queries
Divvy bikers would like to search for places located on certain streets in Chicago downtown area and plot divvy nearest docking stations for a selected place on Google Map for Chicago downtown area.
Angular to create the front-end (client-side) application

The app-user shall be able to specify the search conditions using two fields to represent the pair (business-category, street-name),
The search results for top rated Yelp-reviewed places based on the specified filter by the app-user shall be displayed on a web-page
The app-user shall be provided with the capability to view the real- time status for the near-by Divvy docking stations of the selected place along with Google map for the current location, the selected place location, and the nearest 3 Divvy docking stations of the selected place.




