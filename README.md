# Digital-Factory

-->This is the Restaurant Table reservation system. There are 4 types of tables (2,4,6,8) total 3 of each type. So in total restaurant has 12 tables. Reservation is made hourly.

-->It is made using Ruby 2.3.4 and Rails 4.2

-->I fyou have all the specs installed just ignore this, else use:

>bundle install

--> To migrate and initialize database use:

>"rake db:migrate" "rake db:setup"

-->This will setup database creating 12 tables(3 of each (2 seated, 4 seated, 6 seated, 8 seated tables)). The seeds.rb will create random reservations for tables.

You can not book more than 3 tables for 8 people each at a same time. If you have 6 people but all 6 seated tables are booked at a same time and if one 8 seated table is empty then you can book that. Booking can be done for 2 members on any table according to availability. But booking of 4 people can not be done for a table of 2 and so on.

--> Run the application on rails server using:

>rails server

Open Locathost:

http://localhost:3000/

-->I have used SQLite3 for this project. Although there is not much of UI but I have used Bootstrap for this.

Enjoy!!
