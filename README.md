# FreshGoogleMaps
World View Cleanup. Taking the initial code of WorldView and cleaning it up by using the most updated API's, and making it future proof by cleaing up existing code making it shorter, smarter, and powerful. The title "Fresh Google Maps" is temporary. All code here will be implemented in WorldView


* Progress report*

Around 300 lines of code has been deleted (or better yet refactored) regarding the UI system and the Google Map API system. 
It is now using the most updated of plays services (11.8.0) and using the most updated of Google services.
Also a XML UI system was created, rather than a hardcoded UI system.
Design is not yet cleaned up. A more "Google" look, and feel, is soon to come.

The purpose of creating a new project was for two reasons.
1) any changes I tried to made on the existing one was breaking the project.
2) fear of accidentally deleting the existing project.

* Future report*

The next step is taking on the Google Directions API and Google Places API. The aim is to do the same thing done with the Google Map API.
The goal is to subtract, or refactor, as many lines of code as possible to give WorldView a more sleek look.

Making the project look sleek and modern, basically as "googley" as possible, is soon to come. My initial concerns was the project code itself.

Plans to implement an optional Google sign in, so the Places API has the saved places that the user has under their google account, as well as their recent history.

Plans to implement a save feature regarding the camera system. This will be done by saving the latitude and longitude of the camera, and having the user name the camera.
