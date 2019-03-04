Comp 20
Assignment 2: The Private Car Service
03_03_2019
William Varteresian

Files:

index.html: A web page that displays a Google Maps map with a marker
            on the user's location. Additional markers display the
            positions of vehicles and/or passengers based on data
            retrieved from the JSON API provided.

style.css: A style sheet for index.html. Only includes basic rules
           for displaying the map, as the page has no other elements.
           An info window on the user's location displays the distance
           to the nearest vehicle/passenger and weinermobile (the 
           course site says that a weinermobile can be a passenger
           or vehicle, so if the weinermobile is the closest marker,
           it will be listed as the closest passenger/vehicle as well).
           Distance is given in miles rounded to five decimal places
           for the sake of readability.

car.png: An icon for vehicles. Taken from the course website.

passenger.png: An icon for passengers. Found via image search.

weinermobile.png: An icon for the weinermobile. Taken from course website.

pin.png: An icon for the user. Taken from https://icons8.com/icons/set/maps.

Acknowledgments: I referenced https://stackoverflow.com/questions/
                 14560999/using-the-haversine-formula-in-javascript
                 for a Javascript implementation of the Haversine
                 Formula.
                 I referenced W3schools for documentation on typeof
                 and toFixed().
                 I referenced https://developers.google.com/maps/documentation/
                 javascript/tutorial for help using the Google Maps
                 API.

Issues: Initially had difficulty iterating through the JSON data.
        After asking on Piazza and experimenting with the console,
        I discovered that the JSON data only contained an array
        and was not an array itself. I therefore added code to
        keep only the actual array and iterate through that, which
        solved the issue.
        I then encountered a bug where icons still appeared not to
        display, but I discovered that this was only a typo in one
        of my if statements causing the icons for those markers
        to be undefined (apparently undefined icons do not cause
        errors when running the code).
        When I set about ensuring that the site would work with
        passenger data as well as vehicle data, I was at first
        unsure how to check, but then I found documentation for
        typeof, which allowed me to check the existence of a
        variable.