# GA WDI Project 4:  CARbon Footprints

This web app is intended to help users reflect on the impact of our everyday decisions on the environment.  As a first step, the app allows users to input start and end locations, and get a comparison of greenhouse gas emissions for driving vs taking public transportation.

Please visit:  https://emilyyutschmidtling.github.io/project4_frontend/#/
NOTE:  If his site is best viewed using Chrome.  Also, you will need to enable cross-origin resource sharing (CORS) on your browser.

Github Repo:

README:  https://github.com/emilyyutschmidtling/project4

Frontend:  https://github.com/emilyyutschmidtling/project4_frontend

Backend:  https://github.com/emilyyutschmidtling/project4_backend

My Trello Project Board:  https://trello.com/b/iifWcUwc/project-4


**_About the Building of this App_**

This app was built using MongoDB, Express, Angular, Node, Google Maps Directions API, ngMap, Bootstrap, HTML, and CSS.  User authentication is via JWT.

The app was originally envisioned with 3 models - User, Address, and Trip.  The auto-complete functionality available with Google Maps made the Address model unnecessary.

![alt text](https://github.com/emilyyutschmidtling/project4/blob/master/planning/ERD_v1.jpg)

Wireframes:

![alt text](https://github.com/emilyyutschmidtling/project4/blob/master/planning/attachments/FullSizeRender.jpg)

![alt text](https://github.com/emilyyutschmidtling/project4/blob/master/planning/attachments/FullSizeRender_1.jpg)

![alt text](https://github.com/emilyyutschmidtling/project4/blob/master/planning/attachments/FullSizeRender_2.jpg)

![alt text](https://github.com/emilyyutschmidtling/project4/blob/master/planning/attachments/FullSizeRender_3.jpg)

**_Known Bugs_**

- Currently, a user can log in and log out of the app.  However, all app content is currently accessible even without login.  Future development will include restricting access to certain features.

**_Future Upgrades_**

- Hiding the CO2 measurement statement until a start location and destination has been entered.

- Incorporate Google Maps' autocomplete functionality in the address input fields.

- Enable users to store trip data, including mileage and mode of transportation (e.g., driving, bus, train, walking, cycling).

- Enable users to pull a report of their trips and estimated carbon dioxide emissions for a given period of time.

- Provide additional information about typical carbon emissions and target levels as a way for users to evalutate how they're doing.

- Connect with a vehicle data API so users can get less generic estimates of their carbon emissions for driving based on their vehicle's make and model.
