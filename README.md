My task was change status through Drag & Drop of a card.

I have done this using Laravel framework.

All requests handle through axios request and validation with custom form request & custom rules.

I've used Laravel Repository pattern for backend logic.

Return response data as an API response.

To run this project in your local machine please follow the below instructions......


1. Download the project from github link using clone or download zip.
2. Create a database in your xamp phpmyadmin (mysql).
3. Setup/create an env file (you can get help from env example file).
4. Setup created database in env file.
5. Then run " composer update --ignore-platform-req=ext-gd " command in terminal.
6. Then run " php artisan optimize:clear "
7. If require any files permission in your local machine please provide that permission such as bootstrap/cache folder, storage folder etc.
8. Then run " php artisan migrate --seed ". By doing this web guard for user and admin, role, permission and some dummy data will be created.
9. Then visit the site via login. In the first page you see the card list according to status. You can drag & drop here to update card status. Also you can see card details by clicking any card you'll see all card details there. Also you can add multiple attachment, multiple checklist, multiple task etc. All request are handle by axios request. So there will no page refreshing problem. Just module wise change will be happened.
