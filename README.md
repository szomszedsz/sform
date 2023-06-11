# sform

1. Run docker containers with
  `$ docker-compose up -d`
2. Enter to the PHP container 
  `$ docker exec -it sform_php_1 bash`
3. Enter to the project folder
  `$ cd ./html/sform`
4. Run composer install
  `$ composer install`
5. Create database and run migration 
  `$ php bin/console help doctrine:database:create`  
  `$ php bin/console doctrine:migrations:migrate`  
6. Run npm install
  `$ npm install`
7. Build in dev mode
  `$ npm run dev --watch`   
8. Open in browser
   `localhost:8080`
