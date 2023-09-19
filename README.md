## Periodic Tables - Restaurant Reservation <br>
<br>
<br>
## Link <br>
<br>
## Summary <br>
This software application has been specifically tailored for upscale dining establishments, serving as a robust Restaurant Reservation Management tool. It is exclusively utilized by restaurant staff when patrons contact the restaurant to make a reservation. Within the application, users have the capability to generate, modify, review, and cancel reservations, in addition to overseeing the allocation of tables for seating arrangements. <br>
<br>
<br>

## Installation

1. Fork and clone this repository.
1. Run `npm install` to install project dependencies. 
1. Run `npm run start` to start your the project on your local machine.


Use the following routes for the API: The API allows for the following routes:

Method	Route	Description
GET	/reservations	List all reservations for current date
GET	/reservations?date=YYYY-MM-DD	List all reservations for specified date
POST	/reservations	Create new reservation
GET	/reservations/:reservation_id	List reservation by ID
PUT	/reservations/:reservation_id	Update reservation
PUT	/reservations/:reservation_id/status	Update reservation status
| GET | /tables | List all tables | POST | /tables | Create new table | PUT | /tables/:table_id/seat | Assign a table to a reservation (changes reservation's status to "seated") | DELETE | /tables/:table_id/seat | Remove reservation from a table (changes reservation's status to "finished")



