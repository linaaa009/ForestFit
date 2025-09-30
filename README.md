# ForestFit
Capstone Project

# About

ForestFit is a cardio tracking web application that helps users log and keep track of their cardio fitness activities.
Users can view their live location, click on the map to set a destination, and save trails with names.

The web application integrates the Google Maps API on the frontend and uses JSONBin for backend data storage.
It also estimates calories burned using MET values and awards badges for reaching cardio milestones.

# Technologies

Frontend: 
* HTML, CSS, JavaScript.
* Google Maps API (location, markers, routes).

Database: 
* JSONBin.io
* Stores trails, calories, miles, stats, and badges.

Backend:
* getJSONData.js - fetches JSON array.
* putJSONData.js - updates JSON array.
* helpers.js - manages core functions: Adding trails, parsing lat/lng, calculating calories, and badges.

# Team Contributions

Lina (PM + Support)
* Repository setup and management, team coordination, backend/frontend/db support, and system integration.

Jenna (Database + FE Support)
* Database management, JSONBin setup, frontend support, and documentation.

Sena (Frontend + Docs) 
* Google Maps integration, frontend HTML/JS, and documentation.

Ricardo (Backend) 
* JSONBin scripts (getJSONData, putJSONData), supporting Josh in extended features.

Josh (Backend + BE Support)
* Extended features: live coordinate tracking, distance & calorie calculation, and backend support.
