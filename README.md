A template for making a symfony development app with database and phpmyadmin

# TO DO
Create a folder named codebase in root

Run docker-compose up -d

Run docker exec -it <project-server-name> bash

Run composer self-update --2 (Update Composer)

Run composer create-project symfony/website-skeleton

If reaching a 404 check that the DocumentRoot under docker\server\apache\sites-enabled\site.conf is correct.
