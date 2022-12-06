# README
Check in the .env files the correct name for the database.
Change the config/application.rb to rename your app

This repo uses docker compose to setup the required services.

Use docker compose up to build the images and spin the containers.

Since you are using docker you can use this template in a host that does not have ruby or rails installed.

Just remember that you need to get into a container to issue rails commands such as 'rails test' or 'rails generate model Task body:string' etc

After you clone the repo please make sure to change your origin remote not to pollute this repo.


