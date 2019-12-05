KIDS RIDE: TRANSPORTATION SERVICES YOU NEED
Safe and Reliable
At Kids Ride, our goal is to provide professional and safe transportation services for your kids.
We are proud to offer worry-free, quality service at a great price. 
Contact us today and get where you need to go.

This Project is a combination of a Python Flask Application that does webscraping, and stores the data in a MongoDB.
The /map route shows a Leaflet map with either:
1) A layer of all kids activites that shows as MarkerClusters (the number represents the quantity of kids activities in the specified region
2) A laser of 3 types of kids activities scraped from GoogleMaps including:
	a) Dance Classes
	b) Music Classes
	c) Sports Classes
The /data route shows the scraped data in JSON format
The /directions route shows a Mapbox Geolocator Jaascript Library to show directions from pickup point A to dropoff point B
Link to Heroku App (Optional) Include screenshots of app

Group Members
Pamela 
Shwetha 
Mark

Instructions for how to run the app:
Run the Google Dance,Music and Sports-Address Updated_MD urls.ipynb first which does the webscraping (takes some time)
	which automaticallyl uses pymongo to setup the kidsridedb MongoDB database and stores all the webscraped data into the activityData30 collection
Open up GitBash and type "python app.py" to run the Python Flask application
Copy the 127.0.0.1:5000/ to see the home route (i.e. the landing page). Other routes described above
You must have created an account for an API Key in Mapbox and put in config.js file.
Use the /map route to see all the Kids Activities in the map region.
When you click on a specific icon, it shows the Name of the company, address, and phone (if available).
Click on the Name and the browser will direct you to the company website.

Presentation: KidsRide
Link to presentation (or include the .ppt in your repo)