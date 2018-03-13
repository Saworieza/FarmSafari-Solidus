# README
...
Installation
clone this repo
run bundle install


then run rails db:create db:migrate
This creates and migrates your database tables assuming you already have postgres installed. if not
Install PostgreSQL with the following command:

sudo apt-get install postgresql postgresql-contrib

then create a user, for the purpose of this code base the user will have same name as our store:

sudo -u postgres createuser sprubyshop -s
sudo -u postgres psql

At the postgresql prompt, enter:

\password sprubyshop

Then enter your password (You’ll be required to enter it twice.)

You can now exit using CTRL + D.


default admin details
email : admin@example.com
password: test123


To change 
categories go to products > taxonomies > categories
brand go to products > taxonomies > brand

from there, you can CRUD them up