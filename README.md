This is a CRUD operation frontend in Vuejs and backend in PHP/Laravel
1. clone the ripository : git clone https://https://github.com/ravipatel1989/laravel-vue-crud.git
2. Open the frontend folder and run below command to setup the frontend
 ```sh
  npm install
  ```
3. Open the Backend folder .env file in laravel and make database configuration
4. Open the Backend folder and run run below command to setup to install vendor folder with PHP dependencies
 ```sh
  composer install
  php artisan migrate
  ```
5. In frontend folder open src/composables/skills.js and configure the backend path
6. Now run the "php artisan serve" command in backend
7. And run the "npm run dev" command in frontend
