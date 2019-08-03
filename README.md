# CSCI-370-Project-4-Movie-GUI-and-Database
Group Project to create a GUI to display movies and cinemas along with filter functions.

Team Members:
Daniel Chang
Dennis Chang
Ka Leung
Jason Polanco
Final Report:
11/17/18
 
4.8.1 MAIN GUI
•	Movies and Cinemas Tab, on the top left, when selected will display a list of all the movies or cinemas
•	The Log In field on the top right requires “admin” password to gain administrative functions
•	Movie filter utilizes check boxes to filter movies
•	Cinema filter requires an “address” in x and y coordinates and a distance in the form of a radius
 
4.8.2 Movie GUI
•	The movie GUI displays all the movies and their ratings
•	There is a movie filter on the right side
o	It is a check box filter
o	The default (unchecked) filter displays all movies 
•	Double clicking on a movie will create a GUI with the movie, the cinemas that play it, the address of the cinema, and the showtimes

4.8.3 Cinema GUI
•	The cinema GUI displays all the cinemas and their address in x & y coordinates
•	There is a cinema filter on the right side
o	It consists of 3 text fields
o	x-coordinate, y-coordinate, and a Radius or Distance is necessary for the filter
•	Double clicking on a cinema will create a GUI with the cinema, the movies that are playing, the rating of the movie, and the showtimes

4.8.4 Administrator GUI
•	After logging into Admin Mode, the log in field is replaced by a log out button
•	To add a movie, a title is required, and a rating is selected from a pull-down menu
•	To add a showing, a movie, cinema, and show time is selected from their individual pull down menus
•	To add a cinema, a name, x-coordinate, y-coordinate, and ratings that are permitted by the cinema is required
•	To remove a movie or cinema
o	Select the proper Movies or Cinema tab
o	Select the movie or cinema by clicking on it once; it will be highlighted
o	Then click the “Removed Selected Item” button on the bottom
 
•	To remove a specific movie showtime
o	Double click on the movie (or the cinema of the targeted showtime)
o	Highlight the showtime and click “Remove”

11/11/18
•	Main GUI’s functions are in place
•	Text Fields/User input cannot be empty
•	Restrictions on showings of movies
o	No duplicates
o	Limit of three showings per cinema
•	Restrictions on cinemas
o	Cannot be at the same location
o	Cannot be of the same name 
o	On creation of the cinema, ratings are required
•	Database take care of a number of checks

11/04/18
•	The GUI displaying movies and cinemas is mostly complete.
o	Check boxes to filter by rating are functional but require testing.
o	Input text fields for finding cinemas in proximity are in place.
•	The admin login area is in place.
o	The password is admin.
o	Functionality to add and remove movies, cinemas, and listings is only accessible when logged in.
•	Database is connected.
o	Functions related to the database are under construction.


10/28/18
•	We have not fully discussed the details of the projects because of midterms. 



