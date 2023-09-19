Periodic Tables - Restaurant Reservation <br>
<br>
Link <br>
<br>
Summary: <br>
This software application has been specifically tailored for upscale dining establishments, serving as a robust Restaurant Reservation Management tool. It is exclusively utilized by restaurant staff when patrons contact the restaurant to make a reservation. Within the application, users have the capability to generate, modify, review, and cancel reservations, in addition to overseeing the allocation of tables for seating arrangements. <br>
<br>

## Installation

1. Fork and clone this repository.
1. Run `npm install` to install project dependencies. 
1. Run `npm run start` to start your the project on your local machine.



Routes
Request Type	Route	Description
Get	/reservations	Returns all movies reservations in the database
Get	/reservations?date=YYYY-MM-DD	Returns all reservations by a specific date
Post	/reservations	Creates a new reservation that is added to the database
Get	/reservations/:reservation_id	Returns a specific reservation
Put	/reservations/:reservation_id	Updates the information for a specific reservation
Put	/reservations/:reservation_id/status	Updates the status of a specific reservation
Get	/tables	Returns a list of all tables
Post	/tables	Creates a new table that is added to the database
Put	/tables/:table_id/seat	Assigns a reservation to a table and updates the seated status
Delete	/tables/:table_id/seat	Removes a reservation from a table
