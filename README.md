Restaurant Reservation - Periodic Tables <br><br>
This repository comprises the server and client components for a Restaurant Reservation System. 
This system empowers restaurants to manage their tables by assigning names and capacities to them, keep track of reservations including date, time, first and last names, and party size, and facilitate seating arrangements for reservations on specific dates.<br><br>
The technologies used are HTML, CSS, JS, React, Express, PostgreSQL, and Knex.<br><br>
Live link: <br><br>
To install, please fork and clone the repository. Open the folder in your code editor and run "npm i" in the front-end directory. Run the command again in the back-end directory. Once completed, run "npm start" and the repo should launch locally on your machine.<br><br>
API Documentation:<br><br>

| Method              | Route | Desc |
| :---------------- | :------: | ----: |
| GET        |   /reservations   | List all reservations for current date |
| GET        |   /reservations   | date=YYYY-MM-DD	List all reservations for specified date |
| POST   |  /reservations   | Create new reservation |
| GET |  /reservations:reservation_id   |	List reservation by ID |
| PUT |  /reservations:reservation_id   | 	Update reservation |
| PUT |  /reservations/:reservation_id/status   | Update reservation status |
| GET |  /tables   | List all tables |
| POST |  /tables   | Create new table |
| PUT | /tables/:table_id/seat   | Assign a table to a reservation (changes reservation's status to "seated") |
| DELETE |  /tables/:table_id/seat   | Remove reservation from a table (changes reservation's status to "finished") |

