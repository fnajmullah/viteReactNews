#you should have php directory in enviroment path and also have node js installed
#Version Compability check
npm -v
#9.5.1
node --version
#v18.16.1
php -v
#PHP 8.2.6
php artisan --version
#Laravel Framework 10.28.0
npm view react version
#18.2.0

#enable the php extention sqlite3 and pdo_sqlite and change .env to sqlite as bellow
DB_CONNECTION=sqlite
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=laravel
# DB_USERNAME=root
# DB_PASSWORD=

php artisan migrate

#note: we need to fetch news from api and save to database and then get records from database and also we need to create another models news_favorite with user_id and news_id and also category_favorite with user_id and category_id, we have categories, and news master tables. and also favorite_authors with user_id and author_id.

we need to add compound indexes for title and description so that i can be easily searched
and display result by date,category and source api.

for mobile-responsive we need to give 3 parameters like 4 and 3 and 2 gride system.
api i used trtfrances we can use trtarabic and trtenglish different apis.

i did using laravel backend and react js front end.

i know how docker concept working with images and containers and internal and external ports and run and stop services. running app on docker gives more mobile-flexible

if this was laravel vite then i could have used one template for admin and one for users and one for visitors but i am starter in react js.

i know principles of DRY and keep it simple etc becuase i have studies master level.

The End.
