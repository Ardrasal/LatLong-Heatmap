import IPv4 file
Parse data from IPv4 file
    extract only latitude and longitude columns
        (use pandas or csv modules)

Define a REST endpoint that returns a list of coordinates within a geographic coordinate bounding box (may need to fine tune resolution of data to improve performance) 
	research REST endpoint
	write code to return list of coordinates
		use Leaflet and Leaflet.heat libraries and others to draw geographical data on a map in the browser

	bound in geo bounding box such as MapBox (free tier)
	Opt: fine tune data

Use REST endpoint in a single-page JavaScript application to display data to user
	code REST endpoint in JS

Deploy to Heroku

BONUS

Write tests to verify behavior
	review how to write tests (assert function)
Fast front-end performance
REST endpoints should be able to be recalculated
