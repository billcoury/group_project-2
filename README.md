# Luxe Resort
An internal hotel management application using Node.js, Express, Sequelize, Handlebars.js and Passport.js

Working demo: https://arcane-tundra-64116.herokuapp.com

<br>

![welcome](https://user-images.githubusercontent.com/51132578/68827521-1dcb3700-0657-11ea-8af3-00c177510144.PNG)



### About
Allows guests to book a room, reserve a table at the hotel's restaurant and bar, and to select a service and book an appointment at the hotel spa
Allows managers to view room availability, current guests, checkin and checkout guests, restaurant table reservations, and spa reservations


### Guest View
Booking a room:
<br>
<img src="./public/assets/img/book_a_room.png" width="500px">

Once a guest books a room, they can login and view their room info and guest options:<br>
<img src="./public/assets/img/guest_login.png" width="500px">

Guests can reserve a table at the restaurant:<br>
<img src="./public/assets/img/restaurant_reservation.png" width="500px">

They can also select a service from the sap and book an appointment:<br>
<img src="./public/assets/img/spa_reservation.png" width="500px">


### Manager View
The manager view is hidden from the main view. The Manager Portal route is: `/admin`
<br>
Managers need to be signed up to login. Mangers can view room availability, check in and check out guests, and view current reservations at the restaurant.<br>
<img src="./public/assets/img/admin_login.png" width="500px"><br><br>
<br>
<img src="./public/assets/img/admin_rooms.png" width="500px">

You must create an admin login to use.

