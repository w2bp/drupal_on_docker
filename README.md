## 1. Add a directory/folder named html


## 2. Get drupal files 
$ docker run --rm drupal tar -cC /var/www/html . | tar -xC ./html

## 3. docker compose  
$ docker compose up -d

## 4. Install drupal
Access http://localhost:8086/ , follow the instruction to setup you drupal site.