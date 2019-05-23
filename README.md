# Project-2--Online-Movie-Listing

Online Movie Listing based on Genre. The database of movies fetched from The Movie Database (TMDb) using API call. This is single page web application.

Overview:
The whole project workflow has designed and implemented using open source PHP Model-View-Controller (MVC) architecture.
Technologies used – PHP, Ajax, Json, REST-API, HTML5, Bootstrap4, JavaScript, jQuery, phpMyAdmin- MySQL Database, Sever hosting (personal).

URL - http://velvetfoundation.in/amar/index.php 

Default login details –
Username/Email id: amarpethkar007@gmail.com
Password: admin

About Project:

Login validation:
Basic validation has been implemented during the login process such as input validation, input authentication, session validation, and decent user error message notification.

Register user/Sign Up:
Facilitate to register a new user to login an application.

Landing page/home page:
The landing page with basic responsive/optimized navbar facilitates user to navigate through the roadmap/application. The “on Click” string-based search option allows a user to search for a movie using a movie title. Search based output will render on the same page without reloading or navigating the home page. However, if the search result is null, it will simply display a blank screen with “Data not found” as an error message.
The default landing screen will show a movie-based Genre type “Action”. The see more button allows a user to check more details about the same movie, again without reloading and navigating the home page.
The button “Select Genre” allows a user to select a genre from the list of genres retrieved by API call from The Movie Database. When a user clicks on a genre label an event will trigger (JavaScript event) with all the respective list of movies and that genre label will be highlighted. 
Note: my observation, the API call is based on unique genre id provided by The Movie Database, however, some movies are listed with multiple genre ids’. 


