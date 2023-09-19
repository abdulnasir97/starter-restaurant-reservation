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
