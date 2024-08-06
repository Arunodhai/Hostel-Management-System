# README

Online Hostel Management System

* It is a web application through which students can register with their basic details and select the hostel room and mess of their choice by requesting the warden.
* Students can raise any kind of complaints regarding the hostel and mess. Warden can register with his basic details and upload the hostel and mess fee details.
* Warden can verify the students details and allocate the rooms and mess based on the availability.
* Warden can see the complaints made by the students and resolve them .
* Technology: Ruby on Rails, HTML, CSS

Screenshots of Project
<img width="1336" alt="1  homepage" src="https://github.com/user-attachments/assets/fdecc41c-26f8-4790-a56a-d0102a6145ec">



Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Try these lines in the console in the project folder:

gem install bundler
bundle
rake db:create && rake db:migrate
rails s

These commands will start Rails server at localhost:3000. This project requires DB to be installed. (DB type depends on Gemfile content). Also you should check if config/database.yml file is present.
