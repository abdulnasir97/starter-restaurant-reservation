Periodic Tables - Restaurant Reservation <br>
<br>
Link <br>
<br>
Summary: <br>
This software application has been specifically tailored for upscale dining establishments, serving as a robust Restaurant Reservation Management tool. It is exclusively utilized by restaurant staff when patrons contact the restaurant to make a reservation. Within the application, users have the capability to generate, modify, review, and cancel reservations, in addition to overseeing the allocation of tables for seating arrangements. <br>
<br>
Installation
1. Fork and clone this repository.
1. Run `npm install` to install project dependencies. 
1. Run `npm run start` to start the project on your local machine.
<br>
Routes<br>

| Request              | Type | Route Description |
| :---------------- | :------: | ----: |
| GET        |   /reservations   |Returns all movies reservations in the database |
| GET          |   /reservations?date=YYYY-MM-DD   | Returns all reservations by a specific date |
| POST    |  /reservations   | Creates a new reservation that is added to the database |
| GET |  /reservations/:reservation_id   | Returns a specific reservation |
| PUT        |   /reservations/:reservation_id   | Updates the information for a specific reservation |
| PUT           |   /reservations/:reservation_id/status   | Updates the status of a specific reservation |
| GET   |  /tables   | Returns a list of all tables |
| POST |  /tables   | Creates a new table that is added to the database |
| PUT |  /tables/:table_id/seat   | Assigns a reservation to a table and updates the seated status |
| DELETE |  /tables/:table_id/seat   | Removes a reservation from a table |
<br>
<br>
Technology Used<br>
Frontend:<br>
Javascript, React, HTML, CSS, Bootstrap <br>
<br>
Backend: <br>
Node.js, Express, Knex, PostgreSQL

Photos<br>
<br>
![1](https://github.com/abdulnasir97/starter-restaurant-reservation/assets/120065583/74041429-c63b-4c97-8afd-d71b45dd59b4)


![2](https://github.com/abdulnasir97/starter-restaurant-reservation/assets/120065583/f5f942a5-62d3-4a84-9629-d067ec7e9b9d)


![3](https://github.com/abdulnasir97/starter-restaurant-reservation/assets/120065583/aed8a528-392e-4642-9538-e4b4f5caa85f)


![4](https://github.com/abdulnasir97/starter-restaurant-reservation/assets/120065583/6c9c303c-0073-49d2-aac3-494aea923aef)





