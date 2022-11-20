## 1. Add a folder named "html"
This folder is required for save the drupal files which will be downloaded at the 2nd step.

## 2. Get drupal files from drupal official docker image
```$ docker run --rm drupal tar -cC /var/www/html . | tar -xC ./html```

## 3. docker compose  
```$ docker compose up -d```

## 4. Install drupal
Access http://localhost:8086/ , setup you drupal site by following the instruction.